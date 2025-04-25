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
| Mostajo Orosco, Maria Fernanda           | U202210838 |

**Ciclo 2025-01**

# Registro de Versiones del Informe


| Version | Fecha      | Autor                            | Descripción de modificación                          |
| ------- | ---------- | -------------------------------- | ------------------------------------------------------ |
| 1.0     | 01/04/2025 | Chi, Paucar, Hallasi, Oroncoy, Cossar, Mostajo | Creación del documento de trabajo en formato markdown |
| 1.1     |            | Chi, Paucar, Hallasi, Oroncoy, Cossar, Mostajo|                                                        |
| 1.2     |            | Chi, Paucar, Hallasi, Oroncoy, Cossar, Mostajo|                                                        |
| 1.3     |            | Chi, Paucar, Hallasi, Oroncoy, Cossar, Mostajo |                                                        |
| 1.4     |            | Chi, Paucar, Hallasi, Oroncoy, Cossar, Mostajo |                                                        |
| 1.5     |            | Chi, Paucar, Hallasi, Oroncoy, Cossar, Mostajo |                                                        |
| 1.6     |            | Chi, Paucar, Hallasi, Oroncoy, Cossar, Mostajo |                                                        |
| 1.7     |            | Chi, Paucar, Hallasi, Oroncoy, Cossar, Mostajo |                                                        |
| 1.8     |            | Chi, Paucar, Hallasi, Oroncoy, Cossar, Mostajo |                                                        |

</div>

# Project Report Collaboration Insights

URL del repositorio para el proyecto: https://github.com/UPC-PaxTech/uTime/

**TB1**

Para el desarrollo del informe perteneciente a la entrega TB1, se dividió la implementación de secciones de la siguiente forma
para cada integrante del equipo:


| Integrantes    | Tareas Asignadas |
| -------------- | ---------------- |
| Kevin Chi      |                  |
| Jeremy Paucar   |                  |
| Miguel Hallasi |                  |
| Alejandro Oroncoy   |                  |
| Eduardo Cossar      |                  |
| Maria Fernanda Mostajo     |                  |


**Github Collaboration Insights**

Github también presenta un timeline de las ramas principales y los procesos de merge a los que se han sometido. Todas las
ramas se crearon tomando en cuenta el diseño de GitFlow para una buena organización cuando se usa un software de control
de versiones.

Los integrantes son:

- Kevin Chi (Krillsom)
- Jeremy Paucar (gael-rs)
- Miguel Hallasi (VarBus)
- Alejandro Oroncoy (aaaaangie)
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
| Comunica oralmente con efectividad a diferentes rangos de audiencia. | Kevin Chi:<br> Jeremy Paucar:<br> Miguel Hallasi:<br> Alejandro Oroncoy:<br> Eduardo Cossar:<br> Maria Fernanda Mostajo:<br> | ddsa         |
| Comunica por escrito con efectividad a diferentes rangos de audiencia | Kevin Chi:<br> Jeremy Paucar:<br> Miguel Hallasi:<br> Alejandro Oroncoy:<br> Eduardo Cossar:<br> Maria Fernanda Mostajo:<br> | ddsa         |

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Somos JobConnect, una startup iniciada por estudiantes del quinto ciclo de la Universidad Peruana de Ciencias Aplicadas. Nuestro objetivo es acercar a los trabajadores técnicos a los clientes mediante herramientas informáticas modernas, accesibles y confiables. A través de nuestra solución digital, buscamos facilitar la conexión directa entre ambos, potenciando la visibilidad, formalización y crecimiento de los profesionales independientes.

A través de nuestra plataforma, los trabajadores técnicos pueden crear un perfil profesional, promocionar sus habilidades, experiencias y sus tarifas a los clientes. De esta manera los clientes se mantienen informados, teniendo la capacidad de escoger entre un alta red de trabajadores.

Nuestra misión es desarrollar una plataforma accesible a los usuarios, que permita a los trabajadores técnicos mejorar su visibilidad y ampliar su base de clientes. De esta manera, logramos formalizar el contacto con los clientes y brindar una mayor seguridad al usuario en el proceso de contratación.

Nuestra visión es convertirnos en la plataforma principal de servicios técnicos en el Perú, promoviendo la seguridad al usuario mediante un servicio confiable y que mejoren la experiencia tanto del cliente como del trabajador

### 1.1.2. Perfiles de integrantes del equipo

- 


## 1.2. Solution Profile

En esta sección, se presenta en detalle el perfil de la solución, respaldado por
antecedentes sólidos y construido paso a paso siguiendo el proceso de
Lean UX

### 1.2.1 Antecedentes y problemática

En el Perú, una gran cantidad de trabajadores técnicos ofrecen sus servicios de manera informal, sin una plataforma que los respalde ni que facilite su visibilidad profesional. Esto genera desconfianza entre los clientes, dificulta el crecimiento de estos profesionales y reduce las oportunidades de empleo de calidad. JobConnect surge como una solución digital que busca formalizar esta relación, conectando a técnicos con clientes de forma segura, eficiente y profesional.

**What (Qué)**

##### ¿Cuál es el problema?

El problema principal es la falta de una plataforma especializada que conecte de forma efectiva a trabajadores técnicos independientes (electricistas, gasfiteros, carpinteros, etc.) con clientes que necesitan sus servicios. En la actualidad, muchos de estos profesionales dependen de métodos informales como recomendaciones boca a boca, redes sociales o grupos de WhatsApp, lo que limita su visibilidad, dificulta la generación de confianza y reduce sus oportunidades de crecimiento económico.

##### ¿Cuál es la relación con la persona en cuestión?

JobConnect busca resolver este problema proporcionando una plataforma digital que conecte a técnicos verificados con clientes en busca de servicios confiables. A través de la digitalización del proceso de búsqueda, solicitud y pago, JobConnect no solo mejora la experiencia del cliente, sino que también permite a los trabajadores técnicos formalizar sus servicios, aumentar su visibilidad y acceder a más oportunidades laborales. Según un informe del BID (2021), las plataformas digitales que promueven el empleo formal pueden incrementar hasta en 40% los ingresos de trabajadores independientes en América Latina.


**Who (Quién)**

##### ¿Quiénes están involucrados?

Los principales involucrados son los trabajadores técnicos independientes (electricistas, gasfiteros, técnicos de aire acondicionado, etc.), y los clientes que requieren sus servicios para el hogar, oficinas o negocios. También se incluyen microempresas que contratan técnicos de manera eventual..

##### ¿A quiénes le sucede el problema?

El problema afecta principalmente a los técnicos independientes, quienes no cuentan con medios eficientes para mostrar sus servicios ni herramientas para captar clientes nuevos. También afecta a los clientes, quienes se enfrentan a la incertidumbre de no encontrar técnicos de confianza de forma rápida y segura. Según el Ministerio de Trabajo (2022), casi un 60% de los trabajadores técnicos en el Perú no tienen presencia digital.

**Where (Dónde)**

##### ¿En dónde ocurre el problema?

 Este problema ocurre principalmente en zonas urbanas del Perú donde hay una alta demanda de servicios técnicos, pero los trabajadores aún gestionan sus actividades mediante medios informales como llamadas, mensajes de texto o publicaciones esporádicas en redes sociales, lo que genera ineficiencia y desconfianza.

##### ¿En dónde nos enfocaremos?

Nos enfocaremos inicialmente en Lima, donde existe un alto volumen de clientes potenciales y trabajadores técnicos con acceso básico a tecnología móvil e internet. Estas zonas permiten una implementación escalable con impacto real y medible.

**When (Cuándo)**

##### ¿Cuándo sucede el problema?

El problema se presenta cada vez que un cliente requiere un servicio técnico y no encuentra rápidamente a un proveedor confiable, o cuando el trabajador técnico pierde oportunidades por no tener un canal activo de contacto o visibilidad en línea.

##### ¿Cuándo utiliza el cliente el producto?

El cliente utilizaría JobConnect al momento de necesitar un servicio técnico específico. La plataforma permitirá buscar por tipo de servicio, ubicación y disponibilidad. Del lado del técnico, el producto será utilizado tanto para gestionar sus citas como para visualizar reseñas, actualizar su disponibilidad y recibir pagos.

**Why (Por qué)**

##### ¿Cuál es la causa del problema?

Las principales causas del problema incluyen la informalidad del sector técnico, la baja digitalización de los trabajadores independientes y la falta de plataformas especializadas que respondan a sus necesidades específicas. Si bien existen plataformas como Workana o Clic, estas no están orientadas a servicios presenciales ni al perfil técnico, lo que deja un vacío en el mercado. Además, muchos trabajadores técnicos carecen de conocimientos para usar plataformas complejas o poco localizadas.

**How (Cómo)**

##### ¿En qué condiciones los clientes usan nuestro producto?

A través de una aplicación web o móvil ligera y fácil de usar, disponible en dispositivos con conexión a internet. JobConnect ofrecerá funcionalidades como búsqueda por cercanía, perfiles verificados, historial de servicios, sistema de pago seguro y soporte post-servicio. Para los técnicos, la interfaz permitirá recibir solicitudes, programar citas, subir evidencias de trabajos y recibir evaluaciones de clientes.

**How much (Cuánto)**

##### Estadísticas que sustentan la problemática.

Según el Instituto Nacional de Estadística e Informática (INEI, 2023), más del 70% de los trabajadores técnicos en Perú operan de manera informal, sin acceso a herramientas digitales que les permitan organizar y formalizar sus servicios. Esta situación conlleva a una baja visibilidad, desconfianza por parte de los clientes y pérdida de oportunidades laborales.

De acuerdo al Ministerio de Trabajo y Promoción del Empleo (MTPE, 2022), solo el 18% de los técnicos independientes en zonas urbanas usa plataformas digitales para la promoción o gestión de sus servicios. La gran mayoría depende de llamadas telefónicas, grupos de WhatsApp o recomendaciones informales para obtener trabajo.

Un estudio de la CAF (Banco de Desarrollo de América Latina, 2021), indica que la digitalización puede aumentar los ingresos de los trabajadores independientes hasta en un 40%, y mejorar la percepción de confiabilidad por parte de los clientes en un 60%.

### 1.2.2. Lean UX Process

El Lean UX es un enfoque de diseño centrado en la colaboración, la retroalimentación continua y la mejora iterativa. Se enfoca en construir productos útiles y funcionales desde etapas tempranas, validando constantemente las ideas con los usuarios reales. En el caso de JobConnect, este enfoque es esencial para crear una plataforma eficiente y confiable que conecte a trabajadores técnicos con clientes que necesitan servicios de calidad.

### 1.2.2. Lean UX Process

El Lean UX es un enfoque de diseño centrado en la colaboración, la retroalimentación continua y la mejora iterativa. Se enfoca en construir productos útiles y funcionales desde etapas tempranas, validando constantemente las ideas con los usuarios reales. En el caso de JobConnect, este enfoque es esencial para crear una plataforma eficiente y confiable que conecte a trabajadores técnicos con clientes que necesitan servicios de calidad.

#### 1.2.2.1. Lean UX Problem Statements

JobConnect busca resolver una problemática muy común en el mercado peruano: la informalidad, baja visibilidad y poca credibilidad de los trabajadores técnicos independientes, lo que dificulta su conexión con potenciales clientes.

Hemos identificado que existe una brecha entre los trabajadores técnicos y los clientes, causada por la falta de canales digitales accesibles que permitan promocionar sus servicios de forma segura y ordenada. Muchos trabajadores no tienen medios formales para ofrecer sus servicios, y los clientes no cuentan con referencias verificadas para tomar decisiones informadas.

En un contexto donde el trabajo técnico es muy demandado pero aún mayormente informal, es crucial facilitar un espacio digital que formalice estos vínculos. Sin una plataforma confiable, se perpetúa la desconfianza, la baja demanda y el limitado crecimiento profesional de estos trabajadores.

**¿Cómo podemos diseñar una plataforma accesible que permita a los trabajadores técnicos visibilizar sus habilidades y a los clientes encontrar y contratar profesionales de forma confiable y segura?**

#### 1.2.2.2. Lean UX Assumptions

JobConnect está diseñado para facilitar el contacto entre trabajadores técnicos e independientes y personas que necesitan servicios confiables en el hogar o el negocio. Asumimos que la plataforma debe ser intuitiva, permitir mostrar portafolios y valoraciones, y ofrecer filtros eficientes para encontrar al profesional adecuado.

#### a. Assumption Worksheet

**¿Quién será nuestro usuario?**  
Trabajadores técnicos independientes (electricistas, gasfiteros, técnicos en refrigeración, etc.) y clientes residenciales o comerciales que requieren estos servicios.

**¿Dónde encaja nuestro producto en su vida?**  
Para los técnicos, como herramienta para conseguir más clientes y mejorar su reputación profesional. Para los clientes, como solución práctica para contratar servicios de forma segura y rápida.

**¿Qué problemas tiene nuestro producto y cómo se pueden resolver?**  
La informalidad del sector, la baja visibilidad de los trabajadores y la desconfianza del cliente. Esto se puede resolver brindando perfiles verificables, reseñas de otros clientes y un sistema de búsqueda simple pero eficaz.

**¿Cómo y cuándo es usado nuestro producto?**  
La plataforma se usa mediante computadoras y celulares, en el momento en que un cliente necesita contratar un técnico o cuando un trabajador quiere mejorar su presencia digital.

**¿Cómo debe verse nuestro producto y cómo debe comportarse?**  
Debe tener un diseño simple, visual y amigable. Fluido, con perfiles claros, filtros rápidos, sistema de valoraciones, y opción de contactar al profesional dentro de la app.

**¿Qué características son importantes?**
- Creación fácil de perfiles para técnicos.
- Sistema de calificaciones y comentarios.
- Filtros por ubicación, especialidad y precio.
- Seguridad en la verificación de identidad.
- Plataforma optimizada para móviles.
- Sistema de mensajes o contacto directo.

#### b. Business Outcomes

- JobConnect se posicionará como una plataforma confiable para contratar servicios técnicos.  
- Aumentará el número de trabajadores técnicos formales registrados en el país.  
- Reducirá la tasa de clientes insatisfechos al contar con perfiles verificados.  
- Generará ingresos por comisiones y suscripciones premium para técnicos.  
- Obtendrá buenas calificaciones en tiendas de apps por su facilidad y utilidad.

#### c. User Outcomes

- Los técnicos mejorarán su visibilidad y conseguirán más clientes.  
- Los clientes se sentirán más seguros al contratar servicios verificados.  
- Aumentará la confianza y satisfacción gracias al sistema de reseñas.  
- Los usuarios encontrarán al profesional adecuado en menos tiempo.  
- Se reducirá el número de incidentes o malas experiencias en contrataciones.

#### 1.2.2.3. Lean UX Hypothesis Statements

**Hipótesis 1:**  
Creemos que los trabajadores técnicos aumentarán su visibilidad y número de contrataciones al crear un perfil profesional en JobConnect.  
_Sabremos que estamos en lo correcto cuando, en los primeros 3 meses, al menos el 60% de los técnicos registrados reporten haber conseguido nuevos clientes a través de la plataforma._

**Hipótesis 2:**  
Creemos que los clientes se sentirán más seguros al contratar técnicos con perfiles verificados y reseñas visibles.  
_Sabremos que estamos en lo correcto cuando el 70% de los usuarios encuestados manifiesten sentirse más confiados al contratar mediante JobConnect que por medios tradicionales._

**Hipótesis 3:**  
Creemos que incluir un sistema de calificaciones y comentarios mejorará la calidad del servicio prestado por los técnicos.  
_Sabremos que estamos en lo correcto cuando las calificaciones promedio de los técnicos aumenten en un 20% en los primeros seis meses._

**Hipótesis 4:**  
Creemos que permitir a los clientes filtrar técnicos por especialidad, ubicación y precio facilitará el proceso de búsqueda y contratación.  
_Sabremos que estamos en lo correcto cuando el tiempo promedio que toma contratar a un técnico se reduzca en un 40%._

**Hipótesis 5:**  
Creemos que ofrecer una versión móvil optimizada de JobConnect aumentará la frecuencia de uso y retención.  
_Sabremos que estamos en lo correcto cuando el 80% de los usuarios activos utilicen la app desde el celular y la tasa de retención mensual supere el 50%._

#### 1.3. Segmento Objetivo

##### Trabajadores Técnicos Independientes

**Aspectos demográficos:**
- Sexo: Masculino y Femenino  
- Edad: 20-55 años  

**Aspectos geográficos:**
- Nacionalidad: Peruana  
- Departamento: Lima  

**Aspectos psicográficos:**
- Desean incrementar su visibilidad profesional y captar más clientes.  
- Buscan oportunidades de formalizar su trabajo y generar confianza en sus servicios.  
- Tienen interés en una plataforma digital sencilla que les permita promocionar sus habilidades.  
- Están dispuestos a recibir retroalimentación mediante valoraciones para mejorar su reputación laboral.

##### Usuarios que requieren servicios técnicos

**Aspectos demográficos:**
- Sexo: Masculino y Femenino  
- Edad: 25-60 años  

**Aspectos geográficos:**
- Nacionalidad: Peruana  
- Departamento: Lima Metropolitana  

**Aspectos psicográficos:**
- Desean encontrar profesionales técnicos confiables y con buenas referencias.  
- Buscan una plataforma práctica para comparar opciones por especialidad, precios y cercanía.  
- Valoran la rapidez y facilidad al momento de contratar un servicio técnico.  
- Quieren tener seguridad y confianza durante el proceso de contratación, evitando fraudes o estafas.

### 2.1. Competidores

Hemos identificado tres competidores clave en el mercado peruano que ofrecen soluciones para conectar a profesionales independientes con potenciales clientes:

- **Chambea**  
Aplicación móvil peruana diseñada para conectar a emprendedores y trabajadores independientes con posibles clientes en diversas categorías, como tecnología, comida, mascotas, delivery, automóviles y finanzas.

- **Workana**  
Plataforma en línea que opera en varios países de América Latina, incluyendo Perú, enfocada en conectar a freelancers con empresas que buscan profesionales para proyectos en áreas como programación, diseño, traducción, marketing y más.

- **Clic**  
Hub digital que ofrece servicios profesionales en diversos rubros, como medicina, psicología, nutrición, fisioterapia, derecho y consultoría. A través de su aplicación, las personas pueden contactar a especialistas y coordinar servicios según sus necesidades.

# Capítulo III: Requirements Specification

## 3.2. User Stories.

### 3.2.1. Requisitos Funcionales
| **Epic/User Story ID** | **Título**                              | **Descripción**                                                                                                                                                                                                                         | **Criterios de Aceptación**                                                                                                                                                                                                               | **Relacion con (Epic ID)** |
| ---------------------- | --------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------- |
| EP01                   | Creación de Cuenta y Autenticación      | **Como cliente o trabajador técnico**, quiero registrarme e iniciar sesión de forma segura, para acceder a todas las funcionalidades de la plataforma según mi rol.                                                                     |                                                                                                                                                                                                                                           |                            |
| EP02                   | Navegación y Experiencia de Usuario     | **Como cliente**, quiero navegar fácilmente por categorías de servicios, para encontrar trabajadores técnicos cerca de mi ubicación. **Como trabajador**, quiero acceder a un panel intuitivo, para gestionar mis servicios y clientes. |                                                                                                                                                                                                                                           |                            |
| EP03                   | Gestión de Perfiles                     | **Como trabajador técnico**, quiero completar mi perfil con mis habilidades, experiencia y tarifas, para atraer más clientes. **Como cliente**, quiero personalizar mis preferencias, para recibir recomendaciones relevantes.          |                                                                                                                                                                                                                                           |                            |
| EP04                   | Sistema de Confiabilidad                | **Como cliente**, quiero ver perfiles de trabajadores verificados y leer reseñas de otros usuarios, para contratar con confianza. **Como trabajador**, quiero mostrar mis certificaciones, para demostrar mi profesionalismo.           |                                                                                                                                                                                                                                           |                            |
| EP05                   | Búsqueda y Filtros                      | **Como cliente**, quiero buscar trabajadores técnicos por especialidad, precio o calificación, para encontrar al profesional que mejor se adapte a mis necesidades.                                                                     |                                                                                                                                                                                                                                           |                            |
| EP06                   | Comparación de Perfiles                 | **Como cliente**, quiero comparar hasta 3 perfiles de trabajadores técnicos en una misma pantalla, para tomar la mejor decisión basada en habilidades, costos y reseñas.                                                                |                                                                                                                                                                                                                                           |                            |
| EP07                   | Gestión de Suscripciones                | **Como trabajador técnico**, quiero conocer los planes de suscripción disponibles (gratis/premium), para aumentar mi visibilidad y oportunidades de trabajo en la plataforma.                                                           |                                                                                                                                                                                                                                           |                            |
| EP08                   | Comunicación y Contratación                | **Como plataforma**, quiero facilitar la comunicación directa entre clientes y trabajadores, así como un sistema seguro para propuestas y pagos, para formalizar acuerdos y proteger a ambas partes.                                                           |                                                                                                                                                                                                                                           |                            |
| EP09                   | Landing Page y Contenido Informativo       | **Como plataforma**, quiero ofrecer una página de inicio con información esencial (testimonios, beneficios y funcionamiento), para captar nuevos usuarios y comunicar el valor de nuestros servicios. |
| US01                   | Inicio de sesión                        | Como usuario, quiero iniciar sesión en la aplicación, para acceder a mi cuenta personal.                                                                                                                                                | 1. Dado que el usuario ingrese credenciales válidas, entonces deberá poder acceder al sistema.  <br>2. Dado que las credenciales sean incorrectas, el sistema deberá mostrar un mensaje de error.                                         | EP01                       |
| US02                   | Creación de cuenta                      | Como nuevo usuario, quiero registrarme en la plataforma, para poder usar los servicios.                                                                                                                                                 | 1. Dado que el usuario complete todos los campos requeridos, el sistema deberá permitir la creación de cuenta.  <br>2. Dado que falte un dato obligatorio, el sistema deberá informar el error.                                           | EP01                       |
| US03                   | Recuperar contraseña                    | Como usuario, quiero recuperar mi contraseña, para poder acceder si la olvido.                                                                                                                                                          | 1. Dado que el usuario introduzca su correo, el sistema deberá enviar un enlace de recuperación.  <br>2. Dado que el enlace sea usado, el sistema deberá permitir establecer una nueva contraseña.                                        | EP01                       |
| US04                   | Cambio de vista cliente/trabajador      | Como usuario, quiero cambiar entre vista de cliente y trabajador, para usar la plataforma según mi rol.                                                                                                                                 | 1. Dado que el usuario haga clic en el cambio de rol, la vista deberá actualizarse correctamente.  <br>2. Dado que el rol cambie, las funcionalidades disponibles deberán adaptarse al nuevo rol.                                         | EP02                       |
| US05                   | Navegación en la interfaz: Cliente      | Como cliente, quiero navegar por la interfaz fácilmente, para explorar y contratar trabajadores.                                                                                                                                        | 1. Dado que el cliente esté en su panel, deberá ver botones claros para buscar, comparar y contactar.  <br>2. Dado que navegue entre secciones, el sistema deberá cargar el contenido sin errores.                                        | EP02                       |
| US06                   | Navegación interfaz trabajador          | Como trabajador, quiero navegar fácilmente por mi panel, para gestionar mis servicios y clientes.                                                                                                                                       | 1. Dado que el trabajador ha iniciado sesión, cuando acceda a su panel, entonces deberá poder ver su calendario, mensajes y configuración.  <br>2. Dado que el trabajador navegue entre secciones, estas deben cargar correctamente.      | EP02                       |
| US07                   | Personalización de perfil técnico       | Como trabajador, quiero personalizar mi perfil, para destacar mis habilidades y experiencia.                                                                                                                                            | 1. Dado que el trabajador accede a su perfil, cuando edite sus datos, entonces deberá poder guardar la información con éxito.  <br>2. Dado que haya completado su perfil, deberá visualizarse con formato profesional al público.         | EP03                       |
| US08                   | Personalización de perfil cliente       | Como cliente, quiero personalizar mi perfil, para recibir mejores recomendaciones.                                                                                                                                                      | 1. Dado que el cliente acceda a su perfil, cuando actualice sus preferencias, entonces el sistema deberá guardar los cambios.  <br>2. Dado que el perfil esté completo, el sistema deberá usarlo para mejorar la experiencia de búsqueda. | EP03                       |
| US09                   | Configuración                           | Como usuario, quiero acceder a configuración de mi cuenta, para gestionar notificaciones, idioma, etc.                                                                                                                                  | 1. Dado que el usuario acceda a la configuración, podrá modificar sus preferencias y guardarlas.  <br>2. Dado que se realicen cambios, estos deberán reflejarse inmediatamente en la interfaz correspondiente.                            | EP03                       |
| US10                   | Verificación del perfil del trabajador  | Como cliente, quiero ver que un trabajador esté verificado, para confiar en contratarlo.                                                                                                                                                | 1. Dado que un trabajador haya verificado su identidad/documentos, el sistema deberá mostrar un sello de verificación.  <br>2. Dado que un cliente vea un perfil verificado, deberá poder acceder al detalle del proceso.                 | EP04                       |
| US11                   | Sistema de reseñas y calificación       | Como cliente, quiero dejar una reseña y calificación, para ayudar a otros usuarios a tomar decisiones.                                                                                                                                  | 1. Dado que el cliente haya contratado un servicio, podrá calificarlo una vez finalizado.  <br>2. Dado que una reseña sea publicada, esta deberá ser visible en el perfil del trabajador.                                                 | EP04                       |
| US12                   | Denuncia de perfil                      | Como usuario, quiero denunciar un perfil sospechoso, para mantener la seguridad de la plataforma.                                                                                                                                       | 1. Dado que un usuario encuentre un perfil sospechoso, podrá usar un botón para reportarlo.  <br>2. Dado que se envíe un reporte, el sistema deberá notificar a los moderadores para revisión.                                            | EP04                       |
| US13                   | Búsqueda por lenguaje natural           | Como cliente, quiero buscar trabajadores describiendo mi problema, para encontrar rápidamente a quien necesito.                                                                                                                         | 1. Dado que el cliente escriba una descripción, el sistema deberá mostrar resultados relevantes.  <br>2. Dado que el sistema interprete el texto, deberá resaltar palabras clave y perfiles coincidentes.                                 | EP05                       |
| US14                   | Búsqueda por filtro                     | Como cliente, quiero filtrar trabajadores por ubicación, experiencia, etc., para encontrar el perfil ideal.                                                                                                                             | 1. Dado que el cliente aplique filtros, los resultados deberán actualizarse dinámicamente.  <br>2. Dado que se combinen múltiples filtros, el sistema deberá mantener los criterios activos.                                              | EP05                       |
| US15                   | Recomendación de perfil                 | Como cliente, quiero recibir recomendaciones de trabajadores, para agilizar mi elección.                                                                                                                                                | 1. Dado que el cliente navegue regularmente, el sistema deberá sugerir trabajadores según su comportamiento.  <br>2. Dado que haya historial de contrataciones, el sistema deberá usarlo para mejorar las recomendaciones.                | EP05                       |
| US16                   | Comparación de perfiles                 | Como cliente, quiero comparar varios perfiles, para tomar una mejor decisión de contratación.                                                                                                                                           | 1. Dado que el cliente seleccione varios perfiles, el sistema deberá mostrar una vista comparativa.  <br>2. Dado que vea la comparación, podrá acceder a enlaces directos para contratar o contactar.                                     | EP06                       |
| US17                   | Visualización de reseñas en comparación | Como cliente, quiero ver las reseñas durante la comparación, para valorar mejor a los trabajadores.                                                                                                                                     | 1. Dado que el cliente esté comparando perfiles, las reseñas deberán mostrarse de forma compacta y ordenada.  <br>2. Dado que el cliente necesite más información, deberá poder expandir las reseñas desde la comparación.                | EP06                       |
| US18                   | Gestión de disponibilidad               | Como trabajador, quiero actualizar mis horarios disponibles, para que los clientes sepan cuándo puedo atender.                                                                                                                          | 1. Dado que el trabajador edite su calendario, el sistema deberá reflejar los cambios en su perfil.  <br>2. Dado que un cliente consulte un día ocupado, el sistema mostrará "No disponible".                                             | EP03                       |
| US19                   | Subir portafolio de trabajos            | Como trabajador, quiero subir fotos de mis proyectos anteriores, para demostrar mi experiencia.                                                                                                                                         | 1. Dado que el trabajador adjunte imágenes, el sistema deberá permitir previsualizarlas.  <br>2. Dado que el portafolio supere 10 fotos, el sistema mostrará un mensaje de límite.                                                        | EP03                       |
| US20                   | Respuesta a reseñas                     | Como trabajador, quiero responder a las reseñas de los clientes, para aclarar dudas o agradecer.                                                                                                                                        | 1. Dado que el trabajador acceda a una reseña, podrá escribir una respuesta pública.  <br>2. Dado que envíe una respuesta, esta se mostrará bajo la reseña original.                                                                      | EP04                       |
| US21                   | Búsqueda por geolocalización            | Como cliente, quiero buscar trabajadores cerca de mi ubicación actual, para contratar servicios urgentes.                                                                                                                               | 1. Dado que el cliente active la geolocalización, el sistema mostrará trabajadores en un radio de 5 km.  <br>2. Dado que no haya resultados cercanos, el sistema sugerirá ampliar el radio.                                               | EP05                       |
| US22                   | Exportar comparación                    | Como cliente, quiero exportar la comparación de perfiles en PDF, para compartirla con otras personas.                                                                                                                                   | 1. Dado que el cliente finalice la comparación, el sistema ofrecerá un botón de exportación.  <br>2. Dado que se genere el PDF, este incluirá imágenes y datos clave de los perfiles.                                                     | EP06                       |
| US23                   | Chat personal                          | Como cliente, quiero comunicarme directamente con el trabajador técnico, para resolver dudas y coordinar detalles del servicio.                                                                                                           | 1. Dado que el cliente seleccione un trabajador, podrá iniciar un chat desde su perfil.  <br>2. Dado que se envíe un mensaje, el sistema notificará al receptor en tiempo real.                                                           | EP08                       |
| US24                   | Crear y enviar propuestas             | Como trabajador técnico, quiero enviar propuestas personalizadas a los clientes, para ofrecer soluciones y tarifas adaptadas a sus necesidades.                                                                                          | 1. Dado que el cliente describa su problema, el trabajador podrá crear una propuesta con costo y plazo.  <br>2. Dado que el cliente reciba la propuesta, podrá aceptarla, rechazarla o negociar cambios.                                 | EP08                       |
| US25                   | Pago seguro dentro de la app          | Como usuario, quiero realizar pagos dentro de la plataforma, para garantizar seguridad y respaldo en caso de inconvenientes.                                                                                                              | 1. Dado que el cliente confirme un servicio, el sistema redirigirá a un gateway de pago integrado.  <br>2. Dado que el pago sea exitoso, el trabajador recibirá una notificación y el monto se retendrá hasta la confirmación del servicio. | EP08                       |
| US26                   | Gestión de habilidades técnicas        | Como trabajador técnico, quiero mantener actualizada mi lista de habilidades y campo de especialización, para que los clientes conozcan mis competencias específicas.                                                                   | 1. Dado que el trabajador agregue una habilidad, esta se añadirá a su lista de habilidades. <br>2. Dado que seleccione un campo de especialización, este se mostrará destacado en su perfil.                                            | EP03                       |
| US27                   | Gestión de recomendaciones externas    | Como trabajador técnico, quiero poder agregar recomendaciones externas a mi perfil, para aumentar mi credibilidad profesional.                                                                                                         | 1. Dado que el trabajador añada una recomendación externa, esta se mostrará en una sección específica de su perfil. <br>2. Dado que tenga múltiples recomendaciones, se mostrarán ordenadas cronológicamente.                          | EP03                       |
| US28                   | Gestión de tarifa por hora             | Como trabajador técnico, quiero establecer y actualizar mi tarifa por hora, para que los clientes conozcan mis costos antes de contactarme.                                                                                            | 1. Dado que el trabajador establezca su tarifa, el sistema la mostrará en su moneda local. <br>2. Dado que actualice su tarifa, el cambio se reflejará en todas las búsquedas y comparaciones.                                         | EP03                       |
| US29 | Formulario de contacto  | Como visitante, quiero enviar consultas a través de un formulario, para resolver dudas sobre la plataforma. | 1. Dado que el visitante complete los campos obligatorios (nombre, correo, mensaje), el sistema enviará la consulta al equipo de soporte.<br>2. Dado que el formulario se envíe, el usuario recibirá un correo de confirmación. | EP09 |
| US30 | Sección de testimonios  | Como visitante, quiero ver testimonios seleccionados por la plataforma, para confiar en los servicios ofrecidos. | 1. Dado que el visitante acceda al landing page, verá al menos 4 testimonios con foto, nombre y servicio contratado.<br>2. Dado que haya más testimonios, el sistema mostrará un botón "Ver más" para cargar otros 4. | EP09 |
| US31 | Categorías de servicios | Como visitante, quiero explorar las categorías de servicios disponibles (ej: plomería, electricidad), para conocer el alcance de la plataforma. | 1. Dado que el visitante navegue por la sección, verá hasta 6 categorías destacadas con iconos y descripciones breves.<br>2. Dado que el visitante quiera ver más, habrá un botón "Ver todos los servicios" que lo redirigirá al registro o búsqueda. | EP09 |
| US32 | Sección de beneficios   | Como visitante, quiero conocer los beneficios de registrarme (seguridad, ahorro de tiempo, etc.), para decidir unirme a la plataforma. | 1. Dado que el visitante revise la sección, verá 3 beneficios para clientes y 3 para trabajadores, con iconos y textos claros.<br>2. Dado que un beneficio incluya un enlace (ej: "Comenzar Ahora"), este funcionará correctamente. | EP09 |
| US33 | Sección "Cómo funciona" | Como visitante, quiero entender los pasos para usar la plataforma, tanto como cliente como trabajador, para saber cómo empezar. | 1. Dado que el visitante acceda a la sección, verá dos flujos: Para trabajadores (crear perfil, promocionar servicios, conectar con clientes) y Para clientes (buscar, comparar, contratar).<br>2. Dado que el visitante esté interesado, habrá un botón "Comenzar ahora" que lo redirigirá al registro. | EP09 |