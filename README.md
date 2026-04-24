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

# Capitulo III: Requirements Specification
## 3.1 User Stories
| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|----------------|--------|-------------|--------------------------|----------------------------|
| US01 | Visualizar almacenes registrados | Como dueño de PYME, quiero visualizar mis almacenes registrados para tener control general de mis operaciones. | Given el usuario tiene almacenes registrados, When accede al sistema, Then el sistema muestra la lista de almacenes asociados.<br>Given no tiene almacenes, When accede, Then el sistema muestra un estado vacío. | EP01 |
| US02 | Ver estado de un almacén | Como dueño de PYME, quiero consultar el estado de un almacén para conocer su situación actual. | Given existe un almacén, When el usuario lo selecciona, Then el sistema muestra su estado actual.<br>Given el almacén tiene eventos recientes, When se consulta, Then se muestran dichos eventos. | EP01 |
| US03 | Monitorear actividad en tiempo real | Como jefe de seguridad, quiero monitorear la actividad en tiempo real para detectar incidentes rápidamente. | Given existen eventos en el almacén, When ocurren, Then el sistema los actualiza en tiempo real.<br>Given múltiples eventos, When se generan, Then se visualizan sin retraso significativo. | EP01 |
| US04 | Registrar un nuevo almacén | Como dueño de PYME, quiero registrar un nuevo almacén para gestionarlo dentro del sistema. | Given el usuario ingresa datos válidos, When registra un almacén, Then el sistema lo guarda correctamente.<br>Given datos incompletos, When intenta registrar, Then el sistema rechaza la operación. | EP02 |
| US05 | Configurar horarios de acceso | Como jefe de seguridad, quiero definir horarios de acceso para controlar entradas y salidas. | Given el usuario define un horario, When lo guarda, Then el sistema lo aplica al almacén.<br>Given un acceso fuera de horario, When ocurre, Then se registra como evento. | EP02 |
| US06 | Recibir alertas de acceso fuera de horario | Como jefe de seguridad, quiero recibir alertas cuando haya accesos fuera de horario para reaccionar rápidamente. | Given ocurre un acceso fuera de horario, When el evento es detectado, Then el sistema genera una alerta.<br>Given una alerta generada, When se envía, Then llega al usuario correctamente. | EP03 |
| US07 | Recibir alertas de movimiento sospechoso | Como dueño de PYME, quiero recibir alertas de movimientos sospechosos para prevenir robos. | Given se detecta un movimiento inusual, When el sistema lo identifica, Then genera una alerta.<br>Given la alerta es válida, When se envía, Then el usuario la recibe. | EP03 |
| US08 | Registrar eventos de seguridad | Como jefe de seguridad, quiero registrar eventos de seguridad para mantener control histórico. | Given ocurre un evento, When es detectado, Then el sistema lo almacena.<br>Given eventos registrados, When se consultan, Then se muestran correctamente. | EP04 |
| TS09 | Registrar evento mediante API | Como developer, quiero registrar eventos de seguridad mediante API para integrarlos al sistema. | Given una solicitud válida, When se envía al endpoint, Then el sistema registra el evento.<br>Given datos inválidos, When se envía la solicitud, Then el sistema retorna error. | EP05 |
| US10 | Visualizar historial de eventos | Como jefe de seguridad, quiero visualizar el historial de eventos para analizar incidentes pasados. | Given existen eventos registrados, When el usuario consulta el historial, Then el sistema muestra la lista completa.<br>Given no existen eventos, When se consulta, Then se muestra un estado vacío. | EP04 |
| US11 | Filtrar eventos por tipo | Como jefe de seguridad, quiero filtrar eventos por tipo para facilitar el análisis. | Given existen múltiples tipos de eventos, When el usuario aplica un filtro, Then el sistema muestra solo los eventos correspondientes.<br>Given un filtro aplicado, When se elimina, Then se muestran todos los eventos. | EP04 |
| US12 | Filtrar eventos por fecha | Como jefe de seguridad, quiero filtrar eventos por fecha para revisar periodos específicos. | Given el usuario selecciona un rango de fechas, When aplica el filtro, Then el sistema muestra eventos dentro del rango.<br>Given fechas inválidas, When se aplican, Then el sistema no procesa la consulta. | EP04 |
| US13 | Gestionar múltiples almacenes | Como jefe de seguridad, quiero gestionar múltiples almacenes para tener control centralizado. | Given el usuario tiene varios almacenes, When accede al sistema, Then puede visualizar y seleccionar cualquiera.<br>Given cambia de almacén, When lo selecciona, Then el sistema actualiza la información mostrada. | EP02 |
| US14 | Recibir alertas de puertas abiertas | Como dueño de PYME, quiero recibir alertas cuando una puerta quede abierta para evitar riesgos. | Given una puerta permanece abierta, When se supera el tiempo permitido, Then el sistema genera una alerta.<br>Given la alerta generada, When se envía, Then el usuario la recibe. | EP03 |
| US15 | Consultar detalle de un evento | Como jefe de seguridad, quiero ver el detalle de un evento para entender lo ocurrido. | Given existe un evento, When el usuario lo selecciona, Then el sistema muestra su información detallada.<br>Given el evento no existe, When se consulta, Then el sistema retorna error. | EP04 |
| US16 | Recibir notificaciones en tiempo real | Como jefe de seguridad, quiero recibir notificaciones en tiempo real para actuar inmediatamente. | Given ocurre un evento crítico, When es detectado, Then el sistema envía una notificación inmediata.<br>Given múltiples eventos, When ocurren, Then se notifican sin retraso significativo. | EP03 |
| US17 | Acceder al sistema desde dispositivo móvil | Como dueño de PYME, quiero acceder al sistema desde mi celular para monitorear mi negocio en cualquier momento. | Given el usuario accede desde un dispositivo móvil, When ingresa al sistema, Then la interfaz se adapta correctamente.<br>Given interacción en móvil, When navega, Then las funcionalidades se mantienen operativas. | EP01 |
| TS18 | Obtener eventos mediante API | Como developer, quiero obtener eventos mediante API para integrarlos en el sistema. | Given una solicitud válida, When se consulta el endpoint, Then el sistema retorna los eventos.<br>Given la solicitud es inválida, When se envía, Then el sistema retorna error. | EP05 |
| US19 | Acceder al sistema | Como dueño de PYME, quiero acceder al sistema para gestionar mis almacenes. | Given el usuario tiene credenciales válidas, When intenta acceder, Then el sistema permite el ingreso.<br>Given credenciales inválidas, When intenta acceder, Then el sistema rechaza el acceso. | EP02 |
| US20 | Cerrar sesión | Como jefe de seguridad, quiero cerrar sesión para proteger el acceso al sistema. | Given el usuario tiene sesión activa, When cierra sesión, Then el sistema finaliza la sesión.<br>Given sesión cerrada, When intenta acceder a recursos, Then el sistema requiere autenticación. | EP02 |
| US21 | Visualizar landing page | Como dueño de PYME (visitante), quiero visualizar la landing page para conocer el producto. | Given el usuario accede al sitio, When carga la página, Then el sistema muestra la información del producto.<br>Given contenido disponible, When se visualiza, Then se presenta correctamente. | EP06 |
| US22 | Visualizar video del producto | Como jefe de seguridad (visitante), quiero ver el video del producto para entender su funcionamiento. | Given el video está disponible, When el usuario lo reproduce, Then el sistema lo muestra correctamente.<br>Given el video no carga, When se intenta reproducir, Then el sistema muestra un error. | EP06 |
| US23 | Visualizar información del equipo | Como dueño de PYME (visitante), quiero ver información del equipo para generar confianza en el producto. | Given existe información del equipo, When el usuario accede a la sección, Then el sistema la muestra.<br>Given no hay contenido, When se accede, Then se muestra estado vacío. | EP06 |
| US24 | Contactar desde la landing page | Como jefe de seguridad (visitante), quiero contactar al equipo para resolver dudas. | Given el usuario completa los datos requeridos, When envía el formulario, Then el sistema registra la solicitud.<br>Given datos inválidos, When intenta enviar, Then el sistema rechaza la solicitud. | EP06 |
| US25 | Registrar usuario | Como dueño de PYME, quiero registrarme en el sistema para usar la plataforma. | Given el usuario ingresa datos válidos, When se registra, Then el sistema crea la cuenta.<br>Given datos inválidos, When intenta registrarse, Then el sistema rechaza el registro. | EP02 |
| US26 | Asociar usuario a almacén | Como jefe de seguridad, quiero asociarme a un almacén para gestionarlo. | Given el usuario tiene permisos, When se asocia a un almacén, Then el sistema registra la relación.<br>Given no tiene permisos, When intenta asociarse, Then el sistema rechaza la acción. | EP02 |
| TS27 | Autenticación de usuario mediante API | Como developer, quiero autenticar usuarios mediante API para controlar el acceso al sistema. | Given credenciales válidas, When se envía la solicitud, Then el sistema retorna autenticación exitosa.<br>Given credenciales inválidas, When se envía, Then el sistema retorna error. | EP05 |
| US28 | Visualizar dashboard consolidado | Como jefe de seguridad, quiero visualizar un dashboard consolidado para tener una visión general de todos los almacenes. | Given existen múltiples almacenes, When el usuario accede al dashboard, Then el sistema muestra información consolidada.<br>Given no hay datos, When accede, Then se muestra estado vacío. | EP01 |
| US29 | Priorizar alertas críticas | Como jefe de seguridad, quiero priorizar alertas críticas para atender primero los incidentes más importantes. | Given existen múltiples alertas, When se generan, Then el sistema identifica las críticas.<br>Given alertas críticas, When se visualizan, Then se muestran con prioridad. | EP03 |
| US30 | Marcar alertas como atendidas | Como jefe de seguridad, quiero marcar alertas como atendidas para llevar control de incidentes gestionados. | Given una alerta existe, When el usuario la marca como atendida, Then el sistema actualiza su estado.<br>Given alerta actualizada, When se consulta, Then refleja el nuevo estado. | EP03 |
| US31 | Generar reportes de seguridad | Como jefe de seguridad, quiero generar reportes para analizar el comportamiento de los almacenes. | Given existen datos registrados, When el usuario genera un reporte, Then el sistema produce el reporte.<br>Given no hay datos, When genera el reporte, Then el sistema indica ausencia de información. | EP04 |
| US32 | Acceder desde diferentes ubicaciones | Como jefe de seguridad, quiero acceder al sistema desde cualquier lugar para mantener el control operativo. | Given el usuario tiene conexión, When accede al sistema, Then puede ingresar desde cualquier ubicación.<br>Given acceso remoto, When navega, Then mantiene funcionalidades completas. | EP01 |
| US33 | Gestionar permisos de acceso | Como dueño de PYME, quiero gestionar permisos de acceso para controlar quién puede ver mis almacenes. | Given el usuario asigna permisos, When guarda los cambios, Then el sistema los aplica.<br>Given permisos insuficientes, When un usuario accede, Then el sistema restringe el acceso. | EP02 |
| US34 | Integrar servicio externo de notificaciones | Como jefe de seguridad, quiero integrar un servicio externo para recibir notificaciones confiables. | Given el servicio externo está disponible, When ocurre un evento, Then el sistema envía la notificación.<br>Given falla del servicio, When se intenta enviar, Then el sistema maneja el error. | EP05 |
| TS35 | Manejo de errores en API | Como developer, quiero manejar errores en la API para asegurar la estabilidad del sistema. | Given ocurre un error, When se procesa la solicitud, Then el sistema retorna un mensaje de error controlado.<br>Given error inesperado, When ocurre, Then el sistema registra el incidente. | EP05 |

## Relación de Epics y User Stories – Locksight

### Epic 01: Monitoreo y visualización de almacenes
| Story ID | Título |
|----------|--------|
| US01 | Visualizar almacenes registrados |
| US02 | Ver estado de un almacén |
| US03 | Monitorear actividad en tiempo real |
| US17 | Acceder al sistema desde dispositivo móvil |
| US28 | Visualizar dashboard consolidado |
| US32 | Acceder desde diferentes ubicaciones |

---

### Epic 02: Gestión de usuarios y almacenes
| Story ID | Título |
|----------|--------|
| US04 | Registrar un nuevo almacén |
| US05 | Configurar horarios de acceso |
| US13 | Gestionar múltiples almacenes |
| US19 | Acceder al sistema |
| US20 | Cerrar sesión |
| US25 | Registrar usuario |
| US26 | Asociar usuario a almacén |
| US33 | Gestionar permisos de acceso |

---

### Epic 03: Alertas y seguridad activa
| Story ID | Título |
|----------|--------|
| US06 | Recibir alertas de acceso fuera de horario |
| US07 | Recibir alertas de movimiento sospechoso |
| US14 | Recibir alertas de puertas abiertas |
| US16 | Recibir notificaciones en tiempo real |
| US29 | Priorizar alertas críticas |
| US30 | Marcar alertas como atendidas |

---

### Epic 04: Historial, auditoría y reportes
| Story ID | Título |
|----------|--------|
| US08 | Registrar eventos de seguridad |
| US10 | Visualizar historial de eventos |
| US11 | Filtrar eventos por tipo |
| US12 | Filtrar eventos por fecha |
| US15 | Consultar detalle de un evento |
| US31 | Generar reportes de seguridad |

---

### Epic 05: Integraciones técnicas y API RESTful
| Story ID | Título |
|----------|--------|
| TS09 | Registrar evento mediante API |
| TS18 | Obtener eventos mediante API |
| TS27 | Autenticación de usuario mediante API |
| US34 | Integrar servicio externo de notificaciones |
| TS35 | Manejo de errores en API |

---

### Epic 06: Landing Page y adquisición de usuarios
| Story ID | Título |
|----------|--------|
| US21 | Visualizar landing page |
| US22 | Visualizar video del producto |
| US23 | Visualizar información del equipo |
| US24 | Contactar desde la landing page |

## 3.3. Impact Mapping
### Segmento 1: Dueños y Administradores de PYMES

<p align="center">
  <img src="https://github.com/user-attachments/assets/873b5135-e602-48f6-9627-f24400a6a3ea" width="800"/>
</p>

<br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/97bcb5c5-7b4b-4e78-a1d0-696b355c0cf9" width="800"/>
</p>

<br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/35b67905-6fc8-46f5-9708-0750bc66b419" width="800"/>
</p>

---

### Segmento 2: Jefes de Seguridad y Operaciones

<p align="center">
  <img src="https://github.com/user-attachments/assets/d659a9d3-48e1-4eff-905c-72c063ddbb75" width="800"/>
</p>

<br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/8b453081-e2e8-446c-8a9e-6b4ec107008f" width="800"/>
</p>

<br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/26ae3501-feee-4c6b-99f5-74040c93faee" width="800"/>
</p>

## 3.4. Product Backlog

| # | User Story ID | Título | Descripción | Story Points |
|---|--------------|--------|-------------|--------------|
| 1 | US21 | Visualizar landing page | Como dueño de PYME (visitante), quiero visualizar la landing page para conocer el producto. | 3 |
| 2 | US22 | Visualizar video del producto | Como jefe de seguridad (visitante), quiero ver el video del producto para entender su funcionamiento. | 2 |
| 3 | US23 | Visualizar información del equipo | Como dueño de PYME (visitante), quiero ver información del equipo para generar confianza. | 2 |
| 4 | US24 | Contactar desde la landing page | Como jefe de seguridad (visitante), quiero contactar al equipo para resolver dudas. | 3 |
| 5 | US25 | Registrar usuario | Como dueño de PYME, quiero registrarme en el sistema para usar la plataforma. | 5 |
| 6 | US19 | Acceder al sistema | Como dueño de PYME, quiero acceder al sistema para gestionar mis almacenes. | 3 |
| 7 | US01 | Visualizar almacenes registrados | Como dueño de PYME, quiero visualizar mis almacenes registrados para tener control general. | 5 |
| 8 | US04 | Registrar un nuevo almacén | Como dueño de PYME, quiero registrar un nuevo almacén para gestionarlo. | 5 |
| 9 | US02 | Ver estado de un almacén | Como dueño de PYME, quiero consultar el estado de un almacén. | 3 |
| 10 | US17 | Acceder desde dispositivo móvil | Como dueño de PYME, quiero acceder desde mi celular para monitorear. | 3 |
| 11 | US03 | Monitorear actividad en tiempo real | Como jefe de seguridad, quiero monitorear actividad en tiempo real. | 8 |
| 12 | US05 | Configurar horarios de acceso | Como jefe de seguridad, quiero definir horarios de acceso para controlar entradas y salidas. | 5 |
| 13 | US16 | Recibir notificaciones en tiempo real | Como jefe de seguridad, quiero recibir notificaciones inmediatas. | 5 |
| 14 | US06 | Alertas de acceso fuera de horario | Como jefe de seguridad, quiero recibir alertas de accesos indebidos. | 5 |
| 15 | US07 | Alertas de movimiento sospechoso | Como dueño de PYME, quiero recibir alertas para prevenir robos. | 5 |
| 16 | US14 | Alertas de puertas abiertas | Como dueño de PYME, quiero recibir alertas de puertas abiertas. | 3 |
| 17 | US29 | Priorizar alertas críticas | Como jefe de seguridad, quiero priorizar alertas importantes. | 5 |
| 18 | US30 | Marcar alertas como atendidas | Como jefe de seguridad, quiero gestionar alertas atendidas. | 3 |
| 19 | US08 | Registrar eventos de seguridad | Como jefe de seguridad, quiero registrar eventos. | 5 |
| 20 | US10 | Visualizar historial de eventos | Como jefe de seguridad, quiero revisar historial. | 5 |
| 21 | US11 | Filtrar eventos por tipo | Como jefe de seguridad, quiero filtrar eventos. | 3 |
| 22 | US12 | Filtrar eventos por fecha | Como jefe de seguridad, quiero filtrar por fechas. | 3 |
| 23 | US15 | Consultar detalle de evento | Como jefe de seguridad, quiero ver detalles. | 3 |
| 24 | US31 | Generar reportes de seguridad | Como jefe de seguridad, quiero generar reportes. | 8 |
| 25 | US13 | Gestionar múltiples almacenes | Como jefe de seguridad, quiero gestionar múltiples almacenes. | 8 |
| 26 | US28 | Visualizar dashboard consolidado | Como jefe de seguridad, quiero ver un dashboard general. | 8 |
| 27 | US33 | Gestionar permisos de acceso | Como dueño de PYME, quiero gestionar permisos. | 5 |
| 28 | US26 | Asociar usuario a almacén | Como jefe de seguridad, quiero asociarme a un almacén. | 3 |
| 29 | US20 | Cerrar sesión | Como jefe de seguridad, quiero cerrar sesión. | 2 |
| 30 | US32 | Acceder desde cualquier ubicación | Como jefe de seguridad, quiero acceso remoto. | 3 |
| 31 | US34 | Integrar servicio de notificaciones | Como jefe de seguridad, quiero integrar notificaciones externas. | 8 |
| 32 | TS09 | Registrar evento mediante API | Como developer, quiero registrar eventos vía API. | 5 |
| 33 | TS18 | Obtener eventos mediante API | Como developer, quiero obtener eventos vía API. | 5 |
| 34 | TS27 | Autenticación mediante API | Como developer, quiero autenticar usuarios vía API. | 5 |
| 35 | TS35 | Manejo de errores en API | Como developer, quiero manejar errores. | 5 |



