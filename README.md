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

Se han establecido algunas preguntas dirigidas a nuestro grupo objetivo con el fin de recolectar información cualitativa, como opiniones o descripciones. Esta información será muy útil en la creación de nuestra solución.

<b>Preguntas generales:</b>

- ¿Cuál es su nombre?
- ¿Cuántos años tiene?
- ¿En qué ciudad y distrito reside?
- ¿A qué se dedica actualmente?

<b>Segmento 1: Medianos agricultores</b>

<b>Preguntas sobre su experiencia:</b>

- En términos de cantidad, ¿considera que su producción es al por mayor o al por menor?
- ¿Qué tipo de cultivos normalmente maneja?
- ¿Cómo gestiona normalmente sus cosechas?
- ¿Qué datos considera importantes tener en cuenta para un seguimiento adecuado?
- ¿Cómo realiza generalmente el monitoreo de las condiciones del suelo?
- ¿Cómo realiza el riego de sus cultivos? ¿Utilizas algún sistema automatizado o es manual?

<b>Preguntas sobre los desafíos y problemas:</b>

- ¿Ha enfrentado problemas relacionados con el riego, como escasez de agua o falta de uniformidad en la distribución?- ¿Cómo ha solucionado dichos problemas?
- ¿Ha enfrentado problemas relacionados con el cambio brusco en el clima últimamente? ¿Cómo ha mitigado estos cambios?
- ¿Qué dificultades encuentra al verificar la calidad del suelo? ¿Cómo afecta una mala verificación a la calidad de los productos?
- ¿Qué tan complejo es, para usted, identificar y corregir los posibles imprevistos?
- ¿Cómo afectan estos problemas a su productividad y rentabilidad?
- ¿Qué obstáculos ha encontrado al intentar implementar nuevas tecnologías en sus cultivos?

<b>Deseos del usuario:</b>

- ¿Qué información le gustaría recibir para tomar mejores decisiones sobre sus cultivos?
- ¿Busca mejorar la eficiencia del uso de recursos como el agua y los fertilizantes? Si es así, ¿qué métodos emplea?

<b>Segmento 2: Centros de investigación agrícola</b>

**Preguntas sobre su experiencia:**

- ¿Cuál es tu rol dentro del centro de investigación y en qué proyectos estás actualmente involucrado?
- ¿Cómo gestionan y controlan el riego en los cultivos? ¿Qué herramientas utilizan para hacer estas mediciones?
- ¿Cómo verifican la calidad del suelo de los cultivos al momento de realizar sus experimentos?
- ¿Qué características valoras más en una herramienta para la recolección de datos?
- ¿Cómo se procesan los datos recolectados en los diferentes experimentos?
- ¿De qué manera usted visualiza los datos recolectados en los diferentes experimentos?

<b>Desafíos y problemas:</b>

- ¿Qué desafíos enfrenta usualmente al momento de hacer mediciones de datos (Ejemplo, humedad, temperatura, etc)?
- ¿Ha tenido problemas para obtener datos precisos y en tiempo real? ¿Cómo han afectado estos problemas sus resultados de investigación?

**Deseos:**

- ¿Qué datos le gustaría recolectar para mejorar su comprensión de los procesos agrícolas y desarrollar nuevas tecnologías?
- ¿Usted desearía que ciertos procesos fueran automatizados? Si es así, ¿cuáles procesos?

**A continuación, se presenta al entrevistado la idea del proyecto junto a las principales funcionalidades que esta posee.**

- ¿Qué te parece la propuesta de proyecto?
- ¿Alguna vez ha usado una aplicación y dispositivo como el presentado? ¿Cuál fue su experiencia?
- ¿Cuál es el aspecto que más le llama la atención?
- ¿Qué otras características le gustaría que tuviera la aplicación?

### 2.2.2. Registro de entrevistas
- Entrevistas realizadas a Medianos agricultores (Segmento 1):

| **Entrevista 1** | **Juan Armando Castilla Saldaña** |
| --- | --- |
| **Edad** | 38 |
| **Ocupación** | Tecnico Agropecuario |
| **Distrito** | Ica |
| **Fecha** | 23-08-2024 |
| <img src="assets/ss_entrevistas/segmento1_entrevista1.png"/> | La entrevista fue realizada a Juan Castilla, un técnico agropecuario de 38 años dedicado al cultivo de cítricos en la región de Ica. Él trabaja en un fundo que dirige su producción hacia el mercado mayorista, tanto nacional como internacional, por lo que es crucial asegurar la alta calidad del producto. Para lograr esto, ajusta los costos y proyecta inversiones basándose en datos críticos como los porcentajes de maduración de los cultivos. Además, realiza análisis psicoquímicos del suelo y utiliza un sistema de riego por goteo con proyección a automatización. Juan menciona que ha enfrentado desafíos climáticos, como el fenómeno de El Niño, que han requerido un aumento en el riego y la aplicación de bioestimulantes para mantener la productividad. En cuanto a la calidad del suelo, toma muestras, las envía a laboratorio y aplica un programa nutricional basado en los resultados. Aunque ha trabajado con tecnología de sensores para el riego automatizado, ha enfrentado problemas con la señal en áreas remotas. Castilla considera interesante la propuesta de automatizar el riego y el monitoreo nutricional mediante una aplicación, pero subraya la importancia de evaluar los costos y beneficios antes de su implementación. |
| **URL de la grabación** |  |
| **Timming** |  |





- Entrevistas realizadas a Centros de investigación agrícola (Segmento 2):

| **Entrevista 4** | **Piero Segundo Silvano Guerra** |
| --- | --- |
| **Edad** | 21 |
| **Ocupación** | Practicante de Agronomía en INIA|
| **Distrito** | Iquitos |
| **Fecha** | 23-08-2024 |
| <img src="assets/ss_entrevistas/segmento2_entrevista1.png"/> | Nuestro invitado Piero Silvano, nos comenta que está en un proyecto referente al cultivo del cacao, y que es encargado de gestionar el riego y asegurarse que las plantas estén en condiciones óptimas para su crecimiento. Nos comenta que cuentan con sistemas de riegos manuales que se conectan a una llave de las cuales personalmente tiene que dirigirse a encender dicha llave para que el sistema de riego sea activado, valora mucho que las herramientas para recolectar datos sean fáciles de usar, porque el cacao requiere un control riguroso, menciona que los datos recolectados se registran manualmente por medio de fotos y en hojas de cálculo donde se procesa la información. También nos menciona que el desafío principal es obtener mediciones exactas de humedad y temperatura constante, dado que el clima de Iquitos es bastante raro, porque en un solo dia puede estar soleado y llover. Nos comenta que sus deseos son recolectar datos precisos sobre los nutrientes del suelo y la humedad y sobre todo automatizar el sistema de riego y las mediciones del clima y suelo. Respecto a la idea del proyecto, nos menciona que le entusiasma mucho ver cómo nuestra solución podría adaptarse a cultivos específicos como el cacao, que requiere un manejo preciso de las condiciones ambientales. |
| **URL de la grabación** | [upc-pre-202402-si572-SW71-HidroBots-needfinding-sprint-1](Link de la entrevista) |
| **Timming** | Timming |


### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas

**Segmento 1: Medianos agricultores**

![User Persona: Medianos Agricultores](assets/ss_entrevistas/segmento1_userpersona.png)


**- Segmento 2: Centros de Investigación Agrícola**

![User Persona: Centros de Investigación Agrícola](assets/ss_entrevistas/segmento2_userpersona.png)

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

**Segmento 1: Medianos agricultores**
![User Persona: EmpathyMapping](assets/EmpathyMapping/Segment1.png)

**- Segmento 2: Centros de Investigación Agrícola**

![User Persona: EmpathyMapping](assets/EmpathyMapping/Segment2.png)

### 2.3.5. As-Is Scenario Mapping


## 2.4. Ubiquitous Language

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

## 3.2. User Stories

## 3.3. Impact mapping

## 3.4. Product Backlog

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
