---
title: "¿Por qué ser un Arquitecto de Datos?"
date: 2024-05-27
summary: 
tags: ["intro", "data architect", "pilot", "arquitectura de datos", "piloto"]
draft: false
---

Es crucial que los datos sean accesibles y reutilizables para la sociedad y la industria. Hoy en día, es esencial que los datos puedan ser accedidos y reutilizados no solo por profesionales, sino también por usuarios regulares, como aquellos que utilizan las redes sociales e intentan descargar su propia información.

Tareas como crear, guardar, ingerir, transformar, procesar y visualizar datos requieren tiempo y esfuerzo. Además, mantener la seguridad, ejecutar la administración, realizar operaciones, detallar la orquestación, preservar buenas prácticas de ingeniería de software y definir la estrategia de arquitectura de datos son aspectos críticos del ecosistema de datos.

De todos estos puntos, quiero centrarme en la arquitectura de datos. Hay varios roles de datos en la fuerza laboral que a veces pueden resultar abrumadores o difíciles de distinguir entre sí.

Si tienes experiencia trabajando con datos, es posible que hayas notado que a veces un Analista de Datos realiza tareas típicamente realizadas por un Ingeniero de Datos, o viceversa. De manera similar, un Científico de Datos puede estar enfocado únicamente en consultas SQL y paneles para una empresa. Esta variación en roles a menudo depende de la madurez de los datos de la empresa, organización o proyecto.

&nbsp;

### ¿Qué es un Arquitecto de Datos?

Si buscas en internet, en libros, o consultas a alguien con experiencia en datos, es posible que te encuentres con diferentes definiciones de lo que es un arquitecto de datos.

Según el libro _"Deciphering Data Architectures"_ de James Serra:
> Ellos son los que diseñan la estructura de alto nivel de la arquitectura de datos (MDW, data fabric o data lakehouse) y deciden qué tecnologías y políticas de gobernanza de datos debe usar el proyecto.

Según _TOGAF_:
> Son responsables de describir la estructura e interacción de los principales tipos y fuentes de datos, activos de datos lógicos, activos de datos físicos y recursos de gestión de datos de la empresa.

Según _DAMA DMBOK_:
> Son quienes identifican las necesidades de datos de la empresa (independientemente de la estructura) y diseñan y mantienen planes maestros para guiar la integración de datos, controlar los activos de datos y alinear las inversiones de datos con la estrategia empresarial.

Según el libro _"Fundamentals of Data Engineering"_ escrito por Joe Ries & Matt Housley:
> Funcionan como un nivel de abstracción de los ingenieros de datos. Los arquitectos de datos diseñan el modelo para la gestión de datos organizativos, mapeando procesos y arquitectura general de datos y sistemas. También sirven como puente entre los aspectos técnicos y no técnicos de una organización.

También tienen otra definición:
> Es quien diseña sistemas para apoyar las cambiantes necesidades de datos de una empresa, logradas a través de decisiones flexibles y reversibles alcanzadas mediante una cuidadosa evaluación de compensaciones.

&nbsp;

¿Ahora, cuál definición debería ser elegida?

Resumiendo todas estas definiciones, se podría encapsular de la siguiente manera:
- Diseñan la estructura general de cómo se almacenan, organizan y utilizan los datos.
- Deciden qué tecnologías se utilizarán para gestionar los datos.
- Crean reglas y políticas para garantizar que los datos sean de alta calidad y confiables.
- Aseguran que los sistemas de datos sean flexibles y puedan adaptarse a las necesidades cambiantes de la empresa.

Funcionan como diseñadores, desarrollando sistemas necesarios para todo el ciclo de vida de los datos para que las empresas puedan maximizar y potenciar el valor de sus datos.

Un arquitecto de datos analiza los pros y los contras, diseña con agilidad y agrega valor al negocio.

&nbsp;

### ¿Y qué NO es un Arquitecto de Datos?

Todo lo relacionado tanto con la estrategia y con la táctica se puede considerar como parte de Arquitectura de Datos.

La estrategia implica las preguntas de **qué, por qué y cuándo**, mientras que las tácticas involucran el **cómo**. Digamos que alguien de tu empresa se acerca a ti y expresa la necesidad de integrar información de diversas fuentes para utilizar los datos. Como arquitecto de datos, debes comenzar investigando con qué exactamente están lidiando, comprendiendo por qué desean esa integración y utilización de datos, y determinando cuándo necesitan este tipo de solución.

Estas no son las únicas preguntas que hace un arquitecto de datos, pero el punto que quiero enfatizar es que no es preciso simplemente afirmar, _"Tenemos herramientas X, Y y Z para extraer y analizar datos,"_ ya que esto puede tener consecuencias negativas en el diseño de la solución.

Además de la estrategia y la táctica, los arquitectos de datos deben considerar tres aspectos principales al desarrollar una nueva arquitectura de datos:
* Completitud
* Precisión
* Consistencia

A menudo, los interesados pueden no tener una comprensión clara de con qué están lidiando, por lo que es esencial estar presente al definir esos requisitos funcionales. En mi opinión, es un arte; a veces, los interesados solo pueden saber que necesitan integrar y utilizar datos, lo cual puede ser en realidad un buen punto de partida.

#### ¿Pero estas tareas generalmente son realizadas por un Ingeniero de Datos, correcto?

Es cierto que un ingeniero de datos es capaz de manejar todas estas tareas, pero como se mencionó anteriormente, los arquitectos de datos operan a un nivel más alto de abstracción. Además, aunque no soy un experto en construcción, entiendo que un ingeniero civil podría cumplir con las funciones de un arquitecto. Entonces, ¿por qué existen los arquitectos? Porque los arquitectos se centran en la estrategia y la táctica, mientras que los ingenieros dan vida a los diseños.

&nbsp;

Un ingeniero de datos tiene la tarea de crear, probar y mantener la arquitectura de datos. Escriben scripts para extraer, cargar y transformar datos de diversas fuentes para crear una solución de datos, colaborando estrechamente con un arquitecto de datos para implementar la arquitectura planificada.

Si bien un ingeniero puede realizar trabajo arquitectónico, es importante definir sus limitaciones, objetivos, tareas y alcance. Esto es crucial porque es posible que hayas encontrado situaciones en tu lugar de trabajo donde un ingeniero asume más responsabilidades de las necesarias.

Ahora, de todos estos roles, ¿has observado alguna posición en la que se hayan combinado las tareas?
- Data Analyst
- Data Scientist
- Business Analyst
- Data Engineer
- Database Administrator
- Data Steward
- Data Architect
- Data Governance Manager
- Data Quality Manager
- Project Manager/Scrum Master
- DevOps Engineer
- Product Owner/Manager

No es raro que los roles se combinen, pero es esencial recordar que un rol de datos puede abarcar múltiples responsabilidades.


### Su rol en el ciclo de vida de datos de ingeniería

Comprender el ciclo de vida de la ingeniería de datos es importante debido a su impacto en cada etapa de un proyecto, brindando en última instancia valor comercial a las partes interesadas.

* Generación
* Almacenamiento
* Ingestión
* Transformación
* Visualización o entrega

Los datos tienen valor en cada fase de este ciclo, y los datos que no se consumen o consultan pueden representar un riesgo para cualquier empresa. Muchas empresas, en su búsqueda de proyectos ambiciosos en la era del big data, han recopilado cantidades masivas de datos que finalmente no se utilizaron.

Los proyectos deben ser intencionales a lo largo de todo el ciclo de vida, tanto en la ingeniería como en los datos. Un ingeniero de datos es responsable de extraer información de manera oportuna, siguiendo los protocolos adecuados de seguridad e integración, y cualquier otra tarea necesaria.

#### ¿Pero el trabajo de un Ingeniero de Datos termina aquí?

Eso es lo que quiero que entiendas y a lo que quiero llegar: Un arquitecto de datos tiene que evaluar, diseñar, organizar y ver el valor en las fases del proyecto. Un ingeniero de datos podría realizar todas estas tareas, pero no es su trabajo principal.

Por ejemplo, imaginemos que vas a un hospital y conoces a un médico. Probablemente sabes con certeza que el médico:
* Examinará tu condición
* Realizará un diagnóstico
* Recetará medicamentos

Y seguramente no haría:
* Limpiar el hospital
* Fabricar el medicamento
* Gestionar la administración del hospital

&nbsp;

Pero ¿qué pasa con los ingenieros de datos? ¿Las expectativas no están claras? Lo que pasa, es que ellos pueden:

* Diseñar el modelo de datos de un Data Warehouse
* Manejar bases de datos de aplicaciones
* Crear un pipeline de datos para Machine Learning
* Gestionar todas las infraestructuras de big data e instalación de software
* Analizar big data para transformar datos crudos en información significativa

Como mencioné anteriormente, si las empresas fueran más maduras en datos, entonces habría límites mejor definidos. Al final del día, también depende de cómo las herramientas en lo que se le conoce como "modern data mangamenet" incrementan con la creciente complejidad de los datos.

#### ¿Qué es lo que un Ingeniero de Datos debería de hacer?

Creo que deberían tener una comprensión amplia de todo el ciclo de vida de los datos, distinguiendo entre habilidades esenciales, beneficiosas y/o opcionales.

Sin embargo, lo que se considera esencial en una empresa puede ser visto como opcional en otra. En última instancia, depende de las operaciones específicas y las necesidades de la empresa y sus clientes.


### Desafíos Comunes en el Ámbito de los Datos

Si la madurez de los datos es baja, es posible que encuentres:
* Silos de datos
* Infraestructura inadecuada
* Resistencia cultural
* Vulnerabilidades de seguridad

Por otro lado, si la madurez de los datos es alta, es posible que encuentres:
* Problemas de Gobierno y Gestión de Datos
* Innovación con tecnologías emergentes
* Desarrollo y mantenimiento de análisis avanzados

En ambos escenarios, puede haber una variedad de desafíos, pero es importante reconocer que muchos datos no se están utilizando de manera efectiva. Esto podría deberse a un diseño deficiente de la arquitectura de datos, una gobernanza o gestión de datos inadecuada, o una baja calidad de datos desde su creación.

### Conclusión

Un Arquitecto de Datos juega un papel crucial en la configuración del panorama de datos de una organización. Son responsables de crear arquitecturas de datos sólidas que garanticen la accesibilidad, confiabilidad y seguridad de los datos.

Al abordar tanto los aspectos estratégicos como tácticos, los Arquitectos de Datos llenan el vacío entre los requerimientos funcionales y los requerimientos técnicos. Su capacidad para evaluar compensaciones y desarrollar sistemas adaptables es esencial para satisfacer las necesidades de datos.

Por último, los Arquitectos de Datos capacitan a las organizaciones para utilizar efectivamente sus recursos de datos, impulsando el valor comercial y la innovación.

### TL;DR

Un Arquitecto de Datos diseña la estructura de almacenamiento, organización y utilización de datos para garantizar la calidad y flexibilidad de los mismos. Se enfocan en estrategia y tácticas, colaborando estrechamente con ingenieros de datos para implementar la arquitectura. Comprender el ciclo de vida de la ingeniería de datos y los desafíos comunes es clave para agregar el valor empresarial necesario.

