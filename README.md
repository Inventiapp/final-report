# <center>Project Report</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software - 2025-20</strong><br>
    <strong>Desarrollo de Aplicaciones Open Source - 7391</strong><br>
    <strong>Profesor: Hugo Allan Mori Paiva</strong><br>
    <br><strong>Informe del Trabajo Final</strong>
</p>


<p align="center">
    <strong>Startup: Inventiapp</strong><br>
    <strong>Producto: StockTrack</strong>
</p>

<div style="text-align:center;">
    <h3 align="center">Team Members:</h3>
    <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
            <td>Vanessa May Lang Choy Robles</td>
            <td>U202317450</td>
        </tr>
        <tr>
            <td>María Patricia Hernández Uchuya</td>
            <td>U202311258</td>
        </tr>
        <tr>
            <td>Dayro Richard Rios Piñan</td>
            <td>U202315283</td>
        </tr>
        <tr>
            <td>Fabiola Del Rocio Saldaña Ayala</td>
            <td>U202313773</td>
        </tr>
        <tr>
            <td>Piero Angel Sulca Sanchez</td>
            <td>U202423711</td>
        </tr>
    </table>
</div>

<p align="center">
    <strong>Septiembre, 2025</strong>
</p>

<br>

<div style="text-align:center;">
    <h1 align="center">Registro de versiones del Informe</h1>
    </br>
    <table align="center">
        <tr>
            <th>Versión</th>
            <th>Fecha</th>
            <th>Autor</th>
            <th>Descripción de modificaciones</th>
        </tr>
        <tr>
            <td>0</td>
            <td>3/09/2025</td>
            <td>María Hernández</td>
            <td>Creación del reporte.</td>
        </tr>
    </table>
<div>

<br>

# Project Report Collaboration Insights
Link del repositorio del reporte: https://github.com/Inventiapp/workstation-markdown

## TB1

<br>

# Contenido
[Student Outcome](#student-outcome)

- [Project Report](#project-report)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
  - [TB1](#tb1)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Objetivos SMART](#objetivos-smart)
- [Capítulo I: Presentación](#capítulo-i-presentación)
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
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
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
  - [4.1. Style Guidelines.](#41-style-guidelines)
    - [4.1.1. General Style Guidelines.](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines.](#412-web-style-guidelines)
  - [4.2. Information Architecture.](#42-information-architecture)
    - [4.2.1. Organization Systems.](#421-organization-systems)
    - [4.2.2. Labeling Systems.](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems.](#424-searching-systems)
    - [4.2.5. Navigation Systems.](#425-navigation-systems)
  - [4.3. Landing Page UI Design.](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe.](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up.](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design.](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes.](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams.](#442-web-applications-wireflow-diagrams)
    - [4.4.2. Web Applications Mock-ups.](#442-web-applications-mock-ups)
    - [4.4.3. Web Applications User Flow Diagrams.](#443-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping.](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture.](#46-domain-driven-software-architecture)
    - [4.6.1. Design-Level Event Storming.](#461-design-level-event-storming)
    - [4.6.2. Software Architecture Context Diagram.](#462-software-architecture-context-diagram)
    - [4.6.3. Software Architecture Container Diagrams.](#463-software-architecture-container-diagrams)
    - [4.6.4. Software Architecture Components Diagrams.](#464-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design.](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams.](#471-class-diagrams)
  - [4.8. Database Design.](#48-database-design)
    - [4.8.1. Database Diagrams](#481-database-diagrams)
- [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management.](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration.](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management.](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions.](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration.](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services \& Applications Implementation.](#52-landing-page-services--applications-implementation)
    - [5.2.X. Sprint n](#52x-sprint-n)
      - [5.2.X.1. Sprint Planning n.](#52x1-sprint-planning-n)
      - [5.2.X.2. Aspect Leaders and Collaborators.](#52x2-aspect-leaders-and-collaborators)
      - [5.2.X.3. Sprint Backlog n.](#52x3-sprint-backlog-n)
      - [5.2.X.4. Development Evidence for Sprint Review.](#52x4-development-evidence-for-sprint-review)
      - [5.2.X.5. Execution Evidence for Sprint Review.](#52x5-execution-evidence-for-sprint-review)
      - [5.2.X.6. Services Documentation Evidence for Sprint Review.](#52x6-services-documentation-evidence-for-sprint-review)
      - [5.2.X.7. Software Deployment Evidence for Sprint Review.](#52x7-software-deployment-evidence-for-sprint-review)
      - [5.2.X.8. Team Collaboration Insights during Sprint](#52x8-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews.](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas.](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas.](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas.](#533-evaluaciones-según-heurísticas)
  - [5.4. Video About-the-Product.](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones.](#conclusiones-y-recomendaciones)
  - [Video About-the-Team.](#video-about-the-team)
- [Conclusiones](#conclusiones-1)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones-1)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

  
<br>
<br>

# Student Outcome

<br>
<br>

# Objetivos SMART


# Capítulo I: Presentación

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
### 1.1.2. Perfiles de integrantes del equipo

<table align="center" border="1" cellspacing="0" cellpadding="8" style="width: 90%; border-collapse: collapse;">
  <tr>
    <td style="width: 150px; text-align: center;">
      <img src=""  width="520"></img>
    </td>
      <td>
          <p align="center"><strong>Vanessa May Lang Choy Robles - U202317450</strong></p>
          <p align="justify">
            Soy una estudiante responsable con el trabajo. Respeto y escucho la opinión de los demás ayudando al trabajo en equipo. Me comprometo a contribuir al equipo siendo puntual en las reuniones y responsable en las entregas.
          </p>
    </td>
  </tr>
</table>

<table align="center" border="1" cellspacing="0" cellpadding="8" style="width: 90%; border-collapse: collapse;">
  <tr>
    <td style="width: 150px; text-align: center;">
      <img src="assets/Chapter-I/maria-hernandez.jpeg"  width="520"></img>
    </td>
      <td>
          <p align="center"><strong>María Patricia Hernández Uchuya - U202311258</strong></p>
          <p align="justify">
            Estudio la carrera de Ingeniería de Software, tengo 19 años y actualmente me encuentro cursando el sexto ciclo de dicha carrera. Tengo conocimientos en C++, C#, Python, Java, HTML, CSS, JavaScript y Vue. Me considero una persona con responsabilidad, optimismo y honestidad, cualidades que considero fundamentales para una colaboración efectiva en equipo y un buen desarrollo en este proyecto.
          </p>
    </td>
  </tr>
</table>

<table align="center" border="1" cellspacing="0" cellpadding="8" style="width: 90%; border-collapse: collapse;">
  <tr>
    <td style="width: 150px; text-align: center;">
      <img src=""  width="520"></img>
    </td>
      <td>
          <p align="center"><strong>Dayro Richard Rios Piñan - U202315283</strong></p>
          <p align="justify">
            ...
          </p>
    </td>
  </tr>
</table>

<table align="center" border="1" cellspacing="0" cellpadding="8" style="width: 90%; border-collapse: collapse;">
  <tr>
    <td style="width: 150px; text-align: center;">
      <img src="assets/Chapter-I/fabiola.jpeg"  width="520"></img>
    </td>
      <td>
          <p align="center"><strong>Fabiola Del Rocio Saldaña Ayala - U202313773</strong></p>
          <p align="justify">
            Mi nombre es Fabiola Saldaña, tengo 19 años y actualmente curso el 6to ciclo de la carrera de Ingeniería de Software. En lo personal busco aprender constantemente y me considero alguien responsable, proactiva y dedicada con mis trabajos. Es por ello que me comprometo apoyar al equipo con mis habilidades y conocimientos para alcanzar los mejores resultados.
          </p>
    </td>
  </tr>
</table>
<table align="center" border="1" cellspacing="0" cellpadding="8" style="width: 90%; border-collapse: collapse;">
  <tr>
    <td style="width: 150px; text-align: center;">
      <img src=""  width="520"></img>
    </td>
      <td>
          <p align="center"><strong>Piero Angel Sulca Sanchez - U202423711</strong></p>
          <p align="justify">
             ...
          </p>
    </td>
  </tr>
</table>

## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática
### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
#### 1.2.2.2. Lean UX Assumptions
#### 1.2.2.3. Lean UX Hypothesis Statements
#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

<br>
<br>

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores
### 2.1.1. Análisis competitivo
### 2.1.2. Estrategias y tácticas frente a competidores
## 2.2. Entrevistas

En esta sección se lleva a cabo la investigación y recopilación de información mediante entrevistas a los usuarios de cada segmento objetivo, con el propósito de comprenderlos de manera más profunda.

### 2.2.1. Diseño de entrevistas

En esta sección se plantean preguntas principales y complementarias destinadas a entrevistas con cada uno de nuestros segmentos objetivos, con el propósito de recopilar la mayor cantidad posible de información relevante. Tras un análisis detallado, se definieron las siguientes preguntas para aplicar en las entrevistas a dichos segmentos.

**Segmento #1: Bodegas especializadas por rubro**

Preguntas principales:
1. ¿Podrías describirme cómo gestionas actualmente el inventario de tu bodega?
2. ¿Cuáles consideras que son los principales desafíos al momento de organizar tus productos?
3. ¿Has enfrentado pérdidas o inconvenientes por errores en el inventario? ¿Cómo los solucionaste?
4. ¿Qué tan relevante es para ti contar con un control del stock en tiempo real?
5. ¿Empleas algún sistema o herramienta digital para la gestión? Si es así, ¿cuál utilizas y cómo ha sido tu experiencia?
6. ¿De qué manera detectas cuando un producto está por agotarse o próximo a vencer?

Preguntas complementarias:
- ¿Qué tipo de reportes o información te gustaría obtener acerca de tu inventario?
- ¿Qué navegador y sistema operativo utilizas más? ¿Qué dispositivos utilizas con mayor frecuencia en tu trabajo (laptop, celular, tablet)?
- ¿Cómo imaginas que una plataforma digital podría ayudarte a optimizar tu operación diaria?
- ¿Qué redes sociales o canales digitales empleas para vender tus productos?

**Segmento #2: Startups y emprendedores en expansión con necesidades logísticas**

Preguntas principales:
1. ¿Cómo gestionas actualmente el inventario de tu negocio?
2. ¿En qué situaciones sientes que el control del stock te limita o te hace perder tiempo?
3. ¿De qué forma registras las entradas y salidas de productos?
4. ¿Qué aspectos te gustaría mejorar en tu proceso logístico actual?
5. ¿Has evaluado implementar una plataforma para gestionar tu inventario? ¿Por qué tomarías o no esa decisión?

Preguntas complementarias:

- ¿Qué herramientas digitales utilizas actualmente en tu negocio?
- ¿Dónde se encuentran almacenados tus productos?
- ¿Con qué frecuencia necesitas revisar tu stock?
- ¿Qué redes sociales o canales digitales empleas para vender tus productos?
- ¿Qué navegador y sistema operativo utilizas más? ¿Qué dispositivos utilizas con mayor frecuencia en tu trabajo (laptop, celular, tablet)?


### 2.2.2. Registro de entrevistas

Entrevista x:

[video]

[XX:XX - XX:XX]

Duración: 

Link de la entrevista: (link acortado en algun shortener)

Nombre: 

Apellidos: 

Edad: 

Distrito:

Resumen:
### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding
En el siguiente apartado, analizaremos a nuestros segmentos objetivos para identificar sus necesidades y en base a esto ofrecerles soluciones óptimas a sus problemas.

### 2.3.1. User Personas
**Segmento 1: Dueños de bodegas**
<img src="assets/Chapter-II/segmento1.png" alt="User persona - segmento 1" width="700"/>


**Segmento 2: Startups y emprendedores en expansión con necesidades logísticas**
<img src="assets/Chapter-II/segmento2.png" alt="User persona - segmento 2" width="700"/>

### 2.3.2. User Task Matrix

**Segmento 1: Dueños de bodegas**

| **Task Matrix**                                                     | **Frecuencia** | **Importancia** |
|----------------------------------------------------------------------|----------------|------------------|
| Supervisar el stock y revisar niveles de inventario                 | Alta           | Alta             |
| Realizar conteos físicos o auditorías manuales                      | Media          | Alta             |
| Negociar precios y coordinar con proveedores                        | Alta           | Alta             |
| Revisar reportes de ventas, rotación y márgenes                     | Media          | Alta             |
| Ingresar datos en Excel o sistemas básicos de control               | Media          | Media            |
| Delegar tareas a sus asistentes o empleados                         | Media          | Alta             |
| Atender clientes en tienda                                          | Alta           | Alta             |
| Coordinar pedidos con mayoristas o distribuidores                   | Alta           | Alta             |
| Capacitarse en nuevas herramientas tecnológicas                     | Baja           | Media            |
| Resolver errores de inventario (sobrestock, productos vencidos)  | Alta           | Alta             |

<br> <!-- Esto agrega espacio visual en algunas plataformas -->


**Segmento 2: Startups y emprendedores en expansión con necesidades logísticas**

| **Task Matrix**                                                                | **Frecuencia** | **Importancia** |
| ------------------------------------------------------------------------------ | -------------- | --------------- |
| Gestionar el envío y distribución de productos                                 | Alta           | Alta            |
| Coordinar con operadores logísticos y transportistas                           | Alta           | Alta            |
| Monitorear tiempos de entrega y resolver incidencias                           | Alta           | Alta            |
| Optimizar costos de transporte y almacenamiento                                | Media          | Alta            |
| Evaluar y contratar proveedores logísticos externos                            | Media          | Alta            |
| Implementar herramientas digitales para el control de logística                | Media          | Alta            |
| Revisar métricas de satisfacción del cliente respecto a entregas               | Media          | Alta            |
| Escalar la capacidad de operaciones en función de la demanda                   | Media          | Alta            |

### 2.3.3. User Journey Mapping
**Segmento 1: Dueños de bodegas**
<img src="assets/Chapter-II/journeymap1.png" alt="Journey map - segmento 1" width="700"/>

**Segmento 2: Startups y emprendedores en expansión con necesidades logísticas**
<img src="assets/Chapter-II/journeymap2.png" alt="Journey map - segmento 2" width="700"/>


### 2.3.4. Empathy Mapping
**Segmento 1: Dueños de bodegas**
<img src="assets/Chapter-II/empathymap1.png" alt="Empathy map - segmento 1" width="700"/>


**Segmento 2: Startups y emprendedores en expansión con necesidades logísticas**
<img src="assets/Chapter-II/empathymap2.png" alt="Empathy map - segmento 2" width="700"/>

## 2.4. Big Picture Event Storming

<img src="assets/Chapter-II/event-storming1.png" alt="Big Picture Event Storming" width="700"/>

<img src="assets/Chapter-II/event-storming2.png" alt="Big Picture Event Storming" width="700"/>
<img src="assets/Chapter-II/event-storming3.png" alt="Big Picture Event Storming" width="700"/>
<img src="assets/Chapter-II/event-storming4.png" alt="Big Picture Event Storming" width="700"/>




## 2.5. Ubiquitous Language
El siguiente glosario presenta los términos clave utilizados en el desarrollo del proyecto StockTrack. Este lenguaje común asegura que todos los miembros del equipo (técnicos y no técnicos) compartan una comprensión unificada de los conceptos centrales, facilitando la comunicación y el diseño colaborativo del sistema.

1. **Landing Page**: Página inicial de StockTrack que presenta la propuesta de valor y permite a los usuarios registrarse o iniciar sesión.

2. **Inventario**: Conjunto organizado de productos gestionados dentro de la plataforma, que incluye información como cantidades disponibles, ubicación en la bodega, lotes y fechas de vencimiento.

3. **Producto**: Unidad básica registrada en el sistema. Cada producto posee atributos como nombre, descripción, categoría, unidades de medida, stock mínimo y fecha de vencimiento.

4. **Stock**: Cantidad disponible de un producto específico dentro del inventario.

5. **Stock mínimo**: Nivel definido por el usuario que representa la cantidad mínima aceptable de un producto antes de requerir reposición.

6. **Stock bajo**: Estado de un producto cuyo nivel de stock ha alcanzado o está por debajo del stock mínimo definido.

7. **Panel de Control**: Interfaz principal de la plataforma que centraliza la visualización de métricas clave (inventario disponible, alertas de stock bajo, movimientos recientes y reportes).

8. **Movimiento de Inventario**: Registro de cualquier variación en las existencias de productos, incluyendo entradas (compras o reposiciones), salidas (ventas, pérdidas o devoluciones) y ajustes manuales.

9. **Reporte**: Representación visual o estadística generada por el sistema que resume información relevante del inventario (rotación de productos, quiebres de stock, productos próximos a vencer, etc.).

10. **Bodega**: Pequeño negocio de venta de productos de consumo diario, principalmente alimentos, bebidas y artículos de primera necesidad.

11. **Dueña/o de bodega**: Usuario que gestiona directamente la operación de su bodega y utiliza StockTrack para optimizar el control de inventario, evitar pérdidas y mejorar la eficiencia.

12. **Emprendedor/a**: Usuario en etapa de crecimiento que gestiona uno o más puntos de venta y requiere profesionalizar su gestión logística con herramientas digitales.

13. **Proveedor**: Persona o empresa que abastece a las bodegas o emprendedores con productos que serán registrados y gestionados en StockTrack.

14. **Pedido**: Solicitud de reposición o compra de productos hecha a un proveedor, ya sea de forma manual o asistida por las recomendaciones del sistema.

15. **Alerta**: Notificación generada automáticamente por el sistema cuando ocurre un evento relevante (stock bajo, productos próximos a vencer, quiebre de stock, etc.).



<br>
<br>

# Capítulo III: Requirements Specification

## 3.1. User Stories
## 3.2. Impact Mapping
## 3.3. Product Backlog

<br>
<br>

# Capítulo IV: Product Design

## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.
### 4.1.2. Web Style Guidelines.
## 4.2. Information Architecture
En esta sección se detallará parte importante de la estructura y etiquetado de la aplicación web.
### 4.2.1. Organization Systems
**Jerarquía del sistema de organización de la aplicación web**
<img src="assets/Chapter-IV/organization-system-herarchy-web-app.jpg" alt="Jerarquía del sistema de organización de la aplicación web" width="700"/>

**Jerarquía del sistema de organización de la landing page**
<img src="assets/Chapter-IV/organization-system-herarchy-landing-page.jpg" alt="Jerarquía del sistema de organización de la landing page" width="700"/>

### 4.2.2. Labeling Systems
En esta sección se especifica el conjunto de etiquetas que se utilizarán para representar la información y las acciones dentro de la plataforma StockTrack. El objetivo de este sistema de etiquetado es garantizar la simplicidad, evitar la confusión y presentar los datos de manera consistente para nuestros usuarios.

Para lograrlo, hemos definido un sistema de etiquetas con el mínimo número de palabras posible, asegurando que cada etiqueta comunique de forma clara y directa el conjunto de información que representa. A continuación, se detallan las etiquetas agrupadas por su función dentro de la aplicación.

**1. Etiquetas de Navegación Principal**

Representan las secciones principales de la aplicación y se ubicarán en el menú de navegación principal. Su propósito es permitir al usuario identificar y acceder a las funcionalidades clave de StockTrack de forma inmediata.

| Etiqueta | Uso / Contexto | Propósito / Justificación |
| :--- | :--- | :--- |
| **Dashboard** | Enlace en el menú principal. | Accede al panel de control principal. Se mantiene en inglés por ser un término estándar y universalmente reconocido en software. |
| **Productos** | Enlace en el menú principal. | Dirige a la sección de gestión del catálogo de productos. Es un término claro y directo. |
| **Inventario** | Enlace en el menú principal. | Accede a las funciones de movimientos de stock (entradas, salidas, ajustes). Representa el conjunto de acciones sobre el stock físico. |
| **Proveedores**| Enlace en el menú principal. | Dirige a la gestión de la lista de proveedores. Etiqueta inequívoca. |
| **Reportes** | Enlace en el menú principal. | Accede a la sección de análisis y visualización de datos. Término estándar y claro. |
| **Configuración**| Enlace en el menú principal. | Dirige a los ajustes de la cuenta, usuarios y alertas. Representa el conjunto de opciones de personalización del sistema. |

**2. Etiquetas de Acciones (Botones y Enlaces)**

Estas etiquetas indican acciones que el usuario puede realizar. Son verbos o frases cortas que comunican un resultado claro, diseñadas para ser intuitivas y guiar al usuario a completar sus tareas.

| Etiqueta | Uso / Contexto | Propósito / Justificación |
| :--- | :--- | :--- |
| **Añadir Nuevo**| Botón principal en secciones como Productos y Proveedores. | Inicia el proceso de creación de un nuevo elemento. "Añadir" es más amigable que "Crear". |
| **Guardar** | Botón para confirmar cambios en un formulario. | Acción estándar para persistir datos. Universalmente entendido. |
| **Cancelar** | Botón o enlace para descartar una acción o cerrar una ventana. | Acción estándar para anular un proceso sin guardar cambios. |
| **Editar** | Botón o ícono en listas y páginas de detalle. | Permite modificar la información de un elemento existente. |
| **Eliminar** | Botón o ícono para borrar un elemento. | Acción destructiva, claramente etiquetada. Siempre irá acompañada de una confirmación. |
| **Exportar** | Botón en la sección de Reportes y listas. | Permite al usuario descargar los datos (ej. a Excel o PDF). Comunica la función de forma precisa. |
| **Registrar Entrada**| Botón en la sección de Inventario. | Inicia el flujo para añadir stock de un producto. Describe la acción exacta. |
| **Registrar Salida**| Botón en la sección de Inventario. | Inicia el flujo para reducir stock por una venta u otro motivo. |

**3. Etiquetas de Estatus y Alertas**

Estas etiquetas comunican el estado actual de un producto o un proceso. A menudo estarán acompañadas de un color para reforzar visualmente el significado y permitir un escaneo rápido de la información.

| Etiqueta | Uso / Contexto | Propósito / Justificación |
| :--- | :--- | :--- |
| **En Stock** | Indicador de estado en la lista de productos. (Color: Verde) | Comunica que el nivel de stock está por encima del mínimo definido. |
| **Stock Bajo** | Indicador de estado en la lista de productos y Dashboard. (Color: Naranja) | Alerta visual de que un producto ha alcanzado su nivel mínimo y requiere atención. |
| **Agotado** | Indicador de estado en la lista de productos. (Color: Rojo) | Informa claramente que no hay unidades disponibles de un producto. |
| **Próximo a Vencer**| Etiqueta en reportes y Dashboard. (Color: Naranja/Rojo) | Alerta sobre productos cuya fecha de vencimiento está cerca, para prevenir pérdidas. |
| **Vencido** | Etiqueta en reportes y listas de lotes. (Color: Rojo Oscuro) | Indica que un lote de producto ya ha superado su fecha de vencimiento. |

**4. Etiquetas de Campos de Datos y Tablas**

Son los nombres de los campos en formularios y las cabeceras de las columnas en las tablas. La consistencia en estas etiquetas es crucial para que el usuario entienda qué información debe ingresar o qué dato está viendo.

| Etiqueta | Uso / Contexto | Propósito / Justificación |
| :--- | :--- | :--- |
| **Nombre del Producto** | Campo en formulario de creación/edición y cabecera de tabla. | Etiqueta clara y estándar para el nombre del ítem. |
| **SKU / Código** | Campo y cabecera de tabla. | Abarca tanto el SKU interno como el código de barras, usando términos comunes en el rubro. |
| **Stock Actual** | Cabecera de tabla y dato en el Dashboard. | Representa la cantidad de unidades disponibles en el momento. |
| **Stock Mínimo** | Campo en el formulario de producto. | Define el umbral para las alertas de "Stock Bajo". |
| **Fecha de Vencimiento** | Campo en el registro de entrada de lotes y cabecera de tabla. | Etiqueta inequívoca para el control de productos perecederos. |
| **Precio de Costo** | Campo en el formulario de producto y registro de entrada. | Claro y directo, se refiere al costo de adquisición. |
| **Precio de Venta**| Campo en el formulario de producto. | Claro y directo, se refiere al precio para el cliente final. |

Este sistema de etiquetado unificado asegura que la experiencia del usuario en StockTrack sea predecible, eficiente y libre de ambigüedades, cumpliendo con el objetivo de representar la información de la forma más simple posible.

### 4.2.3. SEO Tags and Meta Tags

En esta sección se definen los principales meta tags y etiquetas SEO que se implementarán en las páginas clave de la solución StockTrack. El objetivo es optimizar la visibilidad de nuestra plataforma en los motores de búsqueda (como Google) para atraer a nuestros segmentos objetivo, y asegurar que el contenido se presente de manera clara y relevante en los resultados de búsqueda.

A continuación, se especifican los valores para las etiquetas `Title`, `Description`, `Keywords` y `Author` para la Landing Page (sitio web estático) y la página principal de la Web Application (Dashboard).

**1. Landing Page (Sitio Web Estático)**

Esta es la página principal de cara al público, diseñada para atraer y convertir a nuevos usuarios. Las etiquetas están optimizadas con palabras clave relevantes para dueños de bodegas y emprendedores que buscan una solución de inventario.

* **Title Tag:**
    * `<title>StockTrack | Software de Inventario para Bodegas y Emprendedores</title>`
    * **Justificación:** Incluye el nombre de la marca ("StockTrack") y las palabras clave principales ("Software de Inventario", "Bodegas", "Pymes") para un posicionamiento claro y directo. Es conciso y descriptivo.

* **Meta Tag Description:**
    * `<meta name="description" content="Gestiona tu inventario sin errores ni pérdidas. StockTrack es el software fácil de usar para bodegas y emprendedores. Controla tu stock en tiempo real, recibe alertas y toma mejores decisiones. ¡Prueba gratis!">`
    * **Justificación:** Es un resumen persuasivo de la propuesta de valor. Incluye un llamado a la acción ("¡Prueba gratis!") y palabras clave relevantes para atraer clics desde los resultados de búsqueda.

* **Meta Tag Keywords:**
    * `<meta name="keywords" content="software de inventario, control de stock, gestión de inventario para pymes, inventario para bodegas, sistema de inventario, control de vencimientos, app para inventario, perú">`
    * **Justificación:** Contiene una lista de términos de búsqueda relevantes que nuestros segmentos objetivo (Carla y Andrés) podrían utilizar para encontrar una solución como StockTrack. Incluye términos de cola larga y geolocalización ("perú").

* **Meta Tag Author:**
    * `<meta name="author" content="Inventiapp">`
    * **Justificación:** Identifica a los creadores del contenido de la página.

**2. Web Application (Dashboard Principal)**

Esta es la página que ven los usuarios después de iniciar sesión. Aunque su indexación por parte de buscadores públicos no es una prioridad, es una buena práctica definir sus etiquetas para la claridad en el navegador y la gestión de marcadores.

* **Title Tag:**
    * `<title>Dashboard | StockTrack</title>`
    * **Justificación:** Ofrece una identificación clara de la página actual ("Dashboard") dentro de la aplicación ("StockTrack") en la pestaña del navegador, mejorando la usabilidad para el usuario.

* **Meta Tag Description:**
    * `<meta name="description" content="Panel de control de tu inventario. Visualiza tus alertas, niveles de stock y reportes clave en un solo lugar.">`
    * **Justificación:** Describe de manera concisa el propósito de la página para el usuario, aunque no esté destinada a SEO público.

* **Meta Tag Keywords:**
    * `<meta name="keywords" content="dashboard, inventario, control de stock, reportes, alertas">`
    * **Justificación:** Términos relevantes que describen el contenido de la página, principalmente para propósitos internos.

* **Meta Tag Author:**
    * `<meta name="author" content="Inventiapp">`
    * **Justificación:** Mantiene la consistencia en la autoría del contenido.

## 4.2.4 Searching Systems
En esta sección se describen los medios de ayuda que se proporcionarán al usuario para la búsqueda de datos dentro de la plataforma **StockTrack**. Estas decisiones sobre los sistemas de búsqueda están diseñadas para evitar que los usuarios se sientan perdidos entre el volumen de información y para permitirles encontrar lo que necesitan con rapidez y sin esfuerzo.

A continuación, se especifican las opciones de búsqueda que ofrecerá la aplicación, los filtros disponibles en cada caso y cómo se presentarán los datos después de la búsqueda.

**1. Sistema de Búsqueda del Catálogo de Productos**

Esta funcionalidad es central para la gestión diaria del inventario, permitiendo localizar productos específicos dentro del catálogo.

* **Opciones de Búsqueda:**
  - Barra de búsqueda principal y prominente en la parte superior de la vista del catálogo.
  - Búsqueda dinámica (autocompletado en tiempo real) en los siguientes campos:
    - Nombre del producto
    - SKU / Código de barras
    - Descripción corta

* **Filtros Disponibles:**
  - **Por Categoría:** menú desplegable (ej: *Bebidas*, *Lácteos*).
  - **Por Proveedor:** menú desplegable que muestra los productos asociados a un proveedor específico.
  - **Por Estado de Stock:** opciones predefinidas (*En stock, Stock bajo, Agotado*).

* **Presentación de Resultados:**
  - La cuadrícula/lista de productos se actualiza en tiempo real.
  - Contador de resultados (ej: *“Mostrando 25 de 150 productos”*).
  - Mensaje claro si no hay coincidencias (ej: *“No se encontraron productos. Intenta con otros términos.”*).

**2. Sistema de Búsqueda del Historial de Movimientos**

Permite auditar y encontrar transacciones específicas de inventario (entradas, salidas o ajustes).

* **Opciones de Búsqueda:**
  - Barra de búsqueda que acepta nombre del producto o SKU.

* **Filtros Disponibles:**
  - **Por Tipo de Movimiento:** selector (*Entradas, Salidas, Ajustes*).
  - **Por Rango de Fechas:** calendario con fecha de inicio y fin.
  - **Por Usuario (para planes multiusuario):** selector de responsables de la transacción.

* **Presentación de Resultados:**
  - Tabla cronológica con los movimientos filtrados.
  - Filtros activos visibles (ej: *“Mostrando: Entradas | Período: 01/08/2025 - 31/08/2025”*).

**3. Sistema de Búsqueda de Proveedores**

Facilita la localización de un proveedor específico dentro del directorio.

* **Opciones de Búsqueda:**
  - Barra de búsqueda simple que evalúa:
    - Nombre del proveedor
    - Nombre del contacto
    - RUC o identificador fiscal

* **Filtros Disponibles:**
  - Inicialmente, no se aplican filtros avanzados.
  - A futuro, posibilidad de **etiquetas personalizadas** (*Local, Importado*).

* **Presentación de Resultados:**
  - Lista en tiempo real a medida que se escribe.
  - Resultados en formato de tarjetas con información clave de cada proveedor.

**4. Sistema de Búsqueda de Lotes y Vencimientos**

Permite ubicar y controlar productos a nivel de lote.

* **Opciones de Búsqueda:**
  - Barra de búsqueda para número de lote o nombre de producto asociado.

* **Filtros Disponibles:**
  - **Por Fecha de Vencimiento:** selector con orden cronológico ascendente.
  - **Por Estado:** (*Vigente, Próximo a vencer, Vencido*).

* **Presentación de Resultados:**
  - Tabla con columnas de producto, lote, cantidad, fecha de vencimiento y estado.
  - Codificación por colores: verde (vigente), naranja (próximo a vencer), rojo (vencido).

**5. Sistemas de Búsqueda y Filtrado de Datos en Reportes**

Cada reporte individual dentro de la plataforma contará con un potente sistema de filtros para permitir al usuario analizar la información específica que necesita.

* **Filtros Disponibles en todos los Reportes:**
  - **Por Rango de Fechas:** Permite seleccionar períodos predefinidos (diario, semanal, mensual) o un rango personalizado.
  - **Por Categoría de Producto:** Focaliza el análisis en un grupo temático de productos.
  - **Por Proveedor:** Analiza el rendimiento o los movimientos de productos de un proveedor específico.

* **Presentación de Resultados:**
  - Los datos del reporte se actualizan dinámicamente al aplicar los filtros.
  - El panel visual muestra gráficos interactivos (barras, líneas, circulares) que reflejan la data filtrada.

### 4.2.5. Navigation Systems.

### 4.2.5. Navigation Systems

En esta sección, el equipo explica las acciones y técnicas que guiarán a los usuarios a través del Landing Page y la aplicación web de StockTrack. El objetivo de estos sistemas es permitirles a los usuarios cumplir sus metas e interactuar de forma satisfactoria con el producto, detallando las maneras en que podrán recorrer el contenido y las funcionalidades.

Para lograr una experiencia de usuario fluida e intuitiva, se han diseñado sistemas de navegación distintos pero coherentes para el sitio público (Landing Page) y la aplicación privada (post-login).

**1. Sistema de Navegación del Landing Page**

El sistema de navegación del sitio web estático está optimizado para la conversión. Su diseño es minimalista para mantener al usuario enfocado en la propuesta de valor y guiarlo hacia la acción principal: iniciar una prueba gratuita.

* **Navegación Principal (Global):**
    * **Técnica:** Una barra de navegación fija en la parte superior de la página (header).
    * **Acciones:** Contiene enlaces de anclaje que permiten al usuario desplazarse suavemente a las secciones clave de la misma página. Esto facilita la exploración del contenido sin salir de la vista principal.
    * **Etiquetas:** `Beneficios`, `Características`, `Planes`, `FAQ`.

* **Navegación de Cortesía (Botones de Acción):**
    * **Técnica:** Botones claramente diferenciados ubicados en la esquina superior derecha del header.
    * **Acciones:** Proporcionan los dos caminos principales para un usuario: `Iniciar Sesión` para usuarios existentes, y el Call-to-Action principal `[ Prueba Gratis ]` para nuevos visitantes. Su visibilidad constante asegura que la acción de conversión esté siempre al alcance.

**2. Sistema de Navegación de la Aplicación Web (Post-Login)**

Una vez que el usuario inicia sesión, el sistema de navegación cambia para centrarse en la eficiencia y la funcionalidad, permitiendo un acceso rápido a todas las herramientas de gestión de inventario.

* **Navegación Principal Persistente (Barra Lateral):**
    * **Técnica:** Una barra de navegación vertical y fija en el lado izquierdo de la pantalla.
    * **Acciones:** Muestra los enlaces a los módulos principales de la aplicación, correspondiendo a la estructura jerárquica del sistema: `Dashboard`, `Productos`, `Inventario`, `Proveedores`, `Reportes` y `Configuración`. Al ser persistente, el usuario siempre sabe dónde está y cómo acceder a otras secciones sin importar en qué parte de la aplicación se encuentre.

* **Navegación Secundaria (Local):**
    * **Técnica:** Pestañas (tabs) o un submenú que aparece debajo del título de una sección principal.
    * **Acciones:** Se utiliza para organizar funcionalidades dentro de un módulo complejo. Por ejemplo, en la sección de `Configuración`, el usuario verá pestañas para navegar entre `Perfil de Cuenta`, `Gestión de Alertas` y `Usuarios y Roles`, manteniendo la vista principal limpia y organizada.

* **Navegación Contextual:**
    * **Técnica:** Enlaces y botones integrados directamente en el contenido que el usuario está viendo.
    * **Acciones:** Este es el sistema que hace que la aplicación se sienta fluida e inteligente. Permite al usuario realizar acciones relevantes en el momento justo. Ejemplos:
        * **Enlaces en Tablas:** El nombre de cada producto en el catálogo será un enlace directo a su ficha de detalle.
        * **Alertas Interactivas:** Una alerta de "Stock Bajo" en el Dashboard será un enlace que llevará al usuario directamente al producto afectado para que pueda tomar una acción.
        * **Migas de Pan (Breadcrumbs):** Se mostrará una ruta de navegación en la parte superior de las vistas internas (ej: `Productos > Bebidas > Detalle de Producto`) para que el usuario siempre sepa su ubicación dentro de la jerarquía y pueda retroceder fácilmente.

* **Navegación de Cortesía (Menú de Usuario):**
    * **Técnica:** Un menú desplegable en la esquina superior derecha, activado al hacer clic en el nombre o avatar del usuario.
    * **Acciones:** Proporciona acceso a funciones relacionadas con la sesión del usuario, como `Mi Perfil` y la acción esencial de `Cerrar Sesión`.

## 4.3. Landing Page UI Design.
### 4.3.1. Landing Page Wireframe.
### 4.3.2. Landing Page Mock-up.  

## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.
### 4.4.2. Web Applications Wireflow Diagrams.
### 4.4.2. Web Applications Mock-ups.
### 4.4.3. Web Applications User Flow Diagrams.

## 4.5. Web Applications Prototyping.

## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Design-Level Event Storming.
### 4.6.2. Software Architecture Context Diagram.
![Context Diagram](./assets/Chapter-IV/structurizr-106230-SystemContext-001.png)

### 4.6.3. Software Architecture Container Diagrams.
![Container Diagram](./assets/Chapter-IV/structurizr-106230-Container-001.png)

### 4.6.4. Software Architecture Components Diagrams.
![Component Diagram](./assets/Chapter-IV/structurizr-106230-Component-001.png)

- Users and Permission Context
![Users and Permission Context Diagram](./assets/Chapter-IV/structurizr-106321-Component-004.png)

- Inventory Context
![Inventory Context Diagram](./assets/Chapter-IV/structurizr-106321-Component-001.png)

- Sales Context
![Sales Context Diagram](./assets/Chapter-IV/structurizr-106321-Component-002.png)

- Alerts and Reports Context
![Alerts and Reports Context Diagram](./assets/Chapter-IV/structurizr-106321-Component-003.png)

## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.

## 4.8. Database Design.
### 4.8.1. Database Diagrams

<br>
<br>

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.
### 5.1.2. Source Code Management.
### 5.1.3. Source Code Style Guide & Conventions.
### 5.1.4. Software Deployment Configuration.

## 5.2. Landing Page, Services & Applications Implementation.
### 5.2.X. Sprint n
#### 5.2.X.1. Sprint Planning n.
#### 5.2.X.2. Aspect Leaders and Collaborators.
#### 5.2.X.3. Sprint Backlog n.
#### 5.2.X.4. Development Evidence for Sprint Review.
#### 5.2.X.5. Execution Evidence for Sprint Review.
#### 5.2.X.6. Services Documentation Evidence for Sprint Review.
#### 5.2.X.7. Software Deployment Evidence for Sprint Review.
#### 5.2.X.8. Team Collaboration Insights during Sprint

## 5.3. Validation Interviews.
### 5.3.1. Diseño de Entrevistas.
### 5.3.2. Registro de Entrevistas.
### 5.3.3. Evaluaciones según heurísticas.

## 5.4. Video About-the-Product.

<br>
<br>

# Conclusiones
## Conclusiones y recomendaciones.
## Video About-the-Team.

# Conclusiones

## Conclusiones y recomendaciones


<br>
<br>

# Bibliografía


<br>
<br>

# Anexos

Link del Repositorio del Informe: https://github.com/Inventiapp/workstation-markdown <br>
Link del Repositorio del Proyecto: <br>
Link del Repositorio del Backend: <br>
