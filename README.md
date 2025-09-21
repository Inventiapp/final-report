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

<br>

<p align="center">
    <strong>Septiembre, 2025</strong>
</p>

<div style="page-break-after: always;"></div>

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

<div style="page-break-after: always;"></div>

# Project Report Collaboration Insights
Link del repositorio del reporte: https://github.com/Inventiapp/workstation-markdown <br>

<div style="page-break-after: always;"></div>

# Contenido
- [Project Report](#project-report)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
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
  - [2.4. Big Picture Event Storming.](#24-big-picture-event-storming)
  - [2.5. Ubiquitous Language.](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. User Stories](#31-user-stories)
    - [User Stories](#user-stories)
    - [Epics](#epics)
    - [Technical stories](#technical-stories)
  - [3.2. Impact Mapping](#32-impact-mapping)
  - [3.3. Product Backlog](#33-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines.](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
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
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1.](#5211-sprint-planning-1)
      - [5.2.1.2. Aspect Leaders and Collaborators.](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog 1.](#5213-sprint-backlog-1)
      - [5.2.1.4. Development Evidence for Sprint Review.](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review.](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review.](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review.](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

<div style="page-break-after: always;"></div>

# Student Outcome

<div style="page-break-after: always;"></div>

# Capítulo I: Presentación

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

StockTrack es una aplicación innovadora que busca optimizar la gestión de inventarios en bodegas y almacenes, brindando a los negocios una herramienta sencilla, confiable y en tiempo real para controlar el ingreso y salida de productos. La plataforma permite registrar movimientos de stock de manera automatizada, generar alertas inteligentes en caso de niveles bajos o próximos vencimientos, visualizar la información centralizada de cada producto y acceder a reportes con analíticas que facilitan la toma de decisiones estratégicas. Con ello, StockTrack elimina la dependencia de procesos manuales, reduce errores humanos, evita pérdidas por sobrestock o desabastecimiento y mejora la eficiencia operativa, impulsando así la rentabilidad y el crecimiento de las empresas.

### 1.1.2. Perfiles de integrantes del equipo

<table align="center" border="1" cellspacing="0" cellpadding="8" style="page-break-inside: avoid; width: 90%; border-collapse: collapse;">
  <tr>
    <td style="width: 150px; text-align: center;">
      <img src="assets/Chapter-I/FotoChoy.jpeg" alt="Foto de Vanessa Choy" width="500" height="500" style="object-fit: cover;">
    </td>
      <td>
          <p align="center"><strong>Vanessa May Lang Choy Robles - U202317450</strong></p>
          <p align="justify">
            Soy una estudiante responsable con el trabajo. Respeto y escucho la opinión de los demás ayudando al trabajo en equipo. Me comprometo a contribuir al equipo siendo puntual en las reuniones y responsable en las entregas.
          </p>
    </td>
  </tr>
</table>
<br>
<table align="center" border="1" cellspacing="0" cellpadding="8" style="page-break-inside: avoid; width: 90%; border-collapse: collapse;">
  <tr>
    <td style="width: 150px; text-align: center;">
      <img src="" alt="Foto de María Hernández" width="160" height="160" style="object-fit: cover;">
    </td>
      <td>
          <p align="center"><strong>María Patricia Hernández Uchuya - U202311258</strong></p>
          <p align="justify">
            Estudio la carrera de Ingeniería de Software, tengo 19 años y actualmente me encuentro cursando el sexto ciclo de dicha carrera. Tengo conocimientos en C++, C#, Python, Java, HTML, CSS, JavaScript y Vue. Me considero una persona con responsabilidad, optimismo y honestidad, cualidades que considero fundamentales para una colaboración efectiva en equipo y un buen desarrollo en este proyecto.
          </p>
    </td>
  </tr>
</table>
<br>
<table align="center" border="1" cellspacing="0" cellpadding="8" style="page-break-inside: avoid; width: 90%; border-collapse: collapse;">
  <tr>
    <td style="width: 150px; text-align: center;">
      <img src="assets/Chapter-I/dayro.jpg" alt="Foto de Dayro Rios" width="700" height="700" style="object-fit: cover;">
    </td>
      <td>
          <p align="center"><strong>Dayro Richard Rios Piñan - U202315283</strong></p>
          <p align="justify">
            Mi nombre es Dayro Ríos, tengo 19 años, estoy cursando el sexto ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Tengo conocimientos en los lenguajes de programación c++, python, html y css, además gestores de base de datos como mssql. Cuando trabajo en equipo soy comunicativo, responsable y trato de realizar el trabajo lo mejor posible. 
          </p>
    </td>
  </tr>
</table>
<br>
<table align="center" border="1" cellspacing="0" cellpadding="8" style="page-break-inside: avoid; width: 90%; border-collapse: collapse;">
  <tr>
    <td style="width: 150px; text-align: center;">
      <img src="" alt="Foto de Fabiola Saldaña" width="160" height="160" style="object-fit: cover;">
    </td>
      <td>
          <p align="center"><strong>Fabiola Del Rocio Saldaña Ayala - U202313773</strong></p>
          <p align="justify">
            Mi nombre es Fabiola Saldaña, tengo 19 años y actualmente curso el 6to ciclo de la carrera de Ingeniería de Software. En lo personal busco aprender constantemente y me considero alguien responsable, proactiva y dedicada con mis trabajos. Es por ello que me comprometo apoyar al equipo con mis habilidades y conocimientos para alcanzar los mejores resultados.
          </p>
    </td>
  </tr>
</table>
<br>
<table align="center" border="1" cellspacing="0" cellpadding="8" style="page-break-inside: avoid; width: 90%; border-collapse: collapse;">
  <tr>
    <td style="width: 150px; text-align: center;">
      <img src="assets/Chapter-I/profile-piero.png" alt="Foto de Piero Sulca" width="750" height="750" style="object-fit: cover;">
    </td>
      <td>
          <p align="center"><strong>Piero Angel Sulca Sanchez - U202423711</strong></p>
          <p align="justify">
             Curso la carrera de Ingeniería de Software y tengo experiencia en desarrollo web, trabajando con equipos pequeños. Me gusta el Front End, en especial el diseño de interfaces 3D y productos creativos. Tengo conocimientos que pueden ayudar al equipo como levantamiento de requerimientos, diseño de interfaces, desarrollo web (React, Typescript), diseño de bases de datos y las habilidades de organización y colaboración en equipos pequeños.
          </p>
    </td>
  </tr>
</table>
<br>

## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática

**What (Qué)**

- ¿Cuál es el problema?<br>
El problema principal es la falta de control en los inventarios de bodegas y almacenes, lo que genera pérdidas por vencimiento de productos, errores en el registro manual de entradas y salidas, y retrasos en la reposición de stock. Muchas empresas aún dependen de hojas de cálculo o procesos manuales que no reflejan la situación en tiempo real.

- ¿Cuál es la relación con la persona en cuestión?<br>
El problema afecta directamente a dueños de negocios, administradores de almacenes y encargados de logística, quienes necesitan herramientas confiables para evitar quiebres de stock o sobreacumulación. StockTrack se convierte en un aliado para optimizar su gestión y reducir riesgos.

**When (Cuándo)**

- ¿Cuándo sucede el problema?<br>
El problema ocurre en el momento en que se registran entradas o salidas de productos y no hay un sistema automatizado que actualice la información en tiempo real. Esto puede darse diariamente, con cada movimiento de mercadería.

- ¿Cuándo utiliza el cliente el producto?<br>
El cliente utiliza StockTrack en todo momento que gestiona inventario, al recibir un nuevo lote, al realizar ventas o despachos, al planificar compras, e incluso al revisar reportes para la toma de decisiones estratégicas.

**Where (dónde)**

- ¿Dónde está el cliente cuando usa el producto?<br>
El cliente generalmente se encuentra dentro de la bodega o almacén, donde se realizan los movimientos físicos de los productos, o en su oficina, desde donde consulta los reportes y analíticas.

- ¿A dónde se dirige?<br>
El cliente se dirige a digitalizar sus procesos y a tener un mayor control de su inventario con datos confiables y centralizados, accesibles en cualquier momento y lugar.

- ¿Dónde surge el problema?<br>
El problema surge en los puntos críticos del control de inventario, tales como la falta de trazabilidad en los registros manuales, la ausencia de alertas automáticas y la desconexión entre la gestión operativa y la planificación estratégica.

**Who (quién)**

- ¿Quiénes están involucrados?<br>
Están involucrados dueños de negocios, jefes de almacén, encargados de logística y el personal que manipula y registra el stock en la bodega.

- ¿A quiénes le sucede el problema?<br>
El problema le sucede tanto a pequeños y medianos empresarios como a grandes almacenes que carecen de un sistema confiable para controlar su inventario en tiempo real.

- ¿Quién lo utilizará?<br>
El sistema será utilizado principalmente por administradores de almacén y personal operativo, pero también beneficiará a los gerentes y dueños, quienes tendrán acceso a reportes y analíticas centralizadas.

**Why (por qué)**

- ¿Cuál es la causa del problema?<br>
La causa principal es la dependencia de procesos manuales o de sistemas desactualizados que no permiten el registro automatizado ni generan alertas preventivas. Esto provoca errores humanos, retrasos en la reposición, y pérdidas por vencimientos o robos no detectados a tiempo.

**How (cómo)**
- ¿En qué condiciones los clientes usan nuestro producto?<br>
Los clientes usan StockTrack en un entorno de trabajo dinámico y operativo, donde es necesario registrar movimientos de stock de manera rápida y sencilla. Lo utilizan desde dispositivos móviles o computadoras para que la información se actualice en tiempo real.

- ¿Cómo nos conocieron los compradores?<br>
Los compradores conocen StockTrack a través de recomendaciones de otros negocios, redes sociales y campañas digitales enfocadas en la optimización de procesos logísticos. También por demostraciones en ferias o eventos de tecnología empresarial.

- ¿Cómo prefieren los lectores acceder a nuestro contenido?<br>
Los clientes prefieren acceder al sistema mediante una aplicación web intuitiva y fácil de usar, complementada con alertas inteligentes vía correo electrónico o notificaciones móviles.

- ¿Qué llevó a la persona a llegar a esta situación?<br>
La persona llegó a esta situación por la necesidad de controlar mejor su inventario, evitar pérdidas económicas y tener mayor seguridad y confiabilidad en la gestión de sus productos.

**How much (cuánto)**

Según un estudio realizado por GS1 Uruguay (2024), el porcentaje de productos no encontrados en góndolas alcanzó el 7.08 %, lo que representa un aumento del 74 % respecto al año anterior; este dato indica que por cada 100 productos auditados, 7 no estaban disponibles, evidenciando el impacto directo que una gestión ineficiente de inventarios puede tener en la disponibilidad, las ventas y la experiencia del cliente.

![Evolución del Índice](./assets/Chapter-I/Evolucion-del-Indice.png)

### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements

Nuestro servicio ofrece a las bodegas y almacenes una plataforma innovadora para gestionar inventarios en tiempo real, permitiendo registrar movimientos de stock, generar alertas inteligentes, centralizar información de productos y acceder a reportes analíticos que apoyan la toma de decisiones estratégicas.

Hemos observado un factor crítico que afecta la eficiencia de los negocios y esto radica en que actualmente muchas empresas siguen utilizando procesos manuales, como hojas de cálculo o registros en papel para controlar su inventario. Esto provoca errores humanos frecuentes, falta de visibilidad en tiempo real, pérdidas por sobrestock o desabastecimiento y retrasos en la identificación de productos próximos a vencerse.

¿Cómo lograr que las bodegas y almacenes adopten un sistema que automatice el control de inventario, reduzca errores humanos y mejore la eficiencia operativa sin necesidad de procesos manuales que limiten el crecimiento del negocio?

#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions**

- Creo que mis clientes necesitan una forma confiable, rápida y automatizada de controlar su inventario en tiempo real para reducir errores y pérdidas económicas.
- Estas necesidades se pueden resolver con una aplicación que registre entradas y salidas de productos, genere alertas inteligentes y centralice la información en un solo panel.
- Mis clientes iniciales serán pequeñas y medianas empresas con bodegas y almacenes que actualmente usan procesos manuales (Excel, papel, o registros básicos) para su inventario.
- El valor #1 que un cliente quiere de mi servicio es evitar pérdidas y desabastecimientos a través de un control de inventario preciso y en tiempo real.
- El cliente también puede obtener los beneficios de reducción de errores humanos, ahorro de tiempo, mejor planificación de compras y reportes analíticos para decisiones estratégicas.
- Voy a adquirir la mayoría de mis clientes a través de estrategias de marketing digital, en redes sociales y/o Google Ads, asociaciones con cámaras de comercio y ventas directas B2B.
- Haré dinero a través de suscripciones mensuales o anuales, con planes escalables según el número de productos o almacenes que gestione cada cliente.
- Mi competencia principal en el mercado será otros sistemas de gestión de inventarios o soluciones locales personalizadas.
- Los venceremos debido a una interfaz más intuitiva, precios accesibles, configuración sencilla y un enfoque especializado en pymes que no pueden costear sistemas complejos.
- Mi mayor riesgo de producto es que los clientes perciban el sistema como complejo o no lo adopten porque prefieren seguir con sus métodos manuales.
- Resolveremos esto a través de una experiencia de usuario simple, capacitación inicial y soporte al cliente accesible para facilitar la adopción.

**User Assumptions**

- ¿Quién es el usuario?
Encargados de almacén, emprendedores, administradores de bodegas y dueños de pequeños negocios.

- ¿Dónde encaja nuestro producto en su trabajo o vida?
En las operaciones diarias de registro de entradas y salidas de productos, control de stock y planificación de compras.

- ¿Qué problemas tiene nuestro producto que resolver?
Errores en registros manuales, pérdida de productos por vencimiento o sobrestock, falta de información en tiempo real y dificultad para generar reportes claros.

- ¿Cuándo y cómo es nuestro producto usado?
Se usa todos los días, durante la recepción y despacho de productos, así como en reuniones de planificación donde se revisan reportes y métricas.

- ¿Qué características son importantes?
Registro rápido de productos, alertas personalizables, reportes visuales, acceso desde cualquier dispositivo y seguridad en los datos.

- ¿Cómo debe verse nuestro producto y cómo comportarse?
Debe ser intuitivo, minimalista y responsivo, fácil de aprender sin necesidad de manuales extensos, y comportarse de forma rápida, confiable y sin errores.

**Feature Assumptions**

- Creemos que la aplicación debe contar con una interfaz de usuario intuitiva y responsiva que permitirá a los encargados de almacén, emprendedores y administradores adoptarla sin dificultad, reduciendo la curva de aprendizaje.
- Creemos que la plataforma debe proporcionar notificaciones y alertas personalizables tales como stock bajo o fechas próximas de vencimiento, que mantendrán a los usuarios informados para evitar errores logísticos y quiebres de stock.
- Creemos que el sistema debe ser accesible desde la web y dispositivos móviles para asegurar disponibilidad en todo momento.
- Creemos que la seguridad en los datos es clave para generar confianza en los usuarios.

#### 1.2.2.3. Lean UX Hypothesis Statements

Creemos que implementar alertas personalizables sobre niveles bajos de stock y fechas próximas de vencimiento reducirá las pérdidas por quiebre o vencimiento de productos.<br>
Sabremos que hemos tenido éxito<br>
Cuando observemos al menos un 30% de reducción en productos vencidos o faltantes en comparación con los registros previos al uso de alertas.

Creemos que los usuarios valorarán la disponibilidad de reportes gráficos que muestren los productos más rotados, niveles de stock y tendencias de consumo.<br>
Sabremos que hemos tenido éxito<br>
Cuando al menos un 70% de los usuarios activos usen el módulo de reportes semanalmente y reporten satisfacción positiva en encuestas cualitativas.

Creemos que una interfaz intuitiva y fácil de aprender aumentará la adopción por parte de usuarios que dependen de Excel o registros manuales.<br>
Sabremos que hemos tenido éxito<br>
Cuando al menos el 60% de los nuevos clientes registren sus primeros productos dentro de las 24 horas posteriores a la activación de su cuenta.

Creemos que habilitar el acceso a la aplicación tanto desde la web como desde dispositivos móviles aumentará la frecuencia de uso.<br>
Sabremos que hemos tenido éxito<br>
Cuando el 50% de los usuarios accedan a la plataforma al menos una vez al día desde distintos dispositivos.

#### 1.2.2.4. Lean UX Canvas

![Lean UX Canvas](./assets/Chapter-I/Lean-UX-Canvas.jpg)

## 1.3. Segmentos objetivo

Esta sección expone los segmentos vinculados al contexto del problema, integrando características demográficas y datos estadísticos que respaldan el análisis. En este sentido, y con el propósito de desarrollar un producto que se ajuste de manera efectiva a las necesidades de los clientes, **StockTrack** enfocará sus esfuerzos en los siguientes segmentos de la población.

**1. Dueños de bodegas:** Estos usuarios tienen como puesto de trabajo su bodega. Ellos buscan una solución práctica que los ayude a realizar la logística de manera más eficiente y sin errores

- Edad: 20 a 60 años
- Ocupación: Dueños de bodegas.
- País: Perú.
- Dominio: Nivel intermedio o básico en tecnología, pero familiarizados con apps móviles.
- Beneficios buscados:
    - Rápidez de cálculos logísticos.
    - Orden y administración sencilla de los productos.

**2. Startups y emprendedores en expansión con necesidades logísticas:** Estos usuarios se encuentran en una etapa de crecimiento de su negocio y requieren herramientas que les permitan profesionalizar la gestión de sus operaciones. Buscan soluciones accesibles y escalables que faciliten el control del inventario sin necesidad de invertir en sistemas costosos o complejos.

- Edad: 22 a 45 años
- Ocupación: Fundadores de startups, emprendedores y  pequeños empresarios.
- País: Perú (con potencial de expansión a otros países de Latinoamérica).
- Dominio: Nivel intermedio en el uso de herramientas digitales y aplicaciones móviles.
- Beneficios buscados:
    - Escalabilidad en el control del inventario.
    - Reducción de costos y optimización de recursos.
    - Mayor visibilidad y control en tiempo real sobre el stock.
    - Herramientas que acompañen el crecimiento del negocio sin requerir infraestructura adicional.
  
<div style="page-break-after: always;"></div>

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores
### 2.1.1. Análisis competitivo

<p align="center">
  <img src="assets/Chapter-II/analisisCompetitivo.jpg" alt="Análisis Competitivo" width="550">
</p>

### 2.1.2. Estrategias y tácticas frente a competidores

**Estrategias**
  
<p align="justify">
    1. Diferenciación por simplicidad y usabilidad: La solución estará enfocada en bodegas y pequeñas empresas que requieren una interfaz intuitiva y un flujo de trabajo sencillo, reduciendo la curva de aprendizaje.
</p>
<p align="justify">
    2. Accesibilidad económica: La startup ofrecerá planes escalables y accesibles, con opción gratis básica para atraer usuarios y fomentar adopción masiva.
</p>
<p align="justify">
    3. Adaptación al mercado local: Integración directa con la facturación electrónica exigida por SUNAT en Perú y soporte en español, lo cual representa una ventaja frente a soluciones globales.    
</p>
<p align="justify">    
    4. Posicionamiento digital: Focalización en marketing digital dirigido a bodegueros y pymes mediante redes sociales, asociaciones de comerciantes y programas de referidos.
</p>

**Tácticas**
  
<p align="justify">
    1. Frente a las fortalezas de competidores: Ofrecer un onboarding rápido y gratuito que simplifique la transición a nuestro sistema. Mantener integraciones básicas con e-commerce.
</p>
<p align="justify">
    2. Frente a las debilidades de competidores: Simplificar los módulos de inventario para usuarios no técnicos. Ofrecer precios más bajos y planes sin contratos largos. Incorporar soporte técnico personalizado en español.
</p>
<p align="justify">
    3. Aprovechando oportunidades del mercado: Posicionarse como solución para la digitalización de bodegas y pequeños negocios. Diseñar versiones móviles ligeras, dado que muchos bodegueros usan smartphones como principal herramienta de gestión.
</p>
<p align="justify">
    4. Mitigando amenazas: Diferenciarse de grandes empresas destacando el enfoque local. Crear una comunidad de usuarios locales que genere lealtad frente a la entrada de nuevos competidores. Innovar constantemente incorporando módulos escalables.
</p>

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

## 2.4. Big Picture Event Storming.
## 2.5. Ubiquitous Language.

<div style="page-break-after: always;"></div>

# Capítulo III: Requirements Specification

## 3.1. User Stories


### User Stories
<!-- User Stories – Salida de producto / Venta (inventario + ganancia) -->
<!-- User Stories – Salida de productos (inventario + ganancia, con kits) -->
<table border="1" cellspacing="0" cellpadding="8" style="border-collapse:collapse; width:100%;">
  <thead>
    <tr>
      <th style="width:8%;">Story ID</th>
      <th style="width:18%;">Título</th>
      <th style="width:24%;">Descripción técnica</th>
      <th style="width:40%;">Criterios de Aceptación</th>
      <th style="width:10%;">Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US01</td>
      <td>Iniciar borrador de salida</td>
      <td>Como cajero, quiero iniciar un borrador de salida para agrupar ítems de una venta antes de confirmarla.</td>
      <td>
        <strong>Escenario 01: Borrador creado</strong><br>
        <strong>Dado</strong> que el usuario está en “Nueva venta”,<br>
        <strong>Cuando</strong> selecciona “Iniciar borrador”,<br>
        <strong>Entonces</strong> el sistema crea un borrador con ID único, estado <em>Draft</em> y fecha de inicio.<br><br>
        <strong>Escenario 02: Reanudación</strong><br>
        <strong>Dado</strong> un borrador en estado <em>Draft</em>,<br>
        <strong>Cuando</strong> el usuario lo reanuda,<br>
        <strong>Entonces</strong> el sistema muestra ítems, cantidades y totales parciales guardados.
      </td>
      <td>EP-04</td>
    </tr>
    <tr>
      <td>US02</td>
      <td>Gestionar ítems del borrador</td>
      <td>Como cajero, quiero buscar productos y agregar/editar/retirar ítems con cantidades válidas sin impactar el stock aún.</td>
      <td>
        <strong>Escenario 01: Agregar ítem</strong><br>
        <strong>Dado</strong> un borrador activo,<br>
        <strong>Cuando</strong> agrego un producto con cantidad &gt; 0,<br>
        <strong>Entonces</strong> el ítem se añade/actualiza (agrupado por producto/lote) y se recalculan subtotales.<br><br>
        <strong>Escenario 02: Editar cantidad</strong><br>
        <strong>Dado</strong> un ítem en el borrador,<br>
        <strong>Cuando</strong> cambio la cantidad a un valor válido (&gt; 0),<br>
        <strong>Entonces</strong> el sistema actualiza el ítem y muestra el nuevo subtotal.<br><br>
        <strong>Escenario 03: Retirar ítem</strong><br>
        <strong>Dado</strong> un ítem en el borrador,<br>
        <strong>Cuando</strong> lo retiro,<br>
        <strong>Entonces</strong> el ítem desaparece del borrador y se recalculan totales.
      </td>
      <td>EP-04</td>
    </tr>
    <tr>
      <td>US03</td>
      <td>Calcular total y utilidad de la salida</td>
      <td>Como dueño, quiero que el sistema calcule en tiempo real el total y la utilidad por ítem/kit y global, usando el costo vigente.</td>
      <td>
        <strong>Escenario 01: Utilidad por ítem</strong><br>
        <strong>Dado</strong> un ítem con precio y costo vigente,<br>
        <strong>Cuando</strong> se recalcula el total,<br>
        <strong>Entonces</strong> se registra <em>utilidad_item = (precio - costo) × cantidad</em> y margen %.<br><br>
        <strong>Escenario 02: Utilidad de la salida</strong><br>
        <strong>Dado</strong> varios ítems (y/o kits),<br>
        <strong>Cuando</strong> se recalcula el total,<br>
        <strong>Entonces</strong> el sistema calcula <em>utilidad_total = Σ utilidad_item</em> y la muestra en el encabezado.<br><br>
        <strong>Escenario 03: Política de costo</strong><br>
        <strong>Dado</strong> una política de costo (p. ej., promedio ponderado o por lote),<br>
        <strong>Cuando</strong> se obtiene el costo,<br>
        <strong>Entonces</strong> el cálculo usa la política activa y deja traza de cuál costo se aplicó.
      </td>
      <td>EP-04</td>
    </tr>
    <tr>
      <td>US04</td>
      <td>Confirmar salida y descontar inventario</td>
      <td>Como cajero, quiero confirmar la salida para registrar los movimientos de inventario (productos y componentes de kits) y actualizar el on-hand.</td>
      <td>
        <strong>Escenario 01: Confirmación exitosa</strong><br>
        <strong>Dado</strong> un borrador válido,<br>
        <strong>Cuando</strong> confirmo la salida,<br>
        <strong>Entonces</strong> el sistema crea movimientos por ítem (y por componente de kit), decrementa <em>on-hand</em>, guarda <em>saldo_post</em> y cambia el estado a <em>Confirmed</em>.<br><br>
        <strong>Escenario 02: Bloqueo por stock insuficiente</strong><br>
        <strong>Dado</strong> que hay ítems/componentes sin stock suficiente y el stock negativo está desactivado,<br>
        <strong>Cuando</strong> intento confirmar,<br>
        <strong>Entonces</strong> el sistema bloquea la acción y lista los faltantes.<br><br>
        <strong>Escenario 03: Disparo de alertas</strong><br>
        <strong>Dado</strong> que se confirma la salida,<br>
        <strong>Cuando</strong> algún producto queda por debajo del umbral,<br>
        <strong>Entonces</strong> el sistema genera la alerta de bajo stock (y la deja disponible para notificación externa).
      </td>
      <td>EP-04</td>
  </tbody>
</table>  
    </tr>
<table border="1" cellspacing="0" cellpadding="8" style="border-collapse:collapse; width:100%;">
  <thead>
    <tr>
      <th style="width:8%;">Story ID</th>
      <th style="width:18%;">Título</th>
      <th style="width:24%;">Descripción técnica</th>
      <th style="width:40%;">Criterios de Aceptación</th>
      <th style="width:10%;">Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US05</td>
      <td>Reporte de stock a fecha (valorizado)</td>
      <td>
        Como gerente, quiero emitir un reporte de stock a una fecha de corte, con cantidades on-hand, costo vigente y valorizado por producto/lote.
      </td>
      <td>
        <strong>Escenario 01: Corte por fecha</strong><br>
        <strong>Dado</strong> una fecha de corte seleccionada,<br>
        <strong>Cuando</strong> genero el reporte,<br>
        <strong>Entonces</strong> se muestran columnas: producto, lote (si aplica), UM, on_hand, costo_vigente, <em>valorizado = on_hand × costo_vigente</em>.<br><br>
        <strong>Escenario 02: Filtros</strong><br>
        <strong>Dado</strong> filtros por categoría, producto y con/sin lotes,<br>
        <strong>Cuando</strong> aplico los filtros,<br>
        <strong>Entonces</strong> el reporte refleja solo los ítems coincidentes.<br><br>
        <strong>Escenario 03: Export</strong><br>
        <strong>Dado</strong> un reporte en pantalla,<br>
        <strong>Cuando</strong> elijo “Exportar”,<br>
        <strong>Entonces</strong> puedo descargar CSV y PDF con el mismo contenido y metadatos (fecha de corte, filtros).
      </td>
      <td>EP-07</td>
    </tr>
    <tr>
      <td>US06</td>
      <td>Reporte de rotación y ventas (utilidad)</td>
      <td>
        Como gerente, quiero un reporte por periodo con unidades vendidas, ingreso, costo y utilidad por producto/categoría, para identificar top/slow movers.
      </td>
      <td>
        <strong>Escenario 01: Cálculo por periodo</strong><br>
        <strong>Dado</strong> un rango de fechas,<br>
        <strong>Cuando</strong> genero el reporte,<br>
        <strong>Entonces</strong> se calculan por producto: unidades_vendidas, <em>ingreso = Σ (precio × cantidad)</em>, <em>costo = Σ (costo_aplicado × cantidad)</em>, <em>utilidad = ingreso − costo</em>, margen% = utilidad/ingreso.<br><br>
        <strong>Escenario 02: Orden y agrupación</strong><br>
        <strong>Dado</strong> opciones de ordenar por unidades/ingreso/utilidad,<br>
        <strong>Cuando</strong> selecciono el criterio,<br>
        <strong>Entonces</strong> el listado se ordena y permite agrupar por categoría.<br><br>
        <strong>Escenario 03: Kits</strong><br>
        <strong>Dado</strong> ventas con kits,<br>
        <strong>Cuando</strong> genero el reporte,<br>
        <strong>Entonces</strong> puedo ver el kit como línea y (opcional) desglosar a componentes; la utilidad considera la suma de costos de componentes.<br><br>
        <strong>Escenario 04: Export</strong><br>
        <strong>Dado</strong> el reporte en pantalla,<br>
        <strong>Cuando</strong> exporto,<br>
        <strong>Entonces</strong> obtengo CSV/PDF con encabezado de parámetros (rango, agrupación).
      </td>
      <td>EP-07</td>
    </tr>
    <tr>
      <td>US07</td>
      <td>Reporte de mermas y ajustes</td>
      <td>
        Como dueño, quiero un reporte de ajustes (±) y mermas por periodo, con motivo, usuario y valorizado, para auditar pérdidas.
      </td>
      <td>
        <strong>Escenario 01: Detalle de movimientos</strong><br>
        <strong>Dado</strong> un rango de fechas,<br>
        <strong>Cuando</strong> genero el reporte,<br>
        <strong>Entonces</strong> se listan: fecha, producto/lote, cantidad (±), motivo, usuario, <em>valor = |cantidad| × costo_aplicado</em>.<br><br>
        <strong>Escenario 02: Totales</strong><br>
        <strong>Dado</strong> el reporte en pantalla,<br>
        <strong>Cuando</strong> visualizo el resumen,<br>
        <strong>Entonces</strong> veo totales por motivo (merma, corrección, conteo) y total general valorizado.<br><br>
        <strong>Escenario 03: Evidencia</strong><br>
        <strong>Dado</strong> ajustes con evidencia (nota/foto),<br>
        <strong>Cuando</strong> consulto el detalle,<br>
        <strong>Entonces</strong> puedo abrir el enlace/adjunto de la evidencia.<br><br>
        <strong>Escenario 04: Export</strong><br>
        <strong>Dado</strong> el reporte,<br>
        <strong>Cuando</strong> exporto,<br>
        <strong>Entonces</strong> descargo CSV/PDF con detalle y totales.
      </td>
      <td>EP-07</td>
    </tr>
    <tr>
      <td>US08</td>
      <td>Reporte de bajo stock y próximos a vencer</td>
      <td>
        Como jefe de compras, quiero un listado de productos bajo umbral y lotes próximos a vencer, con días de cobertura y acciones sugeridas.
      </td>
      <td>
        <strong>Escenario 01: Bajo stock</strong><br>
        <strong>Dado</strong> los umbrales por producto,<br>
        <strong>Cuando</strong> genero el reporte,<br>
        <strong>Entonces</strong> se listan productos con on_hand &lt; umbral y se calcula <em>días_cobertura = on_hand / consumo_promedio_diario</em> (si hay historial).<br><br>
        <strong>Escenario 02: Próximos a vencer</strong><br>
        <strong>Dado</strong> una ventana de X días,<br>
        <strong>Cuando</strong> genero el reporte,<br>
        <strong>Entonces</strong> se listan lotes con vencimiento dentro de la ventana con cantidad y fecha.<br><br>
        <strong>Escenario 03: Acciones</strong><br>
        <strong>Dado</strong> el reporte en pantalla,<br>
        <strong>Cuando</strong> selecciono un ítem,<br>
        <strong>Entonces</strong> puedo abrir atajos a “Registrar ingreso”, “Iniciar salida” o “Ajuste/merma” (según corresponda).<br><br>
        <strong>Escenario 04: Export</strong><br>
        <strong>Dado</strong> el reporte,<br>
        <strong>Cuando</strong> exporto,<br>
        <strong>Entonces</strong> descargo CSV/PDF (y opcional envío a Google Sheets).
      </td>
      <td>EP-07</td>
    </tr>
  </tbody>
</table>


<!-- Catálogo de Productos -->
<table border="1" cellspacing="0" cellpadding="8" style="border-collapse:collapse; width:100%;">
  <thead>
    <tr>
      <th style="width:8%;">Story ID</th>
      <th style="width:18%;">Título</th>
      <th style="width:24%;">Descripción técnica</th>
      <th style="width:40%;">Criterios de Aceptación</th>
      <th style="width:10%;">Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US12</td>
      <td>Crear producto en catálogo</td>
      <td>Como jefe de compras quiero registrar un nuevo producto para asegurar una gestion productos consistente</td>
      <td>
        <strong>Escenario 01: Registro exitoso</strong><br>
        <strong>Dado</strong> que ingreso un producto con todos los campos obligatorios,<br>
        <strong>Cuando</strong> confirmo el registro,<br>
        <strong>Entonces</strong> el sistema guarda el producto y lo hace disponible en el catálogo.<br><br>
        <strong>Escenario 02: Producto duplicado</strong><br>
        <strong>Dado</strong>que ya existe un producto con el mismo nombre y categoría, <em>Draft</em>,<br>
        <strong>Cuando</strong> intento registrarlo,<br>
        <strong>Entonces</strong> el sistema bloquea el registro y muestra un mensaje de duplicado.
      </td>
      <td>EP-01</td>
    </tr>
    <tr>
      <td>US13</td>
      <td>Edición de producto</td>
      <td>Como jefe de compras quiero editar los datos de un producto existente para mantener actualizada la información en el catálogo</td>
      <td>
        <strong>Escenario 01: Edición exitosa</strong><br>
        <strong>Dado</strong> que selecciono un producto existente,<br>
        <strong>Cuando</strong> edito sus datos válidos,<br>
        <strong>Entonces</strong> el sistema actualiza la información inmediatamente.<br><br>
        <strong>Escenario 02: Campo bloqueado</strong><br>
        <strong>Dado</strong> que intento modificar el identificador único,<br>
        <strong>Cuando</strong> guardo los cambios,<br>
        <strong>Entonces</strong> el sistema rechaza la acción y mantiene el valor original.<br><br>
      </td>
      <td>EP-01</td>
    </tr>
    <tr>
      <td>US14</td>
      <td>Eliminación e inhabilitacion de productos</td>
      <td>Como jefe de compras quiero poder desactivar o eliminar un producto para mantener un control y no saturar el sistema</td>
      <td>
        <strong>Escenario 01: Desactivación exitosa</strong><br>
        <strong>Dado</strong> que selecciono un producto activo,<br>
        <strong>Cuando</strong> ejecuto la acción de desactivar,<br>
        <strong>Entonces</strong> el sistema cambia el estado a inactivo y lo oculta de búsquedas activas.<br><br>
        <strong>Escenario 02: Consulta histórica</strong><br>
        <strong>Dado</strong> que un producto está inactivo,<br>
        <strong>Cuando</strong> consulto un historial o reporte,<br>
        <strong>Entonces</strong> el producto sigue apareciendo con sus registros asociados.<br><br>
      <td>EP-01</td>
    </tr>
    <tr>
      <td>US15</td>
      <td>Clasificación de productos por categoría</td>
      <td>Como jefe de compras quiero asignar categorías a los productos para organizar el catálogo y facilitar búsquedas</td>
      <td>
        <strong>Escenario 01: Clasificación válida</strong><br>
        <strong>Dado</strong> que existe un catálogo de categorías,<br>
        <strong>Cuando</strong> asigno una categoría a un producto,<br>
        <strong>Entonces</strong> el producto queda organizado bajo esa categoría.<br><br>
        <strong>Escenario 02: Filtrado por categoría</strong><br>
        <strong>Dado</strong> que existen varios productos en distintas categorías,<br>
        <strong>Cuando</strong> aplico un filtro por categoría,<br>
        <strong>Entonces</strong> el sistema muestra solo los productos correspondientes.<br><br>
      </td>
      <td>EP-01</td>
    </tr>
    <tr>
      <td>US16</td>
      <td>Búsqueda y filtrado de productos</td>
      <td>Como jefe de compras quiero buscar y filtrar productos por nombre, categoría o estado para acceder rápidamente a la información</td>
      <td>
        <strong>Escenario 01: Búsqueda parcial</strong><br>
        <strong>Dado</strong> que existen productos registrados,<br>
        <strong>Cuando</strong> busco por coincidencias parciales de nombre,<br>
        <strong>Entonces</strong> el sistema lista los resultados correctos.<br><br>
        <strong>Escenario 02: Búsqueda combinada</strong><br>
        <strong>Dado</strong> que aplico filtros por categoría y estado,<br>
        <strong>Cuando</strong> ejecuto la búsqueda,<br>
        <strong>Entonces</strong> el sistema muestra los productos que cumplen todas las condiciones.<br><br>
      </td>
      <td>EP-01</td>
    </tr>
    <tr>
      <td>US17</td>
      <td>Historial de cambios de producto</td>
      <td>Como jefe de compras quiero consultar el historial de cambios de cada producto para corroborar precios y poder planificar estrategicamente</td>
      <td>
        <strong>Escenario 01: Registro de cambios</strong><br>
        <strong>Dado</strong> que un usuario edita un producto,<br>
        <strong>Cuando</strong> se confirma el cambio,<br>
        <strong>Entonces</strong> el sistema genera un registro con usuario, fecha y detalle.<br><br>
        <strong>Escenario 02: Consulta de historial</strong><br>
        <strong>Dado</strong> que accedo al detalle de un producto,<br>
        <strong>Cuando</strong> selecciono la opción de historial,<br>
        <strong>Entonces</strong> el sistema muestra la lista completa de modificaciones.<br><br>
      </td>
      <td>EP-01</td>
    </tr>
  </tbody>
</table>
<!-- Landing -->
<table border="1" cellspacing="0" cellpadding="8" style="border-collapse:collapse; width:100%;">
  <thead>
    <tr>
      <th style="width:8%;">Story ID</th>
      <th style="width:18%;">Título</th>
      <th style="width:24%;">Descripción técnica</th>
      <th style="width:40%;">Criterios de Aceptación</th>
      <th style="width:10%;">Relacionado con (Epic ID)</th>
    </tr>
  </thead>  
  <tbody>
    <tr>
      <td>US18</td>
      <td>Sección de funcionalidades</td>
      <td>Como visitante quiero visualizar las principales funcionalidades de stocktrack en la landing para conocer qué ofrece la plataforma</td>
      <td>
        <strong>Escenario 01: Visualización clara</strong><br>
        <strong>Dado</strong> que navego en la landing,<br>
        <strong>Cuando</strong> hago scroll hasta la sección de funcionalidades,<br>
        <strong>Entonces</strong> se muestran al menos 4 funcionalidades clave con iconos y descripciones.<br><br>
        <strong>Escenario 02: Enlace de más información</strong><br>
        <strong>Dado</strong> que visualizo una funcionalidad,<em>Draft</em>,<br>
        <strong>Cuando</strong> hago clic en “ver más”,<br>
        <strong>Entonces</strong> el sistema me dirige a una página con detalles ampliados.<br><br>
      </td>
      <td>EP-09 </td>
    </tr>
    <tr>
      <td>US19</td>
      <td>Formulario de registro</td>
      <td>Como visitante quiero acceder a un formulario de registro en la landing para crear una cuenta rápidamente</td>
      <td>
        <strong>Escenario 01: Registro básico</strong><br>
        <strong>Dado</strong> que accedo al formulario de registro,<br>
        <strong>Cuando</strong> completo los campos obligatorios y envío,<br>
        <strong>Entonces</strong> el sistema crea mi cuenta y me redirige al panel de bienvenida.<br><br>
        <strong>Escenario 02: Validación de datos</strong><br>
        <strong>Dado</strong> que ingreso datos incompletos o inválidos,<br>
        <strong>Cuando</strong> intento registrar,<br>
        <strong>Entonces</strong> el sistema muestra mensajes de error específicos por campo.<br><br>
      </td>
      <td>EP-09</td>
    </tr>
    <tr>
      <td>US20</td>
      <td>Formulario de contacto</td>
      <td>Como visitante quiero llenar un formulario de contacto en la landing para solicitar información adicional sobre stocktrack</td>
      <td>
        <strong>Escenario 01: Envío exitoso</strong><br>
        <strong>Dado</strong> que ingreso mis datos y consulta en el formulario,<br>
        <strong>Cuando</strong> hago clic en enviar,<br>
        <strong>Entonces</strong> el sistema guarda la solicitud y muestra un mensaje de confirmación.<br><br>
        <strong>Escenario 02: Validación de campos</strong><br>
        <strong>Dado</strong> que ingreso un email no válido,<br>
        <strong>Cuando</strong> intento enviar,<br>
        <strong>Entonces</strong> el sistema bloquea la acción y muestra el error.<br><br>
      <td>EP-09</td>
    </tr>
    <tr>
      <td>US21</td>
      <td>Diseño responsive</td>
      <td>Como visitante quiero que la landing sea responsive para navegar de manera cómoda desde cualquier dispositivo</td>
      <td>
        <strong>Escenario 01: Adaptación en móvil</strong><br>
        <strong>Dado</strong> que accedo desde un celular,<br>
        <strong>Cuando</strong> cargo la landing,<br>
        <strong>Entonces</strong> todos los elementos se adaptan al ancho de pantalla.<br><br>
        <strong>Escenario 02: Adaptación en tablet</strong><br>
        <strong>Dado</strong> que accedo desde una tablet,<br>
        <strong>Cuando</strong> cargo la landing,<br>
        <strong>Entonces</strong> las secciones mantienen legibilidad y proporciones correctas.<br><br>
      </td>
      <td>EP-09</td>
    </tr>  
    <tr>
      <td>US22</td>
      <td>Sección de testimonios</td>
      <td>Como visitante quiero ver testimonios de otros usuarios en la landing para confiar más en la plataforma</td>
      <td>
        <strong>Escenario 01: Visualización de testimonios</strong><br>
        <strong>Dado</strong> que llego a la sección de testimonios,<br>
        <strong>Cuando</strong> la página carga,<br>
        <strong>Entonces</strong> se muestran al menos 3 testimonios con nombre, foto y comentario.<br><br>
        <strong>Escenario 02: Rotación automática</strong><br>
        <strong>Dado</strong> que estoy en la sección de testimonios,<br>
        <strong>Cuando</strong> pasan 5 segundos,<br>
        <strong>Entonces</strong> el sistema muestra automáticamente el siguiente testimonio.<br><br>
      </td>
      <td>EP-09</td>
    </tr>
    <tr>
      <td>US23</td>
      <td>Botones claros</td>
      <td>Como visitante quiero ver botones claros y visibles para que sea intuitivo durante la navegación</td>
      <td>
        <strong>Escenario 01: Botnes visibles</strong><br>
        <strong>Dado</strong> que navego en la landing,<br>
        <strong>Cuando</strong> la página carga,<br>
        <strong>Entonces</strong> encontrar botones visibles sin necesidad de buscar.<br><br>
        <strong>Escenario 02: Redirección correcta</strong><br>
        <strong>Dado</strong> que hago clic en el boton,<br>
        <strong>Cuando</strong> lo presiono,<br>
        <strong>Entonces</strong> el sistema me lleva directamente al formulario correcto.<br><br>
      </td>
      <td>EP-09</td>
    </tr>
  </tbody>   
</table>

<br>

<table border="1" cellspacing="0" cellpadding="8" style="border-collapse:collapse; width:100%;">
  <thead>
    <tr>
      <th style="width:8%;">Story ID</th>
      <th style="width:18%;">Título</th>
      <th style="width:24%;">Descripción técnica</th>
      <th style="width:40%;">Criterios de Aceptación</th>
      <th style="width:10%;">Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US24</td>
      <td>Crear proveedor</td>
      <td>Como jefe de compras, quiero registrar nuevos proveedores con su información clave (nombre, contacto, RUC) para centralizar los datos de mis abastecedores.</td>
      <td>
        <strong>Escenario 01: Creación exitosa</strong><br>
        <strong>Dado</strong> que ingreso los datos obligatorios de un nuevo proveedor,<br>
        <strong>Cuando</strong> guardo el formulario,<br>
        <strong>Entonces</strong> el proveedor se crea y aparece en el listado general.<br><br>
        <strong>Escenario 02: Validación de duplicados</strong><br>
        <strong>Dado</strong> que ya existe un proveedor con el mismo RUC,<br>
        <strong>Cuando</strong> intento guardar el nuevo proveedor,<br>
        <strong>Entonces</strong> el sistema muestra un error de duplicidad y no permite el registro.
      </td>
      <td>EP-10</td>
    </tr>
    <tr>
      <td>US25</td>
      <td>Consultar y editar proveedores</td>
      <td>Como encargado, quiero poder ver la lista de proveedores, buscar uno específico y editar su información para mantener los datos actualizados.</td>
      <td>
        <strong>Escenario 01: Edición exitosa</strong><br>
        <strong>Dado</strong> que abro la ficha de un proveedor existente,<br>
        <strong>Cuando</strong> modifico su número de teléfono y guardo,<br>
        <strong>Entonces</strong> la información se actualiza correctamente.<br><br>
        <strong>Escenario 02: Búsqueda por nombre</strong><br>
        <strong>Dado</strong> que estoy en la lista de proveedores,<br>
        <strong>Cuando</strong> escribo parte del nombre en la barra de búsqueda,<br>
        <strong>Entonces</strong> la lista se filtra en tiempo real mostrando solo las coincidencias.
      </td>
      <td>EP-10</td>
    </tr>
    <tr>
      <td>US26</td>
      <td>Asociar productos a proveedor</td>
      <td>Como jefe de compras, quiero asociar productos a un proveedor para saber a quién comprar cada artículo y facilitar los reportes.</td>
      <td>
        <strong>Escenario 01: Asociar producto</strong><br>
        <strong>Dado</strong> que estoy en la ficha de un proveedor,<br>
        <strong>Cuando</strong> selecciono la opción "Asociar producto" y elijo un ítem del catálogo,<br>
        <strong>Entonces</strong> el producto queda vinculado al proveedor.<br><br>
        <strong>Escenario 02: Visualizar productos del proveedor</strong><br>
        <strong>Dado</strong> un proveedor con productos asociados,<br>
        <strong>Cuando</strong> consulto su ficha,<br>
        <strong>Entonces</strong> puedo ver una lista de todos los productos que este me suministra.
      </td>
      <td>EP-10</td>
    </tr>
  </tbody>
</table>

<table border="1" cellspacing="0" cellpadding="8" style="border-collapse:collapse; width:100%;">
  <thead>
    <tr>
      <th style="width:8%;">Story ID</th>
      <th style="width:18%;">Título</th>
      <th style="width:24%;">Descripción técnica</th>
      <th style="width:40%;">Criterios de Aceptación</th>
      <th style="width:10%;">Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US27</td>
      <td>Visualizar KPIs principales</td>
      <td>Como dueño, quiero ver en el dashboard tarjetas con KPIs clave (valor de inventario, productos con stock bajo) para un resumen rápido del negocio.</td>
      <td>
        <strong>Escenario 01: KPI de Valor de Inventario</strong><br>
        <strong>Dado</strong> que he iniciado sesión,<br>
        <strong>Cuando</strong> cargo el dashboard,<br>
        <strong>Entonces</strong> veo una tarjeta que muestra el valor total de mi inventario (stock x costo).<br><br>
        <strong>Escenario 02: KPI de Stock Bajo</strong><br>
        <strong>Dado</strong> que he iniciado sesión,<br>
        <strong>Cuando</strong> cargo el dashboard,<br>
        <strong>Entonces</strong> veo una tarjeta que muestra el número total de productos cuyo stock está por debajo del umbral mínimo.
      </td>
      <td>EP-03</td>
    </tr>
    <tr>
    <td>US28</td>
    <td>Ver alertas críticas</td>
    <td>Como encargado, quiero que el dashboard me muestre una lista de alertas urgentes (lotes próximos a vencer) para tomar acciones preventivas.</td>
    <td>
      <strong>Escenario 01: Mostrar lotes por vencer</strong><br>
      <strong>Dado</strong> que existen lotes cuya fecha de vencimiento es en los próximos 7 días,<br>
      <strong>Cuando</strong> cargo el dashboard,<br>
      <strong>Entonces</strong> veo una sección de alertas con la lista de dichos lotes.<br><br>
      <strong>Escenario 02: Navegación desde alerta</strong><br>
      <strong>Dado</strong> que veo una alerta de un lote por vencer,<br>
      <strong>Cuando</strong> hago clic en la alerta,<br>
      <strong>Entonces</strong> el sistema me redirige a la ficha del producto correspondiente para gestionarlo.
    </td>
    <td>EP-03</td>
    </tr>
  </tbody>
</table>

<table border="1" cellspacing="0" cellpadding="8" style="border-collapse:collapse; width:100%;">
  <thead>
    <tr>
      <th style="width:8%;">Story ID</th>
      <th style="width:18%;">Título</th>
      <th style="width:24%;">Descripción técnica</th>
      <th style="width:40%;">Criterios de Aceptación</th>
      <th style="width:10%;">Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US29</td>
      <td>Definir composición de un kit</td>
      <td>Como encargado, quiero crear la "receta" de un kit, asociando productos existentes y sus cantidades, para estandarizar el contenido de los paquetes.</td>
      <td>
        <strong>Escenario 01: Creación de la definición</strong><br>
        <strong>Dado</strong> que estoy en la sección de Kits,<br>
        <strong>Cuando</strong> creo un nuevo kit, le asigno un nombre y agrego 3 productos componentes con sus respectivas cantidades,<br>
        <strong>Entonces</strong> el sistema guarda la definición (receta) del kit.<br><br>
        <strong>Escenario 02: Edición de componentes</strong><br>
        <strong>Dado</strong> que un kit ya está definido,<br>
        <strong>Cuando</strong> edito el kit para cambiar la cantidad de un componente,<br>
        <strong>Entonces</strong> la receta del kit se actualiza para futuros ensamblajes.
      </td>
    <td>EP-05</td>
    </tr>
    <tr>
    <td>US30</td>
    <td>Ensamblar kits y ajustar stock</td>
    <td>Como encargado de bodega, quiero registrar el "ensamblaje" de kits para que el sistema descuente el stock de los componentes y aumente el stock del kit como producto final.</td>
    <td>
      <strong>Escenario 01: Ensamblaje exitoso</strong><br>
      <strong>Dado</strong> que tengo stock suficiente de todos los componentes de un kit,<br>
      <strong>Cuando</strong> registro el ensamblaje de 5 kits,<br>
      <strong>Entonces</strong> el sistema reduce el stock de los componentes y aumenta en 5 el stock del producto kit.<br><br>
      <strong>Escenario 02: Bloqueo por falta de stock</strong><br>
      <strong>Dado</strong> que no tengo stock suficiente de uno de los componentes,<br>
      <strong>Cuando</strong> intento registrar el ensamblaje de un kit,<br>
      <strong>Entonces</strong> el sistema bloquea la acción y me informa qué componente falta.
    </td>
    <td>EP-05</td>
    </tr>
  </tbody>
</table>

<table border="1" cellspacing="0" cellpadding="8" style="border-collapse:collapse; width:100%;">
  <thead>
    <tr>
      <th style="width:8%;">Story ID</th>
      <th style="width:18%;">Título</th>
      <th style="width:24%;">Descripción técnica</th>
      <th style="width:40%;">Criterios de Aceptación</th>
      <th style="width:10%;">Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US30</td>
      <td>Configurar umbrales de stock</td>
      <td>Como jefe de compras, quiero definir umbrales mínimos de stock por producto para que el sistema pueda generar alertas automáticas.</td>
      <td>
        <strong>Escenario 01: Registro de umbral</strong><br>
        <strong>Dado</strong> un producto sin umbral,<br>
        <strong>Cuando</strong> registro un valor mínimo,&nbsp;<br>
        <strong>Entonces</strong> el sistema guarda la configuración asociada al producto.<br><br> <strong>Escenario 02: Edición</strong><br>
        <strong>Dado</strong> un umbral ya configurado,<br>
        <strong>Cuando</strong> lo edito y guardo,<br>
        <strong>Entonces</strong> el sistema actualiza el valor y registra la fecha de modificación.
      </td>
        <td>EP-06</td> 
    </tr>
    <tr>
      <td>US31</td>
      <td>Generar alerta de bajo stock</td>
      <td>Como sistema, quiero generar una alerta cuando el stock de un producto caiga por debajo del umbral configurado.</td>
      <td>
        <strong>Escenario 01: Umbral superado</strong><br>
        <strong>Dado</strong> que un producto tiene stock menor al umbral,<br>
        <strong>Cuando</strong> se registra un movimiento de salida,<br>
        <strong>Entonces</strong> el sistema crea una alerta de tipo “Bajo stock” con fecha y cantidad disponible <br><br>
        <strong>Escenario 02: No aplica</strong><br>
        <strong>Dado</strong> un producto sin umbral definido,<br>
        <strong>Cuando</strong> se procesa la salida,<br>
        <strong>Entonces</strong> no se genera alerta.
      </td>
      <td>EP-06</td>
    </tr>
    <tr>
      <td>US32</td>
      <td>Generar alerta de vencimiento</td>
      <td>Como sistema, quiero generar una alerta cuando un lote esté próximo a vencer dentro de la ventana configurada.</td>
      <td>
        <strong>Escenario 01: Próximo vencimiento</strong><br>
        <strong>Dado</strong> un lote con fecha de vencimiento a menos de X días,<br>
        <strong>Cuando</strong> se actualiza el inventario,<br>
        <strong>Entonces</strong> el sistema crea una alerta “Próximo a vencer” con lote, cantidad y fecha.<br><br>
        <strong>Escenario 02: Fuera de ventana</strong><br>
        <strong>Dado</strong> un lote con vencimiento mayor al rango configurado,<br>
        <strong>Cuando</strong> se valida el inventario,<br>
        <strong>Entonces</strong> no se genera alerta. 
      </td>
      <td>EP-06</td> 
    </tr>
    <tr>
      <td>US33</td>
      <td>Listar alertas pendientes</td>
      <td>Como usuario, quiero ver un listado de todas las alertas activas (bajo stock, próximos a vencer, vencidos) para tomar decisiones.</td>
      <td> 
        <strong>Escenario 01: Listado</strong><br>
        <strong>Dado</strong> que existen alertas activas,<br>
        <strong>Cuando</strong> ingreso al módulo de alertas,<br>
        <strong>Entonces</strong> el sistema muestra tabla con tipo, producto/lote, fecha y estado.<br><br>
        <strong>Escenario 02: Sin alertas</strong><br>
        <strong>Dado</strong> que no existen alertas activas,<br>
        <strong>Cuando</strong> consulto el listado,<br>
        <strong>Entonces</strong> el sistema muestra mensaje “No hay alertas pendientes”.
      </td>
      <td>EP-06</td> 
    </tr> 
    <tr>
      <td>US34</td>
      <td>Notificación externa de alertas</td>
      <td>Como usuario, quiero recibir notificaciones por correo o push cuando se generen alertas críticas.</td> <td>
        <strong>Escenario 01: Envío de correo</strong><br>
        <strong>Dado</strong> una alerta de tipo “Bajo stock crítico”,<br>
        <strong>Cuando</strong> se genera,<br>
        <strong>Entonces</strong> el sistema envía correo al jefe de compras con detalle.<br><br>
        <strong>Escenario 02: Notificación push</strong><br>
        <strong>Dado</strong> que el usuario tiene app móvil habilitada,<br>
        <strong>Cuando</strong> ocurre la alerta,<br>
        <strong>Entonces</strong> recibe notificación push con resumen y enlace al sistema.
      </td>
      <td>EP-06</td>
    </tr>
    <tr>
      <td>US35</td>
      <td>Gestionar estado de alertas</td>
      <td>Como jefe de compras, quiero marcar las alertas como atendidas o descartadas para mantener control del seguimiento.</td>
      <td>
        <strong>Escenario 01: Marcar como atendida</strong><br>
        <strong>Dado</strong> una alerta activa,<br>
        <strong>Cuando</strong> la marco como atendida,<br>
        <strong>Entonces</strong> el sistema cambia el estado y registra usuario/fecha.<br><br>
        <strong>Escenario 02: Descartar</strong><br>
        <strong>Dado</strong> una alerta no aplicable,<br>
        <strong>Cuando</strong> la descarto,<br>
        <strong>Entonces</strong> el sistema la archiva sin afectar inventario.
      </td>
      <td>EP-06</td> 
    </tr>
  </tbody>
</table>

<table border="1" cellspacing="0" cellpadding="8" style="border-collapse:collapse; width:100%;">
  <thead>
    <tr>
      <th style="width:8%;">Story ID</th>
      <th style="width:18%;">Título</th>
      <th style="width:24%;">Descripción técnica</th>
      <th style="width:40%;">Criterios de Aceptación</th>
      <th style="width:10%;">Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US36</td>
      <td>Iniciar borrador de ingreso</td>
      <td>Como asistente de almacén, quiero iniciar un borrador de ingreso para registrar productos recibidos antes de confirmarlos.</td>
      <td>
        <strong>Escenario 01: Borrador creado</strong><br>
        <strong>Dado</strong> que estoy en “Nuevo ingreso”,<br>
        <strong>Cuando</strong> selecciono “Iniciar borrador”,<br>
        <strong>Entonces</strong> el sistema crea un borrador con ID único, estado <em>Draft</em> y fecha de inicio.<br><br>
        <strong>Escenario 02: Reanudación</strong><br>
        <strong>Dado</strong> un borrador en estado <em>Draft</em>,<br>
        <strong>Cuando</strong> lo reanudo,<br>
        <strong>Entonces</strong> se muestran ítems y cantidades guardadas.
      </td>
      <td>EP-04</td>
    </tr>
    <tr>
      <td>US37</td>
      <td>Registrar ítems del ingreso</td>
      <td>Como asistente de almacén, quiero agregar productos, lotes y cantidades recibidas al borrador sin impactar aún el stock.</td>
      <td>
        <strong>Escenario 01: Agregar ítem</strong><br>
        <strong>Dado</strong> un borrador activo,<br>
        <strong>Cuando</strong> agrego un producto con lote y cantidad válida,&nbsp;<br>
        <strong>Entonces</strong> el sistema registra el ítem en el borrador.<br><br>
        <strong>Escenario 02: Editar cantidad</strong><br>
        <strong>Dado</strong> un ítem en el borrador,<br>
        <strong>Cuando</strong> cambio la cantidad,<br>
        <strong>Entonces</strong> se actualiza el subtotal.<br><br>
        <strong>Escenario 03: Retirar ítem</strong><br>
        <strong>Dado</strong> un ítem en el borrador,<br>
        <strong>Cuando</strong> lo elimino,<br>
        <strong>Entonces</strong> desaparece y se recalculan totales.
      </td>
      <td>EP-04</td>
    </tr>
    <tr>
      <td>US38</td>
      <td>Registrar costo y proveedor</td>
      <td>Como asistente de almacén, quiero asociar cada ingreso a un costo unitario y proveedor para trazabilidad de compras.</td>
      <td>
        <strong>Escenario 01: Costo y proveedor válidos</strong><br>
        <strong>Dado</strong> un borrador de ingreso,<br>
        <strong>Cuando</strong> ingreso costo y proveedor,<br>
        <strong>Entonces</strong> se guarda la información por producto/lote.<br><br>
        <strong>Escenario 02: Datos incompletos</strong><br>
        <strong>Dado</strong> un ítem sin costo o proveedor,<br>
        <strong>Cuando</strong> intento confirmar,<br>
        <strong>Entonces</strong> el sistema muestra error indicando campos obligatorios.
      </td>
      <td>EP-04</td>
    </tr>
    <tr>
      <td>US39</td>
      <td>Confirmar ingreso y actualizar stock</td>
      <td>Como asistente de almacén, quiero confirmar el ingreso para registrar movimientos positivos y actualizar el on-hand.</td>
      <td>
        <strong>Escenario 01: Confirmación exitosa</strong><br>
        <strong>Dado</strong> un borrador válido,<br>
        <strong>Cuando</strong> confirmo,<br>
        <strong>Entonces</strong> el sistema crea movimientos por ítem, incrementa on-hand y cambia estado a <em>Confirmed</em>.<br><br>
        <strong>Escenario 02: Duplicidad de lote</strong><br>
        <strong>Dado</strong> que ya existe el lote,<br>
        <strong>Cuando</strong> confirmo ingreso,<br>
        <strong>Entonces</strong> el sistema suma cantidades y deja traza de consolidación.
      </td>
      <td>EP-04</td>
    </tr>
    <tr>
      <td>US40</td>
      <td>Adjuntar documento de respaldo</td>
      <td>Como asistente de almacén, quiero adjuntar la factura o guía de remisión al ingreso para evidencia documental.</td>
      <td>
        <strong>Escenario 01: Adjuntar archivo</strong><br>
        <strong>Dado</strong> un borrador,<br>
        <strong>Cuando</strong> subo un PDF o imagen,<br>
        <strong>Entonces</strong> queda vinculado al ingreso y visible en el detalle.<br><br>
        <strong>Escenario 02: Formato inválido</strong><br>
        <strong>Dado</strong> un archivo distinto a PDF/imagen,<br>
        <strong>Cuando</strong> lo subo,<br>
        <strong>Entonces</strong> el sistema rechaza el archivo y muestra mensaje de error.
      </td>
      <td>EP-04</td> 
    </tr>
    <tr>
      <td>US41</td>
      <td>Disparar alertas por ingreso</td>
      <td>Como sistema, quiero recalcular coberturas y eliminar alertas de bajo stock cuando se confirme un ingreso.</td>
      <td>
        <strong>Escenario 01: Recalculo de coberturas</strong><br>
        <strong>Dado</strong> que confirmo un ingreso,<br>
        <strong>Cuando</strong> incrementa el stock de un producto,<br>
        <strong>Entonces</strong> se recalculan días de cobertura y se actualiza estado de alertas previas.<br><br>
        <strong>Escenario 02: Eliminación de alerta</strong><br>
        <strong>Dado</strong> una alerta activa de bajo stock,<br>
        <strong>Cuando</strong> el ingreso hace que on-hand supere el umbral,<br>
        <strong>Entonces</strong> el sistema marca la alerta como resuelta automáticamente.
      </td>
      <td>EP-04</td>
    </tr>
  </tbody>
</table>

<!--Lotes y vencimiento-->
<table border="1" cellspacing="0" cellpadding="8" style="border-collapse:collapse; width:100%;">
  <thead>
    <tr>
      <th style="width:8%;">Story ID</th>
      <th style="width:18%;">Título</th>
      <th style="width:24%;">Descripción técnica</th>
      <th style="width:40%;">Criterios de Aceptación</th>
      <th style="width:10%;">Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US42</td>
      <td>Verificar compra de lotes</td>
      <td>Como dueño de bodega, quiero gestionar y verificar la cantidad de los lotes recibidos para tener un mejor control del inventario.</td>
      <td>
        <strong>Escenario 01: Añadir nuevo lote sin registrar</strong><br>
        <strong>Dado</strong> que el dueño de bodega entra a la aplicación<br>
        <strong>Cuando</strong> recibe un nuevo lote de productos no registrados previamente,<br>
        <strong>Entonces</strong> registra el lote recibido con los datos respectivos dentro de la aplicación <br><br>
        <strong>Escenario 02: Añadir lote registrado</strong><br>
        <strong>Dado</strong> que el dueño de bodega entra a la aplicación,<br>
        <strong>Cuando</strong> recibe un nuevo lote de productos registrados previamente,<br>
        <strong>Entonces</strong> añade la cantidad de lotes recibidos registrados previamente.
      </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>US43</td>
      <td>Ver fecha de vencimiento de los lotes</td>
      <td>Como asistente de almacén, quiero verificar la fecha de vencimiento de mis productos para estar pendiente de cuando reponerlos.</td>
      <td>
        <strong>Escenario 01: Verificar fecha de vencimiento de los lotes</strong><br>
        <strong>Dado</strong> que el dueño de bodega está dentro de la aplicación y tengo lotes registrados,<br>
        <strong>Cuando</strong> quiere ver la fecha de vencimiento de sus productos <br>
        <strong>Entonces</strong> el sistema muestra la información del lote junto con fecha de vencimiento de los mismos .<br><br>
        <strong>Escenario 02: No hay lotes registrados</strong><br>
        <strong>Dado</strong> que el dueño de bodega está dentro de la aplicación y no tiene lotes registrados,<br>
        <strong>Cuando</strong> quiere ver la fecha de vencimiento de sus productos,<br>
        <strong>Entonces</strong> no se muestra información de los productos y el sistema muestra que se deben registrar lotes primero.<br><br>
      </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>US44</td>
      <td>Registrar costo y proveedor</td>
      <td>Como asistente de almacén, quiero asociar cada ingreso a un costo unitario y proveedor para trazabilidad de compras.</td>
      <td>
        <strong>Escenario 01: Costo y proveedor válidos</strong><br>
        <strong>Dado</strong> un borrador de ingreso,<br>
        <strong>Cuando</strong> ingreso costo y proveedor,<br>
        <strong>Entonces</strong> se guarda la información por producto/lote.<br><br>
        <strong>Escenario 02: Datos incompletos</strong><br>
        <strong>Dado</strong> un ítem sin costo o proveedor,<br>
        <strong>Cuando</strong> intento confirmar,<br>
        <strong>Entonces</strong> el sistema muestra error indicando campos obligatorios.
      </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>US45</td>
      <td>Alertar vencimiento próximo</td>
      <td>Como dueño de bodega, quiero recibir una alerta cuando un lote esté próximo a vencer para poder tomar decisiones a tiempo.</td>
      <td>
        <strong>Escenario 01: Confirmación exitosa</strong><br>
        <strong>Dado</strong> que hay un lote registrado con fecha de vencimiento en menos de 15 días<br>
        <strong>Cuando</strong> confirmo,<br>
        <strong>Entonces</strong> el sistema muestra una alerta visual indicando producto, lote y fecha próxima a vencer.<br><br>
        <strong>Escenario 02: Sin lotes próximos a vencer</strong><br>
        <strong>Dado</strong> que todos los lotes registrados vencen en más de 15 días,<br>
        <strong>Cuando</strong> ingreso a la aplicación,<br>
        <strong>Entonces</strong> no se muestra ninguna alerta
      </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>US46</td>
      <td>Buscar lotes por proveedor</td>
      <td>Como dueño de bodega, quiero filtrar los lotes por proveedor para identificar rápidamente qué productos corresponden a cada socio comercial.</td>
      <td>
        <strong>Escenario 01: Proveedor con lotes registrados</strong><br>
        <strong>Dado</strong> que existen lotes con proveedor “Distribuidora XYZ”,<br>
        <strong>Cuando</strong> filtro por ese proveedor,<br>
        <strong>Entonces</strong> el sistema lista los lotes asociados a él con sus fechas de vencimiento.<br><br>
        <strong>Escenario 02: Proveedor sin lotes registrados</strong><br>
        <strong>Dado</strong> que “Proveedor ABC” no tiene lotes en el sistema,<br>
        <strong>Cuando</strong> aplico el filtro,<br>
        <strong>Entonces</strong> el sistema muestra “No hay lotes asociados a este proveedor”.
      </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>US47</td>
      <td>Editar información de un lote</td>
      <td>Como asistente de almacén, quiero poder editar la información de un lote (fecha de vencimiento, cantidad o proveedor) para corregir errores en el registro.</td>
      <td>
        <strong>Escenario 01: Edición exitosa</strong><br>
        <strong>Dado</strong> que un lote está registrado,<br>
        <strong>Cuando</strong> modifico su fecha de vencimiento o cantidad,<br>
        <strong>Entonces</strong> el sistema guarda los cambios y muestra un mensaje de confirmación.<br><br>
        <strong>Escenario 02: Intento de edición con datos inválidos</strong><br>
        <strong>Dado</strong> que ingreso una fecha de vencimiento en el pasado,<br>
        <strong>Cuando</strong> intento guardar,<br>
        <strong>Entonces</strong> el sistema rechaza el cambio y muestra un error.
      </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>US48</td>
      <td>Ver historial de movimientos de un lote</td>
      <td>Como dueño de bodega, quiero consultar el historial de movimientos de cada lote para tener trazabilidad de ingresos y salidas.</td>
      <td>
        <strong>Escenario 01: Historial disponible</strong><br>
        <strong>Dado</strong> que un lote tiene registros de ingreso y salida,<br>
        <strong>Cuando</strong> consulto su historial,<br>
        <strong>Entonces</strong> el sistema muestra una lista con fecha, tipo de movimiento, cantidad y usuario que lo realizó.<br><br>
        <strong>Escenario 02: Sin historial</strong><br>
        <strong>Dado</strong> que un lote recién se registró y no tiene movimientos,<br>
        <strong>Cuando</strong> consulto el historial,<br>
        <strong>Entonces</strong> el sistema indica “Este lote no tiene movimientos registrados”.
      </td>
      <td>EP-02</td>
    </tr>
  </tbody>
</table>

<!--- Usuarios, permisos y roles --->
<table border="1" cellspacing="0" cellpadding="8" style="border-collapse:collapse; width:100%;">
  <thead>
    <tr>
      <th style="width:8%;">Story ID</th>
      <th style="width:18%;">Título</th>
      <th style="width:24%;">Descripción</th>
      <th style="width:40%;">Escenarios</th>
      <th style="width:10%;">Épica</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US49</td>
      <td>Crear usuarios nuevos</td>
      <td>Como dueño de un startup, quiero crear cuentas de usuario para que cada miembro del equipo tenga acceso individual a la plataforma.</td>
      <td>
        <strong>Escenario 01: Creación exitosa</strong><br>
        Dado que estoy en el módulo de usuarios,<br>
        Cuando ingreso nombre, correo y rol,<br>
        Entonces el sistema guarda el nuevo usuario y envía invitación.<br><br>
        <strong>Escenario 02: Datos incompletos</strong><br>
        Dado que no ingresé correo electrónico,<br>
        Cuando intento crear el usuario,<br>
        Entonces el sistema muestra error de campo obligatorio.
      </td>
      <td>EP-08</td>
    </tr>
    <tr>
      <td>US50</td>
      <td>Asignar roles</td>
      <td>Como administrador, quiero asignar un rol a cada usuario para definir qué puede y qué no puede hacer dentro de la aplicación.</td>
      <td>
        <strong>Escenario 01: Rol asignado correctamente</strong><br>
        Dado que un usuario existe,<br>
        Cuando le asigno el rol “Asistente”,<br>
        Entonces el sistema actualiza sus permisos.<br><br>
        <strong>Escenario 02: Usuario sin rol</strong><br>
        Dado que un usuario no tiene rol,<br>
        Cuando intenta ingresar,<br>
        Entonces el sistema muestra “Acceso restringido”.
      </td>
      <td>EP-08</td>
    </tr>
    <tr>
      <td>US51</td>
      <td>Editar permisos personalizados</td>
      <td>Como administrador, quiero ajustar permisos específicos en un usuario para dar accesos excepcionales.</td>
      <td>
        <strong>Escenario 01: Permiso extra</strong><br>
        Dado que un usuario tiene rol “Asistente”,<br>
        Cuando le habilito permiso extra de “Ver reportes”,<br>
        Entonces el usuario puede acceder al módulo.<br><br>
        <strong>Escenario 02: Quitar permisos</strong><br>
        Dado que un usuario tenía acceso a “Crear lotes”,<br>
        Cuando desactivo ese permiso,<br>
        Entonces el sistema bloquea su acceso.
      </td>
      <td>EP-08</td>
    </tr>
    <tr>
      <td>US52</td>
      <td>Bloquear usuarios</td>
      <td>Como administrador, quiero poder desactivar usuarios para evitar accesos no autorizados.</td>
      <td>
        <strong>Escenario 01: Usuario bloqueado</strong><br>
        Dado que un usuario está activo,<br>
        Cuando lo marco como bloqueado,<br>
        Entonces ya no puede iniciar sesión.<br><br>
        <strong>Escenario 02: Intento de ingreso bloqueado</strong><br>
        Dado que un usuario está bloqueado,<br>
        Cuando intenta iniciar sesión,<br>
        Entonces el sistema muestra “Cuenta deshabilitada”.
      </td>
      <td>EP-08</td>
    </tr>
    <tr>
      <td>US53</td>
      <td>Ver lista de usuarios</td>
      <td>Como administrador, quiero ver un listado con todos los usuarios, roles y estado de cuenta para gestionar mejor el equipo.</td>
      <td>
        <strong>Escenario 01: Lista con usuarios</strong><br>
        Dado que hay usuarios registrados,<br>
        Cuando entro al módulo,<br>
        Entonces veo listado con nombre, correo, rol y estado.<br><br>
        <strong>Escenario 02: Sin usuarios</strong><br>
        Dado que no hay usuarios en el sistema,<br>
        Cuando consulto el listado,<br>
        Entonces se muestra “No existen usuarios registrados”.
      </td>
      <td>EP-08</td>
    </tr>
    <tr>
      <td>US54</td>
      <td>Cambiar rol de un usuario</td>
      <td>Como administrador, quiero poder cambiar el rol de un usuario para ajustar sus responsabilidades dentro de la bodega/startup.</td>
      <td>
        <strong>Escenario 01: Cambio exitoso</strong><br>
        Dado que un usuario tiene rol “Asistente”,<br>
        Cuando lo cambio a “Supervisor”,<br>
        Entonces el sistema actualiza sus permisos.<br><br>
        <strong>Escenario 02: Restricción</strong><br>
        Dado que intento degradar al único “Administrador”,<br>
        Cuando confirmo,<br>
        Entonces el sistema impide la acción.
      </td>
      <td>EP-08</td>
    </tr>
    <tr>
      <td>US55</td>
      <td>Auditoría de accesos</td>
      <td>Como administrador, quiero consultar un historial de accesos de los usuarios para detectar intentos fallidos o acciones sospechosas.</td>
      <td>
        <strong>Escenario 01: Accesos exitosos</strong><br>
        Dado que los usuarios ingresaron,<br>
        Cuando consulto el historial,<br>
        Entonces veo fecha, hora, usuario y estado.<br><br>
        <strong>Escenario 02: Intentos fallidos</strong><br>
        Dado que un usuario ingresó mal contraseña 3 veces,<br>
        Cuando reviso,<br>
        Entonces aparece “intento fallido”.
      </td>
      <td>EP-08</td>
    </tr>
    <tr>
      <td>US56</td>
      <td>Roles predefinidos</td>
      <td>Como administrador, quiero contar con roles predefinidos (Administrador, Supervisor, Asistente) para acelerar la configuración inicial.</td>
      <td>
        <strong>Escenario 01: Crear usuario con rol predefinido</strong><br>
        Dado que selecciono “Supervisor”,<br>
        Cuando creo al usuario,<br>
        Entonces el sistema aplica permisos estándar.<br><br>
        <strong>Escenario 02: Personalizar rol</strong><br>
        Dado que un usuario tiene rol “Asistente”,<br>
        Cuando ajusto permisos,<br>
        Entonces el sistema conserva la base del rol y aplica cambios.
      </td>
      <td>EP-08</td>
    </tr>
  </tbody>
</table>

### Epics
<table border="1" cellspacing="0" cellpadding="8" style="border-collapse:collapse; width:100%;">
  <thead>
    <tr>
      <th style="width:10%;">Epic ID</th>
      <th style="width:20%;">Título</th>
      <th style="width:55%;">Descripción</th>
      <th style="width:15%;">HUs asociadas</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>EP-01</td>
      <td>Catálogo de Productos</td>
      <td>Como jefe de compras, quiero crear y mantener el maestro de productos (nombre, UM, categoría, estado) y configurar umbrales de bajo stock, para asegurar datos consistentes y habilitar alertas útiles.</td>
      <td>US018, US19, US20, US21, US22, US23</td>
    </tr>
    <tr>
      <td>EP-02</td>
      <td>Lotes y Vencimientos</td>
      <td>Como encargado de bodega, quiero gestionar lotes y asignar fechas de vencimiento aplicando políticas como FEFO, para garantizar trazabilidad y reducir mermas por caducidad.</td>
      <td>US43, US44, US45, US46, US47, US48</td>
    </tr>
    <tr>
      <td>EP-03</td>
      <td>Dashboard</td>
      <td>Como usuario, quiero acceder a un panel de control con métricas clave (productos próximos a vencer, stock bajo, rotación, alertas recientes), para tener una visión general y tomar decisiones rápidas..</td>
      <td>US27, US28</td>
    </tr>
    <tr>
      <td>EP-04</td>
      <td>Movimientos de Inventario</td>
      <td>Como cajero, quiero registrar de forma precisa todas las entradas (compras, ajustes) y salidas de productos, para mantener la exactitud del stock en tiempo real y tener una trazabilidad completa de cada movimiento.</td>
      <td>US01, US02, US03, US04, US05, US06, US36, US37, US38, US39, US40, US41</td>
    </tr>
    <tr>
      <td>EP-05</td>
      <td>Kits</td>
      <td>Como usuario del negocio, quiero definir kits (combos) y agregarlos a la venta con desglose automático de componentes, para impactar correctamente el stock y el costo real.</td>
      <td>US29, US30</td>
    </tr>
    <tr>
      <td>EP-06</td>
      <td>Alertas y Notificaciones</td>
      <td>Como dueño o jefe de compras, quiero recibir alertas de bajo stock y próximos a vencer por canales externos simples (email, Telegram/Slack, push), para reponer a tiempo y evitar pérdidas.</td>
      <td>US30, US31, US32, US33, US34, US35</td>
    </tr>
    <tr>
      <td>EP-07</td>
      <td>Reportes Operativos</td>
      <td>Como gerente, quiero emitir reportes de stock a fecha (valorizado), rotación/ventas con utilidad, mermas/ajustes, con exportación a CSV/PDF/Sheets, para tomar decisiones y auditar.</td>
      <td>US07, US08, US09, US10, US11</td>
    </tr>
    <tr>
      <td>EP-08</td>
      <td>Usuarios, Roles y Permisos</td>
      <td>Como dueño, quiero crear usuarios y asignar roles y permisos mínimos (dueño, encargado, cajero/supervisor), para controlar el acceso y resguardar operaciones clave.</td>
      <td>US49, US50, US51, US52, US53, US54, US55, US56</td>
    </tr>
    <tr>
      <td>EP-09</td>
      <td>Landing</td>
      <td>Como visitante, quiero visualizar una landing con propuesta de valor, funcionalidades y registro/contacto, para conocer StockTrack y convertirme en usuario.</td>
      <td>US012, US13, US14, US15, US16, US17</td>
    </tr>
    <tr>
      <td>EP-10</td>
      <td>Proveedores</td>
      <td>Como encargado de compras, quiero registrar, consultar, editar y eliminar proveedores, asociarlos a productos y gestionar datos de contacto, para asegurar un abastecimiento confiable y trazable.</td>
      <td>US24, US25, US26</td>
    </tr>
  </tbody>
</table>


### 3.3. Impact Mapping
A continuación se visualiza el **Impact Map** del proyecto **Inventiapp**, donde se muestra la relación entre el *Business Goal* definido, los **User Personas** identificados, los **Impactos** esperados en su comportamiento, los **Deliverables** que como negocio digital podemos ofrecer y las **User Stories** asociadas que permitirán implementar las funcionalidades necesarias en la aplicación web y la landing page. Este mapa busca asegurar la alineación entre los objetivos estratégicos y el desarrollo de la solución digital.


<p align="center">
  <img src="./assets/impactMap.png" alt="Impact Map" width="700">
</p>

### 3.4. Product Backlog

| # Orden |  User Story Id  | Título                                            | Descripción                                                                                                                     |  Story Points (1/2/3/5/8) |
| :------ | :-------------- | :------------------------------------------------ | :------------------------------------------------------------------------------------------------------------------------------ | :-------------------------|
|    01   | US-01           | Iniciar borrador de salida             | Como cajero, quiero iniciar un borrador de salida para agrupar ítems de una venta antes de confirmarla.  |  5                        |
|    02   | US-02           | Gestionar ítems del borrador                           | Como cajero, quiero buscar productos y agregar/editar/retirar ítems con cantidades válidas sin impactar el stock aún.                                                     |  3                        |
|    03   | US-03           | Recuperación de contraseña                        | Como usuario quiero recuperar mi contraseña vía correo/OTP para restaurar acceso.                                               |  2                        |
|    04   | US-04           | Ver y descargar póliza                            | Como usuario quiero ver y descargar mi póliza en PDF para compartirla o archivarla.                                             |  3                        |
|    05   | US-05           | Selección y compra de plan                        | Como estudiante quiero elegir entre plan Básico y Premium y pagar en línea para activar cobertura.                              |  5                        |
|    06   | US-06           | Upgrade/downgrade de plan                         | Como usuario quiero cambiar entre planes para ajustar mi cobertura.                                                             |  2                        |
|    07   | US-07           | Contratación digital con documentos               | Como usuario quiero subir mi DNI y constancia universitaria para validar afiliación automáticamente.                            |  2                        |
|    08   | US-08           | Iniciar reclamo por chat (foto + texto)           | Como usuario quiero abrir un reclamo desde el chat subiendo foto y descripción para rapidez.                                    |  5                        |
|    09   | US-09           | Validación automática de reclamos menores         | Como usuario quiero que reclamos sencillos sean evaluados automáticamente para respuesta rápida.                                |  5                        |
|    10   | US-10           | Escalamiento y comunicación con ajustador         | Como usuario quiero que reclamos complejos se escalen a un ajustador y tenga comunicación clara.                                |  3                        |
|    11   | US-11           | Historial y estado de reclamos                    | Como usuario quiero ver el historial y estado de mis reclamos para seguimiento.                                                 |  3                        |
|    12   | US-12           | Simulador de devolución (cliente)                 | Como usuario quiero simular cuánto recibiría en caso de reclamo para tomar decisiones.                                          |  3                        |
|    13   | US-13           | Panel de prevenciones y recordatorios             | Como usuario quiero recibir alertas de prevención y recordatorios para reducir riesgos.                                         |  3                        |
|    14   | US-14           | Teleconsulta on-demand                            | Como usuario quiero solicitar una teleconsulta rápida para atención médica menor.                                               |  5                        |
|    15   | US-15           | Agenda y registro de teleconsultas                | Como usuario quiero ver mis citas y registro de consultas para historial médico básico.                                         |  3                        |
|    16   | US-16           | Cobertura de viaje corto (activar/confirmar)      | Como usuario quiero activar protección para viajes interurbanos antes de partir.                                                |  5                        |
|    17   | US-17           | Reporte rápido de pérdida en traslado             | Como usuario quiero reportar pérdida de equipaje en traslado con prueba y ubicación aproximada.                                 |  3                        |
|    18   | US-18           | Notificaciones push y correo                      | Como usuario quiero recibir notificaciones sobre estados de reclamos, pagos y consultas.                                        |  2                        |
|    19   | US-19           | Compartir póliza con padres/tutores               | Como usuario quiero compartir mi póliza con mi padre/tutor para que estén informados.                                           |  2                        |
|    20   | US-20           | Ver resumen de beneficios (Landing)               | Como visitante, quiero ver los beneficios que ofrece la app para entender cómo me puede ayudar.                                 |  3                        |
|    21   | US-21           | Visualizar testimonios (Landing)                  | Como visitante, quiero leer testimonios de usuarios para confiar en la app.                                                     |  2                        |
|    22   | US-22           | Acceder desde distintos dispositivos (responsive) | Como visitante, quiero que la landing se vea bien en cualquier dispositivo para explorarla cómodamente.                         |  3                        |
|    23   | US-23           | Conocer la propuesta de valor (Hero)              | Como visitante, quiero entender rápidamente qué hace la app y cómo me beneficia.                                                |  2                        |
|    24   | US-24           | Navegar por beneficios (scroll y accesibilidad)   | Como visitante, quiero navegar por la sección de beneficios para conocer ventajas.                                              |  3                        |
|    25   | US-25           | Barra de navegación con anclas                    | Como visitante, quiero usar la barra superior para moverme a secciones de la landing rápidamente.                               |  2                        |
|    26   | US-26           | Acceder al registro o inicio desde landing        | Como visitante, quiero iniciar sesión o registrarme desde la barra superior.                                                    |  8                        |
|    27   | US-27           | Navegar desde el footer                           | Como visitante, quiero que los enlaces del pie de página funcionen para acceder a info adicional.                               |  1                        |
|    28   | US-28           | Selector de idioma en landing                     | Como visitante internacional, quiero cambiar idioma de la landing para entender la información.                                 |  3                        |
|    29   | US-29           | FAQ y centro de ayuda                             | Como usuario quiero acceso rápido a preguntas frecuentes y tutoriales para usar la app.                                         |  2                        |
|    30   | US-30           | Descargar certificado de cobertura                | Como usuario quiero descargar un certificado de cobertura para trámites o acreditación.                                         |  2                        |
|    31   | US-31           | Compartir evidencia múltiple                      | Como usuario quiero subir varias fotos o archivos en un reclamo para respaldar mi caso.                                         |  3                        |
|    32   | US-32           | Chat histórico por reclamo                        | Como usuario quiero ver el historial de mensajes relacionados a cada reclamo.                                                   |  2                        |
|    33   | US-33           | Evaluación al cierre del reclamo                  | Como usuario quiero calificar la resolución del reclamo para retroalimentación.                                                 |  2                        |
|    34   | TS-01           | Arquitectura backend modular y simple             | Definir arquitectura backend modular (monolito modular o microservicios ligeros) para usuarios, reclamos y pagos.               |  5                        |
|    35   | TS-02           | Modelado de base de datos relacional (Postgres)   | Diseñar esquema de BD para usuarios, pólizas, reclamos, evidencias y auditoría con migraciones.                                 |  5                        |
|    36   | TS-03           | API REST documentada y protegida (OpenAPI)        | Desarrollar endpoints REST para auth, póliza, reclamos y evidencias con documentación mínima.                                   |  5                        |
|    37   | TS-04           | Integración SSO universitario (opcional)          | Implementar opción para autenticación con credenciales universitarias (SSO) si la universidad lo permite.                       |  5                        |
|    38   | TS-05           | Pipeline CI básico (lint + tests)                 | Configurar pipeline en GitHub Actions/GitLab CI que corra lint y tests unitarios antes de merge.                                |  5                        |
|    39   | TS-06           | Almacenamiento de imágenes con URLs firmadas      | Implementar almacenamiento (S3/MinIO) con URLs firmadas y expiración para evidencias.                                           |  3                        |
|    40   | TS-07           | Motor de reglas liviano (JSON)                    | Implementar motor de reglas JSON para validaciones automáticas (fecha, tamaño imagen, metadatos).                               |  5                        |
|    41   | TS-08           | Sistema de notificaciones básico                  | Implementar servicio para push/email con templates que se conecte a eventos de la app.                                          |  5                        |
|    42   | TS-09           | Pagos: integración simple y seguras (webhooks)    | Integrar pasarela de pagos con tokenización y manejo de webhooks básicos.                                                       |  5                        |
|    43   | TS-10           | Logs y monitoreo accesible                        | Implementar logging estructurado y métricas básicas (errores, latencia) con dashboard simple.                                   |  3                        |
|    44   | US-01           | Iniciar borrador de salida             | Como cajero, quiero iniciar un borrador de salida para agrupar ítems de una venta antes de confirmarla.  |  5                        |
|    45   | US-02           | Gestionar ítems del borrador                           | Como cajero, quiero buscar productos y agregar/editar/retirar ítems con cantidades válidas sin impactar el stock aún.                                                     |  3                        |
|    46   | US-03           | Recuperación de contraseña                        | Como usuario quiero recuperar mi contraseña vía correo/OTP para restaurar acceso.                                               |  2                        |
|    47   | US-04           | Ver y descargar póliza                            | Como usuario quiero ver y descargar mi póliza en PDF para compartirla o archivarla.                                             |  3                        |
|    48   | US-05           | Selección y compra de plan                        | Como estudiante quiero elegir entre plan Básico y Premium y pagar en línea para activar cobertura.                              |  5                        |
|    49   | US-06           | Upgrade/downgrade de plan                         | Como usuario quiero cambiar entre planes para ajustar mi cobertura.                                                             |  2                        |
|    50   | US-07           | Contratación digital con documentos               | Como usuario quiero subir mi DNI y constancia universitaria para validar afiliación automáticamente.                            |  2                        |
|    51   | US-08           | Bloquear usuarios          | Como administrador, quiero poder desactivar usuarios para evitar accesos no autorizados.                                    |  5                        |
|    52   | US-09           | Ver lista de usuarios        | Como administrador, quiero ver un listado con todos los usuarios, roles y estado de cuenta para gestionar mejor el equipo.                                |  5                        |
|    53   | US-10           | Cambiar rol de un usuario         | Como administrador, quiero poder cambiar el rol de un usuario para ajustar sus responsabilidades dentro de la bodega/startup.                                |  3                        |
|    54   | US-11           | Auditoría de accesos                    | Como administrador, quiero consultar un historial de accesos de los usuarios para detectar intentos fallidos o acciones sospechosas.                                                 |  3                        |
|    55   | US-55           | Roles predefinidos                 | Como administrador, quiero contar con roles predefinidos (Administrador, Supervisor, Asistente) para acelerar la configuración inicial.                                         |  3                        |


# Capítulo IV: Product Design

## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines

**Branding**

<p align="justify">
Para nuestro logo, hemos implementado símbolos que reflejan el propósito central de StockTrack: la gestión eficiente y confiable del inventario. El logo de StockTrack proyecta una identidad sólida y práctica, alineada con su misión de brindar una solución tecnológica sencilla pero poderosa para la gestión de inventarios.
</p>

<p align="justify">
La caja representa de manera clara y universal el concepto de mercancía, almacenaje y stock, siendo el núcleo del negocio de bodegas y almacenes. El check verde simboliza control, seguridad y validación, transmitiendo la idea de que los productos están siempre bajo seguimiento y en orden.
</p>

<p align="justify">
El conjunto visual comunica simplicidad, confiabilidad y modernidad, reforzando el objetivo de StockTrack de ayudar a las bodegas a mantener su inventario bajo control, reducir errores y optimizar procesos.
</p>

<p align="justify">
La paleta de colores combina tonos cálidos (naranja/amarillo) que evocan dinamismo, accesibilidad y cercanía con el usuario, junto con un verde que transmite seguridad, éxito y confianza.
</p>

<p align="center">
  <img src="assets/Chapter-IV/logoStockTrack.png" alt="Logo" width="550">
</p>

**Tipografía**

<p align="justify">
- Fuente principal:
</p>
<p align="justify">
Nuestra fuente principal es Open Sauce, la cual aporta un estilo sólido y moderno que transmite fuerza, confiabilidad y profesionalismo. Perfecta para logotipos y títulos de alta relevancia, esta tipografía está diseñada para proyectar claridad y autoridad visual. Uso exclusivamente para el logo y títulos principales. Estilo: Mayúsculas, Bold, tamaño 64px.
</p>

<p align="justify">
- Fuente secundaria:
</p>
<p align="justify">
La fuente secundaria utilizada es Roboto, la cual aporta legibilidad y neutralidad en interfaces digitales. Su estilo limpio y curvo facilita la lectura continua en pantallas, ideal para textos extensos, descripciones y datos de inventario. Uso en párrafos, subtítulos, descripciones y etiquetas dentro de la aplicación.
</p>

<p align="justify">
- Jerarquía tipográfica: 
</p>
<p align="justify">
Tamaño variable según jerarquía de texto (H1: títulos principales (32px, bold), H2: subtítulos (24px, semibold), Párrafos: 16px, regular, Notas/etiquetas: 12px). Asegura una visualización cómoda y ordenada.
</p>

<p align="center">
  <img src="assets/Chapter-IV/typografiaStockTrack.png" alt="Tipografía" width="550">
</p>

**Colores**
 
<p align="justify">
La paleta de colores de StockTrack fue diseñada para transmitir energía, confianza y control en la gestión de inventarios.
</p>

<p align="justify">
-Colores principales: Naranja (#FFA22A): Representa dinamismo, accesibilidad y cercanía con el usuario evocando movimiento y acción. Amarillo (#FFC64D): Simboliza optimismo y rapidez, reforzando la idea de eficiencia en procesos. Se emplean como colores principales en el logo y en elementos destacados de la interfaz (botones de acción, iconografía principal). Verde (#2ECC71): Asociado al éxito, la validación y la seguridad. Refuerza el concepto de control y precisión en el stock, se reserva para estados positivos, alertas de stock correcto o validaciones (check, confirmaciones).
</p>

<p align="justify">
- Colores secundarios: Gris oscuro (#333333): Usado en tipografía y detalles, transmite seriedad y profesionalismo. Blanco (#FFFFFF): Representa simplicidad y claridad visual. Conforman la base de la tipografía y fondos, asegurando contraste y legibilidad en cualquier dispositivo.
</p>

<p align="center">
  <img src="assets/Chapter-IV/coloresStockTrack.png" alt="Colores" width="550">
</p>

**Spacing**

<p align="justify">
El espaciado juega un rol fundamental en la experiencia de usuario, asegurando legibilidad, orden y consistencia visual en todas las interfaces de StockTrack. Hemos definido un sistema de espaciado que será utilizado en la aplicación web.
</p>

| Elemento                        | Peso          | Tamaño          | Line height | Notas                                                    |
| :------------------------------ | :------------ | :-------------- | :---------- | :------------------------------------------------------- |
| **H1 (títulos)**                | Bold 700      | 48px            | 110% – 120% | Espaciado adicional de +0.5px para mayor impacto visual. |
| **H2 – H3 (secciones)**         | Semi-Bold 600 | 32px – 40px     | 120% – 130% | Claridad visual, adecuado para encabezados intermedios.  |
| **H4 – H5 (subtítulos)**        | Medium 500    | 24px            | 130% – 140% | Transiciones suaves entre secciones y subsecciones.      |
| **Body text (texto principal)** | Regular 400   | 16px – 18px     | 150% – 160% | Legible y cómodo para párrafos largos.                   |
| **Botones / CTAs**              | Semi-Bold 600 | 16px            | 120%        | Uso de mayúsculas opcionales para dar fuerza visual.     |

**Tono de comunicación**

<p align="justify">
- Lenguaje: Claro, cercano y profesional.    
</p>
<p align="justify">
- Formal/Casual: Casual, pero con respeto hacia los usuarios.
</p>
<p align="justify">
- Divertido/Serio: Equilibrio entre serio y entusiasta.
</p>
<p align="justify">
- Respetuoso/Irreverente: Respetuoso con un toque de humor ligero cuando sea apropiado.
</p>
<p align="justify">
- Entusiasta/Sereno: Entusiasta, motivando a los usuarios a participar en debates y predicciones.
</p>

<p align="center">
  <img src="assets/Chapter-IV/coloresStockTrack.png" alt="Colores" width="550">
</p>

### 4.1.2. Web Style Guidelines

<p align="justify">
DISEÑO RESPONSIVE:
</p>
<p align="justify">
- El diseño se adaptará automáticamente al tamaño de la pantalla.
</p>
<p align="justify">
COMPONENTES VISUALES: 
</p>
<p align="justify">
- Botones: Redondeados con 10px de radio. Cambian de color y tienen un efecto de sombra al usarse.
</p>
<p align="justify">
- Formularios: Cajas de texto con bordes suaves y sombreados ligeros, 40px. de alto.
</p>
<p align="justify">
- Links: En azul (#0000FF), subrayado. Subrayado, con color de cambio a azul oscuro  (#00008E).
</p>
<p align="justify">
- Navegación: Menú superior: Con enlaces a las principales secciones.
</p>


<p align="center">
  <img src="assets/Chapter-IV/webStyleStockTrack.png" alt="Colores" width="550">    
</p>

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

<div style="page-break-after: always;"></div>

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.

| Producto         | Propósito en el proyecto                                | Categoría                   | Ruta de descarga/acceso                                                          | Descripción                                                                                                        |
| ---------------- | ------------------------------------------------------- | --------------------------- | -------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| **OpenJDK**      | Ejecución y compilación de aplicaciones Java            | Software Development        | [https://jdk.java.net/](https://jdk.java.net/)                                   | Implementación de código abierto del JDK, necesaria para compilar y ejecutar aplicaciones backend con Spring Boot. |
| **Maven**        | Automatización de compilación y gestión de dependencias | Software Development        | [https://maven.apache.org/](https://maven.apache.org/)                           | Herramienta para gestionar dependencias y construir proyectos Java, ampliamente utilizada con Spring Boot.         |
| **Spring Boot**  | Desarrollo simplificado de microservicios y APIs REST   | Software Development        | [https://spring.io/projects/spring-boot](https://spring.io/projects/spring-boot) | Framework que acelera el desarrollo de servicios backend y APIs con configuración mínima.                          |
| **VS Code**      | Edición y desarrollo rápido de frontend                 | Software Development        | [https://code.visualstudio.com/](https://code.visualstudio.com/)                 | Editor ligero con extensiones para Angular, TypeScript, HTML y CSS, útil para desarrollo ágil.                     |
| **Angular CLI**  | Gestión del ciclo de vida de aplicaciones Angular       | Software Development        | [https://angular.io/cli](https://angular.io/cli)                                 | Interfaz de línea de comandos para generar y administrar componentes, servicios y módulos en Angular.              |
| **Postman**      | Pruebas y validación de APIs REST                       | Software Development        | [https://www.postman.com/](https://www.postman.com/)                             | Herramienta para probar endpoints y documentar APIs de forma colaborativa.                                         |
| **Figma**        | Diseño UI/UX y prototipado de interfaces                | Product UX/UI Design        | [https://figma.com/](https://figma.com/)                                         | Plataforma colaborativa para diseño de interfaces, integración de prototipos y handoff a desarrollo.               |
| **Lucidchart**   | Modelado de procesos y diagramas de arquitectura        | Product UX/UI Design        | [https://www.lucidchart.com/](https://www.lucidchart.com/)                       | Herramienta de diagramación para flujos de procesos, arquitecturas y casos de uso.                                 |
| **Firebase**     | Servicios de backend en la nube                         | Software Development        | [https://firebase.google.com/](https://firebase.google.com/)                     | Plataforma de Google que ofrece autenticación, base de datos NoSQL y hosting para el proyecto.                     |
| **GitHub**       | Control de versiones y repositorios del proyecto        | Project Management / DevOps | [https://github.com/](https://github.com/)                                       | Plataforma para almacenar el código fuente, gestionar ramas y colaborar en equipo.                                 |
| **Google Drive** | Gestión de documentación colaborativa                   | Documentation               | [https://drive.google.com/](https://drive.google.com/)                           | Almacenamiento y edición colaborativa de documentos, reportes y manuales del sistema.                              |


### 5.1.2. Source Code Management.

El proyecto StockTrack aplica GitHub como plataforma de control de versiones bajo el modelo GitFlow, lo que garantiza la trazabilidad del código, colaboración organizada y estabilidad en cada release.

GitHub: https://github.com/Inventiapp 

Ramas principales:
- main: Contiene la versión estable y en producción.
- develop: Rama de integración de nuevas funcionalidades.

Ramas secundarias:
- feature/<nombre> → Ramas temporales para funciones especificas 

Versionado: Se emplea Semantic Versioning (SemVer 2.0.0) en el formato MAJOR.MINOR.PATCH.

Todas las integraciones hacia develop o main requieren Pull Requests revisados por al menos un miembro del equipo.

### 5.1.3. Source Code Style Guide & Conventions.

El proyecto mantiene una guía de estilo de código uniforme para mejorar la legibilidad, mantenibilidad y colaboración en equipo.

Lenguaje: Todos los identificadores, comentarios y documentación estarán en inglés.

Backend (Java con Spring Boot)
- Nombres de clases → PascalCase (ej: StockService)
- Métodos y variables → camelCase (ej: calculateTotalStock)
- Constantes → UPPER_SNAKE_CASE (ej: MAX_STOCK_LIMIT)
- Paquetes organizados por funcionalidad (controller, service, repository, model).

Frontend (Angular con TypeScript, HTML, CSS)
- Estándares: Angular Style Guide
- Componentes y clases → PascalCase (ej: InventoryComponent)
- Archivos → kebab-case (ej: inventory-list.component.ts)
- Variables y métodos → camelCase
- Uso de programación reactiva con RxJS y principios SOLID en componentes.

HTML / CSS
- Archivos → kebab-case (ej: main-layout.css)
- Clases CSS → en inglés y descriptivas (ej: .inventory-card)
- Uso de etiquetas semánticas
  
Convenciones generales
- Commits claros y cortos bajo Conventional Commits.

### 5.1.4. Software Deployment Configuration.

## 5.2. Landing Page, Services & Applications Implementation.
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1.
#### 5.2.1.2. Aspect Leaders and Collaborators.
#### 5.2.1.3. Sprint Backlog 1.
#### 5.2.1.4. Development Evidence for Sprint Review.
#### 5.2.1.5. Execution Evidence for Sprint Review.
#### 5.2.1.6. Services Documentation Evidence for Sprint Review.
#### 5.2.1.7. Software Deployment Evidence for Sprint Review.
#### 5.2.1.8. Team Collaboration Insights during Sprint

<div style="page-break-after: always;"></div>

# Conclusiones
## Conclusiones y recomendaciones

<div style="page-break-after: always;"></div>

# Bibliografía

<div style="page-break-after: always;"></div>

# Anexos

Link del Repositorio del Informe: https://github.com/Inventiapp/workstation-markdown <br>
Link del Repositorio del Proyecto: <br>
Link del Repositorio del Backend: <br>
