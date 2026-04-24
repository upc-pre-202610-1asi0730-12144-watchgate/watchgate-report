<!-- Carátula -->

<div align="center">
    <img src="./logo-upc.png">
</div>

<div align="center">

# Universidad Peruana de Ciencias Aplicadas

## Carrera de Ingeniería de Software

</div>

<div align="center"> 

**Ciclo:** 2026 - 1  
**Curso:** Aplicaciones Web<br>
**NRC:** 12144<br>
**Docente:** Efraín Ricardo Bautista Ubillús

## "Informe del trabajo final"
**Startup:** watchgate<br>
**Producto:** locksight


## Relacion de integrantes:


| Código      | Nombre                              |
|-------------|-------------------------------------|
| U201819276  | Bardales Tejada, Luis Alexis        |
| U202416276  | Higa Kohatsue, Alonso Enrique       |
| U202412903  | Lozano Quispe, Fabricio Jofred      |
| U202418645  | Sandoval Aiquipa, Kelber Yamir      |
| U202414356  | Vite Celis, Rodrigo Matias          |

<div style="font-weight: bold;"> Abril, 2026</div>

</div>

## Registro de Versiones del Informe

| Versión | Fecha    | Autor       | Descripción de Modificación            |
| ------- | -------- | ----------- | -------------------------------------- |
| 0.1     | 00/04/26 | Bardales Tejada, Luis Alexis    | Desarrollo de la Estructura del informe |
| 0.1    | 00/04/26 | Higa Kohatsue, Alonso Enrique | Desarrollo de la Estructura del informe|
| 0.1    | 10/04/26 | Lozano Quispe, Fabricio Jofred | Desarrollar de la estructura del informe |
| 0.1    | 00/04/26 | Sandoval Aiquipa, Kelver Yamir | Desarrollo de la Estructura del informe|
| 0.1    | 10/04/26 | Vite Celis, Rodrigo Matias | Desarrollo de la Estructura del informe|



## Project Report Collaboration Insights

| URL de la organización del proyecto | URL del repositorio del reporte   |
| :------------------: | :---------------------------: | 
|  |  |

| URL del repositorio de la landing page |
| :----------------------------: | 
|  | 



**URL LANDING PAGE DESPLEGADO**:


Commits del Report:

## CONTENIDO

### Tabla de contenido
- [Universidad Peruana de Ciencias Aplicadas](#universidad-peruana-de-ciencias-aplicadas)
  - [Carrera de Ingeniería de Software](#carrera-de-ingeniería-de-software)
  - ["Informe del trabajo final"](#informe-del-trabajo-final)
  - [Relacion de integrantes:](#relacion-de-integrantes)
  - [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
  - [Project Report Collaboration Insights](#project-report-collaboration-insights)
  - [CONTENIDO](#contenido)
    - [Tabla de contenido](#tabla-de-contenido)
- [**Student Outcomes**](#student-outcomes)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.3.1. Web Applications Wireframes](#431-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
  - [4.8. Database Design](#48-database-design)



# **Student Outcomes**



# Capítulo I: Introducción

## 1.1. Startup Profile

###  1.1.1. Descripción de la Startup
En un entorno empresarial donde la seguridad de los almacenes y el control de accesos representan un desafío constante, especialmente en ciudades como Lima donde las pérdidas por robos internos, accesos no autorizados y falta de monitoreo en tiempo real impactan directamente en la rentabilidad de las empresas, las soluciones tradicionales ya no son suficientes. Frente a esta problemática surge nuestra startup, una iniciativa impulsada por estudiantes enfocada en transformar la gestión de seguridad mediante el uso de tecnología IoT. Reconocemos que la falta de visibilidad, control y trazabilidad en los almacenes genera vulnerabilidad operativa, por lo que proponemos una solución que conecta sensores físicos con una plataforma web inteligente, permitiendo supervisar en tiempo real lo que ocurre en cada espacio. No nos limitamos a registrar eventos, sino que convertimos cada almacén en un entorno inteligente capaz de detectar anomalías, generar alertas automáticas y proporcionar información clara para la toma de decisiones, brindando así mayor control, seguridad y eficiencia operativa.

**Misión:** Nuestra misión es transformar la seguridad y gestión de accesos en almacenes mediante un sistema inteligente basado en IoT, que permita a las empresas monitorear en tiempo real sus instalaciones, reducir riesgos y tomar decisiones informadas a partir de datos precisos. Buscamos proteger los activos empresariales y optimizar la operación mediante alertas inteligentes, trazabilidad completa y una plataforma accesible que elimine la incertidumbre y fortalezca el control sobre cada evento crítico dentro del almacén.

**Visión:** Nuestra visión es posicionarnos como una plataforma líder en seguridad inteligente para entornos empresariales, elevando el estándar de control y protección en almacenes mediante el uso de IoT y análisis de datos. Aspiramos a que cada instalación conectada opere como un sistema autónomo capaz de anticipar riesgos, detectar comportamientos inusuales y activar mecanismos de alerta en tiempo real, permitiendo a las empresas mantener el control total desde cualquier lugar. Con nuestra solución buscamos construir un ecosistema seguro, eficiente y escalable que no solo reduzca pérdidas, sino que también transforme la manera en que las organizaciones gestionan su seguridad y operación diaria.

# Capítulo IV: Product Design

## 4.1. Style Guidelines

###  4.1.1. General Style Guidelines

**Logo de LockSight**

<img src="./assets/chapter-4//logo-locksight.png" alt="logo-locksight" width="400">

El imagotipo de Locksight integra visualmente tres conceptos clave del sector logístico, que son protección, tecnología y entorno operativo. El escudo central representa la seguridad y el resguardo del patrimonio, mientras que los nodos conectados representan a una red de sensores IoT que permiten la transmisión de datos en tiempo real. En la parte inferior, la silueta de estanterías vincula directamente la identidad de la marca con su enfoque principal: el monitoreo inteligente de almacenes.

A nivel tipográfico, el diseño busca transmitir autoridad y modernidad. El uso de una tipografía en negrita para el nombre refuerza la solidez de la marca, mientras que el eslogan “Smart Warehouse Control” comunica de forma directa su propuesta de valor. 

**Tipografía**

Para el desarrollo de la landing page y la plataforma web de Locksight, se ha seleccionado la tipografía Inter.

Inter es una tipografía moderna diseñada específicamente para interfaces de usuario y visualización en pantallas de alta resolución. En el contexto de Locksight, una plataforma enfocada en el monitoreo y la seguridad en tiempo real, la legibilidad se convierte en un factor crítico. Los usuarios, como dueños de negocios y jefes de seguridad, requieren interpretar alertas, datos del dashboard y reportes de forma rápida y sin esfuerzo, incluso desde dispositivos móviles o en situaciones de alta presión. Su diseño limpio y minimalista refuerza una percepción de innovación, tecnología y seriedad corporativa. A diferencia de tipografías más recargadas, Inter prioriza la claridad visual y la funcionalidad, lo que la hace especialmente adecuada para entornos donde la rapidez de lectura y la precisión en la información son esenciales.

**Características de la tipografía**

* Clasificación: Sans-Serif
* Pesos a utilizar

  * Regular 400: Para el cuerpo de texto en la landing page, descripciones largas y el historial de eventos en el dashboard.
  * Medium 500: Para subtítulos secundarios, botones y etiquetas de formularios.
  * Semi-Bold 600: Para destacar nombres de zonas, usuarios y elementos clave en las tablas del sistema.
  * Bold 700: Para los títulos principales (H1, H2), mensajes de alertas críticas y precios en la landing page.

**Paleta de colores**

La paleta de colores de Locksight está diseñada para transmitir confianza corporativa, tecnología y facilitar la rápida toma de decisiones operativas.

<img src="./assets/chapter-4//color-palette-locksight.png" alt="color-palette-locksight" width="600">

* Azul oscuro (#0F172A): El azul oscuro es el estándar universal en psicología del color para representar seguridad corporativa, estabilidad y confianza
* Azul eléctrico (#3B82F6): Aporta un toque moderno y tecnológico
* Rojo (#EF4444): Es vital para el dashboard. En un sistema de seguridad, el color rojo debe interpretarse de inmediato como peligro.
* Verde (#22C55E): Brinda seguridad al usuario, indicando de un solo vistazo todo fluye con normalidad y los sensores están en orden.
* Blanco humo (#F8FAFC): Permite que la interfaz "respire" y resalta la información sin cansar la vista durante largas jornadas de monitoreo.

**Tonos de Comunicación**

La voz y el tono con el que Locksight se dirige a sus usuarios en la landing page y en la plataforma son fundamentales para establecer confianza y eficacia. 

1. **Profesional y Confiable**
   
   Dado que Locksight maneja la seguridad del patrimonio y los activos de las empresas, la comunicación no puede ser informal ni excesivamente coloquial. Al dirigirnos a gerentes de operaciones y dueños de PYMES, el lenguaje debe demostrar experiencia, seriedad y solidez técnica.
  
2. **Directo y Preventivo**
   
   En situaciones de monitoreo o riesgo, los usuarios no tienen tiempo para leer textos largos. El tono debe ir directo al grano, fomentando la prevención y la acción inmediata. Debe ser instructivo y libre de ambigüedades, lo cual es clave para la interfaz de un dashboard donde una instrucción confusa podría resultar en una brecha de seguridad.


###  4.1.2. Web Style Guidelines
Para el desarrollo de las interfaces web de Locksight, se adoptará el lenguaje de diseño Material Design junto con la biblioteca de componentes PrimeVue. Esta elección permite construir interfaces responsivas mediante un sistema de grillas fluidas, adaptando la visualización del dashboard y del landing page a distintos dispositivos. De esta manera, se asegura que los administradores puedan monitorear sus almacenes de forma cómoda y eficiente en todo momento.

En cuanto a la interacción y la estructura visual, se emplearán tarjetas con ligeras elevaciones para organizar la información proveniente de los sensores IoT, favoreciendo una interfaz clara y ordenada. De igual manera, los elementos interactivos, como botones y alertas flotantes, utilizarán una paleta de colores semántica previamente definida, proporcionando un feedback visual inmediato que facilite la interpretación de eventos y la toma de decisiones operativas dentro del sistema.

## 4.2. Information Architecture
En esta sección se definen las decisiones y fundamentos que orientan la organización del contenido dentro de las interfaces web de Locksight. El objetivo principal es facilitar la adaptación de los usuarios, como dueños de negocios y jefes de seguridad, permitiéndoles acceder de manera rápida y sencilla a la información de sus almacenes, alertas y reportes. Para ello, se plantea una estructuración lógica basada en sistemas de organización, etiquetado, búsqueda y navegación, que optimizan la experiencia de uso y reducen el esfuerzo cognitivo.

### 4.2.1. Organization Systems
Para la interfaz principal de Locksight, tanto en el dashboard web como en su versión móvil, se ha optado por un sistema de organización que prioriza el acceso rápido a la información crítica. Dado que la plataforma está orientada a la seguridad de almacenes, se busca que gerentes y dueños de negocio puedan comprender de forma inmediata el estado general del sistema, especialmente en situaciones que requieren una respuesta rápida.

Se adopta una organización jerárquica, ya que permite estructurar la información según su nivel de importancia e inmediatez. Este enfoque facilita que la capa superior muestre siempre un resumen del estado de las instalaciones, como alertas activas o el estado de los sensores, mientras que los niveles inferiores agrupan información más detallada, como el historial de accesos, la gestión de usuarios, las zonas del almacén y la configuración de dispositivos. Complementariamente, se emplea una organización secuencial en procesos críticos que requieren pasos controlados, como la incorporación de nuevos sensores, la creación de perfiles de usuario o la suscripción a planes. En estos casos, el sistema permite retroceder entre pasos para verificar la información antes de confirmar una acción.

En cuanto a la categorización del contenido, el dashboard agrupa la información en función de objetos de negocio, como Sensores, Eventos, Usuarios y Sucursales, lo que facilita la localización de funcionalidades. Asimismo, el módulo de eventos y alertas, se organiza de manera cronológica, mostrando la actividad más reciente en la parte superior, con el fin de asegurar una respuesta oportuna ante cualquier incidente.

### 4.2.2. Labeling Systems

Esta sección se centra en la forma en que se nombran los grupos de información dentro de Locksight. El objetivo es que las etiquetas sean precisas, consistentes y alineadas a un entorno corporativo. En un contexto de seguridad logística, es fundamental que el usuario comprenda de inmediato el significado de cada sección, especialmente al momento de auditar un almacén.

En este sentido, se han definido etiquetas claras y estandarizadas, como “Dashboard” en lugar de “Pantalla de resumen”, “Sensores” en lugar de “Dispositivos conectados”, “Auditoría” en lugar de “Registro de lo que pasó” y “Usuarios” en lugar de “Personas que usan el sistema”. De igual manera, se ha establecido que las etiquetas de la navegación principal no excedan entre dos y tres palabras, con el fin de mantenerlas simples, directas y fáciles de escanear visualmente, incluso en situaciones de presión. Esto también garantiza su correcta adaptación a pantallas móviles. En el landing page, se emplean etiquetas breves y directas como “Solución”, “Planes” y “Contacto”.

Por último, las etiquetas están diseñadas para facilitar una asociación lógica entre los distintos niveles de información. Aquellas que representan módulos principales funcionan como contenedores de contenido más específico.

### 4.2.3. SEO Tags and Meta Tags

En esta sección se definen los SEO Tags y Meta Tags que serán implementados en las principales páginas de la experiencia de LockSight, tanto en la Landing Page como en la Web Application. Estos elementos permiten mejorar el posicionamiento del producto en motores de búsqueda y facilitar su descubrimiento por parte de profesionales del sector logístico y de seguridad.

**Landing Page:**

| Elemento | Valor |
|----------|------|
| Title | LockSight | Seguridad Inteligente para Almacenes con IoT en Tiempo Real |
| Meta Description | Plataforma inteligente de seguridad para almacenes que permite monitorear accesos, detectar anomalías y prevenir pérdidas mediante sensores IoT y alertas en tiempo real. |
| Meta Keywords | seguridad logística, monitoreo de almacenes, IoT almacenes, control de accesos, prevención de robos internos, trazabilidad logística, seguridad empresarial |
| Author | Equipo LockSight - UPC Ingeniería de Software |

**Web Application**

| Elemento | Valor |
|----------|------|
| Title | Dashboard de Seguridad | LockSight |
| Meta Description | Sistema de monitoreo de almacenes que permite gestionar sensores, visualizar eventos, auditar accesos y detectar incidentes en tiempo real. |
| Meta Keywords | dashboard seguridad, monitoreo IoT, sensores inteligentes, auditoría de accesos, control de almacenes, alertas en tiempo real |
| Author | Equipo LockSight - UPC Ingeniería de Software |

### 4.2.4. Searching Systems

En esta sección se describen los mecanismos de búsqueda que ofrece LockSight para ayudar al usuario a encontrar información dentro del sistema, evitando que se sienta perdido frente al volumen de datos generados por sensores y eventos.

El sistema permite realizar búsquedas dentro de los principales módulos del producto, facilitando la localización de información relevante de manera rápida y precisa.

**Opciones de búsqueda**

- Búsqueda de sensores por nombre o tipo.
- Búsqueda de eventos registrados (alertas, accesos, anomalías).
- Búsqueda de registros de auditoría.
- Búsqueda por sucursal o zona del almacén.

**Filtros de búsqueda**

| Filtro | Descripción |
|--------|------------|
| Fecha | Permite delimitar la búsqueda en un rango de tiempo específico |
| Tipo de evento | Permite filtrar por alertas, accesos o incidentes |
| Estado del sensor | Permite identificar sensores activos, inactivos o con fallas |
| Ubicación | Permite filtrar por zonas o sucursales |

**Presentación de resultados**

- Los resultados se muestran en listas organizadas por fecha o relevancia.
- Cada resultado incluye información como tipo de evento, ubicación y hora.
- Se utilizan indicadores visuales para diferenciar estados (alerta, normal, fallo).
- Los resultados se visualizan dentro del contexto del módulo donde se realiza la búsqueda.

**Características del sistema**

- Permite búsquedas rápidas dentro de cada módulo.
- Reduce la sobrecarga de información mediante filtros específicos.
- Presenta resultados claros y fáciles de interpretar.
- Facilita la identificación de eventos críticos en el sistema.

### 4.2.5. Navigation Systems

En esta sección se describen las acciones y técnicas de navegación que permiten guiar a los usuarios a través del Landing Page y la Web Application de LockSight, facilitando el cumplimiento de sus objetivos dentro del sistema.

El sistema de navegación está diseñado para que el usuario pueda recorrer el contenido de manera clara, desde el acceso inicial hasta la interacción con los distintos módulos del producto.

**Tipos de navegación**

| Tipo | Descripción |
|------|------------|
| Navegación global | Menú principal que permite acceder a secciones clave como Solución, Planes, Contacto y acceso al sistema |
| Navegación jerárquica | Organización por niveles que permite pasar de vistas generales a específicas (Dashboard → Sucursal → Zona → Evento) |
| Navegación local | Opciones dentro de cada módulo como Sensores, Auditoría, Usuarios y Configuración |
| Navegación contextual | Acciones disponibles según la sección, como visualizar detalles o revisar eventos |

**Recorrido del usuario**

- En la Landing Page:
  - Inicio → Información de la solución → Beneficios → Planes → Registro/Login

- En la Web Application:
  - Dashboard → Selección de sucursal → Visualización de sensores y eventos → Revisión de alertas o auditoría

**Características**

- Permite una navegación clara y estructurada.
- Facilita el acceso rápido a los módulos principales.
- Reduce la cantidad de pasos para acceder a información crítica.
- Se adapta a diferentes dispositivos (desktop y mobile).

## 4.3. Landing Page UI Design
En esta sección se presenta la propuesta de diseño de interfaz de usuario para el landing page de Locksight desde la versión desktop como la mobile. El objetivo es materializar las decisiones de arquitectura de la información y los lineamientos visuales en una experiencia digital clara y estructurada.

A través de este diseño, se busca captar la atención del segmento objetivo y guiarlo de manera progresiva desde el primer impacto visual hasta la conversión final. Todo ello se desarrolla bajo una estética limpia, corporativa y centrada en la usabilidad, asegurando una interacción intuitiva y coherente en cada etapa del recorrido del usuario.
### 4.3.1. Landing Page Wireframe
**Explicación para Desktop**

<div align="center">
  <img src="./assets/chapter-4/landing-wireframe-desk-hero-section.png" alt="hero-section" width="600">
  <img src="./assets/chapter-4/landing-wireframe-desk-features.png" alt="features" width="600">
  <img src="./assets/chapter-4/landing-wireframe-desk-pricing.png" alt="pricing" width="600">
  <img src="./assets/chapter-4/landing-wireframe-desk-team.png" alt="team" width="600">
  <img src="./assets/chapter-4/landing-wireframe-desk-testimonials.png" alt="testimonials" width="600">
  <img src="./assets/chapter-4/landing-wireframe-desk-cta-footer.png" alt="footer" width="600">
</div>


El diseño de la versión de escritorio está estructurado para guiar al usuario a través de un recorrido narrativo y persuasivo. Cuando se abre en el navegador se abre con un hero section que sigue el patrón de lectura en “F”, integrando una barra de navegación clara y un área principal donde se destaca la propuesta de valor junto con llamadas a la acción, visibles y directas. A medida que el usuario se desplaza en la landing, se presentan las principales características del servicio en una disposición de tres columnas, donde se resaltan sus pilares diferenciales, que son alertas inmediatas, trazabilidad total y gestión centralizada. Luego de esto, la sección de suscripciones escalables utiliza tarjetas comparativas, facilitando la evaluación y elección según el perfil de cada empresa.

Para reforzar la credibilidad, un aspecto clave en soluciones de seguridad, la parte inferior de la página incorpora elementos que dan seguridad al usuario. Entre ellos se incluye una sección dedicada al equipo, que aporta cercanía y transparencia y una cuadrícula de testimonios, que valida la propuesta mediante experiencias de usuarios. Estos elementos contribuyen a generar confianza en potenciales clientes.

Al final la experiencia termina con un último bloque de conversión, donde invita al usuario a registrarse, diseñado para incentivar la acción del usuario. El recorrido se cierra con un footer corporativo bien estructurado, que reúne enlaces legales, soporte, redes sociales y accesos a la aplicación móvil, asegurando que el usuario siempre disponga de una siguiente acción clara dentro de la plataforma.

**Explicación para Mobile**
<div align="center">
  <img src="./assets/chapter-4/landing-wireframe-mob-hero-features.png" alt="mob-hero-features" width="350"><br><br>
  <img src="./assets/chapter-4/landing-wireframe-mob-pricing-team.png" alt="mob-pricing-team" width="350"><br><br>
  <img src="./assets/chapter-4/landing-wireframe-mob-testimonials-footer.png" alt="mob-testimonials-footer" width="350">
</div>

En la versión móvil del landing page, la experiencia se replantea para priorizar la lectura vertical y la interacción táctil. Se adopta un diseño apilado que reorganiza los elementos en una secuencia clara, adaptada a pantallas reducidas. La navegación se simplifica mediante un menú de hamburguesa, liberando espacio visual y evitando distracciones. En este contexto, el hero section no solo mantiene la propuesta de valor, sino que la presenta de forma más directa, en donde el mensaje principal aparece primero, seguido del soporte visual y al final, los botones de acción, los cuales ocupan todo el ancho de la pantalla para facilitar su uso con el pulgar.

A medida que el usuario avanza, el contenido se distribuye en bloques independientes que priorizan la claridad y evitan la sobrecarga visual. Las secciones de características, planes y testimonios se presentan de forma progresiva, permitiendo una comprensión gradual sin necesidad de desplazamientos laterales. Del mismo modo, elementos como el equipo se ajustan dinámicamente al ancho del dispositivo. La experiencia se cierra con un footer organizado en formato vertical, donde los enlaces se presentan con suficiente separación para asegurar una navegación precisa, manteniendo la coherencia y usabilidad hasta el final del recorrido.

### 4.3.2. Landing Page Mock-up

**Explicación para Desktop**
<div align="center">
  <img src="./assets/chapter-4/landing-mockup-desk-hero-section.png" alt="hero-section" width="600">
  <img src="./assets/chapter-4/landing-mockup-desk-features.png" alt="features" width="600">
  <img src="./assets/chapter-4/landing-mockup-desk-pricing.png" alt="pricing" width="600">
  <img src="./assets/chapter-4/landing-mockup-desk-team.png" alt="team" width="600">
  <img src="./assets/chapter-4/landing-mockup-desk-testimonials.png" alt="testimonials" width="600">
  <img src="./assets/chapter-4/landing-mockup-desk-cta-footer.png" alt="footer" width="600">
</div>
El diseño de la landing page para la versión desktop de Locksight presenta una estructura clara y ordenada, iniciando con una sección principal que resalta el monitoreo inteligente en tiempo real y ofrece accesos directos para registrarse o revisar los planes disponibles. A partir de ahí, la navegación continúa de forma fluida hacia una sección organizada en tres columnas, donde se explican las funcionalidades clave como las alertas inmediatas y la trazabilidad de eventos.

**Explicación para Mobile**
<div align="center">
  <img src="./assets/chapter-4/landing-mockup-mob-hero-features.png" alt="mob-hero-features" width="350"><br><br>
  <img src="./assets/chapter-4/landing-mockup-mob-pricing-team.png" alt="mob-pricing-team" width="350"><br><br>
  <img src="./assets/chapter-4/landing-mockup-mob-testimonials-footer.png" alt="mob-testimonials-footer" width="350">
</div>

La versión mobile adapta la landing page a un formato de desplazamiento vertical, ofreciendo una experiencia más fluida y enfocada en pantallas pequeñas. La navegación superior se simplifica mediante un menú hamburguesa, manteniendo como prioridad la propuesta de valor y los principales llamados a la acción. 

Para aprovechar mejor el espacio, las secciones de características, planes de suscripción y equipo se reorganizan en un diseño de una sola columna, lo que mejora la legibilidad y facilita la interacción táctil. 

## 4.4. Web Applications UX/UI Design
El diseño de la experiencia de usuario (UX) y de la interfaz (UI) de la plataforma Locksight se ha centrado en la operatividad bajo presión. Entendemos que un jefe de seguridad o un dueño de negocio entra a la aplicación web buscando respuestas rápidas: "¿Está todo cerrado?", "¿Hubo alguna alerta?". Por ello, la UX prioriza la visibilidad de los estados de los sensores y la facilidad para auditar eventos pasados. La UI, basada en Material Design, utiliza una estética limpia y profesional que reduce la carga cognitiva, permitiendo que el usuario identifique anomalías mediante el uso estratégico de colores semánticos (rojo para alertas, verde para estados seguros).

### 4.3.1. Web Applications Wireframes
En esta sección se presentan los wireframes diseñados para la versión mobile de la plataforma. Estos modelos estructurales establecen la arquitectura de la información, la jerarquía visual y los flujos de interacción principales sin la distracción de elementos gráficos complejos. Los wireframes detallan la experiencia del usuario administrador a través de los módulos críticos del sistema, como lo es el dashboard de monitoreo de almacenes, la gestión del inventario de dispositivos IoT, el control de accesos del personal y el ecosistema de facturación. El objetivo de esta etapa es validar la usabilidad y la eficiencia de las tareas operativas antes de transicionar al diseño de alta fidelidad.


<div align="center">
  <img src="./assets/chapter-4/wireframe-user-goal-1-picture-1.png" alt="user-goal-1" width="450">
</div>

1. User Goal: Acceso al sistema

  Permitir a los dueños de PYMES y administradores registrar su empresa, ingresar a la plataforma de forma segura y recuperar sus credenciales en caso de olvido

  En el diseño del flujo de acceso, la arquitectura de información sigue un modelo de navegación lineal que guía al usuario paso a paso, evitando distracciones innecesarias. Se emplean campos de texto amplios y una tipografía sans-serif de alto contraste, lo que mejora la legibilidad y refuerza principios como la alineación y la simplicidad visual.

  Pantallas de flujo

  * Formulario inicial donde el usuario registra sus datos personales, los de su empresa y crea una contraseña para iniciar su prueba gratuita
  * Pantalla de login estándar para usuarios que ya tienen una cuenta.
  * Interfaz sencilla donde el usuario ingresa su correo electrónico para recibir un enlace de restablecimiento de acceso

<div align="center">
  <img src="./assets/chapter-4/wireframe-user-goal-2-picture-1.png" alt="user-goal-1" width="450"><br><br>
  <img src="./assets/chapter-4/wireframe-user-goal-2-picture-2.png" alt="user-goal-1" width="450">
</div>

2. User Goal: Monitoreo y gestión de almacenes

  Proveer un panel de control para visualizar el estado de todas las sucursales en tiempo real y permitir la configuración de nuevos locales operativos

  Para el panel principal de almacenes, la arquitectura de información sigue un modelo jerárquico basado en cards, lo que permite visualizar y entender rápidamente el estado de múltiples sucursales. Se aplica el principio de contraste para resaltar claramente los estados de “Alerta Crítica” frente a los estados normales, facilitando una lectura rápida y priorizada de la información.

  Otro aspecto de la información crítica no depende únicamente del color, ya que se complementa con etiquetas en texto y elementos destacados. Los botones de acción también cuentan con áreas táctiles amplias, lo que mejora la accesibilidad para usuarios con dificultades motrices.

  Pantallas de flujo

  * Lista principal que muestra el estado en tiempo real de cada sucursal registrada
  * Formulario para registrar una nueva sucursal y establecer sus horarios de operación automáticos
  * Estado del formulario que resalta visualmente en rojo los campos obligatorios faltantes o con formato incorrecto
  * Ventana emergente que confirma que el nuevo almacén ha sido guardado y está listo para monitorearse

<div align="center">
  <img src="./assets/chapter-4/wireframe-user-goal-3-picture-1.png" alt="user-goal-3" width="450"><br><br>
  <img src="./assets/chapter-4/wireframe-user-goal-3-picture-2.png" alt="user-goal-3" width="450">
</div>

3. User Goal: Administración de dispositivos IoT

  Facilitar la vinculación de nuevo hardware de seguridad a zonas específicas, visualizar su estado de conexión y controlar los límites de uso

  La vinculación y gestión de dispositivos se diseña con el objetivo de reducir la carga cognitiva, agrupando el hardware por categorías para facilitar su identificación y acceso. Se aplica el principio de proximidad de Gestalt para organizar de forma clara la información de cada dispositivo junto a su estado de conexión, mientras que el uso de modales superpuestos permite realizar acciones sin perder el contexto de la pantalla principal. Desde un enfoque inclusivo, los formularios y acciones críticas, como la desvinculación, presentan alto contraste y botones con descripciones claras y directas (“Sí, desvincular” y “Cancelar”), evitando ambigüedades y mejorando la comprensión para todo tipo de usuarios.

  Pantallas de flujo

  * Inventario visual del hardware conectado, indicando si están Online/Offline y mostrando el uso actual de la cuota del plan
  * Formulario para ingresar el número de serie de un equipo nuevo y asignarlo a una zona del almacén
  * Ventana emergente de éxito que confirma la correcta sincronización del nuevo sensor con el sistema.
  * Ventana emergente de advertencia que bloquea la vinculación cuando el usuario ha alcanzado el límite de hardware permitido por su plan

<div align="center">
  <img src="./assets/chapter-4/wireframe-user-goal-4-picture-1.png" alt="user-goal-4" width="450"><br><br>
  <img src="./assets/chapter-4/wireframe-user-goal-4-picture-2.png" alt="user-goal-4" width="450">
</div>

4. User Goal: Registro de eventos e incidentes

  Permitir al usuario revisar la bitácora de actividad del sistema, buscar eventos mediante filtros y acceder al detalle de las alertas críticas.

  Dado que el historial maneja grandes volúmenes de datos, su arquitectura de información se organiza de forma secuencial y con opciones de filtrado claras para facilitar la búsqueda. Se aplica una jerarquía visual donde la hora y la gravedad del incidente destacan en el primer nivel de lectura, permitiendo identificar rápidamente eventos críticos.

  Pantallas de flujo

  * Lista cronológica detallada de todas las actividades del almacén, diferenciando alertas de accesos normales o de sistema
  * Menús desplegables que permiten filtrar el historial por "Tipo de evento" o "Rango de fechas"
  * Ventana emergente que muestra el resumen inmediato de un incidente crítico sin salir de la vista actual

<div align="center">
  <img src="./assets/chapter-4/wireframe-user-goal-5-picture-1.png" alt="user-goal-5" width="450"><br><br>
  <img src="./assets/chapter-4/wireframe-user-goal-5-picture-2.png" alt="user-goal-5" width="450">
</div>

5. User Goal: Gestión de personal y accesos

  Controlar de forma segura qué empleados tienen acceso a la plataforma, invitar nuevos miembros y delimitar qué zonas pueden monitorear

  Este módulo utiliza una arquitectura de información facetada que separa claramente los roles de administrador y personal de seguridad, reduciendo el riesgo de errores en la asignación de permisos. Se aplica el principio de repetición en las tarjetas de usuario para mantener un orden visual consistente y fácil de seguir, mientras que elementos como los badges de roles emplean variaciones tonales sutiles para diferenciarlos sin sobrecargar la interfaz. Desde un enfoque inclusivo, la edición de permisos se apoya en interruptores visuales grandes acompañados de texto claro y confirmatorio, además de un diseño tolerante a errores que evita cambios accidentales, especialmente en usuarios con dificultades motoras.

  Pantallas de flujo

  * Panel central que lista al equipo de trabajo, separando claramente a los Administradores del Personal de Seguridad
  * Formulario para enviar una invitación por correo asignando un rol de sistema específico a un nuevo miembro
  * Panel de configuración con opciones para habilitar o deshabilitar el acceso de un guardia a zonas específicas
  * Ventana emergente de advertencia destructiva para revocar definitivamente el acceso de un empleado a la plataforma.

<div align="center">
  <img src="./assets/chapter-4/wireframe-user-goal-6-picture-1.png" alt="user-goal-5" width="450"><br><br>
  <img src="./assets/chapter-4/wireframe-user-goal-6-picture-2.png" alt="user-goal-5" width="450"><br><br>
  <img src="./assets/chapter-4/wireframe-user-goal-6-picture-3.png" alt="user-goal-5" width="450">
</div>

6. User Goal: Administración de suscripción y facturación

  Permitir a la empresa escalar sus operaciones mejorando su plan, personalizar límites a medida o gestionar la cancelación del servicio

  El flujo de facturación guía al usuario desde la comparación de planes hasta el pago mediante una arquitectura de información progresiva. Además, se incorporan elementos interactivos como sliders y resúmenes de pago claros que facilitan la comprensión del proceso. Desde el enfoque inclusivo, se prioriza la legibilidad financiera mediante tipografías grandes para los montos y textos simples, evitando jerga técnica. Esto permite que usuarios con distintos niveles de conocimiento o limitaciones visuales comprendan fácilmente la información y tomen decisiones con mayor confianza.

  Pantallas de flujo

  * Panel de resumen con el plan actual, fecha de próximo cobro y barras de progreso que muestran los límites consumidos
  * Pantalla comparativa de beneficios y precios entre los diferentes planes ofrecidos
  * Interfaz de cotizador interactivo con controles deslizables para elegir la cantidad exacta de almacenes e IoT necesarios.
  * Pantalla de checkout que detalla el costo total, prorrateos y permite confirmar el método de pago con tarjeta
  * Ventana emergente retención que advierte al usuario sobre las funcionalidades clave que perderá si decide cancelar
  * Ventana emergente de confirmación de transacción aprobada y notificación de actualización de los límites del plan
  * Vista del dashboard en estado "sin plan" cuando la cuenta no posee una suscripción activa, bloqueando nuevas acciones


<div align="center">
  <img src="./assets/chapter-4/wireframe-user-goal-7-picture-1.png" alt="user-goal-7" width="450">
</div>

7. User Goal: Configuración de cuenta y notificaciones

  Dar control al usuario sobre sus credenciales de seguridad y los canales por los cuales desea recibir alertas

  La sección de configuración organiza las preferencias mediante una arquitectura categórica, aplicando el principio de agrupamiento para mantener juntas las opciones relacionadas y facilitar su comprensión. Se utilizan controles estándar y líneas divisorias sutiles que ordenan la interfaz sin recargarla, manteniendo una experiencia limpia y clara.
  
  Pantallas de flujo

  * Menú de ajustes con interruptores para activar o desactivar notificaciones Push, Email y SMS.
  * Ventana emergente que advierte al usuario las consecuencias si intenta silenciar por completo las notificaciones del sistema
  * Ventana emergente de confirmación que avisa sobre la pausa de recepción de alertas Push en el dispositivo actual al salir de la cuenta

### 4.4.2. Web Applications Wireflow Diagrams
El Wireflow es un artefacto que combina la estructura de los wireframes con la lógica de un diagrama de flujo. Su importancia radica en que permite visualizar no solo qué elementos hay en cada pantalla, sino cómo el usuario se desplaza entre ellas para completar un proceso. Para Locksight, esto es vital porque el sistema debe ser capaz de guiar al usuario desde la recepción de una alerta hasta la resolución del incidente en el menor número de pasos posible. En esta sección se detalla la arquitectura de navegación, mostrando los caminos que conectan el panel de control con los módulos de configuración de sensores y revisión de historiales.

### 4.4.4. Web Applications User Flow Diagrams
Mientras que el wireflow se enfoca en el diseño de las pantallas, el User Flow o Diagrama de Flujo de Usuario se centra en el proceso de toma de decisiones de la persona que opera Locksight. Este diagrama ayuda a comprender el camino lógico que sigue un Administrador o Jefe de Seguridad para alcanzar un objetivo específico, como puede ser la auditoría de un acceso no autorizado. Al desglosar cada acción y punto de decisión, podemos identificar posibles fricciones en la experiencia y asegurar que el sistema responda de manera coherente a las necesidades operativas de la empresa, garantizando que el flujo de información sea siempre claro y directo.

## 4.5. Web Applications Prototyping
El prototipado de la aplicación web es la etapa donde se materializa la interacción de Locksight de manera funcional antes de pasar al desarrollo. Este artefacto, desarrollado en la herramienta Figma, permite simular el comportamiento real de la plataforma, desde el inicio de sesión hasta la recepción de una alerta inteligente. El objetivo es validar el flujo de navegación y la usabilidad, asegurando que el sistema sea comprensible y que los administradores puedan acceder a sus reportes y cámaras sin fricciones.

## 4.6. Domain-Driven Software Architecture
La arquitectura de software orientada al dominio (DDD) es el enfoque de diseño que estructura Locksight en torno a los procesos clave del negocio de seguridad y almacenamiento. Este método permite que el software refleje con precisión las reglas de negocio, como la gestión de permisos por zonas o la activación automática de alertas. Al aplicar DDD, logramos un sistema robusto, escalable y fácil de mantener, donde cada componente técnico está alineado con los objetivos de seguridad y eficiencia operativa de nuestros clientes.

## 4.7. Software Object-Oriented Design
El diseño orientado a objetos es fundamental para estructurar Locksight de manera modular. A través de este diseño, definimos las clases y métodos que dan vida a las funcionalidades, aprovechando principios de reutilización de código y mantenimiento. Esto nos permite modelar entidades del mundo real (sensores, usuarios, almacenes) dentro del código de forma lógica, facilitando que el sistema crezca y se adapte a nuevas necesidades de seguridad industrial sin comprometer la estabilidad actual.

## 4.8. Database Design
El diseño de la base de datos proporciona la estructura necesaria para almacenar y gestionar toda la información operativa de Locksight de forma segura y eficiente. Se ha modelado un esquema relacional que organiza las tablas, relaciones y restricciones necesarias para garantizar la integridad de los datos de sensores, historiales de acceso y perfiles de usuario. Un diseño de base de datos sólido permite que el sistema responda con rapidez ante consultas históricas y guarde cada evento de seguridad con precisión milimétrica.
