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
            <td style="text-align:center;">U202112164</td>
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
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería. |**Abraham Andres Estrada Cajamune**<br>**TB1:** Dirigió la comunicación con los usuarios finales durante la etapa de investigación, realizando el registro y moderación de las entrevistas para extraer necesidades críticas de los segmentos objetivo. Asimismo, sustentó oralmente ante el equipo y el docente las decisiones técnicas del Capítulo IV, traduciendo requerimientos de negocio en restricciones arquitectónicas viables. | **TB1:** Como equipo, concluimos que la facultad de adaptar el discurso según la audiencia es una competencia crítica para el éxito del proyecto. La interacción directa con usuarios no técnicos en el **Capítulo II** nos permitió validar la problemática de Oryxen desde una perspectiva humana y empática. Por otro lado, la defensa de los perfiles de la startup (**Capítulo I**) y de la arquitectura estratégica (**Capítulo IV**) ante el docente, demostró nuestra capacidad de emplear un lenguaje técnico-formal para sustentar la viabilidad de una solución de ingeniería ante niveles jerárquicos de evaluación.
| Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería. | **Abraham Andres Estrada Cajamune**<br>**TB1:** Documentó de manera detallada el registro de las entrevistas en el Capítulo II, sintetizando los hallazgos cualitativos. Además, fue responsable de la especificación de 10 Technical Stories para los Constraints en el Capítulo IV, utilizando la sintaxis Gherkin (Given-When-Then) para comunicar de forma objetiva las reglas técnicas a desarrolladores y stakeholders. | **TB1:** El equipo concluye que la documentación formal y estructurada es el pilar de la transparencia en ingeniería de software. A través de la redacción del Lean UX Canvas (**Capítulo I**), los artefactos de Needfinding (**Capítulo II**) y el Software Design de nivel estratégico (**Capítulo IV**), logramos sintetizar información compleja en documentos claros y trazables. El uso de estándares como **Gherkin** y el modelo **C4** en el diseño de software asegura que la comunicación escrita sea objetiva, permitiendo que tanto stakeholders de negocio como desarrolladores técnicos comprendan el ecosistema de Oryxen sin ambigüedades. |

<br>


# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Nuestra startup **"GrassFarming"** se enfoca en simplificar el cuidado de plantas mediante una solución inteligente que combina automatización, inteligencia artificial visual y seguimiento centralizado. Con nuestra plataforma **"Oryxen"**, buscamos ayudar a personas amantes de la jardinería y personas con agendas ocupadas, quienes suelen enfrentar dificultades para mantener sus plantas saludables debido al olvido, la falta de tiempo o el desconocimiento sobre las necesidades específicas de cada especie.

La propuesta de valor de Oryxen se basa en tres pilares diferenciales:

- **Automatización inteligente:** El sistema automatiza tareas esenciales como el monitoreo constante y el riego de las plantas mediante sensores IoT y módulos de riego automático, reduciendo la dependencia de recordatorios manuales.
- **IA visual y asistencia personalizada:** Oryxen incorpora inteligencia artificial capaz de analizar imágenes y datos de las plantas para detectar posibles problemas, interpretar su estado y brindar recomendaciones personalizadas mediante un chatbot inteligente.
- **Seguimiento centralizado:** Los usuarios pueden visualizar en una sola plataforma el estado de todas sus plantas en tiempo real, recibiendo alertas, recomendaciones y métricas de cuidado desde cualquier dispositivo.

A diferencia de soluciones tradicionales que solo recuerdan tareas o funcionan dentro de ecosistemas cerrados, Oryxen transforma las plantas y macetas que el usuario ya posee en un sistema inteligente, accesible y escalable.

Con ello, se busca reducir la pérdida de plantas, disminuir la carga del cuidado manual, optimizar el tiempo de los usuarios y mejorar la experiencia general del cuidado de plantas.

**Misión:** Facilitar el cuidado de plantas mediante automatización, inteligencia artificial visual y monitoreo inteligente, ofreciendo una experiencia accesible, práctica y confiable.

**Visión:** Convertirnos en la solución líder de cuidado inteligente de plantas en Latinoamérica, integrando automatización e inteligencia artificial para promover hogares más saludables y conectados con la naturaleza.

**Logotipo de la Startup:**

![Logo_GrassFarming](/assets/Chapter-1/Logo_GrassFarming.png)

**Logotipo de la Solución:**

![Logo_Oryxen](/assets/Chapter-1/Logo_Oryxen.png)

### 1.1.2. Perfiles de integrantes del equipo

| Integrante | Descripción | Conocimientos |
| ---------- | ----------- | ------------- |
| **Alejandro Alberto Pachas Chávez - u201917598** <img src="./assets/Chapter-1/perfil_alejandro.png"> | Mi nombre es Alejandro Alberto Pachas Chávez, tengo 24 años y actualmente curso la carrera de Ingeniería de Software. Me describo como una persona creativa, responsable y constante, con una fuerte disposición para colaborar en equipo. Mi objetivo es contribuir positivamente al grupo y alcanzar las metas propuestas. | Cuento con experiencia en lenguajes de programación como JavaScript, TypeScript y Go; además de desarrollo web utilizando frameworks como React y Next.js, y manejo de bases de datos tanto relacionales como no relacionales, incluyendo PostgreSQL y Firebase. |
| **Pedro Jesús Nanfuñay Liza - u202215462** <img src="./assets/Chapter-1/Perfil_PedroNanfuñay.jpeg"> | Mi nombre es Pedro Jesús Nanfuñay Liza, tengo 20 años y soy estudiante de la carrera de Ingeniería de Software. Me considero una persona creativa, responsable, perseverante y siempre dispuesto a trabajar en equipo. Espero aportar de manera positiva al equipo y cumplir con los objetivos establecidos. | Tengo conocimientos en lenguajes de programación como C++, Java y Python; en el desarrollo web con frameworks Angular y Primevue, y en base de datos relacionales y no relacionales como SQL y MongoDB. |
| **Zevallos Linares, Alessandro Netto - u202216035** <img src="https://github.com/user-attachments/assets/6e621406-9662-4f9f-964c-249eb7cb17a1"> | Mi nombre es Alessandro Netto Zevallos Linares, tengo 22 años y soy estudiante de Ingeniería de Software con un fuerte interés en el desarrollo de productos digitales y la tecnología. En mi tiempo libre, me gusta jugar videojuegos. También tengo un interés especial en la música, lo que me ayuda a equilibrar mi vida académica y personal. | Tengo conocimientos en JavaScript, React, Next.js, Angular, Vue, Java, Flutter, Kotlin, y en base de datos como SQL y MongoDB. |
| **Abraham Andres Estrada Cajamune - U202112164** <img src="./assets/Chapter-1/Abraham.jpg"> | Mi nombre es Abraham Andres Estrada Cajamune, tengo 22 años y soy estudiante de la carrera de Ingeniería de Software, cursando el 9no ciclo. Me califico como una persona responsable, trabajando a presión y con buena disposición en trabajar en equipo. Mi interés está en el desarrollo web y movil. | A lo largo de mis estudios universitarios he adquirido las bases sólidas en lenguajes de programación como Java, C++, Python, utilizando Frameworks como Angular y Vue y un fuerte conocimiento en el manejo de bases de datos. |

## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

| LAS 5W y 2H | Pregunta | Descripción |
| ----------- | -------- | ----------- |
| What? | ¿Cuál es el problema? | Personas ocupadas y aficionados a la jardinería no logran mantener un nivel de salud óptima en sus plantas (humedad, luz solar, estado visual, etc.) por falta de tiempo, olvidos o desconocimiento, lo que provoca plantas marchitas o muertas, frustración y menor bienestar. |
| When? | ¿Cuándo sucede el problema? | Ocurre de forma recurrente, especialmente durante semanas de alta carga laboral, viajes y en épocas de clima cambiante. |
| Where? | ¿Dónde sucede el problema? | Principalmente en hogares, departamentos, oficinas, entre otros espacios, donde existe variedad de plantas y el control manual resulta complicado. |
| Why? | ¿Por qué sucede el problema? | Por la combinación de múltiples factores como la falta de tiempo, ausencia de monitoreo constante, desconocimiento de necesidades específicas de cada especie y falta de herramientas inteligentes que automaticen el cuidado. |
| Who? | ¿Qué llevará a las personas a usar nuestro producto? | Personas que desean mantener un cuidado óptimo de sus plantas con menos esfuerzo, automatizando tareas y centralizando el monitoreo para reducir el tiempo invertido y evitar pérdidas. |
| How? | ¿En qué condiciones los clientes usarán nuestro producto? | Los clientes usarán sensores, módulos de riego y la aplicación en entornos con acceso a internet para monitorear en tiempo real el estado de sus plantas, automatizar procesos y recibir recomendaciones inteligentes mediante IA visual. |
| How Much? | ¿Con qué frecuencia o en qué cantidad se utilizará nuestro producto? | La plataforma será utilizada de manera continua para monitoreo y automatización. Los usuarios podrán revisar el estado de sus plantas diariamente o semanalmente según sus necesidades y recibir alertas automáticas cuando el sistema detecte anomalías. |

### 1.2.2 Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

Oryxen fue diseñado para ayudar a los usuarios a mantener sus plantas saludables mediante la integración de automatización inteligente, inteligencia artificial visual y seguimiento centralizado. La solución utiliza sensores IoT, módulos de riego automático y análisis visual asistido por IA para monitorear continuamente el estado de las plantas y reducir la carga del cuidado manual.

Hemos observado que los usuarios, especialmente personas con agendas ocupadas y aficionados a la jardinería, no logran mantener un cuidado constante, lo que provoca la pérdida de plantas, frustración y una menor continuidad en la creación de áreas verdes.

Además, las soluciones existentes suelen enfocarse únicamente en recordatorios manuales o en ecosistemas cerrados de hardware, sin ofrecer una experiencia integral que combine automatización, diagnóstico inteligente y monitoreo unificado.

¿Cómo podríamos mejorar Oryxen para que nuestros clientes tengan más éxito según su disponibilidad de tiempo y conocimientos previos en el cuidado de plantas, utilizando automatización, IA visual y seguimiento centralizado para reducir la carga de cuidado manual y aumentar la supervivencia de las plantas?

#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions:**

1. Creo que mis clientes necesitan mantener sus plantas saludables sin depender constantemente de supervisión manual.
2. Estas necesidades pueden ser solucionadas mediante una plataforma que combine automatización, IA visual y monitoreo centralizado.
3. Mis primeros clientes serán personas con agendas ocupadas y aficionados a la jardinería.
4. El valor número 1 que un cliente quiere obtener de mi servicio es tranquilidad al saber que sus plantas están siendo monitoreadas y cuidadas automáticamente.
5. El cliente también puede obtener beneficios adicionales como ahorro de tiempo, recomendaciones inteligentes y reducción de pérdida de plantas.
6. Obtendré la mayoría de mis clientes a través de redes sociales, recomendaciones y marketplaces de hogar inteligente.
7. Ganaré dinero a través de planes premium, venta de sensores y módulos inteligentes.
8. Mi principal competencia en el mercado serán aplicaciones de cuidado de plantas y sistemas de automatización básica.
9. Los venceremos al integrar automatización, IA visual y seguimiento centralizado en una sola solución accesible y adaptable.
10. Mi mayor riesgo de producto es que los usuarios no perciban suficiente valor diferencial frente a soluciones más simples.
11. Resolveremos esto demostrando resultados reales mediante monitoreo inteligente y automatización efectiva.
12. Otra posible suposición falsa es que algunos usuarios no estén dispuestos a adoptar hardware inteligente en sus hogares.

**User Assumptions:**

1. ¿Quién es el usuario? Personas ocupadas y amantes de la jardinería que desean gestionar la salud de sus plantas de forma eficiente.
2. ¿Dónde encaja nuestro producto en su vida? En el cuidado diario de plantas dentro del hogar, oficinas y espacios personales.
3. ¿Qué problemas tiene nuestro producto y cómo los resolvemos? Problema: cuidado manual complejo y pérdida frecuente de plantas. Solución: automatización inteligente, IA visual y acceso centralizado a la información.
4. ¿Cuándo y cómo es usado nuestro producto? Durante el cuidado cotidiano de plantas, monitoreando su estado desde cualquier dispositivo.
5. ¿Qué características son importantes? Automatización confiable, visualización centralizada, análisis inteligente y facilidad de uso.
6. ¿Cómo debe verse y comportarse nuestro producto? Diseño limpio, intuitivo, rápido y accesible desde múltiples dispositivos.

**Priorización de suposiciones:**

Siguiendo la metodología Lean UX de Jeff Gothelf, priorizamos nuestras suposiciones con base en dos criterios principales: nivel de riesgo y nivel de conocimiento. El objetivo es identificar aquellas suposiciones de alto riesgo y bajo conocimiento para validarlas primero a través de experimentos y pruebas con usuarios.

**Suposiciones de Alta Prioridad (Alto Riesgo + Bajo Conocimiento):**

1. Los usuarios adoptarán una solución de automatización inteligente si perciben una reducción real del trabajo manual.
2. Los usuarios confiarán en recomendaciones generadas mediante IA visual para el cuidado de sus plantas.
3. Los usuarios valorarán una plataforma centralizada que les permita monitorear todas sus plantas desde un solo lugar.
4. La combinación de automatización, IA visual y monitoreo centralizado será percibida como una propuesta diferencial y útil.

**Suposiciones de prioridad media (Riesgo medio + conocimiento medio):**

5. Los usuarios estarán dispuestos a recibir alertas y recomendaciones frecuentes.
6. La solución será útil tanto para usuarios principiantes como avanzados.
7. Los usuarios confiarán en las recomendaciones generadas por el chatbot inteligente.
8. La automatización reducirá significativamente la pérdida de plantas.

**Suposiciones de baja prioridad (Bajo riesgo + alto conocimiento):**

9. Los usuarios prefieren interfaces simples e intuitivas.
10. La centralización de información mejora la experiencia de uso.
11. Los usuarios valoran recomendaciones personalizadas.
12. Los dispositivos móviles y el acceso a internet son accesibles para la mayoría de usuarios.

Estas suposiciones de alta prioridad serán las primeras en validarse mediante entrevistas, pruebas de concepto y prototipos antes de proceder con el desarrollo completo de Oryxen.

#### 1.2.2.3. Lean UX Hypothesis Statements

- **Hypothesis Statement 01:**  
Creemos que los usuarios con agendas ocupadas buscarán automatizar el cuidado de sus plantas para reducir tiempo y esfuerzo manual.  
Sabremos que esto es cierto al medir la frecuencia con la que utilizan las funciones automáticas de monitoreo y riego.  
Cuando al menos el 60% de los usuarios activos mantenga activadas las funciones automáticas durante el primer mes.

- **Hypothesis Statement 02:**  
Creemos que la integración de IA visual permitirá detectar problemas de salud en las plantas de manera más eficiente que el cuidado manual tradicional.  
Sabremos que esto es cierto al analizar la percepción de utilidad y precisión de las recomendaciones generadas por la IA.  
Cuando más del 70% de los usuarios califique las recomendaciones visuales como útiles y precisas.

- **Hypothesis Statement 03:**  
Creemos que los usuarios valorarán una plataforma centralizada donde puedan visualizar el estado de todas sus plantas en tiempo real.  
Sabremos que esto es cierto al analizar el uso de la pantalla principal de monitoreo.  
Cuando al menos el 75% de los usuarios utilice frecuentemente el panel centralizado de seguimiento.

- **Hypothesis Statement 04:**  
Creemos que la combinación de automatización, IA visual y seguimiento centralizado aumentará la confianza y satisfacción del usuario.  
Sabremos que esto es cierto mediante encuestas de satisfacción y retención de usuarios.  
Cuando más del 80% de los usuarios considere que Oryxen facilita significativamente el cuidado de sus plantas.

#### 1.2.2.4. Lean UX Canvas

![LeanUXCanvas-Oryxen](./assets/Chapter-1/LeanUXCanvas-Oryxen.png)

## 1.3. Segmentos Objetivo

Para asegurar el éxito de Oryxen, hemos identificado dos segmentos clave que serán el foco principal de nuestras estrategias de desarrollo y marketing. Estos segmentos representan a nuestros usuarios ideales y nos permitirán adaptar nuestras funcionalidades y servicios a sus necesidades específicas, maximizando así el impacto de la plataforma.

- **Segmento Objetivo 1 – Personas ocupadas:** Edades comprendidas entre 25 y 45 años que viven en zonas urbanas y llevan un ritmo de vida acelerado. Suelen tener entre 1 y 5 plantas en casa o en su lugar de trabajo, que utilizan para embellecer sus entornos, reducir el estrés y fomentar su bienestar. Les gusta tener plantas, pero no siempre tienen el tiempo o la constancia para cuidarlas bien, lo que muchas veces termina en frustración cuando se deterioran o mueren. Buscan una solución práctica que funcione casi sola y les dé tranquilidad.

- **Segmento Objetivo 2 – Aficionados a la jardinería:** Personas de múltiples rangos de edad que disfrutan del cuidado de sus plantas y suelen tener entre 5 y 20 de distintas especies. Les interesa que sus plantas estén en las mejores condiciones posibles, por lo que valoran entender aspectos como el riego, la humedad o el tipo de suelo. Buscan un mayor control y seguimiento para optimizar el cuidado de sus plantas.

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
