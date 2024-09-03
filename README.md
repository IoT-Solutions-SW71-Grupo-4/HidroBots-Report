<h3 align="center"> Universidad Peruana de Ciencias Aplicadas </h3>

<h3 align="center"> Ingeniería de Software </h3>
<h3 align="center"> Ciclo 2024 - 2 </h3>

<br>

<div align="center">
  <img width=140 src="https://seeklogo.com/images/U/universidad-peruana-de-ciencias-aplicadas-upc-logo-B98C3A365C-seeklogo.com.png"/>
</div>

<br>

<h1 align="center"> TB1 Report </h1>

<h3 align="center"> Desarrollo de Soluciones IoT - SW53 </h3>

<h3 align="center"> Docente:  </h3>

<h3> Startup: HidroBots </h3>

<h3> Product: </h3>

<h3> Team Members: </h3>

<div align="center">

| Member                              |    Code    |
| :---------------------------------- | :--------: |
| Ampudia Flores, José Carlos Isaac   | u202112936 |
| Defilippi Santillán, Diego          | U202120448 |
| Horna Silva, Fabio Ernesto          | u202020229 |
| Lopez Huarcaya, Leonardo Paul       | u202124304 |
| Paucar De La Cruz, Tatiana Medalith | u20211f955 |

</div>

<h3 align="center">Septiembre, 2024</h3>

<br><br>

# Registro de Versiones del Informe

<br><br>

# Project Report Collaboration Insights

<br><br>

# Contenido

## Tabla de Contenidos

### [Registro de versiones del informe](#registro-de-versiones-del-informe)

### [Project Report Collaboration Insights](#project-report-collaboration-insights)

### [Contenido](#contenido)

### [Student Outcome](#student-outcome-1)

### [Capítulo I: Introducción](#capítulo-i-introducción-1)

- [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
  - [1.2.2 Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hyphotesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

### [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis-1)

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
  - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [2.4. Ubiquitous Language](#24-ubiquitous-language)

### [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification-1)

- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

### [Capítulo IV: Solutions Software Design](#capítulo-iv-solution-software-design)

- [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
  - [4.1.1. EventStorming](#411-eventstorming)
    - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
    - [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
    - [4.1.1.3. Bounded COntext Canvases](#4113-bounded-context-canvases)
  - [4.1.2. Context Mapping](#412-context-mapping)
  - [4.1.3. Software Architecture](#413-software-architecture)
    - [4.1.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
    - [4.1.3.2. Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
    - [4.1.3.3. Software Architecture Container Level Diagrams](#4133-software-architecture-container-level-diagrams)
    - [4.1.3.4. Software Architecture Deployment Diagrams](#4134-software-architecture-deployment-diagrams)
- [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
  - [4.2.X. Bounded Context: <Bounded Context name>](#42x-bounded-context)
    - [4.2.X.1. Domain Layer](#42x1-domain-layer)
    - [4.2.X.2. Interface Layer](#42x2-interface-context)
    - [4.2.X.3. Application Layer](#42x3-application-context)
    - [4.2.X.4. Infrastructure Layer](#42x4-infrastructure-context)
    - [4.2.X.5. Bounded Context Software Architecture Component Level Diagrams](#42x5-bounded-context-software-architecture-component-level-diagrams)
    - [4.2.X.6. Bounded Context Software Architecture Code Level Diagrams](#42x6-bounded-context-software-architecture-code-level-diagrams)
      - [4.2.X.6.1. Bounded Context Domain Layer Class Diagrams](#42x61-bounded-context-domain-layer-class-diagrams)
      - [4.2.X.6.2. Bounded Context Database Design Diagram](#42x62-bounded-context-database-design-diagram)

### [Capítulo V: Solution UI/UX Design](#capítulo-v-solutions-uiux-design)

- [5.1. Style Guidelines](#51-style-guidelines)
  - [5.1.1. General Style Guidelines](#511-general-style-guidelines)
  - [5.1.2. Web Style Guidelines](#512-web-style-guidelines)
- [5.2. Information Architecture](#52-information-architecture)
  - [5.2.1. Organization Systems](#521-organization-systems)
  - [5.2.2. Labeling Systems](#522-labeling-systems)
  - [5.2.3. SEO Tags and Meta Tags](#523-seo-tags-and-meta-tags)
  - [5.2.4. Searching Systems](#524-searching-systems)
  - [5.2.5. Navigation Systems](#525-navigation-systems)
- [5.3. Landing Page UI Design](#53-landing-page-ui-design)
  - [5.3.1. Landing Page Wireframe](#531-landing-page-wireframe)
  - [5.3.2. Landing Page Mock-up](#532-landing-page-mock-up)
- [5.4. Applications UX/UI Design](#54-web-applications-uxui-design)
  - [5.4.1. Applications Wireframes](#541-web-applications-wireframes)
  - [5.4.2. Applications Wireflow Diagrams](#542-web-applications-wireflow-diagrams)
  - [5.4.3. Applications Mock-ups](#543-web-applications-mock-ups)
  - [5.4.4. Applications User Flow Diagrams](#544-web-applications-user-flow-diagrams)
- [5.5. Aplications Prototyping](#55-applications-prototyping)

### [Capítulo VI: Product Implementation, Validation \& Deployment](#capítulo-vi-product-implementation-validation--deployment)

- [6.1. Software Configuration Management](#61-software-configuration-management)
  - [6.1.1. Software Development Environment Configuration](#611-software-development-environment-configuration)
  - [6.1.2. Source Code Management](#612-source-code-management)
  - [6.1.3. Source Code Style Guide \& Conventions](#613-source-code-style-guide--conventions)
  - [6.1.4. Software Deployment Configuration](#614-software-deployment-configuration)
- [6.2. Landing Page, Services \& Applications Implementation](#62-landing-page-services--applications-implementation)
  - [6.2.X. Sprint X](#62x-sprint-n)
    - [6.2.X.1. Sprint Planning 1](#62x1-sprint-planning-n)
    - [6.2.X.2. Sprint Backlog 1](#62x2-sprint-backlog-n)
    - [6.2.X.3. Development Evidence for Sprint Review](#62x3-development-evidence-for-sprint-review)
    - [6.2.X.4. Testing Suite Evidence for Sprint Review](#62x4-testing-suite-evidence-for-sprint-review)
    - [6.2.X.5. Execution Evidence for Sprint Review](#62x5-execution-evidence-for-sprint-review)
    - [6.2.X.6. Services Documentation Evidence for Sprint Review](#62x6-services-documentation-evidence-for-sprint-review)
    - [6.2.X.7. Software Deployment Evidence for Sprint Review](#62x7-software-deployment-evidence-for-sprint-review)
    - [6.2.X.8. Team Collaboration Insights during Sprint](#62x8-team-collaboration-insights-during-sprint)
- [6.3. Validation Interviews](#63-validation-interviews)
  - [6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)
  - [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
  - [6.3.3. Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)
- [6.4. Video About-the-Product](#64-video-about-the-product)

### [Conclusiones](#conclusiones-1)

- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)

### [Bibliografía](#bibliografía-1)

### [Anexos](#anexos-1)

<br><br>

# Student Outcome

<b>ABET – EAC - Student Outcome 5:</b> La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.

<br><br>

# Capítulo I: Introducción

## 1.1. StartUp Profile

### 1.1.1. Descripción de la StartUp

### 1.1.2. Perfiles de integrantes del equipo

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

#### 1.2.2.2. Lean UX Assumptions

#### 1.2.2.3. Lean UX Hyphotesis Statements

#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

### 2.2.2. Registro de entrevistas

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

### 2.3.5. As-Is Scenario Mapping

## 2.4. Ubiquitous Language

<div align="justify">

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

En esta sección, se visualiza el rendimiento esperado del sistema propuesto después de su implementación. Se describirán los flujos de trabajo, las interacciones y las mejoras respecto al estado actual, destacando cómo la solución propuesta resolverá problemas y optimizará los procesos existentes.

**Segmento 1: Medianos agricultores**

![Empathy Mapping: Medianos Agricultores](assets/To-Be_Mapping/segment1.jpg)

**Segmento 2: Centros de Investigación Agrícola**

![Empathy Mapping: Centros de Investigación Agrícola](assets/To-Be_Mapping/segment2.jpg)

## 3.2. User Stories

En esta sección, se presenta las User Stories que capturan las necesidades de los usuarios finales, tanto medianos agricultores como centros de investigación agrícola. Estas historias ayudan a definir y priorizar las funcionalidades clave para asegurar que la aplicación cumpla con las expectativas del usuario.

<table align="center">
  <thead align="center">
    <tr>
      <th>Epic/User Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de Aceptación</th>
      <th>Relación (EPIC ID)</th>
    </tr>
  </thead>
  <tbody  align="center">
   <tr>
      <td>EP-01</td>
      <td>Análisis del Suelo</td>
      <td  align="justify">Como agricultor, quiero visualizar, analizar y programar el análisis del suelo para optimizar el uso de fertilizantes.</td>
      <td  align="justify">
        <strong>Escenario 1: Visualización de nutrientes</strong><br>
        Dado que el agricultor desea analizar el suelo, cuando acceda a la sección de análisis, entonces podrá ver los niveles de nutrientes y realizar recomendaciones de fertilización.<br>
        <strong>Escenario 2: Programación de análisis</strong><br>
        Dado que el agricultor quiere programar análisis, cuando configure un nuevo análisis, entonces el sistema debe permitir seleccionar la fecha y frecuencia del análisis.
      </td>
      <td>
         -
      </td>
    </tr>
    <tr>
      <td>EP-02</td>
      <td>Gestión Integral del Riego</td>
      <td  align="justify">Como agricultor, quiero configurar y controlar el riego automático y manual, así como aplicar fertilizantes y registrar eventos de riego, para mantener mis cultivos bien hidratados y nutridos.</td>
      <td  align="justify">
        <strong>Escenario 1: Configuración de riego automático</strong><br>
        Dado que el agricultor desea configurar riego, cuando acceda a la configuración de riego, entonces podrá establecer horarios y frecuencia de riego automático.<br>
        <strong>Escenario 2: Control manual del riego</strong><br>
        Dado que el agricultor quiere un control preciso, cuando acceda al control manual, entonces podrá activar y desactivar el riego según sea necesario.
      </td>
      <td>
        -
      </td>
    </tr>
    <tr>
      <td>EP-03</td>
      <td>Monitoreo Climático y del Terreno</td>
      <td  align="justify">Como agricultor, quiero monitorear en tiempo real las condiciones climáticas y del terreno para tomar decisiones informadas sobre el cuidado de mis cultivos.</td>
      <td  align="justify">
        <strong>Escenario 1: Monitoreo en tiempo real</strong><br>
        Dado que el agricultor necesita información en tiempo real, cuando acceda a la sección de monitoreo, entonces podrá ver datos actualizados sobre clima y condiciones del terreno.<br>
        <strong>Escenario 2: Alertas y recomendaciones</strong><br>
        Dado que el agricultor requiere alertas, cuando los datos muestren condiciones críticas, entonces recibirá notificaciones para tomar medidas correctivas.
      </td>
      <td>
         -
      </td>
    </tr>
    <tr>
      <td>EP-05</td>
      <td>Gestión de cuenta</td>
      <td  align="justify">Como usuario, quiero gestionar mi cuenta, incluyendo la creación de perfil y configuración de preferencias, para personalizar mi experiencia con la aplicación.</td>
      <td  align="justify">
        <strong>Escenario 1: Registro y configuración</strong><br>
        Dado que el usuario quiere gestionar su cuenta, cuando complete el registro y configure preferencias, entonces el perfil deberá actualizarse y personalizarse.<br>
        <strong>Escenario 2: Acceso y seguridad</strong><br>
        Dado que el usuario desea proteger su cuenta, cuando inicie sesión, entonces el sistema debe validar sus credenciales y permitir acceso seguro.
      </td>
      <td>
         -
      </td>
    </tr>
    <tr>
      <td>EP-06</td>
      <td>Desarrollo de la Landing Page</td>
      <td  align="justify">Como visitante, quiero acceder a una landing page que presente las características de la aplicación, un formulario de contacto y facilite la descarga de la aplicación, para obtener más información y acceder al servicio.</td>
      <td  align="justify">
        <strong>Escenario 1: Información y diseño</strong><br>
        Dado que el visitante quiere información, cuando acceda a la landing page, entonces debe visualizar claramente las características de la aplicación y un formulario de contacto.<br>
        <strong>Escenario 2: Acceso a la aplicación</strong><br>
        Dado que el visitante desea descargar la aplicación, cuando seleccione la opción de descarga, entonces el enlace debe redirigir correctamente a la tienda de aplicaciones.
      </td>
      <td>
         -
      </td>
    </tr>
    <tr>
      <td>EP-07</td>
      <td>Desarrollo de la API</td>
      <td  align="justify">Como desarrollador, quiero contar con una API robusta y ágil para integrar y comunicar la aplicación con los sistemas de backend, asegurando una sincronización eficiente de los datos.</td>
      <td  align="justify">
        <strong>Escenario 1: Funcionalidad y rendimiento</strong><br>
        Dado que se necesita una API, cuando se realicen solicitudes, entonces la API debe responder eficientemente y manejar grandes volúmenes de datos.<br>
        <strong>Escenario 2: Seguridad y errores</strong><br>
        Dado que la API debe ser segura, cuando se detecten errores o intentos de acceso no autorizado, entonces la API debe manejar los errores adecuadamente y proteger los datos.
      </td>
      <td>
         -
      </td>
    </tr>
    <tr>
  <td>EP-08</td>
  <td>Desarrollo de la Aplicación Web y Móvil</td>
  <td align="justify">Como desarrollador, quiero construir una aplicación web y móvil intuitiva y funcional que permita a los usuarios gestionar sus cultivos, configurar riegos y monitorear condiciones en tiempo real desde cualquier dispositivo.</td>
  <td align="justify">
    <strong>Escenario 1: Interfaz de Usuario y Experiencia de Usuario</strong><br>
    Dado que se necesita una aplicación atractiva, cuando los usuarios interactúan con la aplicación web o móvil, entonces deben encontrar una interfaz intuitiva y una experiencia de usuario fluida que facilite la navegación y la gestión de cultivos.<br>
    <strong>Escenario 2: Sincronización de Datos entre Aplicación Web y Móvil</strong><br>
    Dado que los datos deben estar sincronizados, cuando los usuarios realicen cambios en la aplicación web o móvil, entonces estos cambios deben reflejarse en ambas plataformas en tiempo real, asegurando que la información esté actualizada y consistente.<br>
    <strong>Escenario 3: Funcionalidades Específicas por Plataforma</strong><br>
    Dado que cada plataforma tiene sus propias características, cuando los usuarios utilicen la aplicación móvil o web, entonces la aplicación debe ofrecer funcionalidades específicas optimizadas para la plataforma utilizada, como notificaciones push en la app móvil y vistas detalladas en la aplicación web.
  </td>
  <td>-</td>
</tr>
    <tr>
      <td>HU-01</td>
      <td>Visualizar nutrientes del suelo</td>
      <td align="justify">Como agricultor, quiero obtener información sobre los niveles de nutrientes del suelo para ajustar el uso de fertilizantes.</td>
      <td  align="justify">
        <strong>Escenario 1: Consultar niveles actuales</strong><br>
        Dado que el agricultor desea obtener información sobre los nutrientes del suelo, cuando acceda a la sección de nutrientes en la aplicación, entonces visualizará los niveles actuales de nutrientes.<br>
        <strong>Escenario 2: Comparar con niveles ideales</strong><br>
        Dado que el agricultor quiere comparar los nutrientes actuales con los ideales, cuando vea la información, entonces deberá comparar los niveles actuales con los niveles ideales recomendados.
      </td>
      <td>EP-01</td>
    </tr>
    <tr>
      <td>HU-02</td>
      <td>Historial de nutrientes del suelo</td>
      <td align="justify">Como agricultor, quiero obtener el historial de los niveles de nutrientes del suelo para comparar cambios a lo largo del tiempo.</td>
      <td  align="justify">
        <strong>Escenario 1: Ver historial completo</strong><br>
        Dado que el agricultor desea revisar el historial de nutrientes, cuando acceda a la sección de historial, entonces podrá ver un gráfico con los niveles de nutrientes a lo largo del tiempo.<br>
        <strong>Escenario 2: Filtrar por fechas</strong><br>
        Dado que el agricultor necesita comparar niveles en un rango específico, cuando seleccione un rango de fechas, entonces el gráfico debe actualizarse para mostrar los datos del rango seleccionado.
      </td>
      <td>EP-01</td>
    </tr>
    <tr>
      <td>HU-03</td>
      <td>Programación de Análisis del suelo</td>
      <td align="justify">Como agricultor, quiero programar análisis de suelo mediante la aplicación, para monitorear la salud del terreno.</td>
      <td  align="justify">
        <strong>Escenario 1: Programar análisis</strong><br>
        Dado que el agricultor desea programar un análisis de suelo, cuando acceda a la opción de programación en la aplicación, entonces podrá seleccionar la frecuencia y fecha para los análisis.<br>
        <strong>Escenario 2: Confirmación de programación</strong><br>
        Dado que el agricultor ha programado un análisis, cuando confirme la programación, entonces recibirá una notificación de confirmación y recordatorios antes de cada análisis.
      </td>
      <td>EP-01</td>
    </tr>
    <tr>
      <td>HU-04</td>
      <td>Notificaciones de Análisis del suelo</td>
      <td align="justify">Como agricultor, quiero recibir notificaciones sobre los resultados del análisis del suelo, para estar al tanto de las condiciones actuales del terreno.</td>
      <td  align="justify">
        <strong>Escenario 1: Recibir notificación de resultados</strong><br>
        Dado que el agricultor espera los resultados de un análisis, cuando los resultados estén disponibles, entonces recibirá una notificación con un resumen de los resultados.<br>
        <strong>Escenario 2: Ver detalles de los resultados</strong><br>
        Dado que el agricultor ha recibido una notificación, cuando acceda a los detalles de los resultados, entonces podrá visualizar un informe completo con recomendaciones para ajustar el uso de fertilizantes.
      </td>
      <td>EP-01</td>
    </tr>
    <tr>
      <td>HU-05</td>
      <td>Aplicación de fertilizantes</td>
      <td align="justify">Como agricultor, quiero que el sistema de fertilización aplique la cantidad adecuada de fertilizantes, para optimizar el uso de insumos.</td>
      <td  align="justify">
        <strong>Escenario 1: Configurar cantidad de fertilizantes</strong><br>
        Dado que el agricultor desea aplicar fertilizantes, cuando configure la cantidad en la aplicación, entonces el sistema deberá calcular la dosis adecuada basada en las necesidades del suelo.<br>
        <strong>Escenario 2: Aplicación efectiva</strong><br>
        Dado que el agricultor ha configurado la aplicación de fertilizantes, cuando el sistema ejecute la aplicación, entonces debe hacerlo de manera precisa y documentar la cantidad aplicada.
      </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>HU-06</td>
      <td>Programación de riego automático</td>
      <td align="justify">Como usuario, quiero configurar un sistema de riego automático, para que mis plantas reciban agua sin necesidad de intervención manual.</td>
      <td  align="justify">
        <strong>Escenario 1: Configurar horarios de riego</strong><br>
        Dado que el usuario desea configurar el riego automático, cuando acceda a la opción de configuración en la aplicación, entonces podrá seleccionar horarios y frecuencias para el riego.<br>
        <strong>Escenario 2: Confirmación y ajuste</strong><br>
        Dado que el usuario ha configurado el riego automático, cuando la configuración se guarde, entonces recibirá una confirmación y podrá ajustar la configuración según sea necesario.
      </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>HU-07</td>
      <td>Control manual del riego</td>
      <td align="justify">Como usuario, quiero activar y desactivar el riego manual desde la aplicación, para tener un control más preciso sobre el riego en situaciones específicas.</td>
      <td  align="justify">
        <strong>Escenario 1: Activar/desactivar riego</strong><br>
        Dado que el usuario desea controlar el riego manualmente, cuando acceda a la opción de riego manual en la aplicación, entonces podrá activar o desactivar el riego en cualquier momento.<br>
        <strong>Escenario 2: Confirmar acción</strong><br>
        Dado que el usuario ha cambiado el estado del riego, cuando la acción se confirme, entonces el sistema debe reflejar el cambio inmediatamente y proporcionar una notificación de la acción realizada.
      </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>HU-08</td>
      <td>Registrar evento de riego</td>
      <td align="justify">Como usuario, quiero que cada riego sea guardado en el sistema para poder ser accedido en un futuro.</td>
      <td  align="justify">
        <strong>Escenario 1: Registro automático</strong><br>
        Dado que el usuario desea registrar los eventos de riego, cuando el sistema ejecute un riego, entonces el evento debe ser registrado automáticamente en el sistema.<br>
        <strong>Escenario 2: Acceso al registro</strong><br>
        Dado que el usuario quiere revisar el historial de riegos, cuando acceda a la sección de registros en la aplicación, entonces podrá ver todos los eventos de riego registrados.
      </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>HU-09</td>
      <td>Notificaciones de riego</td>
      <td align="justify">Como usuario, quiero recibir notificaciones cuando mis cultivos hayan sido regados, para tener información a detalle.</td>
      <td  align="justify">
        <strong>Escenario 1: Notificación de riego</strong><br>
        Dado que el usuario desea recibir notificaciones de riego, cuando el sistema complete un riego, entonces enviará una notificación con detalles sobre el riego realizado.<br>
        <strong>Escenario 2: Configuración de notificaciones</strong><br>
        Dado que el usuario quiere personalizar las notificaciones, cuando configure sus preferencias en la aplicación, entonces recibirá notificaciones basadas en sus configuraciones.
      </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>HU-10</td>
      <td>Acceder al registro de riego</td>
      <td align="justify">Como usuario, quiero tener un registro de los riegos que se han efectuado, para acceder desde la aplicación.</td>
      <td  align="justify">
        <strong>Escenario 1: Ver historial de riegos</strong><br>
        Dado que el usuario desea revisar el historial de riegos, cuando acceda a la sección de registros en la aplicación, entonces podrá ver una lista completa de todos los riegos realizados.<br>
        <strong>Escenario 2: Filtrar registros</strong><br>
        Dado que el usuario quiere buscar riegos específicos, cuando aplique filtros como fechas o tipos de riego, entonces los registros deben actualizarse para mostrar solo los datos que cumplen con los filtros aplicados.
      </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>HU-11</td>
      <td>Monitoreo en tiempo real de las plantas</td>
      <td align="justify">Como usuario, quiero monitorear en tiempo real diferentes factores externos a mis plantas, para reconocer sus necesidades.</td>
      <td  align="justify">
        <strong>Escenario 1: Monitoreo de factores externos</strong><br>
        Dado que el usuario desea monitorear las plantas, cuando acceda a la sección de monitoreo en la aplicación, entonces podrá ver datos en tiempo real sobre factores como temperatura y humedad.<br>
        <strong>Escenario 2: Alertas de condiciones</strong><br>
        Dado que el usuario quiere estar informado sobre condiciones críticas, cuando los datos en tiempo real indiquen valores fuera de rango, entonces recibirá alertas para tomar medidas correctivas.
      </td>
      <td>EP-04</td>
    </tr>
     <tr>
      <td>HU-12</td>
      <td>Reconocer las ventajas de HidroBots a través del landing page</td>
      <td align="justify">Como visitante del landing page quiero conocer las ventajas de la plataforma para saber si se ajusta a lo que necesito.</td>
      <td align="justify">
        <strong>Scenario 1: Visualizar ventajas para los medianos agricultores</strong><br>
        Dado que: El usuario se encuentra en la landing page de HidroBots.<br>
        Cuando: Presiona sobre "servicios para agricultores" (o "services for farmers").<br>
        Entonces: Se envía al usuario a la sección "Agricultores" donde se muestran las ventajas para este segmento.<br><br>
        <strong>Scenario 2: Visualizar ventajas para los Centros de Investigación Agrícola</strong><br>
        Dado que: El usuario se encuentra en la landing page de HidroBots.<br>
        Cuando: Presiona sobre "Services for research centers" (o "Servicios para centros de investigación").<br>
        Entonces: Se envía al usuario a la sección "Centros de Investigación" donde se muestran las ventajas para los investigadores.
      </td>
      <td>EP-06</td>
    </tr>
    <tr>
      <td>HU-13</td>
      <td>Redirección a la aplicación</td>
      <td align="justify">Como visitante de la landing page, quiero acceder a la aplicación para comenzar a usarla.</td>
      <td align="justify">
        <strong>Scenario 1: Acceso a la app web</strong><br>
        Dado que el visitante se encuentra en la landing page<br>
        Y quieren acceder a la aplicación desde la web<br>
        Cuando seleccione el botón “Acceder”<br>
        Entonces será redirigido a la aplicación web<br><br>
        <strong>Scenario 2: Acceso a la app desde móvil</strong><br>
        Dado que el visitante se encuentra en la landing page desde su móvil<br>
        Y quiere acceder a la aplicación móvil<br>
        Cuando seleccione el botón “Acceder”<br>
        Entonces será redirigido a la aplicación móvil
      </td>
      <td>EP-06</td>
    </tr>
    <tr>
      <td>HU-14</td>
      <td>Registrar cuenta</td>
      <td align="justify">Como usuario, quiero crear una cuenta para poder acceder a la aplicación.</td>
      <td  align="justify">
        <strong>Escenario 1: Proceso de registro</strong><br>
        Dado que el usuario desea crear una cuenta, cuando complete el formulario de registro en la aplicación, entonces la cuenta deberá ser creada y el usuario recibirá una confirmación.<br>
        <strong>Escenario 2: Verificación de cuenta</strong><br>
        Dado que el usuario ha registrado una cuenta, cuando la cuenta se cree, entonces el usuario deberá verificar su correo electrónico para activar la cuenta y acceder a la aplicación.
      </td>
      <td>EP-05</td>
    </tr>
    <tr>
      <td>HU-15</td>
      <td>Iniciar sesión</td>
      <td align="justify">Como usuario, quiero ingresar a mi cuenta para utilizar la aplicación.</td>
      <td  align="justify">
        <strong>Escenario 1: Acceso a la cuenta</strong><br>
        Dado que el usuario desea ingresar a la aplicación, cuando ingrese sus credenciales correctas, entonces deberá tener acceso a su cuenta y a todas las funcionalidades.<br>
        <strong>Escenario 2: Mensaje de error</strong><br>
        Dado que el usuario ha ingresado credenciales incorrectas, cuando intente iniciar sesión, entonces deberá recibir un mensaje de error y la opción de intentar nuevamente.
      </td>
      <td>EP-05</td>
    </tr>
    <tr>
      <td>HU-16</td>
      <td>Cerrar sesión</td>
      <td align="justify">Como usuario quiero cerrar mi sesión para mantener mis datos seguros.</td>
      <td  align="justify">
        <strong>Escenario 1: Cierre de sesión</strong><br>
        Dado que el usuario desea cerrar su sesión, cuando seleccione la opción de cerrar sesión en la aplicación, entonces su sesión deberá finalizar y será redirigido a la pantalla de inicio.<br>
        <strong>Escenario 2: Confirmación de cierre</strong><br>
        Dado que el usuario ha cerrado su sesión, cuando el proceso se complete, entonces deberá recibir una confirmación de que ha cerrado sesión exitosamente.
      </td>
      <td>EP-05</td>
    </tr>
    <tr>
  <td>HU-17</td>
  <td>Recuperar contraseña</td>
  <td align="justify">Como usuario, quiero recuperar mi contraseña en caso de olvidarla para poder acceder a mi cuenta.</td>
  <td align="justify">
    <strong>Escenario 1: Solicitar recuperación</strong><br>
    Dado que el usuario ha olvidado su contraseña, cuando seleccione la opción de recuperación de contraseña y proporcione su dirección de correo electrónico, entonces recibirá un enlace para restablecer la contraseña.<br>
    <strong>Escenario 2: Restablecer contraseña</strong><br>
    Dado que el usuario ha recibido el enlace de recuperación, cuando siga el enlace y complete el formulario de restablecimiento de contraseña, entonces la contraseña deberá actualizarse y el usuario recibirá una confirmación de que la contraseña ha sido cambiada exitosamente.
  </td>
  <td>EP-05</td>
</tr>
<tr>
      <td>HU-18</td>
      <td>Ver Historial Climático</td>
      <td align="justify">Como agricultor, quiero ver el historial de las condiciones climáticas para entender mejor cómo afecta a mis cultivos.</td>
      <td  align="justify">
        <strong>Escenario 1: Consultar historial</strong><br>
        Dado que el agricultor desea revisar el historial climático, cuando acceda a la sección de historial en la aplicación, entonces visualizará un gráfico con las condiciones climáticas pasadas.<br>
        <strong>Escenario 2: Filtrar datos climáticos</strong><br>
        Dado que el agricultor quiere analizar datos en un rango específico, cuando seleccione un rango de fechas, entonces el gráfico debe actualizarse para mostrar solo los datos del rango seleccionado.
      </td>
      <td>EP-03</td>
    </tr>
    <tr>
      <td>HU-19</td>
      <td>Compartir Datos con la Cooperativa</td>
      <td align="justify">Como agricultor, quiero compartir mis datos de riego y análisis de suelo con mi cooperativa para recibir recomendaciones.</td>
      <td  align="justify">
        <strong>Escenario 1: Enviar datos</strong><br>
        Dado que el agricultor desea compartir datos, cuando seleccione la opción de compartir en la aplicación, entonces los datos de riego y análisis de suelo serán enviados a la cooperativa.<br>
        <strong>Escenario 2: Confirmación de envío</strong><br>
        Dado que el agricultor ha enviado los datos, cuando el proceso se complete, entonces recibirá una confirmación de que los datos han sido compartidos exitosamente.
      </td>
      <td>EP-04</td>
    </tr>
    <tr>
      <td>TS-01</td>
      <td>Registrar datos sobre los nutrientes del suelo</td>
      <td align="justify">Como desarrollador, quiero contar con un endpoint para registrar los datos sobre los nutrientes del suelo.</td>
      <td  align="justify">
        <strong>Escenario 1: Endpoint funcional</strong><br>
        Dado que se necesita registrar datos sobre nutrientes, cuando se llame al endpoint, entonces los datos deben ser registrados correctamente en la base de datos.<br>
        <strong>Escenario 2: Manejo de errores</strong><br>
        Dado que pueden ocurrir errores en la solicitud, cuando se detecte un error en el registro de datos, entonces el sistema debe manejar el error y devolver un mensaje adecuado.
      </td>
      <td>EP-07</td>
    </tr>
    <tr>
      <td>TS-02</td>
      <td>Registrar riegos</td>
      <td align="justify">Como desarrollador, quiero contar con un endpoint para registrar los riegos que efectúa el dispositivo.</td>
      <td  align="justify">
        <strong>Escenario 1: Endpoint funcional</strong><br>
        Dado que se necesita registrar los riegos, cuando se llame al endpoint, entonces los datos del riego deben ser registrados en el sistema.<br>
        <strong>Escenario 2: Validación de datos</strong><br>
        Dado que el endpoint debe manejar datos variados, cuando los datos sean enviados, entonces el sistema debe validar la integridad y formato de los datos antes de registrarlos.
      </td>
      <td>EP-07</td>
    </tr>
    <tr>
      <td>TS-03</td>
      <td>Registrar datos meteorológicos</td>
      <td align="justify">Como desarrollador, quiero contar con un endpoint para registrar los datos meteorológicos que registra el dispositivo.</td>
      <td  align="justify">
        <strong>Escenario 1: Endpoint funcional</strong><br>
        Dado que se necesita registrar datos meteorológicos, cuando se llame al endpoint, entonces los datos deben ser registrados adecuadamente en la base de datos.<br>
        <strong>Escenario 2: Respuesta del sistema</strong><br>
        Dado que el endpoint debe responder a solicitudes, cuando se registren los datos, entonces el sistema debe devolver una respuesta de éxito o un mensaje de error adecuado si algo sale mal.
      </td>
      <td>EP-07</td>
    </tr>
    <tr>
      <td>TS-04</td>
      <td>Diseñar la interfaz de Usuario</td>
      <td align="justify">Como desarrollador, quiero diseñar una interfaz de usuario atractiva y fácil de usar para una experiencia agradable.</td>
      <td  align="justify">
        <strong>Escenario 1: Diseño atractivo</strong><br>
        Dado que se necesita una interfaz atractiva, cuando se implemente el diseño, entonces los elementos visuales deberán ser coherentes con el estilo y agradable para el usuario.<br>
        <strong>Escenario 2: Pruebas de usabilidad</strong><br>
        Dado que la interfaz debe ser fácil de usar, cuando se realicen pruebas con usuarios, entonces el diseño deberá ajustarse según los comentarios recibidos para mejorar la usabilidad.
      </td>
      <td>EP-08</td>
    </tr>
    <tr>
      <td>TS-05</td>
      <td>Optimizar el Rendimiento de la Aplicación</td>
      <td align="justify">Como desarrollador, quiero optimizar el rendimiento de la aplicación para una experiencia rápida y fluida.</td>
      <td  align="justify">
        <strong>Escenario 1: Mejora en tiempos de respuesta</strong><br>
        Dado que se busca mejorar el rendimiento, cuando se optimicen los componentes de la aplicación, entonces los tiempos de respuesta deberán ser reducidos y más eficientes.<br>
        <strong>Escenario 2: Reducción de carga</strong><br>
        Dado que la aplicación debe ser fluida, cuando se realicen optimizaciones, entonces la carga en el servidor y la aplicación debe disminuir, mejorando la experiencia general.
      </td>
      <td>EP-08</td>
    </tr>
    <tr>
      <td>TS-06</td>
      <td>Sistema de Autenticación y Registro</td>
      <td align="justify">Como desarrollador, quiero implementar un sistema de autenticación y registro.</td>
      <td  align="justify">
        <strong>Escenario 1: Proceso de autenticación</strong><br>
        Dado que se necesita un sistema de autenticación, cuando el usuario intente iniciar sesión, entonces el sistema deberá validar las credenciales y permitir el acceso a la cuenta.<br>
        <strong>Escenario 2: Gestión de registros</strong><br>
        Dado que el sistema debe gestionar registros, cuando un nuevo usuario se registre, entonces el sistema deberá almacenar sus datos de manera segura y permitir la verificación de la cuenta.
      </td>
      <td>EP-08</td>
    </tr>
  </tbody>
</table>


## 3.3. Impact mapping

En esta sección, se evidencia cómo el sistema se alinea perfectamente con los objetivos estratégicos del proyecto. Asimismo, se muestra cómo cada función del sistema contribuirá a lograr los resultados esperados.

**Segmento 1: Medianos agricultores**

![Impact Mapping: Medianos Agricultores](assets/Impact_Mapping/segment1.png)

**Segmento 2: Centros de Investigación Agrícola**

![Impact Mapping: Centros de Investigación Agrícola](assets/Impact_Mapping/segment2.png)

## 3.4. Product Backlog

En esta sección, listamos y priorizamos todas las tareas y funcionalidades necesarias para el desarrollo de la aplicación. El backlog guiará el desarrollo del proyecto y garantizará que se aborden todas las necesidades del usuario de manera eficiente.

<table>
  <thead align="center">
    <tr>
      <th>Número de Orden</th>
      <th>User Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Story Points</th>
    </tr>
  </thead>
  <tbody align="center">
    <tr>
      <td>1</td>
      <td>HU-01</td>
      <td>Visualizar nutrientes del suelo</td>
      <td align="justify">Como agricultor, quiero obtener información sobre los niveles de nutrientes del suelo para ajustar el uso de fertilizantes.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>2</td>
      <td>HU-02</td>
      <td>Historial de nutrientes del suelo</td>
      <td align="justify">Como agricultor, quiero obtener el historial de los niveles de nutrientes del suelo para comparar cambios a lo largo del tiempo.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>3</td>
      <td>HU-03</td>
      <td>Programación de Análisis del suelo</td>
      <td align="justify">Como agricultor, quiero programar análisis de suelo mediante la aplicación, para monitorear la salud del terreno.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>4</td>
      <td>HU-04</td>
      <td>Notificaciones de Análisis del suelo</td>
      <td align="justify">Como agricultor, quiero recibir notificaciones sobre los resultados del análisis del suelo, para estar al tanto de las condiciones actuales del terreno.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>5</td>
      <td>HU-05</td>
      <td>Aplicación de fertilizantes</td>
      <td align="justify">Como agricultor, quiero que el sistema de fertilización aplique la cantidad adecuada de fertilizantes, para optimizar el uso de insumos.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>6</td>
      <td>HU-06</td>
      <td>Programación de riego automático</td>
      <td align="justify">Como usuario, quiero configurar un sistema de riego automático, para que mis plantas reciban agua sin necesidad de intervención manual.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>7</td>
      <td>HU-07</td>
      <td>Control manual del riego</td>
      <td align="justify">Como usuario, quiero activar y desactivar el riego manual desde la aplicación, para tener un control más preciso sobre el riego en situaciones específicas.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>8</td>
      <td>HU-08</td>
      <td>Registrar evento de riego</td>
      <td align="justify">Como usuario, quiero que cada riego sea guardado en el sistema para poder ser accedido en un futuro</td>
      <td>2</td>
    </tr>
    <tr>
      <td>9</td>
      <td>HU-09</td>
      <td>Notificaciones de riego</td>
      <td align="justify">Como usuario, quiero recibir notificaciones cuando mis cultivos hayan sido regados, para tener información a detalle</td>
      <td>5</td>
    </tr>
    <tr>
      <td>10</td>
      <td>HU-10</td>
      <td>Acceder el registro de riego</td>
      <td align="justify">Como usuario, quiero tener un registro de los riegos que se han efectuado, para acceder desde la aplicación.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>11</td>
      <td>HU-11</td>
      <td>Monitoreo en tiempo real de las plantas</td>
      <td align="justify">Como usuario, quiero monitorear en tiempo real diferentes factores externos a mis plantas, para reconocer sus necesidades</td>
      <td>2</td>
    </tr>
    <tr>
      <td>12</td>
      <td>HU-12</td>
      <td>Reconocer las ventajas de HidroBots a través del landing page</td>
      <td align="justify">Como visitante del landing page quiero conocer las ventajas de la plataforma para saber si se ajusta a lo que necesito.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>13</td>
      <td>HU-13</td>
      <td>Redirección a la aplicación</td>
      <td align="justify">Como visitante de la landing page, quiero acceder a la aplicación para comenzar a usarla</td>
      <td>1</td>
    </tr>
    <tr>
      <td>14</td>
      <td>HU-14</td>
      <td>Registrar cuenta</td>
      <td align="justify">Como usuario quiero crear una cuenta para poder acceder a la aplicación.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>15</td>
      <td>HU-15</td>
      <td>Iniciar sesión</td>
      <td align="justify">Como usuario quiero ingresar a mi cuenta para utilizar la aplicación</td>
      <td>2</td>
    </tr>
    <tr>
      <td>16</td>
      <td>HU-16</td>
      <td>Cerrar sesión</td>
      <td align="justify">Como usuario quiero cerrar mi sesión para mantener mis datos seguros.</td>
      <td>1</td>
    </tr>
    <tr>
      <td>17</td>
      <td>HU-17</td>
      <td>Recuperar contraseña</td>
      <td align="justify">Como usuario, quiero recuperar mi contraseña en caso de olvidarla para poder acceder a mi cuenta.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>18</td>
      <td>HU-18</td>
      <td>Ver Historial Climático</td>
      <td align="justify">Como agricultor, quiero ver el historial de las condiciones climáticas para entender mejor cómo afecta a mis cultivos.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>19</td>
      <td>HU-19</td>
      <td>Compartir Datos con la Cooperativa</td>
      <td align="justify">Como agricultor, quiero compartir mis datos de riego y análisis de suelo con mi cooperativa para recibir recomendaciones.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>20</td>
      <td>TS-01</td>
      <td>Registrar datos sobre los nutrientes del suelo</td>
      <td align="justify">Como desarrollador, quiero contar con un endpoint para registrar los datos sobre los nutrientes del suelo</td>
      <td>3</td>
    </tr>
    <tr>
      <td>21</td>
      <td>TS-02</td>
      <td>Registrar riegos</td>
      <td align="justify">Como desarrollador, quiero contar con un endpoint para registrar los riegos que efectúa el dispositivo</td>
      <td>3</td>
    </tr>
    <tr>
      <td>22</td>
      <td>TS-03</td>
      <td>Registrar datos meteorológicos</td>
      <td align="justify">Como desarrollador, quiero contar con un endpoint para registrar los datos meteorológicos que registra el dispositivo</td>
      <td>3</td>
    </tr>
    <tr>
      <td>23</td>
      <td>TS-04</td>
      <td>Diseñar la interfaz de Usuario</td>
      <td align="justify">Como desarrollador, quiero diseñar una interfaz de usuario atractiva y fácil de usar para una experiencia agradable.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>24</td>
      <td>TS-05</td>
      <td>Optimizar el Rendimiento de la Aplicación</td>
      <td align="justify">Como desarrollador, quiero optimizar el rendimiento de la aplicación para una experiencia rápida y fluida.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>25</td>
      <td>TS-06</td>
      <td>Sistema de Autenticación y Registro</td>
      <td align="justify">Como desarrollador, quiero implementar un sistema de autenticación y registro.</td>
      <td>3</td>
    </tr>
  </tbody>
</table>

</div>

# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. EventStorming

#### 4.1.1.1. Candidate Context Discovery

#### 4.1.1.2. Domain Message Flows Modeling

#### 4.1.1.3. Bounded Context Canvases

### 4.1.2 Context mapping

### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture System Landscape Diagram

#### 4.1.3.2. Software Architecture Context Level Diagrams

#### 4.1.3.3. Software Architecture Container Level Diagrams

#### 4.1.3.4. Software Architecture Deployment Diagrams

## 4.2. Tactical-Level Domain-Driven Design

### 4.2.X. Bounded Context:

#### 4.2.X.1. Domain Layer

#### 4.2.X.2. Interface Context

#### 4.2.X.3. Application Context

#### 4.2.X.4. Infrastructure Context

#### 4.2.X.5. Bounded Context Software Architecture Component Level Diagrams

#### 4.2.X.6. Bounded Context Software Architecture Code Level Diagrams

#### 4.2.X.6.1. Bounded Context Domain Layer Class Diagrams

#### 4.2.X.6.2. Bounded Context Database Design Diagram

# Capítulo V: Solutions UI/UX Design

## 5.1. Style Guidelines

### 5.1.1. General Style Guidelines

### 5.1.2. Web, Mobile and IoT Style Guidelines

## 5.2. Information Architecture

### 5.2.1. Organization Systems

### 5.2.2. Labeling Systems

### 5.2.3. SEO Tags and Meta Tags

### 5.2.4. Searching Systems

### 5.2.5. Navigation Systems

## 5.3. Landing Page UI Design

### 5.3.1. Landing Page Wireframe

### 5.3.2. Landing Page Mock-up

## 5.4. Application UX/UI Design

### 5.4.1. Applications Wireframes

### 5.4.2. Applications Wireflow Diagrams

### 5.4.3. Applications Mock-ups

### 5.4.4. Applications User Flow Diagrams

## 5.5. Applications Prototyping

# Capítulo VI: Product Implementation, Validation & Deployment

## 6.1. Software Configuration Management

### 6.1.1. Software Development Environment Configuration

### 6.1.2. Source Code Management

### 6.1.3. Source Code Style Guide & Conventions

### 6.1.4. Software Deployment Configuration

## 6.2. Landing Page, Services & Applications Implementation

### 6.2.X. Sprint n

#### 6.2.X.1. Sprint Planning n.

#### 6.2.X.2. Sprint Backlog n.

#### 6.2.X.3. Development Evidence for Sprint Review

#### 6.2.X.4. Testing Suite Evidence for Sprint Review.

#### 6.2.X.5. Execution Evidence for Sprint Review.

#### 6.2.X.6. Services Documentation Evidence for Sprint Review.

#### 6.2.X.7. Software Deployment Evidence for Sprint Review.

#### 6.2.X.8. Team Collaboration Insights during Sprint.

## 6.3. Validation Interviews.

### 6.3.1. Diseño de Entrevistas.

### 6.3.2. Registro de Entrevistas.

### 6.3.3. Evaluaciones según heurísticas.

## 6.4. Video About-the-Product.

# Conclusiones

## Conclusiones y recomendaciones

## Video About-the-Team

# Bibliografía

# Anexos
