<div align="center">
    <img src="./assets/logo-upc(1).png">
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

| Nº Entrevista | Datos del entrevistado | Resumen de la entrevista | Evidencia de entrevista |
|--------------|------------------------|--------------------------|--------------------------|
| 1 | **Nombre:** Carlos Marcelo Mansilla Rivero <br> **Edad:** 23 <br> **Distrito:** Surquillo <br> **Ocupación:** Dueño/Administrador de distribuidora mayorista <br> **Link:** colocar link | El entrevistado administra una distribuidora mayorista y utiliza herramientas digitales para su gestión diaria; su principal problema es la merma y el “robo hormiga”, lo que afecta la rentabilidad del negocio; considera que el control actual es insuficiente, por lo que valora el monitoreo en tiempo real y alertas ante eventos críticos; busca una solución intuitiva, confiable y accesible desde el celular que le brinde mayor control y tranquilidad. | <p align="center"><img src="./assets/screenshot-interview-marcelo-mansilla.png" width="300"></p> |
| 2 | **Nombre:** Valeria Alejandra Flores Paz <br> **Edad:** 28 <br> **Distrito:** San Borja <br> **Ocupación:** Administradora de tienda de ropa <br> **Link:** colocar link | La entrevistada administra una tienda de ropa y utiliza exclusivamente su celular para la gestión diaria; su principal problema es el "robo hormiga", lo que le genera preocupación al no tener registro de accesos; considera fundamental recibir alertas en tiempo real en su celular ante aperturas fuera de horario; por ello, busca una aplicación sumamente intuitiva, de rápida instalación y costo accesible que le brinde tranquilidad. | <p align="center"><img src="./assets/screenshot-interview-valeria-flores.png" width="300"></p> |
| 3 | **Nombre:** Song Ju Loo <br> **Edad:** 22 <br> **Distrito:** El Agustino <br> **Ocupación:** Dueño de tienda mayorista <br> **Link:** — | El entrevistado, dueño de una tienda mayorista, presenta preocupación por pérdidas de mercadería sin poder identificar su origen; actualmente usa cámaras y confianza en el personal, pero considera el sistema limitado; valora monitoreo en tiempo real, alertas inmediatas y registros históricos; busca una solución simple, accesible desde el celular y que le permita mayor control sin estar presente. | <p align="center"><img src="./assets/screenshot-interview-song-ju-loo.png" width="300"></p> |
| 4 | **Nombre:** Gloria Celis <br> **Edad:** 59 <br> **Distrito:** Villa el Salvador <br> **Ocupación:** Dueña de almacén <br> **Link:** — | La entrevistada, dueña de un almacén con un equipo de aprox 5 personas, enfrenta pérdidas constantes y falta de control de accesos; depende de métodos manuales y cámaras básicas, por lo que valora monitoreo en tiempo real y alertas inmediatas; busca una solución confiable, simple y accesible desde el celular que le brinde mayor control y tranquilidad. | <p align="center"><img src="https://github.com/user-attachments/assets/ce3907dd-d339-4066-9c1a-6d28a808a78a" width="300"></p> |

**Resumen de entrevistas segmento #1**
En general, todas las entrevistas muestran algo bien claro: quienes manejan estos negocios viven con la preocupación constante de pérdidas de mercadería, sobre todo por el “robo hormiga”, y sienten que el control que tienen hoy no es suficiente. Usan cámaras o registros manuales, pero igual les cuesta saber exactamente qué pasa y cuándo ocurre. Por eso, todos coinciden en que necesitan ver lo que sucede en tiempo real y recibir alertas inmediatas para poder reaccionar rápido. También valoran mucho tener un historial que les permita revisar lo ocurrido cuando hay dudas. Al final, lo que buscan es una solución sencilla de usar, que funcione desde el celular y que no sea complicada de implementar, porque más que nada quieren tener mayor control sobre su negocio y sentirse tranquilos incluso cuando no están presentes.


**Segundo segmento: Jefes de Seguridad y Operaciones**

<div align="center">

| Nº Entrevista | Datos del entrevistado | Resumen de la entrevista | Evidencia de entrevista |
|--------------|------------------------|--------------------------|--------------------------|
| 1 | **Nombre:** Joao Jiménez <br> **Edad:** 26 <br> **Distrito:** San Juan de Lurigancho <br> **Ocupación:** Encargado de seguridad y planificación <br> **Link:** colocar link | El entrevistado trabaja en seguridad supervisando almacenes y utilizando métodos tradicionales como guardias, registros manuales y cámaras; enfrenta problemas como accesos fuera de horario y pérdidas difíciles de rastrear, además de la ineficiencia al revisar grabaciones; por ello, valora el monitoreo en tiempo real, alertas precisas y un historial de accesos, buscando una solución confiable que optimice el control y mejore la toma de decisiones. | <p align="center"><img src="./assets/screenshot-interview-joao-jimenez.png" width="300"></p> |
| 2 | **Nombre:** Carlos Rodrigo Chavez Quispe <br> **Edad:** 36 <br> **Distrito:** La Molina <br> **Ocupación:** Supervisor Logístico <br> **Link:** colocar link | El entrevistado supervisa tres almacenes utilizando sistemas tradicionales desconectados entre sí; su principal problema es rastrear las mermas debido a la naturaleza reactiva de las cámaras actuales; valora críticamente la información en tiempo real para reaccionar ante aperturas no autorizadas o fallas de sensores; por ello, requiere una plataforma centralizada que ofrezca trazabilidad absoluta y reportes consolidados, buscando una solución estable que optimice sus auditorías. | <p align="center"><img src="./assets/screenshot-interview-carlos-chavez.png" width="300"></p> |
| 3 | **Nombre:** Diego Castillo <br> **Edad:** 24 <br> **Distrito:** San Juan de Lurigancho <br> **Ocupación:** Jefe de seguridad y supervisor de almacenes <br> **Link:** — | El entrevistado, jefe de seguridad en una empresa de logística y distribución, es responsable de supervisar múltiples almacenes, lo que implica un alto nivel de control y toma de decisiones sobre la seguridad operativa. Señala que la seguridad es crítica, ya que cualquier falla impacta directamente en la empresa, y ha enfrentado problemas como accesos no autorizados y pérdidas difíciles de justificar.<br>Actualmente utiliza cámaras, controles de acceso y registros manuales, pero identifica como principal limitación la falta de centralización de la información, lo que genera ineficiencia y pérdida de tiempo en el monitoreo y análisis.<br>Valora especialmente la posibilidad de contar con información en tiempo real, alertas automáticas ante eventos sospechosos (como accesos fuera de horario o movimientos en zonas restringidas) y un historial completo de accesos para auditorías y toma de decisiones.<br>Busca un sistema confiable, claro y centralizado, que le permita supervisar múltiples almacenes desde cualquier lugar, mejorar la trazabilidad y optimizar la gestión de la seguridad, facilitando una respuesta más rápida y efectiva ante incidentes. | <p align="center"><img src="./assets/screenshot-interview-diego-castillo.png" width="300"></p> |
| 4 | **Nombre:** Cristina Celis <br> **Edad:** 61 <br> **Distrito:** Ate <br> **Ocupación:** Jefa de almacen— <br> **Link:** — | La entrevistada, jefa de Seguridad/Operaciones en una empresa mediana/grande de logística o retail que gestiona entre 2 y 10 almacenes en Lima y alrededores, enfrenta problemas de accesos fuera de horario, pérdidas difíciles de rastrear y falta de integración entre sistemas (CCTV, controles básicos y registros manuales), lo que limita la visibilidad y retrasa la detección de incidentes; valora altamente el monitoreo en tiempo real, las alertas automáticas (accesos no autorizados, actividad inusual, puertas abiertas) y un historial detallado para auditorías, además de poder acceder a la información desde cualquier lugar, por lo que considera clave una solución unificada, precisa e integrada que mejore la eficiencia, reduzca riesgos y simplifique la gestión operativa.| <img width="1350" height="739" alt="image" src="https://github.com/user-attachments/assets/a0a296eb-be77-467c-a995-15f26c506b01" />

</div>

**Resumen de entrevistas segmento #2**
En estas entrevistas se repite una idea bastante clara: quienes trabajan en seguridad y supervisión de almacenes lidian todos los días con sistemas poco integrados que les hacen perder tiempo y les quitan visibilidad. Aunque usan cámaras, controles de acceso y registros manuales, igual les cuesta detectar a tiempo accesos fuera de horario o pérdidas, y muchas veces terminan reaccionando tarde porque todo es más reactivo que preventivo. Por eso, valoran mucho poder tener información en tiempo real, recibir alertas precisas apenas ocurre algo sospechoso y contar con un historial claro que les facilite auditorías y decisiones. Al final, lo que buscan es una plataforma centralizada, confiable y fácil de manejar que les permita controlar varios almacenes desde cualquier lugar, reducir riesgos y responder más rápido sin complicarse con sistemas dispersos.

### 2.2.3. Análisis de entrevistas.
## Análisis de entrevistas – Segmento 1: Dueños y Administradores de PYMES

A partir de las 4 entrevistas realizadas a dueños y administradores de PYMES en distintos rubros (distribución, retail y almacenes), se identificaron patrones consistentes en sus características objetivas y subjetivas, evidenciando necesidades claras relacionadas con el control y la seguridad de sus negocios.

### Características objetivas

- El **100% de los entrevistados administra directamente su negocio** (dueños o responsables de operación).
- El **100% utiliza herramientas digitales básicas** (principalmente celular, apps como WhatsApp o sistemas simples de control).
- El **75% depende de métodos tradicionales de seguridad**, como cámaras y registros manuales.
- El **100% ha experimentado pérdidas de mercadería** o situaciones donde no pueden identificar claramente su origen.
- El **100% gestiona equipos de trabajo**, lo que incrementa la necesidad de control de accesos y supervisión.

### Características subjetivas

- El **100% manifiesta preocupación constante por pérdidas de mercadería**, especialmente asociadas al “robo hormiga”.

- El **100% considera que sus sistemas actuales son insuficientes**, debido a:
  - Falta de monitoreo en tiempo real  
  - Dependencia de revisión manual (cámaras o registros)  
  - Dificultad para identificar responsables o momentos exactos de incidentes  

- El **100% valora funcionalidades clave como:**
  - Monitoreo en tiempo real  
  - Alertas inmediatas ante accesos o movimientos sospechosos  
  - Historial o registro de eventos para revisión  

- El **100% busca una solución que sea:**
  - Fácil de usar  
  - Accesible desde el celular  
  - Rápida de implementar  
  - Intuitiva (sin necesidad de capacitación compleja)  

- El **75% prioriza la confiabilidad del sistema**, mostrando rechazo a soluciones con falsas alarmas o fallos.

- El **100% muestra disposición a adoptar nuevas tecnologías**, siempre que:
  - Sean accesibles en costo  
  - No compliquen su operación diaria  
  - Generen valor directo en reducción de pérdidas  

- El **100% asocia este tipo de soluciones con mayor control y tranquilidad**, destacando que el principal beneficio es poder supervisar su negocio sin estar físicamente presente.

## Análisis de entrevistas – Segmento 2: Jefes de Seguridad y Operaciones

A partir de las 4 entrevistas realizadas a jefes de seguridad y supervisores de operaciones en entornos logísticos, se identificaron patrones claros en sus características objetivas y subjetivas, evidenciando necesidades enfocadas en la centralización, eficiencia y control de la seguridad operativa.

### Características objetivas

- El **100% de los entrevistados trabaja en roles de supervisión o gestión de seguridad**, con responsabilidad directa sobre uno o más almacenes.
- El **75% supervisa múltiples almacenes**, lo que incrementa la complejidad del control y monitoreo.
- El **100% utiliza sistemas tradicionales de seguridad**, como cámaras, controles de acceso y registros manuales.
- El **75% trabaja con sistemas no integrados**, lo que dificulta la gestión unificada de la información.
- El **100% ha enfrentado incidentes como accesos no autorizados o pérdidas difíciles de rastrear**.

### Características subjetivas

- El **100% manifiesta frustración por la falta de integración de los sistemas actuales**, lo que genera pérdida de tiempo y menor visibilidad.

- El **100% considera que el monitoreo actual es reactivo e ineficiente**, debido a:
  - Dependencia de revisión manual de cámaras  
  - Falta de alertas en tiempo real  
  - Dificultad para detectar incidentes de forma oportuna  

- El **100% valora funcionalidades clave como:**
  - Monitoreo en tiempo real  
  - Alertas automáticas y precisas  
  - Historial de accesos y eventos para auditorías  

- El **100% busca una solución que sea:**
  - Centralizada (una sola plataforma)  
  - Confiable y sin errores  
  - Accesible desde cualquier lugar  
  - Clara y fácil de usar  

- El **75% prioriza la trazabilidad y generación de reportes**, como apoyo para auditorías y toma de decisiones.

- El **100% muestra disposición a adoptar nuevas tecnologías**, siempre que:
  - Se integren con sus sistemas actuales  
  - Mejoren la eficiencia operativa  
  - Reduzcan tiempos de supervisión  

- El **100% asocia este tipo de soluciones con mayor control, rapidez de respuesta y reducción de riesgos**, destacando que el valor principal está en pasar de un enfoque reactivo a uno preventivo en la gestión de seguridad.

## 2.3. Needfinding
### 2.3.1. User Personas
> Segmento 1
<img width="1920" height="1080" alt="Black and White Simple User Persona Brainstorm (1)" src="https://github.com/user-attachments/assets/eaa98a45-fc38-4d33-b509-2be98e38e938" />

> Segmento 2
<img width="1920" height="1080" alt="Black and White Simple User Persona Brainstorm (2)" src="https://github.com/user-attachments/assets/7e5f923f-9b0b-4385-a30a-9b2ad64ad57b" />

### 2.3.2 User Task Matrix
### Segmento 1: Dueños y Administradores de PYMES

| Tarea | Frecuencia | Importancia |
|------|------------|-------------|
| Monitorear el estado de su negocio o almacén cuando no está presente | Often | High |
| Detectar pérdidas o faltantes de mercadería | Often | High |
| Identificar posibles robos o “robo hormiga” | Often | High |
| Revisar registros de accesos o actividad del personal | Sometimes | High |
| Recibir alertas ante eventos sospechosos | Occasionally | High |
| Gestionar su negocio desde el celular | Often | High |
| Tomar decisiones rápidas ante incidentes | Sometimes | High |

---

### Segmento 2: Jefes de Seguridad y Operaciones

| Tarea | Frecuencia | Importancia |
|------|------------|-------------|
| Supervisar múltiples almacenes o puntos de control | Often | High |
| Revisar cámaras o registros de seguridad | Often | High |
| Detectar accesos no autorizados o fuera de horario | Often | High |
| Coordinar acciones ante incidentes de seguridad | Sometimes | High |
| Analizar historial de eventos para auditorías | Occasionally | High |
| Gestionar información dispersa de diferentes sistemas | Often | High |
| Responder rápidamente ante alertas de seguridad | Sometimes | High |

### 2.3.3 User Journey Mapping
> Segmento 1
<img width="1053" height="949" alt="Customer Journey by XO Projects (2)" src="https://github.com/user-attachments/assets/20e6d520-f0ca-443d-b73d-550d09ab947c" />


> Segmento 2
<img width="1049" height="952" alt="Customer Journey by XO Projects (4)" src="https://github.com/user-attachments/assets/fd7a9003-c573-41ce-8a39-a776b6b69823" />

### 2.3.4. Empathy Mapping
> Segmento 1
<img width="1024" height="768" alt="Copia de Brainstorming Mapa de Empatia Usuario Simple Blanco Y Negro (2)" src="https://github.com/user-attachments/assets/81968604-632d-42a7-8acc-da0d898de92c" />

> Segmento 2
<img width="1024" height="768" alt="Copia de Brainstorming Mapa de Empatia Usuario Simple Blanco Y Negro (3)" src="https://github.com/user-attachments/assets/39001a97-eb6d-4024-9288-702c280d79e5" />


## 2.4. Big Picture Event Storming

En la sesión de Big Picture Event Storming, el equipo identificó los eventos más relevantes del dominio de seguridad inteligente para almacenes, trazando de forma visual el panorama general de la plataforma LockSight. Se representaron los flujos críticos de monitoreo, control de accesos y gestión de alertas, integrando los sistemas externos que interactúan con la solución e identificando dudas, problemas y oportunidades de mejora. Esta primera exploración permitió al equipo alinear el entendimiento del negocio y establecer las bases para un diseño más detallado en etapas posteriores.

### Big Picture Event Storming – Mapa General

<p align="center"><img src="./assets/big picture event storming.jpg" width="1505" height="664"></p>

### Big Picture Event Storming - Leyenda de Colores

<p align="center"><img src="./assets/big-picture-event-storming.png" width="1505" height="664"></p>

## 2.5. Ubiquitous Language

| Término | Definición |
|--------|-----------|
| Asset (Activo) | Mercadería, inventario o recursos almacenados que son monitoreados y protegidos dentro del sistema. |
| Active Defense Protocol (Protocolo de Defensa Activa) | Conjunto de acciones automáticas (como generación de alertas o bloqueo de accesos) ejecutadas ante una amenaza detectada en el almacén. |
| Interference Detection (Detección de Interferencias) | Identificación de fallas o interrupciones en la comunicación de los dispositivos que afectan el monitoreo del almacén. |
| Live Tracking (Monitoreo en tiempo real) | Visualización continua del estado del almacén y de los eventos que ocurren dentro de la plataforma. |
| Driving Behavior (Comportamiento de actividad) | Análisis del comportamiento dentro del almacén basado en eventos como movimientos, accesos y actividad del personal. |
| Geofence (Geocerca) | Área virtual definida dentro del almacén o zonas específicas que permite detectar accesos o movimientos fuera de los límites establecidos. |
| Health Check (Verificación de Estado) | Confirmación periódica de que los sensores y el sistema se encuentran conectados y operativos. |
| Security Alert (Alerta de Seguridad) | Notificación de alta prioridad ante eventos críticos como accesos no autorizados o actividad sospechosa. |
| Operational Performance (Rendimiento Operativo) | Medición de la eficiencia en la gestión del almacén basada en eventos, tiempos de respuesta y control de accesos. |
