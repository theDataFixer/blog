---
title: "DE Zoomcamp | Semana 1"
summary: Tutorial para semana 1 de Data Engineering Zoomcamp
tags: ["zoomcamp", "python", "docker", "postgresql"]
draft: true
---

*Post totalmente inspirado por este artículo: https://www.jonahboliver.com/blog/de-zc-w1*

## Introducción
Este zoomcamp es un curso totalmente gratuito enfocado en ingeniería de datos y lo puedes tomar al momento que quieras, cuando tengas disponibilidad y a tu propio ritmo. Dentro del curso existen varios modulos:

* Contenerización e infraestructura como código (IaC)
* Orquestación
* Ingestión de datos
* Data Warehouse
* Analytics Engineering
* Procesamiento por lotes (Batch)
* Transmisión en tiempo real (Streaming)
* Crear un proyecto

Si quieres saber más información al respecto, puedes entrar al siguiente enlace dando [click aquí](https://github.com/DataTalksClub/data-engineering-zoomcamp)  

El objetivo de este artículo es crear un ambiente en el que podamos ingestar y guardar información utilizando docker, python y postgresql.

## Requisitos
Antes de empezar, necesitas tener los siguientes archivos y herramientas:

* [Python](https://www.python.org/downloads/)
* [Docker](https://docs.docker.com/engine/install/)
* New York Taxi Data - [green_tripdata_2019-09.csv.gz](https://github.com/DataTalksClub/nyc-tlc-data/releases/download/green/green_tripdata_2019-09.csv.gz)

**Nota:** en el enlace de github del zoomcamp hay también videos y tutoriales paso a paso. Además, cabe aclarar que estoy utilizando Linux (openSUSE) por lo que si es que utilizas Windows te recomiendo ir al repositorio del curso. 

## Configuración de Docker
En los videos del zoomcamp lo que hacen es configurar manualmente cada contenedor de Docker con varios comandos en la terminal y sinceramente es algo tedioso y complicado de gestionar. Afortunadamente existe algo dentro de docker que se llama docker-compose, donde este tiene varios beneficios:

- Simplifica la gestión de múltiples contenedores.
- Permite definir la configuración de contenedores en un archivo YAML.
- Facilita el inicio, detención y supervisión de múltiples contenedores con un solo comando.
- Simplifica la gestión de la red entre los contenedores, ya que docker-compose gestiona automáticamente la conectivdad entre ellos.

El contenido de la configuración del archivo YAML debe de ser parecido al siguiente:
```yaml
services:
    pgdatabase:
        image: postgres:13
        environment:
            - POSTGRES_USER=${POSTGRES_USER}
            - POSTGRES_PASSWORD=${POSTGRES_PASSWORD}
            - POSTGRES_DB=ny_taxi
        volumes:
            - "./data/ny_taxi_postgres_data:/var/lib/postgresql/data:rw"
        ports:
            - "5432:5432"
    pgadmin:
        image: dpage/pgadmin4
        environment:
            - PGADMIN_DEFAULT_EMAIL=${PGADMIN_DEFAULT_EMAIL}
            - PGADMIN_DEFAULT_PASSWORD=${PGADMIN_DEFAULT_PASSWORD}
        volumes:
            - "./data/pgadmin_data:/var/lib/pgadmin:rw"
        ports:
            - "8080:80"
```
### ¿Qué pasó aquí?

MODIFICAR ESTO PONERLO CON PUNTOS COMO LO DE AL FINAL

Este código es como dar instrucciones para configurar un lugar donde guardar información (como un gran armario). El primer conjunto de instrucciones se refiere a la base de datos, indicando cómo configurarla, dónde guardar los datos y cómo acceder a ella. El segundo conjunto de instrucciones se refiere a una herramienta llamada pgAdmin, que facilita la gestión de la base de datos de PostgreSQL, indicando cómo configurarla y cómo acceder a ella.

El primer servicio, llamado "pgdatabase", utiliza la imagen de Docker "postgres:13" para crear una base de datos PostgreSQL. Se define un nombre de usuario y contraseña para la base de datos, y se especifica el nombre de la base de datos "ny_taxi". Para agregar, se establece un volumen para almacenar los datos de la base de datos en el directorio local "./data/ny_taxi_postgres_data". El servicio expone el puerto 5432 para que las aplicaciones se puedan conectar a la base de datos.

El segundo servicio, llamado "pgadmin", utiliza la imagen de Docker "dpage/pgadmin4" para ejecutar una interfaz de administración para la base de datos PostgreSQL. Se establece un correo electrónico y contraseña predeterminados para acceder a pgAdmin, y se define un volumen para almacenar los datos de pgAdmin. El servicio expone el puerto 8080 para acceder a la interfaz de usuario de pgAdmin.

IMAGEN

Al momento de correr `docker-compose up` deberías de tener dos contenedores, uno con PostgreSQL y otro con pgAdmin, y como los creamos con docker-compose ya están configurados en la misma red por lo que se pueden comunicar sin problema.

Por cierto, el tener `${POSTGRES_USER} o ${POSTGRES_PASSWORD}` con esta sintaxis es porque es una buena práctica de seguridad tener tus credenciales de forma secreta. Además, otros beneficios de usarlo de esta manera son la mejora de portabilidad entre entornos y poder parametrizar tus credenciales por si quieres que sea más flexible y reutilizable para diferentes entornos.

### Ejecutar servicios de Docker
Como lo mencioné anteriormente, `docker-compose up` es la manera para ejecutar una vez que ya cuentes con tu YAML file. Ahora, lo que sigue es abrir tu explorador de preferencia e ir a `localhost:8080` y usar las credenciales definidas en tu archivo `.env` si es que decidiste usar variables de forma secreta como lo tengo en mi YAML.

GIF LOGEANDOTE A LOCALHOST, LUEGO AGREGAR SERVER Y LA CONEXION Y TODO

## Python script
En el curso de Data Engineering Zoomcamp hay un código de Python que funciona y que el mismo creador menciona que probablemente exista otra forma más óptima de hacerla. Ahora bien, como lo digo al inicio de este artículo que este post es totalmente inspirado por un [tutorial ya creado pero en inglés](https://www.jonahboliver.com/blog/de-zc-w1), ahí se muestra otro código de python que a mi punto de vista es mucho más elegante y sobre todo sencillo de entender:

```python
import argparse
import pandas as pd
import os
import pyarrow.parquet as pq
from sqlalchemy import create_engine
from time import time, sleep

def main(params):
    user = params.user
    password = params.password
    host = params.host
    port = params.port
    db = params.db
    table = params.table
    url = params.url
    file_name = url.split('/')[-1]
    
    # download csv from URL using wget
    os.system(f'wget {url} -O {file_name}')

    # postgresql://root:root@localhost:5432/ny_taxi
    engine = create_engine(f'postgresql://{user}:{password}@{host}:{port}/{db}')

    if file_name.endswith('.parquet'):
        pf = pq.read_table(file_name)
        data = pf.to_pandas()
    elif file_name.endswith('.csv') or file_name.endswith('.csv.gz'):
        data = pd.read_csv(file_name, compression='infer')
    else:
        print(f'Unsupported file format: {file_name}')
        return

    df_len = data.shape[0]

    # Data Definition Language (DDL): defines the schema
    print(pd.io.sql.get_schema(data, name='yellow_taxi_data', con=engine))

    chunk_size = 100000
    chunk_count = 0
    chunks = [data.iloc[i:i+chunk_size] for i in range(0, len(data), chunk_size)]

    for df in chunks:
        chunk_count += chunk_size
        if chunk_count >= df_len:
            completion = 100
        else:
            completion = (chunk_count/df_len) * 100
        t_start = time()
        df.to_sql(name=table, con=engine, if_exists='append')
        t_end = time()
        print(f'inserted another chunk, took {(t_end-t_start):.3f} seconds. {completion:.3f} % Complete.') 

if __name__ == '__main__':

    parser = argparse.ArgumentParser(description='Ingest CSV data to Postgres')

    #password, host, port, database name, table name, url of the csv

    parser.add_argument('--user', help='username')
    parser.add_argument('--password', help='password')
    parser.add_argument('--host', help='hostname')
    parser.add_argument('--port', help='port number')
    parser.add_argument('--db', help='database name')
    parser.add_argument('--table', help='name of the tabler')
    parser.add_argument('--url', help='url of the csv')                   

    args = parser.parse_args()

    main(args)
```

Este código automatiza el proceso de descargar un archivo CSV desde una URL dada, convertirlo a un formato adecuado para almacenar datos en una base de datos PostgreSQL, e insertar los datos de manera eficiente en una tabla específica dentro de la base de datos.

En términos simples, imagina que tienes un archivo CSV grande que contiene información que deseas almacenar en una base datos. Este script te ayuda a:
1. Descargar el archivo de internet
2. Conectarse a su base de datos PostgreSQL
3. Leer los datos del archivo en un formato adecuado para la base de datos
4. Dividir los datos en fragmentos más pequeños para una inserción más rápida, y si se produce un error durante la inserción, solo afecta ese fragmento, no todo el dataset.
5. El script te muestra el progreso de la inserción de datos al incluir el tamaño del fragmento actual, el tiempo de ejecución y el porcentaje de finalización.

## Ingestión de datos de Nueva York en una base de datos PostgreSQL
El siguiente paso es crear el `Dockerfile` una vez creado el script de ingestión.

```docker
FROM python:3.11.7

RUN apt-get install wget
RUN pip install pandas sqlalchemy psycopg2 pyarrow wheel

WORKDIR /app
COPY ingest_data.py ingest_data.py

ENTRYPOINT ["python", "ingest_data.py"]
```
Si usaramos una analogía para dimensionar lo que hace este `Dockerfile`, podríamos imaginar que estás queriendo cocinar y que necesitas unos ingredientes específicos y sobre todo herramientas especiales.

Haz de cuenta que este archivo es como una lista de compras y sobre todo instrucciones que te ayudan a comprar los ingredientes (Es decir instalar las librerias de Python), preparar las herramientas (Es decir configurar el directorio y copiar el script), y por último cocinar la receta (Es decir, ejecutar el script).

Si todavía tienes dudas, vamos desglosando línea por línea para que te quede más claro:

1. `FROM python:3.11.7`
* Esta línea indica que la imgane se basa en la imagen oficial de Python 3.11.7, por lo que contendrá todas las herramientas y bibliotecas estándar de esta versión.

2. `RUN apt-get install wget`
* Esta línea instala el paquete wget dentro de la imagen, donde `wget` sirve para descargar archivos desde internet. Si te vas al script de ingestión de python puedes ver que se usa `wget` para descargar el archivo CSV.

3. `RUN pip install pandas sqlalchemy psycopg2 pyarrow wheel`
* Esta línea instala las librerías de Python necesarias para leer archivos CSV, conectarse a la base de datos PostgreSQL, procesar datos, etc.

4. `WORKDIR /app`
* Esta línea establece el directorio de trabajo dentro de la imagen como /app. Por ende, cualquier comando que se efectue dentro del contenedor se ejecutará en este directorio.

5. `COPY ingest_data.py ingest_data.py`
* Esta línea copia el archivo `ingest_data.py` desde la máquina local al directorio /app dentro de la imagen.

6. `ENTRYPOINT ["python", "ingest_data.py"]`
* Esta línea determina el comando que se ejecutará cuando se inicia el contenedor. En este caso, el comando `python ingest_data.py` ejecutará el script `ingest_data.py` dentro del contenedor.


