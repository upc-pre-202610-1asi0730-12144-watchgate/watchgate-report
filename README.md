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
| U202418645  | Sandoval Aiquipa, Kelver Yamir      |
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
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivos](#13-segmentos-objetivos)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
  - [2.4. Big Picture Event Storming](#24-big-picture-event-storming)
  - [2.5. Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. User Stories](#31-user-stories)
  - [3.2. Impact Mapping](#32-impact-mapping)
  - [3.3. Product Backlog](#33-product-backlog)
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
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Design-Level Event Storming](#461-design-level-event-storming)
    - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
    - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
    - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagrams](#481-database-diagrams)
- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint n](#521-sprint-n)
      - [5.2.1.1. Sprint Planning n](#5211-sprint-planning-n)
      - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog n](#5213-sprint-backlog-n)
      - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
  - [5.4. Video About-the-Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)



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

### 4.4. Web Applications UX/UI Design
El diseño de la experiencia de usuario (UX) y de la interfaz (UI) de la plataforma Locksight se ha centrado en la operatividad bajo presión. Entendemos que un jefe de seguridad o un dueño de negocio entra a la aplicación web buscando respuestas rápidas: "¿Está todo cerrado?", "¿Hubo alguna alerta?". Por ello, la UX prioriza la visibilidad de los estados de los sensores y la facilidad para auditar eventos pasados. La UI, basada en Material Design, utiliza una estética limpia y profesional que reduce la carga cognitiva, permitiendo que el usuario identifique anomalías mediante el uso estratégico de colores semánticos (rojo para alertas, verde para estados seguros).
