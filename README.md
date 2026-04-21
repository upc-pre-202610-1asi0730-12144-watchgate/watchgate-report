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

<img src="./assets/logo-locksight.png" alt="color-palette-locksight" width="400">

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

<img src="./assets/color-palette-locksight.png" alt="color-palette-locksight" width="600">

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


## 4.2. Information Architecture


### 4.2.1. Organization Systems



### 4.2.2. Labeling Systems

### 4.2.3. SEO Tags and Meta Tags

### 4.2.4. Searching Systems

### 4.2.5. Navigation Systems

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

### 4.3.2. Landing Page Mock-up