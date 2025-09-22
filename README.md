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

**Segmento #1: Bodegas especializadas por rubro**

| Nº | Datos del entrevistado | Resumen de la entrevista | Evidencia de entrevista |
|----|------------------------|------------------------------------------| ----------------------- |
| 1  | - **Nombre:** Lucarelly Sanchez Heredia <br> - **Edad:** 21 años | Lucarelly es dueño de una bodega y la gestiona junto a su abuelo. La administra usando excel pero no siempre está actualizado, además de usar una libreta. Uno de los mayores desafíos que enfrenta es la mezcla de lotes y fechas de vencimiento, lo que le genera pérdidas. No tiene un control en tiempo real del stock y no ha considerado usar una plataforma digital para gestionar su inventario, pero le gustaría tener un mejor control de sus productos. Actualmente no emplea alguna herramienta digital para la gestión de su bodega además de excel. Repone los productos de manera reactiva, es decir, cuando se le acaba o está por vencer un producto. Usa una laptop Windows y un celular Android, y como browser usa Chrome. Vende sus productos principalmente de forma presencial, pero también usa Whatsapp, Facebook e Instagram. | ![Entrevista 1 - Segmento Dueños de Bodegas](./assets/Chapter-II/lucas-interview.png) <br> **Duración:** 2:53 min |
| 2  | - **Nombre:** Rubi Vega <br> - **Edad:** 19 años | Actualmente, la bodega no cuenta con un sistema formal de gestión de inventario, pues al ser un negocio familiar las tareas se realizan de manera manual, aunque se considera contratar personal externo. El principal desafío es controlar las fechas de vencimiento, ya que con la llegada de nuevos productos se pierde seguimiento de los que están por caducar. No utilizan herramientas digitales, aunque reconocen la importancia de contar con un control en tiempo real para crecer y organizar pedidos. Detectan faltantes o vencimientos al limpiar estantes o por intuición. Usan celular y computadora, y gestionan pedidos principalmente por WhatsApp. | ![Entrevista 2 - Segmento Dueños de Bodegas](./assets/Chapter-II/Interview-Rubi.png) <br> **Duración:** 4:02 min |

**Segmento #2: Startups y emprendedores en expansión con necesidades logísticas**

| Nº | Datos del entrevistado | Resumen de la entrevista | Evidencia de entrevista |
|----|------------------------|------------------------------------------| ----------------------- |
| 1  | - **Nombre:** Alexander Miranda Vivanco <br> - **Edad:** 27 años | Alexander Miranda tiene un emprendimiento dedicado a venta de productos para mascotas. Actualmente, gestiona su inventario revisando su almacén presencialmente y lo hace interdiario, dependiendo de las ventas. Se siente limitado por lo tardado que es revisar el stock disponible. Registra su inventario únicamente en Excel y se guía por las boletas que emite. Le gustaría mejorar las entradas y salidas de productos e inventariado para así llevar un mejor control y saber cuando es necesario reponer ciertos ítems. Aún no ha considerado implementar una página, pero lo considera una oportunidad para digitalizar el negcio y agilizar el proceso de venta e inventario. | ![Entrevista 1 - Startups y emprendedores en expansión con necesidades logísticas](./assets/Chapter-II/Entrevista-Alexander-Miranda.png) <br> **Duración:** 3:30 min |

| Nº | Datos del entrevistado | Resumen de la entrevista | Evidencia de entrevista |
|----|------------------------|------------------------------------------| ----------------------- |
| 2  | - **Nombre:** Alicia Navarro Chang <br> - **Edad:** 20 años | Alicia Navarro Chang tiene un negocio dedicado a la venta de queques. Actualmente gestiona su inventario utilizando principalmente Notion y Excel, donde registra compras y salidas de productos, aunque reconoce que el proceso es propenso a errores humanos, especialmente en los cálculos y conteos manuales. Le gustaría contar con un sistema más automático que reduzca esas fallas. Ha evaluado implementar plataformas digitales de inventario, pero aún no encuentra una que le ofrezca todas las herramientas que necesita ni planes de suscripción adecuados. Sus productos los almacena en un cuarto de su casa y revisa los insumos interdiario o casi a diario. Para ventas y promoción emplea TikTok e Instagram, y para contacto con clientes utiliza Instagram y WhatsApp. Desarrolla su trabajo principalmente desde su laptop y también con su celular. | ![Entrevista 2 - Startups y emprendedores en expansión con necesidades logísticas](./assets/Chapter-II/entrevista-alicia-navarro.png) <br> **Duración:** 3:32 min |
<br>

| Nº | Datos del entrevistado | Resumen de la entrevista | Evidencia de entrevista |
|----|------------------------|------------------------------------------| ----------------------- |
| 3  | - **Nombre:** Macpier Condezo <br> - **Edad:** 29 años |Macpier Condezo tiene un negocio e-commerce. Actualmente gestiona su inventario utilizando principalmente Excel, donde registra compras y salidas de productos, aunque reconoce que el proceso es manual y puede presentar errores, especialmente en los cálculos y conteos manuales. Le gustaría contar con un sistema más automático que reduzca esas fallas. Ha evaluado implementar plataformas digitales de inventario, pero aún no encuentra una que le parezca adecuada. Sus productos los almacena en su casa y revisa el stock a diario. Para publicitarse y manejar las ventas en su negocio usa facebook. Desarrolla su trabajo principalmente desde su PC y ocacionalmente desde su celular. | ![Entrevista 3 - Startups y emprendedores en expansión con necesidades logísticas](./assets/Chapter-II/entrevista-macpier-condezo.png) <br> **Duración:** 3:41 min |
<br>

### 2.2.3. Análisis de entrevistas


En este apartado se documenta de manera estructurada cada una de las entrevistas realizadas a los diferentes segmentos objetivo. Para cada entrevista, se incluye información relevante como el perfil del entrevistado, el registro de sus respuestas, observaciones contextuales, y un resumen de los principales hallazgos obtenidos.

Esta sistematización permite asegurar la trazabilidad de los datos recolectados, facilitando su posterior análisis y su utilización en la construcción de artefactos de usuario, tales como User Personas, Empathy Maps y User Task Matrices.

Características objetivas y subjetivas más comunes de cada segmento:

| Segmento | Características Objetivas Comunes | Características Subjetivas Comunes |
|----------|-----------------------------------|------------------------------------| 
| Segmento 1: Dueños de bodegas | - Sexo: Femenino.<br>- Edad: 19-21 años.<br>- Gestión actual: Excel + libreta, no actualizados.<br>- Problema recurrente: mezcla de lotes, fechas de vencimiento descontroladas → pérdidas.<br>- No usan ninguna herramienta digital especializada.<br>- Reposición reactiva, cuando ya falta el producto.<br>- Usan WhatsApp y Facebook para clientes.<br>- Interés: plataforma simple, que no sea compleja como un ERP.| - Digitalizar inventario para dejar papel/Excel.<br>- Evitar pérdidas por vencimiento.<br>- Planificar reposiciones en vez de reaccionar tarde.|
| Segmento 2: Startups / Emprendedores | - Sexo: Masculino/Femenino.<br>- Edad: 20-29 años.<br>- Gestión actual: Excel, Notion, boletas.<br>- Problema recurrente: procesos manuales → errores en conteo y cálculos.<br>- Limitante: tardar mucho en revisar stock físicamente.<br>- Interés: automatización del inventario para reducir errores y ganar tiempo.<br>- Buscan: Escalabilidad y planes accesibles y flexibles.<br>- Usan redes sociales (TikTok, Instagram, Facebook) para ventas y marketing. | - Reducir errores humanos.<br> - Control en tiempo real del stock.<br>- Crecer sin necesidad de sistemas caros. |
<br>

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

<br> 


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
## 4.2. Information Architecture.
### 4.2.1. Organization Systems.
### 4.2.2. Labeling Systems.
### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems.
### 4.2.5. Navigation Systems.

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
### 4.6.3. Software Architecture Container Diagrams.
### 4.6.4. Software Architecture Components Diagrams.

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
