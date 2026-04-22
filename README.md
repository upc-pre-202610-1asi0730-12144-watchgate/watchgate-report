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

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores.
### 2.1.1. Análisis competitivo

## ¿Por qué llevar a cabo este análisis?
**Objetivo:**  
Identificar y comparar a los principales competidores en soluciones de seguridad IoT y rastreo de flotas, con el fin de definir ventajas competitivas, estrategias de precios y oportunidades de diferenciación para nuestra startup en el mercado.


| Característica | Su Startup | Competidor 1: Ditrack | Competidor 2: Global GPS Perú | Competidor 3: Soluciones Globales |
|--------------|------------|------------------------|-------------------------------|----------------------------------|
| Logo | <div align="center"><img src="https://github.com/user-attachments/assets/d4d14a4a-26cc-4a51-834c-40f43ed119cf" width="180"/></div> | <div align="center"><img src="https://github.com/user-attachments/assets/c33c57af-5c5c-4616-a47e-48dee729ecdf" width="120"/></div> | <div align="center"><img src="https://github.com/user-attachments/assets/4c19f285-e721-42c2-bc3e-ffd711ece1ce" width="120"/></div> | <div align="center"><img src="https://github.com/user-attachments/assets/d48af284-5bf4-4f6f-ba42-dfc65162d044" width="120"/></div> |
| Overview | Plataforma IoT que integra sensores físicos y software para monitoreo en tiempo real de almacenes y rutas. | Empresa líder en rastreo satelital con larga trayectoria en Perú. | Empresa enfocada en GPS accesible para pymes con planes simples. | Empresas globales con soluciones avanzadas de gestión de flotas e IoT. |
| Perfil | Startup tecnológica enfocada en innovación IoT aplicada a seguridad. | Empresa consolidada con enfoque en monitoreo tradicional. | Empresa pequeña enfocada en soluciones económicas. | Corporaciones tecnológicas con soluciones avanzadas. |
| Ventaja competitiva | Monitoreo inteligente + detección de anomalías + integración almacén + flota. | Experiencia, cumplimiento normativo y monitoreo confiable 24/7. | Bajo costo + facilidad de uso. | Tecnología avanzada, escalabilidad global y analítica. |
| ¿Qué valor ofrece? | Control total, prevención de riesgos y toma de decisiones en tiempo real. | Seguridad confiable y cumplimiento legal. | Ahorro y accesibilidad para pymes. | Optimización operativa y análisis avanzado. |
| Mercado objetivo | Empresas logísticas, almacenes, pymes y medianas empresas. | Grandes flotas, minería y transporte formal. | Pymes de transporte y logística. | Empresas globales y grandes flotas. |
| Estrategias de marketing | Enfoque en innovación, eficiencia y seguridad inteligente. | Posicionamiento como empresa confiable y líder. | Estrategia basada en precios bajos. | Marketing digital global y branding fuerte. |
| Perfil de Producto | Sensores IoT + plataforma web + alertas inteligentes + trazabilidad. | GPS vehicular + monitoreo + reportes. | GPS + plataforma básica + alertas. | GPS + dashboards + cámaras + analítica avanzada. |
| Precios & Costos | Planes mensuales escalonados (Básico, Profesional, Empresarial). | Desde aprox. S/600 mensual por vehículo. | Desde S/550 anuales. | Desde ~$16 USD mensual por activo. |
| Canales de distribución | Web + app móvil propia. | Web + app + instalación física. | Web + WhatsApp + app. | Web + app + integraciones empresariales. |
| Fortalezas | Innovación IoT, integración completa, escalabilidad. | Marca fuerte, experiencia, cumplimiento legal. | Precio competitivo y accesibilidad. | Tecnología avanzada y gran inversión en I+D. |
| Debilidades | Falta de posicionamiento y experiencia. | Menor innovación tecnológica. | Baja diferenciación y alcance limitado. | Costos elevados y menor enfoque local. |
| Oportunidades | Crecimiento del IoT y necesidad de seguridad inteligente. | Integrar nuevas tecnologías. | Expansión a nuevos segmentos. | Expansión en Latinoamérica. |
| Amenazas | Competidores posicionados y barrera de confianza. | Nuevas startups innovadoras. | Alta competencia en precios. | Regulaciones y competencia local. |

### 2.1.2. Estrategias y tácticas frente a competidores

En el mercado actual existen distintas soluciones de seguridad para almacenes, desde sistemas tradicionales solo enfocados en alarmas hasta plataformas avanzadas de videovigilancia. Sin embargo, muchas de estas opciones se limitan a registrar incidentes, sin enfocarse en prevenirlos o analizarlos en tiempo real. Ante esta situación, nuestra propuesta se diferencia al integrar monitoreo en tiempo real, tecnología IoT adaptable y análisis inteligente en una sola plataforma, accesible para empresas de distintos tamaños.

#### Estrategia de diferenciación tecnológica
Nuestra propuesta se posiciona como una solución integral que reúne monitoreo en tiempo real, sensores IoT y análisis inteligente en un solo sistema. En comparación de otros competidores que ofrecen estos servicios por separado, nosotros buscamos simplificar la gestión a través de un dashboard intuitivo que permita controlar sensores, alertas y accesos desde un único lugar.

#### Estrategia de inserción en el mercado
Puesto que existen empresas consolidadas con alta reputación, nuestra entrada al mercado se enfocará en la implementación de pruebas piloto en pequeñas y medianas empresas. Esto nos permitirá demostrar la efectividad del sistema, generar casos de éxito reales y reducir la desconfianza hacia una nueva startup.

#### Estrategia de captación de clientes
Aprovechando la creciente digitalización de las empresas peruanas, ofreceremos un modelo SaaS flexible y escalable. Los planes de suscripción estarán diseñados según la cantidad de almacenes que maneje cada empresa, permitiendo que elijan la opción que mejor se adapte a sus necesidades y presupuesto.

#### Estrategia frente a lo existente
Para empresas que aún utilizan sistemas tradicionales, ya sea por desconfianza o por los elevados costos, nuestra estrategia será demostrar de forma clara los beneficios de la solución, como la facilidad de uso y capacidad preventiva. Buscaremos posicionarnos no solo como una alternativa tecnológica, sino como una inversión rentable que mejora la seguridad y optimiza la operación.

## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas
**Primer segmento: Dueños y Administradores de PYMES**

A continuación, se presentan las preguntas dirigidas al segmento de dueños y administradores de pequeñas y medianas empresas, quienes buscan tener mayor control y seguridad sobre sus almacenes sin necesidad de sistemas complejos o costosos.

**Preguntas principales**
1. ¿Te preocupa la seguridad de tu almacén o negocio?
2. ¿Has tenido problemas de robos o pérdidas dentro de tu local?
3. ¿Cómo controlas actualmente quién entra o sale de tu almacén?
4. ¿Te gustaría saber en tiempo real lo que pasa en tu almacén?
5. ¿Qué tan útil sería recibir alertas en tu celular si ocurre algo extraño?
6. ¿Qué tipo de alertas te gustaría recibir? (puertas abiertas, movimiento, fuera de horario, etc.)
7. ¿Te ayudaría poder revisar lo que pasó en el almacén en cualquier momento?
8. ¿Qué tan fácil debería ser usar una app para controlar tu almacén?
9. ¿Qué es lo más importante para ti en un sistema de seguridad?
10. ¿Te daría tranquilidad poder ver todo desde tu celular sin estar presente?
11. ¿Qué problemas te gustaría evitar con una herramienta como esta?
12. ¿Usarías una solución como Locksight en tu negocio?

**Preguntas complementarias**

13. ¿Qué edad tienes?
14. ¿A qué se dedica tu negocio?
15. ¿Cuántas personas trabajan contigo?
16. ¿En qué distrito está tu negocio?
17. ¿Usas aplicaciones en tu celular para tu negocio? ¿Cuáles?
18. ¿Qué tan seguido revisas tu negocio cuando no estás presente?
19. ¿Prefieres usar más el celular o la computadora?
20. ¿Qué tan cómodo te sientes usando tecnología nueva?

**Segundo segmento: Jefes de Seguridad y Operaciones**

A continuación, se presentan las preguntas dirigidas al segmento de jefes de seguridad y operaciones, quienes necesitan controlar almacenes de mayor tamaño, tener registro de accesos y tomar decisiones basadas en información.

**Preguntas principales**
1. ¿Te preocupa la seguridad de los almacenes o instalaciones que supervisas?
2. ¿Qué problemas has tenido con accesos no autorizados o pérdidas?
3. ¿Cómo controlan actualmente quién entra y sale de los almacenes?
4. ¿Te gustaría tener información en tiempo real de lo que ocurre en cada almacén?
5. ¿Qué tan útil sería recibir alertas automáticas ante movimientos sospechosos?
6. ¿Qué tipo de alertas serían más útiles para tu trabajo?
7. ¿Te serviría tener un historial de accesos y eventos del almacén?
8. ¿Qué tan importante es para ti poder revisar información desde cualquier lugar?
9. ¿Qué es lo más importante en un sistema de seguridad para almacenes?
10. ¿Te ayudaría tener todo el control en una sola plataforma?
11. ¿Qué problemas actuales te gustaría solucionar con una herramienta como esta?
12. ¿Crees que una solución así mejoraría la seguridad y control en tu trabajo?
    
**Preguntas complementarias**

13. ¿Cuál es tu cargo dentro de la empresa?
14. ¿En qué tipo de empresa trabajas?
15. ¿Cuántos almacenes o sedes manejan?
16. ¿En qué zonas operan?
17. ¿Qué sistemas o herramientas usan actualmente?
18. ¿Qué tan seguido usas computadora o celular en tu trabajo?
19. ¿Trabajas más en oficina o en campo?
20. ¿Qué tan familiarizado estás con sistemas tecnológicos?

### 2.2.1. Registro de entrevistas
**Primer segmento: Dueños y Administradores de PYMES**

<div align="center">

## Segmento 2: Dueños y Administradores de PYMES

<div align="center">

| Nº Entrevista | Datos del entrevistado | Resumen de la entrevista | Evidencia de entrevista |
|--------------|------------------------|--------------------------|--------------------------|
| 1 | **Nombre:** Carlos Marcelo Mansilla Rivero <br> **Edad:** 23 <br> **Distrito:** Surquillo <br> **Ocupación:** Dueño/Administrador de distribuidora mayorista <br> **Link:** colocar link | El entrevistado administra una distribuidora mayorista y utiliza herramientas digitales para su gestión diaria; su principal problema es la merma y el “robo hormiga”, lo que afecta la rentabilidad del negocio; considera que el control actual es insuficiente, por lo que valora el monitoreo en tiempo real y alertas ante eventos críticos; busca una solución intuitiva, confiable y accesible desde el celular que le brinde mayor control y tranquilidad. | <p align="center"><img src="./assets/screenshot-interview-marcelo-mansilla.png" width="300"></p> |
| 2 | **Nombre:** — <br> **Edad:** — <br> **Distrito:** — <br> **Ocupación:** — <br> **Link:** — | Pendiente de entrevista | — |
| 3 | **Nombre:** — <br> **Edad:** — <br> **Distrito:** — <br> **Ocupación:** — <br> **Link:** — | Pendiente de entrevista | — |
| 4 | **Nombre:** — <br> **Edad:** — <br> **Distrito:** — <br> **Ocupación:** — <br> **Link:** — | Pendiente de entrevista | — |

</div>

</div>


**Segundo segmento: Jefes de Seguridad y Operaciones**

<div align="center">

| Nº Entrevista | Datos del entrevistado | Resumen de la entrevista | Evidencia de entrevista |
|--------------|------------------------|--------------------------|--------------------------|
| 1 | **Nombre:** Joao Jiménez <br> **Edad:** 26 <br> **Distrito:** San Juan de Lurigancho <br> **Ocupación:** Encargado de seguridad y planificación <br> **Link:** colocar link | El entrevistado trabaja en seguridad supervisando almacenes y utilizando métodos tradicionales como guardias, registros manuales y cámaras; enfrenta problemas como accesos fuera de horario y pérdidas difíciles de rastrear, además de la ineficiencia al revisar grabaciones; por ello, valora el monitoreo en tiempo real, alertas precisas y un historial de accesos, buscando una solución confiable que optimice el control y mejore la toma de decisiones. | <p align="center"><img src="./assets/screenshot-interview-joao-jimenez.png" width="300"></p> |
| 2 | **Nombre:** — <br> **Edad:** — <br> **Distrito:** — <br> **Ocupación:** — <br> **Link:** — | Pendiente de entrevista | — |
| 3 | **Nombre:** — <br> **Edad:** — <br> **Distrito:** — <br> **Ocupación:** — <br> **Link:** — | Pendiente de entrevista | — |
| 4 | **Nombre:** — <br> **Edad:** — <br> **Distrito:** — <br> **Ocupación:** — <br> **Link:** — | Pendiente de entrevista | — |

</div>
## 1.2. Solution Profile

## 1.2.1. Antecdentes y problematica
Antecedentes
En los últimos años, el sector logístico y de almacenamiento ha experimentado un crecimiento acelerado, impulsado en gran medida por el auge del comercio electrónico y la necesidad de optimizar las cadenas de suministro. Sin embargo, a pesar de la modernización en la gestión de inventarios, los sistemas de seguridad física en los almacenes han avanzado a un ritmo mucho menor.

En el contexto local y nacional, particularmente en las zonas industriales de Lima y provincias, la seguridad de los almacenes sigue dependiendo en gran medida de métodos tradicionales y reactivos. Las empresas suelen apoyarse en el uso de candados físicos, registros manuales de entrada y salida en cuadernos de control, y sistemas de videovigilancia (CCTV) cerrados. Estos métodos presentan una limitación crítica: son sistemas aislados que requieren supervisión humana constante y, por lo general, solo sirven para revisar incidentes una vez que ya han ocurrido, sin ofrecer capacidad de prevención o alerta temprana.

Si bien existen soluciones corporativas de control de acceso electrónico, estas suelen ser infraestructuras monolíticas, costosas y difíciles de implementar para pequeñas y medianas empresas. Además, carecen de la flexibilidad necesaria para integrarse en un modelo de monitoreo centralizado en la nube que permita gestionar múltiples sedes desde una única plataforma.

Problemática
El problema central que aborda watchgate con su producto locksight es la alta vulnerabilidad de los almacenes ante accesos no autorizados, robos internos y la falta de visibilidad en tiempo real sobre los eventos de seguridad físicos, lo cual genera pérdidas económicas significativas y deficiencias operativas.

Esta problemática principal se desglosa en los siguientes puntos críticos que afectan tanto a pequeños negocios como a grandes corporaciones:
Ausencia de alertas en tiempo real: Los sistemas actuales no notifican a los administradores cuando ocurre un evento inusual (por ejemplo, la apertura de una puerta fuera del horario laboral o movimiento en zonas restringidas). Esto retrasa el tiempo de respuesta ante intrusiones o actividades sospechosas.

Gestión deficiente y descentralizada de accesos: Las empresas con múltiples zonas de almacenamiento o diferentes sedes enfrentan dificultades para controlar quién tiene acceso a qué áreas. La falta de un registro digital automatizado impide tener una trazabilidad exacta (cuándo, dónde y por cuánto tiempo se accedió a un espacio).

Altos costos de implementación tecnológica: Las soluciones de seguridad perimetral e interna tradicionales requieren instalaciones complejas y servidores locales. Esto crea una barrera de entrada para empresas emergentes que necesitan seguridad de alto nivel pero no pueden asumir el costo de arquitecturas de red cerradas.

Toma de decisiones basada en intuición en lugar de datos: Al no contar con un dashboard que centralice e interprete el flujo de actividad física del almacén, los gerentes de operaciones no pueden identificar patrones de riesgo, auditar incidentes de manera eficiente, ni optimizar los protocolos de seguridad.

Frente a esta situación, existe una brecha tecnológica evidente: la necesidad de un sistema puente que logre comunicar el entorno físico (mediante sensores IoT y microcontroladores) con el entorno digital (aplicación web), emitiendo información procesable y escalable mediante un modelo de suscripción (SaaS).
