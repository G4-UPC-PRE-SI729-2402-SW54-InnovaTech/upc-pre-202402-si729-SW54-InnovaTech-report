<div align="center">

![image](https://github.com/PetPalORG/PetPal-Informe/assets/164519824/55b272a3-26f7-4c8b-9da7-39b023ceaeb5)
</p> 

# Universidad Peruana de Ciencias Aplicadas

# INGENIERA DE SOFTWARE

# CURSO: SI729 Aplicaciones Open Source | SECCIÓN SW54 | 2024-2
 Profesor: Alberto Wilmer Sanchez Seña

**Startup:** Connex 

### Integrantes:
- Escobar Palomino, Sebastian Matias - U202125968
- Javier Murillo, Mathias - U202022211
- Macavilca Quispe, Ian - U202121325
- Nakasone Gomes, Marco Antonio - U202210790
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
En un mundo cada vez más digitalizado, donde las relaciones entre marcas e influencers juegan un papel crucial en la estrategia de marketing, surge Connex. Con un enfoque claro en la innovación y un compromiso con la excelencia, nuestro equipo está compuesto por profesionales con experiencia en marketing digital, desarrollo de software, y gestión empresarial, quienes trabajan en sinergia para hacer de Connex una plataforma líder en su sector.


### **1.1.1. Descripcion de la Startup** 
Connex es una plataforma digital que facilita la interacción y colaboración entre influencers de todos los niveles y empresas de diversos sectores. Las empresas pueden acceder a una amplia gama de influencers, analizar sus portafolios y estadísticas, y elegir aquellos que mejor se alineen a sus objetivos de marketing y comunicación con Connex. De manera similar, los influencers pueden conectarse con empresas interesadas en promocionar sus bienes o servicios, estableciendo relaciones de beneficio mutuo.
### **1.1.2. Perfiles de los integrantes del equipo**

|**Integrantes**|**Descripción del Perfil**|
| :-: | :-: |
|**Escobar Palomino , Sebastian Matias (U202125968)**<img src="https://github.com/G4-UPC-PRE-SI729-2402-SW54-InnovaTech/upc-pre-202402-si729-SW54-InnovaTech-report/blob/d0f175ff041622410a361f357fed233ec57d4c16/Assets/Sebastian%20Escobar%20Palomino.png?raw=true" width="300"/>|Como estudiante de ingeniería de software, me comprometo a contribuir al máximo en el grupo y a cumplir con las entregas dentro del plazo establecido, manteniendo una comunicación efectiva con mis compañeros y aplicando mis habilidades para desarrollar las tareas asignadas en este proyecto.|
|**Javier Murillo, Mathias (U202022211)**<img src="https://github.com/G4-UPC-PRE-SI729-2402-SW54-InnovaTech/upc-pre-202402-si729-SW54-InnovaTech-report/blob/main/Assets/MathiasJM.jpg?raw=true" width="300"/>|Siendo estudiante de Ingeniería de Software, me permite aportar con mis conocimientos desarrollados a lo largo de mi formación como ingeniero, esperando dar un gran apoyo y relevancia en el equipo. |
|**Macavilca Quispe, Ian (U202121325)**<img src="https://github.com/G4-UPC-PRE-SI729-2402-SW54-InnovaTech/upc-pre-202402-si729-SW54-InnovaTech-report/blob/main/Assets/IanMQ.png?raw=true" width="300"/>|Como estudiante de Ingeniería de Software, mi destreza en el pensamiento lógico me habilita para abordar desafíos de manera eficaz, optimizar procesos, diseñar software robusto, comunicar de manera clara, ser resiliente ante obstáculos y colaborar efectivamente en equipos, con lo que pienso aportar al éxito y eficiencia de la startup.|
|**Laban Hijar, Jorge Armando (U201616054)**<img src="https://github.com/G4-UPC-PRE-SI729-2402-SW54-InnovaTech/upc-pre-202402-si729-SW54-InnovaTech-report/blob/main/Assets/JorgeLH.png?raw=true" width="300"/>|Soy estudiante de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. En un principio escogí esa carrera porque siempre me interesó el tema de tecnología y el desarrollo de aplicaciones web.|
|**Nakasone Gomes, Marco Antonio (U202210790)**<img src=" " width="300"/>|Soy estudiante de Ingeniería de software, tengo cualidades como la perseverancia, que me va a ayudar a ser resiliente ante cualquier adversidad que se nos presente más adelante en el trabajo y tambien soy buen compañero de trabajo que siempre quiere lo mejor para su grupo.|


## **1.2. Solution Profile** 
### **1.2.1. Antecedentes y problemáticas** 

**What?**

Connex es una plataforma creada para facilitar y optimizar la conexión entre empresas e influencers, permitiendo que ambos encuentren socios estratégicos de manera eficiente. La plataforma ofrece herramientas que simplifican el proceso de identificación, selección y gestión de colaboraciones entre marcas e influencers.

**Why?**

Porque las empresas enfrentan crecientes desafíos para encontrar influencers que realmente representen sus valores y lleguen a su audiencia objetivo. Al mismo tiempo, los influencers necesitan plataformas confiables que les ofrezcan oportunidades de colaboración con marcas relevantes. La falta de un espacio centralizado para gestionar estas relaciones lleva a procesos ineficientes, decisiones desacertadas y oportunidades perdidas.

**Where?**

Este problema es global, afectando tanto a pequeñas como a grandes empresas que buscan expandir su presencia digital a través del marketing de influencers. De igual manera, influencers en todo el mundo se ven limitados por la falta de herramientas que les permitan gestionar sus colaboraciones de manera efectiva.

**When?**

La necesidad surge a medida que el marketing de influencers se convierte en una estrategia central para las empresas, que buscan diferenciarse y conectar con audiencias de manera auténtica. Los influencers, por su parte, requieren una gestión más profesional de sus colaboraciones para maximizar su impacto y crecimiento.

**Who?**

Las principales partes afectadas son las empresas, que necesitan encontrar influencers adecuados para sus campañas, y los influencers, que buscan oportunidades de colaboración que se alineen con su marca personal. Ambos grupos enfrentan desafíos en la gestión de estas relaciones sin una plataforma especializada como Connex.

**How?**

Connex aborda esta problemática proporcionando una plataforma integral que permite a las empresas y a los influencers conectarse de manera eficiente. A través de Connex, las empresas pueden revisar portafolios de influencers y establecer colaboraciones estratégicas, mientras que los influencers pueden acceder a oportunidades relevantes para potenciar su carrera.

### **1.2.2. Lean UX Process** 
#### **1.2.2.1. Lean UX Problem Statments** 

El estado actual del dominio del marketing digital, específicamente dentro de las plataformas que conectan empresas e influencers, se ha centrado principalmente en abordar las necesidades de varios segmentos de clientes, incluidas empresas de sectores como tecnología, moda, belleza y alimentos, así como influencers de todos los niveles. Sin embargo, estos esfuerzos a menudo no logran abordar completamente las necesidades de las empresas que luchan por identificar y gestionar colaboraciones con influencers de manera efectiva, y de los influencers que encuentran dificultades para conectarse con marcas relevantes y gestionar sus asociaciones de manera eficiente.

Lo que los productos/servicios existentes no logran abordar es la falta de una plataforma centralizada y especializada que simplifique y optimice todo el proceso de conexión entre empresas e influencers. Las herramientas actuales están fragmentadas y son ineficientes, y no ofrecen una solución integral para gestionar todas las etapas de la colaboración, desde el descubrimiento hasta la ejecución y el seguimiento.

Nuestro producto, Connex, abordará esta brecha creando un ecosistema confiable que facilite la identificación, selección y gestión de colaboraciones entre empresas e influencers. Ofreceremos herramientas avanzadas que permitan a las empresas analizar el impacto de sus campañas y a los influencers gestionar sus acuerdos de manera profesional.

Nuestro enfoque inicial será en el mercado peruano, dirigiéndose a empresas medianas del sector entretenimiento y a microinfluencers e influencers medianos que buscan crecer y encontrar nuevas oportunidades de colaboración. Estos segmentos fueron elegidos por su alto potencial y la necesidad crítica de una plataforma eficiente como Connex.

Sabremos que hemos tenido éxito cuando observemos comportamientos que indiquen que nuestros segmentos objetivo están utilizando Connex de manera consistente, lo que se reflejará en un aumento de colaboraciones exitosas y mejoras en la satisfacción y retención de los usuarios.

#### **1.2.2.2. Lean UX Assumptions** 

**¿Quién es el usuario?**

Los usuarios de Connex son principalmente dos grupos:

- Empresas medianas que buscan conectar con influencers para aumentar su visibilidad y mejorar sus campañas de marketing.
- Microinfluencers y medianos influencers que desean acceder a oportunidades de colaboración con marcas relevantes para crecer y monetizar su influencia.

**¿Dónde encaja nuestro producto, en su trabajo o en su vida?**

Para las empresas, Connex se integra en su estrategia de marketing digital, facilitando la búsqueda y gestión de influencers para sus campañas. Para los influencers, Connex se convierte en una herramienta esencial en su vida profesional, ayudándolos a encontrar y gestionar colaboraciones que impulsen su carrera.

**¿Qué problema resuelve nuestro producto?**

Connex resuelve la dificultad de encontrar y gestionar colaboraciones eficaces entre empresas e influencers. Simplifica el proceso de identificación, contacto y seguimiento de las campañas, optimizando el tiempo y los recursos de ambas partes.

**¿Cuándo y cómo se utiliza nuestro producto?**

El producto se utiliza durante las fases de planificación, ejecución y seguimiento de campañas de marketing. Las empresas lo usan para buscar y seleccionar influencers, gestionar acuerdos y monitorear el rendimiento de las campañas. Los influencers lo usan para buscar oportunidades de colaboración y gestionar sus acuerdos con las marcas.

**¿Qué características son importantes?**

- Búsqueda avanzada y filtrado para encontrar influencers adecuados según criterios específicos.
- Portafolios detallados de influencers con métricas de rendimiento.
- Gestión de campañas para organizar y seguir el progreso de las colaboraciones.
- Herramientas de comunicación integradas para facilitar la negociación y coordinación.
- Análisis de rendimiento para medir el éxito de las campañas y la influencia.

**¿Cómo debe verse y comportarse nuestro producto?**

Connex debe tener una interfaz intuitiva y profesional, fácil de usar tanto para empresas como para influencers. El diseño debe ser limpio, moderno y accesible, con una navegación clara que permita a los usuarios encontrar rápidamente lo que necesitan. El comportamiento del producto debe ser fluido, respondiendo rápidamente a las acciones del usuario y proporcionando retroalimentación clara en cada paso.

#### **1.2.2.3. Lean UX Hypothesis Statements** 

**Usuario cliente**

Creemos que lograremos posicionar a Connex como líder en el sector del entretenimiento en Perú<br>
Si las empresas del sector entretenimiento e influencers<br>
Obtienen un proceso simplificado y efectivo para gestionar colaboraciones y campañas<br>
Con una plataforma digital que conecta eficientemente a empresas con influencers, permitiendo la gestión completa de colaboraciones y campañas<br>


#### **1.2.2.4. Lean UX Canvas** 

<img src="https://github.com/G4-UPC-PRE-SI729-2402-SW54-InnovaTech/upc-pre-202402-si729-SW54-InnovaTech-report/blob/main/Assets/uxcanvas.JPG?raw=true" style="width: 100%;"/>

## **1.3. Segmentos objetivo** 

**Empresas medianas en Perú**

Características Demográficas:

- Tamaño de la Empresa: Suelen tener entre 50 y 250 empleados.
- Ubicación: Mayormente ubicadas en las principales ciudades del Perú, como Lima, Arequipa, y Trujillo.
- Industria: Empresas enfocadas en la producción de contenido, eventos, y medios de entretenimiento que buscan aumentar su visibilidad y engagement a través de campañas de marketing de influencers.
- Capacidad de Inversión en Marketing: Empresas con presupuestos de marketing que oscilan entre los $10,000 y $100,000 anuales, con una creciente inversión en estrategias de marketing digital.

Información Estadística:

- Según, el portal de noticias, Gestión, se espera que el sector entretenimiento y medios de comunicación en Perú generará US$ 6,624 millones en el 2026, dado su rápida recuperación post pandemia.
- La inversión publicitaria en influencers durante el año 2022 ha superado los 16.4 billones de dólares a nivel mundial, lo que supone un 18,84% de incremento respecto al 2021 y un 864% respecto al año 2016, según un estudio de influencer marketing Hub.

**Microinfluencers y medianos influencers en Perú**

Características Demográficas:

- Edad: Predominantemente jóvenes entre 18 y 35 años.
Seguidores:
- Microinfluencers: Con una base de seguidores entre 5,000 y 50,000.
- Influencers Medianos: Con una base de seguidores entre 50,000 y 500,000.
- Ubicación: Mayormente concentrados en Lima, aunque también hay una presencia significativa en otras regiones como Cusco, Piura, y Arequipa.
- Áreas de Enfoque: Especializados en contenido relacionado con moda, tecnología, belleza, estilo de vida, y entretenimiento.

Información Estadística:

- Los jóvenes peruanos pasan una cantidad considerable de tiempo en redes sociales como Facebook, Instagram, TikTok y Twitter. Un estudio realizado por la Universidad de Lima reveló que el 90% de los adolescentes entre 12 y 17 años utilizan redes sociales diariamente, con un promedio de cuatro horas al día.
- En 2023, el mercado de microinfluencers en Perú tuvo un crecimiento del 25%, y se espera que continúe en aumento debido a la efectividad de las campañas en nichos específicos.
- Las últimas estadísticas de influencer marketing para el 2023 indican que los micro influencers generaron hasta un 60% más de engagement que los macro influencers, según Alonso Salinas, Country Manager de MileniumGroup Perú.

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

| Competitive Analysis Landscape |   |
|--------------------------------| - |
| ¿Por qué llevar a cabo este análisis? | Este análisis es importante para nuestra startup, ya que, de este modo podemos darnos cuenta cuales son nuestras ventajas y desventajas estando dentro del mercado y como poder realizar diferentes estrategias para poder aprovechar nuestras ventajas y poder contrarestar nuestras desventajas. |

| | | Connex | Coobis | Nuntia |
|-|-|-|-|-|
| Perfil | Overview | Connex es una plataforma que conecta influencers con empresas generando estadisticas para los usuarios | Coobis es una plataforma de marketing de contenidos que conecta marcas con influencers | Nuntia es una empresa que se dedica a conectar bloggers con marcas |
|  | Ventaja competitiva ¿Qué valor ofrece a los clientes? | Connex ofrece caracteristica como poder ver tus estadisticas con una marca, poder subir tu alcance en diferentes redes y poder personalizar tu feed, mostrandolo como un portafolio | Facilitan el aumento de visibilidad de los influencers registrados y las marcas con las que trabajan | Genera conversaciones online, promocionan diferentes acciones y escuchan activamente a través de los bloggers que trabajan con ellos día a día |
|  | Mercado Objetivo | Influnecers y Empresas | Influencer y Empresas | Bloggers y Empresas |
| Perfil de Marketing | Estategia de Marketing | Segmentación y Posicionamiento, Propuesta de valor para marcas y creadores, SEO, Campañas PPC y Programas de referencia | Marketing de contenidos, Marketplaces de Influencers, Automatitación y Segmentación y Modelo de Monitoreo y Reporting | Distribución de Contenidos y Notas de Prensa, Publicidad Nativa y SEO |
| Perfil de Producto | Productos y servicios | Aplicación web desarrollada para Influencer y marcas, que gestiona los vinculos entre ellos y sus estadisticas de manera personalizada por el propio usuario | Aplicacion web relaciona con el marketing de contenidos, que contecta marcas con influencers | Aplicacion web dedicada a relacionar bloggers con empresas |
|  | Precios y costos | Plan Free, Plan Premium (S/.29.99) y Plan Business (S/.19.99) | Se queda con 30% de tus colaboraciones | Tarifa de publicación varia entre 200 y 1000 dolarés, y puede llegar a más |
|  | Canales de distribución (Web y/o Móvil) | Web | Web | Web | 

### **2.1.2. Estrategias y tácticas frente a competidores** 

| Competidores | | Connex | Coobis | Nuntia |
|-|-|-|-|-|
| Análisis SWOT | Fortalezas | Herramienta de análisis para evaluar portafolios y estadísticas de influencers, Enfoque en establecer relaciones de beneficio mutuo entre influencers y empresas y Diversidad Sectorial, permitiendo que diversos sectores accedan a una gama amplia de incluencers | Amplia red de creadores de contenido  y herramientas de segmentación y automatización | Experiencia en distribución de contenido y notas de prensa, también contando una amplia red de medios de comunicación |
| | Debilidades | Competencia con plaformas ya establecidas en el mercado con un reputacion consolidada, Posibles limitaciones de recursos comparados con plataformas más grandes | Puede tener un enfoque limitado en influencers y los costos pueden ser elevados para algunas empresas | No enfocarse tanto en la colaboración directa con influencers, lo que puede limitar su alcance en el mercado de marketing de influencers |
| | Oportunidades | Crecimiento del marketing de influencers, Expansión de servicios y Mercados Internacionales | Expansión en el mercado de publicidad nativa y contenido patrocinado | Expansión de servicios para incluir nuevas formas de colaboración de contenido |
| | Amenazas | Competencia con plataformas ya establecidas y Saturación del mercado | Competencia de  plataformas emergentes | Competencia con plataformas especializadas en infñuencers y marketing digital |

## **2.2. Entrevistas** 
### **2.2.1. Diseño de Entrevistas** 

**Preguntas Generales**

1. ¿Cuales es tu nombre?
2. En caso seas parte una empresa ¿Cual es el tamaño de la empresa, en cuanto a trabajadores y marca?
3. En caso seas influencer ¿Que tipo de contenido produces? ¿Y para que redes?

**Preguntas para el Influencer**

1. ¿Que plataformas usas para gestionar tus campañas o conectar con marcas?
2. ¿Como llevas las estadísticas de tus redes despúes de una campaña?
3. ¿Que crees que es lo más importante al concretar una campaña con alguna marca?

**Preguntas para las empresas**

1. ¿Que tipo de contenido crees que es necesario para tu empresa?
2. ¿Te guías mucho por las estadísticas de los influencers a la hora de contactarlos para alguna campaña?
3. ¿Conoces alguna aplicación para poder establecer contacto o encontrar a el creador de contenido adecuado para el rubro de tu empresa?

### **2.2.2. Registro de entrevistas** 
### **2.2.3. Ánalisis de entrevistas** 

## **2.3. Needfinding** 
### **2.3.1. User Personas** 

**User Persona: Influencer:**
<br>
<img src="Assets/UserPersona-Influencer.png" width="100%"/>
<br>
**User Persona: Empresa**
<br>
<img src="Assets/UserPersona-Empresa.png" width="100%"/>
### **2.3.2. User Task Matrix** 
**Creadores de contenido para Redes Sociales (Influencers)**
|  |  User 1  | User 2 | User 3  | User 4 |
| --- | ----------- | ------------ | ----------- | ---------- |
| Saben como crear un portafolio atractivo  | <span style="color:#90D26D; font-weight:bold">SI</span>   | <span style="color:#FFC700; font-weight:bold">NO</span>| <span style="color:#90D26D; font-weight:bold">SI</span>   | <span style="color:#90D26D; font-weight:bold">SI</span> |
| Conocen herramientas de análisis de métricas | <span style="color:#FFC700; font-weight:bold">NO</span> | <span style="color:#E72929; font-weight:bold">NO</span>        | <span style="color:#FFC700; font-weight:bold">SI</span>         | <span style="color:#E72929; font-weight:bold">NO</span>       |
| Tienen experiencia gestionando múltiples campañas | <span style="color:#90D26D; font-weight:bold">SI</span> | <span style="color:#90D26D; font-weight:bold">SI</span>        | <span style="color:#FFC700; font-weight:bold">NO</span>         | <span style="color:#90D26D; font-weight:bold">SI</span>       | 
| Colaboran con marcas reconocidas | <span style="color:#FFC700; font-weight:bold">SI</span> | <span style="color:#FFC700; font-weight:bold">NO</span>        | <span style="color:#FFC700; font-weight:bold">NO</span>         | <span style="color:#E72929; font-weight:bold">NO</span>       |

**Empresas con Marketing Digital** 
|  |  User 1  | User 2 | User 3  | User 4 |
| --- | ----------- | ------------ | ----------- | ---------- |
| Tienen un equipo dedicado al marketing digital  | <span style="color:#90D26D; font-weight:bold">SI</span>   | <span style="color:#90D26D; font-weight:bold">SI</span>| <span style="color:#90D26D; font-weight:bold">SI</span>   | <span style="color:#90D26D; font-weight:bold">SI</span> |
| Conocen el mercado de influencers | <span style="color:#E72929; font-weight:bold">NO</span> | <span style="color:#E72929; font-weight:bold">NO</span>        | <span style="color:#FFC700; font-weight:bold">POCO</span>         | <span style="color:#E72929; font-weight:bold">NO</span>       |
| Pueden gestionar varias campañas a la vez | <span style="color:#90D26D; font-weight:bold">SI</span> | <span style="color:#90D26D; font-weight:bold">SI</span>        | <span style="color:#FFC700; font-weight:bold">POCO</span>         | <span style="color:#90D26D; font-weight:bold">SI</span>       | 
| Buscan influencers con alto alcance y reconocimiento | <span style="color:#90D26D; font-weight:bold">SI</span> | <span style="color:#90D26D; font-weight:bold">SI</span>        | <span style="color:#90D26D; font-weight:bold">SI</span>         | <span style="color:#90D26D; font-weight:bold">SI</span>       |
### **2.3.3. User Jorney Mapping** 
**Registro: ¿Por qué confirarían en nosotros?**
- Los usuarios potenciales investigan Connex en redes sociales, blogs, y articulos de terceros para validar su relevancia.
- Buscan reseñas y testimonios de otros influencers o empresas que ya han usado Connex.
- Evalúan nuestra propuesta de valor, las estadísticas y la transparencia sobre cómo funcionan las colaboraciones en la plataforma.

**Incorporación y Primer Uso: ¿Cómo pueden sentirse exitosos?**
- El proceso de registro y configuración del perfil es sencillo, con instrucciones claras y sin complicaciones.
- La interfaz de usuario es intuitiva, permitiendo encontrar fácilmente oportunidades, perfiles y funcionalidades clave.

**Compatir: ¿Por qué invitarían a otro?s**
- Los usuarios perciben el valor añadido en funcionalidades como herramientas de comunicación directa, sistemas de recomendación y seguimiento de métricas.
- La calidad de los proyectos, la facilidad para conectar con empresas/influencers, y los insights proporcionados fomenta confianza y satisfaccion.
- Se implementan programas de referidos, bonificaciones o acceso a funciones premium como motivación pra invitar a nuevos usuarios.
### **2.3.4. Empathy Mapping** 
### **2.3.5. As-is Scenario Mapping** 

## Influencers

| **Fases**   | **Fase 1: Descubrimiento**                  | **Fase 2: Registro y Configuración**      | **Fase 3: Búsqueda y Aplicación**            | **Fase 4: Colaboración y Evaluación**        |
|-------------|--------------------------------------------|------------------------------------------|---------------------------------------------|---------------------------------------------|
| **Doing**   | Buscando información sobre Connex en redes sociales y blogs. | Registrándose en la plataforma y creando su perfil. | Explorando oportunidades de colaboración y aplicando a campañas. | Coordinando la entrega de contenido y revisando métricas post-campaña. |
| **Thinking**| "¿Será esta la plataforma adecuada para mi crecimiento?" | "¿Cómo puedo crear un perfil atractivo?" | "¿Cuál es la campaña más alineada con mi audiencia?" | "¿Estoy entregando el contenido adecuado para la marca?" |
| **Feeling** | Curioso pero algo escéptico.               | Emocionado pero con algo de incertidumbre sobre la configuración. | Motivado pero ansioso por la competencia. | Confianza pero también algo de presión por cumplir con las expectativas. |

## Empresas

| **Fases**   | **Fase 1: Descubrimiento**                  | **Fase 2: Registro y Configuración**      | **Fase 3: Búsqueda y Selección de Influencers**| **Fase 4: Gestión de Campaña y Evaluación**   |
|-------------|--------------------------------------------|------------------------------------------|-----------------------------------------------|---------------------------------------------|
| **Doing**   | Investigando Connex como opción para marketing con influencers. | Registrándose en la plataforma y definiendo objetivos de marketing. | Explorando perfiles de influencers y seleccionando los adecuados. | Supervisando la ejecución de la campaña y revisando resultados. |
| **Thinking**| "¿Será Connex la mejor plataforma para conectar con influencers relevantes?" | "¿Cómo configuro mi perfil para atraer los influencers adecuados?" | "¿Qué influencers pueden aportar mayor valor a mi campaña?" | "¿El ROI de la campaña cumple con nuestras expectativas?" |
| **Feeling** | Interesado pero con dudas sobre la inversión. | Expectante y planificando estrategias. | Confiado pero atento a encontrar el match ideal. | Satisfecho si la campaña fue exitosa, o analizando posibles mejoras. |

## **2.4. Ubiquitous Language**

# **Capítulo III: Requirements Specification** 

## **3.1. To-Be Scenario Mapping**
## 4. Escenario Futuro (To-Be Scenario Mapping)

### Influencers:

| **Fases**   | **Descubrimiento Mejorado**                                        | **Registro y Configuración Automatizada**                               | **Búsqueda y Aplicación Optimizada**                                  | **Colaboración y Evaluación Mejorada**                                |
|-------------|--------------------------------------------------------------------|--------------------------------------------------------------------------|------------------------------------------------------------------------|------------------------------------------------------------------------|
| **Doing**   | Connex ofrece contenido personalizado en redes sociales y blogs.   | Sistema automatizado para importar datos y configurar perfiles rápidamente. | Función de búsqueda avanzada con recomendaciones basadas en intereses. | Coordinación de contenido y revisión de métricas automatizada.        |
| **Thinking**| "Connex me entiende, es ideal para mi carrera."                    | "Crear un perfil es fácil y me ayuda a destacar."                        | "Estas campañas son perfectas para mi audiencia."                     | "Estoy seguro de que cumpliré las expectativas con estas herramientas."|
| **Feeling** | Confiado en que Connex es la plataforma adecuada.                  | Tranquilo y satisfecho con el proceso de configuración.                  | Seguro y motivado para competir por las mejores campañas.              | Relajado, confiado en la calidad de la colaboración.                   |

### Empresas:

| **Fases**   | **Descubrimiento Mejorado**                                        | **Registro y Configuración Guiada**                                     | **Búsqueda y Selección Eficiente de Influencers**                     | **Gestión y Evaluación Automatizada de Campañas**                     |
|-------------|--------------------------------------------------------------------|--------------------------------------------------------------------------|------------------------------------------------------------------------|------------------------------------------------------------------------|
| **Doing**   | Connex proporciona casos de éxito y análisis de ROI en la plataforma. | Configuración guiada con recomendaciones personalizadas de objetivos.  | Herramienta de selección rápida con IA que sugiere influencers ideales. | Sistema de gestión que automatiza el seguimiento y proporciona análisis en tiempo real. |
| **Thinking**| "Connex es la opción más confiable para nuestras campañas."         | "Este proceso de configuración nos prepara para el éxito."               | "Estos influencers son exactamente lo que necesitamos."               | "El ROI está claramente definido y es fácil de seguir."                |
| **Feeling** | Convencido de la relevancia y utilidad de Connex.                  | Seguro de haber configurado un perfil competitivo y eficaz.             | Confiado en la elección de influencers y el éxito de la campaña.       | Tranquilo y satisfecho con la gestión automatizada y los resultados claros. |


## **3.2. User Stories** 

| User Story ID | Título                                       | Descripción                                                                                                                                          | Criterios de Aceptación                                                                                                                                                     | Relación (EPIC ID) |
|---------------|---------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------|
| US01          | Filtrado avanzado de influencers            | Como empresa usuaria de Connex, quiero poder filtrar influencers por criterios específicos como audiencia, sector, y ubicación, para asegurarme de que selecciono a los más adecuados para mi campaña. | Los usuarios pueden aplicar múltiples filtros simultáneamente. Los resultados se actualizan en tiempo real al aplicar los filtros. Los filtros incluyen categorías como demografía de la audiencia, ubicación geográfica, sector y nivel de influencia. | EP-001             |
| US02          | Creación de portafolios personalizados por influencers | Como influencer en Connex, quiero crear y personalizar mi portafolio para mostrar mis métricas de rendimiento, para atraer a marcas relevantes. | Los influencers pueden agregar y editar contenido en su portafolio (videos, fotos, estadísticas). El portafolio muestra métricas clave como alcance, engagement y demografía de la audiencia. Los influencers pueden actualizar su portafolio en tiempo real. | EP-002             |
| US03          | Gestión de acuerdos de colaboración         | Como empresa usuaria de Connex, quiero gestionar acuerdos de colaboración con influencers dentro de la plataforma, para mantener todo centralizado y organizado. | Los acuerdos pueden ser creados, editados y almacenados en la plataforma. Ambas partes pueden revisar y firmar acuerdos digitalmente. Los términos clave del acuerdo (plazos, entregables, pagos) son fácilmente visibles. | EP-001             |
| US04          | Comunicación integrada entre empresas e influencers | Como usuario de Connex, quiero comunicarme directamente con influencers o empresas a través de la plataforma, para coordinar detalles de colaboración sin necesidad de utilizar herramientas externas. | La plataforma incluye un sistema de mensajería interna. Las conversaciones se pueden etiquetar y organizar por campaña o colaboración. Notificaciones automáticas alertan a los usuarios de nuevos mensajes. | EP-001             |
| US05          | Análisis de rendimiento de campañas         | Como empresa usuaria de Connex, quiero analizar el rendimiento de mis campañas de influencers dentro de la plataforma, para medir su efectividad y ajustar futuras estrategias. | La plataforma ofrece reportes detallados con métricas de rendimiento como alcance, engagement y conversión. Los reportes pueden ser exportados en formatos como PDF o CSV. Los resultados de las campañas se actualizan en tiempo real. | EP-003             |
| US06          | Notificaciones de oportunidades de colaboración | Como influencer en Connex, quiero recibir notificaciones de nuevas oportunidades de colaboración que se alineen con mi perfil, para aprovechar rápidamente las mejores ofertas. | Los influencers reciben notificaciones automáticas basadas en las preferencias y categorías que han seleccionado. Las oportunidades relevantes se destacan en el dashboard del usuario. Los influencers pueden ajustar la frecuencia y tipo de notificaciones que reciben. | EP-002             |
| US07          | Registro de nuevas empresas e influencers    | Como nuevo usuario de Connex, quiero registrarme fácilmente en la plataforma, ya sea como empresa o influencer, para empezar a utilizar sus servicios rápidamente. | El proceso de registro es simple y rápido, requiriendo solo la información esencial. Los usuarios pueden registrarse usando su correo electrónico o cuentas de redes sociales. Los nuevos usuarios reciben una guía inicial sobre cómo utilizar la plataforma. | EP-004             |
| US08          | Dashboard personalizado para usuarios       | Como usuario de Connex, quiero un dashboard personalizado que muestre las métricas, oportunidades y actividades más relevantes para mí, para gestionar mi cuenta de manera eficiente. | El dashboard muestra un resumen de las campañas activas, oportunidades y métricas clave. Los usuarios pueden personalizar qué elementos ven en su dashboard. Las actualizaciones y notificaciones recientes son destacadas en el dashboard. | EP-003             |
| US09          | Sistema de evaluación y feedback post-colaboración | Como usuario de Connex, quiero poder evaluar y dejar feedback después de una colaboración, para mejorar la calidad de futuras interacciones en la plataforma. | Los usuarios pueden calificar y dejar comentarios sobre la experiencia de la colaboración. Los resultados de las evaluaciones se reflejan en los perfiles de las empresas e influencers. El sistema de evaluación es confidencial y asegura la autenticidad del feedback. | EP-002             |
| US10          | Herramienta de búsqueda de influencers emergentes | Como empresa usuaria de Connex, quiero tener acceso a una herramienta que me permita descubrir influencers emergentes con alto potencial, para aprovechar su crecimiento y relevancia antes que mis competidores. | La herramienta identifica influencers emergentes basados en tendencias de crecimiento y engagement. Los resultados pueden ser filtrados por sector, audiencia y geografía. Las empresas reciben alertas sobre influencers que muestran un rápido aumento en popularidad. | EP-001             |

## **3.3. Impact Mapping** 

<img src="https://github.com/user-attachments/assets/4320b405-af36-4a38-9955-308ad29c796c" style="width: 100%;"/>

## **3.4. Product Backlog** 

| Prioridad | User Story ID | Título                                    | Story Points |
|-----------|---------------|------------------------------------------|--------------|
| Alta      | US01          | Filtrado avanzado de influencers         | 8            |
| Alta      | US03          | Gestión de acuerdos de colaboración      | 8            |
| Alta      | US04          | Comunicación integrada                   | 5            |
| Media     | US05          | Análisis de rendimiento de campañas      | 13           |
| Media     | US02          | Creación de portafolios personalizados   | 8            |
| Media     | US07          | Registro de nuevas empresas e influencers | 3            |
| Baja      | US06          | Notificaciones de oportunidades          | 5            |
| Baja      | US08          | Dashboard personalizado                  | 8            |
| Baja      | US09          | Evaluación y feedback post-colaboración  | 5            |
| Baja      | US10          | Búsqueda de influencers emergentes       | 8            |


# **Capítulo IV: Product Design** 

## **4.1. Style Guidelines** 

A continuación, se presentará un repositorio central y organizado que servirá como guía para el desarrollo enfocado y consistente de nuestra solución.

### **4.1.1. General Style Guidelines** 

**Brand Overview**

Connex es una plataforma digital innovadora que redefine la manera en que las empresas y los influencers se conectan y colaboran. En un mundo donde la influencia digital es clave para el éxito comercial, Connex se posiciona como el puente perfecto que une a las marcas con los creadores de contenido, facilitando una sinergia que potencia el alcance y la efectividad de las campañas de marketing.

**Brand Name**

El nombre "Connex" es una combinación estratégica que refleja la esencia de la marca: "Connection" (conexión) y "Exchange" (intercambio). Connex encapsula la misión central de la plataforma, que es facilitar y fortalecer las conexiones entre empresas e influencers, promoviendo el intercambio de valor y oportunidades en el ámbito digital. Es un nombre moderno, breve y memorable, lo que facilita su reconocimiento y posicionamiento en el mercado global del marketing de influencers.

A continuación, se presenta el logo o marca de nuestra solución propuesta.

<img src="https://github.com/G4-UPC-PRE-SI729-2402-SW54-InnovaTech/upc-pre-202402-si729-SW54-InnovaTech-report/blob/main/Assets/logo.JPG?raw=true" style="width: 100%;"/>



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
