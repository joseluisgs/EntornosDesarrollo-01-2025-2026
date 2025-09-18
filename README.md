# Entornos de Desarrollo - 01 - Desarrollo de Software
Tema 01. Desarrollo de Software. 1DAW. Curso 2025-2026.

![imagen](https://raw.githubusercontent.com/joseluisgs/EntornosDesarrollo-00-2022-2023/master/images/entornos.png)

- [Entornos de Desarrollo - 01 - Desarrollo de Software](#entornos-de-desarrollo---01---desarrollo-de-software)
- [Contenido en Youtube](#contenido-en-youtube)
  - [1. Introducción al Desarrollo de Software](#1-introducción-al-desarrollo-de-software)
    - [1.2 La Importancia del Proceso de Desarrollo](#12-la-importancia-del-proceso-de-desarrollo)
  - [2. Conceptos Fundamentales: Software y Hardware](#2-conceptos-fundamentales-software-y-hardware)
    - [2.1. ¿Qué es el Software?](#21-qué-es-el-software)
    - [2.2. ¿Qué es el Hardware?](#22-qué-es-el-hardware)
    - [2.3. Relación Hardware-Software](#23-relación-hardware-software)
  - [3. El Ciclo de Vida del Desarrollo de Software (Fases)](#3-el-ciclo-de-vida-del-desarrollo-de-software-fases)
    - [3.1. Concepto de Ciclo de Vida del Software](#31-concepto-de-ciclo-de-vida-del-software)
    - [3.2. Fases Principales del Desarrollo de una Aplicación Informática](#32-fases-principales-del-desarrollo-de-una-aplicación-informática)
      - [3.2.1. Fase Inicial (Planificación)](#321-fase-inicial-planificación)
      - [3.2.2. Análisis (Etapa de Análisis)](#322-análisis-etapa-de-análisis)
      - [3.2.3. Diseño](#323-diseño)
      - [3.2.4. Codificación (Implementación)](#324-codificación-implementación)
      - [3.2.5. Pruebas](#325-pruebas)
      - [3.2.6. Documentación](#326-documentación)
      - [3.2.7. Explotación (Despliegue)](#327-explotación-despliegue)
      - [3.2.8. Mantenimiento](#328-mantenimiento)
      - [3.2.9. Retirada del Software](#329-retirada-del-software)
  - [4. Modelos y Metodologías de Desarrollo de Software](#4-modelos-y-metodologías-de-desarrollo-de-software)
    - [4.1. Modelos Clásicos (Predictivos)](#41-modelos-clásicos-predictivos)
      - [4.1.1. Modelo en Cascada](#411-modelo-en-cascada)
      - [4.1.2. Modelo en V](#412-modelo-en-v)
    - [4.2. Modelo de Construcción de Prototipos](#42-modelo-de-construcción-de-prototipos)
    - [4.3. Modelos Evolutivos o Incrementales](#43-modelos-evolutivos-o-incrementales)
    - [4.4. Metodologías Ágiles (Adaptativas)](#44-metodologías-ágiles-adaptativas)
      - [4.4.1. Manifiesto Ágil](#441-manifiesto-ágil)
      - [4.4.2. Kanban](#442-kanban)
      - [4.4.3. Scrum](#443-scrum)
      - [4.4.4. XP (eXtreme Programming)](#444-xp-extreme-programming)
  - [5. Lenguajes de Programación](#5-lenguajes-de-programación)
    - [5.1. ¿Qué es un Lenguaje de Programación?](#51-qué-es-un-lenguaje-de-programación)
    - [5.2. Clasificación de Lenguajes de Programación](#52-clasificación-de-lenguajes-de-programación)
      - [5.2.1. Según su cercanía al lenguaje humano (Nivel de Abstracción)](#521-según-su-cercanía-al-lenguaje-humano-nivel-de-abstracción)
      - [5.2.2. Según su mecanismo de traducción (Compilados, Interpretados, Mixtos)](#522-según-su-mecanismo-de-traducción-compilados-interpretados-mixtos)
      - [5.2.3. Según su sistema de tipos (Tipado Fuerte, Tipado Débil)](#523-según-su-sistema-de-tipos-tipado-fuerte-tipado-débil)
        - [Rigidez: Tipado Fuerte vs. Tipado Débil](#rigidez-tipado-fuerte-vs-tipado-débil)
        - [Momento de Verificación: Tipado Estático vs. Tipado Dinámico](#momento-de-verificación-tipado-estático-vs-tipado-dinámico)
        - [Declaración: Tipado Explícito vs. Implícito (Inferencia)](#declaración-tipado-explícito-vs-implícito-inferencia)
        - [Lenguajes sin Tipado (Tipado Nulo)](#lenguajes-sin-tipado-tipado-nulo)
        - [Tabla Resumen de Sistemas de Tipado](#tabla-resumen-de-sistemas-de-tipado)
      - [5.2.4. Según la forma en que operan (Paradigmas de Programación)](#524-según-la-forma-en-que-operan-paradigmas-de-programación)
      - [5.2.5. Según Generaciones](#525-según-generaciones)
    - [5.3. Criterios para la Selección de un Lenguaje de Programación](#53-criterios-para-la-selección-de-un-lenguaje-de-programación)
    - [5.4. Lenguajes más Utilizados en la Actualidad](#54-lenguajes-más-utilizados-en-la-actualidad)
  - [6. Proceso de Traducción, Máquinas Virtuales y Entornos de Ejecución](#6-proceso-de-traducción-máquinas-virtuales-y-entornos-de-ejecución)
    - [6.1. Proceso de Traducción: Compilación e Interpretación](#61-proceso-de-traducción-compilación-e-interpretación)
      - [6.1.1. Diferenciación entre Traducción, Compilación e Interpretación](#611-diferenciación-entre-traducción-compilación-e-interpretación)
      - [6.1.2. Fases de un Traductor (Compilador/Intérprete)](#612-fases-de-un-traductor-compiladorintérprete)
        - [1. Análisis Léxico (Scanner)](#1-análisis-léxico-scanner)
        - [2. Análisis Sintáctico (Parser)](#2-análisis-sintáctico-parser)
        - [3. Análisis Semántico](#3-análisis-semántico)
        - [4. Generación de Código Intermedio](#4-generación-de-código-intermedio)
        - [5. Optimización de Código](#5-optimización-de-código)
        - [6. Generación de Código Objeto](#6-generación-de-código-objeto)
        - [7. Enlazador (Linker) y Cargador (Loader)](#7-enlazador-linker-y-cargador-loader)
    - [6.2. Códigos Fuente, Objeto y Ejecutable](#62-códigos-fuente-objeto-y-ejecutable)
    - [6.3. Máquinas Virtuales y Entornos de Ejecución](#63-máquinas-virtuales-y-entornos-de-ejecución)
      - [6.3.1. Concepto de Máquina Virtual](#631-concepto-de-máquina-virtual)
      - [6.3.2. Entornos de Ejecución (Runtime Environments)](#632-entornos-de-ejecución-runtime-environments)
      - [6.3.3. Frameworks](#633-frameworks)
  - [7. Herramientas de Apoyo al Desarrollo de Software](#7-herramientas-de-apoyo-al-desarrollo-de-software)
    - [7.1. Herramientas de Desarrollo](#71-herramientas-de-desarrollo)
    - [7.2. Herramientas CASE (Computer Aided Software Engineering)](#72-herramientas-case-computer-aided-software-engineering)
    - [7.3. Desarrollo Rápido de Aplicaciones (RAD)](#73-desarrollo-rápido-de-aplicaciones-rad)
    - [7.4. Entornos de Desarrollo Integrado (IDE)](#74-entornos-de-desarrollo-integrado-ide)
  - [8. Perfiles del Desarrollo de Software](#8-perfiles-del-desarrollo-de-software)
  - [9. Conclusión](#9-conclusión)
  - [Autor](#autor)
    - [Contacto](#contacto)
  - [Licencia de uso](#licencia-de-uso)


# Contenido en Youtube

- [Podcast](https://youtu.be/KybhDIWZj44)
- [Resumen](https://youtu.be/GDCJGR5XERA)
- [Análisis de Lenguajes](https://youtu.be/3NEh4kb9raU)
- [Lista de Reproducción](https://www.youtube.com/watch?v=VoamKywLez8&list=PLGIH-7eZDbVwCTLTEJ_yJJ3NWE0eKqqqH)



## 1. Introducción al Desarrollo de Software

###1.1 ¿Qué es el Desarrollo de Software?
El **Desarrollo de Software** abarca todo el proceso que ocurre desde que se concibe una idea hasta que un programa está implementado en el ordenador y funcionando. Es una disciplina que estudia los principios y metodologías para el desarrollo y mantenimiento de sistemas software. Algunos autores consideran que el término "desarrollo de software" es más apropiado que "ingeniería de software", ya que este último implica niveles de rigor y prueba de procesos que no son siempre adecuados para todo tipo de desarrollo de software. La **Ingeniería del software** se define como la ciencia y el arte de especificar, diseñar y desarrollar programas, documentación y procedimientos operativos.

### 1.2 La Importancia del Proceso de Desarrollo
El proceso de desarrollo, que al principio puede parecer una tarea simple, consta de una serie de pasos de obligado cumplimiento. Solo así se puede garantizar que los programas creados sean eficientes, fiables, seguros y respondan a las necesidades de los usuarios finales.


## 2. Conceptos Fundamentales: Software y Hardware

### 2.1. ¿Qué es el Software?
El **software** es la parte intangible o lógica de un sistema informático. Es el conjunto de programas informáticos que actúan sobre el hardware para ejecutar lo que el usuario desee. Se desarrolla para llevar a cabo una tarea determinada, se comunica con el hardware y le indica qué hacer, y se encarga de traducir las instrucciones de los usuarios.

Existen diferentes **tipos de software**:
*   **Software de Sistema**: Es el software base que debe estar instalado y configurado en el ordenador para que las aplicaciones puedan ejecutarse y funcionar. Incluye el sistema operativo (como Windows, Linux, Mac OS X) y los *drivers* o controladores de dispositivos.
*   **Software de Aplicación**: Es un conjunto de programas que tienen una finalidad más o menos concreta. Ejemplos incluyen suites ofimáticas, navegadores, editores de imagen, procesadores de textos, hojas de cálculo, reproductores de música o videojuegos.
*   **Software de Desarrollo (o de Programación)**: Es el conjunto de herramientas que permiten desarrollar programas informáticos. Esto incluye editores, compiladores, intérpretes, entre otros.

También podemos distinguir entre:
*   **Software a medida**: Se desarrolla según las especificaciones o requerimientos de una empresa u organismo, adaptándose a su actividad específica. Necesita tiempo de desarrollo, se adapta a necesidades concretas, puede contener errores iniciales y suele ser más costoso.
*   **Software estándar**: Es un software genérico válido para cualquier cliente potencial y resuelve múltiples necesidades, a menudo incluyendo herramientas de configuración. Se compra ya desarrollado, suele tener menos errores al ser más testeado y es más barato. Sin embargo, puede incluir funciones nunca usadas o carecer de opciones importantes.

### 2.2. ¿Qué es el Hardware?
El **hardware** es el conjunto de dispositivos físicos que conforman un ordenador. Los componentes principales del sistema informático incluyen:
*   **CPU (Unidad Central de Procesamiento)**: También llamada UCP (en inglés), procesador o microprocesador. Lee y ejecuta las instrucciones almacenadas en la memoria RAM, así como los datos necesarios.
*   **Memoria RAM**: Almacena de forma temporal el código binario de los archivos ejecutables y los archivos de datos necesarios para la ejecución del programa.
*   **Disco Duro**: Almacena de forma permanente los archivos ejecutables y los archivos de datos. Se considera un periférico de Entrada/Salida (E/S).
*   **Periféricos de Entrada/Salida (E/S)**: Recogen nuevos datos desde la entrada, muestran los resultados, leen o guardan datos en disco, etc..

### 2.3. Relación Hardware-Software
Existe una relación indisoluble entre hardware y software, ya que ambos necesitan estar instalados y configurados correctamente para que el equipo funcione. El software se ejecutará sobre los dispositivos físicos.

Esta relación se manifiesta desde dos puntos de vista:
*   **Desde el punto de vista del sistema operativo**: El **sistema operativo** es el encargado de coordinar el hardware durante el funcionamiento del ordenador, actuando como intermediario entre este y las aplicaciones que se están ejecutando. Todas las aplicaciones necesitan recursos hardware (tiempo de CPU, espacio en memoria RAM, tratamiento de interrupciones, gestión de dispositivos de E/S, etc.) durante su ejecución. El sistema operativo controla estos aspectos de manera "oculta" para las aplicaciones y el usuario.
*   **Desde el punto de vista de las aplicaciones**: Una aplicación es un conjunto de programas, escritos en algún lenguaje de programación. Mientras que los lenguajes de programación están diseñados para que los humanos puedan entenderlos y usarlos fácilmente, el hardware solo interpreta señales eléctricas (ausencias o presencias de tensión) que se traducen en secuencias de 0 y 1 (código binario). Esto implica que el código escrito en un lenguaje de programación debe pasar por un proceso de traducción para que el ordenador pueda entenderlo y ejecutarlo.

![img01](/images/sofrware_vs_hardware.png)


## 3. El Ciclo de Vida del Desarrollo de Software (Fases)

### 3.1. Concepto de Ciclo de Vida del Software
La serie de pasos a seguir para desarrollar un programa es lo que se conoce como **Ciclo de Vida del Software**. Cada etapa del ciclo de vida del software se explicará con más detalle, y el desarrollo de software es un proceso que conlleva una serie de pasos genéricos. Es un proceso que puede parecer muy complejo y que exige una gran coordinación y disciplina del grupo de trabajo que lo desarrolle.

### 3.2. Fases Principales del Desarrollo de una Aplicación Informática
Independientemente del modelo elegido, siempre hay una serie de etapas que se deben seguir para construir software fiable y de calidad. Las fases principales, comúnmente aceptadas, son:

![Diagrama: Fases del Desarrollo de Software](/images/fases_desarrollo.jpg)

#### 3.2.1. Fase Inicial (Planificación)
En esta fase se establecen los **objetivos** del proyecto, se define su **alcance** y se realiza un **estudio de viabilidad y costes**. Es la fase más compleja, que precisa de expertos en planificación de proyectos y donde se desarrollan documentos importantes como el de viabilidad y estimación.

#### 3.2.2. Análisis (Etapa de Análisis)
Esta es la primera fase y la de mayor importancia en el desarrollo del proyecto. Todo lo demás dependerá de lo bien detallada que esté, siendo también la más complicada ya que no está automatizada y depende en gran medida del analista que la realice.

En esta fase, se determina y define claramente las **necesidades del cliente** y se especifican los **requisitos** que debe cumplir el software a desarrollar. Lo fundamental es una buena comunicación entre el analista y el cliente para que la aplicación desarrollada cumpla con sus expectativas, es decir, necesitamos saber el "**qué**" hace nuestro software.

La **especificación de requisitos** debe:
*   Ser completa y sin omisiones.
*   Ser concisa y sin trivialidades.
*   Evitar ambigüedades, utilizando lenguaje formal.
*   Evitar detalles de diseño o implementación.
*   Ser entendible por el cliente.
*   Separar requisitos funcionales y no funcionales.
*   Dividir y jerarquizar el modelo.
*   Fijar criterios de validación.

Tipos de Requisitos a especificar:
*   **Requisitos Funcionales**: Definen qué funciones tendrá que realizar la aplicación. Responden a preguntas como qué respuesta dará la aplicación ante todas las entradas o cómo se comportará en situaciones inesperadas. Por ejemplo, en una aplicación de cosmética, podría ser si desea que la lectura de productos se haga mediante códigos de barras, cómo se detallan las facturas, si se controlará el stock o si se operará con tarjetas de crédito.
*   **Requisitos No Funcionales**: Definen las características de calidad del sistema. Incluyen tiempos de respuesta del programa, legislación aplicable, tratamiento ante la simultaneidad de peticiones, etc..
*   **Requisitos de Información** (Información no provista directamente en las fuentes, se basa en conocimiento general del área): Detallan qué información se ofrecerá como salida y qué datos son necesarios como entrada para resolver el problema.

La culminación de esta fase es el documento de **Especificación de Requisitos del Software (ERS)**, que actúa como un contrato entre el cliente y el desarrollador. Este documento especifica la planificación de reuniones, los objetivos del usuario y del sistema, la relación de requisitos funcionales y no funcionales, los objetivos prioritarios y la temporización, y el reconocimiento de requisitos mal planteados o contradictorios. No detectar o entender mal los requisitos en esta etapa puede provocar un fuerte impacto negativo en todo el proceso de desarrollo.


#### 3.2.3. Diseño
Durante esta fase, una vez que ya se sabe "qué" hay que hacer, el siguiente paso es definir "**cómo**" hacerlo. Se descompone y organiza el sistema en elementos componentes que pueden ser desarrollados por separado, especificando su interrelación y funcionalidad.

Las actividades habituales incluyen el diseño arquitectónico, el diseño detallado, el diseño de datos y el diseño de la interfaz de usuario. En este punto, se deben tomar decisiones importantes como las entidades y relaciones de las bases de datos, la selección del lenguaje de programación y la elección del Sistema Gestor de Base de Datos (SGBD). Los documentos generados son más técnicos. El resultado tras el diseño arquitectónico es el **Documento de arquitectura del software**, y tras el diseño detallado, la **Especificación de módulos y funciones**.


#### 3.2.4. Codificación (Implementación)
Esta etapa consiste en transformar o traducir los resultados obtenidos a un determinado lenguaje de programación. Se escribe el código fuente de cada componente, traduciendo los algoritmos definidos en la fase de diseño. Esta tarea la realiza el programador y debe cumplir exhaustivamente con los datos impuestos en el análisis y diseño.

Las características deseables de todo código son:
1.  **Modularidad**: Dividido en trozos pequeños.
2.  **Corrección**: Que haga lo que se le pide.
3.  **Facilidad de lectura**: Para facilitar su desarrollo y mantenimiento futuro.
4.  **Eficiencia**: Que haga un buen uso de los recursos.
5.  **Portabilidad**: Que se pueda implementar en cualquier equipo.

Durante esta fase, el código pasa por diferentes estados (código fuente, objeto, ejecutable). El resultado de esta fase es el **Código fuente**.

#### 3.2.5. Pruebas
El principal objetivo de las **pruebas** es conseguir que el programa funcione incorrectamente para descubrir y corregir defectos. El programa debe ser sometido al máximo número de situaciones diferentes. Las pruebas son imprescindibles para asegurar la validación y verificación del software construido.

Entre los tipos de pruebas se distinguen:
*   **Pruebas Unitarias**: Prueban, una a una, las diferentes partes del software y comprueban su funcionamiento por separado.
*   **Pruebas de Integración**: Se realizan una vez que las pruebas unitarias han sido exitosas, comprobando el funcionamiento del sistema completo con todas sus partes interrelacionadas.
*   **Pruebas Funcionales**: Validan que la aplicación hace lo que tiene que hacer, a menudo con la participación del cliente.
*   **Pruebas Estructurales**: Pruebas técnicas sobre el sistema (estrés, carga, integración, etc.).
*   **Beta Test**: La prueba final que se realiza sobre el entorno de producción, en el entorno real del cliente y bajo un funcionamiento normal de su empresa.

Los resultados de las pruebas de unidades son **Módulos utilizables**, y de las pruebas de integración, un **Sistema utilizable**. Las pruebas del sistema culminan con un **Sistema aceptado**.

#### 3.2.6. Documentación
La **documentación** es vital para el desarrollo y mantenimiento del software. Todas las etapas en el desarrollo de software deben quedar perfectamente documentadas. Una correcta documentación permitirá la reutilización de parte de los programas en otras aplicaciones, especialmente si se desarrollan con diseño modular.

Se distinguen tres grandes tipos de documentos:
*   **Guía Técnica (o Manual Técnico)**: Dirigida al personal técnico (analistas y programadores). Refleja el diseño, la codificación de los programas y las pruebas realizadas. Su objetivo es facilitar el desarrollo, las correcciones y el mantenimiento futuro.
*   **Guía de Uso (o Manual de Usuario)**: Dirigida a los usuarios finales (clientes). Describe la funcionalidad de la aplicación, cómo empezar a ejecutarla y ejemplos de uso. Su objetivo es dar a los usuarios toda la información necesaria para utilizar la aplicación.
*   **Guía de Instalación (o Manual de Instalación)**: Dirigida al personal informático responsable de la instalación. Detalla los requerimientos software de la aplicación y la solución a posibles problemas. Su objetivo es garantizar una implantación segura, confiable y precisa.

El resultado final es la **Documentación técnica y de usuario**.

#### 3.2.7. Explotación (Despliegue)
La **explotación** es la fase en que los usuarios finales conocen la aplicación y comienzan a utilizarla. Implica la instalación, puesta a punto y funcionamiento de la aplicación en el equipo final del cliente. En esta fase, los programas son transferidos al computador del usuario, configurados y verificados. Es recomendable que los clientes estén presentes durante la instalación. También se pueden llevar a cabo las Beta Test en los equipos del cliente bajo cargas normales de trabajo. La configuración puede ser realizada por los propios usuarios con la guía de instalación o programarse automáticamente si el software es sencillo. Es un momento crítico del proyecto tenerlo todo preparado antes de la presentación al cliente.

#### 3.2.8. Mantenimiento
La etapa de **mantenimiento** es la más larga de todo el ciclo de vida del software. Por su naturaleza, el software es cambiante y deberá actualizarse y evolucionar con el tiempo, adaptándose a mejoras de hardware y nuevas situaciones. Siempre surgen errores y la necesidad de nuevas versiones. El mantenimiento se define como el proceso de control, mejora y optimización del software.

Los **tipos de mantenimiento** incluyen:
*   **Correctivo**: Para corregir defectos o fallos encontrados en el software.
*   **Perfectivo**: Para mejorar la funcionalidad existente del software.
*   **Evolutivo**: Para añadir nuevas funcionalidades solicitadas por el cliente o expansiones de código.
*   **Adaptativo**: Para ajustar el software a nuevos entornos, tendencias del mercado o componentes hardware.

Los resultados del mantenimiento son **Informes de errores y control de cambios**.

#### 3.2.9. Retirada del Software
Esta fase ocurre cuando el software ha llegado al **final de su vida útil** y ya no resulta rentable seguir ampliándolo o manteniéndolo. En este punto, el ciclo puede comenzar de nuevo, ya sea comprando un nuevo software o desarrollando uno a medida.


## 4. Modelos y Metodologías de Desarrollo de Software

Siempre se debe aplicar un modelo de ciclo de vida al desarrollo de cualquier proyecto software. Estos modelos son la serie de pasos a seguir para desarrollar un programa.

### 4.1. Modelos Clásicos (Predictivos)
Los modelos clásicos son más rígidos.

#### 4.1.1. Modelo en Cascada
Es el modelo de desarrollo de software de mayor antigüedad. Identifica las fases principales del desarrollo de software y establece que las fases deben realizarse en el orden indicado, siendo el resultado de una fase la entrada de la siguiente. Es un modelo secuencial y lineal. Es un modelo bastante rígido que se adapta mal al cambio continuo de especificaciones. Es prácticamente imposible que se pueda utilizar, ya que requiere conocer de antemano todos los requisitos del sistema. Solo es aplicable a pequeños desarrollos, ya que las etapas pasan de una a otra sin retorno posible. Cualquier error detectado en una fase muy tardía implica sobrecoste y desperdicios.

*   **Modelo en Cascada con Realimentación**: Es una variante del modelo en cascada que introduce una realimentación entre etapas. Esto permite volver atrás en cualquier momento para corregir, modificar o depurar algún aspecto. Es el modelo perfecto si el proyecto es rígido (pocos cambios, poco evolutivo) y los requisitos están claros, aunque no es el más idóneo si se prevén muchos cambios.

![Diagrama: Modelo en Cascada](/images/fases_desarrollo.jpg)

#### 4.1.2. Modelo en V
Es un modelo muy parecido al modelo en cascada. Presenta una visión jerarquizada con distintos niveles, donde los superiores indican mayor abstracción y los inferiores mayor nivel de detalle. El resultado de una fase es la entrada de la siguiente.

![Diagrama: Modelo en V](/images/modelo_v.jpeg)

### 4.2. Modelo de Construcción de Prototipos
Se utiliza a menudo cuando los requisitos no están especificados claramente, ya sea por falta de experiencia previa o por omisión/falta de concreción del usuario/cliente. El proceso implica crear un prototipo durante la fase de análisis, que es probado por el usuario/cliente para refinar los requisitos del software a desarrollar. Este paso se repite las veces necesarias.

Existen dos tipos de prototipos:
*   **Prototipos rápidos**: El prototipo puede desarrollarse usando otro lenguaje o herramientas y finalmente se desecha.
*   **Prototipos evolutivos**: El prototipo está diseñado en el mismo lenguaje y herramientas del proyecto y se usa como base para desarrollar el proyecto.

![Diagrama: Modelo de Prototipos](/images/modelo_prototipos.webp)

### 4.3. Modelos Evolutivos o Incrementales
Son modelos más modernos que los clásicos y tienen en cuenta la naturaleza cambiante y evolutiva del software. La idea es desarrollar una implementación inicial del sistema, exponerla a los comentarios del usuario y refinarla en sucesivas versiones hasta obtener el sistema adecuado. Permiten una rápida realimentación del usuario, ya que las actividades de especificación, desarrollo y pruebas se ejecutan en cada iteración.

Distinguimos dos variantes:
*   **Modelo Iterativo Incremental**: Está basado en el modelo en cascada con realimentación, donde las fases se repiten y refinan, propagando su mejora a las fases siguientes.
*   **Modelo en Espiral**: Desarrollado por Boehm en 1988, es una combinación del modelo iterativo incremental con el modelo en cascada. El software se construye repetidamente en forma de versiones que son cada vez mejores, incrementando la funcionalidad en cada versión. Este modelo también se centra en la gestión de riesgos en cada fase del proceso de desarrollo. Es un modelo bastante complejo.
    Las cuatro fases principales son:
    1.  **Determinación de objetivos**: Identificar objetivos para la iteración actual (nuevas características, mejoras, corrección de errores).
    2.  **Análisis de riesgos**: Identificar y evaluar riesgos potenciales (técnicos, de gestión).
    3.  **Desarrollo y validación**: Desarrollar y probar el software, incluyendo prototipos e implementación.
    4.  **Planificación**: Revisar el proyecto y planificar la próxima iteración.

![Diagrama: Modelo en Espiral](/images/modelo_espiral.png)

### 4.4. Metodologías Ágiles (Adaptativas)
Las **metodologías ágiles** son un conjunto de metodologías de desarrollo de software basadas en el desarrollo iterativo e incremental. Los requisitos y soluciones evolucionan con el tiempo según la necesidad del proyecto. Promueven el trabajo en equipo, la colaboración con el cliente y la adaptación al cambio. Los equipos se autoorganizan y son multidisciplinares, inmersos en un proceso compartido de toma de decisiones a corto plazo.

#### 4.4.1. Manifiesto Ágil
Todos los equipos de desarrollo ágil deben seguir los cuatro valores y los doce principios del Manifiesto Ágil. Los cuatro valores son:
*   **Individuos e interacciones** sobre procesos y herramientas.
*   **Software funcionando** sobre documentación extensiva.
*   **Colaboración con el cliente** sobre negociación contractual.
*   **Respuesta ante el cambio** sobre seguir un plan.

#### 4.4.2. Kanban
También conocido como "sistema de tarjetas", fue desarrollado inicialmente por Toyota para la industria de fabricación de productos. Controla por demanda la fabricación de los productos necesarios en la cantidad y tiempo justos. Está enfocado a entregar el máximo valor para los clientes, utilizando los recursos justos. Se basa en el *Lean manufacturing*.

![Diagrama: Proceso Kanban](/images/modelo_kanban.webp)

#### 4.4.3. Scrum
Es un modelo de desarrollo incremental. Utiliza **iteraciones (sprint)** regulares, que suelen durar entre 2 y 4 semanas. Al principio de cada iteración se establecen sus **objetivos priorizados (sprint backlog)**. Al finalizar cada iteración se obtiene una **entrega parcial utilizable por el cliente**. Existen reuniones diarias para tratar la marcha del *sprint*.

![Diagrama: Proceso Scrum](/images/modelo_scrum.webp)

#### 4.4.4. XP (eXtreme Programming)
Se basa en los siguientes **valores**:
*   Simplicidad
*   Comunicación
*   Retroalimentación
*   Valentía o coraje
*   Respeto o humildad

Sus **características** incluyen:
*   Diseño sencillo.
*   Pequeñas mejoras continuas.
*   Pruebas y refactorización.
*   Integración continua.
*   **Programación por parejas**.
*   **El cliente se integra en el equipo de desarrollo**.
*   Propiedad del código compartida.
*   Estándares de codificación.
*   Trabajo de 40 horas semanales.

![Diagrama: Proceso XP](/images/modelo_tradicional_agil.png)


## 5. Lenguajes de Programación

### 5.1. ¿Qué es un Lenguaje de Programación?
Un **lenguaje de programación** es un idioma creado de forma artificial, formado por un conjunto de símbolos y normas que se aplican sobre un alfabeto para obtener un código que el hardware de la computadora pueda entender y ejecutar. Son los instrumentos que tenemos para que el ordenador realice las tareas que necesitamos. Es un lenguaje formal que proporciona un conjunto de instrucciones que permiten a un programador escribir secuencias de comandos, que son interpretadas por una máquina, para producir un comportamiento deseado.

Los elementos que componen un lenguaje de programación son:
*   **Alfabeto (Léxico)**: Es el conjunto finito de símbolos permitidos y palabras especiales, el vocabulario del lenguaje.
*   **Sintaxis**: Son las normas de construcción permitidas de los símbolos y palabras del lenguaje. Se refiere a las reglas que rigen la estructura de las declaraciones y expresiones válidas.
*   **Semántica**: Es el significado de las construcciones. Define las acciones que se llevarán a cabo con las combinaciones de los símbolos.

Otros elementos importantes incluyen:
*   **Tipos de Datos**: Los diferentes tipos de valores que pueden ser representados y manipulados (enteros, flotantes, caracteres, cadenas, booleanos). Definen el conjunto de valores válidos y las operaciones permitidas para ellos, así como el **espacio de memoria** que ocupan.
*   **Variables**: Símbolos que representan valores en el programa y tienen tipos asociados.
*   **Operadores**: Símbolos que representan operaciones específicas (por ejemplo, `+` para adición, `==` para comparación).
*   **Control de Flujo**: Estructuras que determinan el orden de ejecución de las instrucciones (condicionales como `if`, `switch`; bucles como `for`, `while`).
*   **Subrutinas y Funciones**: Bloques de código que pueden ser definidos y llamados por nombre, permitiendo la reutilización y modularidad.
*   **Comentarios**: Notas que los programadores dejan en el código para explicar su funcionamiento, no son ejecutados.

![Diagrama: Elementos de un Lenguaje de Programación](/images/componentes_lenguaje.jpg)

### 5.2. Clasificación de Lenguajes de Programación

#### 5.2.1. Según su cercanía al lenguaje humano (Nivel de Abstracción)
Los lenguajes han evolucionado siempre hacia una mayor usabilidad y cercanía al razonamiento humano.

*   **Lenguajes de Bajo Nivel**: Son lenguajes totalmente dependientes de la máquina, lo que significa que un programa desarrollado en ellos no puede ser migrado o utilizado en otras máquinas. Aprovechan al máximo las características del hardware.
    *   **Lenguaje Máquina**: Sus instrucciones son combinaciones de unos y ceros (código binario). Es el único lenguaje que el ordenador entiende directamente (no necesita traducción). Fue el primer lenguaje utilizado y es único para cada procesador (no portable). Es rápido, pero difícil de manejar, con códigos fuente enormes y detección de fallos casi imposible. Hoy día nadie programa en este lenguaje.
    *   **Lenguaje Ensamblador**: Sustituyó al lenguaje máquina, utilizando mnemotécnicos (instrucciones complejas) en lugar de unos y ceros. Necesita traducción al lenguaje máquina para ejecutarse. Sus instrucciones hacen referencia a la ubicación física de los archivos en el equipo. Es difícil de utilizar. Como ventaja frente al código máquina, los códigos fuente eran más cortos y ocupaban menos memoria.
*   **Lenguajes de Medio Nivel**: Este término no es universalmente aceptado, pero se refiere a lenguajes que se encuentran en un punto medio. Pueden acceder a los registros del sistema y trabajar con direcciones de memoria (características de bajo nivel), y a la vez realizar operaciones de alto nivel. Un ejemplo es C.
*   **Lenguajes de Alto Nivel**: Se encuentran más cercanos al lenguaje natural que al lenguaje máquina, y son independientes de la arquitectura del ordenador. Permiten al programador olvidarse del funcionamiento interno de la máquina. Utilizan sentencias y órdenes derivadas del idioma inglés. Necesitan un traductor para ser entendidos por la máquina. Incorporan librerías y funciones predeterminadas, y suelen ofrecer *frameworks*. La mayoría de los lenguajes de programación actuales se engloban en esta categoría. Ejemplos incluyen C++, Java, Python, JavaScript, PHP.

![Diagrama: Clasificación de Lenguajes por Nivel](/images/lenguajes_cercania.png)

#### 5.2.2. Según su mecanismo de traducción (Compilados, Interpretados, Mixtos)
La obtención de código binario ejecutable se realiza mediante compilación o interpretación.

*   **Lenguajes Compilados**: Necesitan un **compilador** que traduce el código fuente a código binario (código objeto) en un solo paso. Se ejecutan muy eficientemente. La principal desventaja es que es necesario compilar cada vez que el código fuente es modificado. Precisan de un programa enlazador (*linker*) que une el código objeto con el código objeto de librerías. El código es más seguro, ya que el código fuente no es directamente accesible. Ejemplos incluyen C y C++.
*   **Lenguajes Interpretados**: No generan código objeto. El código fuente se interpreta directamente, línea a línea, y se ejecuta simultáneamente. Esto se realiza mediante un programa auxiliar llamado **intérprete**, que debe estar cargado en memoria. La ejecución es menos eficiente que los compilados. La ventaja es que el código fuente se interpreta directamente sin un paso de compilación explícito a código objeto. La detección de errores es más detallada. La principal desventaja es que el código fuente es legible, lo que puede comprometer la seguridad o los derechos de autor. Ejemplos incluyen PHP y JavaScript.
*   **Lenguajes Mixtos o Virtuales**: Combinan características de ambos. El código fuente se compila a un código binario intermedio denominado **bytecode**. Este bytecode puede considerarse código objeto, pero está destinado a una **máquina virtual** en lugar de a código objeto nativo. Luego, este bytecode se interpreta para ejecutarlo en cualquier máquina virtual compatible. Son más portables que los lenguajes compilados. El objetivo es compilar una vez y ejecutar en distintos sistemas. Ejemplos incluyen Java, C# o Python.

![Diagrama: Clasificación de Lenguajes por Traducción](/images/lenguajes_compialdos_interpretados.jpg)

#### 5.2.3. Según su sistema de tipos (Tipado Fuerte, Tipado Débil)

Un **tipo de dato** es una clasificación que define el conjunto de valores que una variable puede tomar y las operaciones válidas que se pueden realizar sobre esos valores. Esta clasificación es fundamental porque **determina la cantidad de memoria que el sistema operativo debe reservar** para la variable. Por ejemplo, una variable de tipo `int` ocupará menos espacio que una de tipo `float` porque su rango de valores es menor.

El **sistema de tipos** de un lenguaje de programación es un conjunto de reglas que definen cómo se manejan y verifican estos tipos de datos. La clasificación de estos sistemas se basa en tres dimensiones principales: la rigidez, el momento de verificación y la declaración.

##### Rigidez: Tipado Fuerte vs. Tipado Débil

Esta dimensión se refiere a la flexibilidad con la que un lenguaje maneja las conversiones entre tipos de datos.

* **Lenguajes de Tipado Fuerte**: Requieren que los tipos de datos sean compatibles para realizar operaciones. No permiten conversiones automáticas o "implícitas" entre tipos no relacionados. Si intentas sumar un número y una cadena de texto, el lenguaje lo marcará como un error, lo que previene errores inesperados en tiempo de ejecución y hace el código más robusto.
    * **Ejemplos**: Python, Java, C#, Ruby.
* **Lenguajes de Tipado Débil**: Permiten conversiones de tipo automáticas. El lenguaje puede intentar convertir un tipo de dato a otro sin que el programador lo solicite explícitamente. Esta flexibilidad puede llevar a errores que son difíciles de detectar.
    * **Ejemplos**: JavaScript, PHP, VBScript.

##### Momento de Verificación: Tipado Estático vs. Tipado Dinámico

Esta dimensión se basa en el momento en que se realiza la verificación de los tipos de datos.

* **Lenguajes de Tipado Estático**: La verificación de tipos se realiza en **tiempo de compilación**. El tipo de cada variable debe ser conocido y, a menudo, declarado explícitamente antes de ejecutar el programa. Si hay un error de tipo, el programa no compilará. Esto garantiza mayor seguridad y rendimiento.
    * **Ejemplos**: C++, Java, C#, Swift.
* **Lenguajes de Tipado Dinámico**: La verificación de tipos se realiza en **tiempo de ejecución**. No es necesario declarar el tipo de una variable de forma explícita; el intérprete lo determina automáticamente. Una misma variable puede cambiar de tipo durante la ejecución. Esto ofrece gran flexibilidad, pero los errores de tipo solo se descubren al ejecutar el código.
    * **Ejemplos**: Python, JavaScript, Ruby, PHP.


##### Declaración: Tipado Explícito vs. Implícito (Inferencia)

Esta dimensión se refiere a la forma en que el programador indica el tipo de una variable.

* **Tipado Explícito**: Requiere que el programador declare manualmente el tipo de cada variable. Esto hace el código más claro y fácil de leer, ya que el tipo está siempre a la vista.
    * **Ejemplo**: En C++: `int numero = 10;`.
* **Tipado Implícito (Inferencia de Tipos)**: El compilador o intérprete infiere el tipo de la variable a partir del valor asignado, sin que el programador tenga que declararlo. Esta característica hace que el código sea más conciso y rápido de escribir. La inferencia de tipos es muy común en lenguajes con tipado estático modernos.
    * **Ejemplo**: En Python: `numero = 10;` (el intérprete infiere que `numero` es de tipo `int`).

##### Lenguajes sin Tipado (Tipado Nulo)

En algunos lenguajes de muy bajo nivel, como el **lenguaje de ensamblador**, no existe un sistema de tipos formal. Todas las variables se manejan como una simple secuencia de bits, y es responsabilidad total del programador interpretar los datos.

##### Tabla Resumen de Sistemas de Tipado

La combinación de estas tres dimensiones define el sistema de tipos de un lenguaje.

| Sistema de Tipado     | Descripción                                                       | Ejemplos de Lenguajes           |
| :-------------------- | :---------------------------------------------------------------- | :------------------------------ |
| **Estático y Fuerte** | Tipos verificados en compilación; no hay conversiones implícitas. | C++, Java, C#                   |
| **Dinámico y Fuerte** | Tipos verificados en ejecución; no hay conversiones implícitas.   | Python, Ruby                    |
| **Estático y Débil**  | Tipos verificados en compilación; sí hay conversiones implícitas. | C, VBScript (algunos dialectos) |
| **Dinámico y Débil**  | Tipos verificados en ejecución; sí hay conversiones implícitas.   | JavaScript, PHP                 |

#### 5.2.4. Según la forma en que operan (Paradigmas de Programación)
Un **paradigma de programación** es un modelo fundamental para el diseño y la implementación de programas, que determina la estructura y el enfoque del código. La mayoría de los lenguajes de programación modernos, como **Java**, **Kotlin** y **C#**, son multiparadigma, lo que significa que combinan características de varios de ellos para ofrecer mayor flexibilidad y poder a los desarrolladores.

Los principales paradigmas de programación son:

* **Programación Imperativa/Estructurada**: Se basa en una serie de comandos que la computadora ejecuta en orden para cambiar el estado del programa. Es un enfoque muy directo y se basa en tres estructuras principales: sentencias secuenciales, selectivas (condicionales) y repetitivas (bucles). Es fácil de entender para programas sencillos, pero puede volverse difícil de manejar en proyectos grandes, ya que todo el código se concentra en un solo bloque. Ejemplos: C, Pascal.

* **Programación Procedimental**: Es un subtipo del paradigma imperativo. Aquí, los programas se organizan en **procedimientos** (o funciones) que manipulan el estado global del programa. Se relaciona estrechamente con la programación estructurada y modular. C, Visual Basic, y otros lenguajes permiten este estilo de programación al escribir funciones o métodos que no están necesariamente asociados a una clase.

* **Programación Orientada a Objetos (POO)**: En este paradigma, los programas se construyen como una colección de **objetos** que interactúan entre sí. Un objeto es una instancia de una **clase** que contiene datos (atributos) y los métodos para operar sobre ellos. La POO promueve la reutilización de código, facilita la depuración y mejora el mantenimiento a largo plazo. Sus pilares son el **polimorfismo**, la **herencia** y la **encapsulación**. Ejemplos: C++, Python, Java, Kotlin, C#.

* **Programación Declarativa**: Los programas describen el **resultado deseado**, no el proceso paso a paso para lograrlo. Suelen ser lenguajes interpretados.

    * **Lógica**: Utiliza reglas y afirmaciones de lógica formal para que la computadora deduzca la respuesta a una consulta. Se usa mucho en inteligencia artificial. Ejemplo: Prolog.
    * **Funcional**: Se enfoca en el uso de **funciones matemáticas** que no cambian el estado ni los datos externos. Esto resulta en un código modular y estructurado, aunque puede volverse complejo. Java a partir de la versión 8 (con expresiones lambda y la API Streams) y C# (con LINQ y expresiones lambda) han incorporado características importantes de este paradigma. Kotlin está diseñado con el paradigma funcional en mente desde el principio, con soporte para funciones de orden superior e inmutabilidad. Ejemplos: Lisp, Haskell, Scala.

* **Programación de Eventos**: El flujo del programa es impulsado por **eventos**, como clics del usuario, movimientos del ratón o cambios en el sistema. Es muy común en el desarrollo de interfaces gráficas de usuario (GUI) y servidores. Java (con sus listeners y event handlers) y C# (con sus eventos y delegados) son ejemplos clave de lenguajes que aplican este paradigma.

* **Programación Reactiva**: Es un subtipo de la programación de eventos que se enfoca en la gestión de flujos de datos asincrónicos y la propagación de cambios. Es ideal para aplicaciones que necesitan responder a grandes volúmenes de datos en tiempo real. Java (con librerías como RxJava) y C# (con Rx.NET) tienen un fuerte soporte para la programación reactiva.

* **Programación Multiparadigma**: Son lenguajes que admiten y combinan múltiples paradigmas. Esto permite a los desarrolladores elegir el mejor enfoque para cada parte del problema. Ejemplos: C++, JavaScript, Python, Java, Kotlin, C#.

#### 5.2.5. Según Generaciones
La evolución de los lenguajes de programación se puede dividir en 5 etapas o generaciones:
*   **Primera Generación**: Lenguaje máquina.
*   **Segunda Generación**: Creación de los primeros lenguajes ensambladores.
*   **Tercera Generación**: Creación de los primeros lenguajes de alto nivel (C, Pascal, Cobol).
*   **Cuarta Generación**: Lenguajes capaces de generar código por sí solos (RAD), con los cuales se pueden realizar aplicaciones sin ser experto. Aquí se incluyen los lenguajes orientados a objetos, permitiendo la reutilización de código. Suelen tener acceso a bases de datos, capacidades gráficas y generación de código automática.
*   **Quinta Generación**: Lenguajes orientados a la inteligencia artificial (LISP).

### 5.3. Criterios para la Selección de un Lenguaje de Programación
La elección del lenguaje a utilizar en un proyecto es de extrema importancia. Algunos criterios para su selección son:
*   Campo de aplicación.
*   Experiencia previa del equipo.
*   Herramientas de desarrollo disponibles.
*   Documentación disponible.
*   Base de usuarios de la comunidad.
*   Reusabilidad.
*   Transportabilidad (portabilidad).
*   Imposición del cliente.

### 5.4. Lenguajes más Utilizados en la Actualidad
Lenguajes como Java, C, C++, PHP y Visual Basic concentran alrededor del 60% del interés de la comunidad informática mundial. Existen índices como [TIOBE](https://www.tiobe.com/tiobe-index/) que analizan la demanda de lenguajes de programación diariamente.


## 6. Proceso de Traducción, Máquinas Virtuales y Entornos de Ejecución

### 6.1. Proceso de Traducción: Compilación e Interpretación
Para que el ordenador entienda algo escrito en un lenguaje de programación, debe pasar por un proceso de traducción de código. La traducción de un programa escrito en un lenguaje de programación a un lenguaje de máquina se realiza mediante un **traductor**, que puede ser un **compilador** o un **intérprete**.

#### 6.1.1. Diferenciación entre Traducción, Compilación e Interpretación
*   **Traducción**: Es el proceso general de transformar código de un lenguaje a otro.
*   **Compilación**: Proceso que traduce el código fuente completo a código objeto o binario ejecutable en un solo paso. Un ejemplo es el compilador de C.

*   **Interpretación**: Proceso que traduce y ejecuta el código fuente línea a línea, o instrucción por instrucción, sin generar un archivo intermedio. Un ejemplo es el intérprete de JavaScript.

![Diagrama: Compilación vs Interpretación](/images/compilado_interpretado.jpeg)

*   **Mixto**: Algunos lenguajes utilizan ambos métodos, compilando a un código intermedio (bytecode) que luego es interpretado por una máquina virtual. Un ejemplo es Java y C#.
  
![Diagrama: Lenguaje Mixto](/images/lenguaje_mixto.png)

#### 6.1.2. Fases de un Traductor (Compilador/Intérprete)
Un **traductor** es un programa que convierte el código escrito por un programador (código fuente) en un lenguaje que la máquina puede entender directamente (código máquina o código objeto). Este proceso no es una simple traducción palabra por palabra, sino que se lleva a cabo en varias fases bien definidas.

Fases Principales de un Traductor (Compilador/Intérprete):

![Diagrama: Fases de un Compilador](/images/fases_compilador.png)

##### 1. Análisis Léxico (Scanner)

Es la primera fase del proceso. El **analizador léxico** lee el código fuente carácter a carácter y lo agrupa en unidades lógicas llamadas **tokens**. Un token representa una unidad léxica, como una palabra clave (`if`, `while`), un identificador (`variableX`), un operador (`+`, `=`), o un literal (`"hola mundo"`, `123`). También se encarga de eliminar comentarios y espacios en blanco.

* **Ejemplo:** La línea de código `int suma = a + 5;` sería descompuesta en los siguientes tokens:
    * `int` (token de palabra clave)
    * `suma` (token de identificador)
    * `=` (token de operador de asignación)
    * `a` (token de identificador)
    * `+` (token de operador de suma)
    * `5` (token de literal numérico)
    * `;` (token de delimitador)

##### 2. Análisis Sintáctico (Parser)

Una vez que los tokens han sido identificados, el **analizador sintáctico** toma esta secuencia y comprueba que la estructura del programa sea gramaticalmente correcta. Este proceso genera una representación jerárquica del código, conocida como **Árbol Sintáctico (o Árbol de Análisis)**. Si la secuencia de tokens no cumple con las reglas gramaticales del lenguaje, se genera un error de sintaxis.

* **Ejemplo:** Para la expresión `a + 5`, el analizador sintáctico crearía un árbol donde el nodo superior es el operador `+`, con `a` y `5` como sus hijos.

##### 3. Análisis Semántico

En esta fase se verifica el "sentido" del programa, asegurando que las operaciones sean lógicamente coherentes y permitidas. El **analizador semántico** comprueba aspectos como:
* **Compatibilidad de tipos:** Se asegura de que no se estén realizando operaciones entre tipos de datos incompatibles (ej. sumar un número a una cadena de texto).
* **Declaración de variables:** Verifica que todas las variables utilizadas hayan sido declaradas previamente.
* **Número y tipo de argumentos:** Comprueba que las llamadas a funciones tengan el número y tipo de argumentos correctos.

Si el código supera esta fase, se garantiza que es válido y tiene un significado claro, aunque esto no asegura que funcione como el programador espera.

##### 4. Generación de Código Intermedio

Antes de producir el código máquina final, muchos compiladores generan un **código intermedio**. Este es un lenguaje de bajo nivel, parecido al ensamblador, pero independiente de la arquitectura de la máquina de destino. Esta fase simplifica el diseño del compilador, ya que las optimizaciones pueden realizarse sobre este código genérico en lugar de sobre múltiples arquitecturas de máquina.

* **Ejemplo:** Una expresión compleja como `x = a + 5 * y` podría traducirse a un código intermedio de tres direcciones:
    * `t1 = 5 * y`
    * `t2 = a + t1`
    * `x = t2`

##### 5. Optimización de Código

Esta fase es opcional pero crucial para el rendimiento. El **optimizador** mejora el código intermedio (o, en algunos casos, el código final) para que el programa resultante sea más eficiente. El objetivo puede ser reducir el tiempo de ejecución, minimizar el tamaño del archivo o disminuir el consumo de memoria. Existen diversas técnicas de optimización, como la eliminación de código redundante o la sustitución de expresiones por resultados precalculados.

##### 6. Generación de Código Objeto

En esta fase, el código intermedio (ya optimizado) se convierte en **código máquina** de la arquitectura específica (por ejemplo, x86, ARM). El resultado es un archivo binario que contiene instrucciones que la CPU puede ejecutar directamente. Sin embargo, este código aún no es un programa completo, ya que las referencias a funciones o datos de otras partes del programa o de librerías externas están representadas por etiquetas simbólicas.

##### 7. Enlazador (Linker) y Cargador (Loader)

* **Enlazador (Linker):** Es el programa que toma uno o más archivos de código objeto y los combina con las **librerías** y rutinas necesarias (como las funciones para entrada y salida) para crear un único **archivo ejecutable** completo. El enlazador resuelve las referencias simbólicas, asignando direcciones de memoria reales. En lenguajes como C, esto incluye las instrucciones del preprocesador (ej. `#include`), que se encargan de incluir el contenido de otros archivos antes de la compilación.

* **Cargador (Loader):** Aunque no es parte del compilador, es la fase final que se encarga de cargar el archivo ejecutable en la memoria RAM y prepara su ejecución cuando el usuario lo inicia.

### 6.2. Códigos Fuente, Objeto y Ejecutable
Durante el proceso de codificación, el código pasa por diferentes estados:

*   **Código Fuente**: Es el archivo de texto legible escrito por los programadores en un lenguaje de programación de alto nivel. Contiene el conjunto de instrucciones necesarias. Este código no es directamente ejecutable por la máquina y debe ser traducido. Un aspecto importante es su licencia: puede ser **abierto** (disponible para estudiar, modificar, reutilizar) o **cerrado** (no se tiene permiso para editarlo).
*   **Código Objeto (Intermedio)**: Es un archivo binario no ejecutable. Es el resultado de traducir (compilar) el código fuente a un código equivalente formado por unos y ceros. En Java, el código objeto se denomina **Bytecode**. Solo existe si el programa se compila. No es directamente inteligible por el ser humano ni por la computadora.
*   **Código Ejecutable**: Es el archivo binario ejecutable directamente por la computadora. También conocido como **código máquina**. Se obtiene al enlazar los archivos de código objeto con ciertas rutinas y bibliotecas necesarias. El sistema operativo es el encargado de cargarlo en memoria RAM y ejecutarlo. Los programas interpretados no producen código objeto, el paso de fuente a ejecutable es directo.

### 6.3. Máquinas Virtuales y Entornos de Ejecución

#### 6.3.1. Concepto de Máquina Virtual
Una **máquina virtual (MV)** es un tipo especial de software cuya misión es separar el funcionamiento del ordenador de los componentes hardware instalados. Actúa como una capa de software de bajo nivel, haciendo de puente entre el bytecode de la aplicación y los dispositivos físicos del sistema. Esto garantiza la **portabilidad** de las aplicaciones, permitiendo desarrollarlas y ejecutarlas sobre cualquier equipo, independientemente de sus características hardware.

Las funciones principales de una máquina virtual son:
*   Conseguir que las aplicaciones sean portables.
*   Reservar memoria para los objetos y liberar la no utilizada.
*   Comunicarse con el sistema huésped para el control de dispositivos hardware y procesos.
*   Verificar todo el bytecode antes de ejecutarlo.
*   Cumplir las normas de seguridad de las aplicaciones.

Los **lenguajes mixtos o virtuales** (como Java o Python) compilan el código fuente a un código intermedio llamado **bytecode** (en Java), que luego es interpretado por la máquina virtual.

![Diagrama: Máquina Virtual](/images/lenguaje_java.webp)

![img05](/images/lenguajes_traduccion.gif)

#### 6.3.2. Entornos de Ejecución (Runtime Environments)
Un **entorno de ejecución** es un servicio de máquina virtual que sirve como base software para la ejecución de programas. Puede pertenecer al sistema operativo o instalarse como software independiente. Es un conjunto de utilidades que permiten la ejecución de programas. Se encarga de configurar la memoria principal, enlazar los archivos del programa con bibliotecas existentes y subprogramas creados, y depurar programas (comprobar errores semánticos).

El Entorno de Ejecución está formado por la máquina virtual y los **API's** (bibliotecas de clases estándar), que se distribuyen conjuntamente al necesitar ser compatibles. Funciona como intermediario entre el lenguaje fuente y el sistema operativo, ejecutando aplicaciones. Para el desarrollo de nuevas aplicaciones, se necesita algo más que el entorno de ejecución, como un entorno de desarrollo integrado (IDE). Un ejemplo es el **JRE (Java Runtime Environment)**, que permite la ejecución de programas Java sobre cualquier plataforma, compuesto por la JVM y las bibliotecas de clase estándar de Java.

#### 6.3.3. Frameworks
Un **framework** (plataforma, entorno, marco de trabajo de desarrollo rápido de aplicaciones) es una estructura de ayuda para el programador, en base a la cual se pueden desarrollar proyectos sin partir desde cero. Es una plataforma software que define programas de soporte, bibliotecas, lenguajes interpretados, etc., ayudando a desarrollar y unir los diferentes módulos de un proyecto.

**Ventajas de utilizar un framework**:
*   **Desarrollo rápido de software**.
*   **Reutilización de partes de código** para otras aplicaciones.
*   **Diseño uniforme** del software.
*   **Portabilidad de aplicaciones**, ya que los bytecodes generados pueden ser ejecutados sobre cualquier máquina virtual compatible.

**Inconvenientes**:
*   **Gran dependencia del código** respecto al framework utilizado (si se cambia, gran parte de la aplicación debe reescribirse).
*   La instalación e implementación del framework consume bastantes recursos del sistema.

Ejemplos de Frameworks son **.NET** (para Windows, con el ".Net framework" para la ejecución) y **Spring de Java** (conjuntos de bibliotecas para desarrollo y ejecución de aplicaciones).

## 7. Herramientas de Apoyo al Desarrollo de Software

### 7.1. Herramientas de Desarrollo
En la práctica, para llevar a cabo varias de las etapas del desarrollo de software, se utilizan **herramientas informáticas**. Su finalidad principal es automatizar las tareas y ganar fiabilidad y tiempo. Esto permite a los desarrolladores centrarse en los requerimientos del sistema y el análisis, que son las causas principales de los fallos del software. Los tipos de software de desarrollo incluyen editores, compiladores e intérpretes.

### 7.2. Herramientas CASE (Computer Aided Software Engineering)
Las **herramientas CASE** son un conjunto de aplicaciones que se utilizan en el desarrollo de software con el objetivo de reducir costes y tiempo del proceso, mejorando la productividad.

Ofrecen la siguiente **funcionalidad**:
*   Mejorar la planificación del proyecto.
*   Dar agilidad al proceso.
*   Permitir la reutilización de partes del software en proyectos futuros.
*   Hacer que las aplicaciones respondan a estándares.
*   Mejorar la tarea del mantenimiento de los programas.
*   Mejorar el proceso de desarrollo, al permitir visualizar las fases de forma gráfica.
*   Ayudar en el diseño del proyecto, codificación, detección de errores.

Se clasifican en función de las fases del ciclo de vida del software en las que ofrecen ayuda:
*   **U-CASE (Upper CASE)**: Ofrecen ayuda en las fases de planificación y análisis de requisitos.
*   **M-CASE (Middle CASE)**: Ofrecen ayuda en análisis y diseño.
*   **L-CASE (Lower CASE)**: Ayudan en la programación del software, detección de errores, depuración de programas, pruebas y generación de documentación.

Ejemplos de herramientas CASE libres son ArgoUML, Use Case Maker, ObjectBuilder.

### 7.3. Desarrollo Rápido de Aplicaciones (RAD)
El **Desarrollo Rápido de Aplicaciones (RAD)** es un proceso que comprende el desarrollo iterativo, la construcción de prototipos y el uso de utilidades CASE. Actualmente se utiliza para referirse al desarrollo rápido de interfaces gráficas de usuario o entornos de desarrollo integrado completos.

### 7.4. Entornos de Desarrollo Integrado (IDE)
Un **Entorno de Desarrollo Integrado (IDE)** es una herramienta que facilita y posibilita el desarrollo de software. Agrupa diversas herramientas de desarrollo (editor de código, compilador, depurador) en una única interfaz gráfica para aumentar la productividad del programador. Ejemplos incluyen Eclipse y Visual Studio Code.

## 8. Perfiles del Desarrollo de Software

El desarrollo de software es un proceso que involucra a diferentes profesionales, cada uno con roles y responsabilidades específicas a lo largo del ciclo de vida del software. Estos roles son cruciales para el éxito de un proyecto, combinando conocimientos técnicos, de gestión y de negocio.

A continuación, se detallan algunos de los roles más comunes en el proceso de desarrollo de software:

*   **Arquitecto de Software**:
    *   Este profesional tiene la responsabilidad de decidir "cómo" se realiza el proyecto y cómo se estructurará.
    *   Posee un amplio conocimiento de las tecnologías, los *frameworks* y las librerías disponibles.
    *   Decide y conforma los recursos necesarios para el desarrollo de un proyecto.
    *   Se involucra activamente en la fase de diseño.

*   **Jefe de Proyecto**:
    *   Es el encargado de dirigir el curso del proyecto.
    *   Puede ser un analista con experiencia, un arquitecto o una persona dedicada en exclusividad a este puesto.
    *   Debe poseer habilidades para gestionar un equipo y lidiar con los tiempos y plazos.
    *   Mantiene una comunicación continua y fluida con el cliente.

*   **Analista de Sistemas**:
    *   Realiza un estudio exhaustivo del problema a resolver.
    *   Efectúa el análisis y el diseño de todo el sistema.
    *   Este perfil requiere mucha experiencia y suele involucrarse en reuniones con el cliente para recopilar requisitos.
    *   Es la figura clave en la fase de **Análisis**, donde se determinan y definen las necesidades del cliente y los requisitos del software. También interviene en la fase de diseño.

*   **Analista Programador**:
    *   Según las fuentes, este rol comparte muchas responsabilidades con el **Analista de Sistemas**, incluyendo la realización de un estudio exhaustivo del problema, la ejecución del análisis y diseño del sistema, y la interacción con el cliente.
    *   Este perfil también requiere mucha experiencia y conocimiento tanto en la definición de soluciones como en la capacidad de comprender la implementación técnica.

*   **Programador (o Desarrollador)**:
    *   Conoce en profundidad el lenguaje de programación que se utiliza en el proyecto.
    *   Se encarga de codificar las tareas encomendadas por el analista o el analista programador.
    *   Su misión principal es la de codificar y probar los diferentes módulos de la aplicación.
    *   Actúa en la fase de **Codificación (Implementación)**, escribiendo el código fuente y traduciendo los algoritmos a un lenguaje de programación.
    *   No suele intervenir en la fase de diseño.

*   **QA (Quality Assurance) / Testeador**:
    *   Aunque las fuentes no lo mencionan explícitamente como un "rol" con título específico en la lista de perfiles, la fase de **Pruebas** es fundamental y su objetivo principal es "conseguir que el programa funcione incorrectamente para descubrir y corregir defectos".
    *   Este rol se enfoca en someter el programa al máximo número de situaciones diferentes, realizando pruebas unitarias, de integración, funcionales, estructurales y *Beta Test*.
    *   La existencia de estas pruebas detalladas implica que hay personal dedicado o especializado en la validación y verificación del software construido, asegurando su calidad antes de la entrega al cliente.
    *   Los programadores también tienen la misión de probar los módulos que desarrollan, pero en proyectos más grandes o complejos, se suelen establecer roles dedicados a la calidad y las pruebas.



## 9. Conclusión

El desarrollo de software es un proceso complejo pero estructurado, que va desde la concepción de una idea hasta la puesta en funcionamiento y mantenimiento de una aplicación. Comprender las fases del ciclo de vida (análisis, diseño, codificación, pruebas, mantenimiento), los diferentes modelos y metodologías (cascada, ágiles como Scrum), y la interacción del software con el hardware es fundamental. Asimismo, es crucial conocer los tipos de lenguajes de programación y sus paradigmas, así como el proceso de traducción de código y el papel de las máquinas virtuales y herramientas de apoyo al desarrollo. Todos estos elementos se combinan para crear soluciones informáticas eficientes, fiables y adaptadas a las necesidades cambiantes de los usuarios y el mercado.

## Autor

Codificado con :sparkling_heart: por [José Luis González Sánchez](https://twitter.com/JoseLuisGS_)

[![Twitter](https://img.shields.io/twitter/follow/JoseLuisGS_?style=social)](https://twitter.com/JoseLuisGS_)
[![GitHub](https://img.shields.io/github/followers/joseluisgs?style=social)](https://github.com/joseluisgs)
[![GitHub](https://img.shields.io/github/stars/joseluisgs?style=social)](https://github.com/joseluisgs)

### Contacto

<p>
  Cualquier cosa que necesites házmelo saber por si puedo ayudarte 💬.
</p>
<p>
 <a href="https://joseluisgs.dev" target="_blank">
        <img src="https://joseluisgs.github.io/img/favicon.png" 
    height="30">
    </a>  &nbsp;&nbsp;
    <a href="https://github.com/joseluisgs" target="_blank">
        <img src="https://distreau.com/github.svg" 
    height="30">
    </a> &nbsp;&nbsp;
        <a href="https://twitter.com/JoseLuisGS_" target="_blank">
        <img src="https://i.imgur.com/U4Uiaef.png" 
    height="30">
    </a> &nbsp;&nbsp;
    <a href="https://www.linkedin.com/in/joseluisgonsan" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/LinkedIn_logo_initials.png/768px-LinkedIn_logo_initials.png" 
    height="30">
    </a>  &nbsp;&nbsp;
    <a href="https://g.dev/joseluisgs" target="_blank">
        <img loading="lazy" src="https://googlediscovery.com/wp-content/uploads/google-developers.png" 
    height="30">
    </a>  &nbsp;&nbsp;
<a href="https://www.youtube.com/@joseluisgs" target="_blank">
        <img loading="lazy" src="https://upload.wikimedia.org/wikipedia/commons/e/ef/Youtube_logo.png" 
    height="30">
    </a>  
</p>

## Licencia de uso

Este repositorio y todo su contenido está licenciado bajo licencia **Creative Commons**, si desea saber más, vea
la [LICENSE](https://joseluisgs.dev/docs/license/). Por favor si compartes, usas o modificas este proyecto cita a su
autor, y usa las mismas condiciones para su uso docente, formativo o educativo y no comercial.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Licencia de Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">
JoseLuisGS</span>
by <a xmlns:cc="http://creativecommons.org/ns#" href="https://joseluisgs.dev/" property="cc:attributionName" rel="cc:attributionURL">
José Luis González Sánchez</a> is licensed under
a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons
Reconocimiento-NoComercial-CompartirIgual 4.0 Internacional License</a>.<br />Creado a partir de la obra
en <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/joseluisgs" rel="dct:source">https://github.com/joseluisgs</a>.