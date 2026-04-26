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



# **Student Outcomes**



# Capítulo I: Introducción

## 1.1. Startup Profile

###  1.1.1. Descripción de la Startup
En un entorno empresarial donde la seguridad de los almacenes y el control de accesos representan un desafío constante, especialmente en ciudades como Lima donde las pérdidas por robos internos, accesos no autorizados y falta de monitoreo en tiempo real impactan directamente en la rentabilidad de las empresas, las soluciones tradicionales ya no son suficientes. Frente a esta problemática surge nuestra startup, una iniciativa impulsada por estudiantes enfocada en transformar la gestión de seguridad mediante el uso de tecnología IoT. Reconocemos que la falta de visibilidad, control y trazabilidad en los almacenes genera vulnerabilidad operativa, por lo que proponemos una solución que conecta sensores físicos con una plataforma web inteligente, permitiendo supervisar en tiempo real lo que ocurre en cada espacio. No nos limitamos a registrar eventos, sino que convertimos cada almacén en un entorno inteligente capaz de detectar anomalías, generar alertas automáticas y proporcionar información clara para la toma de decisiones, brindando así mayor control, seguridad y eficiencia operativa.

**Misión:** Nuestra misión es transformar la seguridad y gestión de accesos en almacenes mediante un sistema inteligente basado en IoT, que permita a las empresas monitorear en tiempo real sus instalaciones, reducir riesgos y tomar decisiones informadas a partir de datos precisos. Buscamos proteger los activos empresariales y optimizar la operación mediante alertas inteligentes, trazabilidad completa y una plataforma accesible que elimine la incertidumbre y fortalezca el control sobre cada evento crítico dentro del almacén.

**Visión:** Nuestra visión es posicionarnos como una plataforma líder en seguridad inteligente para entornos empresariales, elevando el estándar de control y protección en almacenes mediante el uso de IoT y análisis de datos. Aspiramos a que cada instalación conectada opere como un sistema autónomo capaz de anticipar riesgos, detectar comportamientos inusuales y activar mecanismos de alerta en tiempo real, permitiendo a las empresas mantener el control total desde cualquier lugar. Con nuestra solución buscamos construir un ecosistema seguro, eficiente y escalable que no solo reduzca pérdidas, sino que también transforme la manera en que las organizaciones gestionan su seguridad y operación diaria.

## 1.2.2. Lean UX Process

###  1.2.2.1. Lean UX Problem Statements
Nuestro servicio busca resolver la falta de control y visibilidad en la gestión de almacenes empresariales. Es por esto que se propone integrar tecnología IoT como sensores, con una plataforma web que permita monitorear los espacios, controlar accesos y gestionar la información en tiempo real.

En muchos sectores, especialmente en logística e industria, las empresas enfrentan dificultades para proteger sus activos de manera eficiente. Los sistemas tradicionales de seguridad suelen ser reactivos, ya que solo registran lo que ocurrió, pero no ayudan a prevenir incidentes, esto genera problemas como robos internos, accesos no autorizados y falta de control continuo, afectando directamente la rentabilidad de las empresas.

Ante esta situación, surge la necesidad de contar con soluciones que permitan un control más activo y en tiempo real. Sin embargo, muchas empresas no adoptan nuevas tecnologías porque las perciben como costosas, complejas o difíciles de implementar. Es por esto que proponemos una solución que centraliza la gestión de los almacenes en una sola plataforma, permitiendo supervisar accesos, recibir alertas y tomar decisiones con información actualizada. De esta manera, se busca pasar de un enfoque reactivo a uno preventivo, donde los problemas puedan detectarse antes de que ocurran.

Conociendo esto, se generan las siguientes preguntas, ¿Cómo podemos ayudar a las empresas a tener un control más claro y en tiempo real de sus almacenes?,
¿Cómo podemos hacer que el uso de tecnología IoT sea más accesible y fácil de implementar? y ¿Cómo podemos convertir los datos recolectados en información útil para reducir pérdidas?

###  1.2.2.2. Lean UX Assumptions

**Business Outcomes**

* Incrementar la cantidad de empresas que se suscriban a la plataforma Locksight.
* Mejorar la retención de clientes corporativos ofreciendo un servicio estable y confiable.
* Reducir las pérdidas económicas causadas por robos, accesos no autorizados y fallas de control en los almacenes.
* Facilitar el uso de tecnología IoT para que las empresas puedan modernizar su seguridad y pasar de un enfoque reactivo a uno solo preventivo.
* Generar ingresos recurrentes mediante un modelo de suscripción con distintos planes según el tamaño del cliente.

**User Benefits**

* **Dueños de empresas medianas**

  Tener control claro sobre lo que ocurre en sus almacenes sin necesidad de estar físicamente presentes, reduciendo la incertidumbre sobre posibles pérdidas o accesos no autorizados.

* **Jefes de Operaciones / Logística**

  Monitorear en tiempo real la actividad del almacén y reaccionar rápidamente ante cualquier incidente gracias a alertas automáticas y un panel centralizado.

* **Personal de Seguridad**

  Reducir la carga de trabajo manual al contar con un sistema que automatiza la vigilancia y registra los eventos de forma ordenada.

* **Empresas con múltiples almacenes**

  Centralizar la supervisión de todas sus sedes en una sola plataforma, facilitando el control y la toma de decisiones.

**Assumptions**

* Se asume que los clientes necesitan una forma más activa y en tiempo real de monitorear sus almacenes, en lugar de depender de sistemas que solo registran incidentes.
* Se cree que esta necesidad puede resolverse mediante una plataforma que conecte sensores físicos con un dashboard web simple y claro.
* Los clientes iniciales serán dueños de PYMES y responsables de operaciones en empresas más grandes que necesitan mayor control y trazabilidad.
* El principal valor para el cliente será la tranquilidad de saber que sus activos están protegidos y monitoreados constantemente.
* Se espera que valoren beneficios adicionales como el control de horarios del personal y la gestión de varias sedes.
* Los clientes se captarán principalmente mediante contacto directo, redes profesionales y pruebas piloto.
* El modelo de ingresos será por suscripción, según la cantidad de almacenes o sensores utilizados.
* La principal competencia serán los sistemas tradicionales de cámaras y alarmas.
* Uno de los principales riesgos es la dependencia de una conexión a internet estable. Para reducir este riesgo, el sistema podrá almacenar información de forma temporal y sincronizarla cuando se recupere la conexión.
* Se asume que las empresas estarán dispuestas a pagar una suscripción mensual por el servicio. Si no es así, el modelo de negocio podría verse afectado.

**Assumptions Worksheet**

* ¿Quién es el usuario?
  
  Son dueños o administradores de PYMES, así como jefes de operaciones o seguridad en empresas más grandes que necesitan controlar sus almacenes.
* ¿Dónde encaja nuestro producto en su trabajo o vida?
  
  Forma parte de la gestión diaria del almacén. Funciona de manera continua y se consulta desde una computadora o celular en cualquier momento.
* ¿Qué problemas tiene nuestro producto y cómo se puede resolver?
  
  Puede existir cierta dificultad inicial al usar tecnología nueva, por lo que se priorizará una interfaz simple e intuitiva. También pueden presentarse problemas de conexión o energía, que se manejarán guardando información temporalmente hasta recuperar el servicio.
* ¿Cuándo y cómo es usado nuestro producto?
  
  Los sensores funcionan todo el tiempo. La plataforma se usa para revisar el estado del almacén, controlar accesos o responder ante alertas.
* ¿Qué características son importantes?
  
  Que sea confiable, rápido, fácil de usar y que muestre la información de forma clara.
* ¿Cómo debe verse nuestro producto y cómo comportarse?
  
  Debe tener un diseño limpio y profesional, transmitiendo seguridad. Además, debe responder de forma rápida y precisa ante cualquier evento.

###  1.2.2.3. Lean UX Hypothesis Statements

* Creemos que implementar alertas en tiempo real mediante sensores IoT permitirá a los dueños de empresas y jefes de seguridad reaccionar más rápido ante accesos no autorizados. Sabremos que funciona si el tiempo de respuesta se reduce a menos de 1 minuto y los casos de mermas o robos disminuyen durante el primer trimestre.
* Creemos que contar con un dashboard web centralizado e intuitivo permitirá a los administradores gestionar varios almacenes y configurar accesos sin necesidad de conocimientos técnicos. Sabremos que funciona si el 90% de los usuarios puede revisar eventos o configurar permisos en menos de 3 minutos sin ayuda.
* Creemos que incorporar almacenamiento local temporal en los dispositivos mejorará la confiabilidad del sistema, evitando la pérdida de datos ante fallas de conexión. Sabremos que funciona si el 100% de los eventos se sincroniza correctamente después de restablecer el servicio y se mantiene una alta retención de clientes.
* Creemos que ofrecer un modelo de suscripción flexible junto con pruebas piloto facilitará la adopción del sistema. Sabremos que funciona si al menos 5 empresas prueban el sistema en el primer mes y el 60% decide continuar con un plan de pago.

###  1.2.2.4. Lean UX Canvas

![Lean UX Canvas](./assets/img/lean-ux-canvas-locksight.png)

## 1.3. Segmentos objetivos

El modelo de negocio se enmarca en el sector B2B (Business-to-Business), enfocándose en la seguridad de activos críticos y la optimización de la gestión operativa en almacenes. Se han identificado dos segmentos principales que presentan necesidades diferenciadas en cuanto a escalabilidad y profundidad de control:

### Segmento 1: Dueños y Administradores de PYMES (Retail, Tiendas y Pequeños Almacenes)
Este segmento representa a los emprendedores y gerentes de pequeñas y medianas empresas. Son los clientes objetivo para el **Plan Básico**. Por lo general, no cuentan con el presupuesto para mantener un equipo de vigilancia 24/7, pero tienen una necesidad imperiosa de tranquilidad y control sobre su inventario.

**Aspectos demográficos:**
* **Edad:** Entre 25 y 55 años.
* **Ocupación:** Dueños de negocio, gerentes generales o administradores comerciales.
* **Nivel de digitalización:** Usan intensivamente el celular para actividades clave de su negocio (WhatsApp, banca móvil). Buscan *dashboards* simples que no requieran conocimientos técnicos previos.

**Aspectos psicográficos:**
* **Motivaciones:** Obtener tranquilidad mental, mantener el control del negocio a distancia y evitar inversiones costosas o complejas en seguridad tradicional.
* **Intereses:** Soluciones simples, tecnología accesible y herramientas prácticas que faciliten la gestión diaria sin añadir carga operativa.

**Comportamiento y necesidades:**
* Prefieren herramientas intuitivas y valoran la rapidez de configuración.
* Priorizan el uso de la plataforma desde sus dispositivos móviles.
* **Principal dolor:** La merma por robos (internos o externos, como el "robo hormiga").
* Necesitan notificaciones en tiempo real en el celular, especialmente para saber si el local fue abierto fuera del horario establecido.

> **Dato estadistico:** De acuerdo con Gómez et al. (2024), el 73% de las PYMES latinoamericanas carecen de sistemas automatizados de gestión de almacenes, lo cual genera ineficiencias que pueden representar hasta el 25% de sus costos logísticos totales.

---

### Segmento 2: Jefes de Seguridad y Operaciones (Medianas y Grandes Corporaciones)
Este segmento incluye a profesionales que gestionan infraestructuras logísticas complejas para empresas de gran envergadura (fábricas, constructoras, centros de distribución). Son el público objetivo que justificaría la adquisición del **Plan Pro o Empresarial**, ya que su enfoque requiere el cumplimiento de normativas de seguridad industrial.

**Aspectos demográficos:**
* **Edad:** Entre 35 y 60 años.
* **Ocupación:** Jefes de Seguridad Industrial, Supervisores Logísticos, Supply Chain Managers o Jefes de Planta.
* **Nivel de digitalización:** Alto. Acostumbrados a manejar sistemas ERP (SAP, Oracle), generar reportes consolidados y utilizar software de gestión de almacenes (WMS).

**Aspectos psicográficos:**
* **Motivaciones:** Tener control total de las operaciones, reducir las pérdidas a gran escala y optimizar la seguridad en múltiples sedes de forma simultánea.
* **Intereses:** Auditoría constante, trazabilidad de eventos, automatización de procesos y gestión centralizada.

**Comportamiento y necesidades:**
* Buscan soluciones robustas y escalables que puedan crecer con la empresa.
* Prefieren plataformas que ofrezcan facilidades de integración con sus sistemas corporativos existentes.
* **Principal dolor:** La lentitud para auditar incidentes y la falta de control granular.
* Necesitan más que simples alertas: requieren una auditoría completa y trazabilidad detallada de accesos (quién, cuándo y dónde).
* Requieren control de permisos diferenciados por usuario y zona, además de historiales completos para justificar pérdidas y la capacidad de configurar reglas automáticas inteligentes para múltiples almacenes.

> **Dato estadistico:** Simultáneamente, el Internet de las Cosas Industrial (IIoT) permite monitorear condiciones ambientales y ubicación de productos en tiempo real, reduciendo pérdidas por caducidad o daños en un 35% (Ortiz y Paredes-Rodríguez, 2021).
