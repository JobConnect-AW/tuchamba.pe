# Informe del Trabajo Final

**Universidad Peruana de Ciencias Aplicadas**

<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="Logo UPC">

**Ingeniería de software**

**1ASI0730 Aplicaciones Web**

**Sección:** 4381

**Profesor:** Villafuerte Bazan, Oscar Ivan 

**Nombre del StartUp:** TuChamba

**Nombre del Producto:** JobConnect


| Nombre                              | Código    |
| ----------------------------------- | ---------- |
| Chi Cruzatt, Kevin Jorge            | U202313655 |
| Paucar Meneses, Jeremy Alion         | U202019449 |
| Hallasi Saravia, Miguel Angel | U202312391 |
| Oroncoy Almeyda, Alejandro Daniel       | U202313397 |
| Cossar Sanchez, Eduardo Jose           | U202312109 |
| Mostajo Orosco, Maria Fernanda           | U202312874|

**Ciclo 2025-01**

# Registro de Versiones del Informe


| Version | Fecha      | Autor                            | Descripción de modificación                          |
| ------- | ---------- | -------------------------------- | ------------------------------------------------------ |
| 1ra    | 25/04/2025 | Chi, Paucar, Hallasi, Oroncoy, Cossar, Mostajo | TB1: Se realizo los capitulos 1, 2, 3, 4 y el primer sprint del capitulo 5 |
|


</div>

# Project Report Collaboration Insights

URL del repositorio para el proyecto: https://github.com/JobConnect-AW/tuchamba.pe

**TB1**

Para el desarrollo del informe perteneciente a la entrega TB1, se dividió la implementación de secciones de la siguiente forma
para cada integrante del equipo:


| Integrantes    | Tareas Asignadas |
| -------------- | ---------------- |
| Kevin Chi      |   2.3.1 User Persona, 3.2 User Stories, 4.7.1 Class Diagram, Diagramas C4               |
| Jeremy Paucar   | 2.3.2 User persona, 2.3.3 User Journey mapping, 2.3.4 Empathy mapping, 2.3.2 User matrix, 2.3.5. AS-IS Scenario Mapping, 4.8 Diagrama de base de datos                 |
| Miguel Hallasi | 2.2 Entrevistas, 3.2 User Stories y Diagramas c4                 |
| Alejandro Oroncoy   |  2.2 Entrevistas, Capitulo V: Product Implementation, Validation & Deployment                |
| Eduardo Cossar      | Capitulo I: Introducción,  2.1 Competidores, 4.3 Landing Page UI Desing, 4.4 Web Applications UX/UI Design, 4.7.2 Class Dictionary               |
| Maria Fernanda Mostajo     | 4.1 Style Guidelines, 4.2 Information Architecture, 4.3 Landing Page UI Desing, 4.4 Web Applications UX/UI Design                 |


**Github Collaboration Insights**

Github también presenta un timeline de las ramas principales y los procesos de merge a los que se han sometido. Todas las
ramas se crearon tomando en cuenta el diseño de GitFlow para una buena organización cuando se usa un software de control
de versiones.

Los integrantes son:

- Kevin Chi (Krillsom)
- Jeremy Paucar (asmip10)
- Miguel Hallasi (mhallasi)
- Alejandro Oroncoy (alejooroncoy)
- Eduardo Cossar (coleeeee-dev)
- Maria Fernanda Mostajo (Mafer-m30)

Se explican las ramas más prominentes:

**main:** Es representada por el color negro. Se trata de la rama principal del proyecto y se actualiza para cada entregable.<br>
**develop:** Es representada por el color azul. Se trata de la rama principal para el proceso del desarrollo del proyecto.<br>
**feature/Nombre-del-integrante**: <br>

# Contenido

1. [Capítulo I: Introducción](#capítulo-i-introducción)<br>
    1.1. [Startup Profile](#11-startup-profile)<br>
    1.1.1. [Descripción de la Startup](#111-descripción-de-la-startup)<br>
    1.1.2. [Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)<br>
    1.2. [Solution Profile](#12-solution-profile)<br>
    1.2.1 [Antecedentes y problemática](#121-antecedentes-y-problemática)<br>
    1.2.2 [Lean UX Process](#122-lean-ux-process)<br>
    1.2.2.1. [Lean UX Problem Statements](#1221-lean-ux-problem-statements)<br>
    1.2.2.2. [Lean UX Assumptions](#1222-lean-ux-assumptions)<br>
    1.2.2.3. [Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)<br>
    1.2.2.4. [Lean UX Canvas](#1224-lean-ux-canvas)<br>
    1.3. [Segmentos objetivo](#13-segmentos-objetivo)<br>
2. [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)<br>
   2.1. [Competidores](#21-competidores)<br>
   2.1.1. [Análisis competitivo](#211-análisis-competitivo)<br>
   2.1.2. [Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)<br>
   2.2. [Entrevistas](#22-entrevistas)<br>
   2.2.1. [Diseño de entrevistas](#221-diseño-de-entrevistas)<br>
   2.2.2. [Registro de entrevistas](#222-registro-de-entrevistas)<br>
   2.2.3. [Análisis de entrevistas](#223-análisis-de-entrevistas)<br>
   2.3. [Needfinding](#23-needfinding)<br>
   2.3.1. [User Personas](#231-user-personas)<br>
   2.3.2. [User Task Matrix](#232-user-task-matrix)<br>
   2.3.3. [User Journey Mapping](#232-user-task-matrix)<br>
   2.3.4. [Empathy Mapping](#234-empathy-mapping)<br>
   2.3.5. [As-is Scenario Mapping](#235-as-is-scenario-mapping)<br>
   2.4. [Ubiquitous Language](#24-ubiquitous-language)<br>
3. [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)<br>
   3.1. [To-Be Scenario Mapping](#31-to-be-scenario-mapping)<br>
   3.2. [User Stories](#32-user-stories)<br>
   3.3. [Impact Mapping](#33-impact-mapping)<br>
   3.4. [Product Backlog](#34-product-backlog)<br>
4. [Capítulo IV: Product Design](#capítulo-iv-product-design)<br>
   4.1. [Style Guidelines](#41-style-guidelines)<br>
   4.1.1. [General Style Guidelines](#411-general-style-guidelines)<br>
   4.1.2. [Web Style Guidelines](#412-web-style-guidelines)<br>
   4.2. [Information Architecture](#42-information-architecture)<br>
   4.2.1. [Organization Systems](#421-organization-systems)<br>
   4.2.2. [Labeling Systems](#422-labeling-systems)<br>
   4.2.3. [SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)<br>
   4.2.4. [Searching Systems](#424-searching-systems)<br>
   4.2.5. [Navigation Systems](#425-navigation-systems)<br>
   4.3. [Landing Page UI Design](#43-landing-page-ui-design)<br>
   4.3.1. [Landing Page Wireframe](#431-landing-page-wireframe)<br>
   4.3.2. [Landing Page Mock-up](#432-landing-page-mock-up)<br>
   4.4. [Web Applications UX/UI Design](#44-web-applications-uxui-design)<br>
   4.4.1. [Web Applications Wireframes](#441-web-applications-wireframes)<br>
   4.4.2. [Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)<br>
   4.4.2. [Web Applications Mock-ups](#442-web-applications-mock-ups)<br>
   4.4.3. [Web Applications User Flow Diagrams](#443-web-applications-user-flow-diagrams)<br>
   4.5. [Web Applications Prototyping](#45-web-applications-prototyping)<br>
   4.6. [Domain-Driven Software Architecture](#46-domain-driven-software-architecture)<br>
   4.6.1. [Software Architecture Context Diagram](#461-software-architecture-context-diagram)<br>
   4.6.2. [Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)<br>
   4.6.3. [Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)<br>
   4.7. [Software Object-Oriented Design](#47-software-object-oriented-design)<br>
   4.7.1. [Class Diagrams](#471-class-diagrams)<br>
   4.7.2. [Class Dictionary](#472-class-dictionary)<br>
   4.8. [Database Design](#48-database-design)<br>
   4.8.1. [Database Diagram](#481-database-diagram)<br>
5. [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)<br>
   5.1. [Software Configuration Management](#51-software-configuration-management)<br>
   5.1.1. [Software Development Environment Configuration](#511-software-development-environment-configuration)<br>
   5.1.2. [Source Code Management](#512-source-code-management)<br>
   5.1.3. [Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)<br>
   5.1.4. [Software Deployment Configuration](#514-software-deployment-configuration)<br>
   5.2. [Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)<br>
   5.2.1. [Sprint 1](#521-sprint-1)<br>
   5.2.1.1. [Sprint Planning 1](#5211-sprint-planning-1)<br>
   5.2.1.2. [Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)<br>
   5.2.1.3. [Sprint Backlog 1](#5213-sprint-backlog-1)<br>
   5.2.1.4. [Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)<br>
   5.2.1.5. [Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)<br>
   5.2.1.6. [Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)<br>
   5.2.1.7. [Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)<br>
   5.2.1.8. [Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)<br>

6. [Conclusiones](#conclusiones)<br>
   6.1 [Conclusiones y recomendaciones](#61-conclusiones-y-recomendaciones)<br>
7. [Bibliografía](#bibliografía)<br>
8. [Anexos](#anexos)<br>

# Student Outcomes
   **Student Outcome 3**

| Criterio específico                                                | Acciones realizadas                                                                 | Conclusiones |
|--------------------------------------------------------------------|-------------------------------------------------------------------------------------|--------------|
| Comunica oralmente con efectividad a diferentes rangos de audiencia. | Para el desarrollo del TB1, hubo una buena comunicación en el equipo al momento de deliberar aspectos importantes acerca del desarrollo del trabajo. Todos participamos en las reuniones en las cuales expresamos nuestras ideas y opiniones. | TB1 <br> Para la TB1, el equipo trabajó colaborativamente y se logró una particiapción activa de cada uno de los integrantes. Se realizaron reuniones grupales en la que cada miembro compartió sus ideas de manera oral o escrita y, a partir de ello, se logró una toma de decisiones en conjunto la cual beneficio el equipo en la toma de decisiones y en la ejecución de tareas.       |
| Comunica por escrito con efectividad a diferentes rangos de audiencia | Para el desarrollo del TB1, desarrollamos correctamente la capacidad de comunicación escrita donde se ha explicado las ideas que hemos acordado en las reuniones através del presente documento | TB1 <br> Para el TB1, el equipo comunicó las ideas tomadas en el documento de manera conjunta y equitativa, siendo todos parte y responsables del desarrollo del informe        |

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Somos JobConnect, una startup iniciada por estudiantes del quinto ciclo de la Universidad Peruana de Ciencias Aplicadas. Nuestro objetivo es acercar a los trabajadores técnicos a los clientes mediante herramientas informáticas modernas, accesibles y confiables. A través de nuestra solución digital, buscamos facilitar la conexión directa entre ambos, potenciando la visibilidad, formalización y crecimiento de los profesionales independientes.

A través de nuestra plataforma, los trabajadores técnicos pueden crear un perfil profesional, promocionar sus habilidades, experiencias y sus tarifas a los clientes. De esta manera los clientes se mantienen informados, teniendo la capacidad de escoger entre un alta red de trabajadores.

Nuestra misión es desarrollar una plataforma accesible a los usuarios, que permita a los trabajadores técnicos mejorar su visibilidad y ampliar su base de clientes. De esta manera, logramos formalizar el contacto con los clientes y brindar una mayor seguridad al usuario en el proceso de contratación.

Nuestra visión es convertirnos en la plataforma principal de servicios técnicos en el Perú, promoviendo la seguridad al usuario mediante un servicio confiable y que mejoren la experiencia tanto del cliente como del trabajador

### 1.1.2. Perfiles de integrantes del equipo

| **Perfil**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | **Foto**                                                                       |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| **Jeremy Alión Paucar Meneses**<br>Mi nombre es Jeremy, Tengo 22 años. En la actualidad estoy estudiando la carrera de ingeniería de software en la Universidad Peruana de Ciencias Aplicadas. Albergo conocimientos intermedios en algunos lenguajes de programación, tales como C++, JavaScript y Python. Me considero una persona responsable con disposición de apoyar al grupo, también me gustan mucho los retos y así mismo poder cumplirlos.                                                                                                                                                                       | <img src="https://files.catbox.moe/vl4z7c.jpg" alt="angie image" width="200">  |
| **Kevin Jorge Chi Cruzatt**<br>Mi nombre es Kevin Chi. Tengo 19 años y actualmente estoy cursando el 5° ciclo de ingeniería de software. Me considero una persona con capacidades de liderazgo y capaz de trabajar bajo presión.                                                                                                                                                                                                                                                                                                  | <img src="https://files.catbox.moe/bacwjq.jpg" alt="kevin image" width="200">  |
| **Miguel Angel Hallasi Saravia**<br> Soy Miguel Hallasi, estudiante del quinto ciclo de la carrera de Ingeniería de Software. Me gusta el aprendizaje continuo y adquirir nuevas experiencias.                                                                            | <img src="https://files.catbox.moe/sds7k5.png" alt="kevin image" width="200">  |
| **Alejandro Daniel Oroncoy Almeyda**<br>Mi nombre es Alejandro Oroncoy. Tengo 19 años, soy estudiante de la carrera de ingeniería de software, estoy en 5to ciclo. Me considero una persona proactiva, autodidacta y orientada a objetivos.                                                                                                                                                    | <img src="https://files.catbox.moe/v1iqn9.png" alt="gael image" width="200">   
| **Eduardo Jose Cossar Sanchez**<br>Mi nombre es Eduardo Cossar. Soy estudiante de la carrera de Ingeniería de Software, tengo 19 años y actualmente estoy cursando el quinto ciclo en la UPC. Me considero una persona responsable y comprometida con un gran interés por la tecnología. Como integrante de este equipo, me comprometo a brindar todo mi apoyo y participación activa para afrontar los desafíos que se presenten y dar lo mejor de mí para lograr el éxito de este proyecto. | <img src="https://files.catbox.moe/mw437z.png" alt="kevin image" width="200"> |
| **Maria Fernanda Mostajo Orosco**<br>Mi nombre es Maria Fernanda Mostajo, estoy estudiando la carrera de Ingeniería de Software en la UPC, tengo conocimientos en los lenguajes de programación C++, Python, HTML, CSS, JavaScript y SQL. Además, cuento con habilidades de trabajo en equipo, el cual me permitira realizar un buen trabajo y cumplir con los objetivos planteados en el tiempo establecido.                                                                                                                                                                                            | <img src="https://files.catbox.moe/6moeru.png" alt="gael image" width="200">  

## 1.2. Solution Profile
