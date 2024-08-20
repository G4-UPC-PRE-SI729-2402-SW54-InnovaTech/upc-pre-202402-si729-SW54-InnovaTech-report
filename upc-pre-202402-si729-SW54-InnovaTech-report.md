<div align="center">

![image](https://github.com/PetPalORG/PetPal-Informe/assets/164519824/55b272a3-26f7-4c8b-9da7-39b023ceaeb5)

# Universidad Peruana de Ciencias Aplicadas

# INGENIERA DE SOFTWARE

# CURSO: SI729 Aplicaciones Open Source | SECCIÓN SW54 | 2024-2
 Profesor: Alberto Wilmer Sanchez Seña

**Startup:** 

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
1. [Capítulo I: Introducción](#cap1)<br>
   1.1. [Startup Profile](#1.1.)<br>
      1.1.1. [Descripción del startup](#1.1.1.)<br>
      1.1.2. [Perfiles de los integrantes del equipo](#1.1.2.)<br>
   1.2. [Solution Profile](#1.2.)<br>
      1.2.1. [Antecedentes y Problemática](#1.2.1.)<br>
      1.2.2. [Lean UX Process](#1.2.2.)<br>
        1.2.2.1. [Lean UX Problem Statements](#1.2.2.1.)<br>
        1.2.2.2. [Lean UX Assumptions](#1.2.2.2.)<br>
        1.2.2.3. [Lean UX Hypothesis Statements](#1.2.2.3.)<br>
        1.2.2.4. [Lean UX Canvas](#1.2.2.4.)<br>
   1.3. [Segmentos objetivo](#1.3.)<br>
2. [Capítulo II: Requirements Elicitation & Analysis](#cap2)<br>
   2.1. [Competidores](#2.1.)<br>
      2.1.1. [Análisis competitivo](#2.1.1.)<br>
      2.1.2. [Estrategias y tácticas frente a competidores](#2.1.2.)<br>
   2.2. [Entrevistas](#2.2.)<br>
      2.2.1. [Diseño de entrevistas](#2.2.1.)<br>
      2.2.2. [Registro de entrevistas](#2.2.2.)<br>
      2.2.3. [Análisis de entrevistas](#2.2.3.)<br>
   2.3. [Needfinding](#2.3.)<br>
      2.3.1. [User Personas](#2.3.1.)<br>
      2.3.2. [User Task Matrix](#2.3.2.)<br>
      2.3.3. [User Journey Mapping](#2.3.3.)<br>
      2.3.4. [Empathy Mapping](#2.3.4.)<br>
      2.3.5. [As-is Scenario Mapping](#2.3.5.)<br>
   2.4. [Ubiquitous Language](#2.4.) <br>
3. [Capítulo III: Requirements Specification](#cap3)<br>
   3.1. [To-Be Scenario Mapping](#3.1.)<br>
   3.2. [User Stories](#3.2.)<br>
   3.3. [Impact Mapping](#3.3.)<br>
   3.4. [Product Backlog](#3.4.)<br>
4. [Capítulo IV: Product Design](#cap4)<br>
   4.1. [Style Guidelines](#4.1.)<br>
      4.1.1. [General Style Guidelines](#4.1.1.)<br>
      4.1.2. [Web Style Guidelines](#4.1.2.)<br>
   4.2. [Information Architecture](#4.2.)<br>
      4.2.1. [Organization Systems](#4.2.1.)<br>
      4.2.2. [Labeling Systems](#4.2.2.)<br>
      4.2.3. [SEO Tags and Meta Tags](#4.2.3.)<br>
      4.2.4. [Searching Systems](#4.2.4.)<br>
      4.2.5. [Navigation Systems](#4.2.5.)<br>
   4.3. [Landing Page UI Design](#4.3.)<br>
      4.3.1. [Landing Page Wireframe](#4.3.1.)<br>
      4.3.2. [Landing Page Mock-up](#4.3.2.)<br>
   4.4. [Web Applications UX/UI Design](#4.4.)<br>
      4.4.1. [Web Applications Wireframes](#4.4.1.)<br>
      4.4.2. [Web Applications Wireflow Diagrams](#4.4.2.)<br>
      4.4.3. [Web Applications Mock-ups](#4.4.3.)<br>
      4.4.4. [Web Applications User Flow Diagrams](#4.4.4.)<br>
   4.5. [Web Applications Prototyping](#4.5.)<br>
   4.6. [Domain-Driven Software Architecture](#4.6.)<br>
      4.6.1. [Software Architecture Context Diagram](#4.6.1.)<br>
      4.6.2. [Software Architecture Container Diagrams](#4.6.2.)<br>
      4.6.3. [Software Architecture Components Diagrams](#4.6.3.)<br>
   4.7. [Software Object-Oriented Design](#4.7.)<br>
      4.7.1. [Class Diagrams](#4.7.1.)<br>
      4.7.2. [Class Dictionary](#4.7.2.)<br>
   4.8. [Database Design](#4.8.)<br>
      4.8.1. [Database Diagram](#4.8.1.)<br>
5. [Capítulo V: Product Implementation, Validation & Deployment](#cap5)<br>
   5.1. [Software Configuration Management](#5.1.)<br>
      5.1.1. [Software Development Environment Configuration](#5.1.1.)<br>
      5.1.2. [Source Code Management](#5.1.2.)<br>
      5.1.3. [Source Code Style Guide & Conventions](#5.1.3.)<br>
      5.1.4. [Software Deployment Configuration](#5.1.4.)<br>
   5.2. [Landing Page, Services & Applications Implementation](#5.2.)<br>
      5.2.1. [Sprint 1](#5.2.1.)<br>
         5.2.1.1. [Sprint Planning 1](#5.2.1.1.)<br>
         5.2.1.2. [Sprint Backlog 1](#5.2.1.2.)<br>
         5.2.1.3. [Development Evidence for Sprint Review](#5.2.1.3.)<br>
         5.2.1.4. [Testing Suite Evidence for Sprint Review](#5.2.1.4.)<br>
         5.2.1.5. [Execution Evidence for Sprint Review](#5.2.1.5.)<br>
         5.2.1.6. [Services Documentation Evidence for Sprint Review.](#5.2.1.6.)<br>
         5.2.1.7. [Software Deployment Evidence for Sprint Review.](#5.2.1.7.)<br>
         5.2.1.8. [Team Collaboration Insights during Sprint.](#5.2.1.8.)<br>
      5.2.2. [Sprint 2](#5.2.2.)<br>
         5.2.2.1. [Sprint Planning 2](#5.2.2.1.)<br>
         5.2.2.2. [Sprint Backlog 2](#5.2.2.2.)<br>
         5.2.2.3. [Development Evidence for Sprint Review](#5.2.2.3.)<br>
         5.2.2.4. [Testing Suite Evidence for Sprint Review](#5.2.2.4.)<br>
         5.2.2.5. [Execution Evidence for Sprint Review](#5.2.2.5.)<br>
         5.2.2.6. [Services Documentation Evidence for Sprint Review.](#5.2.2.6.)<br>
         5.2.2.7. [Software Deployment Evidence for Sprint Review.](#5.2.2.7.)<br>
         5.2.2.8. [Team Collaboration Insights during Sprint.](#5.2.2.8.)<br>
      5.2.3. [Sprint 3](#5.2.3.)<br>
         5.2.3.1. [Sprint Planning 3](#5.2.3.1.)<br>
         5.2.3.2. [Sprint Backlog 3](#5.2.3.2.)<br>
         5.2.3.3. [Development Evidence for Sprint Review](#5.2.3.3.)<br>
         5.2.3.4. [Testing Suite Evidence for Sprint Review](#5.2.3.4.)<br>
         5.2.3.5. [Execution Evidence for Sprint Review](#5.2.3.5.)<br>
         5.2.3.6. [Services Documentation Evidence for Sprint Review.](#5.2.3.6.)<br>
         5.2.3.7. [Software Deployment Evidence for Sprint Review.](#5.2.3.7.)<br>
         5.2.3.8. [Team Collaboration Insights during Sprint.](#5.2.3.8.)<br>
      5.2.4. [Sprint 4](#5.2.4.)<br>
         5.2.4.1. [Sprint Planning 4](#5.2.4.1.)<br>
         5.2.4.2. [Sprint Backlog 4](#5.2.4.2.)<br>
         5.2.4.3. [Development Evidence for Sprint Review](#5.2.4.3.)<br>
         5.2.4.4. [Testing Suite Evidence for Sprint Review](#5.2.4.4.)<br>
         5.2.4.5. [Execution Evidence for Sprint Review](#5.2.4.5.)<br>
         5.2.4.6. [Services Documentation Evidence for Sprint Review.](#5.2.4.6.)<br>
         5.2.4.7. [Software Deployment Evidence for Sprint Review.](#5.2.4.7.)<br>
         5.2.4.8. [Team Collaboration Insights during Sprint.](#5.2.4.8.)<br>
      5.3. [Validation Interviews](#5.3.)<br>
         5.3.1. [Diseño de Entrevistas](#5.3.1.)<br>
         5.3.2. [Registro de Entrevistas](#5.3.2.)<br>
         5.3.3. [Evaluaciones según Heurísticas](#5.3.3.)<br>
   5.4. [Video About-the-Product](#5.4.)<br>
6. [Conclusiones](#conclusiones)<br>
7. [Bibliografía](#bibliografía)<br>
8. [Anexos](#anexos)

# Capítulo I: Introducción <a name ="cap1">

## 1.1. Startup Profile <a name ="1.1.">

### 1.1.1. Descripcion de la Startup <a name ="1.1.1.">

### 1.1.2. Perfiles de los integrantes del equipo <a name ="1.1.2.">

## 1.2. Solution Profile <a name ="1.2.">

### 1.2.1. Antecedentes y problemáticas <a name ="1.2.1.">

### 1.2.2. Lean UX Process <a name ="1.2.2.">
#### 1.2.2.1. Lean UX Problem Statments <a name ="1.2.2.1.">

#### 1.2.2.2. Lean UX Assumptions <a name ="1.2.2.2.">

#### 1.2.2.3. Lean UX Hypothesis Statements <a name ="1.2.2.3.">

#### 1.2.2.4. Lean UX Canvas <a name ="1.2.2.4.">

## 1.3. Segmentos objetivo <a name ="1.3.">

# Capítulo II: Requeriments Elicitation & Analysis <a name ="cap2">

## 2.1. Competidores <a name ="2.1.">

### 2.1.1. Analisis Competitivo <a name ="2.1.1.">

### 2.1.2. Estrategias y tácticas frente a competidores <a name ="2.1.2.">

## 2.2. Entrevistas <a name ="2.2.">
### 2.2.1. Diseño de Entrevistas <a name ="2.2.1.">

### 2.2.2. Registro de entrevistas <a name ="2.2.2.">

### 2.2.3. Ánalisis de entrevistas <a name ="2.2.3.">

## 2.3. Needfinding <a name ="2.3.">
### 2.3.1. User Personas <a name ="2.3.1.">

### 2.3.2. User Task Matrix <a name ="2.3.2.">

### 2.3.3. User Jorney Mapping <a name ="2.3.3.">

### 2.3.4. Empathy Mapping <a name ="2.3.4.">

### 2.3.5. As-is Scenario Mapping <a name ="2.3.5.">

## 2.4. Ubiquitous Language <a name ="2.4.">


