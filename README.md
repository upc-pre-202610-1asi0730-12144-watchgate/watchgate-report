<div align="center">
    <img src="./assets/logo-upc (1).png">
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



# Capítulo V: Product Implementation, Validation & Deployment. 
## 5.1. Software Configuration Management. 
### 5.1.1. Software Development Environment Configuration. 
# Project Management

| Producto | Propósito | Ruta |
|----------|----------|------|
| GitHub Projects | Planificación y seguimiento de issues, user stories y tareas del equipo. | https://github.com |

---

# Requirements Management

| Producto | Propósito | Ruta |
|----------|----------|------|
| GitHub | Gestión de requerimientos mediante Issues y documentación versionada del proyecto. | https://github.com |
| Markdown | Documentación estructurada de requerimientos dentro del repositorio. | Integrado en GitHub |

---

# Product UX/UI Design

| Producto | Propósito | Ruta |
|----------|----------|------|
| Figma | Diseño de wireframes, mockups y prototipos de la interfaz de usuario. | https://figma.com |
| UXPressia | Plataforma para diseñar la experiencia del cliente (Customer Journey Mapping), incluyendo User Personas, mapas de empatía y Customer Journey Maps. | https://uxpressia.com/ |
| Miro | Lienzo virtual colaborativo para investigación, brainstorming y organización de ideas mediante mapas mentales. | https://miro.com/ |
| PlantUML | Herramienta de código abierto para crear diagramas UML a partir de texto (casos de uso, clases y esquemas técnicos). | https://plantuml.com/ |

---

# Software Development

Se refiere al marco de trabajo y metodologías empleadas para la creación de productos digitales. Define los procesos y actividades del ciclo de vida del software.

| Producto | Descripción | Ruta |
|----------|------------|------|
| GitHub | Plataforma de alojamiento y colaboración que permite gestionar el control de versiones y el trabajo en equipo. | https://github.com |
| Visual Studio Code | Editor de código fuente ligero y extensible desarrollado por Microsoft. | https://code.visualstudio.com/ |
| HTML | Lenguaje de marcado estándar para estructurar contenido web. | https://developer.mozilla.org/es/docs/Web/HTML |
| CSS | Lenguaje de estilos para definir la presentación visual de páginas web. | https://developer.mozilla.org/es/docs/Web/CSS |

---

# Software Testing

Proceso de evaluación del sistema para garantizar el cumplimiento de requisitos mediante validación y verificación.

| Herramienta | Descripción | Ruta |
|-------------|------------|------|
| Gherkin | Lenguaje DSL para definir comportamientos mediante escenarios (Given, When, Then). | https://cucumber.io/docs/gherkin/ |
| GitHub Pages | Servicio de hosting estático para desplegar landing pages y aplicaciones web directamente desde repositorios. | https://pages.github.com/ |

### 5.1.2. Source Code Management. 
En esta sección se describe la gestión del código fuente (SCM, por sus siglas en inglés: Source Code Management), la cual permite registrar, organizar y controlar los cambios realizados durante el desarrollo del proyecto en los distintos repositorios.

Este sistema de control de versiones facilita el seguimiento de las modificaciones hechas por cada integrante del equipo, asegurando un historial claro y ordenado del progreso del software. Para este propósito, se utilizará GitHub como plataforma central para la administración de repositorios y colaboración entre desarrolladores.

El equipo trabajará con repositorios independientes para cada componente del sistema, los cuales se detallan a continuación:

| Component                  | Repository                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| Project Report            | https://github.com/upc-pre-202610-1asi0730-12144-watchgate/watchgate-report |
| Landing Page              | https://github.com/upc-pre-202610-1asi0730-12144-watchgate/watchgate-website |
| Web Services              | https://github.com/upc-pre-202610-1asi0730-12144-watchgate/watchgate-platform |
| Frontend Web Application  | https://github.com/upc-pre-202610-1asi0730-12144-watchgate/watchgate-webapp |

---

### GitFlow

GitFlow es un modelo de trabajo basado en el uso de ramas dentro de Git, ampliamente adoptado en proyectos de desarrollo de software. Fue propuesto por Vincent Driessen y permite estructurar de manera eficiente el ciclo de vida del desarrollo, facilitando la incorporación de nuevas funcionalidades y la corrección de errores.

Este enfoque organiza el trabajo mediante distintas ramas, lo que ayuda a mantener una separación clara entre el desarrollo activo, las versiones en preparación y el código listo para producción.

#### Main Branches

- **main:**  
  Es la rama principal del repositorio. Contiene las versiones finales y estables del sistema que están listas para ser desplegadas en producción.

- **develop:**  
  Se deriva de la rama `main` y funciona como la base de integración donde se consolidan las funcionalidades desarrolladas antes de su liberación.

---

#### Support Branches

- **Feature:**  
  Se crea a partir de `develop` y se utiliza para implementar nuevas funcionalidades. Una vez completada, se integra nuevamente en la rama `develop`.


---

### Conventional Commits

Se empleará la convención Conventional Commits para estructurar los mensajes de los commits, permitiendo una mejor comprensión del historial de cambios y facilitando la automatización de procesos.
**Tipos utilizados:**

- **feat:** incorporación de nuevas funcionalidades  
- **fix:** corrección de errores  
- **docs:** modificaciones en la documentación  
- **style:** cambios de formato o estilo sin impacto en la lógica  
- **refactor:** mejoras internas del código sin añadir funcionalidades ni corregir errores  
- **test:** creación o modificación de pruebas  
- **chore:** tareas menores de configuración o mantenimiento  

**Ejemplos:**
- docs(chapter-02): improve clarity and wording
- docs(chapter-02): add big picture event storming in README.md
- docs(chapter-02): add user journey mapping and empathy mapping
- docs(chapter-02): add interview analysis
- docs(chapter-02): add interview summary

- assets: add image big picture event storming
- assets: add image big picture color legends
- assets: add logo upc

- docs(chapter-02): add as-is scenario mapping
- docs(chapter-02): add user personas and user task matrix

Los tipos utilizados son: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`. Ejemplos aplicados en el proyecto:

- `feat(sensors): add endpoint to register IoT sensor`
- `fix(alerts): correct timezone offset in alert timestamp`
- `docs(readme): update sprint 1 deployment evidence section`
- `chore(deps): upgrade PrimeVue to latest version`

---
### 5.1.3. Source Code Style Guide & Conventions

Para garantizar coherencia, legibilidad y mantenibilidad en todos los repositorios del proyecto Locksight, el equipo adoptó las siguientes guías de estilo y convenciones de codificación. Todos los identificadores, comentarios y documentación en el código se redactan en inglés.

**HTML & CSS**

Se adoptaron las convenciones de [W3Schools HTML Style Guide](https://www.w3schools.com/html/html5_syntax.asp) y [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html). Entre las reglas principales se aplican:

- Uso de minúsculas para todos los nombres de elementos y atributos HTML.
- Atributos entre comillas dobles.
- Indentación de 2 espacios.
- Clases CSS nombradas con kebab-case (ej. `sensor-card`, `alert-banner`).
- Evitar estilos en línea; toda declaración de estilos se centraliza en archivos `.css` o dentro del bloque `<style>` del componente Vue correspondiente.
- Cada elemento `<img>` debe incluir el atributo `alt` para cumplir con los requisitos de accesibilidad (a11y).

**JavaScript**

Se sigue la [Google JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html) y las [MDN JavaScript guidelines](https://developer.mozilla.org/en-US/docs/MDN/Guidelines/Code_guidelines/JavaScript). Las reglas aplicadas incluyen:

- Uso de `const` para variables que no se reasignan y `let` para las que sí.
- Nombres de variables y funciones en camelCase (ej. `fetchSensorData`, `alertList`).
- Nombres de clases y constructores en PascalCase.
- Punto y coma obligatorio al final de cada sentencia.
- Funciones flecha para callbacks.
- Evitar `var` en todo el código base.

**Vue Framework**

Se sigue la [Vue Style Guide oficial](https://vuejs.org/style-guide/) (prioridad A y B). Las convenciones aplicadas incluyen:

- Nombres de componentes en PascalCase en los archivos (ej. `SensorCard.vue`, `AlertList.vue`).
- Uso de la Options API para componentes simples y la Composition API con `<script setup>` para componentes de mayor complejidad.
- Props siempre definidas con su tipo y valor por defecto cuando aplica.
- Uso de PrimeVue como biblioteca de componentes UI, siguiendo su sistema de temas basado en Material Design.
- Los archivos `.vue` están organizados por bounded context dentro del directorio `src/`.

**C# y ASP.NET Core**

Se aplican las [C# Coding Conventions de Microsoft](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions) y las [Microsoft ASP.NET Core Coding Guidelines](https://github.com/dotnet/aspnetcore/wiki/Engineering-guidelines#coding-guidelines). Las principales reglas adoptadas son:

- Nombres de clases, métodos y propiedades públicas en PascalCase (ej. `SensorRepository`, `GetAlertsByWarehouse`).
- Nombres de variables locales y parámetros en camelCase (ej. `sensorId`, `alertList`).
- Interfaces con prefijo `I` (ej. `ISensorRepository`).
- Uso de archivos separados por clase; una clase por archivo.
- Inyección de dependencias mediante el contenedor de IoC de ASP.NET Core.
- Los bounded contexts se organizan como carpetas independientes dentro del proyecto API (ej. `Monitoring`, `Alerts`, `AccessControl`, `Subscriptions`).

**Gherkin (Acceptance Criteria)**

Para los criterios de aceptación se aplican las [Gherkin Conventions for Readable Specifications de SpecFlow](https://specflow.org/gherkin/gherkin-conventions-for-readable-specifications/):

- Uso de `Given`, `When`, `Then` y `And` en inglés.
- Una sola acción por paso `When`.
- Escenarios con nombres descriptivos del comportamiento esperado.
- Datos de ejemplo representados con tablas Gherkin cuando corresponda.

**Conventional Commits**

Todos los mensajes de commit siguen la especificación de [Conventional Commits](https://www.conventionalcommits.org/).

### 5.1.4. Software Deployment Configuration

Creación de la Landing Page:
Se crea un repositorio (watchgate-website) desde upc-pre-202610-1asi0730-12144-watchgate organization
<img width="1628" height="501" alt="image" src="https://github.com/user-attachments/assets/4e1bc7af-1dd5-444c-8085-398ca0ae9402" />

Agregamos a los miembros del equipo

Habilitamos GitHub Pages en branch main y ruta "/(root)".
## 5.2. Landing Page, Services & Applications Implementation

Esta sección registra y explica el proceso de implementación, pruebas y despliegue de los productos digitales de Locksight organizados por Sprint. Durante el Sprint 1, el equipo centró sus esfuerzos en la implementación y despliegue de la primera versión funcional de la Landing Page, que representa la primera forma de contacto del modelo de negocio con los segmentos objetivo.

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1

En esta sección se documenta el Sprint Planning Meeting del Sprint 1, en el que el equipo Watchgate estableció el objetivo del sprint, definió el alcance de trabajo y distribuyó las tareas entre los integrantes para lograr la primera versión desplegada de la Landing Page de Locksight.

| Sprint # | Sprint 1 |
|---|---|
| **Sprint Planning Background** | |
| Date | 2026-04-07 |
| Time | 06:00 PM |
| Location | Reunión virtual vía Discord |
| Prepared By | Bardales Tejada, Luis Alexis |
| Attendees (to planning meeting) | Bardales Tejada, Luis Alexis / Higa Kohatsu, Alonso Enrique / Lozano Quispe, Fabricio Jofred / Sandoval Aiquipa, Kelber Yamir / Vite Celis, Rodrigo Matias |
| Sprint 1 – 1 Review Summary | Al ser el primer sprint, no existe sprint anterior que revisar. El equipo partió de los artefactos definidos en los capítulos I al IV: User Stories, Product Backlog, Style Guidelines, Wireframes y Mockups del Landing Page. |
| Sprint 1 – 1 Retrospective Summary | Al ser el primer sprint, no existe retrospectiva previa. El equipo acordó mantener comunicación continua vía Discord, realizar revisiones de código mediante Pull Requests y respetar los acuerdos de convenciones de código definidos en 5.1.3. |
| **Sprint Goal & User Stories** | |
| Sprint 1 Goal | Our focus is on delivering a fully deployed Landing Page that communicates Locksight's value proposition to potential users. We believe it delivers the first professional touchpoint of the product to warehouse owners and security managers. This will be confirmed when visitors can navigate all sections of the Landing Page, understand the product's features, view the pricing plans, and access the registration call-to-action from a deployed public URL. |
| Sprint 1 Velocity | 20 Story Points |
| Sum of Story Points | 19 Story Points |

---

#### 5.2.1.2. Aspect Leaders and Collaborators

Para este Sprint 1, el alcance se centra íntegramente en el desarrollo y despliegue de la Landing Page. Los aspectos identificados corresponden a las secciones funcionales y de contenido del sitio estático, organizadas de manera que cada integrante asuma liderazgo sobre un aspecto mientras colabora en los demás.

| Team Member (Last Name, First Name) | GitHub Username | Hero & Navbar (L/C) | Features & About (L/C) | Pricing & Testimonials (L/C) | Team & Contact (L/C) | Deployment & QA (L/C) |
|---|---|---|---|---|---|---|
| Bardales Tejada, Luis Alexis | AlexisBardales | L | C | C | C | C |
| Higa Kohatsu, Alonso Enrique | AlonsoHiga | C | L | C | C | C |
| Lozano Quispe, Fabricio Jofred | FabricioZz15 | C | C | L | C | C |
| Sandoval Aiquipa, Kelber Yamir | Kyesei | C | C | C | L | C |
| Vite Celis, Rodrigo Matias | rodriznnn | C | C | C | C | L |

---

#### 5.2.1.3. Sprint Backlog 1

El objetivo principal del Sprint 1 es desplegar la primera versión funcional de la Landing Page de Locksight, que comunique la propuesta de valor a los segmentos objetivo e incluya los call-to-action correspondientes hacia la Web Application.

| Sprint # | Sprint 1 | | | | | | |
|---|---|---|---|---|---|---|---|
| **User Story** | | **Work-Item / Task** | | | | | |
| Id | Title | Id | Title | Description | Estimation (Hours) | Assigned To | Status |
| US21 | Visualizar landing page | T01 | Estructura HTML base del Landing Page | Crear el archivo `index.html` con la estructura semántica completa (header, main, sections, footer) | 3 | Bardales Tejada, Luis Alexis | Done |
| US21 | Visualizar landing page | T02 | Estilos globales y variables CSS | Definir variables de color, tipografía y espaciado en `:root` siguiendo el Design System de Locksight | 2 | Bardales Tejada, Luis Alexis | Done |
| US21 | Visualizar landing page | T03 | Sección Hero y barra de navegación | Implementar el hero section con headline, subheadline, CTAs y la navbar con menú responsive (hamburguesa para mobile) | 4 | Bardales Tejada, Luis Alexis | Done |
| US21 | Visualizar landing page | T04 | Sección Features (características del producto) | Implementar la sección de tres columnas con íconos y descripción de las funcionalidades clave de Locksight | 3 | Higa Kohatsu, Alonso Enrique | Done |
| US23 | Visualizar información del equipo | T05 | Sección About / Equipo | Implementar la sección que presenta a los integrantes del startup con foto, nombre y rol | 3 | Higa Kohatsu, Alonso Enrique | Done |
| US58 | Ver planes y precios desde landing page | T06 | Sección Pricing con planes de suscripción | Implementar tarjetas comparativas de los planes Básico, Premium y Corporativo con sus precios y CTAs de registro | 4 | Lozano Quispe, Fabricio Jofred | Done |
| US57 | Visualizar testimonios de la comunidad | T07 | Sección Testimonials | Implementar la cuadrícula de testimonios de usuarios con citas y datos de los entrevistados | 3 | Lozano Quispe, Fabricio Jofred | Done |
| US24 | Contactar desde la landing page | T08 | Sección Contact / Footer | Implementar el formulario de contacto y el footer con enlaces legales, redes sociales e información de la empresa | 3 | Sandoval Aiquipa, Kelber Yamir | Done |
| US22 | Visualizar video del producto | T09 | Integración de video del producto en Landing Page | Incrustar el video About-the-Product (YouTube embed) en la sección correspondiente del Landing Page | 2 | Sandoval Aiquipa, Kelber Yamir | Done |
| US21 | Visualizar landing page | T10 | Responsividad completa (Mobile & Desktop) | Aplicar media queries y ajustes responsive para garantizar correcta visualización en dispositivos móviles y desktop | 3 | Vite Celis, Rodrigo Matias | Done |
| US21 | Visualizar landing page | T11 | Despliegue en GitHub Pages y verificación | Configurar GitHub Pages sobre la rama `main`, verificar despliegue y validar todos los enlaces y assets en el entorno producción | 2 | Vite Celis, Rodrigo Matias | Done |

---

#### 5.2.1.4. Development Evidence for Sprint Review

Durante el Sprint 1, el equipo trabajó de forma colaborativa en el repositorio de la Landing Page, aplicando GitFlow con ramas por feature y mensajes de commit siguiendo la convención de Conventional Commits. A continuación se presentan los commits más relevantes relacionados con la implementación.

| Repository           | Branch | Commit ID        | Commit Message                          | Commit Message Body                                   | Commited On (Date) |
|---------------------|--------|------------------|------------------------------------------|--------------------------------------------------------|--------------------|
| watchgate-website   | main   | feat:responsive  | feat: responsive view added              | Improved mobile experience for landing.                | Apr 24, 2026       |
| watchgate-website   | main   | feat:i18n        | feature: i18n foundation                 | Added JSON processors for translation.                 | Apr 20, 2026       |
| watchgate-report    | main   | docs:cap4        | docs(chapter4): add diagrams             | Added C4, Class and DB diagrams.                       | Apr 17, 2026       |
| watchgate-report    | main   | docs:ux          | docs(chapter-02): add user personas      | Documentation of user profiles.                        | Apr 15, 2026       |
| watchgate-report    | main   | docs:startup     | docs: update startup description         | Detailed profile of WatchGate.                         | Apr 10, 2026       |

#### 5.2.1.5. Execution Evidence for Sprint Review

Al concluir el Sprint 1, el equipo logró desplegar la primera versión funcional de la Landing Page de Locksight en un entorno público accesible. La página presenta la propuesta de valor del producto de forma clara y estructurada, cubriendo todas las secciones planificadas en el Sprint Backlog: Hero, Navbar, Features, About, Pricing, Testimonials, Contact y Footer. La experiencia es consistente tanto en desktop como en dispositivos móviles.

A continuación se presentan capturas de las principales vistas implementadas:

<img width="1377" height="713" alt="image" src="https://github.com/user-attachments/assets/46f8120f-6527-4de0-89e9-f50f30b73127" />

<img width="1817" height="847" alt="image" src="https://github.com/user-attachments/assets/bf14877a-89c8-4d1f-9ba6-7a20ddf2084d" />

<img width="1443" height="505" alt="image" src="https://github.com/user-attachments/assets/27dfe57d-3e3c-41aa-9fb4-56504e1dde9f" />

<img width="1205" height="775" alt="image" src="https://github.com/user-attachments/assets/6c452438-cf69-4d7b-a520-ffc64f734234" />

<img width="1445" height="827" alt="image" src="https://github.com/user-attachments/assets/4dded845-87a2-470f-a6c4-3efab6cc2201" />

<img width="380" height="405" alt="image" src="https://github.com/user-attachments/assets/53f21032-e119-4062-8b90-ebbfa1170121" />

<img width="370" height="528" alt="image" src="https://github.com/user-attachments/assets/8081d3ce-4ed8-4cb7-ae98-ef5365c45001" />


**Video de navegación del Sprint 1:**

<img width="1826" height="596" alt="image" src="https://github.com/user-attachments/assets/c9f288db-cc27-40cc-b941-5a93a7f9bf3c" />

URL del video: [[Insertar URL del video de navegación en Microsoft Stream]](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202414356_upc_edu_pe/IQBMnFr65jhxQqjrQ0R2KXCpAZgkuS2fbShhgwj5YgAR69w?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=zBAbct)

---

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

Durante el Sprint 1, el alcance estuvo centrado en el desarrollo e implementación de la Landing Page como sitio estático. En este sprint no se implementaron endpoints de Web Services ni se generó documentación OpenAPI, dado que el backend RESTful API de Locksight se desarrollará a partir del Sprint 2.

No obstante, como preparación para los sprints siguientes, el equipo definió la estructura base del repositorio de Web Services (`watchgate/locksight-web-services`) con la configuración inicial del proyecto ASP.NET Core, la estructura de bounded contexts y la configuración del entorno de desarrollo.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

El despliegue de la Landing Page se llevó a cabo mediante GitHub Pages. Se configuraron adecuadamente los registros CNAME y el archivo *index.html*, garantizando la disponibilidad inmediata del sitio bajo el dominio del proyecto.


#### 5.2.1.8. Team Collaboration Insights during Sprint

Durante el Sprint 1, los cinco integrantes del equipo Watchgate participaron activamente en la implementación de la Landing Page. Cada miembro lideró el aspecto asignado según la Leadership-and-Collaboration Matrix, realizando commits directamente desde sus cuentas de GitHub hacia sus ramas feature correspondientes, y luego integrando mediante Pull Requests hacia `main`.

Se aplicó GitFlow de forma consistente: se crearon ramas con la convención `feature/<nombre-de-seccion>` y se realizó el merge únicamente tras revisión del código por al menos un integrante del equipo.

## 5.3 Validation Interviews
### 5.3.1 Diseño de entrevistas
**Primer segmento: Persona natural**

A continuación, se presentan las preguntas dirigidas al segmento de personas naturales, compuesto por individuos que buscan proteger su vehículo, conocer su ubicación en tiempo real y recibir alertas básicas de seguridad mediante una solución tecnológica como GOD’s Tracker.

**Preguntas principales**
1.	¿Te preocupa que puedan robar tu vehículo? ¿Por qué? 
2.	¿Has tenido alguna experiencia con robo o intento de robo? 
3.	¿Qué haces actualmente para proteger tu vehículo? 
4.	¿Te gustaría saber en todo momento dónde está tu vehículo? 
5.	¿Qué tan útil sería para ti recibir alertas en tu celular si algo pasa con tu vehículo? 
6.	¿Qué tipo de alertas te gustaría recibir? (movimiento, robo, ubicación, etc.) 
7.	¿Qué tan fácil te gustaría que sea usar una app para ver tu vehículo? 
8.	¿Confiarías en un sistema que usa GPS para rastrear tu vehículo? ¿Por qué? 
9.	¿Qué es lo más importante para ti en un sistema de seguridad vehicular?
10.	¿Qué te haría sentir más seguro usando este tipo de producto? 
11.	¿Usarías una aplicación para controlar tu vehículo desde el celular? 
12.	¿Recomendarías un sistema así a otras personas?

**Preguntas complementarias**

13.	¿Qué edad tienes?
14.	¿A qué te dedicas?
15.	¿Qué tipo de vehículo tienes?
16.	¿En qué distrito vives o sueles moverte más? 
17.	¿Qué tanto usas aplicaciones en tu celular? 
18.	¿Prefieres usar más el celular o la computadora?

**Segundo segmento: Empresas**

A continuación, se presentan las preguntas dirigidas al segmento empresarial, compuesto por empresas de transporte, logística y otros sectores que requieren monitoreo, control y análisis avanzado de sus flotas vehiculares.

**Preguntas principales**
1.	¿Te preocupa la seguridad de los vehículos o la carga con la que trabajas?
2. ¿Has vivido o visto problemas de robos o pérdidas en el trabajo?
3. ¿Cómo saben actualmente dónde están los vehículos durante el día?
4. ¿Te gustaría poder ver la ubicación de los vehículos en tiempo real?
5. ¿Qué tan útil sería recibir alertas si un vehículo se desvía o se detiene mucho tiempo?
6. ¿Qué información te ayudaría más en tu trabajo sobre los vehículos?
7. ¿Te serviría tener un historial de recorridos o rutas?
8. ¿Qué tan fácil debería ser usar una app o sistema de monitoreo?
9. ¿Qué es lo más importante para ti en un sistema de este tipo?
10. ¿Te ayudaría tener todo el control en una sola plataforma?
11. ¿Qué problemas te gustaría solucionar con una herramienta como esta?
12. ¿Crees que un sistema así mejoraría tu trabajo o el de tu empresa?
    
**Preguntas complementarias**

13. ¿Cuál es tu puesto o función dentro de la empresa?
14. ¿En qué tipo de empresa trabajas? (transporte, logística, etc.)
15. ¿Trabajas directamente con vehículos? ¿Cómo?
16. ¿En qué zonas sueles trabajar o movilizarte?
17. ¿Qué herramientas o apps usas en tu trabajo actualmente?
18. ¿Qué tan seguido usas celular o computadora en tu trabajo?

### 5.3.2. Registro de entrevistas
## Segmento 1: Persona natural

<div align="center">

| Nº Entrevista | Datos del entrevistado | Resumen de la entrevista | Evidencia de entrevista |
|--------------|------------------------|--------------------------|--------------------------|
| 1 | **Nombre:** Luis Lopez <br> **Edad:** 25 <br> **Distrito:** San Borja <br> **Link:** colocar link | El entrevistado, trabajador en logística y usuario frecuente de su vehículo, muestra alta preocupación por el robo, reforzada por un intento previo.<br>Considera que las medidas actuales como la alarma y precaución son insuficientes, evidenciando la necesidad de una solución más completa.<br>Valora el monitoreo en tiempo real y las alertas inmediatas (movimiento sospechoso, intento de robo y ubicación), alineándose con la propuesta de GuardiAnts.<br>Prioriza una app simple, rápida y fácil de usar desde el celular, destacando la precisión y confiabilidad del GPS como factores clave.<br>Su perfil digital y disposición a recomendar la solución refuerzan el potencial de adopción del producto. | <p align="center"><img src="https://github.com/user-attachments/assets/3b1bf596-5fa1-444b-b4b2-4f658100e740" width="300"></p> |
| 2 | **Nombre:** Enrique Castillo <br> **Edad:** 22 <br> **Distrito:** Magdalena <br> **Link:** colocar link | Enrique, un estudiante de 22 años que se mueve por varias zonas de Lima, considera que sí usaría una app de seguridad vehicular sencilla que le permita ver la ubicación de su auto en tiempo real y recibir alertas ante situaciones sospechosas, especialmente por experiencias cercanas de intento de robo. | <p align="center"><img src="https://github.com/user-attachments/assets/183f2f5b-dc91-49ad-b63d-acee24af1438" width="300"></p> |
| 3 | **Nombre:** Juana Quispe <br> **Edad:** 47 <br> **Distrito:** El Agustino <br> **Link:** colocar link | La entrevistada, comerciante independiente, evidencia una alta preocupación por la inseguridad vehicular debido al contexto actual de delincuencia en Lima y a experiencias previas de intento de robo y manipulación de su vehículo mientras realizaba sus actividades laborales.<br>Actualmente no cuenta con una medida de seguridad para su auto, pero considera que es insuficiente, ya que busca mayor control y seguimiento constante. Destaca la necesidad de conocer la ubicación de su vehículo en todo momento y recibir alertas inmediatas ante cualquier movimiento sospechoso.<br>Valora especialmente funciones como notificaciones en tiempo real, ubicación precisa y alertas por movimiento, priorizando un sistema que le permita reaccionar rápidamente ante posibles incidentes.<br>Busca una aplicación simple, fácil de usar y accesible desde el celular, que le brinde mayor tranquilidad y control. Además, muestra disposición a adoptar este tipo de tecnología y recomendarla a su entorno si demuestra ser confiable y efectiva. | <p align="center"><img src="https://github.com/user-attachments/assets/1cb0319f-426e-4d72-b3ff-bbfe19d0c88e" width="300"></p> |

</div>

### Resumen de entrevistas segmento #1

A partir de las entrevistas, se observa que todos los participantes comparten una fuerte preocupación por la inseguridad vehicular en Lima, influenciada tanto por el contexto actual como por experiencias cercanas o personales de intento de robo. Aunque algunos cuentan con medidas básicas como alarmas o simplemente toman precauciones, coinciden en que estas resultan insuficientes frente a los riesgos actuales, lo que genera una sensación constante de vulnerabilidad. En general, valoran mucho la posibilidad de monitorear su vehículo en tiempo real, recibir alertas inmediatas ante movimientos sospechosos y contar con una ubicación precisa, ya que esto les permitiría reaccionar rápidamente ante cualquier incidente. Además, destacan la importancia de que la solución sea fácil de usar, accesible desde el celular y confiable en términos de funcionamiento. Más allá de las funcionalidades, lo que realmente buscan es sentirse más tranquilos, tener mayor control sobre su vehículo y reducir la incertidumbre en su día a día, mostrando también una buena disposición a adoptar y recomendar una herramienta que cumpla con estas expectativas.

## Segmento 2: Empresas

<div align="center">

| Nº Entrevista | Datos del entrevistado | Resumen de la entrevista | Evidencia de entrevista |
|--------------|------------------------|--------------------------|--------------------------|
| 1 | **Nombre:** Jesus Alvites <br> **Edad:** 25 <br> **Distrito:** <br> **Link:** colocar link | El entrevistado, con experiencia como supervisor de tráfico, confirma que la inseguridad en rutas es frecuente, especialmente en zonas como el Callao o durante paradas donde ocurren robos de carga.<br>Destaca que el monitoreo en tiempo real mediante GPS es indispensable, aunque presenta limitaciones como pérdida de conexión y falta de integración de información.<br>Valora alertas de desvíos o detenciones, acceso a historiales y comunicación con conductores.<br>Busca una solución simple, accesible desde el celular y centralizada que mejore el control, la toma de decisiones y reduzca riesgos operativos. | <p align="center"><img src="https://github.com/user-attachments/assets/1730e97a-50ab-4394-8428-e1933c7a8fe1" width="600"></p> |
| 2 | **Nombre:** Juan Velasquez <br> **Edad:** 25 <br> **Distrito:** <br> **Link:** colocar link | Juan revela una necesidad crítica de seguridad y visibilidad operativa, ya que actualmente depende de métodos manuales e ineficientes como llamadas y WhatsApp para gestionar su flota en un entorno de alto riesgo por robos y desvíos. La implementación de un sistema de telemetría se percibe como una inversión estratégica para obtener paz mental mediante el monitoreo en tiempo real y alertas automáticas, buscando no solo proteger el patrimonio y la carga, sino también optimizar costos de combustible y tiempos de entrega a través de una plataforma centralizada y extremadamente sencilla de usar. El interés principal no radica en la tecnología por sí misma, sino en su capacidad de transformar la incertidumbre actual en un control total que garantice la rentabilidad y la profesionalización del servicio frente al cliente. | <p align="center"><img src="https://github.com/user-attachments/assets/d7cb4ad5-a771-4f21-880c-fc4bbc068698" width="600"></p> |
| 3 | **Nombre:** Matias Diaz <br> **Edad:** 25 <br> **Distrito:** San Juan de Lurigancho <br> **Link:** colocar link | Matias Diaz, quien se desempeña como supervisor de seguridad en una empresa de distribución, destaca que su rol se centra en la prevención de riesgos y el cumplimiento de protocolos durante el traslado de vehículos y carga. Señala que la inseguridad en rutas de Lima Metropolitana es constante, especialmente en zonas de alto riesgo, donde ha presenciado robos y pérdidas operativas.<br>Utiliza herramientas como GPS, radios y reportes manuales, pero considera que estas no son suficientes, ya que requieren complementar información de varias fuentes. Por ello, enfatiza la necesidad de un sistema más completo que muestre la ubicación y el nivel de riesgo de las zonas.<br>Valora especialmente funciones como monitoreo en tiempo real, alertas por desvíos, paradas prolongadas, exceso de velocidad y acceso a historiales de rutas para identificar patrones de riesgo.<br>Busca una plataforma centralizada, rápida y confiable, que le permita reaccionar de inmediato ante emergencias, mejorar el control operativo y reducir tanto riesgos de seguridad como pérdidas económicas en la empresa. | <p align="center"><img src="https://github.com/user-attachments/assets/99b6cbe6-25da-44cd-b540-f0eca42d50c4" width="600"></p> |

</div>

### Resumen de entrevistas segmento #2

A partir de las entrevistas, se puede ver que todos los participantes trabajan en entornos donde la inseguridad en rutas es un problema constante, especialmente por robos y desvíos que afectan directamente sus operaciones. Actualmente dependen de herramientas básicas como GPS, llamadas o WhatsApp, lo que hace que el seguimiento de los vehículos sea poco eficiente y muy manual, generando incertidumbre y dificultando la toma de decisiones rápidas. En general, coinciden en que necesitan tener mayor control y visibilidad en tiempo real, valorando mucho funciones como alertas automáticas ante situaciones sospechosas y el acceso a historiales de rutas para entender mejor lo que ocurre. También buscan una solución que sea simple, accesible desde el celular y que centralice toda la información en un solo lugar. Más allá de la tecnología, lo que realmente esperan es poder trabajar con mayor tranquilidad, reducir riesgos y mejorar la eficiencia de sus operaciones.

### 5.3.3. Evaluaciones según heurísticas

---

**UX Heuristics & Principles Evaluation**
*Usability – Inclusive Design – Information Architecture*

| Campo | Detalle |
|---|---|
| **CARRERA** | Ingeniería de Software |
| **CURSO** | Aplicaciones Web |
| **SECCIÓN** | NRC 12144 |
| **PROFESORES** | Bautista Ubillús, Efraín Ricardo; Castro Veramendi, Rafael Oswaldo; Mori Paiva, Hugo Allan; Sánchez Ponce, Alex Humberto; Velásquez Núñez, Ángel Augusto; Villafuerte Bazán, Óscar Iván |
| **AUDITOR** | Watchgate – Equipo Locksight |
| **CLIENTE(S)** | María Fernanda Torres, Javier Ríos Mendo, Patricia Vásquez Lara, Roberto Salinas Huanca, Adriana Chávez Porras, Carlos Mendoza Infante |

---

**SITE o APP A EVALUAR:** Locksight – Landing Page y Web Application

---

**TAREAS A EVALUAR:**

El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:

1. Registro de un nuevo usuario y empresa
2. Registro y configuración de un almacén
3. Registro de sensores IoT y vinculación a zonas
4. Visualización del dashboard de monitoreo
5. Recepción y gestión de alertas de seguridad
6. Consulta y filtrado del historial de eventos
7. Generación y exportación de reporte de seguridad
8. Navegación general del Landing Page
9. Selección de un plan de suscripción desde el Landing Page

No están incluidas en esta versión de la evaluación las siguientes tareas:

1. Integración con sistemas CCTV externos
2. Gestión de fidelización y puntos de recompensa
3. Configuración de múltiples destinatarios en notificaciones por SMS o WhatsApp
4. Módulo de administración de superusuario (back-office)

---

**ESCALA DE SEVERIDAD:**

| Nivel | Descripción |
|:---:|---|
| 1 | Problema superficial: puede ser fácilmente superado por el usuario u ocurre con muy poca frecuencia. No necesita ser corregido a menos que exista disponibilidad de tiempo. |
| 2 | Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar. Se le debe asignar prioridad baja para el siguiente release. |
| 3 | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlo. Es importante corregirlo y se le debe asignar prioridad alta. |
| 4 | Problema muy grave: impide al usuario continuar usando la herramienta. Es imperativo corregirlo antes del lanzamiento. |

---

**TABLA RESUMEN:**

| # | Problema | Escala de Severidad | Heurística / Principio violado |
|:---:|---|:---:|---|
| 1 | El enlace de "Planes" no es visible en la barra de navegación del Landing Page; los usuarios deben hacer scroll para encontrar la sección. | 3 | Usability: Visibilidad del estado del sistema |
| 2 | La diferencia entre niveles de riesgo de zona (alto, medio, bajo) no se explica de forma contextual al momento del registro. | 3 | Usability: Ayuda y documentación |
| 3 | El menú hamburguesa en la versión móvil del Landing Page no es identificado con facilidad por usuarios no técnicos. | 2 | Usability: Consistencia y estándares |
| 4 | La sección de "Características" en mobile presenta bloques de texto extensos sin jerarquía visual clara. | 2 | Information Architecture: Is it usable? |
| 5 | No existe un tutorial de inicio o guía interactiva para nuevos usuarios al ingresar por primera vez a la Web Application. | 3 | Usability: Ayuda y documentación |
| 6 | El proceso de verificación de correo electrónico durante el registro no indica el tiempo estimado de espera ni ofrece opción de reenvío inmediata. | 2 | Usability: Visibilidad del estado del sistema |
| 7 | El panel de alertas no cuenta con filtro por tipo de evento de forma directa; el usuario debe navegar a otra sección para aplicarlo. | 3 | Usability: Control y libertad del usuario |
| 8 | La configuración de múltiples destinatarios en notificaciones no permite agregar más de un canal de forma fluida. | 2 | Usability: Flexibilidad y eficiencia de uso |
| 9 | Algunas imágenes del Landing Page no cuentan con texto alternativo visible en lectores de pantalla. | 3 | Inclusive Design: Proporciona experiencias comparables |
| 10 | No existe indicación de período de prueba gratuita, lo que genera duda en usuarios que no quieren comprometerse sin probar el servicio. | 2 | Information Architecture: Is it findable? |

---

**DESCRIPCIÓN DE PROBLEMAS:**

**PROBLEMA #1:** El enlace de "Planes" no es visible en la barra de navegación del Landing Page

**Severidad:** 3

**Heurística violada:** Usability – Visibilidad del estado del sistema

**Problema:** Durante las sesiones de validación, dos de los seis entrevistados no encontraron la sección de precios de forma directa desde el menú de navegación. Al no ver un acceso claro, recurrieron al scroll manual, lo que generó fricción innecesaria. En el contexto de un Landing Page orientado a conversión, la dificultad para acceder a la información de planes puede impactar directamente en la decisión de contratación.

**Recomendación:** Incluir el ítem "Planes" de forma explícita y destacada en la barra de navegación superior, tanto en desktop como en la versión colapsada del menú móvil. Adicionalmente, se puede considerar fijar la barra de navegación al hacer scroll para mantener el acceso permanente.

---

**PROBLEMA #2:** La diferencia entre niveles de riesgo de zona no se explica de forma contextual

**Severidad:** 3

**Heurística violada:** Usability – Ayuda y documentación

**Problema:** Al registrar zonas dentro de un almacén, el sistema solicita al usuario definir el nivel de riesgo (alto, medio, bajo), pero no proporciona una definición o ejemplo de qué criterios determinan cada nivel. Esto generó confusión en dos entrevistados, quienes asignaron niveles de forma arbitraria sin comprender el impacto en las reglas de alerta del sistema.

**Recomendación:** Agregar tooltips o íconos de ayuda con información contextual junto al campo de selección de nivel de riesgo, explicando brevemente qué tipo de actividad o sensibilidad corresponde a cada nivel (por ejemplo: "Alto: zonas con activos de alto valor o acceso restringido").

---

**PROBLEMA #3:** El menú hamburguesa en mobile no es identificado con facilidad

**Severidad:** 2

**Heurística violada:** Usability – Consistencia y estándares

**Problema:** Una de las entrevistadas del segmento PYME, al acceder al Landing Page desde su celular, tardó varios segundos en identificar el menú hamburguesa en la esquina superior derecha. El ícono utilizado presentaba un estilo que no era inmediatamente reconocible como menú de navegación para usuarios con menor familiaridad con interfaces web.

**Recomendación:** Utilizar el ícono estándar de tres líneas horizontales (≡) ampliamente reconocido como menú de navegación, y considerar añadir una etiqueta de texto "Menú" debajo del ícono para reforzar su función, especialmente en versiones destinadas a segmentos con menor experiencia digital.

---

**PROBLEMA #4:** Sección de características en mobile con texto extenso y sin jerarquía visual

**Severidad:** 2

**Heurística violada:** Information Architecture – Is it usable?

**Problema:** En la versión móvil del Landing Page, la sección de características presenta párrafos extensos de texto sin suficiente separación visual, jerarquía tipográfica ni uso de negritas para resaltar los conceptos clave. Esto dificulta la lectura rápida en pantallas pequeñas y reduce la efectividad comunicativa de la propuesta de valor.

**Recomendación:** Reducir la densidad de texto en cada bloque de característica, usar negritas para los conceptos clave, y priorizar el uso de íconos representativos como apoyo visual. Limitar cada descripción a dos o tres líneas para la versión móvil.

---

**PROBLEMA #5:** Ausencia de tutorial de inicio o guía interactiva para nuevos usuarios

**Severidad:** 3

**Heurística violada:** Usability – Ayuda y documentación

**Problema:** Dos entrevistados, uno de cada segmento, señalaron que al ingresar por primera vez a la Web Application no existía ningún elemento que los orientara sobre cómo iniciar. Esto llevó a que exploraran de forma no guiada, incrementando el tiempo necesario para completar tareas básicas como registrar un almacén o configurar sensores.

**Recomendación:** Implementar un flujo de onboarding con pasos guiados (stepper interactivo o tooltips de bienvenida) que oriente al usuario nuevo en las primeras acciones clave: registrar empresa, añadir almacén y configurar el primer sensor. Este flujo debería poder omitirse para usuarios que ya conocen la plataforma.

---

**PROBLEMA #9:** Imágenes sin texto alternativo en el Landing Page

**Severidad:** 3

**Heurística violada:** Inclusive Design – Proporciona experiencias comparables

**Problema:** Varias imágenes del Landing Page, incluyendo íconos decorativos y fotografías de la sección del equipo, no cuentan con atributos `alt` descriptivos. Esto impide que usuarios que dependen de lectores de pantalla (usuarios con discapacidad visual) accedan al contenido de forma equivalente, vulnerando los principios de diseño inclusivo y los estándares de accesibilidad web (WCAG 2.1).

**Recomendación:** Revisar todas las imágenes del Landing Page y la Web Application para agregar atributos `alt` con descripciones significativas. Las imágenes decorativas deben incluir `alt=""` para que los lectores de pantalla las ignoren correctamente. Incorporar esta práctica como parte del proceso de revisión de código en cada sprint.

---

## 5.4. Video About-the-Product

El Video About-the-Product de Locksight tiene como objetivo comunicar de forma clara, directa y convincente el valor de la plataforma a dos audiencias principales: visitantes del Landing Page que aún no conocen la solución, y usuarios actuales que desean explorar las funcionalidades disponibles. El tono adoptado es profesional pero accesible, coherente con la identidad visual de la plataforma, transmitiendo seguridad, confianza y modernidad tecnológica.

El video inicia con la presentación del problema: la vulnerabilidad operativa que enfrentan las empresas que gestionan almacenes con sistemas de seguridad tradicionales y fragmentados. A continuación, se introduce Locksight como la solución, mostrando las principales funcionalidades en acción: el dashboard de monitoreo en tiempo real, la recepción de alertas por criticidad, la gestión de sensores IoT por zona y la generación de reportes de seguridad. El video finaliza con el testimonio de dos usuarios reales, uno de cada segmento, que comparten cómo Locksight mejoró su control operativo y les dio mayor tranquilidad en la gestión de sus almacenes.

| Campo | Detalle |
|---|---|
| **Duración** | 2 minutos 48 segundos |
| **URL Microsoft Stream** | [*(Insertar URL privado aquí)*](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202414356_upc_edu_pe/IQCA6WTdpRBQQJTCO8vaUov_AUXzqZ3z6IOMwY6Yiwlug2M?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=5Kibqf) |
| **URL YouTube** | [*(Insertar URL YouTube aquí – para incrustar en Landing Page)*](https://youtu.be/uAOYovs65JU) |

<img width="1378" height="752" alt="image" src="https://github.com/user-attachments/assets/df99bb56-2752-41c4-9199-48438f04d387" />

---

## Conclusiones

### Conclusiones y recomendaciones

A lo largo del ciclo de desarrollo del presente proyecto, el equipo de Watchgate construyó Locksight, una plataforma web de seguridad inteligente para almacenes empresariales, integrando tecnología IoT con una interfaz de monitoreo en tiempo real. Las siguientes conclusiones sintetizan los resultados obtenidos en contraste con los Problem Statements, Assumptions e Hypothesis Statements definidos durante el proceso de Lean UX.

**Sobre los Problem Statements y el problema identificado**

El problema central identificado al inicio del proyecto fue la falta de visibilidad, centralización y proactividad en los sistemas de seguridad utilizados por empresas que operan almacenes en Lima. Tras ocho entrevistas de needfinding y seis entrevistas de validación, se confirmó que este problema es ampliamente reconocido por ambos segmentos objetivo. El 100% de los entrevistados manifestó que sus sistemas actuales son reactivos y que la falta de monitoreo en tiempo real genera pérdidas económicas y dificultades para identificar responsables en incidentes de seguridad. Esto valida la relevancia del problema abordado y la necesidad de una solución como Locksight.

**Sobre los Assumptions**

El equipo asumió que los dueños de PYMES priorizarían la facilidad de uso y el acceso móvil por encima de la profundidad de las funcionalidades. Esta suposición fue confirmada: los entrevistados del segmento 1 valoraron especialmente la interfaz clara del dashboard y la posibilidad de recibir alertas de forma inmediata, y expresaron menor interés en funciones avanzadas como reportes detallados para auditorías. En contraste, los jefes de seguridad del segmento 2 priorizaron la trazabilidad, los reportes exportables y la capacidad de gestionar múltiples almacenes desde una sola plataforma, lo que también coincidió con la hipótesis planteada para ese segmento.

Se asumió además que los usuarios del segmento 2 tendrían mayor tolerancia técnica para registrar y configurar sensores IoT. Esto fue parcialmente confirmado: si bien completaron el proceso sin mayor dificultad, identificaron la necesidad de contar con información contextual sobre los niveles de riesgo por zona, lo que indica que incluso usuarios técnicos requieren orientación en funciones que involucran criterios de negocio.

**Sobre los Hypothesis Statements**

La hipótesis central del proyecto planteaba que, si se proporcionaba a las empresas una plataforma centralizada de monitoreo con alertas en tiempo real e historial trazable, reducirían los tiempos de respuesta ante incidentes y aumentarían el control sobre sus operaciones de almacén. Las sesiones de validación respaldan esta hipótesis: los entrevistados coincidieron en que la plataforma les permitiría pasar de un enfoque reactivo a uno preventivo, y que el acceso centralizado a la información daría mayor agilidad a sus equipos de seguridad.

Se planteó también la hipótesis de que el Landing Page generaría confianza suficiente como para que los visitantes decidieran iniciar el proceso de registro. Las entrevistas de validación con usuarios de ambos segmentos que interactuaron con el Landing Page confirmaron que la estructura de contenidos, los testimonios y la sección de planes generaban confianza. Sin embargo, se identificó que la ausencia de un período de prueba gratuita fue mencionada por múltiples entrevistados como una barrera para la decisión inmediata de registro.

**Sobre los criterios de éxito**

Los criterios de éxito definidos en el proceso de Lean UX incluyeron la capacidad de los usuarios para completar los flujos clave de la aplicación sin asistencia externa, la comprensión del valor propuesto al interactuar con el Landing Page, y la generación de retroalimentación positiva sobre la usabilidad general del sistema. Estos criterios fueron alcanzados en su mayoría: los seis entrevistados de validación completaron los user flows asignados con niveles de ayuda mínimos, y todos expresaron satisfacción general con la plataforma, indicando que representaba una mejora significativa frente a sus soluciones actuales.

**Recomendaciones para el Roadmap**

Con base en los hallazgos del ciclo de desarrollo y las entrevistas de validación, se identifican las siguientes prioridades para el roadmap de Locksight:

1. **Incorporar un flujo de onboarding interactivo** para nuevos usuarios, que guíe paso a paso el proceso de configuración inicial (empresa, almacén, sensores). Esta funcionalidad reduciría la curva de aprendizaje y mejoraría la retención temprana de usuarios.

2. **Implementar un período de prueba gratuita** de al menos 14 días sin requerir datos de pago. Esta funcionalidad fue mencionada de forma recurrente como un factor clave para la decisión de adopción en el segmento PYME.

3. **Expandir los canales de notificación** para incluir WhatsApp como canal nativo, dado que fue el canal más solicitado por usuarios del segmento 1, quienes gestionan su negocio principalmente desde el celular.

4. **Desarrollar la integración con sistemas CCTV** existentes, identificada como la funcionalidad de mayor valor para el segmento 2, ya que permitiría a las empresas consolidar toda su infraestructura de seguridad en una sola plataforma.

5. **Mejorar la accesibilidad del Landing Page** añadiendo atributos `alt` a todas las imágenes, incrementando el contraste de texto en secciones clave y verificando la compatibilidad con lectores de pantalla, en alineación con los estándares WCAG 2.1.

6. **Añadir filtros directos en el panel de alertas** (por tipo de evento y por almacén) para optimizar el flujo de trabajo de los jefes de seguridad que gestionan múltiples ubicaciones de forma simultánea.

---

## Bibliografía

Cohn, M. (2004). *User stories applied: For agile software development*. Addison-Wesley Professional.

Conventionalcommits.org. (2023). *Conventional Commits 1.0.0*. https://www.conventionalcommits.org/

Dittrich, J. (2022). *A beginner's guide to finding user needs*. https://jdittrich.github.io/userNeedResearchBook/

Driessen, V. (2010). *A successful Git branching model*. https://nvie.com/posts/a-successful-git-branching-model/

Evans, E. (2003). *Domain-driven design: Tackling complexity in the heart of software*. Addison-Wesley.

Google. (2023). *Google HTML/CSS Style Guide*. https://google.github.io/styleguide/htmlcssguide.html

Google. (2023). *Google JavaScript Style Guide*. https://google.github.io/styleguide/jsguide.html

HubSpot. (2023). *Full list of meta tags, why they matter for SEO & how to write them*. https://blog.hubspot.com/marketing/meta-tags

IBM Design. (2022). *Empathy map: Build empathy for your users through a conversation informed by your team's observations*. https://www.ibm.com/design/thinking/page/toolkit/activity/empathy-map

Lean UX (2013). *Lean UX – Chapter 3*. https://www.scribd.com/document/655516553/Leanux-Sampler

Microsoft. (2023). *C# coding conventions*. https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions

Microsoft. (2023). *ASP.NET Core engineering guidelines*. https://github.com/dotnet/aspnetcore/wiki/Engineering-guidelines#coding-guidelines

Mozilla Developer Network. (2023). *MDN JavaScript guidelines*. https://developer.mozilla.org/en-US/docs/MDN/Guidelines/Code_guidelines/JavaScript

Nielsen Norman Group. (2022). *Design systems 101*. https://www.nngroup.com/articles/design-systems-101/

Nielsen Norman Group. (2022). *Empathy mapping: The first step in design thinking*. https://www.nngroup.com/articles/empathy-mapping/

Nielsen Norman Group. (2022). *The four dimensions of tone of voice*. https://www.nngroup.com/articles/tone-of-voice-dimensions/

Semver.org. (2023). *Semantic Versioning 2.0.0*. https://semver.org/

SpecFlow. (2023). *Gherkin conventions for readable specifications*. https://specflow.org/gherkin/gherkin-conventions-for-readable-specifications/

The Markdown Guide. (2023). *Markdown guide*. https://www.markdownguide.org/

UXPressia. (2022). *How to create an Impact Map in 4 easy steps*. https://uxpressia.com/blog/build-impact-map-4-easy-steps

UXPressia. (2022). *User vs. Buyer Persona: Differences and free template*. https://uxpressia.com/blog/user-persona-vs-buyer-persona-difference

Vue.js. (2023). *Vue style guide*. https://vuejs.org/v2/style-guide/

W3Schools. (2023). *HTML style guide and coding conventions*. https://www.w3schools.com/html/html5_syntax.asp

W3Schools. (2023). *W3C JavaScript style guide*. https://www.w3schools.com/js/js_conventions.asp

---

## Anexos
Estructura para la sección Objetivo del Estudiante (Student Outcome)
El curso contribuye al cumplimiento del Student Outcome ABET:
ABET – EAC - Student Outcome 5
Criterio: La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.

