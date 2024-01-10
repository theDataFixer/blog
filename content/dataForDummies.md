---
title: "Data for Dummies"
url: "/datafordummies"
ShowToc: true
ShowReadingTime: true
---

Si alguna vez te has sentido abrumado por términos como Data Lake, metadata o Data Governance, entonces llegaste al lugar correcto. Sé que incluso para un mismo concepto existen diferentes interpretaciones, por lo que mi intención no es definir, sino explicar de forma sencilla la palabra acompañado de un ejemplo o un contexto.

Si crees que falta agregar o editar algo, puedes hacer un comentario al final de esta publicación, o de igual manera puedes contactarme de la forma que se te haga más fácil.

### **Data**
Son hechos, cifras, o información cruda que se recopilan y almacenan para su posterior análisis. Puede incluir hechos, números, mediciones, observaciones, o cualquier otro detalle que se pueda utilizar para comprender un tema en particular.

_Si estás registrando la temperatura diaria en alguna ciudad durante un mes, puedes recopilar datos sobre la temperatura, humedad, velocidad del viento, y precipitaciones a lo largo del día. Los datos existen en diversas formas y se pueden encontrar en situaciones cotidianas._


### **Metadata**
Es información que describe otros datos. Proporciona detalles sobre el contenido, calidad, condición, origen y otras características de un elemento específico. En el contexto digital, los metadatos puede incluir detalles como el autor, la fecha de creación, el tamaño del archivo y palabras clave.

_Si tienes fotos en tu smartphone, abre una imagen y puedes ver los metadatos como la fecha que se tomó, el tamaño, la ubicación, etc. La foto en sí misma es el dato principal, mientras que los metadatos proporcionan información complementaria sobre la foto._


### **Database**
Es una colección organizada de información estructurada, generalmente almacenada y accedida electrónicamente desde un sistema informático. Permite el almacenamiento, la recuperación y la manipulación eficientes de datos.

_El clásico ejemplo es pensar en una biblioteca. Cada libro tiene su etiqueta con su título, autor, etc. En la biblioteca se guardan y organizan libros, pero en lugar de libros, piensa en datos. Al igual que un sistema de archivos, una base de datos ayuda a mantener la información estructurada._


### **Structured Data**
Se refiere a información que está organizada en un formato en específico, haciéndolo fácil de entender tanto para los humanos como para las computadoras. Consiste de elementos de datos organizados en filas y columnas, como una tabla.

_Una guía telefónica contiene datos estructurados porque tiene organizados campos específicos como el nombre, el número telefónico, la dirección, y así sucesivamente._


### **Unstructured Data**
Se refiere a información que no tiene un formato en específico. Por lo general, los datos no estructurados carecen de una estructura predefinida, por lo que los hacen más difíciles de analizar y procesar en comparación con los datos estructurados.

_Imagina una pila de cartas escritas a mano. Cada carta puede contener diferente tipo de información, como historias personales, emociones, u opiniones. Estas cartas no siguen un formato estandarizado y puede variar en longitud, estilo de escritura o idioma._

_En el mundo digital los correos, las publicaciones de redes sociales, las imágenes, los videos, las grabaciones de audio y los documentos con texto de formato libre son ejemplos de datos no estructurados._


### **Semi-structured Data**
Los datos semiestructurados se encuentran entre los datos estructurados y los datos no estructurados. Posee algo de organización pero no tiene un estricto formato predefinido como los datos estructurados.

_Piensa en una bandeja de entrada de un email. Cada email consiste en elementos estructurados como remitente, destinatario, asunto, y timestamp. No obstante, el cuerpo del email puede contener información no estructurada como texto de formato libre, adjuntos, o estilos de formato diferentes. Esta combinación de estructura y flexibilidad representa datos semiestructurados._


### **Data Testing**
Es el proceso de examinar y validar datos para asegurar su calidad, precisión y confiabilidad. Involucra checkar si los datos cumple con los estándares esperados y satisfacen los criterios deseados. En esencia, la prueba de datos es como corregir pruebas en tus datos para detectar errores o inconsistencias, asegurando que la información con la que estás trabajando sea confiable y digna de confianza.

_Imagina que trabajas como cajero/a en un supermercado, y tu trabajo es registrar los precios de diferentes productos vendidos. La prueba de datos en este contexto implicaría verificar que el precio que ingreses para cada producto sea correcto, asegurándote de que no haya errores tipográficos o equivocaciones. Podrías comparar los precios ingresados con una lista de referencia o verificar con un coworker para validar la precisión de los datos registrados._


### **Duplicate Data**
Se refiere a tener múltiples copias idénticas o casi idénticas de la misma información dentro de un conjunto de datos o sistemas.

_Considera el escenario en donde estás administrando tu lista de contactos. En esa lista guardas nombres, teléfonos, y correos de tus amigos. Ahora, digamos que accidentalmente agregar el mismo contacto dos veces, resultando en datos duplicados._


### **Orphaned Data**
Son datos que existen sin ningún contexto asociado o significativo. Esencialmente, se trata de datos que carecen de conexiones o relaciones adecuadas con otros elementos de datos.

_Piensa en una bliblioteca en donde encuentras un libro que falta la información sobre su autor, su título, etc. Este libro se convierte en un libro huérfano porque no puede ser adecuadamente categorizado o utilizado, ya que carece de los detalles que lo harían valioso dentro del sistema de la biblioteca._

_De manera similar, en el contexto de los datos, los datos huérfanos podrían ser una entrada de datos sin ninguna información correspondiente, como un registro de cliente sin nombre o detalles de contacto. Estos datos se vuelven difíciles de analizar o utlizar de manera efectiva debido a que carecen del contexto necesario._


### **Incomplete or Missing Data**
Son los datos que no están completamente disponibles o carecen de cierta información requerida. Esto implica que existen brechas en los datos que pueden impedir su utilidad para el análisis o la toma de decisiones.

_Imagina que estás de viaje y estás usando una app de navegación (google maps) que te da los tiempos estimados de viaje basados en datos históricos de tráfico. Sin embargo, si la app no tiene la información actualizada sobre el tráfico o cierres de carreteras, no podrás predecir con precisión tu tiempo de viaje._

_En este escenario, los datos incompletos o faltantes son la ausencia de información en el tiempo real sobre el tráfico. De manera similar, en el mundo de los datos, lo faltante podría encontrarse cuando analizas el comportamiento de los clientes si ciertas variables no se capturan o se registran_ 


### **Mislabeled Data**
Son datos que han sido etiquetados o clasificados incorrectamente, lo que conlleva a información inexacta o engañosa. Esto implica que los datos no representan con precisión su verdadera naturaleza o significado.

_Estás organizando una colección de fotos. Tienes un folder llamado "vacaciones en Hawaii", pero al abrirlo encuentras imagenes que de tus vacaciones en México. En el contexto de datos, los datos mal etiquetados pueden ocurrir cuando se asignan etiquetas incorrectas._


### **Data Swamp**
Es la situación en donde una gran cantidad de datos se vuelve desorganizada, sin estructura y difícil utilizar de manera efectiva. Es un estado en el que los datos pierden valor y se vuelven estancado so inutilizables debido a la falta de una gestión y organización adecuadas.

_Estás en tu cuarto lleno de varios objetos como ropa, zapatos, libros, etc. El cuarto está desorganizado y se vuelve muy complicado encontrar lo que necesitas. En este ejemplo, el cuarto desordenado representa un data swamp._

_Asimismo, en el ámbito digital, un data swamp puede surgir cuando existe una abrumadora cantidad de datos desorganizados almacenados en diversos sistemas, bases de datos, o archivos._


### **Data Temperature**
Ayuda a las organizaciones a gestionar de manera más eficiente sus estrategias de almacenamiento y recuperación de datos, asegurando que los datos de acceso frecuente y críticos estén dispnibles de manera rápida, al tiempo que se optimizan los costos para los datos de acceso menos frecuente.

_En el ámbito de los datos, la temperatura de datos generalmente se clasfica en Hot Data, Warm data, and Cold Data. Los datos 'hot' se refieren a los datos que se utilizan activamente y se acceden con frecuencia (Como datos transaccionales en un sistema bancario), los datos 'warm' se refieren a los datos que se acceden con menos frecuencia pero que aún son relevantes para el análisis o toma de decisiones (Como datos históricos de ventas para análisis), y por último los datos 'cold' se refieren a los datos que se acceden raramente y se consideran menos críticos (Como copias de seguridad de datos)._


### **Data Lineage**
Es la capacidad de rastrear el origen y movimiento de los datos a lo largo de su ciclo de vida. Esto te ayuda a entender de dónde provienen los datos, cómo se transforman y a dónde van, lo que te permite realizar un seguimiento y analizar el flujo de datos dentro de un sistema u organización. En términos simples, la línea de datos es como rastrear los pasos de tus datos, lo que te permite comprender su recorrido desde el principio hasta el final y obtener información sobre cómo se utiliza y transforma en el camino.

_Imagina que ordenas un producto en linea. La plataforma de e-commerce procesa tu orden, lo cual implica múltiples pasos como la gestión de inventario, el procesamiento de pagos y el envío. La línea de datos en este escenario implicaría rastrear el recorrido de los detalles de tu pedido desde el momento en que realizas el pedido hasta que llega a tu puerta. Por ejemplo, la línea de datos podría mostrar que los detalles de tu pedido se originaron en la base de datos de la tienda en línea, luego se movieron al sistema de pago y posteriormente al departamento de logística para el envío._


### **Data Migration**
Es el proceso de transferir datos de un sistema, aplicación, o ubicación de almacenamiento a otro. Involucra mover los datos desde su ubicación actual a un nuevo destino, asegurando su integridad, completitud y compatibilidad. En resumen, es como mover tus datos digitales de una ubicación a otra, al igual que mover objetos físicos de una casa a otra durante una mudanza. 

_Es como mudarse de una casa vieja a una nueva. Como parte de la mudanza, necesitas transferir todas tus pertenencias, incluyendo muebles, electrodomésticos y objetos personales desde tu antigua casa a la nueva. La migración de datos es similar a este proceso, pero en lugar de objetos físicos, implica mover datos digitales._ 

_Durante la migración, es importante considerar factores como la compatibilidad de formato de datos, la seguridad de datos, y la validación de los datos para garantizar una transferencia exitosa._ 


### **Data Model**
Es la representación estructurada de datos que define cómo se organizan, almacenan, y relacionan entre sí. Describe la estructura lógica, las relaciones y las restricciones de los datos. Un modelo de datos puede estar representado en diversas formas, como un diagrama, un esquema o un conjunto de reglas. Prácticamente es el plano para diseñar y crear un sistema de datos.

_Una forma popular de representar un modelo de datos es por medio de un diagrama entidad-relación (ER diagram), en donde las entidades son representadas con rectángulos, y las relaciones se representan por medio de líneas que se conectan entre sí._

_Otra forma de representar el modelo es por medio de un esquema, que básicamente define la estructura y organización de una base de datos. Y por último un modelo de datos también puede ser definido usando una serie de reglas que describan cómo la data puede ser organizada y relacionada (como convenciones de nombres, restricciones de integridad de datos y relaciones de datos)_


### **Data Modeling**
Es el proceso de crear el modelo de datos. Involcura analizar los requerimientos, entender las fuentes de datos, y diseñar la estructura y relaciones de los datos. El 'Modelado de Datos' puede considerarse como la actividad de traducir conceptos y entidades del mundo real en una representación formal de un modelo de datos.

_Tienes una plataforma de e-commerce. Al momento de crear un modelo de datos para un tipo de plataforma como estas, el modelado de datos involucraría identificar y representar entidades clave, relaciones, y atributos. Por ejemplo un usuario representaría una persona que se registra en la plataforma y puede tener atributos como ID, nombre, información de contacto, y detalles de su modo de pago._


### **Data Maturity**
Es una forma de evaluar en qué etapa se encuentra una organización en términos de cómo utiliza y gestiona datos. Representa la capacidad de la organización para recolectar, almacenar, procesar y analizar datos de manera efectiva para obtener ideas valiosas y tomar decisiones.

_Tienes un pequeño negocio que se basa en datos de clientes para impulsar campañas de marketing. Inicialmente, recopilas información de los clientes en hojas de cálculo y tomas decisiones basadas en datos demográficos básicos. En esta etapa, tu nivel de madurez es relativamente bajo. Conforme tu negocio crece, inviertes en un sistema de gestión de relaciones con los clientes (CRM) que automatiza la recoplicación de datos y proporciona capacidades analíticas más avanzadas._

_Comienzas a utilizar estos datos para crear campañas de marketing personalizadas y hacer un seguimiento de su efectividad. En esta etapa, tu nivel de madurez aumentaría. Y más adelante, implementas prácticas de gestión de datos más sofisticadas, como políticas de gobierno de datos, mediciones de calidad de datos, e integración de datos en múltiples sistemas. Utilizas algoritmos de Machine Learning para predecir el comportamiento de los clientes y tienes un equipo dedicado de datos que monitorea y mejora continuamente los procesos de datos. En esta etapa, tu nivel de madurez es alto._

### **Data Pipeline**
Es una serie de procesos digitales utilizados para recolectar, modificar, y entregar datos de un lugar a otro. Consiste en la ingestión de datos sin procesar de diversas fuentes, como aplicaciones, dispositivos y otros canales digitales, y trasladarlos a un repositorio de datos, como un Data Lake o un Data Warehouse, para su análisis.

_Piensa que estás en una tienda en línea. Cuando realizas un pedido, la página necesita procesar tu orden, checar inventario, generar una etiqueta de envío, y enviarte un correo de confirmación. Todos estos pasos son parte de un Data Pipeline porque la página toma tu orden, pasa por varias etapas, y finalmente obtienes tu correo de confirmación._


### **Data Contract**
Es un documento que define la estructura, formato, semántica, calidad, y términos de uso para el intercambio de datos entre un proveedor de datos y sus consumidores. Ayuda a asegurar que los datos sean consistentes, confiables, y entendibles en diferentes sistemas.

_Eres un chef que necesita otros ingredientes de un proveedor. En este caso, un contrato de datos sería una lista de compras detallada que especifica claramente el tipo de ingredientes, la cantidad necesaria, etc._ 

_Ahora, en datos, diferentes sistemas necesitan compartir o intercambiar datos. Para garantizar una comunicación fluida, un contrato ayuda a definir la estructura y reglas para los datos que se comparten. Especifica cosas como el formato de los datos (por ejemplo, CSV, JSON), los campos y sus tipos, cualquier regla de validación o restricción, y el comportamiento esperado._


### **Data Entropy**
Describe la cantidad de incertidumbre o desorden en un conjunto de datos. Cuanto mayor sea la entropía, mayor será la aleatoriedad y la falta de patrones en los datos.

_Tienes una baraja de cartas que está perfectamente ordenada desde el as hasta el rey en cada palo. En este caso, la entropía de los datos es baja porque el orden es predecible y no contiene mucha aleatoriedad. Ahora, consideremos una baraja de cartas mezclada donde las cartas están en un orden aleatorio. En este caso, la entropía de los datos es alta porque el orden es impredecible y contiene más aleatoriedad_


### **Data Debt**
Es la acumulación de problemas que surgen de prácticas inadecuadas de gestión de datos. Al igual que la deuda técnica, la deuda de datos es el resultado de descuidar el mantenimiento de los activos de datos, lo que conduce a inconsistencias, redundancias e inexactitudes en los datos.

_Imagina que en tu empresa, las partes interesadas requieren una nueva función o producto de datos. Los científicos de datos empiezan a explorar y se dan cuenta que los datos no están disponibles, por lo que le piden a los ingenieros de datos un nuevo data pipeline. Sin embargo, los ingenieros de datos tienen varias solicitudes por lo que les tomará meses resolver este requerimiento._


_Los científicos de datos se sienten presionados, así que deciden no esperar y acceder directamente a los sistemas fuente y a las bases de datos sin los estándares de producción o mejores prácticas y, en consecuencia, se acostumbran a este proceso porque les brinda mayor autonomía y terminan creando una gran cantidad de deuda de datos (Y por ende generan inconsistencias de datos, altos costos de mantenimiento, o responsabilizar a las personas por los datos generados)_


### **Data Silo**
Es una colección de datos que está controlado por un departamento o unidad de negocio y aislado del resto de la organización. Normalmente los datos se terminan almacenando en un sistema independiente y a menudo es incompatible con otros conjuntos de datos, lo que dificulta que los usuarios en otras partes de la organización accedan y utilicen los datos.

_Imagina que tienes varias piezas de rompecabezas dispersas en diferentes habitaciones de tu casa. Cada habitación representa un departamento diferente dentro de una empresa, y las piezas de rompecabezas representan datos._

_En el escenario de los silos de datos, cada departamento tiene su propia pieza de rompecabezas separada de los demás. Las piezas de un cuarto no son accesibles o compartidas con otros cuartos. Esto significa que cada departamento tiene su propio conjunto de datos que están aisladas del resto de la organización_


### **Data Management**
Es el proceso de recopilar, almacenar, organizar y utilizar datos de manera segura, eficiente y rentable.

_Tienes una gran colección de fotos de tu familia guardadas en tu computadora. Para administrar mejor tu colección, creas folders y subfolders para categorizar las fotos basado en eventos (Probablemente separas folders por cumpleaños, vacaciones, etc). Si quieres encontrar una foto en particular, es mucho más sencillo navegar al folder correspondiente en vez de encontrar las fotos una por una._

_Similarmente, en la gestión de datos, los datos deben de estar organizados, etiquetados, y guardados en sistemas apropiados. Esto conlleva a que se tengan que definir las estructura de los datos, que se tengan que establecer convenciones de nombres para los datos, determinar controles de acceso e implementar mecanismos de respaldo y recuperación de datos._


### **Master Data Management**
Es un proceso y conjunto de prácticas dirigido a crear y administrar un único 'golden record' de entidades de datos importantes dentro de una organización para garantizar coherencia, precisión y confiabilidad. Un MDM otorga una vista unificada de los datos en varios sistemas para satisfacer las necesidades de un negocio.

_Eres parte de una empresa de retail que opera múltiples tiendas y una plataforma en línea. En esta compañía, tienes datos de clientes dispersos en distintos sitemas y bases de datos (como registros de ventas, programas de lealtad y registros en línea). Sin un adeucado Master Data Management, es posible que termines teniendo registros duplicados o inconsistencias en la entidad de clientes (Un ejemplo, tener a Juan Hernández, y en el sistema de ventas tiene diferentes entradas, programa de lealtad, y sistema de registro en línea con diferentes variaciones en el nombre, información de contacto, etc.)_

_Entonces la empresa decide abordar este problema creando un MDM. Decide crear un repositorio central que funciona como la única fuente de verdad para los datos de los clientes. En este sistema de gestión de datos maestros, se consolidan, estandarizan, y elmininan duplicados de diferentes fuentes. Así, en lugar de tener múltiples versiones de los registros de Juan Hernández, el MDM garantiza que solo haya un registro consolidado y preciso._


### **Data Democratization**
Significa que todos en la organización puedan acceder, entender, y utilizar los datos para tomar decisiones. Para lograr que los datos sean útiles, las organizaciones deben de romper los silos de datos y asegurarse de que los diversos usuarios de datos puedan colaborar, y que ya no tengan que depender de especialistas de datos o departamentos de IT.

_Trabajas para una empresa de e-commerce que tienen un equipo centralizado de análisis responsable de generar informes y obtener información. Por ello, departamentos como marketing, ventas y operaciones tenían que depender del equipo de análisis para solicitar e interpretar datos para sus procesos de toma de decisiones._

_Sin embargo, la compañía decide implementar la democratización de datos. Introducen herramientas de análisis self-service y tableros de control que ofrecen interfaces amigables para que los usuarios accedan y analicen los datos. Ahora, los departamentos pueden navegar fácilmente por la plataforma de análisis, ejecutar consultar y generar informes por sí mismos sin la necesidad de involucrar al equipo de análisis en cada paso._


### **Data Catalog**
Es un inventario organizado de los activos de los datos que usa metadatos para ayudar a una organización a administar sus datos. Piensa como si fuera un repositorio centralizado donde puedes encontrar información relevante para tus necesidades respecto a datos, ya que te ayuda a entender qué dato está disponible, dónde está ubicado, y cómo puedes accesar a el.

_Estás en una tienda de retail. Un catálogo de datos tendría información de varias fuentes de datos, como datos de ventas, datos de clientes, datos de inventario, y así sucesivamente. Esto tendría detalles como qué conjunto de datos tienen, cuándo fue actualizado por última vez, quién lo administra, y metadata relevante._

_Un catálogo de datos abarca una gama más amplia de información sobre diversos activos de datos en toda la organización, incluyendo metadatos, linaje de datos, calidad de datos e información de acceso. El objetivo es proporcionar una visión integral del panorama de datos de la organización._


### **Data Dictionary**
Se enfoca en proveer definiciones y descripciones de elementos de datos en específico dentro de una base de datos o de un conjunto de datos. Ayuda a entender el significado y formato de los elementos individuales de datos.

_Tienes una aplicación de administración de contactos y quieres almacenar información sobre tus amigos. Para cada amigo, quieres guardar su nombre, número de teléfono y dirección de correo electrónico._

_Un diccionario de datos ayudaría a tener una visión general de los datos disponibles, ayudaría a identificar los recursos relevantes y permite ver los detalles técnicos como esquemas, formatos de datos, responsable del mantenimiento, etc._


### **Data Ops**
Es una práctica que se enfoca en gestionar y optimizar el flujo de datos dentro de una organización. Es similar a cómo se administran otros procesos en una empresa, pero se centra específicamente en el manejo de datos. En resumen, DataOps es una metodología que se utiliza para gestionar y optimizar el flujo de datos en una organización. Es similar a DevOps, pero se enfoca específicamente en el manejo de datos.

_Imagina que eres el gerente de una tienda de ropa en línea. Tienes una gran cantidad de datos, como información de clientes, inventario, etc. Para asegurarte de que estos datos sean útiles y estén disponibles cuando los necesites, necesitas implementar Data Ops._

_En este caso, Data Ops implicaría establecer procesos y herramientas para recopilar, almacenar y analizar los datos de manera eficiente. Por ejemplo, podrías utilizar un sistema automatizado que registre automáticamente los datos de los clientes cuando realizan una compra, los almacene en una base de datos segura y los organice de manera que puedas acceder a ellos fácilmente._


### **Data Orchestration**
Implica la coordinación y gestión de diversas fuentes de datos, procesos y flujos de trabajo para garantizar una integración e interacción perfecta. Incluye actividades como movimiento de datos, transformación , programación y monitoreo para habilitar operaciones basadas en datos.

_Te encuentras en la gestión de la cadena de suministro de una empresa minorista. La orquestación de datos puede usarse para coordinar de manera transparente los datos de inventario de los proveedores, los datos de ventas de las tiendas y los datos de envío para optimizar la cadena de suministro y garantizar operaciones eficientes. Al orquestar estas fuentes y procesos de datos, la empresa puede tomar decisiones informadas y optimizar su logísitca._

### **Data Governance**
Son las políticas, reglas, y prácticas que aseguran la calidad, integridad, y seguridad de los datos. Incluye catalogar los datos, definir estandares y el proceso en torno a cómo se utiliza los datos en una organización.

_Piensa en el típico ejemplo en donde el gobierno de datos se ejecuta mal o no existe. Un analista de negocio tiene un requerimiento de crear un reporte pero no sabe que data usar para solucionar la petición. Probablemente tarde horas y horas revisando decenas de tablas en una base de datos transaccional, adivinando qué campos podrían ser útiles. El analista crea un informe "correcto", pero no está completamente seguro de que los datos del informe sean confiables. El destinatario del reporte también cuestiona la validez de los datos (y no solo de este reporte, sino también los datos de los sistemas de la empresa). La compañía está confundida acerca de su confiabildiad, por lo que dificulta la planificación y decisión al momento de usar los datos._

_El gobierno de datos es fundamental para la empresa que se quiera regir en los datos. Cuando se practica una buena gobernanza de datos, las personas, los procesos y las tecnologías se alinean para considerar llos datos como un impulsor clave de negocio. Si surgen problemas con los datos, se abordan de manera oportuna. (Nota: Las categorías principales de la gobernanza de datos son la observabilidad, la seguridad, y la responsabilidad. Dentro de estas categorías existen subcategorías, como la calidad de datos, los metadatos y la privacidad)_


### **Data Owner**
Es el individuo o entidad que tiene la responsabilidad y el control último sobre activos de datos específicos. El propietario de datos suele ser responsable de determinar quién tiene acceso a los datos, garantizar su precisión y seguridad, y definir su uso permitido.

_Un ejemplo podría ser un hospital, donde el médico jefe o el administrador del hospital pueden estar designados como los propietarios de datos de los expedientes médicos de los pacientes. Serían responsables de supervisar quién puede acceder a los expedientes, mantener su confidencialidad y garantizar el cumpllimiento de las regulaciones de protección de datos._


### **Data Steward**
Es alguien responsable de gestionar y garantizar la calidad, seguridad y uso de los activos de datos de una organización. Por lo general, establecen y hacen cumplir políticas y procedimientos de gestión de datos, supervisan la integración de datos y facilitan el cumplimiento de regulaciones. 

_Eres el encargado de una institución financiera que supervisa la protección y privacidad de los datos de los clientes. Tu te encargas de cumplir y asegurar que los datos de los clientes se manejen de acuerdo con los requisitos legales, las normas de la industria y las políticas internas, actuando así como un data steward para los datos financieros sensibles de la organización._


### **Data Guardian**
Se refiere a un rol, política o tecnología específicamente designada para proteger la integridad, confidencialidad y disponibilidad de los datos. Esto podría incluir la gestión de permisos, la implementación de medidas de seguridad y la supervisión del acceso a los datos.

_Imagina que has dejado tu casa al cuidado de un vecino de confianza mientras estás de vacaciones. Este vecino vigila tu casa, riega tus plantas y se asegura de que no entren visitantes no deseados. En este escenario, tu casa y pertenencias son tus datos, y el vecino es el guardián de datos que mantiene todo seguro y en orden hasta que regreses._

_En un entorno de atención médica, un guardián de datos es crucial. Un guardián supervisaría los registros de pacientes, un tipo de datos sensibles que requiere una protección rigurosa. El guardián se aseguraría de que los datos médicos estén encriptados, se registre y analice el acceso para detectar actividades no autorizadas, y de que los datos se compartan de manera segura con partes autorizadas._


### **Data Security**
Se refiere a la protección de los datos digitales contra el acceso no autorizado, la corrupción o el robo a lo largo de su ciclo de vida. Implica implementar medidas como el cifrado, controles de acceso y monitoreo para salvaguardar la información confidencial y prevenir violaciones o revelaciones no autorizadas.

_Una institución financiera cifra los datos financieros de los clientes e implementa estrictos controles de acceso para evitar que personas no autorizadas vean o modifiquen los datos. Esto ayuda a proteger la información financiera sensible de los clientes de amenazas cibernéticas y posibles violaciones de datos._


### **Data Privacy**
Consta en respetar los derechos y preferencias de las personas en cuanto al uso y manejo de sus datos personales. Es el manejo responsable de la información personal de individuos, asegurando que sus datos estén protegidos contra el acceso, uso o divulgación no autorizados.

_“No necesitas privacidad si no tienes nada que ocultar”. Es una mala forma de interpretar la privacidad porque se crea la sensación de que las personas que exigen privacidad deben ser criminales. Todos sabemos que pasa cuando vas al baño, pero aun así, cierras la puerta. Un ejemplo de privacidad de datos es cuando un minorista en línea recopila la información personal de los clientes para procesar pedidos, pero se asegura que estos datos se almacenen de forma segura y se obtenga el consentimiento de los clientes para comunicaciones de marketing._


### **Data Lifecycle**
Se refiere a las etapas por las que atraviesa la información desde su creación o captura inicial hasta su posterior eliminación o archivado. Estas etapas suelen incluir la creación de datos, su almacenamiento, uso, compartición, archivado y eliminación.

_Es como el viaje de un libro: desde que el autor lo escribe, pasando por su publicación, lectura por las personas, almacenamiento en una biblioteca y posiblemente su archivado o retirada de circulación._

_En el ámbito de los datos, un ejemplo del ciclo de vida de los datos sería la información de productos de una empresa minorista. Comienza con la creación de la información del producto, luego se almacena en una base de datos, se utiliza para ventas en línea, se comparte con proveedores, se archiva para análisis históricos y finalmente se elimina cuando el producto ya no está disponible._


### **Data Engineering Lifecycle**
El ciclo de ingeniería de datos involucra recolectar, guardar, procesar, analizar, y mantener la infraestructura. Detectas las fuentes, defines el almacenamiento, defines la ingestión, transformas, y por último disponibilizas la información.

_Una compañía de ecommerce ingesta datos de múltiples fuentes, lo transforma, lo integra, hace análisis, y visualiza la información para tomar mejores decisiones. Es un proceso iterativo e implica monitorear y mejorar continuamente._


### **Data Sources**
Se refieren al origen o ubicación desde la cual se recopilan o extraen los datos para utilizar en análisis, informes o toma de decisiones.

_Las fuentes de datos se pueden comparar con diferentes ingredientes utilizados en la cocina, como frutas, verduras y especias, que se recopilan de varios lugares para crear una receta._

_En el ámbito de los datos, un ejemplo de fuentes de datos es una empresa que recopila información de sistemas dispares, como transacciones de ventas de un sistema de punto de venta, datos de clientes de una plataforma CRM y datos de tráfico web de una herramienta de análisis, para análisis empresarial e informes._


### **Data Storage**
Es un lugar centralizado donde se recopila y se combinan datos de múltiples fuentes. Implica la retención de datos en un formato estructurado para su acceso y uso futuro.

_Es como encontrar un lugar para guardar tus libros en una librería para que después puedas encontrarlos y usarlos cuando lo requieras. En el mundo digital, este concepto involucra usar sistemas o dispositivos para almacenar y recuperar información digital._


### **Data Ingestion**
Es el proceso de recopilar, importar y transferir datos procedentes de diversas fuentes hacia un sistema de almacenamiento o informático para su posterior procesamiento y análisis.

_Es como recopilar y organizar ingredientes de diferentes proveedores y llevarlos a la cocina de un restaurante para preparar comidas._

_Ahora, en datos, un ejemplo sería una empresa minorista que recopila datos de ventas de múltiplestiendas y canales en línea, y los ingiere en un almacén de datos centralizado para análisis e informes._


### **Data Integration**
Se enfoca en combinar datos de diferentes fuentes en una vista unificada y consistente. Su propósito es establecer un modelo de datos común.

_De igual manera cuando ensamblas piezas de rompecabezas de diferentes lugares para completar la foto, la integración de datos unifica las fuentes. Un ejemplo sería una empresa que fusiona datos de clientes de un CRM, datos de ventas de un sistema ERP y datos de marketing de campañas digitales para crear una visión integral para análisis y toma de decisiones empresariales estratégicas._


### **Data Transformation**
Es convertir, reformatear y reestructurar los datos para adaptarlos al análisis, almacenamiento o presentación.

_Imagina que estás en un supermercado en un diferente país al que naciste y ves los precios en una moneda diferente, por lo que tienes que comparar precios y transformarlo en una moneda que te sea más fácil de interpretar._


### **Data Serving**
Es el proceso de hacer los datos accesibles y disponibles para los usuarios o aplicaciones de manera eficiente.

_Piensa que estás en un restaurante y ordenaste un platillo. Los chefs en la cocina preparan la comida, y una vez que está listo, los meseros te sirven el platillo a tu mesa. En el contexto de datos, piensa en los datos como en la "comida" y piensa en los usuarios o aplicaciones como los "clientes"_

### **Staging Data**
Es el proceso de almacenar temporalmente y preparar datos para cargarlos en un almacén de datos, lago de datos u otro repositorio de datos.

_Es como preparar y organizar todas las herramientas, equipos y materiales necesarios antes de comenzar un proyecto casero, como pintar una habitación o ensamblar muebles. Involucra tener todo listo y organizado para facilitar la ejecución fluida del proyecto._

_En datos sería almacenar y estructurar datos sin procesar de diversas fuentes en una zona de staging antes de integrarlos en un almacenamiento unificado o en una plataforma de análisis._


### **Data Warehouse**
Es un repositorio centralizado y optimizado para gestionar grandes cantidades de datos de diferentes fuentes. Su enfoque es para análisis y toma de decisiones.

_Eres el gerente de varias tiendas. Tienes datos de ventas, de inventarios, de clientes, y otros datos relacionados a tu negocio. Se vuelve complicado obtener una visión integral de tu negocio y tomar decisiones informadas basadas en datos dispersos. Al crear un Data Warehouse, consolidas y optimizas la información para consultas eficientes, informes, y análisis._

### **Data Mart**
Es un subconjunto de un almacén de datos de una organización que está diseñado para atender a una línea de negocio o departamento específico.

_Es como una sección especializada en una biblioteca que contiene libros, revistas y recursos centrados en un tema o materia específica, satisfaciendo las necesidades de un grupo particular de lectores._

_Si ponemos en contexto datos, un ejemplo práctico de un data mart es un departamento de ventas que tiene su propio data mart dentro del almacén de datos de la empresa, dedicado a almacenar y analizar datos relacionados con las ventas para los requisitos específicos de informes y análisis del departamento._


### **Data Lake**
Es un repositorio que puede recopilar una gran cantidad de datos estructurados, semiestructurados y no estructurados que se almacenan hasta que se necesiten para procesar o analizar.

_Te vas de viaje a una playa y tienes varias fotos de donde estuviste. En vez de organizar tus fotos, las mandas a tu Data Lake de Fotos donde van a estar disponibles en su estado original. Cuando ya desees clasificarlos, puedes elegir qué fotos y organizarlas de acuerdo a tus necesidades._


### **Data Lakehouse**
Es una arquitectura moderna de gestión de datos que combina los elementos de un data lake y un data warehouse. Un data lake termina siendo un depósito de datos sin procesar, mientras que un data warehouse está altamente estructurado y se utiliza para fines analíticos. Un data lakehouse tiene como objetivo almacenar grandes cantidades de datos estructurados y no estructurados (como un data lake) y soporta el tipo de consultas y análisis de datos eficientes típicamente posibles de un data warehouse.

_Netflix tiene que lidiar con un volumen colosal de datos de diversas fuentes, como datos de usuarios, preferencias, datos de transmisión, metadatos de contenido, etc. Tradicionalmente, podrían almacenar datos sin procesar en un lago de datos y luego procesar y trasladar partes relevantes as un data warehouse para su análisis._

_Con un lakehouse, Netflix puede almacenar todo en un solo lugar, utilizando técnicas avanzadas en el mismo entorno para realizar análisis complejos, recomendar películas, entender patrones de visualización y optimizar la calidad de transmisión sin la necesidad de mover constantemente datos entre un lago y un almacén._

### **Data Platform**
Es una infraestructura tecnológica que permite la recopilación, almacenamiento, gestión y análisis de datos procedentes de diversas fuentes para respaldar las operaciones comerciales y la toma de decisiones.

_Una plataforma de datos se asemeja a un panel de control central que reúne diversas herramientas y sistemas, permitiendo a los usuarios acceder, gestionar y analizar datos de manera efectiva, como un tabler único para múltiples funicones._

_Una plataforma de datos agiliza el proceso de recopilación, gestión y almacenamiento de datos, haciéndolos accesibles y utilizables para diversas aplicaciones. Proporciona gestión de datos en toda la extensión del entorno, incluyendo funciones críticas para el negocio como seguridad y observabilidad. Sin una plataforma de datos, cada componente suele ser manejado por una herramienta diferente o colección de herramientas para hacer que los datos fluyan desde la fuente hasta el usuario final en un entorno complejo._


### **Data Mesh**
Es un enfoque descentralizado de la arquitectura de datos que hace hincapié en la distribución de la propiedad, el acceso y la gobernanza de datos en diferentes dominios o unidades comerciales dentro de una organización.

_En términos sencillos, Data Mesh se asemeja a una red de bibliotecas locales autónomas, donde cada biblioteca gestiona y gobierna su colección de forma independiente, colaborando con otras para proporcionar una amplia gama de libros y recursos._

_Un enfoque de Data Mesh es una organización en la que las unidades comerciales o departamentos individuales gestionan y gobiernan sus propios conjuntos de datos, al mismo tiempo que colaboran a través de estándares e interfaces compartidos para permitir la utilización y análisis de datos interfuncionales._

### **Data Sharing**
Es el proceso de poner a disposición los mismos recursos de datos a múltiples aplicaciones, usuarios u organizaciones. Involucra tecnologías, prácticas, marcos legales y elementos culturales que facilitan el acceso seguro a los datos para múltiples entidades sin comprometer la integridad de los datos.

_El intercambio de datos mejora la eficiencia dentro de una organización y fomenta la colaboración con proveedores y socios. Permite a las partes interesadas aprender unas de otras y colaborar en prioridades compartidas._

_Los datos compartidos pueden varias, desde artículos de investigación o publicaciones académicas hasta estadísiticas corporativas, datos científicos o revisiones de desempeño anuales._


### **Data Product**
Es una aplicación o herramienta de software que utiliza datos para ofrecer conocimientos valiosos, servicios o funcionalidad a usuarios u otros sistemas.

_Es como una aplicación de smartphone que utiliza datos de ubicación para proporcionar recomendaciones personalizadas de restaurantes cercanos, ayudando a los usuarios a tomar decisiones informadas sobre dónde cenar._

_Un producto de datos es un panel de inteligencia empresarial que integra y visualiza datos de ventas, marketing y financieros para proporcionar conocimientos accionables a los tomadores de decisiones dentro de una organización._

### **Data Quality**
Abarca dimensiones como precisión, completitud, consistencia, confiabilidad y puntualidad. Involucra procesos y tecnologías que miden, gestionan y mejoran la salud de los datos. Mantener la calidad de los datos requiere vigilancia en las prácticas de gestión de datos y monitoreo continuo para detectar y corregir problemas.

_Piensa que haces un viaje por carretera usando un mapa. Si el mapa está actualizado, preciso y detallado, es probable que tengas un viaje sin problemas, pero si está desactualizado es posible que te pierdas o te retrases. Los datos de alta calidad son como un mapa preciso y actualizado para un negocio, lo que conduce a mejores decisiones y operaciones más eficientes._

### **Data Gathering**
Es el proceso de recopilación, compilación y captura de información de diversas fuentes. La recolección es esencial para adquirir la materia prima necesaria para el análisis, la interpretación y la toma de decisiones.

_Tan simple como llevar a cabo una encuesta para recopilar información sobre las preferencias de los clientes para un nuevo producto es un ejemplo de recolección de datos. Cuando alguien hace una encuesta puede analizar respuestas para obtener información sobre las necesidades y preferencias de los mismos._


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
