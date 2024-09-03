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

Aquí presentamos las User Stories que capturan las necesidades de los usuarios finales. Estas historias ayudan a definir y priorizar las funcionalidades clave para asegurar que la aplicación cumpla con las expectativas del usuario.

## 3.3. Impact mapping

En esta sección, se evidencia cómo el sistema se alinea perfectamente con los objetivos estratégicos del proyecto. Asimismo, se muestra cómo cada función del sistema contribuirá a lograr los resultados esperados.

**Segmento 1: Medianos agricultores**

![Impact Mapping: Medianos Agricultores](assets/Impact_Mapping/segment1.png)

**Segmento 2: Centros de Investigación Agrícola**

![Impact Mapping: Centros de Investigación Agrícola](assets/Impact_Mapping/segment2.png)

## 3.4. Product Backlog

En esta sección, listamos y priorizamos todas las tareas y funcionalidades necesarias para el desarrollo de la aplicación. El backlog guiará el desarrollo del proyecto y garantizará que se aborden todas las necesidades del usuario de manera eficiente.

<table>
  <thead>
    <tr>
      <th>Número de Orden</th>
      <th>User Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Story Points</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>HU-12</td>
      <td>Reconocer las ventajas de HidroBots a través del landing page</td>
      <td>Como visitante del landing page quiero conocer las ventajas de la plataforma para saber si se ajusta a lo que necesito.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>2</td>
      <td>HU-13</td>
      <td>Redirección a la aplicación</td>
      <td>Como visitante de la landing page, quiero acceder a la aplicación para comenzar a usarla</td>
      <td>1</td>
    </tr>
    <tr>
      <td>3</td>
      <td>HU-06</td>
      <td>Programación de riego automático</td>
      <td>Como usuario, quiero configurar un sistema de riego automático, para que mis plantas reciban agua sin necesidad de intervención manual.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>4</td>
      <td>HU-07</td>
      <td>Control manual del riego</td>
      <td>Como usuario, quiero activar y desactivar el riego manual desde la aplicación, para tener un control más preciso sobre el riego en situaciones específicas.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>5</td>
      <td>TS-02</td>
      <td>Registrar riegos</td>
      <td>Como desarrollador, quiero contar con un endpoint para registrar los riegos que efectúa el dispositivo</td>
      <td>3</td>
    </tr>
    <tr>
      <td>6</td>
      <td>HU-08</td>
      <td>Registrar evento de riego</td>
      <td>Como usuario, quiero que cada riego sea guardado en el sistema para poder ser accedido en un futuro</td>
      <td>2</td>
    </tr>
    <tr>
      <td>7</td>
      <td>HU-10</td>
      <td>Acceder el registro de riego</td>
      <td>Como usuario, quiero tener un registro de los riegos que se han efectuado, para acceder desde la aplicación.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>8</td>
      <td>HU-05</td>
      <td>Aplicación de fertilizantes</td>
      <td>Como agricultor, quiero que el sistema de fertilización aplique la cantidad adecuada de fertilizantes, para optimizar el uso de insumos.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>9</td>
      <td>HU-04</td>
      <td>Notificaciones de Análisis del suelo</td>
      <td>Como agricultor, quiero recibir notificaciones sobre los resultados del análisis del suelo, para estar al tanto de las condiciones actuales del terreno.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>10</td>
      <td>HU-09</td>
      <td>Notificaciones de riego</td>
      <td>Como usuario, quiero recibir notificaciones cuando mis cultivos hayan sido regados, para tener información a detalle</td>
      <td>5</td>
    </tr>
    <tr>
      <td>11</td>
      <td>HU-18</td>
      <td>Ver Historial Climático</td>
      <td>Como agricultor, quiero ver el historial de las condiciones climáticas para entender mejor cómo afecta a mis cultivos.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>12</td>
      <td>HU-11</td>
      <td>Monitoreo en tiempo real de las plantas</td>
      <td>Como usuario, quiero monitorear en tiempo real diferentes factores externos a mis plantas, para reconocer sus necesidades</td>
      <td>2</td>
    </tr>
    <tr>
      <td>13</td>
      <td>TS-03</td>
      <td>Registrar datos meteorológicos</td>
      <td>Como desarrollador, quiero contar con un endpoint para registrar los datos meteorológicos que registra el dispositivo</td>
      <td>3</td>
    </tr>
    <tr>
      <td>14</td>
      <td>HU-01</td>
      <td>Visualizar nutrientes del suelo</td>
      <td>Como agricultor, quiero obtener información sobre los niveles de nutrientes del suelo para ajustar el uso de fertilizantes.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>15</td>
      <td>HU-03</td>
      <td>Programación de Análisis del suelo</td>
      <td>Como agricultor, quiero programar análisis de suelo mediante la aplicación, para monitorear la salud del terreno.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>16</td>
      <td>TS-01</td>
      <td>Registrar datos sobre los nutrientes del suelo</td>
      <td>Como desarrollador, quiero contar con un endpoint para registrar los datos sobre los nutrientes del suelo</td>
      <td>3</td>
    </tr>
    <tr>
      <td>17</td>
      <td>HU-02</td>
      <td>Historial de nutrientes del suelo</td>
      <td>Como agricultor, quiero obtener el historial de los niveles de nutrientes del suelo para comparar cambios a lo largo del tiempo.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>18</td>
      <td>HU-14</td>
      <td>Registrar cuenta</td>
      <td>Como usuario quiero crear una cuenta para poder acceder a la aplicación.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>19</td>
      <td>HU-15</td>
      <td>Iniciar sesión</td>
      <td>Como usuario quiero ingresar a mi cuenta para utilizar la aplicación</td>
      <td>2</td>
    </tr>
    <tr>
      <td>20</td>
      <td>TS-06</td>
      <td>Sistema de Autenticación y Registro</td>
      <td>Como desarrollador, quiero implementar un sistema de autenticación y registro.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>21</td>
      <td>TS-04</td>
      <td>Diseñar la interfaz de Usuario</td>
      <td>Como desarrollador, quiero diseñar una interfaz de usuario atractiva y fácil de usar para una experiencia agradable.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>22</td>
      <td>HU-16</td>
      <td>Cerrar sesión</td>
      <td>Como usuario quiero cerrar mi sesión para mantener mis datos seguros.</td>
      <td>1</td>
    </tr>
    <tr>
      <td>23</td>
      <td>HU-19</td>
      <td>Compartir Datos con la Cooperativa</td>
      <td>Como agricultor, quiero compartir mis datos de riego y análisis de suelo con mi cooperativa para recibir recomendaciones.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>24</td>
      <td>TS-05</td>
      <td>Optimizar el Rendimiento de la Aplicación</td>
      <td>Como desarrollador, quiero optimizar el rendimiento de la aplicación para una experiencia rápida y fluida.</td>
      <td>8</td>
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
