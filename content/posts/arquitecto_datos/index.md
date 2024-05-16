---
title: "¿Por qué un Arquitecto de Datos?"
date: 2024-05-07
summary: 
tags: ["intro", "data architect", "arquitecto de datos", "concepto"]
draft: true
---

### Introducción
Es muy importante que los datos sean accesibles y reutilizables para la sociedad y para la industria. Hoy por hoy es crucial que los datos tengan la capacidad de que sean accesibles y reutilizables no solo para el sector laboral, sino también uno como usuario. 

Crear o generar, guardar, ingestar, transformar, procesar y visualizar los datos es una tarea que requiere tiempo y esfuerzo. Además, mantener la seguridad, ejecutar la administración, realizar la operación, detallar la orquestación, conservar las buenas prácticas de la ingeniería de software, y definir la estrategia de la arquitectura de datos son aspectos sumamente críticos para el ecosistema de datos.

De todos estos puntos que mencioné, quiero enfocarme en lo que es la arquitectura de datos, específicamente el rol de un Arquitecto de Datos. Hay varios roles de datos en el mundo laboral que en ocasiones se vuelve abrumador, o incluso se vuelve un poco difícil distinguir entre un rol y otro.

Si estás familiarizado con los roles de datos o más bien si tienes experiencia trabajando con datos, estarás de acuerdo en que en ocasiones un Data Analyst hace trabajos de Data Engineer, o viceversa. Asimismo un Data Scientist puede estar trabajando para una empresa sólo haciendo queries en SQL y Dashboards. Puedo seguir con un sin fin de ejemplos, pero para no entrar mucho a detalle, esto prácticamente pasa por la madurez en datos que se encuentra la empresa, organización o proyecto.

### ¿Qué es un Arquitecto de datos?
Si buscas en internet, en libros, o consultas a una persona con experiencia en datos, puedes toparte con diferentes definiciones de lo que es un arquitecto de datos.

Si laboras en una empresa donde la madurez de los datos son nivel 0 o nivel bajo, también te puedes topar con variaciones de definiciones de un arquitecto de datos.

De acuerdo al libro _Deciphering Data Architectures_ por parte de _James Serra_, un arquitecto de datos:
> Es el que diseña la estructura de alto nivel de la arquitectura de datos (MDW, data fabric o data lakehouse) y decide qué tecnologías y políticas de gobernanza de datos debe de utilizar el proyecto.

De acuerdo a _TOGAF_:
> Es el que se encarga de describir la estructura e interacción de los principales tipos y fuentes de datos, activos de datos lógicos, activos de datos físicos y recursos de gestión de datos de la empresa.

De acuerdo a _DAMA DMBOK_:
> Es el que identifica las necesidades de datos de la empresa (independientemente de la estructura) y diseña y mantiene los planos maestros para guiar la integración de datos, controlar los activos de datos y alinear las inversiones en datos con la estrategia empresarial.

De acuerdo al libro _Fundamentals of Data Engineering_ escrito por _Joe Ries & Matt Housley_:
> Es el que funciona como un nivel de abstracción de los ingenieros de datos. Los arquitectos de datos diseñan el modelo para la gestión de datos organizacionales, trazando procesos y la arquitectura y los sistemas de datos en general. También sirven como puente entre los aspectos técnicos y no técnicos de una organización.

También ellos mismos definen:
> Es el que diseña los sistemas para respaldar las necesidades de datos cambiantes de una empresa, logrado mediante decisiones flexibles y reversibles alcanzadas a través de una evaluación cuidadosa de las compensaciones.

&nbsp;

Ahora, ¿con cuál definición irte?

Si quisiera resumir todos estas definiciones, podría resumirlo de esta manera:

* Diseñan la estructura general de cómo se almacenan, organizan y utilizan los datos.
* Deciden qué tecnologías se usarán para gestionar los datos.
* Crean las reglas y políticas para garantizar que los datos sean de alta calidad y confiables.
* Se aseguran de que los sistemas de datos sean flexibles y puedan adaptarse a las necesidades cambiantes de la empresa.

Son como los ingenieros de los datos (prácticamente funcionan como un nivel de abstracción), que diseñan los sistemas necesarios de todo el ciclo de vida de datos para que las empresas puedan aprovechar al máximo sus datos.

Un arquitecto de datos analiza los pros y contras, diseña con agilidad, y agregar valor a negocio.

### ¿Y qué NO es un Arquitecto de Datos?
Todo lo que involucra tanto estrategia como táctica, se puede considerar un Arquitecto de datos.

La estrategia involucra las preguntas qué, por qué y cuándo, mientras que la táctica involucra el cómo. Supongamos que alguien de tu empresa llega contigo y te dice que necesitan integrar información de varias fuentes porque quieren explotar los datos. Tú como arquitecto de datos tienes que empezar a investigar qué exactamente es con lo que están tratando, tienes que saber el por qué desean esa integración y esa explotación de datos, y tienes que saber cuándo necesitan este tipo de solución.

No es que sean las únicas preguntas que se hagan para ser un arquitecto, pero a lo que quiero llegar es que NO es correcto decir _"Tenemos X, Y, y Z herramientas para poder hacer la extracción y hacer analítica de datos"_ porque eso trae consecuencias negativas del diseño de solución.

&nbsp;

#### ¿Pero qué no hace esto un Ingeniero de Datos?
Es cierto que un ingeniero de datos puede hacer todo esto, pero como se mencionó anteriormente, los arquitectos de datos funcionan como un nivel de abstracción. Es más, no soy experto en edificios ni casas ni departamentos, pero sé que un ingeniero civíl podría hacer el trabajo de una arquitecto. ¿Entonces por qué existen los arquitectos? Porque ellos se enfocan en la estrategia y táctica, mientras que los ingenieros convierten lo diseñado en realidad.

Un Ingeniero de datos es el responsable de crear, probar y mantener la arquitectura de datos. Escriben los cripts correspondientes para extraer, cargar y transformar de una o varias fuentes y lo convierten en una solución de datos, y trabajan muy directamente con un arquitecto de datos para implementar la arquitectura diseñada.

Si bien un ingeniero puede hacer trabajo de arquitectura, es importante establecer los límites, objetivos, tareas y alcance de lo que puede llegar a hacer. Lo digo porque muy probablemente te haz encontrado puestos de trabajo o bien empleados en donde laboras que un ingeniero hace más tareas de lo que debería. 

Es más, dime de todos estos roles que existen cuáles te ha tocado que terminan "combinando"?
* Data Analyst
* Data Scientist
* Business Analyst
* Data Engineer
* Database Administrator
* Data Steward
* Data Architect
* Data Governance Manager
* Data Quality Manager
* Project Manager/Scrum Master
* DevOps Engineer
* Product Owner/Manager

Lo que te puedo decir es que es "normal" que pase esto, pero es crucial tener presente de que existe la posibilidad de que un rol de datos sea varios roles de datos.

### Su papel en el ciclo de vida de datos
Hay que tener claro que es muy diferente el ciclo de vida de datos contra el ciclo de la ingenieria de datos. Primero, vamos con el ciclo de ingenieria de datos:

* Generación
* Almacenamiento
* Ingestión
* Transformación
* Visualización o entrega

Los datos tienen valor en cada fase de este ciclo, y los datos que no son consumidos o que ni se consultan pueden ser un riesgo para cualquier companía. Muchas empresas, por el simple hecho de querer hacer proyectos ambiciosos en esta era del big data, terminaron (y siguen haciendo) recolectando datos masivos, y al final no se utilizaron de forma correcta.

Los proyectos deben de tener intención en todo el ciclo, tanto de ingenieria como del dato. Un ingeniero de datos se va a encargar de extraer la información en tiempo y forma, de seguir los protocolos correctos de seguridad y de integarción, y lo que quieras ponerle.

¿Pero el trabajo de un ingeniero termina ahí?

Es a lo que voy. Un arquitecto de datos tiene que evaluar, diseñar, organizar, y ver el valor de las fases del proyecto.

CICLO DE VIDA DE DATOS

data creation
data storage
data backup
data analysis
data disposal

data identification
data mapping
data cleansing
data transformation
data validation
data archiving
data deletion


### Desafíos comúnes en el mundo de los datos

### Conclusión

### TL;DR

