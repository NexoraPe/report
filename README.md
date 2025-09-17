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
    <strong>Nombre del startup: </strong> [Startup]
</p>

<p align="center">
    <strong>Nombre del producto:</strong> [Producto]
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
    <strong>Agosto, 2025</strong>
</p>

---

# Registro de Versiones del Informe

| **Versión** | **Fecha** | **Autor** | **Descripción de modificación** |
|     ---     |     ---   |     ---   |             ---                 |
| 1.0 | 26/08/2025 | Anónimo | Se implementó el diseño/esqueleto del informe sobre todas las secciones|

---

# Project Report Collaboration Insights
**URL del repositorio para el Project Report:** [https://github.com/boafe/report](https://github.com/boafe/report)

Temporal => *En esta sección el equipo indica el URL del repositorio para el Project Report en la
organización de GitHub del equipo. Adicionalmente, para cada entrega explica cómo
se han desarrollado las actividades de elaboración del informe y se presenta
capturas en imagen de los analíticos de colaboración y commits en GitHub para el
repositorio del informe, realizados por los miembros del equipo. Todos los miembros
del equipo deben tener participación en la elaboración del informe. Esta sección
debe ir expandiéndose con descripciones y evidencias en cada entrega. Lo descrito y
evidenciado debe tener coherencia con el Registro de Versiones del Informe.*

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
    - [5.2.X. Sprint n](#52x-sprint-n)
      - [5.2.X.1. Sprint Planning n](#52x1-sprint-planning-n)
      - [5.2.X.2. Aspect Leaders and Collaborators](#52x2-aspect-leaders-and-collaborators)
      - [5.2.X.3. Sprint Backlog n](#52x3-sprint-backlog-n)
      - [5.2.X.4. Development Evidence for Sprint Review](#52x4-development-evidence-for-sprint-review)
      - [5.2.X.5. Execution Evidence for Sprint Review](#52x5-execution-evidence-for-sprint-review)
      - [5.2.X.6. Services Documentation Evidence for Sprint Review](#52x6-services-documentation-evidence-for-sprint-review)
      - [5.2.X.7. Software Deployment Evidence for Sprint Review](#52x7-software-deployment-evidence-for-sprint-review)
      - [5.2.X.8. Team Collaboration Insights during Sprint](#52x8-team-collaboration-insights-during-sprint)
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
| **Comunica oralmente con efectividad a diferentes rangos de audiencia** | **Cacho Seminario, Diego Alonso**<br>_**TB1**_<br>Morbi vel tortor id eros dictum venenatis id ut dui.<br>Mauris quis tellus sed nunc hendrerit vehicula ac id mauris.<br>Pellentesque volutpat tellus non ligula blandit ullamcorper quis sodales erat.<br>_**TP**_<br>[TP aqui blablablab]<br>_**TB2**_<br>[Tb2 aqui ;V blablaba]<br>_**TF**_<br>[TF aqui ;V blablabla]<br><br>**Castro Sanchez, Amir Gabriel**<br>_**TB1**_<br>Morbi vel tortor id eros dictum venenatis id ut dui.<br>Mauris quis tellus sed nunc hendrerit vehicula ac id mauris.<br>Pellentesque volutpat tellus non ligula blandit ullamcorper quis sodales erat.<br>_**TP**_<br>[TP aqui blablablab]<br>_**TB2**_<br>[Tb2 aqui ;V blablaba]<br>_**TF**_<br>[TF aqui ;V blablabla]<br><br>**Tantaleán Mesta, Guillermo Fabián**<br>_**TB1**_<br>Morbi vel tortor id eros dictum venenatis id ut dui.<br>Mauris quis tellus sed nunc hendrerit vehicula ac id mauris.<br>Pellentesque volutpat tellus non ligula blandit ullamcorper quis sodales erat.<br>_**TP**_<br>[TP aqui blablablab]<br>_**TB2**_<br>[Tb2 aqui ;V blablaba]<br>_**TF**_<br>[TF aqui ;V blablabla]<br><br>**Vidal Castro, Miguel Angel**<br>_**TB1**_<br>Morbi vel tortor id eros dictum venenatis id ut dui.<br>Mauris quis tellus sed nunc hendrerit vehicula ac id mauris.<br>Pellentesque volutpat tellus non ligula blandit ullamcorper quis sodales erat.<br>_**TP**_<br>[TP aqui blablablab]<br>_**TB2**_<br>[Tb2 aqui ;V blablaba]<br>_**TF**_<br>[TF aqui ;V blablabla]| Conclusion Aqui |
| **Comunica por escrito con efectividad a diferentes rangos de audiencia** |**Cacho Seminario, Diego Alonso**<br>_**TB1**_<br>Morbi vel tortor id eros dictum venenatis id ut dui.<br>Mauris quis tellus sed nunc hendrerit vehicula ac id mauris.<br>Pellentesque volutpat tellus non ligula blandit ullamcorper quis sodales erat.<br>_**TP**_<br>[TP aqui blablablab]<br>_**TB2**_<br>[Tb2 aqui ;V blablaba]<br>_**TF**_<br>[TF aqui ;V blablabla]<br><br>**Castro Sanchez, Amir Gabriel**<br>_**TB1**_<br>Morbi vel tortor id eros dictum venenatis id ut dui.<br>Mauris quis tellus sed nunc hendrerit vehicula ac id mauris.<br>Pellentesque volutpat tellus non ligula blandit ullamcorper quis sodales erat.<br>_**TP**_<br>[TP aqui blablablab]<br>_**TB2**_<br>[Tb2 aqui ;V blablaba]<br>_**TF**_<br>[TF aqui ;V blablabla]<br><br>**Tantaleán Mesta, Guillermo Fabián**<br>_**TB1**_<br>Morbi vel tortor id eros dictum venenatis id ut dui.<br>Mauris quis tellus sed nunc hendrerit vehicula ac id mauris.<br>Pellentesque volutpat tellus non ligula blandit ullamcorper quis sodales erat.<br>_**TP**_<br>[TP aqui blablablab]<br>_**TB2**_<br>[Tb2 aqui ;V blablaba]<br>_**TF**_<br>[TF aqui ;V blablabla]<br><br>**Vidal Castro, Miguel Angel**<br>_**TB1**_<br>Morbi vel tortor id eros dictum venenatis id ut dui.<br>Mauris quis tellus sed nunc hendrerit vehicula ac id mauris.<br>Pellentesque volutpat tellus non ligula blandit ullamcorper quis sodales erat.<br>_**TP**_<br>[TP aqui blablablab]<br>_**TB2**_<br>[Tb2 aqui ;V blablaba]<br>_**TF**_<br>[TF aqui ;V blablabla]| Conclusion Aqui |


<div style="page-break-after: always;">

---

# Capítulo I: Introducción

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
[Contenido]
### 1.1.2. Perfiles de integrantes del equipo
| Foto | Nombre y Apellidos | Código de Estudiante | Carrera | Resumen de Conocimientos y Habilidades |
|------|--------------------|----------------------|---------|----------------------------------------|
| ![Foto 1](https://github.com/user-attachments/assets/5ce9542d-aa72-4810-b37e-0b73cc5fb690) | **Diego Alonso Cacho Seminario** | u202223990 | Ingeniería de Software | EJEMPLO DE IA XDD (CAMBIARLO A TU GUSTO): Experto en desarrollo web con Vue.js, dominio de bases de datos relacionales y metodologías ágiles. Aporta habilidades en programación, documentación técnica y liderazgo de equipo. |
| ![Foto 2](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSz01csRLpbqGIyVwHlDMGyrk1jJ0VKkgej5A&s) | **Amir Gabriel Castro Sanchez** | u202310680 | Ingeniería de Software | EJEMPLO DE IA (CAMBIARLO A TU GUSTO): Conocimientos en ciberseguridad, análisis de sistemas y modelado UML. Aporta al equipo su capacidad de análisis crítico y estructuración de soluciones escalables. |
| ![Foto 3](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSyB9wYiFHRASr2QzEUpnnjQ8PDj7tmkkFJ5g&s) | **Guillermo Fabián Tantaleán Mesta** | u202311958 | Ingeniería de Software | EJEMPLO DE IA (CAMBIARLO A TU GUSTO): Especialista en machine learning y ciencia de datos. Aporta experiencia en análisis estadístico, programación en Python y visualización de datos. |
| ![Foto 4](https://github.com/user-attachments/assets/bdd14d4d-1888-4244-8a1b-842034bfa6eb) | **Miguel Angel Vidal Castro** | u202314186 | Ingeniería de Software | EJEMPLO DE IA (CAMBIARLO A TU GUSTO): Conocimientos en gestión de proyectos y optimización de procesos. Aporta al equipo su enfoque en eficiencia, coordinación y manejo de recursos. |

## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática
[Contenido]

### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements.
[Contenido]
#### 1.2.2.2. Lean UX Assumptions.
[Contenido]
#### 1.2.2.3. Lean UX Hypothesis Statements.
[Contenido]
#### 1.2.2.4. Lean UX Canvas.
[Contenido]

## 1.3. Segmentos objetivo.
[Contenido]

---

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores.
### 2.1.1. Análisis competitivo.
[Contenido]
### 2.1.2. Estrategias y tácticas frente a competidores.
[Contenido]

## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.
[Contenido]
### 2.2.2. Registro de entrevistas.
[Contenido]
### 2.2.3. Análisis de entrevistas.
[Contenido]

## 2.3. Needfinding.
### 2.3.1. User Personas.
[Contenido]
### 2.3.2. User Task Matrix.
[Contenido]
### 2.3.3. User Journey Mapping.
[Contenido]
### 2.3.4. Empathy Mapping.
[Contenido]

## 2.4. Big Picture Event Storming.
[Contenido]
## 2.5. Ubiquitous Language.
[Contenido]

---

# Capítulo III: Requirements Specification
## 3.1. User Stories.

## 3.2. Impact Mapping.

## 3.3. Product Backlog.

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
Uso de la tipografía **"Raleway"** en encabezados *(IMAGEN)*  
Fuente: [1001 Fonts - Raleway](https://www.1001fonts.com/raleway-font.html)  

**Figura 2:**  
Uso de la tipografía **"Montserrat"** en textos generales *(IMAGEN)*  
Fuente: [1001 Fonts - Montserrat](https://www.1001fonts.com/montserrat-font.html)  

---

# Colores principales  

La elección de colores en **SafeWork** refuerza la identidad visual de la marca y guía la experiencia del usuario.  
El **violeta oscuro** `#7B7DC1` se establece como principal, comunicando confianza, seguridad y modernidad, cualidades clave para una plataforma enfocada en la prevención de riesgos laborales.  

Este tono se combina con un **fondo oscuro** `#0D0C22` que aporta contraste, elegancia y reduce la fatiga visual en pantallas.  

Para garantizar una lectura clara, se utilizan textos en **blanco** y **grises suaves**, mientras que los botones y elementos interactivos mantienen un estilo llamativo pero coherente.  

En conjunto, esta paleta genera un entorno profesional, accesible y visualmente equilibrado, adaptado a dispositivos modernos.  

**Figura 1:** Colores del texto *(IMAGEN)*  
👉 [Paleta en Coolors](https://coolors.co/ffffff-000000-7b7dc1)  

**Figura 2:** Colores principales *(IMAGEN)*  
👉 [Paleta en Coolors](https://coolors.co/0d0c22-7b7dc1-5a5ca0-1a1835)  

**Figura 3:** Colores secundarios *(IMAGEN)*  
👉 [Paleta en Coolors](https://coolors.co/444654-888a9c-e1e3ec)  

**Figura 4:** Colores aplicados en wireframes *(IMAGEN)*  
👉 [Paleta en Coolors](https://coolors.co/f0f0f0-bdbdbd-b3b3b3-3f3f3f-2e2e2e)  

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

### 4.4.3. Web Applications Mock-ups.

### 4.4.4. Web Applications User Flow Diagrams.


## 4.5. Web Applications Prototyping.


## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Design-Level Event Storming.

### 4.6.2. Software Architecture Context Diagram.

### 4.6.3. Software Architecture Container Diagrams.

### 4.6.4. Software Architecture Components Diagrams.

## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.

## 4.8. Database Design.
### 4.8.1. Database Diagrams.

---

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
#### 5.2.X.8. Team Collaboration Insights during Sprint.

## 5.3. Validation Interviews.
### 5.3.1. Diseño de Entrevistas.
### 5.3.2. Registro de Entrevistas.
### 5.3.3. Evaluaciones según heurísticas.

## 5.4. Video About-the-Product.

---

# Conclusiones
## Conclusiones y recomendaciones.
## Video About-the-Team.

---

# Bibliografía

---

# Anexos




