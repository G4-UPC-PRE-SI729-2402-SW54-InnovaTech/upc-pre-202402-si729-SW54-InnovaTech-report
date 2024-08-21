<div align="center">

![image](https://github.com/PetPalORG/PetPal-Informe/assets/164519824/55b272a3-26f7-4c8b-9da7-39b023ceaeb5)

# Universidad Peruana de Ciencias Aplicadas

# INGENIERA DE SOFTWARE

# CURSO: SI729 Aplicaciones Open Source | SECCIÓN SW54 | 2024-2
 Profesor: Alberto Wilmer Sanchez Seña

**Startup:** Connex 

### Integrantes:
- Javier Murillo, Mathias - U202022211
- Macavilca Quispe, Ian - U202121325

</div>

---
# **Registro de versiones del Informe** 

| Version | Fecha | Autor | Descripcion de Modificacion |
| ----------- | ------------ | ---------- | ----------- |
| 0.0 | 20/08/2024 | Grupo 4 | Creación del documento |


# **Project Report Collaboration Insights**

**Commits del Informe**

Link del repositorio: 

# **Student Outcome**

**ABET - EAC - Student Outcome 3:** Capacidad de comunicarse efectivamente con un rango de audiencias.




# Contenido

- [Registro de Versiones](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Student Outcome](#student-outcome)
1. [Capítulo I: Introducción](#capítulo-i-introducción)<br>
   1.1. [Startup Profile](#11-startup-profile)<br>
      1.1.1. [Descripción del startup](#111-descripcion-del-startup)<br>
      1.1.2. [Perfiles de los integrantes del equipo](#112-perfiles-de-los-integrantes-del-equipo)<br>
   1.2. [Solution Profile](#12-solution-profile)<br>
      1.2.1. [Antecedentes y Problemática](#121-antecedentes-y-problemática)<br>
      1.2.2. [Lean UX Process](#122-lean-ux-process)<br>
        1.2.2.1. [Lean UX Problem Statements](#1221-lean-ux-problem-statements)<br>
        1.2.2.2. [Lean UX Assumptions](#1222-lean-ux-assumptions)<br>
        1.2.2.3. [Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)<br>
        1.2.2.4. [Lean UX Canvas](#1224-lean-ux-canvas)<br>
   1.3. [Segmentos objetivo](#13-segmentos-objetivo)<br>
2. [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation-analysis)<br>
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
      2.3.3. [User Journey Mapping](#233-user-journey-mapping)<br>
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
   4.4. [Web Applications UX/UI Design](#44-web-applications-ux-ui-design)<br>
      4.4.1. [Web Applications Wireframes](#441-web-applications-wireframes)<br>
      4.4.2. [Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)<br>
      4.4.3. [Web Applications Mock-ups](#443-web-applications-mock-ups)<br>
      4.4.4. [Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)<br>
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
         5.2.1.2. [Sprint Backlog 1](#5212-sprint-backlog-1)<br>
         5.2.1.3. [Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)<br>
         5.2.1.4. [Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)<br>
         5.2.1.5. [Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)<br>
         5.2.1.6. [Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)<br>
         5.2.1.7. [Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)<br>
         5.2.1.8. [Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)<br>
      5.2.2. [Sprint 2](#522-sprint-2)<br>
         5.2.2.1. [Sprint Planning 2](#5221-sprint-planning-2)<br>
         5.2.2.2. [Sprint Backlog 2](#5222-sprint-backlog-2)<br>
         5.2.2.3. [Development Evidence for Sprint Review](#5223-development-evidence-for-sprint-review)<br>
         5.2.2.4. [Testing Suite Evidence for Sprint Review](#5224-testing-suite-evidence-for-sprint-review)<br>
         5.2.2.5. [Execution Evidence for Sprint Review](#5225-execution-evidence-for-sprint-review)<br>
         5.2.2.6. [Services Documentation Evidence for Sprint Review](#5226-services-documentation-evidence-for-sprint-review)<br>
         5.2.2.7. [Software Deployment Evidence for Sprint Review](#5227-software-deployment-evidence-for-sprint-review)<br>
         5.2.2.8. [Team Collaboration Insights during Sprint](#5228-team-collaboration-insights-during-sprint)<br>
      5.2.3. [Sprint 3](#523-sprint-3)<br>
         5.2.3.1. [Sprint Planning 3](#5231-sprint-planning-3)<br>
         5.2.3.2. [Sprint Backlog 3](#5232-sprint-backlog-3)<br>
         5.2.3.3. [Development Evidence for Sprint Review](#5233-development-evidence-for-sprint-review)<br>
         5.2.3.4. [Testing Suite Evidence for Sprint Review](#5234-testing-suite-evidence-for-sprint-review)<br>
         5.2.3.5. [Execution Evidence for Sprint Review](#5235-execution-evidence-for-sprint-review)<br>
         5.2.3.6. [Services Documentation Evidence for Sprint Review](#5236-services-documentation-evidence-for-sprint-review)<br>
         5.2.3.7. [Software Deployment Evidence for Sprint Review](#5237-software-deployment-evidence-for-sprint-review)<br>
         5.2.3.8. [Team Collaboration Insights during Sprint](#5238-team-collaboration-insights-during-sprint)<br>
      5.2.4. [Sprint 4](#524-sprint-4)<br>
         5.2.4.1. [Sprint Planning 4](#5241-sprint-planning-4)<br>
         5.2.4.2. [Sprint Backlog 4](#5242-sprint-backlog-4)<br>
         5.2.4.3. [Development Evidence for Sprint Review](#5243-development-evidence-for-sprint-review)<br>
         5.2.4.4. [Testing Suite Evidence for Sprint Review](#5244-testing-suite-evidence-for-sprint-review)<br>
         5.2.4.5. [Execution Evidence for Sprint Review](#5245-execution-evidence-for-sprint-review)<br>
         5.2.4.6. [Services Documentation Evidence for Sprint Review](#5246-services-documentation-evidence-for-sprint-review)<br>
         5.2.4.7. [Software Deployment Evidence for Sprint Review](#5247-software-deployment-evidence-for-sprint-review)<br>
         5.2.4.8. [Team Collaboration Insights during Sprint](#5248-team-collaboration-insights-during-sprint)<br>
   5.3. [Validation Interviews](#53-validation-interviews)<br>
      5.3.1. [Diseño de Entrevistas](#531-diseño-de-entrevistas)<br>
      5.3.2. [Registro de Entrevistas](#532-registro-de-entrevistas)<br>
      5.3.3. [Evaluaciones según Heurísticas](#533-evaluaciones-según-heurísticas)<br>
   5.4. [Video About-the-Product](#54-video-about-the-product)<br>
6. [Conclusiones](#conclusiones)<br>
7. [Bibliografía](#bibliografía)<br>
8. [Anexos](#anexos)

# **Capítulo I: Introducción** 

## **1.1. Startup Profile** 
### **1.1.1. Descripcion de la Startup** 
### **1.1.2. Perfiles de los integrantes del equipo** 

## **1.2. Solution Profile** 
### **1.2.1. Antecedentes y problemáticas** 
### **1.2.2. Lean UX Process** 
#### **1.2.2.1. Lean UX Problem Statments** 
#### **1.2.2.2. Lean UX Assumptions** 
#### **1.2.2.3. Lean UX Hypothesis Statements** 
#### **1.2.2.4. Lean UX Canvas** 

## **1.3. Segmentos objetivo** 

# **Capítulo II: Requeriments Elicitation & Analysis** 

## **2.1. Competidores** 

# Coobis
Coobis es una plataforma de marketing de contenidos que conecta distintas marcas con diferentes medios o tambien con influncers. Coobis llega a difundir el contenido entre mas de 5000 medios clasificados y puntuados, y además, amplifica el mensaje que los influencers o marcas quieran transmitir en diferentes redes sociales.

# Nuntia 
Nuntia, o anteriormente conocida como Blog on brands, es una empresa que se dedica a conectar bloggers con marcas. Esta empresa se basa en la influencia y la independencia. Por un lado, la influencia, porque un blog es lo que te hace diferente en un mundo virtual y, por otro lado, la independencia, porque es la clave que te convierte en influencer. 

# Brantube
Brantube se centra en los influences qu puedan contrar en la red social de Youtube. Trabajando de esta manera, tanto con influencers o Youtubers, como con empresas para que éstas contraten a los usuarios mas populares para conseguir que sus campañas sean mas exitosas. 

# Socialpubli
Socialpubli es una empresa de publicidad social que pone en contacto a empresas con personas influyentes del momento. De esta manera, los mensajes que las empresas quieren transmitir se pueden difundir a través de diferentes plataformas como Twitter, blogs o Facebook.

### **2.1.1. Analisis Competitivo** 

| Competitive Analysis Landscape | |
|--------------------------------| - |
| ¿Por qué llevar a cabo este análisis? | Este análisis es importante para nuestra startup, ya que, de este modo podemos darnos cuenta cuales son nuestras ventajas y desventajas estando dentro del mercado y como poder realizar diferentes estrategias para poder aprovechar nuestras ventajas y poder contrarestar nuestras desventajas. |

| | | Connex | Coobis | Nuntia |
|-|-|-|-|-|
| Perfil | Overview | Connex es una plataforma que conecta influencers con empresas generando estadisticas para los usuarios | Coobis es una plataforma de marketing de contenidos que conecta marcas con influencers | Nuntia es una empresa que se dedica a conectar bloggers con marcas |
|  | Ventaja competitiva ¿Qué valor ofrece a los clientes? | Connex ofrece caracteristica como poder ver tus estadisticas con una marca, poder subir tu alcance en diferentes redes y poder personalizar tu feed, mostrandolo como un portafolio | Facilitan el aumento de visibilidad de los influencers registrados y las marcas con las que trabajan | Genera conversaciones online, promocionan diferentes acciones y escuchan activamente a través de los bloggers que trabajan con ellos día a día |
|  | Mercado Objetivo | Influnecers y Empresas | Influencer y Empresas | Bloggers y Empresas |
| Perfil de Marketing | Estategia de Marketing | Segmentación y Posicionamiento, Propuesta de valor para marcas y creadores, SEO, Campañas PPC y Programas de referencia | Marketing de contenidos, Marketplaces de Influencers, Automatitación y Segmentación y Modelo de Monitoreo y Reporting | Distribución de Contenidos y Notas de Prensa, Publicidad Nativa y SEO |
| Perfil de Producto | Productos y servicios | | | |
|  | Precios y costos | | | |
|  | Canales de distribución (Web y/o Móvil) | Web | Web | Web | 

### **2.1.2. Estrategias y tácticas frente a competidores** 

| Competidores | | Connex | Coobis | Nuntia |
|-|-|-|-|-|
| Análisis SWOT | Fortalezas | | | |
| | Debilidades | | | |
| | Oportunidades | | | |
| | Amenazas | | | |

## **2.2. Entrevistas** 
### **2.2.1. Diseño de Entrevistas** 
### **2.2.2. Registro de entrevistas** 
### **2.2.3. Ánalisis de entrevistas** 

## **2.3. Needfinding** 
### **2.3.1. User Personas** 
### **2.3.2. User Task Matrix** 
### **2.3.3. User Jorney Mapping** 
### **2.3.4. Empathy Mapping** 
### **2.3.5. As-is Scenario Mapping** 

## **2.4. Ubiquitous Language**

# **Capítulo III: Requirements Specification** 

## **3.1. To-Be Scenario Mapping**
## **3.2. User Stories** 
## **3.3. Impact Mapping** 
## **3.4. Product Backlog** 

# **Capítulo IV: Product Design** 

## **4.1. Style Guidelines** 
### **4.1.1. General Style Guidelines** 
### **4.1.2. Web Style Guidelines** 

## **4.2. Information Architecture** 
### **4.2.1. Organization Systems** 
### **4.2.2. Labeling Systems** 
### **4.2.3. SEO Tags and Meta Tags** 
### **4.2.4. Searching Systems** 
### **4.2.5. Navigation Systems** 

## **4.3. Landing Page UI Design** 
### **4.3.1. Landing Page Wireframe** 
### **4.3.2. Landing Page Mock-up** 

## **4.4. Web Applications UX/UI Design** 
### **4.4.1. Web Applications Wireframes** 
### **4.4.2. Web Applications Wireflow Diagrams** 
### **4.4.3. Web Applications Mock-ups** 
### **4.4.4. Web Applications User Flow Diagrams** 

## **4.5. Web Applications Prototyping** 

## **4.6. Domain-Driven Software Architecture** 
### **4.6.1. Software Architecture Context Diagram** 
### **4.6.2. Software Architecture Container Diagrams** 
### **4.6.3. Software Architecture Components Diagrams** 

## **4.7. Software Object-Oriented Design** 
### **4.7.1. Class Diagrams** 
### **4.7.2. Class Dictionary** 

## **4.8. Database Design** 
### **4.8.1. Database Diagram** 

# **Capítulo V: Product Implementation, Validation & Deployment**

## **5.1. Software Configuration Management**
### **5.1.1. Software Development Environment Configuration**
### **5.1.2. Source Code Management**
### **5.1.3. Source Code Style Guide & Conventions**
### **5.1.4. Software Deployment Configuration**

## **5.2. Landing Page, Services & Applications Implementation**
### **5.2.1. Sprint 1**
#### **5.2.1.1. Sprint Planning 1**
#### **5.2.1.2. Sprint Backlog 1**
#### **5.2.1.3. Development Evidence for Sprint Review**
#### **5.2.1.4. Testing Suite Evidence for Sprint Review**
#### **5.2.1.5. Execution Evidence for Sprint Review**
#### **5.2.1.6. Services Documentation Evidence for Sprint Review**
#### **5.2.1.7. Software Deployment Evidence for Sprint Review**
#### **5.2.1.8. Team Collaboration Insights during Sprint**

### **5.2.2. Sprint 2**
#### **5.2.2.1. Sprint Planning 2**
#### **5.2.2.2. Sprint Backlog 2**
#### **5.2.2.3. Development Evidence for Sprint Review**
#### **5.2.2.4. Testing Suite Evidence for Sprint Review**
#### **5.2.2.5. Execution Evidence for Sprint Review**
#### **5.2.2.6. Services Documentation Evidence for Sprint Review**
#### **5.2.2.7. Software Deployment Evidence for Sprint Review**
#### **5.2.2.8. Team Collaboration Insights during Sprint**

### **5.2.3. Sprint 3**
#### **5.2.3.1. Sprint Planning 3**
#### **5.2.3.2. Sprint Backlog 3**
#### **5.2.3.3. Development Evidence for Sprint Review**
#### **5.2.3.4. Testing Suite Evidence for Sprint Review**
#### **5.2.3.5. Execution Evidence for Sprint Review**
#### **5.2.3.6. Services Documentation Evidence for Sprint Review**
#### **5.2.3.7. Software Deployment Evidence for Sprint Review**
#### **5.2.3.8. Team Collaboration Insights during Sprint**

### **5.2.4. Sprint 4**
#### **5.2.4.1. Sprint Planning 4**
#### **5.2.4.2. Sprint Backlog 4**
#### **5.2.4.3. Development Evidence for Sprint Review**
#### **5.2.4.4. Testing Suite Evidence for Sprint Review**
#### **5.2.4.5. Execution Evidence for Sprint Review**
#### **5.2.4.6. Services Documentation Evidence for Sprint Review**
#### **5.2.4.7. Software Deployment Evidence for Sprint Review**
#### **5.2.4.8. Team Collaboration Insights during Sprint**

## **5.3. Validation Interviews**
### **5.3.1. Diseño de Entrevistas**
### **5.3.2. Registro de Entrevistas**
### **5.3.3. Evaluaciones según Heurísticas**

## **5.4. Video About-the-Product**

# **Conclusiones**

# **Bibliografía**

# **Anexos**
