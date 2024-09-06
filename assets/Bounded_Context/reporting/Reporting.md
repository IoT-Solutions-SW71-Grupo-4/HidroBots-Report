### Índice
- [4.2. Tactical-Level Domain-Driven Design](https://github.com/CrackeletsGroup-IoT/upc-pre-202401-si572-sw71-CrackeletsGroup-report-tf/blob/capitulo4/capitulo4/CAPITULO%20IV.md#42-tactical-level-domain-driven-design)
  - [4.2.5. Bounded Context: Reporting](#421-bounded-context--booking)
    - [4.2.5.1. Domain Layer](#4211-domain-layer)
    - [4.2.5.2. Interface Context](#4212-interface-layer)
    - [4.2.5.3. Application Context](#4213-application-layer)
    - [4.2.5.4. Infrastructure Context](#4214-infrastructure-layer)
    - [4.2.5.5. Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
    - [4.2.5.6. Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
      - [4.2.5.6.1. Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
      - [4.2.5.6.2. Bounded Context Database Design Diagram](#42162-bounded-context-database-design-diagram)
  
<div align="justify">

### 4.2.5. Bounded Context:  Reporting    

El Reporting Context es responsable de recopilar y analizar los datos de los sensores IoT, como los niveles de humedad, nutrientes y temperatura, para generar reportes útiles para los agricultores e investigadores.          

#### 4.2.5.1. Domain Layer

El **Domain Layer** encapsula la lógica de negocio y las reglas que rigen el funcionamiento del **Reporting Context**. 

*Aggregate*

| **Nombre**      | **Categoría**     | **Propósito** |
|:---------------|:-----------------|:--------------|
| Report         | Entity/Aggregate  | Representa un análisis basado en los datos de los sensores, como niveles de humedad, temperatura y nutrientes del suelo. |

  *Atributos*

| **Nombre**        | **Tipo de dato**          | **Visibilidad** | **Descripción** |
|:-----------------:|:------------------------:|:---------------:|:----------------|
| id                | Long                     | Private         | Identificador único del reporte |
| reportDate        | Date                     | Private         | Fecha de generación del reporte |
| humidityLevels    | Map<Date, Double>        | Private         | Niveles de humedad recopilados de los sensores IoT a lo largo del tiempo |
| temperatureLevels | Map<Date, Double>        | Private         | Niveles de temperatura recogidos de los sensores |
| nutrientLevels    | Map<Date, Map<String, Double>> | Private  | Niveles de nutrientes (como nitrógeno, potasio, fósforo) por fecha y tipo |
| summary           | String                   | Private         | Resumen del estado del cultivo basado en los datos de humedad, temperatura y nutrientes |
| readingsList      | List<Reading>            | Private         | Lista de lecturas de sensores que incluyen datos como humedad, temperatura y nutrientes |


*Métodos* 

| **Nombre**       | **Tipo de retorno** | **Visibilidad** | **Descripción** |
|:----------------:|:------------------:|:---------------:|:----------------|
| addReading       | Void               | Public          | Añadir una nueva lectura de sensores (humedad, temperatura, nutrientes) al reporte. |
| generateSummary  | String             | Public          | Genera un resumen basado en las lecturas de humedad, temperatura y nutrientes. |
| generateVisualization    | Object              | Public          |  Genera un objeto que representa un gráfico de los datos del reporte. |


#### 4.2.5.2. Interface Context

#### 4.2.5.3. Application Context

#### 4.2.5.4. Infrastructure Context


#### 4.2.5.5. Bounded Context Software Architecture Component Level Diagrams


#### 4.2.5.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.5.6.1. Bounded Context Domain Layer Class Diagrams


##### 4.2.5.6.2. Bounded Context Database Design Diagram

</div>



