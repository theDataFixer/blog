---
title: "DE Zoomcamp | Semana 1"
summary: Tutorial para semana 1 de Data Engineering Zoomcamp
tags: ["zoomcamp", "python", "docker", "postgresql"]
draft: false
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

Este código es como dar instrucciones para configurar un lugar donde guardar información (como un gran armario). El primer conjunto de instrucciones se refiere a la base de datos, indicando cómo configurarla, dónde guardar los datos y cómo acceder a ella. El segundo conjunto de instrucciones se refiere a una herramienta llamada pgAdmin, que facilita la gestión de la base de datos de PostgreSQL, indicando cómo configurarla y cómo acceder a ella.

El primer servicio, llamado "pgdatabase", utiliza la imagen de Docker "postgres:13" para crear una base de datos PostgreSQL. Se define un nombre de usuario y contraseña para la base de datos, y se especifica el nombre de la base de datos "ny_taxi". Para agregar, se establece un volumen para almacenar los datos de la base de datos en el directorio local "./data/ny_taxi_postgres_data". El servicio expone el puerto 5432 para que las aplicaciones se puedan conectar a la base de datos.

El segundo servicio, llamado "pgadmin", utiliza la imagen de Docker "dpage/pgadmin4" para ejecutar una interfaz de administración para la base de datos PostgreSQL. Se establece un correo electrónico y contraseña predeterminados para acceder a pgAdmin, y se define un volumen para almacenar los datos de pgAdmin. El servicio expone el puerto 8080 para acceder a la interfaz de usuario de pgAdmin.

IMAGEN

Al momento de correr `docker-compose up` deberías de tener dos contenedores, uno con PostgreSQL y otro con pgAdmin, y como los creamos con docker-compose ya están configurados en la misma red por lo que se pueden comunicar sin problema.

Por cierto, el tener `${POSTGRES_USER} o ${POSTGRES_PASSWORD}` con esta sintaxis es porque es una buena práctica de seguridad tener tus credenciales de forma secreta. Además, otros beneficios de usarlo de esta manera son la mejora de portabilidad entre entornos y poder parametrizar tus credenciales por si quieres que sea más flexible y reutilizable para diferentes entornos.

### Ejecutar servicios de Docker

Como lo mencioné anteriormente, `docker-compose up` es la manera para ejecutar una vez que ya cuentes con tu YAML file. Ahora, lo que sigue es abrir tu explorador de preferencia e ir a `localhost:8080` y usar las credenciales definidas en tu archivo `.env` si es que decidiste usar variables de forma secreta como lo tengo en mi YAML.

GIF LOGEANDOTE A LOCALHOST, LUEGO AGREGAR SERVER Y LA CONEXION Y TODO

Si en dado caso 


## Python script


## Ingestión de datos de Nueva York en una base de datos PostgreSQL




