<div align="center">    
    <img src="./assets/logo-upc.png" alt="Logo UPC" width="200" height="200"></img><br><strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <br><p>Ingeniería de Software</p>
    <p>8vo Ciclo</p>
    <br><strong>Arquitecturas de Software Emergentes</strong><br>
    <br><p>Sección: 11770</p>
    <p>Profesor: Christian Luis De Los Rios Fernandez</p><br>
</div>

<p align="center">
    <strong>"Informe del Trabajo Final"</strong><br>
    <br><strong>Startup: GrassFarming</strong><br>
    <br><strong>Producto: Oryxen</strong><br><br>
</p>

<div>
    <h3 align="center">Integrantes:</h3>
</div>

<div>
    <table align="center">
        <tr>
            <th style="text-align:center;">Apellidos y Nombres</th>
            <th style="text-align:center;">Código</th>
        </tr>
        <tr>
            <td style="text-align:center;">Estrada Cajamune, Abraham Andrés</td>
            <td style="text-align:center;">U</td>
        </tr>
        <tr>
            <td style="text-align:center;">Nanfuñay Liza, Pedro Jesús</td>
            <td style="text-align:center;">U202215462</td>
        </tr>
        <tr>
            <td style="text-align:center;">Pachas Chavez, Alejandro Alberto</td>
            <td style="text-align:center;">U</td>
        </tr>
        <tr>
            <td style="text-align:center;">Zevallos Linares, Alessandro Netto</td>
            <td style="text-align:center;">U</td>
        </tr>
    </table>
    </div>
</body>

<br>
<br><p align="center">Abril, 2026</p></p>
<br><br>


# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de Modificación |
| ----------- | ----------- | ----------- | ----------- |
| TB1 | 15/04/2026 |  |  |

# Project Report Collaboration Insights

URL de la organización del proyecto:



**TB1**


# Contenido

## Tabla de contenidos

[Registro de Versiones del Informe](#registro-de-versiones-del-informe)

[Project Report Collaboration Insights](#project-report-collaboration-insights)

[Student Outcome](#student-outcome)

### [Capítulo I: Introducción](#capítulo-i-introducción)

- [1.1 Startup Profile](#11-startup-profile)  
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)  
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)  
- [1.2. Solution Profile](#12-solution-profile)  
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)  
    - [1.2.2 Lean UX Process](#122-lean-ux-process)  
        - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)  
        - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)  
        - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)  
        - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)  
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

### [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)

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
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [2.4. Ubiquitous Language](#25-ubiquitous-language)  

### [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)  

- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)  
- [3.2. User Stories](#32-user-stories)  
- [3.3. Product Backlog](#33-product-backlog)  
- [3.4. Impact Mapping](#34-impact-mapping)

### [Capítulo IV: Strategic-Level Software Design](#capítulo-iv-strategic-level-software-design)

- [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)  
    - [4.1.1. Design Purpose.](#411-design-purpose)  
    - [4.1.2. Attribute-Driven Design Inputs](#412-attribute-driven-design-inputs)  
        - [4.1.2.1. Primary Functionality (Primary User Stories)](#4121-primary-functionality-primary-user-stories)  
        - [4.1.2.2. Quality attribute Scenarios](#4122-quality-attribute-scenarios)  
        - [4.1.2.3. Constraints](#4123-constraints)  
        - [4.1.3. Architectural Drivers Backlog](#413-architectural-drivers-backlog)  
        - [4.1.4. Architectural Design Decisions](#414-architectural-design-decisions)  
        - [4.1.5. Quality Attribute Scenario Refinements](#415-quality-attribute-scenario-refinements)  
- [4.2. Strategic-Level Domain-Driven Design](#42-strategic-level-domain-driven-design)  
    - [4.2.1. EventStorming](#421-eventstorming)  
    - [4.2.2. Candidate Context Discovery](#422-candidate-context-discovery)  
    - [4.2.3. Domain Message Flows Modeling](#423-domain-message-flows-modeling)  
    - [4.2.4. Bounded Context Canvases](#424-bounded-context-canvases)  
    - [4.2.5. Context Mapping](#425-context-mapping)  
- [4.3. Software Architecture](#43-software-architecture)  
    - [4.3.1. Software Architecture System Landscape Diagram](#431-software-architecture-system-landscape-diagram)  
    - [4.3.2. Software Architecture Context Level Diagrams](#432-software-architecture-context-level-diagrams)  
    - [4.3.3. Software Architecture Container Level Diagrams](#433-software-architecture-container-level-diagrams)  
    - [4.3.4. Software Architecture Deployment Diagrams](#434-software-architecture-deployment-diagrams)

#### [Conclusiones](#conclusiones)  
- [Conclusiones y recomendaciones.](#conclusiones-y-recomendaciones)  

#### [Bibliografía](#bibliografía)  

#### [Anexos](#anexos)
<br>


# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:
**ABET – EAC - Student Outcome 3**

**Criterio:** Capacidad de comunicarse efectivamente con un rango de audiencias.
En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 3.

| Criterio específico | Acciones Realizadas | Conclusiones |
| ------------------- | ------------------- | ------------ |
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería. | |
| Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería. | |

<br>


# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Nuestra startup **"GrassFarming"** se enfoca en simplificar el cuidado de plantas mediante una solución inteligente que automatiza tareas esenciales y brinda asistencia continua al usuario. Con nuestra plataforma **"Oryxen"**, nos centramos en ayudar a personas amantes de la jardinería con agendas ocupadas y a adultos mayores, quienes suelen enfrentar dificultades para mantener sus plantas saludables debido al olvido o la falta de tiempo. La solución integra funciones de riego automático, monitoreo con sensores y un chatbot inteligente que brinda recomendaciones personalizadas. A través de la interfaz, los usuarios podrán visualizar fácilmente el estado de todas sus plantas, recibir alertas y gestionar su cuidado de manera práctica y confiable. Con ello, se busca reducir la pérdida de plantas, mejorar la experiencia del usuario y aumentar su satisfacción.

**Misión:** Facilitar el cuidado de plantas mediante automatización e inteligencia artificial, ofreciendo una experiencia más accesible, práctica y confiable.

**Visión:** Convertirnos en una solución líder en el cuidado inteligente de plantas, promoviendo hogares más saludables y conectados con la naturaleza.

**Logotipo de la Startup:**



**Logotipo de la Solución:**


### 1.1.2. Perfiles de integrantes del equipo

| Integrante | Descripción | Conocimientos |
| ---------- | ----------- | ------------- |
| **Pedro Jesús Nanfuñay Liza - u202215462** <img src="./assets/Chapter-1/Perfil_PedroNanfuñay.jpeg"> | Mi nombre es Pedro Jesús Nanfuñay Liza, tengo 20 años y soy estudiante de la carrera de Ingeniería de Software. Me considero una persona creativa, responsable, perseverante y siempre dispuesto a trabajar en equipo. Espero aportar de manera positiva al equipo y cumplir con los objetivos establecidos. | Tengo conocimientos en lenguajes de programación como C++, Java y Python; en el desarrollo web con frameworks Angular y Primevue, y en base de datos relacionales y no relacionales como SQL y MongoDB. |

## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

### 1.2.2 Lean UX Process.

#### 1.2.2.1. Lean UX Problem Statements

#### 1.2.2.2. Lean UX Assumptions

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.4. Lean UX Canvas


## 1.3. Segmentos Objetivo


# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

### 2.1.2. Análisis competitivo


## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

### 2.2.2. Registro de entrevistas

### 2.2.3. Análisis de entrevistas.


## 2.3.	Needfinding

### 2.3.1. User Persons

### 2.3.2. User Task Matrix

### 2.3.3. Empathy Mapping

### 2.3.4. As-is Scenario Mapping.

## 2.4. Ubiquitous Language


# Capítulo III: Requirements Specification

## 3.1. To-be Scenario Mapping

## 3.2 User Stories

## 3.3 Impact Mapping

## 3.4. Product Backlog


# Capítulo IV: Strategic-Level Software Design

## 4.1.	Strategic-Level Attribute-Driven Design

### 4.1.1. Design Purpose

### 4.1.2. Attribute-Driven Design Inputs

#### 4.1.2.1. Primary Functionality (Primary User Stories)

#### 4.1.2.2. Quality attribute Scenarios

#### 4.1.2.3. Constraints


## 4.2.	Strategic-Level Domain-Driven Design

### 4.2.1. EventStorming

### 4.2.2. Candidate Context Discovery

### 4.2.3.	Domain Message Flows Modeling

### 4.2.4.	Bounded Context Canvases

### 4.2.5.	Context Mapping


## 4.3.	Software Architecture

### 4.3.1.	Software Architecture System Landscape Diagram

### 4.3.2.	Software Architecture Context Level Diagrams

### 4.3.3.	Software Architecture Container Level Diagrams

### 4.3.4.	Software Architecture Deployment Diagrams


# Conclusiones

## Conclusiones y recomendaciones


# Bibliografía


# Anexos