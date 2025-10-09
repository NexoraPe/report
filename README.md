# COURSE PROJECT

<p align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <br>
    <strong>Facultad de Ingeniería</strong><br>
    <strong>Carrera de Ingeniería de Software</strong><br>
    <strong>Ciclo 2025-2</strong>
</p>

<p align="center">
  <strong>Código del curso: </strong>1ASI0729<br>
  <strong>Curso: </strong>Desarrollo de Aplicaciones Open Source
</p>

<p align="center">
  <strong>NRC: 7349</strong>
</p>

<p align="center">
    <strong>Profesor: </strong>Bautista Ubillús, Efraín Ricardo
</p>

<p align="center">
    <strong>Informe de Trabajo Final</strong>
</p>

<p align="center">
    <strong>Nombre del startup: </strong> NexoraPe
</p>

<p align="center">
    <strong>Nombre del producto:</strong> SafeWork
</p>

<div>
    <h3 align="center">Integrantes del equipo:</h3>
    </div>
<div>
     <table align="center">
        <tr>
            <th style="text-align:center;">Nombre</th>
            <th style="text-align:center;">Código</th>
        </tr>
        <tr>
            <td>Cacho Seminario, Diego Alonso</td>
            <td>u202223990</td>
        </tr>
        <tr>
            <td>Castro Sanchez, Amir Gabriel</td>
            <td>u202310680</td>
        </tr>
        <tr>
            <td>Tantaleán Mesta, Guillermo Fabián</td>
            <td>u202311958</td>
        </tr>
        <tr>
            <td>Vidal Castro, Miguel Angel</td>
            <td>u202314186</td>
        </tr>
    </table>
</div>

<p align="center">
    <strong>Octubre, 2025</strong>
</p>

---

# Registro de Versiones del Informe

| **Versión** | **Fecha** | **Autor** | **Descripción de modificación** |
|     ---     |     ---   |     ---   |             ---                 |
| 1.0 | 26/08/2025 | C. Diego, C. Amir, T. Guillermo, V. Miguel | Se implementó el diseño/esqueleto del informe sobre todas las secciones|
| 1.1 | 20/09/2025 | C. Diego, C. Amir, T. Guillermo, V. Miguel | Se implementaron diversos puntos del trabajo|
| 2.0 | 20/09/2025 | C. Diego, C. Amir, T. Guillermo, V. Miguel | Se corrigieron detalles de la versión anterior (enlaces, idioma de artefactos, etc), se agregó la planificación y desarrollo del sprint 2, se desplegó una nueva versión de la landing page y se desplegó una primera versión del frontend web app.|

---

# Project Report Collaboration Insights
**URL del repositorio para el Project Report:** [https://github.com/boafe/report](https://github.com/boafe/report)

**TB1**

<img width="911" height="825" alt="Captura de pantalla 2025-09-20 034403" src="https://github.com/user-attachments/assets/e2d3423e-5c75-4b98-acaa-dd80a9e20d86" />

**TP**


---

<div style="page-break-after: always;">

# Contenido

- [Carátula](#course-project)
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)

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
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)

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
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
      - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
      - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
    - [5.2.2. Sprint 2](#522-sprint-2)
      - [5.2.2.1. Sprint Planning 2](#5221-sprint-planning-2)
      - [5.2.2.2. Aspect Leaders and Collaborators](#5222-aspect-leaders-and-collaborators)
      - [5.2.2.3. Sprint Backlog 2](#5223-sprint-backlog-2)
      - [5.2.2.4. Development Evidence for Sprint Review](#5224-development-evidence-for-sprint-review)
      - [5.2.2.5. Execution Evidence for Sprint Review](#5225-execution-evidence-for-sprint-review)
      - [5.2.2.6. Services Documentation Evidence for Sprint Review](#5226-services-documentation-evidence-for-sprint-review)
      - [5.2.2.7. Software Deployment Evidence for Sprint Review](#5227-software-deployment-evidence-for-sprint-review)
      - [5.2.2.8. Team Collaboration Insights during Sprint](#5228-team-collaboration-insights-during-sprint)
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
</div>

---

# Student Outcome

<div style="page-break-after: always;">

El curso contribuye al cumplimiento del Student Outcome ABET:<br>
**ABET – EAC - Student Outcome 3**

**Criterio:** Capacidad de comunicarse efectivamente con un rango de audiencias.
En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro
del ABET – EAC - Student Outcome 3.

| Criterio específico | Acciones realizadas | Conclusiones |
|---------------------|---------------------|--------------|
| **Comunica oralmente con efectividad a diferentes rangos de audiencia** | **Cacho Seminario, Diego Alonso**<br>_**TB1**_<br>Realicé las correcciones necesarias dadas por mis compañeros respecto a los puntos con los que aporté para la TB1, además de subir correctamente mis aportes al repositorio en línea, respetando el formato requerido. <br>_**TP**_<br>Realice las correcciones necesarias de la entrega anterior (TB1) teniendo en cuenta el cambio en las secciones de los User Stories y Sprint 1, además para la entrega del TP aporte para el punto general del Sprint 2 y tmabién realice el endpoint de "profile" de la aplicación web. <br> <br> **Vidal Castro, Miguel Angel**<br>_**TB1**_<br> Investigué y obtuve información mediante las entrevistas para tener claro las funcionalidades que debería tener la aplicación y pueda cubrir las necesidades de los usuarios<br> <br>**Tantaleán Mesta, Guillermo Fabián** <br>**TB1** <br> Comunico de manera clara y adaptable mis ideas a diferentes audiencias; cuando hablo con trabajadores utilizo un lenguaje sencillo y práctico para resaltar la facilidad de uso y el beneficio inmediato de reportar incidentes, mientras que con personal de seguridad y directivos empleo un discurso más técnico y estratégico, destacando la trazabilidad, la reducción de riesgos legales y la optimización de procesos, asegurando así que mi mensaje sea comprendido e impactante en todos los niveles de la organización.<br> <br>**Castro Sanchez, Amir Gabriel** <br>**TB1** <br> Expliqué las ideas del proyecto adaptando mi lenguaje según la audiencia; con los trabajadores fui más sencillo y práctico, mientras que con personal de seguridad resalté los beneficios de control y trazabilidad.<br> | El grupo adaptó su forma de expresarse según la audiencia, usando un lenguaje sencillo con trabajadores y un enfoque más técnico con personal de seguridad y directivos, logrando transmitir el valor de SafeWork en distintos niveles.|
**Comunica por escrito con efectividad a diferentes rangos de audiencia** | **Cacho Seminario, Diego Alonso**<br>_**TB1**_<br>Realicé las correcciones necesarias dadas por mis compañeros respecto a los puntos con los que aporté para la TB1, además de subir correctamente mis aportes al repositorio en línea, respetando el formato requerido. <br>_**TP**_<br> Publique y subi correctamente los avances realizados para la entrega del Trabajo Parcial, además realice mis grabaciones y diapositivas para el video de exposición y para la presentación en clase. <br> <br> **Vidal Castro, Miguel Angel**<br>_**TB1**_<br> Investigué y obtuve información mediante las entrevistas para tener claro las funcionalidades que debería tener la aplicación y pueda cubrir las necesidades de los usuarios<br> <br> **Tantaleán Mesta, Guillermo Fabián** <br>**TB1** <br> Redacto documentos, reportes y materiales con un estilo estructurado y profesional que adapto según la audiencia; utilizo mensajes breves y fáciles de comprender para trabajadores, y presento información más detallada y analítica para el personal de seguridad y directivos, logrando que mi comunicación escrita sea efectiva en distintos rangos de la empresa y que contribuya tanto a la prevención como a la toma de decisiones estratégicas.<br> <br>**Castro Sanchez, Amir Gabriel** <br>**TB1** <br> Redacté mis aportes de manera clara y organizada, con mensajes simples para trabajadores y textos más técnicos para personal de seguridad y responsables de gestión.<br> | El equipo redactó documentos claros y diferenciados para cada público, priorizando la simplicidad con trabajadores y la profundidad con personal de seguridad, lo que permitió comunicar con precisión y profesionalismo.




<div style="page-break-after: always;">

---

# Capítulo I: Introducción

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
Somos NexoraPE, un equipo de estudiantes de la Universidad Peruana de Ciencias Aplicadas comprometidos con el desarrollo de soluciones tecnológicas que mejoren la seguridad laboral en el Perú.
Nuestra misión es ofrecer una plataforma digital que facilite el reporte y seguimiento de incidentes laborales en tiempo real, permitiendo a trabajadores y responsables de seguridad actuar de manera rápida y eficiente para prevenir accidentes y garantizar entornos de trabajo más seguros.
Nuestra visión es convertirnos en la herramienta líder en gestión de seguridad laboral en Latinoamérica, ayudando a las empresas a reducir riesgos, cumplir con normativas y proteger la integridad de sus trabajadores mediante el uso de tecnología accesible, intuitiva y confiable.

### 1.1.2. Perfiles de integrantes del equipo
| Foto | Nombre y Apellidos | Código de Estudiante | Carrera | Resumen de Conocimientos y Habilidades |
|------|--------------------|----------------------|---------|----------------------------------------|
| ![imgs](imgs/DiegoC.png) | **Diego Alonso Cacho Seminario** | u202223990 | Ingeniería de Software | Habilidades: Soy estudiante de Ingeniería de Software cursando el 7mo ciclo de mi carrera en la UPC y tengo 20 años. Me considero una persona tranquila y diligente, intentó realizar mis tareas y trabajos lo antes posible para evitar contratiempos en un futuro, especialmente si son actividades que consumen mucho tiempo. Como miembro de equipo buscaré ayudar a mis compañeros cuando lo necesiten, realizando además mis entregas lo más temprano posible. Habilidades en C++, C#, Python, Unity 2D/3D, html/css/js. |
| ![imgs](imgs/amir.png) | **Amir Gabriel Castro Sanchez** | u202310680 | Ingeniería de Software | Conocimientos en vue.js, c++, c#, .net. Aporta al equipo su capacidad de análisis crítico y compañerismo. |
| ![Foto 3](imgs/guillermo.JPG) | **Guillermo Fabián Tantaleán Mesta** | u202311958 | Ingeniería de Software | Especialista en desarrollo de aplicaciones móviles. Tengo conocimientos de ITSM, ISO 9000, etc.
| <img width="237" height="224" alt="Captura de pantalla 2025-09-20 044338" src="https://github.com/user-attachments/assets/20dd59c2-9771-4d65-a2d4-f7af16c1afea" /> | **Miguel Angel Vidal Castro** | u202314186 | Ingeniería de Software | Conocimientos en gestión de proyectos y optimización de procesos. Aporta al equipo su enfoque en eficiencia, coordinación y manejo de recursos. |

## 1.2. Solution Profile
SafeWork es una aplicación web diseñada para mejorar la gestión de la seguridad laboral en fábricas, almacenes y construcciones. Permite que los trabajadores reporten incidentes en tiempo real, evitando retrasos o la pérdida de información en papeleo. La plataforma asigna responsables de seguimiento, envía notificaciones inmediatas y facilita el monitoreo de cada caso hasta su resolución. Con esto, se garantiza mayor transparencia, rapidez y trazabilidad en los procesos de seguridad. SafeWork contribuye a reducir riesgos, fomentar una cultura de prevención y brindar a las empresas una base de datos útil para analizar y prevenir futuros incidentes.
### 1.2.1 Antecedentes y problemática
##### **¿Cuál es el problema? (What)**

En muchas empresas del sector industrial, logístico y de construcción, los incidentes laborales (accidentes, riesgos o fallas de seguridad) no se reportan de manera inmediata o se pierden en trámites burocráticos. Este retraso impide que se tomen acciones correctivas rápidas y expone a los trabajadores a mayores riesgos. Según la Superintendencia Nacional de Fiscalización Laboral **(SUNAFIL, 2024\)**, en el Perú se registraron más de 2,800 inspecciones relacionadas a accidentes de trabajo entre el 2023 y 2024, siendo 381 de ellos mortales. 

##### **¿Cuándo ocurre el problema? (When)**

El problema ocurre en el día a día de las operaciones de fábricas, almacenes y obras de construcción, especialmente en actividades de alto riesgo (uso de maquinaria, manipulación de materiales, transporte interno). Los incidentes suelen suceder en horarios de alta carga laboral o en turnos nocturnos, cuando la supervisión es limitada y los procedimientos de reporte se vuelven más lentos o poco efectivos.

##### **¿Dónde ocurre el problema? (Where)**

Esta problemática se presenta en empresas medianas y grandes del sector industrial, logístico y de construcción en el Perú, donde la alta rotación de personal y la falta de digitalización dificultan el seguimiento de incidentes. También es frecuente en organizaciones donde la gestión de la seguridad depende de reportes en papel o sistemas fragmentados, lo que genera pérdida de información y baja trazabilidad.

##### **¿A quién afecta el problema? (Who)**

El problema impacta directamente a los trabajadores, quienes enfrentan riesgos de salud y seguridad sin un sistema eficiente para reportarlos. También afecta al personal de seguridad y salud ocupacional, que debe gestionar incidentes sin herramientas modernas de control, y a las empresas, que se ven expuestas a sanciones legales, pérdida de productividad y altos costos asociados a accidentes laborales.

##### **¿Por qué sucede el problema? (Why)**

La causa principal es la dependencia de procesos manuales (formularios físicos, llamadas telefónicas o correos informales) que retrasan la comunicación. Además, existe una cultura de poca prevención, donde los reportes de incidentes menores no siempre se registran, lo que impide detectar patrones de riesgo a tiempo. A esto se suma la falta de plataformas digitales especializadas en seguridad laboral que integren reporte, seguimiento y análisis en un mismo sistema.

##### **¿Cómo sucede el problema? (How)**

Cuando ocurre un incidente, el trabajador debe llenar formularios en papel o informar verbalmente a un supervisor. Esta información tarda en llegar al área de seguridad, se puede extraviar o se registra de manera incompleta. El seguimiento depende de llamadas o correos aislados, sin trazabilidad clara ni métricas de control. Como resultado, los incidentes se resuelven tarde o se repiten por falta de medidas preventivas oportunas.

##### **¿Cuán grande es el impacto de este problema? (How much)**

El impacto es significativo en términos humanos, legales y económicos. Según el Ministerio de Trabajo y Promoción del Empleo **(MTPE)**, en el año 2022 se registraron 16,458 accidentes laborales, siendo los sectores más afectados la construcción, manufactura y minería. A nivel social, la falta de sistemas efectivos de gestión de incidentes perpetúa entornos de trabajo inseguros y afecta la calidad de vida de miles de trabajadores y sus familias.

### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements.
En el sector industrial, logístico y de construcción en el Perú, los trabajadores y responsables de seguridad enfrentan grandes dificultades para gestionar de manera eficiente los incidentes laborales que ocurren en el día a día. La mayoría de reportes se realizan en papel, llamadas o mensajes informales, lo cual retrasa la atención y genera pérdida de información importante.

Hemos observado que no existen herramientas digitales simples y accesibles que permitan a los trabajadores reportar incidentes en tiempo real y a las empresas darles seguimiento estructurado hasta su resolución. Esta falta de digitalización limita la prevención de riesgos y perpetúa entornos de trabajo inseguros.

¿Cómo podemos ayudar a las empresas y trabajadores en el Perú a reportar y gestionar incidentes laborales de forma rápida, organizada y transparente, promoviendo la prevención de accidentes, reduciendo riesgos y garantizando la seguridad en sus entornos de trabajo?

#### 1.2.2.2. Lean UX Assumptions.
**¿Quién es el usuario?**

Trabajadores de fábricas, almacenes y obras de construcción en el Perú, así como personal de seguridad y salud ocupacional que necesitan gestionar incidentes laborales de manera organizada y en tiempo real.

**¿Dónde encaja nuestro producto en su vida?**

SafeWork se integra como una herramienta esencial en la rutina laboral, permitiendo a los trabajadores reportar riesgos o accidentes de forma inmediata desde su celular, y al personal de seguridad darles seguimiento estructurado, reduciendo papeleo y asegurando que los incidentes no pasen desapercibidos.

**¿Qué problemas tiene nuestro producto y cómo se pueden resolver?**

* Posible resistencia al uso de tecnología por parte de algunos trabajadores.  
  → Solución: interfaz intuitiva, capacitaciones breves y soporte en campo.  
* Temor a represalias por reportar incidentes.  
  → Solución: opción de reportes anónimos y protocolos de confidencialidad.  
* Baja frecuencia de uso en ambientes donde no siempre ocurren incidentes.  
  → Solución: agregar funciones de checklist preventivo y recordatorios de seguridad.

**¿Cómo y cuándo es usado nuestro producto?**

El producto se utiliza en el momento exacto en que ocurre un incidente o cuando un trabajador detecta un riesgo. Además, es empleado diariamente por el personal de seguridad para monitorear reportes, asignar responsables y cerrar incidentes. También se puede usar en reuniones de seguridad para revisar métricas e historial de casos.

**¿Qué características son importantes?**

* Reporte de incidentes en tiempo real con foto, ubicación y descripción.  
* Panel de control para responsables de seguridad.  
* Historial de incidentes y estadísticas exportables.  
* Sistema de asignación de responsables y seguimiento de casos.  
* Opción de reportes anónimos.  
* Dashboard de indicadores de seguridad.  
* Multiplataforma: acceso desde web.

**¿Cómo debe verse nuestro producto y cómo comportarse?**

Debe tener un diseño claro, simple y profesional, con íconos fáciles de reconocer y colores asociados a seguridad **(verde, amarillo, rojo)**. Su comportamiento debe ser rápido y confiable, con notificaciones inmediatas y flujos de interacción que requieran pocos pasos para registrar un reporte. Debe comportarse de manera que transmita confianza, facilidad y utilidad real en el entorno laboral.

#### 1.2.2.3. Lean UX Hypothesis Statements.
* **Creemos que** al permitir a los trabajadores reportar incidentes laborales de manera inmediata y digital desde la web, lograremos que los responsables de seguridad los atiendan más rápido y se reduzca el tiempo de respuesta ante riesgos. **Sabremos que** hemos tenido éxito cuando al menos el 60% de los incidentes sean registrados en la plataforma dentro de las primeras 24 horas de ocurridos.

* **Creemos que** al implementar un panel web de seguimiento con asignación de responsables y estado de incidentes, lograremos mayor control y trazabilidad en la gestión de la seguridad laboral. **Sabremos que** hemos tenido éxito cuando más del 70% de los reportes registrados tengan un responsable asignado y un estado actualizado dentro de los primeros 3 días.

* **Creemos que** ofrecer un historial accesible de incidentes con estadísticas y reportes ayudará a las empresas a tomar decisiones preventivas más efectivas. **Sabremos que** hemos tenido éxito cuando al menos el 80% de los usuarios responsables de seguridad accedan al módulo de reportes y estadísticas al menos una vez por semana.

#### 1.2.2.4. Lean UX Canvas.
| 1. Businesses Problem | 5. Solutions | 2. Businesses Outcomes |
|-----------------------|--------------|-------------------------|
| Actualmente, muchas empresas en Perú gestionan incidentes laborales de forma manual y desorganizada, lo que dificulta la prevención de accidentes y el cumplimiento normativo. No existen muchas soluciones que sean digital accesible y estandarizada que permitan reportar, organizar y dar seguimiento a estos incidentes de forma eficiente. Esta falta de herramientas genera riesgos operativos, pérdida de información y baja transparencia en los entornos laborales. | SafeWork es una aplicación web que permite a los trabajadores reportar incidentes, riesgos y fallas de seguridad de forma inmediata desde sus dispositivos móviles. El personal de seguridad recibe estos reportes, asigna responsables, da seguimiento y cierra los casos una vez resueltos. La plataforma también almacena un historial de incidentes para generar reportes y estadísticas que faciliten la toma de decisiones preventivas. <br><br>Características clave:<br>- Reporte de incidentes en tiempo real con foto, ubicación y descripción<br>- Panel de control para responsables de seguridad<br>- Historial de incidentes y estadísticas exportables<br>- Sistema de asignación de responsables y seguimiento de casos<br>- Opción de reportes anónimos<br>- Panel visual con indicadores clave de seguridad<br>- Acceso multiplataforma (web y móvil) (web por ahora) | Sabremos que estamos resolviendo el problema cuando las empresas comiencen a reportar incidentes laborales a través de la plataforma de forma consistente, reduciendo el tiempo de hacer un reporte en al menos un 40%. Esperamos ver un aumento en la trazabilidad de los casos, una mejora en el cumplimiento normativo, y una adopción de la app sostenida por parte de empresas medianas, con una tasa de retención superior al 70% en los primeros seis meses. |

| 3. Users |
|----------|
| Nos enfocaremos inicialmente en tres tipos de usuarios: (1) trabajadores operativos en fábricas, almacenes y obras de construcción que necesitan reportar incidentes de forma rápida y sencilla; (2) personal de seguridad y salud ocupacional que gestiona y da seguimiento a los reportes; y (3) gerentes o jefes de área que aprueban la adopción del sistema y supervisan su uso. Estos perfiles son clave para garantizar la adopción, configuración y uso efectivo de la aplicación. |

| 4. User Outcomes & Benefits |
|-----------------------------|
| Los usuarios buscan nuestra solución para reducir el tiempo y la complejidad al reportar incidentes laborales, lo que les permite enfocarse en tareas más importantes y disminuir el estrés. El personal de seguridad obtiene una herramienta organizada para clasificar y gestionar incidentes, mejorando la trazabilidad y la respuesta. Los gerentes logran mayor visibilidad y control sobre los riesgos, lo que se traduce en decisiones más efectivas y ahorro económico. Observamos como cambio de comportamiento una mayor frecuencia en los reportes, tiempos de respuesta más cortos y una disminución en incidentes repetitivos. |

| 6. Hypotheses |
|----------------|
| - Creemos que se logrará una reducción del tiempo de hacer un reporte en al menos 40% si los trabajadores operativos pueden reportar incidentes rápidamente mediante la función de reporte en tiempo real con foto, ubicación y descripción.<br>- Creemos que se mejorará la trazabilidad de los casos si el personal de seguridad y salud ocupacional obtiene mayor control mediante el panel de gestión de incidentes.<br>- Creemos que se logrará un mejor cumplimiento normativo de riesgos si los gerentes pueden visualizar métricas clave mediante el panel de indicadores de seguridad.<br>- Creemos que se alcanzará una adopción sostenida por parte de empresas medianas en al menos 70% de los casos si los usuarios pueden acceder fácilmente a la plataforma mediante la versión web. |

| 7. What's the most important thing we need to learn first? | 8. What's the least amount of work we need to do to learn the next most important thing? |
|------------------------------------------------------------|--------------------------------------------------------------------------------------------|
| ¿Realmente los trabajadores usarán la función de reporte en tiempo real en el momento del incidente? | Validar si los trabajadores están dispuestos y son capaces de reportar incidentes en tiempo real, sin necesidad de construir el sistema completo:<br><br>- Prototipo interactivo (sin backend): Simulación de la función de reporte en una app o mockup clickable<br>- Video demo + encuesta: Mostrar cómo funciona la aplicación y recolectar feedback |
## 1.3. Segmentos objetivo.

- ##### **Personal encargado de la tramitación de accidentes e incidentes laborales**

Profesionales y responsables dentro de las áreas de seguridad ocupacional, recursos humanos o jefaturas inmediatas, que tienen como función reportar, registrar y dar seguimiento a accidentes o incidentes en el centro laboral.

**Características:**

* Buscan herramientas digitales que simplifiquen el proceso de reporte y documentación.  
* Necesitan reducir errores y duplicidad en la información al gestionar casos.  
* Valoran contar con un sistema centralizado que facilite la comunicación con las entidades competentes.

- ##### **Trabajadores afectados por accidentes o incidentes laborales**

Colaboradores que han sufrido un accidente o incidente en su centro de trabajo y requieren un seguimiento adecuado de su caso.

**Características:**

* Necesitan acceso rápido y claro a la información sobre el estado de su reporte.  
* Buscan confianza y transparencia en el proceso de registro y resolución de incidentes.  
* Valoran plataformas que les permitan sentirse acompañados y respaldados durante la gestión de su caso.

---

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores.
Los competidores que hemos identificado para SafeWork son los siguientes:
CetAPP GO: Solución móvil especializada en la gestión de seguridad, salud y medio ambiente (HSE), con enfoque en grandes corporaciones. Destaca por su escalabilidad, rendimiento y operación sin instalación.
Laus: Plataforma integral para la gestión de Seguridad y Salud en el Trabajo (SST), orientada al cumplimiento normativo y automatización de procesos como capacitaciones, reportes de incidentes y control de equipos de protección.
Work Wallet: Aplicación todo-en-uno para la gestión digital de procesos de seguridad laboral, que incluye reportes de accidentes, auditorías, permisos de trabajo y control de personal, con enfoque en flexibilidad y personalización

### 2.1.1. Análisis competitivo.

| Competitive Analysis Landscape  |  |  |  |  |  |
| :---- | :---- | ----- | ----- | ----- | ----- |
| ¿Por qué llevar a cabo este análisis? |  | Con el objetivo de identificar las ventajas competitivas de SafeWork ante los competidores y definir las estrategias competitivas frente al mercado de seguridad en el trabajo. |  |  |  |
| Servicio |  | **SafeWork** ![imgs](imgs/SafeWorkLogoNoBackground.png) | **CetApp GO** ![imgs](imgs/CetApp-GO.png) | **Laus** ![imgs](imgs/Laus.png) | **Work Wallet** ![imgs](imgs/WorkWallet.png) |
|  Perfil | Overview | Plataforma web que centraliza el reporte, seguimiento y resolución de incidentes laborales, con un enfoque en simplicidad, accesibilidad y trazabilidad para empresas medianas y pequeñas. | Herramienta digital de gestión de Seguridad y Salud en el Trabajo (SST), utilizada para registrar, investigar y hacer seguimiento de incidentes laborales. | Software especializado en prevención de riesgos laborales y gestión de salud ocupacional, con módulos de formación, inspecciones y auditorías. | Plataforma internacional enfocada en comunicación de seguridad y gestión de incidentes en el lugar de trabajo. Incluye reportes en tiempo real, auditorías y checklists móviles. |
|  | Ventaja competitiva ¿Qué valor ofrece a los clientes?  | Valor para clientes: Permite a trabajadores y responsables registrar y dar seguimiento en tiempo real a los incidentes, con reportes claros y exportables. Accesible y económico frente a soluciones internacionales. | Valor para clientes: Cumplimiento con normativa nacional de SST, mayor formalización de los procesos y reducción del papeleo. | Valor para clientes: Ofrece una solución integral de prevención, combinando gestión de incidentes con capacitación y control de cumplimiento. | Valor para clientes: Accesibilidad móvil y comunicación inmediata, lo que agiliza la reacción en incidentes y refuerza la cultura de seguridad. |
| Perfil de Marketing | Mercado Objetivo | Empresas medianas o pequeñas, especialmente de manufactura, logística y construcción que requieren cumplir con normativas de seguridad sin grandes costos. | Empresas nacionales que deben cumplir con la Ley de Seguridad y Salud en el Trabajo en Perú y Latinoamérica. | Corporaciones y empresas con alta exposición a riesgos laborales, interesadas en centralizar prevención, formación y control. | Empresas globales que buscan mejorar la comunicación interna en seguridad y reducir incidentes mediante apps móviles. |
|  | Estrategias de marketing | Alianzas con gremios empresariales, campañas educativas en LinkedIn y webinars sobre SST accesible. | Posicionamiento a través de consultoras en SST y capacitaciones empresariales. | Marketing institucional, presencia en ferias de seguridad laboral, venta directa a grandes clientes. | Campañas digitales en mercados internacionales, uso de casos de éxito en grandes organizaciones. |
|  Perfil de productos | Productos & Servicios | Registro digital de incidentes y accidentes laborales. Panel de seguimiento para responsables de seguridad. Historial de casos por trabajador y por área. Sistema de asignación de responsables y seguimiento de casos. Opción de reportes anónimos. Dashboard de indicadores de seguridad. | Registro y notificación de accidentes e incidentes en cumplimiento con normativas locales. Módulos de investigación y análisis de causas. Gestión documental para SST (informes, actas, auditorías). Generación de indicadores y estadísticas de seguridad. Integración con capacitaciones en seguridad. | Gestión integral de prevención de riesgos laborales. Módulo de inspecciones y auditorías internas. Capacitación online para trabajadores. Registro de incidentes y enfermedades ocupacionales. Herramientas de cumplimiento normativo internacional. | Reporte de incidentes en tiempo real desde dispositivos móviles. Auditorías y checklists digitales. Comunicación instantánea entre trabajadores y responsables vía app. Módulo de inducción digital para trabajadores nuevos. Herramientas de análisis de tendencias en seguridad. |
|  | Precios & Costos  | Modelo SaaS accesible, con planes escalonados según número de usuarios y nivel de funcionalidad. | Suscripción por licencia anual, con precios adaptados al tamaño de la empresa. | Modelo de licencias empresariales con costo elevado, diseñado para corporaciones. | Planes por suscripción mensual, con precios diferenciados según cantidad de usuarios activos. |
|  | Canales de distribución (Web y/o Móvil) | Plataforma web responsive accesible desde cualquier navegador. | Plataforma web y aplicación móvil. | Plataforma web con módulos móviles. | Web y aplicación móvil (iOS y Android). |
|  Análisis SWOT | Fortalezas | Simplicidad y accesibilidad para PYMEs, costos bajos, enfoque local. Base de usuarios inicial limitada, falta de reputación consolidada. Creciente necesidad de digitalizar reportes en PYMEs. Competidores internacionales más robustos, cambios regulatorios. | Adaptación al marco normativo peruano y latinoamericano, experiencia en SST. Interfaz más técnica, menos intuitiva para el trabajador promedio. Demanda de cumplimiento legal en empresas medianas. Aparición de soluciones más fáciles de usar. | Solución integral que combina formación, prevención e incidentes. Alto costo, accesible solo para empresas grandes. Expansión en corporaciones multinacionales. Pérdida de atractivo frente a opciones más económicas. | Fuerte enfoque móvil y comunicación instantánea. Dependencia de conectividad móvil, curva de aprendizaje para usuarios. Crecimiento del trabajo remoto y digitalización de SST. Competencia de apps locales adaptadas al marco legal de cada país. |
|  | Debilidades | Simplicidad y accesibilidad para PYMEs, costos bajos, enfoque local. Base de usuarios inicial limitada, falta de reputación consolidada. Creciente necesidad de digitalizar reportes en PYMEs. Competidores internacionales más robustos, cambios regulatorios. | Adaptación al marco normativo peruano y latinoamericano, experiencia en SST. Interfaz más técnica, menos intuitiva para el trabajador promedio. Demanda de cumplimiento legal en empresas medianas. Aparición de soluciones más fáciles de usar. | Solución integral que combina formación, prevención e incidentes. Alto costo, accesible solo para empresas grandes. Expansión en corporaciones multinacionales. Pérdida de atractivo frente a opciones más económicas. | Fuerte enfoque móvil y comunicación instantánea. Dependencia de conectividad móvil, curva de aprendizaje para usuarios. Crecimiento del trabajo remoto y digitalización de SST. Competencia de apps locales adaptadas al marco legal de cada país. |
|  | Oportunidades | Simplicidad y accesibilidad para PYMEs, costos bajos, enfoque local. Base de usuarios inicial limitada, falta de reputación consolidada. Creciente necesidad de digitalizar reportes en PYMEs. Competidores internacionales más robustos, cambios regulatorios. | Adaptación al marco normativo peruano y latinoamericano, experiencia en SST. Interfaz más técnica, menos intuitiva para el trabajador promedio. Demanda de cumplimiento legal en empresas medianas. Aparición de soluciones más fáciles de usar. | Solución integral que combina formación, prevención e incidentes. Alto costo, accesible solo para empresas grandes. Expansión en corporaciones multinacionales. Pérdida de atractivo frente a opciones más económicas. | Fuerte enfoque móvil y comunicación instantánea. Dependencia de conectividad móvil, curva de aprendizaje para usuarios. Crecimiento del trabajo remoto y digitalización de SST. Competencia de apps locales adaptadas al marco legal de cada país. |
|  | Amenazas | Simplicidad y accesibilidad para PYMEs, costos bajos, enfoque local. Base de usuarios inicial limitada, falta de reputación consolidada. Creciente necesidad de digitalizar reportes en PYMEs. Competidores internacionales más robustos, cambios regulatorios. | Adaptación al marco normativo peruano y latinoamericano, experiencia en SST. Interfaz más técnica, menos intuitiva para el trabajador promedio. Demanda de cumplimiento legal en empresas medianas. Aparición de soluciones más fáciles de usar. | Solución integral que combina formación, prevención e incidentes. Alto costo, accesible solo para empresas grandes. Expansión en corporaciones multinacionales. Pérdida de atractivo frente a opciones más económicas. | Fuerte enfoque móvil y comunicación instantánea. Dependencia de conectividad móvil, curva de aprendizaje para usuarios. Crecimiento del trabajo remoto y digitalización de SST. Competencia de apps locales adaptadas al marco legal de cada país. |

### 2.1.2. Estrategias y tácticas frente a competidores.
**SafeWork** aplicará una estrategia de diferenciación enfocada en la simplicidad de uso y en la adaptación al contexto local de seguridad laboral, destacando por su sistema de reportes inmediatos, trazabilidad clara de casos y generación automática de informes. Frente a competidores como CetApp GO, Laus y Work Wallet, SafeWork se posiciona como una solución ágil, accesible y diseñada para pequeñas y medianas empresas, donde el cumplimiento normativo y la prevención de riesgos son críticos, pero los recursos suelen ser limitados.

El valor de SafeWork está en ofrecer una plataforma ligera y directa, con un flujo de reporte optimizado, lo que reduce los tiempos de respuesta y minimiza la subnotificación de incidentes. Además, integra un chat interno para comunicación rápida, lo cual no está plenamente desarrollado en soluciones competidoras.

Aprovechará las debilidades de otros sistemas como su alta complejidad, precios elevados o la poca adaptación a la realidad de las PYMEs locales. Para mitigar amenazas como la resistencia al cambio tecnológico o la competencia de grandes soluciones internacionales, SafeWork implementará capacitaciones digitales simples, un modelo de precios accesible y un acompañamiento continuo al cliente, reforzando la confianza y el uso sostenido de la herramienta.

## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.

**Segmento objetivo 1: Personal encargado de la tramitación de accidentes e incidentes laborales**

* ¿Cuál es tu nombre completo?

* ¿Cuántos años tienes?

* ¿En dónde vives?

* ¿Cuál es tu cargo dentro de la empresa?

* ¿Cada cuánto tiempo recibes reportes de incidentes laborales?

* ¿Qué medios utilizan actualmente para registrar y dar seguimiento a los incidentes?

* ¿Qué problemas encuentras en el proceso actual de reporte y documentación de incidentes?

* ¿Has tenido casos en los que los reportes se pierden o llegan tarde? ¿Qué consecuencias generó?

* ¿Qué características crees que debería tener una herramienta digital para ayudarte a gestionar incidentes de manera más eficiente?

* ¿Te resultaría útil que la plataforma genere reportes automáticos y consolidados para auditorías o inspecciones?

* ¿Qué tan importante es para ti poder asignar responsables y dar seguimiento en tiempo real a la resolución de un incidente?

**Segmento objetivo 2: Trabajadores afectados por accidentes o incidentes laborales**

* ¿Cuál es tu nombre completo?

* ¿Cuántos años tienes?

* ¿En dónde vives?

* ¿En qué área o puesto trabajas actualmente?

* ¿Has tenido algún accidente o incidente laboral en tu centro de trabajo? ¿Cómo lo reportaste?

* ¿Qué tan fácil o difícil fue reportarlo en ese momento?

* ¿Alguna vez sentiste que tu reporte no fue atendido o quedó sin seguimiento?

* ¿Qué tanto confías en el proceso actual que tiene tu empresa para registrar y resolver incidentes laborales?

* ¿Qué tan importante sería para ti contar con una plataforma donde pudieras reportar un incidente de forma rápida y saber el estado de tu caso en tiempo real?

* ¿Qué información te gustaría poder registrar en un reporte digital (fotos, ubicación, descripción, testigos, etc.)?

* ¿Crees que una plataforma así te daría más confianza de que tu seguridad y bienestar están siendo tomados en serio?

* ¿Qué temores o preocupaciones tendrías al usar una herramienta digital para reportar incidentes?

### 2.2.2. Registro de entrevistas.

**Segmento objetivo \#1: Personal encargado de la tramitación de accidentes e incidentes laborales** 

Entrevistado N°1: Miguel Angel Saucedo Zambrano

* Sexo: Masculino  
* Edad: 34 años  
* Ubicación en la que vive: Santiago de Chile

Acerca de la entrevista:

* Instante en el que inicia: 0:00
* Duración: 3:24

Resumen:

Para Miguel, debido a que en su puesto de trabajo se realizan estos informes de manera manual en papel, tienen problemas debido a que en ocasiones estos formularios llegan incompletos, con el papel dañado o sin ciertos datos que no permiten realizar un correcto seguimiento, además a tenido varios casos en los que se pierden los informes lo que lleva a faltas de coordinación e incluso a más riesgos en un futuro ya que los problemas no son solucionados como deberían.

![imgs](imgs/EntrevistaSeg1Miguel.png)

Entrevistado N°2: Nicole Requena Saiwa

* Sexo: Femenino   
* Edad: 27 años  
* Ubicación en la que vive: Ciudad de Arequipa

Acerca de la entrevista:

* Instante en el que inicia: 3:33
* Duración: 2:53

Resumen:

En el puesto de trabajo de Nicole, utilizan métodos tradicionales para completar los formularios de incidentes como a mano en una hoja de papel o en ocasiones dentro de hojas de excel. Considera que es difícil consolidar todos los datos para el informe ya que muchas veces estos informes llegan incompletos o son perdidos antes de ser terminados. Finalmente cree que una aplicación similar a SafeWork podría ayudarle mucho en su posición. 

![imgs](imgs/EntrevistaSeg1Nicole.png)

Entrevistado N°3: Luis Alberto Paredes

* Sexo: Masculino  
* Edad: 24  
* Ubicación en la que vive: San Martín de Porres

Acerca de la entrevista:

* Instante en el que inicia: 6:29 
* Duración: 4:55

Luis Alberto es un asistente de seguridad en una empresa de construcción y comenta que recibe reportes de accidentes laborales casi semanalmente, la mayoría de estos siendo casos pequeños. En su empresa, utilizan excel o medios comunicativos como WhatsApp para reportar estos incidentes. Considera que tienen problemas ya que los reportes no siempre llegan completos lo que lleva a un difícil seguimiento. Cree que una aplicación como SafeWork si le ayudaria bastante en su área de trabajo.

![imgs](imgs/EntrevistaSeg1Luis.png)

**Segmento objetivo \#2: Trabajadores afectados por accidentes o incidentes laborales**

Entrevistada N°1: Mario André Cacho Seminario

* Sexo: Masculino  
* Edad: 22  
* Ubicación en la que vive: Lima, Surco

Acerca de la entrevista:

* Instante en el que inicia: 11:29
* Duración: 3:20

Resumen:  
Para Mario, cuando pasó por este pequeño accidente durante sus horas de trabajo, lo más complicado para él fue realizar el reporte ya que el sistema presentaba fallas y se demoraba en responder, por ello se le fue difícil subir la información para su reporte. Considera además que una plataforma como SafeWork podría ser muy útil cuando no puedes depender de solo el servicio que tiene tu empresa ya que en ocasiones pueden ocurrir problemas como le ocurrió a él.

![imgs](imgs/EntrevistaSeg2Mario.png)

Entrevistado N°2: Sebastián De Las Casas Latour

* Sexo: Masculino  
* Edad: 21  
* Ubicación en la que vive: Lima, Surco

Acerca de la entrevista:

* Instante en el que inicia: 14:52  
* Duración: 5:26

Resumen:

Para Sebastián una plataforma que le permita organizar y mantener un seguimiento de los incidentes o accidentes podría ser de gran ayuda en caso pase por un problema similar en un futuro. Si bien considera que no tuvo problemas al reportar los incidentes ya que la empresa lo manejo de una manera correcta, indica que si hubiera tenido una herramienta similar a SafeWork, el proceso hubiera sido más rápido, no se habría encontrado confundido de qué hacer cuando sufrió el accidente y podría tener un registro de lo que ocurre en caso se tenga que realizar algún seguimiento.

![imgs](imgs/EntrevistaSeg2Sebastian.png)

Entrevistado N°3: Diego Alarcon Rivas

* Sexo: Masculino  
* Edad: 22  
* Ubicación en la que vive: San Juan de Lurigancho

Acerca de la entrevista:

* Instante en el que inicia: 20:22
* Duración: 5:10

Resumen:

Diego trabaja actualmente en el área de almacenamiento, es un ayudante de logística y si ha tenido accidentes anteriormente en este puesto. En su trabajo anotan los incidentes/accidentes que ocurren en los cuadernos para llevar un seguimiento simple de los problemas que ocurren. Debido a que no había un formato claro para el reporte, se le complicó llenar con la información que consideraba importante. Considera que SafeWork podría ayudar bastante en su puesto de trabajo para llevar una lista de los incidentes y poder seguirlos correctamente.

![imgs](imgs/EntrevistaSeg2Diego.png)

El video completo de las entrevistas puede ser visualizado en el siguiente link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202223990_upc_edu_pe/EXompS5DmExMneyAoAHRKAgBHiOofaiA4tbpoGPA-7fmFQ?e=NXfew1 [https://upcedupe-my.sharepoint.com/personal/u202223990_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202223990_upc_edu_pe%2FDocuments%2Fupc-pre-202520-1asi0729-7349-SafeWork-needfinding-sprint-1%2Emp4&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E3a8e9694-9835-42b7-a44b-12e8189e3111]

### 2.2.3. Análisis de entrevistas.
De acuerdo con la información recopilada de las entrevistas, realizamos el siguiente análisis de entrevistas:

* **Segmento objetivo \#1:**

**Hallazgos:**
**Uso de métodos informales:** actualmente se emplean Excel, WhatsApp o formularios en papel para recibir y procesar reportes (caso Luis, Nicole y Miguel).  
**Reportes incompletos:** la información llega con datos faltantes, lo que complica el seguimiento adecuado de los casos.  
**Pérdida de información:** los formularios físicos o archivos mal gestionados se extravían o se dañan, generando riesgos de coordinación.  
**Dificultad en la consolidación de datos:** procesar la información de forma manual o dispersa hace que elaborar informes sea lento y poco confiable.  
**Valor percibido de SafeWork:** todos coinciden en que una aplicación digital centralizada facilitaría enormemente su trabajo, asegurando reportes completos y organizados.

* **Segmento objetivo \#2:** 

**Hallazgos:**  
**Problemas técnicos**: los sistemas actuales pueden fallar o ser poco confiables (caso Mario).  
**Falta de claridad**: los trabajadores no siempre saben qué hacer en el momento del accidente (caso Sebastián).  
**Valor percibido de SafeWork**: ambos coinciden en que una plataforma externa facilitaría el proceso, ya sea por ser más confiable o por ofrecer seguimiento claro.  
**Necesidad de accesibilidad**: los trabajadores quieren poder reportar y dar seguimiento de manera rápida, sencilla y sin depender exclusivamente del área de la empresa.

* Conclusiones de ambos segmentos:

El segmento de personal SST enfrenta problemas recurrentes de desorganización, pérdida de información y falta de uniformidad en los reportes debido al uso de métodos manuales o informales. Existe una clara percepción de que una herramienta como SafeWork podría optimizar la gestión de reportes, mejorar la trazabilidad y reducir riesgos derivados de información incompleta o extraviada.

Por otro lado, para el segmento 2, las entrevistas muestran que, aunque la gestión interna de accidentes puede funcionar en algunos casos, existen fallas técnicas y vacíos en la experiencia del trabajador que generan frustración o confusión. Una herramienta como SafeWork representa una oportunidad clara para mejorar la confiabilidad del proceso de reporte frente a fallas en los sistemas empresariales, guiar al trabajador en los pasos a seguir inmediatamente después del accidente y por último brindar trazabilidad y registro histórico, aumentando la seguridad y confianza de los trabajadores en la gestión de sus incidentes.

## 2.3. Needfinding.
Se presentan en esta sección los resultados del análisis de la información recolectada de los segmentos objetivos.

**Segmento objetivo \#1: Personal encargado de la tramitación de accidentes e incidentes laborales** 

* Motivaciones Principales:  
- Garantizar un registro completo y confiable de los incidentes laborales.

- Reducir la carga administrativa que generan los reportes manuales.
  
- Mejorar el seguimiento de los casos para prevenir futuros accidentes.
   
- Cumplir con las normativas de seguridad y salud en el trabajo.

* Problemas Identificados:  
- Reportes incompletos que dificultan el análisis posterior.
  
- Uso de medios informales (WhatsApp, papel, Excel) que generan desorden.
  
- Pérdida de información por documentos extraviados o dañados.
  
- Dificultad en consolidar datos para elaborar informes y reportes oficiales.
  
- Falta de trazabilidad en los procesos de gestión de incidentes.

* Requerimientos para una plataforma ideal:  
- Un sistema digital centralizado y seguro para registrar los incidentes.
  
- Formularios estructurados que obliguen a completar todos los campos necesarios.
  
- Posibilidad de almacenar y consultar reportes anteriores de forma organizada.
  
- Herramientas para consolidar automáticamente los datos y generar informes.
  
- Interfaz simple y accesible para que todo el personal pueda usarla fácilmente.

**Segmento objetivo \#2: Trabajadores afectados por accidentes o incidentes laborales**

* Motivaciones Principales:  
- Reportar rápidamente un accidente/incidente para recibir ayuda inmediata.

- Garantizar que su caso sea atendido y no quede olvidado en trámites internos.

- Tener claridad y orientación sobre qué hacer en el momento del accidente.

- Mantener un registro personal de los accidentes/incidentes sufridos.

- Confiar en que su información será tratada de forma segura y transparente.

* Problemas Identificados:  
- Sistemas internos de la empresa que presentan fallas técnicas o lentitud al momento de reportar (ejemplo Mario).

- Falta de claridad sobre los pasos a seguir después de un accidente (ejemplo Sebastián).

- Procesos burocráticos que generan demora en la atención.

- Ausencia de un registro personal accesible de los casos.

- Dependencia total de las áreas internas de la empresa, lo que genera vulnerabilidad cuando fallan sus sistemas.

* Requerimientos para una plataforma ideal:  
- Interfaz simple y rápida que permita registrar un reporte en pocos pasos.

- Guía paso a paso para que el trabajador sepa qué hacer en cada situación.

- Confiabilidad técnica (sin fallas, carga ligera, accesible desde web y móvil).

- Funcionalidad de seguimiento en tiempo real para ver el estado del caso.

- Historial de reportes accesible en el perfil del usuario.

- Seguridad de datos que brinde confianza en el manejo de la información sensible.

### 2.3.1. User Personas.
**User Persona del Personal encargado de la tramitación de accidentes e incidentes laborales:** 
![imgs](imgs/CarlaMendez-UserPersona.png)

**User Persona del Trabajador afectado por accidentes o incidentes laborales:**  
![imgs](imgs/JoseRamirez-UserPersona.png)

### 2.3.2. User Task Matrix.
En esta se presenta el user task matrix, herramienta centrada en los segmentos objetivos que nos permitirá identificar las tareas y objetivos claves de los usuarios.

| USER TASK  | Carla Méndez |  | José Ramírez |  |
| ----- | :---: | :---: | :---: | :---: |
|  | **Frequency** | **Importance** | **Frequency** | **Importance** |
| Registrar un accidente o incidente | Always | High | Sometimes | High |
| Revisar reportes de trabajadores | Often | High | Rarely | Medium |
| Revisar reportes de trabajadores | Always | High | Often | High |
| Generar informes para auditorías o gerencia | Often | High | Never | Low |
| Acceder al historial de incidentes pasados | Often | Medium | Sometimes | Medium |
| Recibir notificaciones sobre actualizaciones de casos | Always | High | Always | High |
| Subir evidencia (fotos, documentos, videos) | Sometimes | High | Often | High |
| Consultar medidas correctivas aplicadas | Often | High | Sometimes | High |
| Comunicarme con responsables (supervisor, médico laboral, etc.) | Often | High | Sometimes | High |
| Reportar condiciones inseguras (antes que un accidente ocurra) | Sometimes | High | Often | High |

### 2.3.3. User Journey Mapping.
Ambos Journey Maps pueden ser visualizados desde este enlace: [https://www.figma.com/design/OA8KMXSmn9KhEPqj9qRM0w/Journey-Map---Open-Source-2025-2?node-id=1-1315\&t=8xYjnKyJQwllgqro-1](https://www.figma.com/design/OA8KMXSmn9KhEPqj9qRM0w/Journey-Map---Open-Source-2025-2?node-id=1-1315&t=8xYjnKyJQwllgqro-1) 

User Journey Mapping Personal encargado de la tramitación de accidentes e incidentes laborales:  
![imgs](imgs/JourneyMap1.jpg)

User Journey Mapping Trabajador afectado por accidentes o incidentes laborales:  
![imgs](imgs/JourneyMap2.jpg)

### 2.3.4. Empathy Mapping.
Empathy mapping de Personal encargado de la tramitación de accidentes e incidentes laborales  
![imgs](imgs/EmpathyMap1.png)

Empathy mapping de Trabajador afectado por accidentes o incidentes laborales

![imgs](imgs/EmpathyMap2.png)

### 2.3.5. As-Is Scenario Mapping.
Se realizaron los siguientes cuadros en la herramienta Canva Whiteboard, el link original puede ser observado aquí: [https://www.canva.com/design/DAGzW03jLMs/g\_OiVuR-JggoMUGJMwWTuA/edit?utm\_content=DAGzW03jLMs\&utm\_campaign=designshare\&utm\_medium=link2\&utm\_source=sharebutton](https://www.canva.com/design/DAGzW03jLMs/g_OiVuR-JggoMUGJMwWTuA/edit?utm_content=DAGzW03jLMs&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) 

* **As-Is Scenario Mapping para Personal encargado de la tramitación de accidentes e incidentes laborales**

![imgs](imgs/AsIsSeg1.png)

* **As-Is Scenario Mapping para Trabajador afectado por accidentes o incidentes laborales**

![imgs](imgs/AsIsSeg2.png)

### 2.3.6 To-Be Scenario Mapping.
Se realizaron los siguientes cuadros en la herramienta Canva Whiteboard, el link original puede ser observado aquí: [https://www.canva.com/design/DAGzW-JsLAw/mDMx7Dd5OpulQwCwOf8RXA/edit?utm\_content=DAGzW-JsLAw\&utm\_campaign=designshare\&utm\_medium=link2\&utm\_source=sharebutton](https://www.canva.com/design/DAGzW-JsLAw/mDMx7Dd5OpulQwCwOf8RXA/edit?utm_content=DAGzW-JsLAw&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) 

* **To-Be Scenario Mapping para Personal encargado de la tramitación de accidentes e incidentes laborales**

![imgs](imgs/ToBeSeg1.png)

* **To-Be Scenario Mapping para Trabajador afectado por accidentes o incidentes laborales**

![imgs](imgs/ToBeSeg2.png)

## 2.4. Big Picture Event Storming.
Big Picture Event Storming es una técnica colaborativa que nos permitirá comprender el funcionamiento global de SAFEWORK. Se basará en visualizar eventos clave del dominio(domain events), fomentar el diálogo entre roles (actores) diversos y detectar oportunidades de mejora. El proceso se divide en tres fases principales:

**Primera Etapa: OPEN**

Aquí colocamos todos los eventos de dominios que se nos pueda ocurrir.
<img width="773" height="857" alt="Captura de pantalla 2025-09-19 155653" src="https://github.com/user-attachments/assets/084b4508-93cc-45b9-ab02-16d2f45bb020" />

**Segunda Etapa: EXPLORE**

Identificamos actores y pain points que luego cuestionamos, y lo más importante crear una secuencia entre los eventos de dominio.
<img width="1192" height="1005" alt="Captura de pantalla 2025-09-19 164843" src="https://github.com/user-attachments/assets/02dba83a-82cd-4290-bb8b-406682241466" />

**Tercera Etapa: CLOSE**

Identificamos problemas que hayamos encontrado, temas a investigar más a fondo y declaramos que esta fuera de nuestro alcance actual.

<img width="1409" height="851" alt="Captura de pantalla 2025-09-19 170329" src="https://github.com/user-attachments/assets/6acf4a0b-d506-47bb-82cf-7f8bae578acb" />

## 2.5. Ubiquitous Language.

**Términos Clave:**
*- Incident (Incidente):*
Evento no deseado que ocurre en el lugar de trabajo y que no causa daño grave, pero que puede indicar una condición insegura.

*- Accident (Accidente):*
Suceso inesperado en el trabajo que causa daño físico a un trabajador o afecta la seguridad.

*- Report (Reporte):*
Registro formal de un accidente o incidente, que incluye datos relevantes como descripción, lugar, fecha, fotos o documentos.

*- Case (Caso):*
Conjunto de reportes y acciones relacionadas a un accidente o incidente específico que está siendo gestionado.

*- Case Status (Estado del caso):*
Fase en la que se encuentra un reporte: pendiente, en revisión, en proceso de acción correctiva o cerrado.


**Roles y Actores**

*- Worker (Trabajador):*
Persona que realiza labores en la empresa y que puede reportar incidentes o accidentes.

*- Affected Worker (Trabajador afectado):*
Colaborador que ha sufrido un accidente o incidente y requiere seguimiento de su caso.

*- Occupational Health and Safety Staff (Personal SST):*
Especialistas responsables de recibir, gestionar y dar seguimiento a los reportes de accidentes e incidentes laborales.

*-Responsible (Responsable):*
Persona designada para atender y resolver un caso específico.

*- Administrator (Administrador):*
Usuario con permisos para gestionar configuraciones, seguridad de datos y auditorías dentro de la plataforma.


**Acciones y Procesos**

*- Report Submission (Registro de reporte):*
Acción realizada por un trabajador para informar sobre un accidente o incidente.

*- Case Management (Gestión de casos):*
Proceso que incluye la recepción, revisión, asignación de responsables, actualización de estado y cierre de un caso.

*- Follow-up (Seguimiento):*
Actividad de monitoreo continuo sobre el progreso de un caso hasta su resolución.

*- Evidence (Evidencia):*
Documentos, fotos o archivos que respaldan la veracidad de un reporte.

*- Audit (Auditoría):*
Revisión oficial de registros y casos para comprobar cumplimiento de normativas de seguridad.

*- Notification (Notificación):*
Aviso enviado en tiempo real al usuario sobre cambios en el estado de un reporte o asignación de responsabilidades.

*- Timeline (Línea de tiempo):*
Representación cronológica de las etapas de un caso desde su registro hasta su cierre.

 
**Contexto Organizacional:**

*- Occupational Safety (Seguridad Ocupacional):*
Conjunto de medidas y procedimientos destinados a proteger la integridad física y psicológica de los trabajadores.

*- Corrective Action (Acción Correctiva):*
Medida implementada para solucionar un problema detectado en un reporte.

*- Preventive Action (Acción Preventiva):*
Medida destinada a evitar que un accidente o incidente vuelva a ocurrir.

*- Transparency (Transparencia):*
Cualidad del sistema que permite a los trabajadores conocer en todo momento el estado de sus reportes.

---

# Capítulo III: Requirements Specification
## 3.1. User Stories.

* EPICS

Las Epic definidas para SafeWork están orientadas a cubrir las necesidades principales tanto del personal encargado de la tramitación de accidentes e incidentes laborales como la de los trabajadores afectados por accidentes o incidentes laborales. Estas epics abordan funcionalidades esenciales para el funcionamiento de la plataforma, asegurando una experiencia fluida y efectiva por parte de ambos segmentos.

| Epic / Story ID | Título | Descripción |
| :---: | ----- | ----- |
| EP01 | Navegación en Landing Page | Como visitante de SafeWork, deseo poder navegar fácilmente en la landing page para entender el propósito de la plataforma, sus beneficios y cómo me puede ayudar en la gestión o reporte de incidentes laborales. |
| EP02 | Autenticación y Registro de Usuarios | Como usuario nuevo, deseo registrarme e iniciar sesión con mis credenciales de forma segura para poder acceder a las funcionalidades que me corresponden (trabajador o personal SST). |
| EP03 | Recuperación de Contraseña | Como usuario registrado, deseo recuperar mi contraseña de forma sencilla en caso de olvidarla para mantener el acceso a mi cuenta. |
| EP04 | Reporte de Accidentes e Incidentes | Como trabajador, deseo registrar rápidamente un accidente o incidente desde mi móvil o web para notificar de inmediato al área encargada y que se actúe oportunamente. |
| EP05 | Gestión de Reportes | Como personal SST, deseo recibir, revisar y actualizar los reportes enviados por trabajadores para dar seguimiento y aplicar medidas correctivas. |
| EP06 | Seguimiento y Estado de Casos | Como trabajador, deseo ver el estado y avance de mi reporte (en revisión, en acción correctiva, cerrado) para saber en qué etapa se encuentra mi caso. |
| EP07 | Soporte y Preguntas Frecuentes | Como usuario, deseo acceder a una sección de soporte y FAQ para resolver dudas comunes sin necesidad de contactar a un asesor. |
| EP08 | Perfil de Usuario y Roles | Como usuario, deseo configurar mi perfil y rol (trabajador o personal SST) para que la plataforma muestre opciones personalizadas a mis necesidades. |
| EP09 | Sistema de Notificaciones | Como usuario, deseo recibir notificaciones en tiempo real (web y móvil) cuando se actualice un reporte o se asigne una acción, para estar siempre informado. |
| EP10 | Gestión Documental | Como personal SST, deseo adjuntar documentos (fotos, reportes médicos, normativas) a un caso para llevar un registro más completo y organizado. |
| EP11 | Comunicación Interna | Como trabajador y como personal SST, deseo contar con un chat interno asociado a cada reporte para coordinar y dar seguimiento directo dentro de la plataforma. |
| EP12 | Estadísticas y Reportes Analíticos | Como personal SST, deseo visualizar gráficos y métricas sobre los incidentes reportados para detectar patrones y tomar decisiones preventivas. |
| EP13 | Validación y Seguridad de Datos | Como administrador de la plataforma, deseo que la información registrada esté protegida y validada para garantizar la confidencialidad, integridad y trazabilidad de los reportes. |

* User Stories

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
| :---: | ----- | ----- | ----- | :---: |
| US01 | Navegación Intuitiva en la Landing Page | Como visitante de SafeWork, deseo que la landing page tenga una barra de navegación clara y accesible para encontrar fácilmente las secciones importantes. | **Escenario 01:** Given el usuario está en la landing page When hace clic en el menú Then debería ver opciones como “Inicio”, “Reportar Incidente”, “Sobre Nosotros” y “Contacto” **Escenario 02:** Given el usuario posiciona el cursor sobre un ítem del menú When el ítem se vuelve activo Then debería resaltarse | EP01 |
| US02 | Visualización de Beneficios | Como visitante, deseo visualizar claramente los beneficios de usar SafeWork para entender su propuesta de valor. | **Escenario 1:** Given el usuario está en la landing page When hace scroll hacia abajo Then debería ver una sección con íconos y descripciones sobre rapidez, seguridad y transparencia | EP01 |
| US03 | Acceso a Testimonios | Como visitante, deseo leer testimonios de otros usuarios para generar confianza en la plataforma. | **Escenario 1:** Given el usuario está en la landing page When accede a la sección de testimonios Then debería ver opiniones de trabajadores y personal de SST | EP01 |
| US04 | Registro de Usuario | Como usuario nuevo, deseo registrarme con correo y usuario para crear una cuenta en SafeWork. | **Escenario 1:** Given el usuario navega a la página de registro When completa sus datos y acepta los términos Then su cuenta debería crearse | EP02 |
| US05 | Inicio de Sesión Seguro | Como usuario, deseo iniciar sesión con mis credenciales para acceder a mis funcionalidades. | **Escenario 1:** Given el usuario ya tiene cuenta When ingresa credenciales válidas Then debería poder acceder a su perfil | EP02 |
| US06 | Roles Diferenciados | Como usuario, deseo seleccionar mi rol (trabajador o personal SST) para personalizar la experiencia. | **Escenario 1:** Given el usuario está en el formulario de registro When selecciona un rol Then la plataforma debería mostrar opciones según el tipo de usuario | EP02 |
| US07 | Recuperación de Contraseña | Como usuario, deseo recuperar mi contraseña mediante botón para poder acceder si la olvido. | **Escenario 1:** Given el usuario está en la página de inicio de sesión y ha olvidado su contraseña When hace clic en el botón de recuperación Then debería poder iniciar el proceso de recuperación **Escenario 02:** Given el usuario presionó el botón de recuperación When sigue el enlace Then debería poder establecer una nueva contraseña. | EP03 |
| US08 | Revisión de contraseña al registrarse | Como usuario nuevo, deseo que el sistema me pida utilizar ciertos caracteres para asegurar mi contraseña. | **Escenario 01:** Given el usuario ingresa una contraseña insegura When no cumple los requisitos de seguridad Then debería mostrarse un mensaje de error **Escenario 02:** Given el usuario ingresa una contraseña segura When confirma el registro Then su cuenta debería crearse sin problemas | EP02 |
| US09 | Reportar Accidente | Como trabajador, deseo registrar un accidente laboral con fotos y detalles para notificar de inmediato a la empresa. | **Escenario 1:** Given el usuario sufrió un accidente When selecciona la opción “Reportar” Then debería poder completar un formulario con descripción, ubicación y archivos adjuntos | EP04 |
| US10 | Reportar Incidente | Como trabajador, deseo reportar un incidente menor para que quede registrado y pueda prevenir futuros accidentes. | **Escenario 1:** Given el usuario es trabajador y selecciona “Incidente” en el formulario When describe la situación Then no debería necesitar adjuntar documentos obligatorios | EP04 |
| US11 | Geolocalización del Reporte | Como trabajador, deseo que mi reporte incluya ubicación geográfica para mayor precisión en la atención. | **Escenario 1:** Given el usuario está registrando un reporte When habilita la geolocalización Then el sistema debería guardar las coordenadas en el reporte | EP04 |
| US12 | Revisión de Reportes | Como personal SST, deseo revisar todos los reportes enviados para priorizar los más urgentes. | **Escenario 1:** Given el usuario accede al panel de reportes When selecciona un reporte Then debería ver el nivel de urgencia | EP05 |
| US13 | Asignación de Responsables | Como personal SST, deseo asignar responsables a cada caso para garantizar el seguimiento. | **Escenario 1:** Given el usuario revisa un reporte When elige “Asignar responsable” Then debería enviarse una notificación al designado | EP05 |
| US14 | Actualización de Estado | Como personal SST, deseo cambiar el estado de un reporte (pendiente, en proceso, cerrado) para llevar control de avances. | **Escenario 1:** Given un reporte está en revisión When el usuario actualiza su estado Then el cambio debería reflejarse al refrescar la página | EP05 |
| US15 | Visualizar Estado del Reporte | Como trabajador, deseo ver en qué estado está mi reporte para mantenerme informado. | **Escenario 1:** Given el usuario envió un reporte When ingresa a “Mis reportes” Then debería ver el estado actualizado | EP05 |
| US16 | Historial de Reportes | Como trabajador, deseo consultar mis reportes anteriores para tener un registro personal. | **Escenario 1:** Given el usuario está en su perfil y selecciona “Historial” When carga la sección Then debería ver la lista de reportes enviados con sus estados finales | EP06 |
| US17 | Preguntas Frecuentes | Como visitante, deseo consultar una sección de FAQ para resolver dudas comunes. | **Escenario 1:** Given el usuario abre el menú y selecciona “Ayuda” When carga la sección de preguntas frecuentes Then debería ver una lista organizada por categoría | EP07 |
| US18 | Chat de Soporte | Como usuario, deseo comunicarme con un asistente virtual para resolver dudas rápidamente. | **Escenario 1:** Given el usuario necesita soporte When abre el chat Then debería poder escribir preguntas y recibir respuestas automáticas | EP07 |
| US19 | Edición de Perfil | Como usuario, deseo editar mis datos personales y de contacto para mantener mi perfil actualizado. | **Escenario 01:** Given el usuario está en su perfil y entra en modo edición When actualiza sus datos personales Then los cambios deberían guardarse **Escenario 02:** Given el usuario guarda los cambios en su perfil When vuelve a ver su perfil Then debería mostrarse la información actualizada | EP08 |
| US20 | Foto de Perfil | Como trabajador, deseo agregar una foto para personalizar mi perfil en la plataforma. | **Escenario 1:** Given el usuario edita su perfil y sube una foto When finaliza la carga Then la foto debería aparecer en su cuenta | EP08 |
| US21 | Notificaciones en Tiempo Real | Como usuario, deseo recibir notificaciones push cuando mi reporte cambie de estado. | **Escenario 1:** Given el estado del reporte del usuario cambia When el personal SST actualiza el reporte Then el usuario debería recibir una notificación instantánea | EP09 |
| US22 | Recordatorios de la aplicación | Como trabajador afectado, deseo recibir recordatorios dentro de la aplicación sobre el estado de mi reporte para estar informado sin necesidad de revisar constantemente. | **Escenario 1:** Given el reporte sigue en revisión When el usuario ingresa a la plataforma Then debería ver un aviso con la etapa actual **Escenario 02:** Given el caso está resuelto When el usuario revisa la plataforma Then debería ver un aviso de cierre del caso | EP08 |
| US23 | Adjuntar Documentos | Como personal SST, deseo adjuntar documentos técnicos al reporte para que quede registrado todo el proceso. | **Escenario 1:** Given el personal SST gestiona un reporte y hace clic en “Adjuntar archivo” When selecciona PDFs, imágenes o documentos Word Then el sistema debería subirlos correctamente | EP10 |
| US24 | Adjuntar Evidencias | Como trabajador, deseo adjuntar fotos al momento de reportar un accidente para mostrar lo ocurrido. | **Escenario 1:** Given el usuario está llenando un reporte y añade archivos When envía el formulario Then los archivos deberían guardarse asociados al caso | EP10 |
| US25 | Notas internas en el caso | Como personal de SST, deseo añadir notas internas a los casos para poder documentar hallazgos o comentarios relevantes sin necesidad de un chat. | **Escenario 1:** Given el personal SST añade una nota interna a un caso When guarda la nota Then debería registrarse con fecha y autor **Escenario 02:** Given el personal SST revisa el historial del caso When consulta las notas internas Then deberían aparecer en orden cronológico | EP09 |
| US26 | Línea de tiempo del caso | Como trabajador afectado, deseo ver una línea de tiempo con las etapas de mi caso para comprender fácilmente su progreso. | **Escenario 01:** Given el usuario abre los detalles de su caso When carga la línea de tiempo Then debería ver fechas de registro, revisión y resolución **Escenario 02:** Given el estado del caso cambia When el usuario revisa la línea de tiempo Then debería actualizarse automáticamente | EP09 |
| US27 | Visualizar Detalles del reporte | Como personal SST, deseo ver detalles sobre los reportes enviados. | **Escenario 1:** Given el personal SST accede al panel de detalles When selecciona un campo Then debería ver la información correspondiente | EP12 |
| US28 | Visualización de reportes en pantalla | Como administrador, deseo visualizar los reportes directamente en pantalla en lugar de exportarlos, para tomar decisiones rápidas. | **Escenario 01:** Given el administrador solicita un reporte en pantalla When carga los datos Then debería verse con tablas y gráficos simples **Escenario 02:** Given el administrador cambia los filtros When actualiza la vista Then los resultados deberían ajustarse en tiempo real | EP07 |
| US29 | Seguridad de Datos | Como administrador, deseo que toda la información esté encriptada para proteger la privacidad. | **Escenario 1:** Given se guarda información en la base de datos When ocurre el almacenamiento Then debe encriptarse automáticamente | EP13 |
| US30 | Cambio de contraseña desde el perfil | Como usuario, deseo cambiar mi contraseña desde la configuración de mi perfil para mantener la seguridad de mi cuenta. | **Escenario 01:** Given el usuario está en la configuración de su perfil y selecciona “Cambiar contraseña” When ejecuta la acción Then debería pedírsele la contraseña actual y la nueva **Escenario 02:** Given el usuario ingresa correctamente la contraseña actual y confirma When finaliza el cambio Then la nueva contraseña debería guardarse | EP02 |
| US31 | Navegación desde cualquier dispositivo | Como visitante, deseo que la landing page sea responsive para acceder desde cualquier dispositivo. | **Escenario 1:** Given el usuario accede desde un dispositivo móvil When abre la landing page Then los elementos deberían ajustarse al tamaño de pantalla **Escenario 2:** Given el usuario accede desde un dispositivo móvil When abre la landing page Then los elementos deberían ajustarse al tamaño de pantalla | EP01 |
| US32 | Actualización de área/departamento en perfil | Como usuario, deseo actualizar el área o departamento al que pertenezco para que la información de mi perfil refleje correctamente mi puesto en la organización. | **Escenario 01:** Given el usuario está en la configuración de su perfil y edita su área o departamento When guarda el cambio Then el nuevo dato debería registrarse **Escenario 02:** Given el usuario regresa a su perfil tras actualizar su área When visualiza su información Then debería verse el dato actualizado | EP08 |
| US33 | Cierre automático de sesión por inactividad | Como usuario, deseo que mi sesión se cierre automáticamente tras un periodo de inactividad para mantener la seguridad de mis datos. | **Escenario 01:** Given el usuario no interactúa por 15 minutos When intenta usar la plataforma nuevamente Then debería pedírsele volver a iniciar sesión **Escenario 02:** Given el usuario vuelve a iniciar sesión When lo hace Then debería dirigírsele a la pantalla donde estaba antes | EP02 |
| US34 | Confirmación de Reporte | Como trabajador, deseo recibir un comprobante al enviar un reporte para asegurarme de que se registró. | **Escenario 1:** Given el usuario envía un reporte y el sistema lo guarda When finaliza el proceso Then debería mostrarse un comprobante visible en pantalla | EP04 |
| US35 | Búsqueda de Reportes | Como personal SST, deseo buscar reportes por trabajador, fecha o tipo de incidente para gestionar más rápido. | **Escenario 1:** Given el personal SST accede al panel y usa el buscador When ingresa criterios (trabajador, fecha o tipo de incidente) Then deberían mostrarse solo los reportes que cumplan | EP05 |
| US36 | Validación de campos obligatorios en registro | Como usuario, deseo que el sistema me obligue a completar los campos requeridos (nombre, fecha, lugar, etc.) para asegurar que la información esté completa realizar un reporte | **Escenario 1:** Given el usuario tiene un reporte en proceso y faltan datos When intenta avanzar Then el sistema debería indicar qué campos están pendientes**Escenario 02:** Given el usuario completa todos los campos obligatorios When confirma el registro Then debería permitirse la subida del reporte | EP06 |
| US37 | Búsqueda en Preguntas Frecuentes | Como usuario, deseo buscar palabras clave dentro de la sección de FAQ para encontrar rápidamente respuestas a mis dudas. | **Escenario 01:** Given el usuario está en la sección FAQ y busca un término When ingresa la palabra clave Then deberían mostrarse las preguntas relacionadas **Escenario 02:** Given no hay coincidencias en la búsqueda When ejecuta la búsqueda Then debería mostrarse el mensaje “No se encontraron resultados” | EP07 |
| US38 | Notificación de Nueva Tarea | Como responsable de un reporte, deseo recibir notificación cuando me asignan un caso. | **Escenario 1:** Given el personal SST asigna un caso a un responsable When designa al usuario Then éste debería recibir una notificación en tiempo real | EP09 |
| US39 | Filtro por estado de casos | Como personal de SST, deseo filtrar los casos por estado (abierto, en proceso, cerrado) para gestionar mejor la carga de trabajo. | **Escenario 01:** Given el personal SST está en la lista de casos y aplica el filtro “Abiertos” When confirma el filtro Then solo deberían mostrarse esos casos **Escenario 02:** Given el personal SST aplica múltiples filtros When confirma la selección Then la vista debería actualizarse con los resultados correspondientes | EP05 |
| US40 | Registro de Auditoría | Como administrador, deseo tener un historial de todas las acciones en la plataforma para auditorías. | **Escenario 1:** Given un usuario realiza una acción en la plataforma When se ejecuta la acción Then debería registrarse en un log de auditoría | EP13 |
| US41 | Botones CTA principales en la Landing Page | Como visitante de la landing page, deseo ver botones de llamada a la acción (CTA) claramente visibles y funcionales para poder interactuar fácilmente con las opciones clave del producto. | **Escenario 01:** Given el usuario está en la landing page y visualiza los botones CTA When carga la sección Then deberían estar etiquetados con acciones claras como “Probar Gratis”, “Ver Planes” o “Contáctanos” **Escenario 02:** Given el usuario hace clic en un botón CTA When la acción se ejecuta correctamente Then debería redirigirse a la sección correspondiente o iniciar el flujo esperado **Escenario 03:** Given el usuario navega desde un dispositivo móvil y ve los botones CTA When carga la vista Then deberían adaptarse al tamaño de pantalla y ser fácilmente accesibles | EP01 |
| US42 | Sección de Preguntas Frecuentes (FAQ) | Como visitante de la landing page, deseo acceder a una sección de preguntas frecuentes bien estructurada para resolver dudas comunes sin necesidad de contactar soporte. | **Escenario 01:** Given el usuario está en la landing page y accede a la sección FAQ When carga la sección Then debería ver una lista de preguntas organizadas por temas **Escenario 02:** Given el usuario hace clic en una pregunta de la FAQ When se despliega la respuesta Then debería poder leerla sin salir de la página **Escenario 03:** Given el usuario tiene una duda no resuelta When revisa la sección FAQ Then debería ver un enlace para contactar soporte o enviar una consulta | EP01 |
| US43 | Sección de Membresía y Planes | Como visitante interesado en el producto, deseo ver una sección que detalle los planes de membresía y sus características para poder comparar opciones y tomar una decisión informada. | **Escenario 01:** Given el usuario está en la landing page y accede a la sección de planes When carga la sección Then debería ver tarjetas o una tabla con niveles de membresía y beneficios **Escenario 02:** Given el usuario compara los planes y revisa sus características When analiza las opciones Then debería identificar fácilmente cuál se ajusta a sus necesidades **Escenario 03:** Given el usuario está listo para elegir un plan y hace clic en “Seleccionar” o “Ver más” When confirma su elección Then debería iniciarse el proceso de registro o compra | EP01 |

## 3.2. Impact Mapping.
Se realizaron los siguientes cuadros en la herramienta Canva Whiteboard, el link original puede ser observado aquí: 

**Impact Map Segmento 1:** **Personal encargado de la tramitación de accidentes e incidentes laborales**  
![imgs](imgs/ImpactMapSeg1.png)

**Impact Map Segmento 2:** **Trabajadores afectados por accidentes o incidentes laborales**  
![imgs](imgs/ImpactMapSeg2.png)

## 3.3. Product Backlog.
Se utilizó la escala Fibonacci para la estimación de los Story Points. En total se tuvieron **162** Story Points.

| \#Orden | Epic / Story ID | Título | Descripción | Story Points (1/2/3/5/8) |
| :---: | :---: | ----- | ----- | :---: |
| 1 | US01 | Navegación Intuitiva en la Landing Page | Como visitante de SafeWork, deseo que la landing page tenga una barra de navegación clara y accesible para encontrar fácilmente las secciones importantes. | 2 |
| 2 | US02 | Visualización de Beneficios | Como visitante, deseo visualizar claramente los beneficios de usar SafeWork para entender su propuesta de valor. | 1 |
| 3 | US03 | Acceso a Testimonios | Como visitante, deseo leer testimonios de otros usuarios para generar confianza en la plataforma. | 2 |
| 4 | US04 | Registro de Usuario | Como usuario nuevo, deseo registrarme con correo y usuario para crear una cuenta en SafeWork. | 5 |
| 5 | US05 | Inicio de Sesión Seguro | Como usuario, deseo iniciar sesión con mis credenciales para acceder a mis funcionalidades. | 5 |
| 6 | US06 | Roles Diferenciados | Como usuario, deseo seleccionar mi rol (trabajador o personal SST) para personalizar la experiencia. | 5 |
| 7 | US07 | Recuperación de Contraseña | Como usuario, deseo recuperar mi contraseña mediante botón para poder acceder si la olvido. | 5 |
| 8 | US08 | Revisión de contraseña al registrarse | Como usuario nuevo, deseo que el sistema me pida utilizar ciertos caracteres para asegurar mi contraseña. | 3 |
| 9 | US09 | Reportar Accidente | Como trabajador, deseo registrar un accidente laboral con fotos y detalles para notificar de inmediato a la empresa. | 8 |
| 10 | US10 | Reportar Incidente | Como trabajador, deseo reportar un incidente menor para que quede registrado y pueda prevenir futuros accidentes. | 5 |
| 11 | US11 | Geolocalización del Reporte | Como trabajador, deseo que mi reporte incluya ubicación geográfica para mayor precisión en la atención. | 8 |
| 12 | US12 | Revisión de Reportes | Como personal SST, deseo revisar todos los reportes enviados para priorizar los más urgentes. | 5 |
| 13 | US13 | Asignación de Responsables | Como personal SST, deseo asignar responsables a cada caso para garantizar el seguimiento. | 5 |
| 14 | US14 | Actualización de Estado | Como personal SST, deseo cambiar el estado de un reporte (pendiente, en proceso, cerrado) para llevar control de avances. | 3 |
| 15 | US15 | Visualizar Estado del Reporte | Como trabajador, deseo ver en qué estado está mi reporte para mantenerme informado. | 3 |
| 16 | US16 | Historial de Reportes | Como trabajador, deseo consultar mis reportes anteriores para tener un registro personal. | 3 |
| 17 | US17 | Preguntas Frecuentes | Como visitante, deseo consultar una sección de FAQ para resolver dudas comunes. | 2 |
| 18 | US18 | Chat de Soporte | Como usuario, deseo comunicarme con un asistente virtual para resolver dudas rápidamente. | 5 |
| 19 | US19 | Edición de Perfil | Como usuario, deseo editar mis datos personales y de contacto para mantener mi perfil actualizado. | 3 |
| 20 | US20 | Foto de Perfil | Como trabajador, deseo agregar una foto para personalizar mi perfil en la plataforma. | 3 |
| 21 | US21 | Notificaciones en Tiempo Real | Como usuario, deseo recibir notificaciones push cuando mi reporte cambie de estado. | 8 |
| 22 | US22 | Recordatorios de la aplicación | Como trabajador afectado, deseo recibir recordatorios dentro de la aplicación sobre el estado de mi reporte para estar informado sin necesidad de revisar constantemente. | 3 |
| 23 | US23 | Adjuntar Documentos | Como personal SST, deseo adjuntar documentos técnicos al reporte para que quede registrado todo el proceso. | 5 |
| 24 | US24 | Adjuntar Evidencias | Como trabajador, deseo adjuntar fotos al momento de reportar un accidente para mostrar lo ocurrido. | 5 |
| 25 | US25 | Notas internas en el caso | Como personal de SST, deseo añadir notas internas a los casos para poder documentar hallazgos o comentarios relevantes sin necesidad de un chat. | 5 |
| 26 | US26 | Línea de tiempo del caso | Como trabajador afectado, deseo ver una línea de tiempo con las etapas de mi caso para comprender fácilmente su progreso. | 5 |
| 27 | US27 | Visualizar Detalles del reporte | Como personal SST, deseo ver detalles sobre los reportes enviados. | 3 |
| 28 | US28 | Visualización de reportes en pantalla | Como administrador, deseo visualizar los reportes directamente en pantalla en lugar de exportarlos, para tomar decisiones rápidas. | 5 |
| 29 | US29 | Seguridad de Datos | Como administrador, deseo que toda la información esté encriptada para proteger la privacidad. | 8 |
| 30 | US30 | Cambio de contraseña desde el perfil | Como usuario, deseo cambiar mi contraseña desde la configuración de mi perfil para mantener la seguridad de mi cuenta. | 3 |
| 31 | US31 | Navegación desde cualquier dispositivo | Como visitante, deseo que la landing page sea responsive para acceder desde cualquier dispositivo. | 3 |
| 32 | US32 | Actualización de área/departamento en perfil | Como usuario, deseo actualizar el área o departamento al que pertenezco para que la información de mi perfil refleje correctamente mi puesto en la organización. | 2 |
| 33 | US33 | Cierre automático de sesión por inactividad | Como usuario, deseo que mi sesión se cierre automáticamente tras un periodo de inactividad para mantener la seguridad de mis datos. | 3 |
| 34 | US34 | Confirmación de Reporte | Como trabajador, deseo recibir un comprobante al enviar un reporte para asegurarme de que se registró. | 2 |
| 35 | US35 | Búsqueda de Reportes | Como personal SST, deseo buscar reportes por trabajador, fecha o tipo de incidente para gestionar más rápido. | 5 |
| 36 | US36 | Validación de campos obligatorios en registro | Como usuario, deseo que el sistema me obligue a completar los campos requeridos (nombre, fecha, lugar, etc.) para asegurar que la información esté completa realizar un reporte | 3 |
| 37 | US37 | Búsqueda en Preguntas Frecuentes | Como usuario, deseo buscar palabras clave dentro de la sección de FAQ para encontrar rápidamente respuestas a mis dudas. | 3 |
| 38 | US38 | Notificación de Nueva Tarea | Como responsable de un reporte, deseo recibir notificación cuando me asignan un caso. | 5 |
| 39 | US39 | Filtro por estado de casos | Como personal de SST, deseo filtrar los casos por estado (abierto, en proceso, cerrado) para gestionar mejor la carga de trabajo. | 3 |
| 40 | US40 | Registro de Auditoría | Como administrador, deseo tener un historial de todas las acciones en la plataforma para auditorías. | 5 |
| 41 | US41 | Botones CTA principales en la Landing Page | Como visitante de la landing page, deseo ver botones de llamada a la acción (CTA) claramente visibles y funcionales para poder interactuar fácilmente con las opciones clave del producto. | 2 |
| 42 | US42 | Sección de Preguntas Frecuentes (FAQ) | Como visitante de la landing page, deseo acceder a una sección de preguntas frecuentes bien estructurada para resolver dudas comunes sin necesidad de contactar soporte. | 3 |
| 43 | US43 | Sección de Membresía y Planes | Como visitante interesado en el producto, deseo ver una sección que detalle los planes de membresía y sus características para poder comparar opciones y tomar una decisión informada. |  5 |

---

# Capítulo IV: Product Design
## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.

# Tipografía  

En **SafeWork** se utilizan dos tipografías que aseguran una experiencia clara y profesional.  
**Raleway** se aplica en títulos y botones por su estilo moderno, limpio y llamativo, lo que ayuda a resaltar secciones importantes.  
Para los textos generales se usa **Montserrat**, una fuente pensada para pantallas, que ofrece excelente legibilidad en cualquier dispositivo.  

Esta combinación crea una jerarquía visual efectiva que guía al usuario de forma intuitiva y ordenada a lo largo de toda la plataforma.  

**Figura 1:**  
Uso de la tipografía **"Raleway"** en encabezados
<img width="1200" height="600" alt="Image" src="https://github.com/user-attachments/assets/38728751-2ad1-4f38-ac13-b584c1d69c54" />

Fuente: [1001 Fonts - Raleway](https://www.1001fonts.com/raleway-font.html)  

**Figura 2:**  
Uso de la tipografía **"Montserrat"** en textos generales
<img width="1200" height="600" alt="Image" src="https://github.com/user-attachments/assets/23decf9b-8a59-42e5-8fe1-e4ee2312c9fe" /> 

Fuente: [1001 Fonts - Montserrat](https://www.1001fonts.com/montserrat-font.html)  

---

# Colores principales  

La elección de colores en **SafeWork** refuerza la identidad visual de la marca y guía la experiencia del usuario.  
El **violeta oscuro** `#7B7DC1` se establece como principal, comunicando confianza, seguridad y modernidad, cualidades clave para una plataforma enfocada en la prevención de riesgos laborales.  

Este tono se combina con un **fondo oscuro** `#0D0C22` que aporta contraste, elegancia y reduce la fatiga visual en pantallas.  

Para garantizar una lectura clara, se utilizan textos en **blanco** y **grises suaves**, mientras que los botones y elementos interactivos mantienen un estilo llamativo pero coherente.  

En conjunto, esta paleta genera un entorno profesional, accesible y visualmente equilibrado, adaptado a dispositivos modernos.  

**Figura 1:** Colores del texto
<img width="1600" height="1200" alt="Image" src="https://github.com/user-attachments/assets/fa6069e5-d854-492c-82b7-6020becddd1e" />

[Paleta en Coolors](https://coolors.co/ffffff-000000-7b7dc1)  

**Figura 2:** Colores principales
<img width="1600" height="1200" alt="Image" src="https://github.com/user-attachments/assets/dd4c5a6b-8aac-4f18-87cb-f35c35d408b8" />

[Paleta en Coolors](https://coolors.co/0d0c22-7b7dc1-5a5ca0-1a1835)  

**Figura 3:** Colores secundarios
<img width="1600" height="1200" alt="Image" src="https://github.com/user-attachments/assets/037fd2b4-e65c-4e6c-8fed-ad1956134894" />

[Paleta en Coolors](https://coolors.co/444654-888a9c-e1e3ec)  

**Figura 4:** Colores aplicados en wireframes
<img width="1600" height="1200" alt="Image" src="https://github.com/user-attachments/assets/cb7cf89e-bd8f-4634-9b8f-fa7d8a6aa17c" />

[Paleta en Coolors](https://coolors.co/f0f0f0-bdbdbd-b3b3b3-3f3f3f-2e2e2e)  

---

# Estilo visual  

El diseño utiliza una paleta centrada en tonos **violetas oscuros** `#7B7DC1` y fondos **azul muy oscuro** `#0D0C22`, que transmiten profesionalismo y calma.  

Los textos **blancos** `#FFFFFF` y **grises claros** (`#888A9C`, `#E1E3EC`) garantizan alta legibilidad y contraste, incluso en dispositivos con bajo brillo.  

Las formas **suaves y redondeadas** crean una apariencia moderna y amigable, que facilita la navegación sin distraer al usuario.  

---

# Interactividad  

Los elementos interactivos, como botones y tarjetas, incluyen **transiciones suaves** y **efectos de hover** que mejoran la experiencia táctil.  

- Los botones cambian de color de `#7B7DC1` a `#5A5CA0`.  
- Las tarjetas se **elevan ligeramente** al pasar el cursor, ofreciendo **feedback visual inmediato**.  
- El **scroll con desplazamiento suave** permite una navegación fluida y natural entre secciones, favoreciendo la usabilidad en todos los dispositivos.  

## 4.1.2. Web Style Guidelines  

### Responsividad  
El diseño es completamente **responsivo**, adaptándose a diferentes tamaños de pantalla desde móviles hasta escritorios.  
Se utilizan *media queries* para reorganizar elementos, como pasar de diseños en fila a columna, y ajustar tamaños y espacios, garantizando que el contenido sea accesible y legible en cualquier dispositivo.  

### Componentes  
Los componentes como **botones, tarjetas y menús** están diseñados con un estilo coherente y sencillo.  
- Botones con bordes redondeados y colores destacados para llamadas a la acción.  
- Tarjetas con sombras suaves y espaciados definidos para mejorar la lectura.  

Todo mantiene una **jerarquía visual clara y consistente**.  

### Accesibilidad  
Se prioriza el **contraste alto** entre texto y fondo para facilitar la lectura a personas con baja visión.  
Además:  
- Los enlaces y botones son navegables mediante **teclado**.  
- Se usan **etiquetas semánticas** para mejorar la comprensión de lectores de pantalla.  

### Animaciones suaves  
Las interacciones incluyen **transiciones y efectos sutiles**, como:  
- Cambio de color en botones.  
- Elevación ligera de tarjetas al pasar el cursor.  

Estas animaciones no distraen, sino que aportan una experiencia más fluida y natural, ayudando a **guiar al usuario visualmente sin sobrecargar la interfaz**.  


## 4.2. Information Architecture.
### 4.2.1. Organization Systems  

**Jerárquico**  
La estructura de la plataforma sigue un sistema jerárquico claro donde la página principal (landing) actúa como punto central.  
Desde ahí, el usuario puede acceder a secciones específicas como **“About Us”, “Services”, “Plans”, “Testimonials”, “FAQ” y "Benefits"**.  
Esta organización permite que la información fluya de lo general a lo particular, facilitando la exploración y comprensión.  

**Modular y Seccional**  
Cada sección está diseñada como un módulo independiente, con contenido y funcionalidades específicas.  
Esto facilita actualizaciones y mantenimiento, además de ofrecer al usuario una experiencia limpia y enfocada.  
Las secciones se distinguen visualmente, ayudando a segmentar la información sin sobrecargar la página.


---

### 4.2.2. Labeling Systems  

**Menú principal**  
Las etiquetas en el menú son claras y directas: **“Home”, “About Us”, “Services”, “Plans”, “Testimonials”, “FAQ” y “Contact”**.  
Esto asegura que el usuario sepa exactamente qué esperar al hacer clic, mejorando la usabilidad.  

**Botones de acción**  
Los botones usan verbos de acción concisos como **“Start Now”, “Learn More” y “Back”**, lo que facilita la toma de decisiones rápidas y la interacción con la plataforma.  

**Formulario**  
Los campos están etiquetados con términos sencillos y comprensibles, como **“Name”, “Email”, y “Message”**, para asegurar que los usuarios puedan completarlos sin dudas o errores.  

### 4.2.3. SEO Tags and Meta Tags

La plataforma SafeWork incorpora metaetiquetas esenciales para mejorar el posicionamiento en buscadores, facilitar la lectura por parte de motores de búsqueda y garantizar una experiencia óptima en navegadores modernos y dispositivos móviles. A continuación, se detallan las principales meta etiquetas utilizadas:

Título: La etiqueta title es una de las más relevantes para SEO. Define el nombre que aparece en la pestaña del navegador y en los resultados de búsqueda.

<img width="578" height="19" alt="Image" src="https://github.com/user-attachments/assets/80eb332d-b023-4ad2-93d4-f2a3239f9098" />

Descripción: La meta descripción proporciona un resumen breve del contenido de sitio. Es clave para mejorar la visibilidad y el CTR en motores de búsqueda como Google.

<img width="725" height="75" alt="Image" src="https://github.com/user-attachments/assets/241b7211-01de-41f3-9e17-0cad13913afb" />

Palabras clave: Ayuda a relacionar el sitio en términos de búsqueda relevantes, aunque actualmente tiene poco peso en algoritmos de búsqueda.

<img width="578" height="19" alt="Image" src="./imgs/keywords.png" />

Derechos de autor: Indica el autor del contenido o la organización responsable del sitio web.
Responsividad: Garantiza que el sitio se vea correctamente en dispositivo móviles, tabletas y pantallas de diferentes tamaños.

<img width="542" height="19" alt="Image" src="https://github.com/user-attachments/assets/5e8902ca-d6a3-43f4-9bac-38d3fc89f63a" />

### 4.2.4. Searching Systems.

Actualmente no hay un sistema de búsqueda implementado. Se recomienda considerar esta funcionalidad en futuras versiones para mejorar la experiencia del usuario en sitios con gran volumen de contenido.

### 4.2.5. Navigation Systems.

**Navegación superior**  
El menú principal está ubicado en la parte superior, con enlaces directos a las secciones principales, facilitando el acceso rápido y visible en todo momento.  

**Flujo lógico**  
El recorrido del usuario está diseñado para ser intuitivo y lineal, desde la introducción en la landing hacia secciones específicas según su interés, sin pasos innecesarios ni confusión.  

**Internacionalización**  
Se incluye un conmutador de idioma sencillo, permitiendo cambiar entre idiomas sin recargar la página, mejorando la accesibilidad para usuarios internacionales.  

**Footer con navegación secundaria**  
El pie de página complementa la navegación con enlaces a información adicional, redes sociales y contacto, reforzando el acceso a contenido importante sin saturar el menú principal.  

**Estructura modular**  
La arquitectura modular permite agregar, modificar o eliminar secciones sin afectar el resto de la página, facilitando la escalabilidad y mantenimiento del sitio.

## 4.3. Landing Page UI Design.

Enlace al Landing Page: https://nexorape.github.io/Landing-Page/ 

### 4.3.1. Landing Page Wireframe.

<img width="658" height="345" alt="Image" src="https://github.com/user-attachments/assets/09868085-60ed-4896-b8ce-247c0d168524" />

<img width="657" height="530" alt="Image" src="https://github.com/user-attachments/assets/591c2aa6-72de-4749-92cb-534669f58035" />

<img width="657" height="566" alt="Image" src="https://github.com/user-attachments/assets/4bd4fb59-6910-4afc-ba82-56b48ecac19f" />

<img width="660" height="564" alt="Image" src="https://github.com/user-attachments/assets/5ffcd15c-451e-405d-ab1e-35c28b9b2359" />

<img width="657" height="327" alt="Image" src="https://github.com/user-attachments/assets/65062db1-5bcf-4e4d-aec6-b6a4cef652a4" />

<img width="658" height="540" alt="Image" src="https://github.com/user-attachments/assets/4d94dddf-98d2-4486-a892-defddee0c86b" />

<img width="657" height="552" alt="Image" src="https://github.com/user-attachments/assets/a7e49de8-59cc-43a8-b0d0-0ab509a644a3" />

<img width="658" height="214" alt="Image" src="https://github.com/user-attachments/assets/8b8ce5b8-0af3-4ec1-b601-6f81a1060b99" />



### 4.3.2. Landing Page Mock-up.

<img width="660" height="343" alt="Image" src="https://github.com/user-attachments/assets/74cd0ebe-0e74-41bd-91d3-1c24fac944c8" />

<img width="656" height="473" alt="Image" src="https://github.com/user-attachments/assets/747ddf92-c0f0-4d3e-8346-f06cefaa1ab3" />

<img width="661" height="564" alt="Image" src="https://github.com/user-attachments/assets/e1a5a73d-c8d2-4e78-bb37-348631f9cb21" />

<img width="656" height="555" alt="Image" src="https://github.com/user-attachments/assets/4cfdfb0a-3ebe-4cfc-a42f-811c56dcc625" />

<img width="655" height="316" alt="Image" src="https://github.com/user-attachments/assets/9a393329-6b2e-472d-b145-8e563d21535e" />

<img width="659" height="530" alt="Image" src="https://github.com/user-attachments/assets/20c1e8e7-6d30-449d-8b76-ad236f3e8280" />

<img width="658" height="560" alt="Image" src="https://github.com/user-attachments/assets/8bda1b93-f9c4-4b1d-89a3-5d295707d199" />

<img width="657" height="210" alt="Image" src="https://github.com/user-attachments/assets/7876a1b0-f900-47fd-8729-11f901e42c9f" />

## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.

**Create Account**  
Pantalla para que los usuarios creen una nueva cuenta ingresando sus datos básicos.  
<img alt="Create Account" src="./imgs/createaccount.png" />

**Reset Password**  
Interfaz que permite recuperar el acceso en caso de olvidar la contraseña.  
<img alt="Reset Password" src="./imgs/resetpassword.png" />

**Login**  
Formulario de inicio de sesión para acceder a la aplicación.  
<img alt="Login" src="./imgs/login.png" />

**Profile**  
Sección del perfil de usuario con información personal, roles y certificaciones.  
<img alt="Profile" src="./imgs/profile.png" />

**Incidents**  
Pantalla de gestión de incidentes, donde se listan, detallan y crean reportes.  
<img alt="Incidents" src="./imgs/incidents.png" />

**Assignments**  
Vista de asignaciones que muestra el estado, detalles y SLA de las tareas asignadas.  
<img alt="Assignments" src="./imgs/Assigments.png" />

**Notifications**  
Módulo para ver notificaciones recibidas, pendientes o enviadas.  
<img alt="Notifications" src="./imgs/notifications.png" />

**Analytics**  
Panel de análisis con métricas, reportes y tendencias de incidentes.  
<img alt="Analytics" src="./imgs/analytics.png" />



### 4.4.2. Web Applications Wireflow Diagrams.

En el presente diagrama se observa como desde el login se tiene la opción de abrir la vista de creación de cuenta, reinicio de contraseña en caso de olvidarla. Luego al pasar el login, se dirige a la pantalla de profile para colocar los datos personales. Luego desde la barra lateral se manejará de manera simple y sencilla la navegación en la app para los usuarios. 

<img width="323" height="555" alt="Image" src="https://github.com/user-attachments/assets/10349bf9-066f-4336-ac09-6bd669c9ef2f" />

### 4.4.3. Web Applications Mock-ups.

<img width="622" height="548" alt="Image" src="https://github.com/user-attachments/assets/ccde196c-b4a1-4153-943f-ef677e4d6ea9" />

<img width="644" height="558" alt="Image" src="https://github.com/user-attachments/assets/9e04da77-3939-4288-8d9a-16bfe79626bb" />

<img width="628" height="556" alt="Image" src="https://github.com/user-attachments/assets/c4ed98aa-16ff-4f0a-9dee-3b6501314d6b" />

<img width="624" height="556" alt="Image" src="https://github.com/user-attachments/assets/fd54f64d-1bd5-4be8-9d8b-fedcc22917dc" />

<img width="627" height="554" alt="Image" src="https://github.com/user-attachments/assets/5a238aa1-486d-4904-b5c9-fcac2c47aede" />

<img width="623" height="555" alt="Image" src="https://github.com/user-attachments/assets/369e3c38-9da7-47f8-b7ce-ce7e85551456" />

<img width="619" height="548" alt="Image" src="https://github.com/user-attachments/assets/e14c5e31-2228-483e-997b-f2d87287bd55" />

<img width="623" height="553" alt="Image" src="https://github.com/user-attachments/assets/199b9ac3-0bfb-49bf-bc5e-854cee9c840a" />

### 4.4.4. Web Applications User Flow Diagrams.

<img width="303" height="562" alt="Image" src="https://github.com/user-attachments/assets/25821459-1dfb-4c29-8113-0c74b1862f76" />

## 4.5. Web Applications Prototyping.

<img width="546" height="481" alt="Image" src="https://github.com/user-attachments/assets/680b1fee-73bc-4b87-99e6-594501bc20f3" />

Enlace al figma: https://www.figma.com/design/4lfYU4omqUax0rxIYtyXp1/Untitled?node-id=87-101&t=vINDSY2w8lBsUY2f-1 

## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Design-Level Event Storming.

Proceso del Design-Level EventStorming:

Paso 1: Partimos del Big Picture Event Storming, como base

<img width="888" height="969" alt="Captura de pantalla 2025-09-19 193005" src="https://github.com/user-attachments/assets/3a9c223e-5a86-42f6-a656-62edb6014dc7" />

Paso 2: Ordenamos de manera cronologíca los eventos de dominio, tuvimos en cuenta el 'happy path'.

<img width="1665" height="837" alt="Captura de pantalla 2025-09-19 194846" src="https://github.com/user-attachments/assets/653c0ba7-fb66-417c-900d-828fd06457d0" />

Paso 3: Se colocó dudas/posibles problemas a futuro sobre el dominio en algunas partes del flujo

<img width="1762" height="951" alt="Captura de pantalla 2025-09-19 195737" src="https://github.com/user-attachments/assets/17b13a87-9c28-4e49-b2af-dcebd18f893a" />

Paso 4: Se buscó eventos importantes que indiquen un cambio en el contexto.

<img width="1101" height="842" alt="Captura de pantalla 2025-09-19 201748" src="https://github.com/user-attachments/assets/592d82bb-1505-46f3-9f72-29ea3ef67594" />

Paso 5: Se añadió comandos que desencadenen eventos y tambien agregamos sus actores

<img width="1546" height="695" alt="Captura de pantalla 2025-09-19 212519" src="https://github.com/user-attachments/assets/457d1e48-9f20-4402-a752-55db5aad9510" />

<img width="1288" height="884" alt="Captura de pantalla 2025-09-19 212552" src="https://github.com/user-attachments/assets/6fc64959-d118-4174-a0e9-971bab965e04" />

<img width="564" height="204" alt="Captura de pantalla 2025-09-19 221438" src="https://github.com/user-attachments/assets/36f32016-3b6b-46d0-877d-9ad9bfbce242" />

Paso 6: Se equipo añadió 'policies' o reglas de negocio que hacen que se ejecuten eventos de dominio

<img width="886" height="907" alt="Captura de pantalla 2025-09-19 223550" src="https://github.com/user-attachments/assets/101ae7b9-5c4b-41c1-9ead-c6b1953c79de" />

<img width="1667" height="665" alt="Captura de pantalla 2025-09-19 223615" src="https://github.com/user-attachments/assets/975057e6-eb8a-4218-a3b6-2939677a66aa" />

<img width="1147" height="726" alt="Captura de pantalla 2025-09-19 223624" src="https://github.com/user-attachments/assets/b7d32622-f539-4e41-a1e6-841c0bed1a7e" />

<img width="1645" height="703" alt="Captura de pantalla 2025-09-19 223654" src="https://github.com/user-attachments/assets/9fad0aad-fbfb-44f0-ab66-4b0738493420" />

Paso 7: Se añadió read models, son la vista de datos o 'views' que ayudarán al usuario con la ejecución de comandos
<img width="1238" height="869" alt="Captura de pantalla 2025-09-19 230749" src="https://github.com/user-attachments/assets/c4346d99-f430-426b-b6ba-c910b5e13c23" />

<img width="1260" height="598" alt="Captura de pantalla 2025-09-19 230805" src="https://github.com/user-attachments/assets/e7ac4a05-a46c-4e10-b1cd-546c29a5e473" />
<img width="1584" height="646" alt="Captura de pantalla 2025-09-19 230929" src="https://github.com/user-attachments/assets/c6d61487-5e4e-45c4-8320-bdff22619956" />

<img width="1248" height="698" alt="Captura de pantalla 2025-09-19 231216" src="https://github.com/user-attachments/assets/533aeba4-d436-4766-99bb-783a1458671f" />


<img width="1765" height="335" alt="Captura de pantalla 2025-09-19 231454" src="https://github.com/user-attachments/assets/773e4adf-7ec9-431a-870d-afad72233b93" />

<img width="1704" height="612" alt="Captura de pantalla 2025-09-19 231604" src="https://github.com/user-attachments/assets/ad6f7ffe-5bb5-466f-88ce-6d5ed74175f2" />

Paso 8: Se identifico sistemas externos, tales como el servicio de guardado de imagenes en la nube, por ahora va como "Cloud Storage"

<img width="1720" height="867" alt="Captura de pantalla 2025-09-19 232402" src="https://github.com/user-attachments/assets/6000d670-f2f7-408e-9bc4-43128d9d393f" />

<img width="1686" height="344" alt="Captura de pantalla 2025-09-19 232414" src="https://github.com/user-attachments/assets/2e4369dd-cf11-4fdb-939e-6160f4e18754" />

<img width="1660" height="646" alt="Captura de pantalla 2025-09-19 233559" src="https://github.com/user-attachments/assets/39acdbd3-b116-4a1e-a71a-66e21fd075e8" />


Paso 9: Se identifico los aggregates

<img width="1135" height="849" alt="Captura de pantalla 2025-09-19 233815" src="https://github.com/user-attachments/assets/82d0bb24-af97-4b17-9db5-df1b115accc0" />

<img width="1097" height="895" alt="Captura de pantalla 2025-09-19 233836" src="https://github.com/user-attachments/assets/ad91e710-c9fd-47a7-979f-713a2ef3527b" />

<img width="1744" height="777" alt="Captura de pantalla 2025-09-19 233848" src="https://github.com/user-attachments/assets/d6a7f7c0-1c97-4b20-9e3f-a1256a7293da" />

Paso 10: Separamos por bounded context, en los cuales algunos tienen un cierto tipo de relación medianto comando y domain

<img width="1282" height="796" alt="Captura de pantalla 2025-09-19 235313" src="https://github.com/user-attachments/assets/dbbf1b20-404a-4a80-b6c6-51e7b46dc6de" />

<img width="1233" height="854" alt="Captura de pantalla 2025-09-19 235338" src="https://github.com/user-attachments/assets/0ac45724-d0d6-45cf-9ef9-bdc3c4e24dc1" />

<img width="1095" height="880" alt="Captura de pantalla 2025-09-19 235354" src="https://github.com/user-attachments/assets/0e669fd7-4592-4dc7-9df0-f34998417fb4" />
<img width="1547" height="894" alt="Captura de pantalla 2025-09-19 235408" src="https://github.com/user-attachments/assets/3dc9efc2-bfd0-4b09-af46-15462c8b84db" />

<img width="1333" height="813" alt="Captura de pantalla 2025-09-19 235416" src="https://github.com/user-attachments/assets/fe95ed97-42b8-42af-a1d0-04e3bc09e9d0" />


### 4.6.2. Software Architecture Context Diagram.

El diagrama de contexto muestra a los dos actores principales —**Encargado** y **Trabajador**— interactuando con la plataforma **SafeWork**, así como la relación con los contenedores principales.  
Este nivel refleja la visión global del sistema y cómo los usuarios acceden a él.  

![imgs](./imgs/contextdiagram.png)

### 4.6.3. Software Architecture Container Diagrams.

El diagrama de contenedores descompone **SafeWork** en sus partes principales:  
- **Landing Page** como punto de entrada.  
- **Web App** para la interacción de usuarios.  
- **API REST** que centraliza la lógica de negocio.  
- Los 5 **Bounded Contexts**: *Incidents, Assignment, Notification, Analytics y Profile*.  

![imgs](./imgs/containterdiagram.png)

### 4.6.4. Software Architecture Components Diagrams.

#### 1. Incident Service 
Gestiona el ciclo de vida de los incidentes, desde su creación hasta su cierre.  
Incluye la máquina de estados, el agregado de dominio y el repositorio para persistencia. 

![imgs](./imgs/component1.png)

#### 2. Assignment Service
Contiene la lógica de asignación de responsables y reglas de SLA.  
Su motor central define a quién se asigna un incidente y maneja la reasignación automática.

![imgs](./imgs/component2.png)

#### 3. Notification Service
Responsable de enviar notificaciones vía push, SMS o correo electrónico.  
Se abstrae mediante un adaptador que permite integrar distintos proveedores de mensajería. 

![imgs](./imgs/component3.png)

#### 4. Analytics & Reporting
Procesa los eventos publicados en el **Event Bus** para generar reportes, métricas y dashboards en tiempo real.  
Se apoya en un pipeline de eventos y un almacén analítico.  

![imgs](./imgs/component4.png)

#### 5. Auth Service 
Encargado de la autenticación y autorización de usuarios.  
Implementa SSO, OAuth2 y JWT para validar identidad y permisos de acceso.

![imgs](./imgs/component5.png)

## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.

### Incident
El diagrama de **Incident** modela cómo se gestiona un incidente dentro del sistema.  
Incluye los estados principales de un incidente (registrado, en proceso, resuelto, cerrado) y su relación con la clase `Incident`, lo que permite entender el ciclo de vida y las transiciones que puede tener.  

![Incident](https://www.plantuml.com/plantuml/dpng/VLLDRlCs4Dtx5CItgOr-zW64m8XZgwc0r0xyaqsG1KEERQ8IAP0ZDqQH4_K8tULaZIIEND6IT-BClCVvUKFTE-GMYomTeC8KMAA5ag3HiGTJQ0cIpOr6-40sPlEKEySMYXyipmQ3d8i_-G7O3qMO2S_pL0cEokWVxEy1OwA4DAGRi2SbeF8mzYiJ5ZW2UOTL1j46hTA7dqo24yt1GcuiWarajDibYn6B6bBFnQMScomhUIWV7_oJYTeH-O0IVJ9A4XAHYsDyAZ42hj7WFH6517YH6jSK4SB_5_iv-EnicZGPLtgI6GbftJNGHNPf6d8i7FLizHmlwwza-H9ljidZR9ii7slJRBD97fVneZwjuytgwOLEywVLflh-7D0DLC_sd0FnF_--sgxgpyLglliZNcxhqqkoY5S4Ru_LOyTCoOYLHVjZCxIskHupgqVhRUMmhSfBuGGULvKV1UsedLv0SeOHMt24hSh0UufSzdXedD-SJyhX7NLXMlj9BEJscfbUPDOe1KvTaWZ4U5jxuiZr0UgQXhxKTgK4QBUUxkrhVM7Je8zupY5gZRpDwFFh8-G57itL9E43wPh-YToGlj9xontQGc1XeUl9M4Dkd49ZpyshuVZfigNKhR2nUwNbmpcHGzNpOb38xTvx4P1vshq0C-SWUq_1DZcYYJKgFFzcJRO6PmehO6ZXSW4Ph_CYh0BdqRdHhaBd3Poi_HagZM3tN00BhYJDj0RSkQhNYzgtfdNtMgP622rhivPaxK-NIgHqIJJHLK6lRpSabbjmeB7w9qs4oRuvItkNrif6ihkx9cWwxR_xzOrzQp0lSEIdPa5BiCDHjq8MW5obDyalt06pEvg_QhmBwMcTTtbgk0GRNk0PYifDmSEzQdwpeyv7uC5yz32vuZrJI6zRkVz4H2FuXQqXhRhjZYftW_3VFnvFEvRxPbZZzDRMZu2gAdtjv-rwEqFIm3sPJA-N9M9V_w3bsksDpTpNlxTnfDfk7AciNKWLMasyYIB1zCU5as-LNqNM2rZUV9bg5UMFGT0zQ5bawNy0)

---

### Assignment
El diagrama de **Assignment** describe cómo se asigna un incidente o tarea a un usuario.  
Incluye la entidad `Assignment` con atributos clave (responsable, fecha de asignación, estado) y muestra la relación con `Incident` y `User`, reflejando la trazabilidad de quién está encargado de resolver un caso.  

![Assignment](https://www.plantuml.com/plantuml/dpng/XLLTRXen47xd55PUkYY50wmY5BBG22bD42HzYQBANG_4ojfUsRD9KPKJzGXzoycAbpKx0GDlxCmtttppC-RI8RTOgQA34WjWG-VaKYlGoAvCfGK8bXcDy1jPZsK5TuwD95zQhZgTakSlV0diZ6-3-hmi2vbpb4QViJyTnd8VGsZdO5zb3hMFiNEMM-08hJ-HEfS2D4v4-l0m6Nrb6tQ0T0C2wBAK43OyFl5gVZDCWXZ2u0gUhbq-xjL84J8RLHP0SpUnJHo1ltVUu-KAexZKVMK459jwGLUAbeiSAnUgdOvlHvFRwyt7CCl6q_lnQFCrkVqvdTrTpyRp-SQGtNsVteozt-UFTB8XxJ4fKkO5Xy-sWSJSjf65FZOEtnssRa_uh1MdUpLyfX53JDc88znB5OX2G_TzvqtOlKag1vPEaav4SVkI1PA4EDlwlT13XOiAVDOzNQMLnafShQj4A_Korb20GwoQAo2HtcHDGKq7jqFgXUKERPLZPI5-3pCeZPDex6fx4ew_0bdZj0Nlz6iXjRXQJVoy8vVZmJVIuKKRFpYqI-jVe7uLOBSYq8mrIbnziqRDm9dAvf1OS4HDCCVkCSHBS0r3QRIh6Kf24Up7j4gDO1Sy1xQVkf5BHnRV_x3zr1XMdGwNhdSmHsLG-K56EpENHiG-FXrRbjA20utrqzdtfsIq9uflpPNXLh2BYorkC3YkuV699LAN5NQR-GZfoeAlMeHBkeUs8pkTZERQoMH12x24FTpn3mblKThm8kqGkMVpvb_uRcZZ5pQ3ecwOUvQbw-p_o_HwW-YjdOGI0F40xDYzoYYKFfoHCzi1HY7z_Y2syIdx-8kMQxSmLhcFVwTZmvh6O-b6xSYgyVK8Fa6p4yWmsgO_dtoNe4MbYly0)

---

### Notification
El diagrama de **Notification** muestra cómo se gestionan las notificaciones generadas por los eventos del sistema.  
Incluye la clase `Notification` y atributos como tipo, fecha, estado de lectura, así como las transiciones que indican si un usuario ya visualizó la alerta o si permanece pendiente.  

![Notification](https://www.plantuml.com/plantuml/dpng/bLNDJXin4BxdAImk3MgJ1rYX24f26mcYYC09SJ3hIJBgUhpop5AYYYVg8_J6apNPEC5BlO7Ul3FVVFFZpxEdBDfBPOkEe1IW9avmZhaMTAI-keeC67NkIE19L4-T5vfP3L4llBQTJgdp7te1weYYiBukooASZzIlZb9v7HLJpy0_OWwrLwdFYe5CxE_6X5diELQPUdHeGc2DMuqfHmCaPyou80iaNGociSbkRyV3Byf3ZYM-MYAYvyvpMo_6MOtKjyv0iMq6gBADNcvMvRwHqTNP-79xd5tDjeVfxUnxdIGLF1Cj5U_2fwF9S3pv5WX6avljwM9DEXe6ZiGqGtXFeSdKfhVm6RSSswFPn6OBp7e1cPg9Hre4gwpRo_vfE3YvBZzBjBG3R6v5CZNK0ZTeuV2qaUPUi_Wgbyf3ctYkeNICulpgLJ_w4JwicJcIcG8Pf4Ltuxf4bfCOFsWVzHaps8S2_3wrk149okh2EtiDx2gVGzS3DohOEJRfOdkJ0u43I-c8QvQoIHCyXwj64l1pdODAbH0AZwMI5afI9YcH18b4XY2BXYa88PWEbnhQ3ALIvE8isTJT_OvHFx1udKlYxiwNcWYAnj8vB9e7vmhGr9J3o6eiTbpm940ccMSViDu4_mEVLhpy2Bxr5PKU64Ys7xcpfICWuRRdj16IEZdP0mU3z-T-Tw-wI6Kbns6M7iY0xnwtlvonW7qtJJFBcnoyT3z3XdMEJ-eQYcrjIoova_gzz7g3bitH1azEEhO5K7CR7aQ4XPXU8s_1BR1-Vv1-pPbw-IrU4y-Tj_povuFnuOaTZ0_IU5jX7L9VJ437DtmOVGfaAbly1G00)  

---

### Analytics
El diagrama de **Analytics** modela la recolección y análisis de datos del sistema.  
Se centra en la clase `Analytics`, donde se registran métricas, reportes y eventos. Permite visualizar cómo se transforman los datos de incidentes y asignaciones en estadísticas útiles para la toma de decisiones.  

![Analytics](https://www.plantuml.com/plantuml/dpng/TLN1Rjim3BtxAuHSbcw8iLsD8cZNR421xTAkkmmxi1AR4fCbGwJJ1KE_Q9-mMxziZYqfTLtV8lBnlIVpsJbZWI1jRGiXiQZE7TYza6RrqRVEe54NtWd-5hLI5nQOrOPW6w0kYWRqBzYYMa2QAQ5fB6aGycwX_XHAwNuaarvZs976lgNKExL5Xm44BvqcWqwkiF51bXIFbwQwkRdSdAXA3Pqufi7greBWju3EyF80-48ifrzH0kbr1tii7bzrQ7mDvChQ6xJFB4R-Q6obo5Jg81sFoQSvbqfj3i9KO-pLlIQF7KIZOCnGMDRLyEDWTUV9z1Qp-j2RKtTGOwMkEuZRnj8ER8kT5T_UscIaTIGPDgBV0D_VUWWcAuJ-kidqSFbasX0t5lP3aPVPyVn39NSNW2MqMjg0hsx-mCOaFkppyXbs61S-sAc6KnPC6P6ZbR7Xtj9KwvmPwrkB8Kk9_-I4PFyv-FeAsRT1OoVAKJ6L9a6BSuGS9nllk9ziucYgpLaZ9nZkGACQIqLheqsFKdPSTqvOZ4cY-F5pAX8HyoAJC4sZD0tII69yxoYHyvIxsU9iQfg0Z4xwhqMfVTtnTKUUlfNV2H_KwMc6hDSZrIIgbkIQLavIlExzm_9avaMOfJG9KHt1BuW3EeCXKdVaRpfzsz-2xwdXOlArMwtMhxq8HRIz-B3e86hnlYpVBk86Yom-RgTuJhFUgyntotBzCe6LUleh0HpV-L3pqx_PiT72fsFFbdJqqCFwnzOXycKoA5T6k3Dqvl1Nz1y0)  



---

### Profile
El diagrama de **Profile** describe la información del perfil de usuario.  
Incluye atributos como datos personales, roles, permisos y estado de la cuenta. También muestra cómo se relaciona el perfil con otras entidades del sistema, como notificaciones y asignaciones, asegurando la personalización de la experiencia de cada usuario.  

![Profile](https://www.plantuml.com/plantuml/dpng/bLNDRjD04BxxAKQva02nu6fLLaaBKYKEAALSgXwstaawmjwrTjOj4UeJyGZS-cJOcusLNMz0N19bvlk--PalzZbROMpNr9abMoDyCNf3_VTATqgYX0kjBFwmi8IBMZ339Ocj4KsMjQBwBhO8itRFo4NRrbG9IrhDu6S6K3c25xn6yqWLkWJ06-XQAIokICyz_qeMDpTNbs_XddHnRGsfxG8AUDGaFKL8UO76qiPNcJ2hFbi4a5Y1cRPghMkSS4qVB8RC4UKvUqxCANKZIEMDbbWd1lKJBe5a0OEs_zancgiWv2Q5_QW-KXqtpmLy9hPdmKIbHmxz7W13s-Mf9VtFKj9B62SCL4xDwMmKZKNC7ShLBXM-5BQ73vzVgS6mu5gVtgSIJLocHTCGyz7gzkdov2r9ROnWQxhATWOJrrnZgvciDhlHkImUH_iK7XQjT4Egd_R6NNpk3p-qFi0y8npK1pymOtDVencBMVrHMRAxJqOtQsJTcGhd1lbG-10BbO-OXEovhLRikEr8zi45-7NvU7beZfH5in4LGbJEznUS93PuRE_OtA6T3igtTmxhxJqO8CX4RKqbqirDNPdsv94ZVJGk6RIKgXJxCd2bZwT6YMxYfRtFs5yttaRIrAr1HcNTJl9ADxqUAii9TtyZV8Apin5Jbc7PiIhCIRMTNNXlyOD-cY-c_zMLa5kS2lfxkdF6KfAuhSKkKWiFEtWpLlstesxleb86bKJZA_MrNi4QwptrWLhEeZVLSbbEdm9_0HrIC7i_w-CmUvVdhsTXJscCsqiMFmCYxIYPvsLi2IZWvPSrGl56cuPVVgTPiT7IB6-EenuSq2sqnupNTeYrZjAJypbO40tmvwXarzH_0000)  

## 4.8. Database Design.
### 4.8.1. Database Diagrams.

En esta sección se presentan los diagramas de base de datos correspondientes a cada Bounded Context del sistema. 
Los diagramas muestran las tablas, sus columnas, tipos de datos, claves primarias y foráneas, 
así como las relaciones entre las tablas, garantizando la persistencia correcta de la información.

![DatabaseDiagram](./imgs/DatabaseDiagram.png)

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.

A continuación, se detallan las herramientas de software empleadas durante el desarrollo de nuestro proyecto.

* Gestión de Proyectos

- **WhatsApp**: [https://www.whatsapp.com](https://www.whatsapp.com)   
  Utilizamos WhatsApp como canal principal de comunicación para coordinar tareas, compartir ideas y brindar soporte entre los miembros del equipo durante todo el proceso de desarrollo.

* Diseño UX/UI del Producto  
    
- **Uxpressia:** [https://uxpressia.com/](https://uxpressia.com/)   
  Con esta herramienta desarrollamos las User Personas, Mapas de Empatía y Journey Maps, facilitando así el entendimiento profundo de nuestros usuarios.  
    
- **Figma:** [https://www.figma.com/](https://www.figma.com/)   
  Figma fue nuestra herramienta principal para crear wireframes, wireflows, prototipos y maquetas de la landing page y las aplicaciones web.  
  


* Desarrollo de Software

- **Landing Page**:  
  La página principal del proyecto fue desarrollada utilizando tecnologías estándar como HTML5, CSS y JavaScript.

* Pruebas de Software

- **Navegador**:  
  Las pruebas del sitio web y la aplicación se llevaron a cabo mediante las herramientas de desarrollo integradas en los navegadores Google Chrome, Brave, Opera y Edge.

* Entornos de Desarrollo (IDE)

- **Visual Studio Code**: [https://code.visualstudio.com](https://code.visualstudio.com)  
  Visual Studio Code fue nuestro entorno de desarrollo secundario para las pruebas debido a su ligereza, amplia disponibilidad de extensiones.  
    
- **IntelliJ IDEA:** [https://www.jetbrains.com/idea](https://www.jetbrains.com/idea)   
  IntelliJ IDEA fue nuestro entorno de desarrollo preferido para el proyecto debido a su funcionalidad, compatibilidad y a nuestra habilidad general con el IDE.

* Despliegue de Software

- **GitHub Pages**: [https://pages.github.com/](https://pages.github.com/)   
  GitHub fue clave para la documentación colaborativa del proyecto, permitiendo la trazabilidad de cambios mediante commits y GitFlow.


* Documentación de Software

- **Google Docs**: [https://docs.google.com/document](https://docs.google.com/document)   
  Google Docs nos permitió hacer seguimiento de tareas y compartir información relevante entre los integrantes del equipo.  
    
- **GitHub**: [https://github.com/](https://github.com/)   
  GitHub fue clave para la documentación colaborativa del proyecto, permitiendo la trazabilidad de cambios mediante commits y GitFlow.
  
### 5.1.2. Source Code Management.
Para administrar y organizar los cambios realizados en el proyecto, creamos un repositorio en GitHub que centralizó el desarrollo. La estructura fue la siguiente:

* Organización

- **Repositorio en GitHub**: [https://github.com/NexoraPe](https://github.com/NexoraPe)   
    
- **Landing Page**: [https://github.com/NexoraPe](https://nexorape.github.io/Landing-Page/)

* Ramas Principales

- **Rama main**:  
  Contiene la versión estable del proyecto, lista para ser puesta en producción.  
    
- **Rama docs/**:  
  Contiene la documentación general del proyecto.
  
### 5.1.3. Source Code Style Guide & Conventions.
Para lograr una legibilidad y calidad de código excelente, adoptamos una serie de convenciones específicas para cada tecnología utilizada en el desarrollo de la Landing Page y la Aplicación Web.

* HTML  
    
- Tipo de Documento: Cada archivo HTML inicia con \<\!DOCTYPE html\> para asegurar su correcta interpretación por los navegadores.  
    
- Etiquetas en Minúsculas: Todas las etiquetas y atributos se escriben en minúscula.  
    
- Cierre Correcto de Etiquetas: Nos aseguramos de cerrar todas las etiquetas, incluso las opcionales, para mantener una estructura clara y evitar errores.  
    
- Atributos entre Comillas: Los valores de los atributos siempre están entre comillas dobles.  
    
- Imágenes Accesibles: Incluimos los atributos alt, width y height en las imágenes, lo cual mejora tanto la accesibilidad como el diseño adaptable.  
    
- Formato Limpio en Atributos: No se colocan espacios alrededor del signo igual, por ejemplo.  
    
- Uso del Elemento \<title\>: No se omite el título de la página, ya que es fundamental para el SEO y la accesibilidad.  
    
- Idioma y Codificación: Se declara el idioma con el atributo lang.

* CSS

- **Recursos Seguros**: Todos los recursos externos, como fuentes y multimedia, se cargan mediante HTTPS.  
    
- **Nombres en Minúsculas**: Los selectores, propiedades y valores se escriben en minúsculas para mantener un estilo uniforme.  
    
- **Nombres de Clase Descriptivos**: Las clases CSS reflejan su función usando palabras clave separadas por guiones.  
    
- **Propiedades Abreviadas**: Se aplican propiedades abreviadas siempre que sea posible para optimizar el tamaño del código.  
    
- **Orden Alfabético**: Las propiedades CSS dentro de un bloque se ordenan alfabéticamente para facilitar la lectura y mantenimiento.  
    
- **Uso Consistente del Punto y Coma**: Cada línea termina con un punto y coma para evitar errores de interpretación.  
    
- **Espaciado Uniforme**: Se mantiene un espacio después de los dos puntos y dentro de las llaves de los bloques.  
    
- **Comillas en Atributos**: Los valores como fuentes están entre comillas simples.

### 5.1.4. Software Deployment Configuration.


## 5.2. Landing Page, Services & Applications Implementation.
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1.

| Sprint \# | Sprint 1 |
| :---: | :---: |
| Sprint Planning Background |  |
| Date | 2025-09-12 |
| Time | 17:20 PM |
| Location | Aula H-51, después de las clases (previamente acabadas) \+ Remota |
| Prepared By | SafeWork |
| Attendees (to planning meeting) | Amir Gabriel Castro Sánchez / Guillermo Fabián Tantaleán Mesta / Miguel Angel Vidal Castro / Diego Alonso Cacho Seminario |
| Sprint Goal & User Stories |  |
| Sprint 1 Goal | Nuestro enfoque está en desarrollar y desplegar una landing page funcional que presente eficazmente nuestro producto. Creemos que esto genera una primera interacción positiva y clara con potenciales clientes, facilitando su comprensión y conexión inicial con la propuesta de valor. Esto se confirmará cuando recibamos las primeras visitas y observemos señales básicas de interés, como clics en elementos clave, navegación dentro de la página y comentarios iniciales de usuarios o colegas. |
| Sprint 1 Velocity | 15 |
| Sum of Story Points | 15 |

#### 5.2.1.2. Aspect Leaders and Collaborators.

| Team Member (Last Name, First Name) | GitHub Username | UI/UX Design (L/C) | Landing Page Development (L/C) | Quality Control (L/C) | Documentation (L/C) |
|-------------------------------------|-----------------|---------------------|---------------------|---|---------------------|
| Castro Sánchez, Amir Gabriel       | AmirbarrabajaLeon   | C                   | C                   | C | L                   |
| Vidal Castro, Miguel Angel        | Gossk              | L                   | L                   | C | C                   |
| Tantaleán Mesta, Guillermo Fabián   | guillermotantalean1   | C                   | C                   | L | C                   |
| Diego Alonso, Cacho Seminario        | Memesitos          | C                   | C                   | L | L                   |


#### 5.2.1.3. Sprint Backlog 1.

**Objetivo:** Desarrollar y desplegar una landing page funcional que cumpla con todas las historias de usuario especificadas para la interacción inicial con clientes y presentación del producto.

**Alcance:**

* Implementar barra de navegación responsive  
* Crear componentes de llamada a la acción (CTA)  
* Desarrollar sección de beneficios del servicio  
* Construir tarjetas interactivas de servicios  
* Implementar funcionalidad de preguntas frecuentes (FAQ)  
* Colocar los nuevos puntos a la documentación del trabajo

**Duración:** 25 de Agosto \- 20 de Septiembre de 2025

**Capacidad de equipo:** 120 horas totales \- 4 integrantes

**Requisitos técnicos:** Google Docs, GitHub, HTML, CSS, JS

| Task ID | User Story | Description | Assigned To | Estimated Hours | Status | Epic |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| T01 | US01 | Navegación Intuitiva en la Landing Page | Vidal Castro, Miguel Angel | 5 | Completed | EP01 |
| T02 | US01 | Implementación de diseño claro dentro del UI | Vidal Castro, Miguel Angel | 3 | Completed | EP01 |
| T03 | US02 | Visualización de Beneficios | Vidal Castro, Miguel Angel | 3 | Completed | EP01 |
| T04 | US02 | Visualización de Secciones About Us | Vidal Castro, Miguel Angel | 2 | Completed | EP01 |
| T05 | US41 | Desarrollar botones CTA principales en el Landing Page | Cacho Seminario, Diego Alonso | 4 | Completed | EP01 |
| T06 | US03 | Acceso a Testimonios | Cacho Seminario, Diego Alonso | 2 | Completed | EP01 |
| T07 | US42 | Sección de Preguntas Frecuentes (FAQ) | Castro Sanchez, Amir Gabriel | 6 | Completed | EP01 |
| T08 | US06 | Diseñar componentes de navegación en Figma | Tantaleán Mesta, Guillermo Fabián | 4 | Completed | EP01 |
| T09 | US43 | Sección de Membresía y Planes | Tantaleán Mesta, Guillermo Fabián | 4 | Completed | EP01 |
| T10 | US07 | Implementar barra de navegación responsive | Tantaleán Mesta, Guillermo Fabián | 5 | Completed | EP01 |
| T11 | US07 | Implementación de componentes funcionales | Tantaleán Mesta, Guillermo Fabián | 3 | Completed | EP01 |

#### 5.2.1.4. Development Evidence for Sprint Review.
En el alcance del sprint 1 se ha desarrollado el landing page como primera instancia, por lo que no se evidencia testeo de servicios o interacciones.

#### 5.2.1.5. Execution Evidence for Sprint Review.
Se evidencia el avance del Primer Sprint por medio del siguiente link: [https://nexorape.github.io/Landing-Page/](https://nexorape.github.io/Landing-Page/) 

#### 5.2.1.6. Services Documentation Evidence for Sprint Review.
En el primer Sprint solamente se ha desarrollado la Landing Page por lo que no se ha hecho uso de servicios web.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review.
Link del Landing Page: [https://nexorape.github.io/Landing-Page/](https://nexorape.github.io/Landing-Page/) 

#### 5.2.1.8. Team Collaboration Insights during Sprint.
<img width="911" height="825" alt="Captura de pantalla 2025-09-20 034403" src="https://github.com/user-attachments/assets/b3d3a865-39ff-41c8-8352-a26f2960a093" />

#### 5.2.2. Sprint 2
#### 5.2.2.1. Sprint Planning 2.

*  Sprint Details

| Sprint \# | Sprint 2 |
| :---: | :---: |
| Sprint Planning Background |  |
| Date | 2025-09-28 |
| Time | 17:20 PM |
| Location | Aula H-51, después de las clases (previamente acabadas) \+ Remota |
| Prepared By | SafeWork |
| Attendees (to planning meeting) | Amir Gabriel Castro Sánchez / Guillermo Fabián Tantaleán Mesta / Miguel Angel Vidal Castro / Diego Alonso Cacho Seminario |
| Sprint 1 Review Summary | Para el Sprint 1, realizamos la estructura principal del documento además de la primera versión del Landing Page. |
| Sprint 1 Retrospective Summary | Durante el Sprint 1, realizamos entrevistas a nuestros segmentos objetivos lo que nos permitió conocer más sus necesidades y realizar un Landing Page que le permita a estos usuarios conocer nuestro producto. |
| Sprint Goal & User Stories |  |
| Sprint 2 Goal | Para el Sprint 2, buscamos desarrollar y desplegar un Frontend funcional para SafeWork utilizando tecnologías JSON servers y Fake API. |
| Sprint 2 Velocity | \# |
| Sum of Story Points | \# |

##### 

##### 5.2.2.2. Aspect Leaders and Collaborators.

| Team Member (Last Name, First Name) | GitHub Username | UI/UX Design (L/C) | Frontend Development (L/C) | Quality Control (L/C) | Documentation (L/C) |
| ----- | ----- | ----- | ----- | ----- | ----- |
| Castro Sánchez, Amir Gabriel | AmirbarrabajaLeon | C | C | C | L |
| Vidal Castro, Miguel Angel | Gossk | L | L | C | C |
| Tantaleán Mesta, Guillermo Fabián | guillermotantalean1 | C | C | L | C |
| Diego Alonso, Cacho Seminario | Memesitos | C | C | L | L |

##### 

##### 5.2.2.3. Sprint Backlog 2.

**Objetivo:** Desarrollar y desplegar un Frontend funcional para SafeWork utilizando tecnologías de JSON servers.

**Alcance:**

* Implementar un Fake API para la obtención de la información  
* Aplicar seguridades básicas  
* Verificar las correcciones del Sprint 1  
* Actualizar el Landing Page con los enlaces del Frontend 

**Duración:** 20 de Septiembre \- 08 de Octubre de 2025

**Capacidad de equipo:** 140 horas totales \- 4 integrantes

**Requisitos técnicos:** Google Docs, GitHub, Angular CLI, NodeJS, WebStorm IDE

| Task ID | User Story | Description | Assigned To | Estimated Hours | Status | Epic |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| T01 | US09 | Generar un reporte de Accidente | Vidal Castro, Miguel Angel | 4 | Completed | EP04 |
| T02 | US10 | Generar un reporte de Incidente | Vidal Castro, Miguel Angel | 4 | Completed | EP04 |
| T03 | US12 | Revisión de Reportes | Vidal Castro, Miguel Angel | 4 | Completed | EP05 |
| T04 | US15 | Visualizar Estado del Reporte | Vidal Castro, Miguel Angel | 3 | Completed | EP05 |
| T05 | US25 | Visualizar notas internas del caso | Cacho Seminario, Diego Alonso | 3 | Completed | EP09 |
| T06 | US28 | Visualización de reportes en pantalla (sin descarga) | Cacho Seminario, Diego Alonso | 2 | Completed | EP07 |
| T07 | US12 | Visualización de lista de reportes | Castro Sanchez, Amir Gabriel | 4 | Completed | EP05 |
| T08 | US36 | Validación de campos obligatorios en registro | Tantaleán Mesta, Guillermo Fabián | 4 | Completed | EP06 |
| T09 | US04 | Registro de Usuario | Tantaleán Mesta, Guillermo Fabián | 5 | Completed | EP02 |
| T10 | US05 | Inicio de Sesión Seguro | Cacho Seminario, Diego Alonso | 5 | Completed | EP02 |
| T11 | \- | Avance del Documento | Tantaleán Mesta, Guillermo Fabián | 5 | Completed | \- |
| T12 | \- | Organización del Código | Tantaleán Mesta, Guillermo Fabián | 3 | Completed | \- |

##### 5.2.2.4. Development Evidence for Sprint Review.

| Repository | Branch | Commit ID | Commit Message | Committed on (Date) |
| ----- | :---: | :---: | ----- | :---: |
| [https://github.com/NexoraPe/report?tab=readme-ov-file\#5213-sprint-backlog-1](https://github.com/NexoraPe/report?tab=readme-ov-file#5213-sprint-backlog-1)  | feature/Diego | 61fb7b1 | docs: fixed TB1 User Stores/Sprint Planning 1 issues | 04/10/2025 |
|  | feature/Diego | cb3c354 | docs: add Sprint 2 version 1 | 04/10/2025 |
|  | main/front-safework | ab2dd02 | chore: add db.json, routes.json for json-server setup and start-scripts for fake api | 29/09/2025 |
|  | develop/front-safework | 99081b1 | chore: add db.json, routes.json for json-server setup and start-scripts for fake api | 06/10/2025 |
|  | feature/incidents | 5958200 | feat(incidents): add incidents-list.ts | 07/10/2025 |
|  | feature/profile | 4db6b83 | feat(profile): add working profile screen with working database data | 08/10/2025 |

##### 

##### 5.2.2.5. Execution Evidence for Sprint Review.

Se evidencia el avance del Segundo Sprint por medio del siguiente link: link frontend desplegado

##### 5.2.2.6. Services Documentation Evidence for Sprint Review.

Se evidencia la documentación de los servicios empleados:  
imgs

##### 5.2.2.7. Software Deployment Evidence for Sprint Review.

Link del Frontend: link frontend desplegado 

##### 

##### 5.2.2.8. Team Collaboration Insights during Sprint.

imgs github con gitflow

---

# Conclusiones
## Conclusiones y recomendaciones.

- TB1:

La propuesta de **SafeWork** surge como una respuesta directa a las necesidades identificadas en el ámbito de la seguridad y salud en el trabajo. Su idea de valor se centra en ofrecer a trabajadores y personal de SST una plataforma confiable, ágil y transparente para reportar, gestionar y dar seguimiento a accidentes e incidentes laborales. A diferencia de los sistemas internos tradicionales, que suelen presentar fallas técnicas, procesos burocráticos o limitaciones de acceso, SafeWork busca garantizar que cada reporte sea rápido de registrar, fácil de rastrear y seguro en el manejo de la información.

En conjunto, lo avanzado hasta la entrega TB1 permite concluir que **SafeWork** representa una solución innovadora y viable para digitalizar, simplificar y dar transparencia al proceso de gestión de incidentes laborales, aportando valor tanto a los trabajadores que buscan seguridad y claridad como al personal de SST que requiere herramientas efectivas para gestionar casos y tomar decisiones preventivas. 

- TP:

Durante la etapa de entrega del TP, **SafeWork** alcanzó un avance significativo al dar sus primeros pasos técnicos hacia una versión funcional de la plataforma. Se desplegó la primera versión del frontend, utilizando Microsoft Azure para el mock API y GitHub Pages para la publicación del entorno web, lo que permitió validar la estructura base de la interfaz de usuario y sentar las bases para futuras integraciones con el backend.

Asimismo, se incorporó el Sprint 2, ampliando las funcionalidades planificadas y fortaleciendo la hoja de ruta del desarrollo ágil. Se implementaron mejoras derivadas de las observaciones de la entrega TB1, lo que permitió afinar tanto la propuesta de valor como la estructura técnica y de diseño.

Este avance marca una etapa clave en la consolidación del proyecto, pasando de la definición conceptual y estratégica a una versión visual e interactiva que permitirá realizar pruebas tempranas, recibir retroalimentación de usuarios y continuar evolucionando hacia un producto funcional y validado en su entorno real.

---

# Bibliografía

Más de 2,800 inspecciones de accidentes de trabajo realizó la Sunafil entre el 2023 y 2024*. (n.d.). Noticias \- Superintendencia Nacional De Fiscalización Laboral \- Plataforma Del Estado Peruano. [https://www.gob.pe/institucion/sunafil/noticias/964567-mas-de-2-800-inspecciones-de-accidentes-de-trabajo-realizo-la-sunafil-entre-el-2023-y-2024](https://www.gob.pe/institucion/sunafil/noticias/964567-mas-de-2-800-inspecciones-de-accidentes-de-trabajo-realizo-la-sunafil-entre-el-2023-y-2024) 

Ewes, L., Llallihuaman, B. y Bojorquez, G. (2023). Seguridad y salud en el trabajo: prevención de accidentes y enfermedades ocupacionales en Perú (2022). Llalliq, 3(1), 199-216. [http://revistas.unasam.edu.pe/index.php/llalliq/article/view/1046](http://revistas.unasam.edu.pe/index.php/llalliq/article/view/1046) 

ISO 45001:2018(es) Sistemas de gestión de la seguridad y salud en el trabajo — Requisitos con orientación para su uso. (2018). Online Browsing Platform. [https://www.iso.org/obp/ui/#iso:std:iso:45001:ed-1:v1:es](https://www.iso.org/obp/ui/#iso:std:iso:45001:ed-1:v1:es)

Metas de los ODS pertinentes vinculados con la seguridad y la salud en el lugar de trabajo. (2024, 30 enero). International Labour Organization. [https://www.ilo.org/es/resource/metas-de-los-ods-pertinentes-vinculados-con-la-seguridad-y-la-salud-en-el](https://www.ilo.org/es/resource/metas-de-los-ods-pertinentes-vinculados-con-la-seguridad-y-la-salud-en-el)

# Anexos
- Enlace para acceder al [video de exposición de TB1](https://link.com)

- Enlace para acceder al [video de exposición de TP](https://link.com)

- Enlace para acceder al [Figma](https://www.figma.com/design/4lfYU4omqUax0rxIYtyXp1/Untitled?node-id=87-101&p=f&t=DSclDKaWIfieBQf6-0)

- Enlace para acceder a la [landing page](https://nexorape.github.io/Landing-Page/index.html)

- Enlace para acceder al [frontend](https://nexorape.github.io/)

- Enlace para acceder a la [organización de github](https://github.com/NexoraPe)

- Enlace para acceder al [repositorio de reporte](https://github.com/NexoraPe/report)

- Enlace para acceder al [repositorio de landing page](https://github.com/NexoraPe/Landing-Page)

- Enlace para acceder al [repositorio del frontend](https://github.com/NexoraPe/)


