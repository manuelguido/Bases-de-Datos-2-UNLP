# Propuesta enseñanza 2025

## FUNDAMENTACIÓN

El objetivo de esta materia es presentar a los estudiantes diferentes alternativas para la persistencia de datos generados y administrados por sistemas desarrollados con el paradigma orientado a objetos. El abordaje de los temas planteados de la materia plantea una evolución desde los sistemas tradicionales hacia las nuevas tecnologías con el fin de lograr generar criterios generales que permitan realizar evaluaciones de los diferentes requerimientos impuestos por los problemas de la vida real, y por sobre todo la aplicabilidad de una solución informática que se ajuste, no sólo como solución desde el punto de vista técnico sino también incluyendo aspectos tales como la planificación de su incorporación, puesta en producción, mantenimiento futuro. Para ello se analizan las ventajas, desventajas y escenarios más comunes para la aplicación de las diferentes tecnologías actuales, desde bases de datos relacionales con soluciones de mapeo, bases de datos orientadas a objetos, bases de datos NOSQL hasta las más recientes basadas en computación en la nube.

## OBJETIVOS GENERALES

Completar el estudio de los temas básicos de BD, desarrollados en Introducción a las BD y Bases de Datos 1, abarcando aspectos de BD orientadas a objetos y lenguajes de operación de BDOO, utilización de diferentes alternativas de mapeo objeto-relacional. Se incluye además el estudio de otros mecanismos de persistencia no tradicional como las bases de datos NOSQL y su aplicabilidad a problemas habituales. Sumar aspectos de Data Warehousing y Data mining. Como también abordar aplicaciones tales como las BD para GIS. Dotar a los estudiantes de criterios que les permitan afrontar las diferentes etapas de un proyecto tendiente al diseño, implementación y posterior puesta en producción de soluciones de software de persistencia de información.

## RESULTADOS DE APRENDIZAJE

3.3. Elegir y utilizar modelos de proceso adecuados, entornos de programación y técnicas de gestión de datos con respecto a proyectos que impliquen aplicaciones tradicionales, así como aplicaciones emergentes (Adecuado).

## COMPETENCIAS

-   CGS6- Capacidad para interpretar la evolución de la informática con una visión de las tendencias tecnológicas futuras.
-   CGT1- Identificar, formular y resolver problemas de Informática.
-   CGT5- Utilizar de manera efectiva las técnicas y herramientas de aplicación de la Informática.
-   LS-CE1- Planificar, dirigir, realizar y/o evaluar proyectos de relevamiento de problemas del mundo real. Especificación formal, diseño, implementación, prueba, verificación, validación, mantenimiento y control de calidad de sistemas de software que se ejecuten sobre sistemas de procesamiento de datos, con capacidad de incorporación de tecnologías emergentes del cambio tecnológico. Capacidad de análisis, diseño y evaluación de interfases humano computador y computadorcomputador.
-   LS-CE9- Analizar y evaluar proyectos de especificación, diseño, implementación, puesta a punto, mantenimiento y actualización de sistemas de procesamiento de datos, con capacidad de incorporación de tecnologías emergentes del cambio tecnológico.

## CONTENIDOS MINIMOS (de acuerdo al Plan de Estudios)

-   Bases de datos orientadas a objetos.
-   Lenguajes de consulta orientados a objetos.
-   Bases de datos XML
-   Bases de datos NOSQL / Introducción a Cloud Computing
-   Conceptos de GIS.
-   Conceptos de Data Warehousing.
-   Conceptos de Minería de Datos

## PROGRAMA ANALÍTICO

### Bases de datos orientadas a objetos

-   Diferencias con el modelo relacional
-   Definición de: esquema, identificador, relación
-   Composición de objetos
-   OQL
-   Modificación de esquema
-   Versionamiento de objetos

El tema de las bases de datos orientadas a objetos se introduce mediante comparaciones de distintos escenarios utilizando como punto de partida las bases de datos relacionales y definiendo una posible evolución de los diferentes conceptos que existen en ambos paradigmas. Se discuten los principales conceptos de las bases de datos orientadas a objetos, como identificador, clase, instancia, persistencia por alcance y versionamiento de instancias.

### JDO

-   Introducción
-   Principales componentes
-   Arquitectura
-   Ejemplos de persistencia simple
-   Archivos de meta-data
-   Consultas a través de JDOQL

Teniendo en cuenta que el mercado suele presentar una variedad de productos y estándares y con el fin de que los estudiantes puedan aplicar los conocimientos en distintos productos se presenta el estándar JDO. Se discute la forma de trabajo bajo este estándar y se presentan detalles de la arquitectura de la solución, enfocándose en cómo este estándar mejora los aspectos relacionados con la calidad del software de persistencia de información y por lo tanto incrementa las posibilidades de realizar una etapa de mantenimiento tanto evolutivo como correctivo. Se analizan brevemente los principales componentes de algunas implementaciones. El estándar se utiliza en múltiples ejemplos a fin de afianzar su aplicación.

### Mapeo Objeto/Relacional

-   Principios y Buenas Prácticas del mapeo objeto/relacional
-   Estrategias de mapeo objeto/relacional
-   Archivos de configuración y anotacio

Teniendo en cuenta que la mayoría de las aplicaciones continúan desarrollándose con tecnología relacional, se presentan los conceptos requeridos para persistir objetos en bases de datos relacionales a través de mapeadores.

### Bases de datos NOSQL

-   Desventajas de las tecnologías tradicionales
-   Infraestructura y escalabilidad en bases de datos NOSQL
-   Diferentes alternativas para seleccionar una base de datos NOSQL (basadas en clave/valor, basadas en documentos, etc.).
-   Bases de Datos Orientadas a Documentos - Ejemplos con MongoDB.
-   Bases de Datos Clave-Valor - Ejemplos con Redis.

### Data Warehousing- Minería de Datos

-   Aspectos generales
-   Ventajas y desventajas
-   Ejemplos

### Conceptos de GIS

-   Diferencias con otro tipo de aplicaciones
-   Formas de representación
-   Soporte en BBDD Relacionales y NoSQL para las diferentes formas de representación

### Framework Spring

-   Inyección de dependencias
-   SpringBoot
-   Spring Data
-   Spring Repositories

## BIBLIOGRAFÍA

-   Bazzocco, J. (2012). Persistencia orientada a objetos. La Plata, Argentina: Universidad Nacional de La Plata
-   Chaudhri, A. B., & Loomis, M. (1998). Object databases in practice. Prentice-Hall, Inc.
-   Chen, J. K., & Lee, W. Z. (2019). An Introduction of NoSQL Databases based on their categories and application industries. Algorithms, 12(5), 106.
-   Dittrich, K. R., Dayal, U., & Buchmann, A. P. (Eds.). (2012). On object-oriented database systems. Springer Science & Business Media.
-   Güting, R. H., & Schneider, M. (2005). Moving objects databases. Elsevier.
-   Harrington, J. L. (2000). Object-oriented database design clearly explained. Morgan Kaufmann.
-   Kim, W. (1995). Modern database systems: the object model, interoperability, and beyond. ACM Press/Addison-Wesley Publishing Co.
-   Özsu, M. T., & Valduriez, P. (2020). NoSQL, NewSQL, and Polystores. In Principles of Distributed Database Systems (pp. 519-557). Springer, Cham.
-   Prabhu, C. S. R. (2004). Object oriented database systems. Prentice-Hall of India Pvt. Ltd.
-   Sadalage, P. & Fowler M. (2012) NoSQL Distilled: A Brief Guide to the Emerging World of Polyglot Persistence. Addison-Wesley Professional
-   Venkatraman, S., Fahd, K., Kaspi, S., & Venkatraman, R. (2016). SQL versus NoSQL movement with big data analytics. Int. J. Inform. Technol. Comput. Sci, 8, 59-66.
