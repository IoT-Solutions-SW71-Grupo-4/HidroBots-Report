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
| **Aspecto**                              | **HidroBots** | **Netafim Perú** | **Irritec Perú** | **Camposol** |
|------------------------------------------|----------------|-------------------------------|--------------------------------|----------------------------|
| **Overview**                             | Solución IoT que automatiza el riego en cultivos agrícolas, permitiendo la toma de decisiones en tiempo real. Está dirigida a medianos agricultores y centros de investigación agrícola en Perú. | Netafim es un líder global en riego tecnificado, especializado en sistemas de goteo y microaspersión. Tiene una sólida presencia en Perú, ofreciendo tecnología avanzada y soporte técnico. | Irritec, una empresa internacional, se enfoca en soluciones de riego por goteo y microaspersión. Tiene una buena penetración en el mercado peruano, especialmente entre medianos y pequeños agricultores. | Camposol es una de las principales agroindustrias del Perú, que utiliza tecnologías avanzadas, incluidas soluciones IoT, para gestionar eficientemente sus cultivos a gran escala. |
| **Ventaja**                              | Ofrece automatización completa del riego con control remoto, monitoreo en tiempo real, y una interfaz amigable diseñada para facilitar su uso por medianos agricultores. | Netafim se destaca por su tecnología avanzada y una red de distribución sólida, lo que le permite ofrecer soluciones de riego de alta precisión a gran escala. | Fuerte presencia en el mercado peruano con soluciones de riego accesibles, enfocadas en la eficiencia del agua y soporte técnico local. | Camposol cuenta con una infraestructura masiva y recursos suficientes para integrar tecnologías IoT avanzadas en todas sus operaciones agrícolas. |
| **Mercado Objetivo**                     | Medianos agricultores y centros de investigación agrícola en Perú. | Grandes y medianos agricultores que buscan soluciones de riego tecnificado de alta precisión. | Medianos y pequeños agricultores que requieren sistemas de riego eficientes y de bajo costo. | Grandes agroindustrias y empresas agrícolas que operan tanto en Perú como en mercados internacionales. |
| **Estrategias de Marketing**             | Promoción en ferias agrícolas, eventos de la industria y campañas en redes sociales. Se enfoca en educar a los agricultores sobre el valor de las tecnologías IoT en la agricultura. | Netafim utiliza marketing directo, demostraciones en campo y participa en ferias internacionales para mostrar su tecnología de vanguardia. | Irritec participa en ferias locales, colabora con cooperativas y utiliza marketing educativo para destacar los beneficios de sus sistemas de riego. | Camposol invierte en publicidad a gran escala, tiene una presencia sólida en ferias internacionales y mantiene alianzas estratégicas con instituciones gubernamentales. |
| **Producto & Servicios**                 | Solución IoT para riego automatizado, con monitoreo en tiempo real de la humedad del suelo, control remoto, y alertas personalizadas. | Ofrece sistemas de riego por goteo, microaspersión, y control avanzado, personalizados para diversos tipos de cultivos y condiciones agrícolas. | Proporciona sistemas de riego por goteo y microaspersión, con un enfoque en la eficiencia hídrica y la facilidad de uso para los agricultores. | Gestiona cultivos a gran escala con integración de tecnologías IoT para monitoreo, control y análisis de datos en toda la cadena de valor agrícola. |
| **Precios & Costos**                     | Precios basados en suscripción y venta de hardware, con opciones personalizables según las necesidades de cada agricultor. | Precios elevados, orientados a grandes y medianos agricultores que buscan soluciones premium de riego tecnificado. | Precios más accesibles, con opciones de financiamiento y soporte técnico, especialmente para pequeños y medianos agricultores. | Precios elevados debido a la integración de múltiples tecnologías avanzadas, dirigidos a grandes empresas agroindustriales. |
| **Canales de Distribución (Web y/o Móvil)** | Solución accesible tanto en plataformas web como móviles, permitiendo el control y monitoreo desde cualquier dispositivo. | Distribución principalmente a través de distribuidores autorizados y venta directa, con soporte técnico en campo. | Venta a través de distribuidores locales y soporte técnico directo, con presencia en el mercado peruano. | Camposol utiliza sistemas propios de distribución y ofrece acceso a sus plataformas de monitoreo para sus clientes principales. |
| **Fortalezas**                           | Innovación tecnológica, enfoque en automatización y adaptabilidad para medianos agricultores, con una interfaz fácil de usar. | Liderazgo en el mercado global, tecnología avanzada y una red de distribución sólida y bien establecida. | Presencia local fuerte, precios competitivos y enfoque en la eficiencia del agua con un soporte técnico accesible. | Capacidad para integrar múltiples tecnologías avanzadas, con una infraestructura robusta y presencia internacional. |
| **Debilidades**                          | Es una startup nueva con menor presencia en el mercado y enfrenta la posible resistencia de los agricultores tradicionales a adoptar nuevas tecnologías. | Sus soluciones tienen costos elevados, lo que puede limitar su acceso a pequeños agricultores con menos capacidad de inversión. | No ofrece soluciones IoT avanzadas y se enfoca principalmente en sistemas de riego sin automatización completa. | Dependencia de mercados internacionales y un alto costo de implementación, lo que puede limitar su flexibilidad para atender a pequeños agricultores. |
| **Oportunidades**                        | Crecimiento en la adopción de tecnologías IoT en la agricultura peruana y expansión hacia otros mercados regionales con necesidades similares. | Expansión en mercados emergentes y mayor integración de tecnologías innovadoras para ofrecer soluciones más completas y adaptadas. | Desarrollo de soluciones más avanzadas que integren riego tecnificado con tecnologías IoT para una mayor automatización. | Expansión a otros mercados de América Latina y desarrollo de nuevas tecnologías que mejoren la eficiencia y sostenibilidad operativa. |
| **Amenazas**                             | Competencia con empresas consolidadas y posibles barreras en la adopción tecnológica por parte de los usuarios tradicionales. | Competencia creciente de startups que ofrecen soluciones más accesibles y personalizadas para pequeños y medianos agricultores. | Competencia de empresas con soluciones más integradas o avanzadas y presión en los precios debido a su enfoque en mercados más pequeños. | Cambios regulatorios internacionales, fluctuaciones en el mercado global y competencia con otras grandes agroindustrias. |

### 2.1.2. Estrategias y tácticas frente a competidores
### 1. **Diferenciación basada en la Innovación y la Usabilidad**
   - **Estrategia:** Destacar la innovación tecnológica de HidroBots y su facilidad de uso frente a la competencia.
   - **Tácticas:**
     - **Desarrollo de una Interfaz Intuitiva:** Asegurar que la interfaz de la aplicación sea amigable y fácil de usar, con tutoriales interactivos y soporte en tiempo real para ayudar a los agricultores a adaptarse rápidamente a la tecnología.
     - **Personalización:** Ofrecer opciones de personalización en la app para que los agricultores puedan adaptar las soluciones a sus necesidades específicas, un área donde competidores como Netafim y Camposol, que tienen soluciones más genéricas, podrían no ser tan flexibles.
     - **Innovación Continua:** Implementar un ciclo rápido de mejoras y actualizaciones basadas en el feedback de los usuarios, introduciendo nuevas funciones antes que la competencia para mantener a HidroBots a la vanguardia.

### 2. **Enfoque en la Educación y el Soporte al Cliente**
   - **Estrategia:** Abordar la barrera de adopción tecnológica educando a los usuarios y proporcionando un soporte robusto.
   - **Tácticas:**
     - **Campañas Educativas:** Realizar talleres y webinars en colaboración con universidades agrícolas y centros de investigación para educar a los agricultores sobre los beneficios del IoT en la agricultura.
     - **Soporte Técnico Dedicado:** Establecer un equipo de soporte técnico disponible 24/7 para resolver dudas y problemas de los usuarios, superando a la competencia en términos de servicio al cliente.
     - **Pruebas Piloto:** Ofrecer pruebas piloto gratuitas a potenciales clientes para demostrar la efectividad de HidroBots en comparación con sistemas tradicionales o soluciones de la competencia.

### 3. **Segmentación y Marketing Dirigido**
   - **Estrategia:** Dirigir esfuerzos de marketing específicamente hacia medianos agricultores y centros de investigación, aprovechando las debilidades de la competencia en este segmento.
   - **Tácticas:**
     - **Marketing de Contenidos:** Crear contenido dirigido específicamente a medianos agricultores y centros de investigación, como estudios de caso, informes técnicos y videos tutoriales que muestren cómo HidroBots puede resolver sus problemas específicos.
     - **Alianzas Estratégicas:** Establecer alianzas con cooperativas agrícolas y asociaciones de agricultores para acceder directamente a los segmentos de mercado que pueden no estar bien atendidos por competidores más grandes como Netafim y Camposol.
     - **Publicidad Geolocalizada:** Utilizar la publicidad geolocalizada para dirigirse a zonas agrícolas específicas en Perú, maximizando la relevancia de los mensajes publicitarios.

### 4. **Competitividad en Precio y Valor**
   - **Estrategia:** Ofrecer una estructura de precios competitiva que justifique la inversión en HidroBots frente a soluciones más costosas como las de Netafim y Camposol.
   - **Tácticas:**
     - **Modelos de Suscripción Flexibles:** Implementar modelos de suscripción que permitan a los agricultores pagar solo por las funciones que utilizan, reduciendo las barreras de entrada.
     - **Ofertas de Lanzamiento:** Ofrecer descuentos y promociones en los primeros meses para incentivar la adopción temprana de la tecnología.
     - **Cálculo de ROI:** Desarrollar herramientas dentro de la app que permitan a los usuarios calcular su retorno sobre la inversión (ROI), demostrando el valor a largo plazo de la adopción de HidroBots frente a soluciones más tradicionales y costosas.

### 5. **Aprovechar las Oportunidades del Mercado**
   - **Estrategia:** Expandir rápidamente en mercados emergentes dentro del Perú y Latinoamérica antes de que los competidores consoliden su presencia.
   - **Tácticas:**
     - **Expansión Regional:** Identificar y expandirse en regiones agrícolas emergentes en Perú donde la penetración de tecnologías de riego tecnificado aún es baja.
     - **Internacionalización:** Explorar mercados en otros países de Latinoamérica con necesidades similares, posicionando a HidroBots como una solución regional líder en tecnología agrícola.
     - **Desarrollo de Comunidad:** Crear una comunidad de usuarios en línea para fomentar el intercambio de conocimientos y experiencias, fortaleciendo la lealtad de los clientes y aumentando la visibilidad de HidroBots en nuevos mercados.

### 6. **Mitigar Amenazas Externas**
   - **Estrategia:** Reducir la dependencia de factores externos y preparar respuestas a las acciones de la competencia.
   - **Tácticas:**
     - **Diversificación de Proveedores:** Establecer relaciones con múltiples proveedores de hardware y servicios para evitar interrupciones en la cadena de suministro.
     - **Monitoreo Competitivo:** Implementar un sistema de monitoreo competitivo para estar al tanto de las acciones de los competidores y ajustar las estrategias de manera proactiva.
     - **Plan de Contingencia:** Desarrollar un plan de contingencia para mitigar el impacto de posibles cambios regulatorios o fluctuaciones en el mercado agrícola.

Estas estrategias y tácticas están diseñadas para posicionar a HidroBots como una solución innovadora, accesible y centrada en el cliente en el mercado peruano de tecnologías agrícolas, enfrentando eficazmente a competidores establecidos y capturando nuevas oportunidades en el sector.

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


| **Entrevista 2** | **Martin Cifuentes** |
| --- | --- |
| **Edad** | 20 |
| **Ocupación** | Practicante de ingenieria agricola |
| **Distrito** | Ica |
| **Fecha** | 25-08-2024 |
| <img src="assets/ss_entrevistas/Segmento1_entrevista2.png"/> | La entrevista fue realizada a Martin, un asistente de un empresario agricola años dedicado al cultivo de tuberculos la región de Ica. Él trabaja en una empresa que siembra y comercializa tuberculos dirigiendo su produccion hacia grandes comerciantes del mercado nacional. Para lograr esto, se hace uso de una siembra manual y gracias a la experiencia en la prediccion del clima manejan su negocio basándose en guias de mantenimiento y la experiencia pura de sus empleados. Se esta viendo el como implementar un sistema de riego en sus tierras para mejorar la calidad y rentabildiad de sus productos. Aunque no ha trabajado con tecnología de sensores para el riego automatizado, ha sabido manejar de una manera optima el bienestar de sus cultivos. |
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

| **Entrevista 5** | **Diego Miguel Ramirez Ortega** |
| --- | --- |
| **Edad** | 25 |
| **Ocupación** | Practicante de Agronomía|
| **Distrito** | Ica |
| **Fecha** | 26-08-2024 |
| <img src="assets/ss_entrevistas/segmento2_entrevista2.png"/> | El practicante Diego Ramirez nos cuenta su experiencia desde que trabajo en la producción de uva en una empresa de exportación de esta misma. Nos cuenta los métodos que usa y cuales fueron sus principales problematicas que le impulsaron para implementarlas en el trabajo. Igualmente los beneficios que les trajo esta y la importancia que tiene la tecnologia en este sector. En su experiencia afirma que el regado por goteo y el sensor de tierra que utilizan, para identificar la fertilidad de sus tierras antes de realizar una siembra, tubo un resultado positivo en sus ganancias y cantidad de producción en los mese que estos se realizaban. |
| **URL de la grabación** | [upc-pre-202402-si572-SW71-HidroBots-needfinding-sprint-1](Link de la entrevista) |
| **Timming** | Timming |

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas

**Segmento 1: Medianos agricultores**

![User Persona: Medianos Agricultores](assets/ss_entrevistas/segmento1_userpersona.png)


**Segmento 2: Centros de Investigación Agrícola**

![User Persona: Centros de Investigación Agrícola](assets/ss_entrevistas/segmento2_userpersona.png)

### 2.3.2. User Task Matrix

<table>
  <thead>
    <tr>
      <th rowspan="2">Tareas</th>
      <th colspan="2">Medianos Agricultores</th>
      <th colspan="2">Centro de Investigaciones Agrícolas</th>
    </tr>
    <tr>
      <th>Frecuencia</th>
      <th>Importancia</th>
      <th>Frecuencia</th>
      <th>Importancia</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Supervisar el riego</td>
      <td>Diario</td>
      <td>Alta</td>
      <td>Semanal</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Monitorear la calidad del suelo</td>
      <td>Semanal</td>
      <td>Alta</td>
      <td>Diario</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Consultar datos históricos</td>
      <td>Mensual</td>
      <td>Media</td>
      <td>Trimestral</td>
      <td>Media</td>
    </tr>
    <tr>
      <td>Optimizar el uso del agua</td>
      <td>Semanal</td>
      <td>Alta</td>
      <td>Mensual</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Planificar cultivos futuros</td>
      <td>Quincenal</td>
      <td>Alta</td>
      <td>Mensual</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Gestionar recursos genéticos</td>
      <td>Mensual</td>
      <td>Media</td>
      <td>Trimestral</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Adoptar nuevas tecnologías</td>
      <td>Mensual</td>
      <td>Alta</td>
      <td>Mensual</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Reportar problemas de plagas</td>
      <td>Quincenal</td>
      <td>Media</td>
      <td>Quincenal</td>
      <td>Media</td>
    </tr>
    <tr>
      <td>Mejorar la gestión del suelo</td>
      <td>Semanal</td>
      <td>Alta</td>
      <td>Mensual</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Realizar análisis de suelo</td>
      <td>Trimestral</td>
      <td>Alta</td>
      <td>Trimestral</td>
      <td>Alta</td>
    </tr>
  </tbody>
</table>


### 2.3.3. User Journey Mapping

**Segmento 1: Medianos agricultores**

![User Journey Mapping: Medianos Agricultores](assets/Journey_Map/segment1.png)


**Segmento 2: Centros de Investigación Agrícola**

![User Journey Mapping: Centros de Investigación Agrícola](assets/Journey_Map/segment2.png)


### 2.3.4. Empathy Mapping

**Segmento 1: Medianos agricultores**
![Empathy Mapping: Medianos Agricultores](assets/EmpathyMapping/Segment1.png)

**Segmento 2: Centros de Investigación Agrícola**

![Empathy Mapping: Centros de Investigación Agrícola](assets/EmpathyMapping/Segment2.png)

### 2.3.5. As-Is Scenario Mapping

**Segmento 1: Medianos agricultores**
![As-Is Scenario Mapping: Medianos agricultores](assets/As-Is_Scenario_Mapping/segment1.jpg)

**Segmento 2: Centros de Investigación Agrícola**

![As-Is Scenario Mapping: Centros de Investigación Agrícola](assets/As-Is_Scenario_Mapping/segment2.jpg)

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
