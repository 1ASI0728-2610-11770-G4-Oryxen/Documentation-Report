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
            <td style="text-align:center;">U201917598</td>
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
- [2.4. Big Picture EventStorming](#24-big-picture-eventstorming)  
- [2.5. Ubiquitous Language](#25-ubiquitous-language)  

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
| **Alejandro Alberto Pachas Chávez - u201917598** <img src="./assets/Chapter-1/perfil_alejandro.png"> | Mi nombre es Alejandro Alberto Pachas Chávez, tengo 24 años y actualmente curso la carrera de Ingeniería de Software. Me describo como una persona creativa, responsable y constante, con una fuerte disposición para colaborar en equipo. Mi objetivo es contribuir positivamente al grupo y alcanzar las metas propuestas. | Cuento con experiencia en lenguajes de programación como JavaScript, TypeScript y Go; además de desarrollo web utilizando frameworks como React y Next.js, y manejo de bases de datos tanto relacionales como no relacionales, incluyendo PostgreSQL y Firebase.  |
| **Pedro Jesús Nanfuñay Liza - u202215462** <img src="./assets/Chapter-1/Perfil_PedroNanfuñay.jpeg"> | Mi nombre es Pedro Jesús Nanfuñay Liza, tengo 20 años y soy estudiante de la carrera de Ingeniería de Software. Me considero una persona creativa, responsable, perseverante y siempre dispuesto a trabajar en equipo. Espero aportar de manera positiva al equipo y cumplir con los objetivos establecidos. | Tengo conocimientos en lenguajes de programación como C++, Java y Python; en el desarrollo web con frameworks Angular y Primevue, y en base de datos relacionales y no relacionales como SQL y MongoDB. |


## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

| LAS 5W y 2H | Pregunta | Descripción |
| ----------- | -------- | ----------- |
| What? | ¿Cuál es el problema? | Personas ocupadas, aficionados a la jardinería y adultos mayores no logran mantener un nivel de salud óptima en sus plantas (humedad, luz solar, etc.) por falta de tiempo u olvidos, lo que provoca plantas marchitas o muertas, frustración y menor bienestar. |
| When? | ¿Cuándo sucede el problema? | Ocurre de forma recurrente, especialmente durante semanas de alta carga laboral, viajes y en épocas de clima cambiante.                                                       |
| Where?  | ¿Dónde sucede el problema? | Principalmente en hogares, departamentos, oficinas, entre otros espacios, donde hay variedad de plantas y el control manual resulte complicado. |
| Why? | ¿Por qué sucede el problema? | Por la combinación de múltiples factores como la falta de tiempo, ausencia de recordatorios útiles y desconocimiento de necesidades específicas de riego y cuidado de cada especie. |
| Who? | ¿Qué llevara a las personas a usar nuestro producto? | Personas que desean mantener un cuidado óptimo de sus plantas con menos esfuerzo y que les permita cumplir con sus otras responsabilidades, con el objetivo de facilitar el proceso de cuidado y disminuir el tiempo necesario. |
| How? | ¿En qué condiciones los clientes usaran nuestro producto? | Los clientes usarán la aplicación y sensores en entornos con acceso a internet, para monitorear el estado de sus plantas, recibir alertas y automatizar el riego. |
| How Much? | ¿Con qué frecuencia o en qué cantidad se utilizará nuestro producto? | La frecuencia de uso será diario o semanal según la especie de la planta y estación del año. Las notificaciones pueden activarse varias veces al mes por maceta, y el sistema puede comenzar con pocas plantas y escalar según las necesidades del usuario. |

### 1.2.2 Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

Oryxen fue diseñado para ayudar a los usuarios a mantener sus plantas saludables mediante sensores que registran parámetros como la humedad, oxígeno, etc; para automatizar procesos de cuidado y brindar asistencia inteligente, reduciendo la carga del cuidado manual. 

Hemos observado que los usuarios, especialmente personas con agendas ocupadas y adultos mayores, no logran mantener un cuidado constante, lo que provoca la pérdida de plantas, frustración y una menor continuidad en la creación de áreas verdes.

¿Cómo podríamos mejorar Oryxen para que nuestros clientes tengan más éxito según su disponibilidad de tiempo y conocimientos previos en el cuidado de plantas, incrementando el interés de las personas por cultivar más plantas y reduciendo la carga de cuidado manual?

#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions:**

1. Creo que mis clientes necesitan mantener sus plantas saludables sin depender de recordatorios manuales o tiempo constante.
2. Estas necesidades puede ser solucionadas con un sistema inteligente que automatice los cuidados y monitoree las plantas mediante sensores e IA.
3. Mis primeros clientes son (o serán) personas con agendas ocupadas, adultos mayores y aficionados a la jardinería.
4. El valor número 1 que un cliente quiere obtener de mi servicio es mantener sus plantas vivas sin esfuerzo y ver su estado mediante un panel de control.
5. El cliente también puede obtener estos beneficios adicionales: Automatizar procesos de cuidado, ahorrar tiempo, obtener bienestar y aprender sobre el cuidado de plantas.
6. Obtendré la mayoría de mis clientes a través de redes sociales, recomendaciones (boca a boca) y marketplaces de tecnología/hogar inteligente.
7. Ganaré dinero a través de planes premium y paquetes con objetos que ayudarán al cliente a entender mejor el proceso de cuidado de plantas.
8. Mi principal competencia en el mercado serán aplicaciones de recordatorio de riego y sistemas básicos de riego automático.
9. Los venceremos por integrar automatización de cuidado con sensores y la implementación de un chatbot impulsado con IA en una sola solución simple y accesible.
10. Mi mayor riesgo de producto es que los usuarios no perciban suficiente valor frente a soluciones más simples o no adopten el hardware.
11. Resolveremos esto a través de una experiencia fácil de usar, funciones claras e intuitivas, soporte técnico constante y demostración de los resultados de la solución en casos reales.
12. Otras suposiciones que tenemos que podrían resultar falsas serían que los usuarios no estén dispuestos a pagar por los planes premium de la solución y o que confíen demasiado en la automatización para el cuidado de sus plantas.

**User Assumptions:**

1. ¿Quién es el usuario? Personas ocupadas, amantes de la jardinería y personas de la tercera edad que desean gestionar de manera efectiva la salud de sus plantas.
2. ¿Dónde encaja nuestro producto en su trabajo o vida? Se integra en el flujo de vida diaria de cada cliente, permitiendo revisar y analizar la información de sus plantas cuando lo deseen.
3. ¿Qué problemas tiene nuestro producto y cómo los resolvemos? Problema: Arduo cuidado manual y uso de tiempo para el cuidado de plantas. Solución: Plataforma unificada con automatización y acceso centralizado a toda la información.
4. ¿Cuándo y cómo es usado nuestro producto? Durante el hábito de cultivar plantas, donde los clientes buscan mantener saludables a sus plantas.
5. ¿Qué características son importantes? Interfaz intuitiva y responsive, sincronización en tiempo real e integración con sistemas existentes.
6. ¿Cómo debe verse y comportarse nuestro producto? Diseño limpio y profesional, navegación simple, tiempo de respuesta rápido y accesible desde múltiples dispositivos.

**Priorización de suposiciones:**

Siguiendo la metodología Lean UX de Jeff Gothelf, priorizamos nuestras suposiciones con base en dos criterios principales: nivel de riesgo y nivel de conocimiento. El objetivo es identificar aquellas suposiciones de alto riesgo y bajo conocimiento para validarlas primero a través de experimentos y pruebas con usuarios.

**Suposiciones de Alta Prioridad (Alto Riesgo + Bajo Conocimiento):**

1. Los usuarios realmente adoptarán una solución de cuidado automático si perciben que les ahorra tiempo y reduce el trabajo manual.
2. Los adultos mayores y personas con agendas ocupadas confiarán en un sistema automatizado para el cuidado de sus plantas.
3. Los usuarios valorarán una interfaz que muestre el estado de todas sus plantas de forma clara y centralizada.
4. La integración de sensores, riego automático y funciones con IA será percibida como útil y no como compleja.

**Suposiciones de prioridad media (Riesgo medio + conocimiento medio):**

5. Los usuarios estarán dispuestos a leer notificaciones y alertas frecuentes para monitorear sus plantas.
6. La solución será útil tanto para personas con pocas plantas como para quienes tienen varias.
7. Los usuarios confiarán en las recomendaciones del chatbot para tomar decisiones de cuidado.
8. La automatización del riego será suficiente para reducir significativamente la cantidad de plantas muertas.

**Suposiciones de baja prioridad (Bajo riesgo + alto conocimiento):**

9. Los usuarios prefieren interfaces simples, intuitivas y fáciles de entender.
10. La visualización del estado de las plantas en una sola plataforma mejora la experiencia de uso.
11. Los usuarios valoran recibir recordatorios y recomendaciones personalizadas.
12. Los dispositivos móviles y la conectividad a internet son accesibles para la mayoría de nuestros usuarios.

Estas suposiciones de alta prioridad serán las primeras en validarse mediante entrevistas, pruebas de concepto y prototipos, antes de proceder con el desarrollo completo de Oryxen.

#### 1.2.2.3. Lean UX Hypothesis Statements

- **Hypothesis Statement 01:** <br>
Creemos que los usuarios amantes de la jardinería con agendas ocupadas y los adultos mayores buscan una forma simple de mantener sus plantas saludables sin depender del riego manual.
Sabremos que esto es cierto al medir la frecuencia con la que usan la app para revisar el estado de sus plantas.
Cuando al menos el 60% de los usuarios activos consulte la plataforma 3 veces por semana o más durante el primer mes.

- **Hypothesis Statement 02:** <br>
Creemos que la automatización del riego reducirá significativamente la cantidad de plantas muertas en comparación con el cuidado manual.
Sabremos que esto es cierto al comparar el número de plantas marchitas o muertas antes y después de usar la solución.
Cuando los usuarios reporten una reducción de al menos 30% en plantas perdidas en los primeros 3 meses.

- **Hypothesis Statement 03:** <br>
Creemos que los usuarios valorarán una interfaz donde puedan ver el estado de todas sus plantas en un solo lugar.
Sabremos que esto es cierto al analizar las ocasiones y el tiempo en el que permanecen los usuarios dentro de la aplicación.
Cuando al menos el 70% de los usuarios activos utilice la pantalla de resumen de plantas y la califique como útil.

- **Hypothesis Statement 04:** <br>
Creemos que un chatbot con IA aumentará la confianza del usuario al brindar recomendaciones claras y oportunas sobre el cuidado de sus plantas.
Sabremos que esto es cierto al analizar el uso del chatbot y la satisfacción percibida por los usuarios.
Cuando al menos el 50% de los usuarios interactúe con el chatbot y más del 75% declare que sus recomendaciones fueron útiles.


#### 1.2.2.4. Lean UX Canvas

![LeanUXCanvas-Oryxen](./assets/Chapter-1/LeanUXCanvas-Oryxen.png)

## 1.3. Segmentos Objetivo

Para asegurar el éxito de Oryxen, hemos identificado dos segmentos clave que serán el foco principal de nuestras estrategias de desarrollo y marketing. Estos segmentos representan a nuestros usuarios ideales y nos permitirán adaptar nuestras funcionalidades y servicios a sus necesidades específicas, maximizando así el impacto de la plataforma.

- **Segmento Objetivo 1 – Personas ocupadas:** Edades comprendidas entre 25 y 45 años que viven en zonas urbanas y llevan un ritmo de vida acelerado. Suelen tener entre 1 y 5 plantas en casa o en su lugar de trabajo, que utilizan para embellecer sus entornos, reducir el estrés y fomentar su bienestar. Les gusta tener plantas, pero no siempre tienen el tiempo o la constancia para cuidarlas bien, lo que muchas veces termina en frustración cuando se deterioran o mueren. Buscan una solución práctica que funcione casi sola y les dé tranquilidad.

- **Segmento Objetivo 2 – Aficionados a la jardinería:** Personas de múltiples rangos de edad que disfrutan del cuidado de sus plantas y suelen tener entre 5 y 20 de distintas especies. Les interesa que sus plantas estén en las mejores condiciones posibles, por lo que valoran entender aspectos como el riego, la humedad o el tipo de suelo. Buscan un mayor control y seguimiento para optimizar el cuidado de sus plantas.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

En el mercado de soluciones digitales para el cuidado de plantas, se han identificado tres competidores representativos que cubren distintos frentes de valor: desde aplicaciones móviles con IA hasta electrodomésticos de jardinería inteligente. Cada uno aborda parcialmente el problema que **Oryxen** resuelve de forma integral, lo que permite posicionar con claridad las ventajas de nuestra propuesta.

**Planta (Strömming & Löf AB)**  
Aplicación móvil sueca con más de 10 millones de descargas que asiste a los usuarios en el cuidado de sus plantas mediante recordatorios, identificación por foto con IA, medidor de luz con la cámara del celular y una extensa base de datos de especies. Es un competidor directo en el plano **software** pero no integra hardware, por lo que depende de la memoria y disciplina del usuario para ejecutar cada tarea. Su plan premium se comercializa por suscripción anual a bajo costo.

**Click & Grow (Smart Garden 3 / 9 / 25)**  
Compañía estonia que ofrece jardines inteligentes de interior en formato de electrodoméstico: una maceta cerrada con riego automatizado, luces LED de crecimiento y cápsulas propietarias ("plant pods") con semillas preparadas. Es un competidor **hardware** de gama media-alta, pero orientado exclusivamente al cultivo de hierbas, vegetales y flores dentro de su propio ecosistema cerrado; no permite monitorear las plantas que el usuario ya tiene en casa.

**Gardyn (Home Kit 3.0 con Kelby AI)**  
Startup estadounidense que vende un huerto vertical hidropónico para el hogar, controlado por una IA propia llamada **Kelby** que utiliza cámaras integradas para detectar el estado de cada planta y recomendar acciones. Funciona con un modelo de suscripción ("Gardyn Membership") que incluye envío recurrente de yCubes (semillas) y soporte. Representa el segmento **premium + IA** y es el competidor más cercano en filosofía, aunque a un precio muy elevado y atado a su propio formato de cultivo.

**¿Por qué llevar a cabo este análisis?**  
**Pregunta clave:** ¿Cómo se posiciona **Oryxen** frente a una app popular sin hardware (Planta), un electrodoméstico de cultivo cerrado (Click & Grow) y una solución premium con IA y cámara (Gardyn), considerando propuesta de valor, mercado objetivo, modelo de negocio y capacidades tecnológicas?

### 2.1.1. Análisis competitivo

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <th colspan="5">Competitive Analysis Landscape - Oryxen (GrassFarming)</th>
  </tr>
  <tr>
    <td>¿Por qué llevar a cabo este análisis?</td>
    <td colspan="4">Identificar fortalezas y debilidades frente a competidores de software (apps de cuidado con IA), electrodomésticos de cultivo cerrado y huertos inteligentes premium, con el fin de posicionar a Oryxen como la única solución modular que convierte las plantas que el usuario ya posee en plantas inteligentes, combinando sensores, riego automático y un chatbot con IA a un precio accesible.</td>
  </tr>
  <tr>
    <td colspan="5"></td>
  </tr>
  <tr>
    <th>(En la cabecera colocar por cada competidor nombre y logo)</th>
    <th>Oryxen (GrassFarming)</th>
    <th>Competidor 1: Planta</th>
    <th>Competidor 2: Click & Grow</th>
    <th>Competidor 3: Gardyn</th>
  </tr>

  <tr>
    <th colspan="5" style="text-align: center;"><strong>Perfil</strong></th>
  </tr>
  <tr>
    <td>Overview</td>
    <td>Solución IoT modular que convierte las macetas existentes del usuario en plantas inteligentes mediante sensores, riego automático, chatbot con IA y panel de control web/móvil.</td>
    <td>Aplicación móvil con recordatorios, identificación de plantas por foto, medidor de luz vía cámara y base de datos de especies. Solo software.</td>
    <td>Electrodoméstico de jardinería indoor con riego automatizado, luces LED y cápsulas propietarias de semillas.</td>
    <td>Huerto vertical hidropónico premium con IA "Kelby" y cámaras integradas, controlado desde una app.</td>
  </tr>
  <tr>
    <td>Ventaja competitiva</td>
    <td>Combina automatización + IA conversacional sobre las plantas que el usuario ya tiene. Sensores modulares de bajo costo y chatbot entrenado para asistir de forma personalizada.</td>
    <td>Enorme base de usuarios, marca consolidada y una experiencia de app pulida con identificación de plantas por IA.</td>
    <td>Jardín llave en mano: el usuario solo conecta el aparato y añade agua cada varias semanas.</td>
    <td>IA con visión por cámara que detecta en tiempo real el estado de cada planta; experiencia "set and forget" de gama alta.</td>
  </tr>
  <tr>
    <td>¿Qué valor ofrece a los clientes?</td>
    <td>Tranquilidad, ahorro de tiempo y reducción de pérdidas para las plantas que ya poseen, con acompañamiento por IA al nivel de un experto.</td>
    <td>Educación básica y recordatorios para usuarios principiantes, a un costo muy bajo.</td>
    <td>Posibilidad de cultivar hierbas y vegetales frescos en casa sin experiencia previa.</td>
    <td>Producción de alimentos en casa con mínimo esfuerzo y una experiencia tech-premium guiada por IA.</td>
  </tr>

  <tr>
    <th colspan="5" style="text-align: center;"><strong>Perfil de Marketing</strong></th>
  </tr>
  <tr>
    <td>Mercado objetivo</td>
    <td>Personas ocupadas (25–45) y aficionados a la jardinería en zonas urbanas, así como adultos mayores que buscan asistencia continua para sus plantas ya existentes.</td>
    <td>Usuarios principiantes y casuales que quieren recordatorios y aprender sobre sus plantas desde el celular.</td>
    <td>Usuarios de clase media-alta interesados en cocina casera, hierbas frescas y decoración indoor.</td>
    <td>Hogares tech-premium y foodies interesados en autoabastecimiento y hidroponia en EE. UU.</td>
  </tr>
  <tr>
    <td>Estrategias de marketing</td>
    <td>Redes sociales, creadores de contenido de jardinería, alianzas con viveros locales y campañas en marketplaces de hogar inteligente.</td>
    <td>App store optimization, freemium agresivo y marketing viral en TikTok/Instagram.</td>
    <td>E-commerce propio, presencia en retailers de diseño y campañas en sostenibilidad.</td>
    <td>Publicidad digital, ferias tecnológicas (CES) y modelo D2C con membresía.</td>
  </tr>

  <tr>
    <th colspan="5" style="text-align: center;"><strong>Perfil de Producto</strong></th>
  </tr>
  <tr>
    <td>Productos & Servicios</td>
    <td>Kit de sensores IoT modulares + módulo de riego automático + aplicación móvil/web + chatbot con IA + planes básico y premium por suscripción.</td>
    <td>Aplicación móvil iOS/Android con plan gratuito y Planta Premium.</td>
    <td>Jardín inteligente cerrado (Smart Garden 3/9/25) + cápsulas de semillas recurrentes.</td>
    <td>Home Kit 3.0 hidropónico + Gardyn Membership + yCubes (semillas) + IA Kelby.</td>
  </tr>
  <tr>
    <td>Precios & Costos</td>
    <td>Kit inicial accesible + suscripción mensual (plan básico gratuito, premium con IA y sensores adicionales).</td>
    <td>App gratuita + Planta Premium ≈ USD 30/año.</td>
    <td>USD 100–600 según tamaño + cápsulas de semillas recurrentes (USD 10–30 por set).</td>
    <td>USD 700+ por el Home Kit + membresía mensual con yCubes incluidos.</td>
  </tr>
  <tr>
    <td>Canales de distribución</td>
    <td>App móvil + Plataforma web + alianzas con viveros y tiendas de hogar inteligente en Perú/LATAM.</td>
    <td>App Store y Google Play (global).</td>
    <td>Sitio propio, Amazon y retail de decoración (internacional).</td>
    <td>Sitio propio D2C (principalmente EE. UU.).</td>
  </tr>

  <tr>
    <th colspan="5" style="text-align: center;"><strong>Análisis SWOT</strong></th>
  </tr>
  <tr>
    <td>Fortalezas</td>
    <td>
      <ul>
        <li>Único que combina sensores + riego automático + chatbot con IA</li>
        <li>Trabaja sobre las plantas y macetas que el usuario ya posee</li>
        <li>Sensores modulares de bajo costo</li>
        <li>Plan freemium accesible para LATAM</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Marca consolidada y comunidad grande</li>
        <li>IA de identificación por foto muy madura</li>
        <li>Costo mínimo para el usuario final</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Automatización total del cultivo</li>
        <li>Diseño atractivo y llave en mano</li>
        <li>Experiencia educativa para principiantes</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Visión por cámara + IA para diagnóstico</li>
        <li>Modelo de suscripción recurrente consolidado</li>
        <li>Branding tecnológico premium</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>Debilidades</td>
    <td>
      <ul>
        <li>Startup nueva sin posicionamiento consolidado</li>
        <li>Presupuesto de marketing inicial limitado</li>
        <li>Requiere validación del hardware a mayor escala</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>No tiene hardware: depende totalmente del usuario para ejecutar tareas</li>
        <li>No riega, no mide humedad real del suelo</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Ecosistema cerrado: solo funciona con sus cápsulas</li>
        <li>No sirve para las plantas existentes del usuario</li>
        <li>Costo recurrente de semillas propietarias</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Precio muy elevado</li>
        <li>Disponibilidad geográfica restringida</li>
        <li>Formato único (no se adapta a macetas)</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>Oportunidades</td>
    <td>
      <ul>
        <li>Crecimiento del hogar inteligente en LATAM</li>
        <li>Auge de la jardinería urbana post-pandemia</li>
        <li>Adopción masiva de asistentes con IA</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Monetizar su base con funciones premium</li>
        <li>Extender hacia integraciones con hardware de terceros</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Tendencia "grow your own food"</li>
        <li>Expansión a mercados emergentes</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Expansión internacional</li>
        <li>Alianzas con retailers de alimentos orgánicos</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>Amenazas</td>
    <td>
      <ul>
        <li>Entrada de grandes players (Xiaomi, Google Home) al segmento</li>
        <li>Fallas de hardware que erosionen la confianza del usuario</li>
        <li>Apps gratuitas con IA como alternativa "suficiente"</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Aparición de competidores con hardware integrado</li>
        <li>Fatiga de suscripciones</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Usuarios que prefieren soluciones abiertas y modulares</li>
        <li>Alternativas más baratas en Amazon</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Competencia de soluciones modulares más económicas</li>
        <li>Sensibilidad al precio en contextos de recesión</li>
      </ul>
    </td>
  </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

**Estrategias generales de Oryxen**
- Diferenciación por la **integración de automatización + IA conversacional** aplicada sobre las plantas que el usuario ya posee, sin obligarlo a migrar a un ecosistema cerrado.
- Ecosistema **hardware + software modular**: sensores independientes, riego automatizado y panel centralizado accesible desde web y móvil.
- Modelo de negocio **freemium** con un plan gratuito para usuarios nuevos y un plan premium con chatbot avanzado y sensores adicionales.
- Posicionamiento como un **aliado cotidiano** para hogares ocupados y aficionados latinoamericanos, con precios adaptados al mercado regional.

---

**Tácticas frente a competidores**

| Competidor | Estrategia | Táctica |
|------------|------------|---------|
| **Planta** | Complementar y superar el "solo software" con hardware | Mostrar que los recordatorios sin sensores siguen dependiendo del usuario; Oryxen ejecuta, no solo recuerda. Ofrecer importación de especies desde apps de recordatorio como puente de migración. |
| **Click & Grow** | Diferenciarse del ecosistema cerrado | Comunicar que Oryxen funciona con cualquier maceta y planta que el usuario ya tenga, sin depender de cápsulas propietarias ni de un solo tipo de cultivo. |
| **Gardyn** | Competir por valor frente a una solución premium y regional | Ofrecer capacidades de IA equivalentes (diagnóstico conversacional por especie) a una fracción del costo y con disponibilidad en LATAM, sin obligar al usuario a comprar un huerto vertical completo. |


<div style="page-break-after: always;"></div>

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

**Preguntas generales (aplicables a todos los entrevistados):**

- Edad, género, distrito de residencia.
- Ocupación y nivel de estudios.
- ¿Qué dispositivos usas con mayor frecuencia (celular, tablet, laptop)?
- ¿En qué canales digitales pasas más tiempo (redes sociales, apps de productividad, etc.)?
- ¿Qué marcas o productos tecnológicos usas y confías?

---

**Segmento 1 – Personas ocupadas**

Objetivo: entender cómo encaja Oryxen en la vida diaria de personas con poco tiempo disponible y qué tanto valoran la automatización del cuidado de plantas.

- ¿Con qué frecuencia tienes dificultades para mantener el cuidado constante de tus plantas (riego, luz, etc.)?
- ¿Qué sientes o haces cuando notas que una planta se está marchitando?
- ¿Cuántas plantas tienes actualmente y dónde las mantienes (casa, oficina, balcón, etc.)?
- ¿Cuánto tiempo dedicas al cuidado de tus plantas en una semana típica?
- ¿Qué es lo más difícil para ti al cuidar tus plantas? (ej. saber cuándo regar, identificar problemas, falta de tiempo)
- ¿Has perdido plantas anteriormente? ¿Por qué crees que ocurrió?
- ¿Usas actualmente alguna app, recordatorio o método para cuidar tus plantas? Si es sí, ¿te funcionó o no y por qué?
- ¿Qué tan útil te parecería que un sistema riegue automáticamente tus plantas cuando lo necesiten?
- Si pudieras tomar una foto de tu planta y recibir un diagnóstico con recomendaciones claras, ¿lo usarías? ¿Por qué?
- ¿Confiarías en recomendaciones generadas por una IA para cuidar tus plantas? ¿Qué necesitarías para confiar en ellas?
- ¿Estarías dispuesto(a) a instalar sensores en tus macetas? ¿Qué te detendría?
- ¿Pagarías por una solución que mantenga tus plantas saludables automáticamente? ¿Cuánto aproximadamente?

---

**Segmento 2 – Aficionados a la jardinería**

Objetivo: descubrir su nivel de compromiso, el detalle con el que cuidan sus plantas y su apertura a integrar tecnología avanzada en su rutina.

- ¿Cuántas plantas tienes actualmente y qué tipos te interesan más?
- ¿Cómo organizas el cuidado de tus plantas (riego, luz, seguimiento)?
- ¿Cuál es el mayor reto que enfrentas al cuidar varias plantas?
- ¿Has perdido plantas por errores de cuidado? ¿Qué crees que pasó?
- ¿Te gustaría llevar un seguimiento del estado de tus plantas (historial, cambios, evolución)?
- ¿Qué tan útil te parecería ver datos como humedad, temperatura o estado en tiempo real?
- Si pudieras tomar una foto y recibir un diagnóstico con recomendaciones específicas, ¿lo usarías?
- ¿Qué nivel de confianza tendrías en recomendaciones hechas por una IA?
- ¿Estarías dispuesto(a) a usar sensores en tus macetas para mejorar el cuidado? ¿Por qué?
- ¿Pagarías por funciones avanzadas (IA, análisis, recomendaciones)? ¿Qué tipo de pago prefieres?

### 2.2.2. Registro de entrevistas

*Sección en desarrollo. Los registros completos de las entrevistas (grabaciones, transcripciones y fichas individuales de cada entrevistado) se incorporarán en la siguiente entrega.*

### 2.2.3. Análisis de entrevistas

**Análisis del Segmento 1 – Personas ocupadas:**

Las entrevistas revelan que los usuarios de este segmento valoran tener plantas por el bienestar y la estética que aportan a sus espacios, pero enfrentan dificultades constantes para cuidarlas debido a la falta de tiempo, el olvido y, en algunos casos, el espacio limitado en departamentos y oficinas. Los entrevistados comparten un patrón común: olvidan regar sus plantas varias veces al mes, y aunque algunos utilizan recordatorios genéricos, estos no son suficientes para evitar la pérdida.

Todos los entrevistados usan dispositivos tecnológicos con fluidez (smartphone y laptop) y muestran interés en una solución digital que facilite el cuidado. Coinciden en que Oryxen sería muy útil para automatizar el riego y emitir recordatorios contextuales, reduciendo así el esfuerzo y los olvidos. Varios manifestaron disposición para pagar por una membresía siempre que el costo sea razonable y los beneficios sean claros.

En síntesis, las entrevistas confirman una necesidad clara: las personas quieren cuidar sus plantas, pero requieren una herramienta inteligente que automatice tareas y les ayude a mantenerlas saludables sin demandar tiempo ni atención constante. Oryxen se presenta como una solución práctica, eficiente y emocionalmente valiosa para este segmento.

**Análisis del Segmento 2 – Aficionados a la jardinería:**

Las entrevistas con aficionados reflejan distintos perfiles de usuarios con un interés común: el gusto por las plantas y el deseo de cuidarlas adecuadamente, aunque todos enfrentan dificultades relacionadas con el riego, los olvidos y la falta de información sobre las condiciones ambientales. Se identificaron usuarios metódicos y previsores que cuidan entre 7 y 15 macetas y buscan una herramienta que les permita registrar el progreso de sus plantas, visualizar estadísticas y anticiparse a problemas climáticos.

Los aficionados más jóvenes destacan por su buen manejo tecnológico y su preferencia por apps visuales, sencillas y prácticas, con alertas personalizadas y monitoreo de humedad en tiempo real. Algunos prefieren pagar una sola vez por el hardware, mientras que otros valoran el acceso a funciones avanzadas mediante una suscripción mensual, siempre que la herramienta ofrezca beneficios tangibles y sea fácil de usar.

Los perfiles más tradicionales, aunque menos expertos en tecnología, están abiertos a adoptarla si la solución es clara, intuitiva y les ayuda a mejorar sus hábitos de cuidado. Les atraen especialmente las apps con gráficos, estadísticas y notificaciones visuales.

En conjunto, las entrevistas evidencian que los principales retos en el cuidado de las plantas son la falta de constancia, los errores de riego y la influencia del clima, y que existe una alta disposición a adoptar soluciones tecnológicas siempre que sean simples, visuales y realmente útiles. Oryxen se presenta como una solución ideal al ofrecer un sistema IoT capaz de automatizar recordatorios, monitorear el estado de las plantas y brindar información contextual mediante su chatbot con IA, adaptándose a distintos tipos de usuarios: desde los más experimentados y metódicos hasta los más tradicionales o principiantes.

<div style="page-break-after: always;"></div>

## 2.3. Needfinding

A través de la observación, entrevistas y análisis, se busca profundizar en las problemáticas que enfrentan nuestros segmentos objetivos. Este apartado se enfoca en recopilar información relevante que sirva como base para la creación del User Persona, User Task Matrix, User Journey Maps y Empathy Mapping.

### 2.3.1. User Personas

Se trata de una representación ficticia de un usuario, basada en datos reales de comportamientos observados. Estas representaciones incluyen detalles como edad, ocupación, motivaciones y frustraciones, lo que ayuda a orientar la toma de decisiones y a crear productos más efectivos, enfocados en las necesidades reales del usuario. La herramienta que se utilizó para mostrar la información fue UXPressia.

**Segmento Objetivo 1: Personas ocupadas**

Este perfil refleja a un joven profesional que busca incorporar plantas a su rutina como una forma de mejorar su espacio de trabajo y reducir el estrés, pero que enfrenta obstáculos por su falta de tiempo, experiencia y constancia. Está abierto a usar tecnología que le facilite el cuidado y le brinde recordatorios prácticos, sin complicaciones adicionales en su día a día.

**Persona:** Diego Mendoza

<img src="./assets/Chapter-2/userpersona-1.png" alt="Diego Mendoza - User Persona">


**Segmento Objetivo 2: Aficionados a la jardinería**

Este perfil refleja a una persona apasionada por las plantas, que ha convertido el cuidado de su colección en parte de su rutina y bienestar diario. Tiene conocimientos básicos o intermedios, disfruta investigando sobre especies, y encuentra satisfacción en ver crecer sus plantas. Aunque ya tiene experiencia, busca herramientas que le ayuden a organizar mejor los cuidados, registrar sus avances y seguir aprendiendo.

**Persona:** Carolina Vargas

<img src="./assets/Chapter-2/userpersona-2.png" alt="Diego Mendoza - User Persona">


### 2.3.2. User Task Matrix

El User Task Matrix permite identificar y comparar los procesos clave de cada segmento, destacando sus similitudes en cuanto a frecuencia e importancia.

|**Necesidad / Función**|**Importancia (Personas ocupadas)**|**Frecuencia (Personas ocupadas)**|**Importancia (Aficionados)**|**Frecuencia (Aficionados)**|
| :- | :- | :- | :- | :- |
|Revisar manualmente la humedad del suelo |Alta|Media|Alta|Media|
|Interpretar señales visuales de la planta |Alta|Baja|Alta|Media|
|Regar las plantas en horarios fijos |Media|Baja|Media|Media|
|Consultar fuentes variadas para saber cuándo y cuánto regar|Media|Baja|Alta|Alta|
|Revisar el clima manualmente para ajustar el riego |Media|Baja|Media|Media|
|Tomar notas manuales del riego |Baja|Baja|Media|Media|
|Recorrer todas las macetas para revisar planta por planta|Baja|Baja|Alta|Alta|

En la matriz presentada, se pueden observar las siguientes tareas con mayor frecuencia e importancia:

- **Personas ocupadas**:

  - **Revisar manualmente la humedad del suelo**  
    Funcionalidad **más crítica**, con **importancia alta y frecuencia media**.  
    Las personas ocupadas necesitan un sistema confiable para medir la humedad del suelo, facilitando el riego de sus plantas sin depender de su disponibilidad.

  - **Regar las plantas en horarios fijos y revisar el clima manualmente**  
    Tareas de **media importancia** pero **frecuencia baja**. Son actividades que los usuarios intentan cumplir, pero que olvidan fácilmente.

  - **Tomar notas manuales del riego**  
    De **importancia y frecuencia baja**. No forman parte de su rutina diaria, por lo que pueden ofrecerse como funciones secundarias u opcionales dentro de Oryxen.

- **Aficionados a la jardinería**:

  - **Consultar fuentes variadas para saber cuándo y cuánto regar**  
    Funcionalidad **más crítica**, con **alta importancia y frecuencia**.  
    Requieren herramientas externas para garantizar el cuidado óptimo de sus plantas, por lo que valoran que Oryxen centralice esta información.

  - **Interpretar señales visuales de la planta**  
    Tareas de **alta importancia** pero **frecuencia media**.  
    Requieren experiencia y apoyo visual para comprobar el estado real de cada especie.

  - **Recorrer todas las macetas para revisar planta por planta**  
    Actividad de **alta importancia** y de **frecuencia alta**, que puede ser optimizada mediante el panel centralizado de Oryxen.

### 2.3.3. User Journey Mapping

El User Journey Mapping fue creado con el objetivo de entender cómo los usuarios experimentan nuestra plataforma. Este proceso describe paso a paso las acciones que realizan, los posibles obstáculos que enfrentan y las emociones que experimentan durante la interacción. De esta manera, nos permite detectar áreas de mejora para optimizar la usabilidad y aumentar la satisfacción del usuario.

#### Segmento 1: Personas ocupadas

En este User Journey Map se muestra la experiencia actual de Diego Mendoza, una persona ocupada que vive en un departamento y necesita atender sus plantas entre sus responsabilidades diarias.

<img src="./assets/Chapter-2/journeymap-1.png" alt="Diego Mendoza - User Persona">

#### Segmento 2: Aficionados a la jardinería

En este User Journey Map se muestra la experiencia actual de Carolina Vargas, una aficionada a las plantas que vive en una casa y dedica parte de su día al cuidado de múltiples macetas de distintas especies.

<img src="./assets/Chapter-2/journeymap-2.png" alt="Carolina Vargas - User Persona">

### 2.3.4. Empathy Mapping

Para desarrollar el Empathy Map, nos basamos en la información recopilada de nuestros dos User Personas, quienes representan a nuestros segmentos objetivo. Este recurso nos facilita una comprensión más profunda de las necesidades, pensamientos, emociones y conductas de los usuarios, lo que nos permite crear soluciones mejor adaptadas a sus expectativas y experiencias reales.

#### Segmento 1: Personas ocupadas

En el siguiente Empathy Map tenemos a Diego Mendoza, un joven profesional que vive en un departamento. Él lucha diariamente para conservar sus plantas en buen estado mientras equilibra su carga laboral y personal.

<img src="./assets/Chapter-2/empathymap-1.png" alt="Diego Mendoza - User Persona">

#### Segmento 2: Aficionados a la jardinería

En el siguiente Empathy Map observamos a Carolina Vargas, una mujer que vive en casa con su familia. Ella es una aficionada a las plantas que dedica tiempo recurrente al cuidado detallado de su colección.

<img src="./assets/Chapter-2/empathymap-2.png" alt="Carolina Vargas - User Persona">

## 2.4. Big Picture EventStorming

Es un taller colaborativo diseñado para que un grupo de personas (desarrolladores, expertos en el negocio, gerentes de producto, etc.) exploren y entiendan un dominio de negocio complejo de manera rápida.

**Sus objetivos principales son:**

- **Alinear a todos:** Asegurarse de que todo el equipo tenga el mismo entendimiento del proceso de negocio.
- **Identificar problemas:** Descubrir cuellos de botella, dudas y complejidades que no son obvias a simple vista.
- **Crear un lenguaje común:** Empezar a construir un "lenguaje ubicuo", es decir, un vocabulario compartido entre los expertos del negocio y el equipo técnico.

***1. Preparing the room***

Para garantizar comodidad, eficiencia y colaboración en tiempo real, elegimos la plataforma Discord como entorno virtual para nuestro primer encuentro. Allí, nos reunimos con el objetivo de alinear la comprensión del negocio, identificar dudas clave, mapear problemas recurrentes y fomentar un ambiente de confianza y comunicación abierta basado en el dominio del problema: el cuidado automatizado de plantas en entornos domésticos y de oficina con Oryxen.



***2. Energizing the audience***

Para activar la atención y crear un clima positivo, iniciamos la sesión con una breve rutina de estiramientos físicos realizados desde nuestros espacios personales, seguida de un ejercicio cognitivo ligero (como un juego de memoria o resolución rápida de acertijos). Esta actividad buscó estimular la concentración, reducir la tensión y promover la conexión humana entre los participantes antes de abordar temas complejos.

***3. Briefing and presenting the plan***

A continuación, presentamos los objetivos centrales del proyecto: desarrollar Oryxen, un producto IoT que facilite el cuidado automatizado de plantas en espacios urbanos —ya sean pequeños departamentos, oficinas u hogares más amplios— mediante sensores inteligentes, riego automático, alertas personalizadas y un chatbot conversacional potenciado con IA.

Además, explicamos el modelo de negocio: un servicio de suscripción mensual que ofrece soporte técnico, recomendaciones personalizadas por especie y actualizaciones continuas, generando ingresos sostenibles. También se revisaron las convenciones básicas del negocio, como los roles esperados, los plazos clave y las herramientas de trabajo a utilizar.

***4. Generating Domain Events***

Pedimos a los participantes que escriban en post-its amarillos los "eventos" que ocurren en el proceso. Un evento es algo relevante para el negocio que ya sucedió (se escribe en pasado, ej: "Usuario registró planta", "Sensor reportó humedad baja", "Riego automático se activó").

[![Big-Picture-Event-Storming-5.jpg](https://i.postimg.cc/3N3tTYX8/Big-Picture-Event-Storming-5.jpg)](https://postimg.cc/YGy6NcDZ)

***5. Sorting Domain Events***

Pedimos al equipo que ordene cronológicamente los eventos colocados en post-its amarillos sobre una pared, de izquierda a derecha, para construir una línea temporal del proceso de cuidado automatizado de plantas con Oryxen.

Este ejercicio no es solo un mero ordenamiento: es el momento más valioso de la sesión. Al debatir si el orden propuesto es correcto, el equipo comienza a revelar diferencias en sus percepciones, asunciones ocultas y malentendidos sobre cómo funciona realmente el proceso. Estas discusiones, lejos de ser conflictos, son oportunidades clave para alinear la comprensión colectiva, identificar brechas en el flujo del negocio y construir un modelo compartido y preciso del dominio.

[![Big-Picture-Event-Storming-6.jpg](https://i.postimg.cc/FzPVXcFS/Big-Picture-Event-Storming-6.jpg)](https://postimg.cc/ZvddrWdY)

***6. Adding Actors and External Systems***

Para profundizar en la modelación del dominio, asignamos colores distintos a los elementos clave que interactúan con los eventos ya ordenados:

- **Actores:** Utilizando post-its de color naranja, identificamos quién (o qué rol) inicia o participa en cada evento. Estos actores representan personas, roles o entidades externas que intervienen en el proceso —por ejemplo: "Usuario final", "Administrador de Oryxen", "Agente del chatbot de IA". Esto permite mapear las responsabilidades humanas y lógicas dentro del flujo.

- **Sistemas Externos:** Con post-its de color azul, señalamos los sistemas, servicios o plataformas externas con los que el producto interactúa como "Pasarela de pagos", "Servicio de envío del kit de sensores", "API de clima local" o "Proveedor de modelos de IA para el chatbot". Esto ayuda a definir los puntos de integración necesarios y a anticipar dependencias técnicas.

- **Problemas o Dudas:** Utilizamos el rojo para identificar dudas o problemas en lugar de detenernos a debatir o discutir durante la sesión.

[![Big-Picture-Event-Storming-7.jpg](https://i.postimg.cc/KjsBH2Q5/Big-Picture-Event-Storming-7.jpg)](https://postimg.cc/ctwvvPpK)

***7. Storytelling***

Se recorre cronológicamente la línea de eventos, desde el inicio hasta el final, narrando la historia que los post-its construyen colectivamente. Esta narrativa permite validar la coherencia del flujo, identificar saltos lógicos, confirmar la secuencia de acciones y detectar eventuales omisiones o redundancias en el proceso de Oryxen.

[![Big-Picture-Event-Storming-8.jpg](https://i.postimg.cc/26SqRtqV/Big-Picture-Event-Storming-8.jpg)](https://postimg.cc/TyB2nCJ6)

***8. Reverse storytelling***

Como complemento, se puede realizar una narración inversa: partir del último evento y retroceder hasta el inicial. Este enfoque revela dependencias ocultas, puntos de fricción no evidentes en el sentido directo y posibles fallos en la causalidad del proceso. Es especialmente útil para desafiar supuestos y descubrir interacciones críticas que podrían pasar desapercibidas al seguir solo el orden tradicional.

***9. Closing***

Al cierre de la sesión, se evalúan los logros alcanzados:

- La construcción de un entendimiento compartido del dominio del negocio.
- La identificación clara de problemas, dudas y puntos de incertidumbre.
- El surgimiento de un lenguaje común entre los participantes, que facilita la comunicación técnica y operativa en futuras etapas del desarrollo de Oryxen.

## 2.5. Ubiquitous Language

| **Term** | **Definition** |
|----------|----------------|
| **Watering Threshold** | The minimum acceptable humidity level for a specific plant, which triggers a notification or an automatic watering action when reached. |
| **Humidity Sensor** | Component that measures the soil moisture level in the pot. |
| **Humidity Level** | Percentage value indicating the amount of water in the soil. |
| **Control Panel** | Main screen showing the overall status of all registered plants. |
| **Plant Profile** | Information linked to a specific plant (species, location, pot, threshold, photos). |
| **Push Notification** | Mobile message notifying the user about plant status, watering events or AI recommendations. |
| **Automatic Watering** | Action performed by the Oryxen device to water a plant when its humidity falls below the configured threshold. |
| **AI Chatbot** | Conversational assistant that provides personalized care recommendations based on plant data and user questions. |
| **Update Status** | Action of confirming in the app that the plant has been watered or cared for manually. |
| **Receive Notification** | Action of being alerted when a plant requires watering, is in a risk state or needs attention. |
| **Register Plant** | Action of adding a new plant into the system with its data, species and assigned sensor. |
| **Subscription Plan** | Service tier (free or premium) that defines the features and capabilities available to a user. |
| **Web Platform / Mobile App** | Digital interface accessible via computer or smartphone where users view and manage information about their plants. |
| **Device Monitoring** | Functionality that allows users to configure, monitor or troubleshoot installed IoT sensors from Oryxen. |


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