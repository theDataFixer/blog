---
title: "Data for Dummies"
url: "/datafordummies"
ShowToc: true
ShowReadingTime: true
---

Si alguna vez te has sentido abrumado por términos como Data Lake, metadata o Data Governance, entonces llegaste al lugar correcto. Sé que incluso para un mismo concepto existen diferentes interpretaciones, por lo que mi intención no es definir, sino explicar de forma sencilla la palabra acompañado de un ejemplo o un contexto.

Si crees que falta agregar algún concepto, o si deseas editar algún término, puedes hacer un comentario al final de esta publicación, o de igual manera puedes contactarme de la forma que se te haga más fácil.

### **Data**
Son hechos, cifras, o información cruda que se recopilan y almacenan para su posterior análisis. Puede incluir hechos, números, mediciones, observaciones, o cualquier otro detalle que se pueda utilizar para comprender un tema en particular.

_Si estás registrando la temperatura diaria en alguna ciudad durante un mes, puedes recopilar datos sobre la temperatura, humedad, velocidad del viento, y precipitaciones a lo largo del día. Los datos existen en diversas formas y se pueden encontrar en situaciones cotidianas._


### **Metadata**
Son los datos que proporcionan información sobre otros datos. Es el dato de los datos, como su origen, contexto, o significado, y nos ayuda a comprenderlos y gestionarlos de manera más efectiva.

_Si tienes fotos en tu smartphone, abre una imagen y puedes ver los metadatos como la fecha que se tomó, el tamaño, la ubicación, etc. La foto en sí misma es el dato principal, mientras que los metadatos proporcionan información complementaria sobre la foto._


### **Database**
Es un sistema de almacén digital que ayuda a organizar y administrar datos.

_El clásico ejemplo es pensar en una biblioteca. Cada libro tiene su etiqueta con su título, autor, etc. En la biblioteca se guardan y organizan libros, pero en lugar de libros, piensa en datos. Al igual que un sistema de archivos, una base de datos ayuda a mantener la información estructurada._


### **Structured Data**
Se refiere a información que está organizada en un formato en específico, haciéndolo fácil de entender tanto para los humanos como para las computadoras. Consiste de elementos de datos organizados en filas y columnas, como una tabla.

_Una guía telefónica contiene datos estructurados porque tiene organizados campos específicos como el nombre, el número telefónico, la dirección, y así sucesivamente._


### **Unstructured Data**
Se refiere a información que no tiene un formato en específico. Por lo general, los datos no estructurados carecen de una estructura predefinida, por lo que los hacen más difíciles de analizar y procesar en comparación con los datos estructurados.

_Imagina una pila de cartas escritas a mano. Cada carta puede contener diferente tipo de información, como historias personales, emociones, u opiniones. Estas cartas no siguen un formato estandarizado y puede variar en longitud, estilo de escritura o idioma. En el mundo digital los correos, las publicaciones de redes sociales, las imágenes, los videos, las grabaciones de audio, y los documentos con texto de formato libre son ejemplos de datos no estructurados._


### **Semi-structured Data**
Los datos semiestructurados se encuentran entre los datos estructurados y los datos no estructurados. Posee algo de organización pero no tiene un estricto formato predefinido como los datos estructurados.

_Piensa en una bandeja de entrada de un email. Cada email consiste en elementos estructurados como remitente, destinatario, asunto, y timestamp. No obstante, el cuerpo del email puede contener información no estructurada como texto de formato libre, adjuntos, o estilos de formato diferentes. Esta combinación de estructura y flexibilidad representa datos semiestructurados._


### **Duplicate Data**
Se refiere a tener múltiples copias idénticas o casi idénticas de la misma información dentro de un conjunto de datos o sistemas.

_Considera el escenario en donde estás administrando tu lista de contactos. En esa lista guardas nombres, teléfonos, y correos de tus amigos. Ahora, digamos que accidentalmente agregar el mismo contacto dos veces, resultando en datos duplicados._


### **Orphaned Data**
Son datos que existen sin ningun contexto asociado o significativo. Esencialmente, se trata de datos que carecen de conexiones o relaciones adecuadas con otros elementos de datos.

_Piensa en una bliblioteca en donde encuentras un libro que falta la información sobre su autor, su título, etc. Este libro se convierte en un libro huérfano porque no puede ser adecuadamente categorizado o utilizado, ya que carece de los detalles que lo harían valioso dentro del sistema de la biblioteca. De manera similar, en el contexto de los datos, los datos huérfanos podrían ser una entrada de datos sin ninguna información correspondiente, como un registro de cliente sin nombre o detalles de contacto. Estos datos se vuelven difíciles de analizar o utlizar de manera efectiva debido a que carecen del contexto necesario._

### **Incomplete or Missing Data**
Son los datos que no están completamente disponibles o carecen de cierta información requerida. Esto implica que existen brechas en los datos que pueden impedir su utilidad para el análisis o la otma de decisiones.

_Imagina que estás de viaje y estás usando una app de navegación (google maps) que te da los tiempos estimados de viaje basados en datos históricos de tráfico. Sin embargo, si la app no tiene la información actualizada sobre el tráfico o cierres de carreteras, no podrás predecir con precisión tu tiempo de viaje. En este escenario, los datos incompletos o faltantes son la ausencia de información en el tiempo real sobre el tráfico. De manera similar, en el mundo de los datos, lo faltante podría encontrarse cuando analizas el comportamiento de los clientes si ciertas variables no se capturan o se registran_ 


### **Mislabeled Data**
Son datos que han sido etiquetados o clasificados incorrectamente, lo que conlleva a información inexacta o engañosa. Esto implica que los datos no representan con precisión su verdadera naturaleza o significado.

_Estás organizando una colección de fotos. Tienes un folder llamado "vacaciones en Hawaii", pero al abrirlo encuentras imagenes que de tus vacaciones en México. En el contexto de datos, los datos mal etiquetados pueden ocurrir cuando se asignan etiquetas incorrectas._


### **Data Swamp**
Es la situación en donde una gran cantidad de datos se vuelve desorganizada, sin estructura y difícil utilizar de manera efectiva. Es un estado en el que los datos pierden valor y se vuelven estancado so inutilizables debido a la falta de una gestión y organización adecuadas.

_Estás en tu cuarto lleno de varios objetos como ropa, zapatos, libros, etc. El cuarto está desorganizado y se vuelve muy complicado encontrar lo que necesitas. En este ejemplo, el cuarto desordenado representa un data swamp. Asimismo, en el ámbito digital, un data swamp puede surgir cuando existe una abrumadora cantidad de datos desorganizados almacenados en diversos sistemas, bases de datos, o archivos._


### **Data Temperature**
Ayuda a las organizaciones a gestionar de manera más eficiente sus estrategias de almacenamiento y recuperación de datos, asegurando que los datos de acceso frecuente y críticos estén dispnibles de manera rápida, al tiempo que se optimizan los costos para los datos de acceso menos frecuente.

_En el ámbito de los datos, la temperatura de datos generalmente se clasfica en Hot Data, Warm data, and Cold Data. Los datos 'hot' se refieren a los datos que se utilizan activamente y se acceden con frecuencia (Como datos transaccionales en un sistema bancario), los datos 'warm' se refieren a los datos que se acceden con menos frecuencia pero que aún son relevantes para el análisis o toma de decisiones (Como datos históricos de ventas para análisis), y por último los datos 'cold' se refieren a los datos que se acceden raramente y se consideran menos críticos (Como copias de seguridad de datos).


### **Data Lineage**
Es el rastreo que muestran los datos desde su origen hasta su uso final a lo largo de su ciclo de vida. Es como si fuera un mapa que te dice de dónde viene el dato y cómo ha cambiado con el tiempo.

_Si quieres seguir el rastro de los ingredientes de alguna receta a lo largo de las generaciones, estás siguiendo el linaje de datos de la misma._


### **Data Migration**
Es cuando transfieres datos de un sistema a otro, ya sea para actualizar tecnología o para cambiar de plataforma.

_Es como mudarse de una casa vieja a una nueva (te llevas tus cosas y las organizas de manera similar en la nueva casa). Ahora para ponerlo más sencillo, en datos aplica cuando cambias de computadora, y transfieres tus fotos, documentos, y archivos necesarios._


### **Data Modeling**
Es la representación estructurada de cómo se organizan y relacionan los datos en un sistema.

_Imagina que estás por organizar tu fiesta y quieres asegurarte de que haya suficiente comida y bebida para tus invitados. Además, piensas en un área específica para cada tipo de comida, bebida, evento, etc. En datos terminas de igual manera organizando cómo estructurar y relacionar los datos en un sistema._


### **Data Maturity**
Es una forma de evaluar en qué etapa se encuentra una organización en términos de cómo utiliza y gestiona datos.

_Una compañía de retail podría empezar a recolectar datos usando spreadsheets, pero con el tiempo puede mejorar su madurez al centralizar sus datos, integrando diferentes fuentes, y utilizando analítica avanzada para tomar mejores decisiones._


### **Data Contract**

### **Data Entropy**

### **Data Debt**

### **Data Management**

### **Master Data Management**

### **Data Ops**

### **Data Orchestration**

### **Data Governance**
Son las políticas, reglas, y prácticas que aseguran la calidad, integridad, y seguridad de los datos.

_En un partido de fútbol, los involucrados son los jugadores y el árbitro, donde este último se asegura de que sigan las reglas y que jueguen limpio. No juega el árbitro, no toca el balón, pero sí se asegura en que se cumplan las normas._


### **Data Owner**
Es alguien que está a cargo de administrar y controlar un conjunto específico de datos.

_En una organización de atención médica, la propia organización sería la propietaria de los datos, responsable de proteger y gestionar los registros médicos de los pacientes._


### **Data Steward**
Es alguien que se asegura de la gestión adecuada, calidad, y usabilidad de los datos dentro de una organización.

_En una institución financiera, un equipo o una persona actúa como Data Steward para supervisar el cumplimiento normativo y el control de acceso para asegurar que los datos puedan utilizarse de manera efectiva para la toma de decisiones._


### **Data Security**
Son las medidas que se tienen que considerar para proteger los datos contra accesos no autorizados y pérdidas.

_Imagina que tienes una tienda de joyas y te llegaron 5 joyas super valiosas. Entonces tu, para protegerlas, los pones en una caja fuerte, y en una habitación especial,y  con una llave que solo tú y unos empleados de confianza pueden entrar. Ahora, trasladandolo a datos, usas contraseñas, accesos restringidos, protección de hackeos, entre otras posibles opciones para proteger tus datos._


### **Data Privacy**
Consta en respetar los derechos y preferencias de las personas en cuanto al uso y manejo de sus datos personales.

_“No necesitas privacidad si no tienes nada que ocultar”. Es una mala forma de interpretar la privacidad porque se crea la sensación de que las personas que exigen privacidad deben ser criminales. Todos sabemos que pasa cuando vas al baño, pero aun así, cierras la puerta._


### **Data Lifecycle**
Es el ciclo completo que sigue ya sea un dato o un conjunto de datos, desde su creación hasta su eliminación o archivo.

_Piensa en una plataforma de red social. Un usuario crea su perfil, captura su información, luego esa información se guarda en una base de datos, y eventualmente se archiva o se elimina de acuerdo a su relevancia y regulaciones._


### **Data Engineering Lifecycle**
El ciclo de ingeniería de datos involucra recolectar, guardar, procesar, analizar, y mantener la infraestructura.

_Una compañía de ecommerce ingesta datos de múltiples fuentes, lo transforma, lo integra, hace análisis, y visualiza la información para tomar mejores decisiones. Es un proceso iterativo e implica monitorear y mejorar continuamente._


### **Data Sources**
Son los lugares o entidades donde la data se origina o se recolecta.

_Si quieres tener información del clima de tu ciudad, puedes tener varios puntos de partida para obtener la información necesaria (como una aplicación, o una estación local). En este ejemplo, las últimas dos opciones que mencioné serían las fuentes de datos._


### **Data Storage**
Es un lugar centralizado donde se recopila y se combinan datos de múltiples fuentes.

_Es como encontrar un lugar para guardar tus libros en una librería para que después puedas encontrarlos y usarlos cuando lo requieras. En el mundo digital, este concepto involucra usar sistemas o dispositivos para almacenar y recuperar información digital._


### **Data Ingestion**
Es el proceso de recolectar e importar datos de varias fuentes hacia un sistema para almacenarlos.

_Imagina que estás en una compañía que opera tanto en físico como en una plataforma e-commerce, y quieres analizar los datos de cliente de varias fuentes. En este caso, la ingestión de datos sería importar datos de un CRM (Customer Relationship Management), de una plataforma de red social, o de la página de e-commerce._


### **Data Integration**
Se enfoca en combinar datos de diferentes fuentes en una vista unificada y consistente. Su propósito es establecer un modelo de datos común.

_De igual manera cuando ensamblas piezas de rompecabezas de diferentes lugares para completar la foto, la integración de datos unifica las fuentes._


### **Data Transformation**
Es cuando modificas, limpias, o reorganizas los datos para que sean más útiles.

_Imagina que estás en un supermercado en un diferente país al que naciste y ves los precios en una moneda diferente, por lo que tienes que comparar precios y transformarlo en una moneda que te sea más fácil de interpretar._


### **Data Serving**
Es el proceso de hacer los datos accesibles y disponibles para los usuarios o aplicaciones de manera eficiente.

_Piensa que estás en un restaurante y ordenaste un platillo. Los chefs en la cocina preparan la comida, y una vez que está listo, los meseros te sirven el platillo a tu mesa. En el contexto de datos, piensa en los datos como en la "comida" y piensa en los usuarios o aplicaciones como los "clientes"_

### **Staging Data**

### **Data Warehouse**
Es un repositorio centralizado y optimizado para gestionar grandes cantidades de datos de diferentes fuentes. Su enfoque es para análisis y toma de decisiones.

_Eres el gerente de varias tiendas. Tienes datos de ventas, de inventarios, de clientes, y otros datos relacionados a tu negocio. Se vuelve complicado obtener una visión integral de tu negocio y tomar decisiones informadas basadas en datos dispersos. Al crear un Data Warehouse, consolidas y optimizas la información para consultas eficientes, informes, y análisis._

### **Data Mart**

### **Data Lake**
Es un repositorio que puede recopilar una gran cantidad de datos estructurados, semiestructurados y no estructurados que se almacenan hasta que se necesiten para procesar o analizar.

_Te vas de viaje a una playa y tienes varias fotos de donde estuviste. En vez de organizar tus fotos, las mandas a tu Data Lake de Fotos donde van a estar disponibles en su estado original. Cuando ya desees clasificarlos, puedes elegir qué fotos y organizarlas de acuerdo a tus necesidades._


### **Data Lakehouse**

### **Data Platform**

### **Data Mesh**

### **Data Catalog**

### **Data Sharing**

### **Data Product**

### **Data Engineer**
Es el que se encarga de construir y mantener sistemas que recopilan, almacenan, y procesan grandes cantidades de datos.

_Es como si construyeras y mantuvieras las carreteras para transportar cosas. Por ejemplo, si trabajaras en Amazon o Mercado Libre, te tienes que encargar de llevar los paquetes a sus respectivos destinos y que estén bien empaquetados. Un ingeniero de datos se asegura de manera similar en que los datos lleguen a su destino de manera eficiente._


### **Data Analyst**
Son los encargados de explorar y encontrar patrones para obtener conocimiento del dominio en cuestión. Utilizan estadística y herramientas necesarias para entender el pasado y el presente.

_Si fueras un detective, analizar datos te ayudaría a convertir pistas en una historia lógica. Tomas números y hechos, y los transformas en información para entender qué pasó y qué está pasando._


### **Data Scientist**
Es parecido al analista de datos, pero la diferencia es que los científicos de datos utilizan técnicas de estadísticas robustas y aprendizaje automático (Machine Learning) para predecir el futuro. (Analistas son pasado y presente, científicos son el futuro)

_Si quieres predecir el clima, tienes que entender primero el por qué unas regiones llueven más que otras, luego recolectar datos sobre temperatura, patrones, etc. Y luego utilizas herramientas para analizar y predecir cuándo lloverá, o utilizas herramientas para tomar decisiones para ver si es seguro viajar._


### **Data Architect**
Es el que se encarga de la estructura de los activos de datos lógicos y físicos, y los recursos de gestión de datos de una organización.

_Si quieres construir una casa, necesitas un plano para ver dónde irían las puertas, la cocina, los cuartos, etc. De manera similar, un arquitecto de datos establece cómo se almacenan y conectan los datos._


&nbsp;

Más términos en construcción...
