<div align="center">

<h3>Universidad Peruana de Ciencias Aplicadas</h3>

<img alt="upc-logo" src="/assets/images/UPC_logo_transparente.png" width="200"/><br>

<strong>Ingeniería de Software - 2025-2</strong><br>
<strong>1ASI0730 - Aplicaciones Web</strong><br>
<strong>NRC: 7414<br>
<strong>Profesor: Alex Humberto Sánchez Ponce</strong><br>

<br><strong>Informe del Trabajo Final</strong><br><br>

<strong>Startup: AgroMind</strong><br>
<strong>Producto: EcoTrack</strong><br>



### Team Members:

|             Member              |    Code     |
|:-------------------------------:|:-----------:|
|       Amaro Villar Anjali       |  20221G044  |
| Baquerizo Cirilo Aaron Santiago | U202520156  |
|  Mostajo Orosco Maria Fernanda  | U202312874  |
|  Navarro Correa César Augusto   | U202310129  |
|  Tuesta Marin Romina Alejandra  | U202211706  |

<strong> Setiembre 2025</strong><br>
</div>

# Registro de Versiones del Informe

| Versión    | Fecha      | Autor                   | Descripción de modificación                                                                          |
|------------|------------|-------------------------|------------------------------------------------------------------------------------------------------|
| 1.0        | 25/08/2025 | Anjali Amaro            | Creación de la estructura inicial del reporte                                                        |
| 1.1        | 31/08/2005 | Anjali Amaro            | Realizacion del Capitulo I.                                                                          |
| 1.1.2      | 11/09/2025 | Maria Fernanda Mostajo  | Desarrollo del needfinfing, general style guidelines, web style guidelines, information architecture |
| 2.0        | 09/10/25   | Romina Tuesta           | Correcciones del capitulo I, conclusiones                                                            |
|            |            |                         |                                                                                                      |
|            |            |                         |                                                                                                      |

# Project Report Collaboration Insights

### TB1 

 ![TB1](./assets/images/network.png)
 ![TB1](./assets/images/colab.png)

### TP1 
![img_16.png](assets/images/sprint2/img_16.png)
![img_15.png](assets/images/sprint2/img_15.png)


---

## Contenido
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
    - [2.4. Big Picture EventStoring](#24-big-picture-eventstorming)
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
        - [4.4.2. Web Applications Mock-ups](#442-web-applications-mock-ups)
        - [4.4.3. Web Applications User Flow Diagrams](#443-web-applications-user-flow-diagrams)
    - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
    - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
        - [4.6.1. Design-Level EventStorming](#461-design-level-eventstorming)
        - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
        - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
        - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
    - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
        - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.8. Database Design](#48-database-design)
        - [4.8.1. Database Diagram](#481-database-diagram)
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
          - [5.2.2.1. Sprint Planning 2.](#5221-sprint-planning-2)
          - [5.2.2.2. Aspect Leaders and Collaborators.](#5222-aspect-leaders-and-collaborators)
          - [5.2.2.3. Sprint Backlog 2.](#5223-sprint-backlog-2)
          - [5.2.2.4. Development Evidence for Sprint Review.](#5224-development-evidence-for-sprint-review)
          - [5.2.2.5. Execution Evidence for Sprint Review.](#5225-execution-evidence-for-sprint-review)
          - [5.2.2.6. Services Documentation Evidence for Sprint Review.](#5226-services-documentation-evidence-for-sprint-review)
          - [5.2.2.7. Software Deployment Evidence for Sprint Review.](#5227-software-deployment-evidence-for-sprint-review)
          - [5.2.2.8. Team Collaboration Insights during Sprint.](#5228-team-collaboration-insights-during-sprint)
      - [5.2.3. Sprint 3](#523-sprint-3)
          - [5.2.3.1. Sprint Planning 3.](#5231-sprint-planning-3)
          - [5.2.3.2. Aspect Leaders and Collaborators.](#5232-aspect-leaders-and-collaborators)
          - [5.2.3.3. Sprint Backlog 3.](#5233-sprint-backlog-3)
          - [5.2.3.4. Development Evidence for Sprint Review.](#5234-development-evidence-for-sprint-review)
          - [5.2.3.5. Execution Evidence for Sprint Review.](#5235-execution-evidence-for-sprint-review)
          - [5.2.3.6. Services Documentation Evidence for Sprint Review.](#5236-services-documentation-evidence-for-sprint-review)
          - [5.2.3.7. Software Deployment Evidence for Sprint Review.](#5237-software-deployment-evidence-for-sprint-review)
          - [5.2.3.8. Team Collaboration Insights during Sprint.](#5238-team-collaboration-insights-during-sprint)
    - [5.3. Validation Interviews](#53-validation-interviews)
      - [5.3.1. Diseño de entrevistas](#531-diseño-de-entrevistas)
      - [5.3.2. Registro de entrevistas](#532-registro-de-entrevistas)
      - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
    - [5.4. Video About the Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)
---

## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 5**
**Criterio:** *La capacidad de funcionar efectivamente en un equipo cuyos miembros
juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo,
establecen objetivos, planifican tareas y cumplen objetivos.*

En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro
del ABET – EAC - Student Outcome 5.

| Criterio específico                                                                            | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Conclusiones                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta                                | TB1:<br> *Anjali:* Guié al equipo en varias ocasiones durante la fase inicial para asegurar que todos tuviéramos una visión clara y compartida del proyecto, facilitando la toma de decisiones en conjunto.<br><br>*Aaron:* Fomenté un liderazgo colaborativo, promoviendo la participación activa de todos los miembros en las reuniones para la toma de decisiones.<br><br>*Maria:* Asumí un papel activo en la coordinación de las tareas y el seguimiento del progreso del equipo, trabajando de manera equitativa en las responsabilidades.<br><br>*César:* Aporté ideas que fueron integradas al equipo, ayudando a estructurar las tareas y metas del proyecto, y participé activamente en la toma de decisiones colectivas.<br><br>*Romina:* Participé activamente en el seguimiento de los objetivos y la asignación de tareas, asegurando que el equipo mantuviera un liderazgo compartido y una dirección clara hacia el éxito del proyecto. <br>TP1:<br> *Anjali:* se destacó por su actitud proactiva en la organización del trabajo colaborativo y su apoyo en la toma de decisiones colectivas. <br>*Aaron:* mostró compromiso en la planificación y coordinación de tareas, fomentando la cohesión grupal. <br>*Maria:* integró ideas y guió el desarrollo de funcionalidades clave, promoviendo una comunicación asertiva y un liderazgo colaborativo. <br>*César:* evidenció habilidades de cooperación y apoyo técnico, fortaleciendo el rendimiento grupal mediante su participación activa en la resolución de problemas. Finalmente, <br>*Romina:* demostró iniciativa y apertura al diálogo, contribuyendo a equilibrar responsabilidades y reforzar el liderazgo compartido. En conjunto, el equipo mantuvo una dinámica colaborativa, responsable y orientada al cumplimiento eficiente de los objetivos del sprint.| TB1: <br>Consideramos que este criterio ha sido alcanzado con éxito, ya que el equipo logró dividir responsabilidades de manera equitativa, asegurando que cada miembro ejerciera un rol de liderazgo en distintos momentos y aspectos del proyecto. Esta dinámica permitió que las decisiones no recayeran en una sola persona, sino que se distribuyeran según las fortalezas y competencias de cada integrante. <br> El liderazgo compartido fue clave para mantener el enfoque, resolver problemas de forma conjunta y avanzar con claridad hacia los objetivos definidos. Además, se promovió un ambiente de confianza y respeto, en el que cada opinión era escuchada y valorada. La comunicación constante por medios digitales y la retroalimentación continua facilitaron una toma de decisiones fluida, fortaleciendo la autonomía de cada miembro sin perder la cohesión del equipo. <br>TP1:<br> En conclusión, el equipo evidenció una destacada capacidad para trabajar en conjunto y ejercer liderazgo compartido a lo largo del sprint. <br> Cada integrante asumió responsabilidades con autonomía y disposición para colaborar, contribuyendo al cumplimiento de los objetivos comunes. La comunicación efectiva, la coordinación en la toma de decisiones y el apoyo mutuo fueron factores clave que fortalecieron la cohesión del grupo. Este desempeño refleja un liderazgo colectivo equilibrado, en el que todos los miembros participaron activamente en la planificación, ejecución y revisión de tareas, consolidando un entorno de trabajo colaborativo orientado a resultados de calidad.| 
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos | TB1: <br>*Anjali:* Fomenté un ambiente inclusivo donde todos los miembros se sintieran cómodos aportando ideas, además, me encargué de coordinar las tareas y definir metas claras para el equipo.<br><br>*Aaron:* Apoyé a mis compañeros en la organización y planificación del trabajo a través de herramientas como Trello, que facilitó la gestión del progreso y asignación de tareas.<br><br>*Maria:* Colaboré activamente en la planificación de las tareas y aseguré que se cumplieran los plazos establecidos, contribuyendo a la organización eficiente del equipo.<br><br>*César:* Contribuí al ambiente inclusivo y respetuoso del equipo, apoyando la planificación de tareas y asegurando que cada miembro estuviera alineado con los objetivos comunes.<br><br>*Romina:* Aporté ideas y propuestas que ayudaron a definir las metas del equipo y me aseguré de que todas las tareas estuvieran bien distribuidas, contribuyendo al cumplimiento de los objetivos establecidos. <br>TP1:<br> *Anjali:* promovió la organización del trabajo en equipo, contribuyendo a la definición de metas claras y alcanzables. <br>*Aaron:* destacó por su compromiso en la planificación de tareas y su apoyo constante en la coordinación de actividades, garantizando una ejecución ordenada. <br>*Maria:* aportó una visión estratégica al establecer prioridades y orientar al grupo hacia el cumplimiento de los objetivos planteados. <br>*César:* fomentó la cooperación y la integración del equipo, mostrando disposición para apoyar a sus compañeros y mantener la cohesión durante el proceso. <br>*Romina:* evidenció responsabilidad y constancia en la realización de las tareas asignadas, asegurando el cumplimiento de los plazos establecidos. En conjunto, el equipo demostró capacidad para planificar, colaborar y alcanzar los objetivos del sprint de manera eficiente y armónica. | TB1: <br>Consideramos que hemos logrado establecer un entorno de trabajo verdaderamente colaborativo e inclusivo, donde todas las voces fueron tomadas en cuenta y cada miembro pudo aportar activamente desde sus habilidades. Se definieron metas claras y realistas desde el inicio de la fase de trabajo, y se llevó a cabo una planificación detallada de las tareas a través de herramientas digitales como Trello, Notion y GitHub. <br> La distribución de responsabilidades se hizo de forma estratégica, permitiendo un flujo de trabajo constante y organizado. Esto no solo favoreció el cumplimiento de los plazos, sino también la trazabilidad de los avances y la identificación oportuna de posibles obstáculos. Gracias a esta estructura, el equipo logró cumplir con los objetivos propuestos en cada etapa, fortaleciendo así la eficiencia y cohesión del grupo. <br> TP1: <br> En conclusión, el equipo demostró una sólida capacidad para trabajar de manera colaborativa e inclusiva, estableciendo metas claras, planificando adecuadamente sus tareas y cumpliendo con los objetivos propuestos del sprint. <br> La comunicación constante, la distribución equilibrada de responsabilidades y el respeto por las opiniones de todos los integrantes permitieron mantener un ambiente de trabajo positivo y productivo. Este desempeño refleja un alto nivel de compromiso, organización y liderazgo compartido, evidenciando que el grupo cuenta con las habilidades necesarias para continuar avanzando de forma efectiva en los siguientes ciclos de desarrollo.|
# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

**Agromind** es una startup tecnológica creada por estudiantes de Ingeniería de Software de la Universidad Peruana de Ciencias Aplicadas, enfocada en el desarrollo de soluciones digitales para el sector agrícola. Nuestro producto principal, **EcoTrack**, es una aplicación diseñada para mejorar la productividad y la trazabilidad en el campo, conectando a agricultores y agrónomos a través de un ecosistema digital colaborativo que facilita el registro, monitoreo y análisis de cultivos en tiempo real.

**Misión:** Desarrollar soluciones tecnológicas innovadoras que impulsen la eficiencia y sostenibilidad del sector agrícola, ofreciendo herramientas que fortalezcan la relación entre agricultores y agrónomos, y que contribuyan al crecimiento económico y la seguridad alimentaria.

**Visión:** Convertirnos en la startup agrotech líder en Latinoamérica, reconocida por transformar la manera en que se gestiona la producción agrícola mediante tecnología intuitiva, generando un impacto positivo en la productividad, la trazabilidad y la competitividad del sector.



### 1.1.2. Perfiles de integrantes del equipo

|                             Miembro                              |                                                                                                                                                                                   Descripción                                                                                                                                                                                   |
|:----------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| <img src="assets/images/members/anjali-amaro.jpg" width="300"/>  | **Anjal Amaro Villar \- u20221g044** <br> Mi nombre es Anjali Amaro, tengo 20 años y estoy cursando el 5to ciclo en la carrera deIngeniería de Software en la UPC. Me considero una persona organizada y responsable con el objetivo de crear un ambiente colaborativo y productivo en mi equipo, contribuyendo con dedicación y compromiso para lograr los mejores resultados. |
| <img src="assets/images/members/MariaFernanda.png" width="300"/> | **Maria Fernanda Mostajo Orosco \- u202312874** <br> Mi nombre es Maria Fernanda Mostajo, estoy estudiando la carrera de Ingeniería de Software en la UPC, tengo conocimientos en los lenguajes de programación C++, Python, HTML, CSS, JavaScript y SQL. Además, cuento con habilidades de trabajo en equipo, el cual me permitira realizar un buen trabajo y cumplir con los objetivos planteados en el tiempo establecido.                                                                                                                                                              | 
| <img src="assets/images/members/aaron-baquerizo.jpg" width="300" /> |                                                              Mi nombre es Aaron, estudio Ingeniria de Software en la UPC de Monterrico. Me considero alguien responsable que bisca aprender mas sobre cosas nuevas, decidido a apoyar a cada miembro del equipo para lograr el mejor resultado. Asimismo, espero que mis habilidades puedan ser de utilidad para completar el trabajo de la forma mas efectiva.                                                               | 
|         <img src="assets/images/members/foto_romina.jpeg">          | Romina Tuesta Marin - u202211706 <br> Mi nombre es Romina Tuesta, tengo 20 años, estudio ingeniería de software y me encuentro en 7mo ciclo. Me considero una persona responsable y dispuesta a ayudar a quien necesite en mi grupo, tengo conocimiento en algunos lenguajes de programación como Python, C++, etc. Creo que la mejor manera de desarrollar un proyecto grupal es mantener buena comunicación y que todos se dediquen enteramente a entregar un buenproducto. | 
|       <img src="assets/images/members/foto-cesar.png" width="300">    |      Mi nombre es Cesar Navarro, tengo 19 años y soy de la carrera de Ingeniería de Software de la UPC. Me considero una persona creativa en la realización de los trabajos y resiliente en mis actividades. Tengo conocimientos de lenguajes de programación en C++ y Python, pues siempre tuve interés en la computación.     | 

## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática

#### What? (¿Qué?)

#### ¿Cuál es el problema?

El problema es que los agricultores en el Perú todavia registran sus cultivos de manera manual o desordenada, lo que provoca falta de control sobre costos, baja productividad, lo que provoca falta de control sobre costos, baja productividad, y dificulta la trazabilidad de los productos agrícolas causando mayores perdidas económicas. Además, la comunicación entre agricultores y agrónomos es limitada, lo que impide el acceso a asesoramiento técnico oportuno y personalizado.

#### When? (¿Cuándo?)

#### ¿Cuándo ocurre el problema?

El problema ocurre de manera continua durante todo el ciclo agrícola, desde la siembra hasta la cosecha. En las etapas iniciales surge por la falta de planificación y registro de insumos, durante el desarrollo del cultivo por la ausencia de un seguimiento ordenado de labores como riego y fertilización, y al momento de la cosecha por la carencia de datos claros sobre rendimientos y trazabilidad que permitan acceder a mercados más exigentes. En consecuencia, se trata de una dificultad recurrente en cada campaña agrícola.

#### Where? (¿Dónde?)

#### ¿Dónde surge el problema?

El problema ocurre principalmente en zonas rurales y agrícolas del Perú, donde la agricultores aún dependen de registros manuales que generan desorden, baja productividad y falta de trazabilidad. Los agrónomos que los asesoran tampoco cuentan con herramientas digitales simples para centralizar información y gestionar mejor a sus clientes.

#### ¿A dónde se dirige?

La solución se dirige a agricultores y agrónomos en el Perú que buscan mejorar la gestión de sus cultivos mediante herramientas digitales.

#### Who? (¿Quién?)

#### ¿Quiénes están involucrados?

Los principales usuarios serán los agricultores y los agrónomos.

#### ¿Quién lo utilizará?

Los agricultores utilizarán la aplicación para registrar labores agrícolas, insumos y rendimientos de sus cultivos, mientras que los agrónomos la emplearán para supervisar fincas, dar seguimiento a las actividades registradas y generar reportes técnicos que respalden sus recomendaciones

#### Why? (¿Por qué?)

#### ¿Cuál es la causa del problema?

La causa principal del problema es la baja digitalización en el sector agrícola en el Perú. Muchos agricultores aún continuan usando registros manuales porque no cuentan con herramientas tecnológicas accesibles, simples y adaptadas a su realidad. A esto se suma la resistencia al cambio hacia métodos digitales y la escasez de soluciones locales, lo que mantiene la brecha entre agricultores y agrónomos.

#### How? (¿Cómo?)

#### ¿En qué condiciones los usuarios usarán nuestro producto?

Los agricultores y agrónomos usarán EcoTrack principalmente durante sus actividades de campo y en la planificación de campañas agrícolas. El agricultor lo empleará para registrar labores y rendimientos al finalizar o durante sus jornadas de trabajo, mientras que el agrónomo lo usará para supervisar los datos de sus clientes y generar reportes técnicos que respalden su asesoría.

#### ¿Cómo nos conocieron nuestros compradores?

Nuestros usuarios podrán conocernos a través de campañas digitales dirigidas al sector agro, ferias especializadas en innovación agrícola, y el contacto directo entre agrónomos y agricultores que ya utilicen la app y la recomienden dentro de su red de trabajo.

#### ¿Cómo prefieren nuestros consumidores acceder a nuestro producto?

Los agricultores prefieren acceder a EcoTrack desde sus teléfonos móviles mediante la plataforma web responsive, ya que les permite registrar sus actividades de manera rápida y práctica mientras gestionan sus labores. Por su parte, los agrónomos prefieren usar la misma plataforma tanto en el celular como en la computadora, para analizar la información de varias fincas, comparar resultados y generar reportes técnicos de manera más detallada.

#### How much? (¿Cuánto?)

#### Estadísticas que sustentan la problemática.

Según el Ministerio de Desarrollo Agrario y Riego (MIDAGRI, 2023), la agricultura familiar representó el 97,6% de todas las unidades agropecuarias en el Perú, lo que refleja que la gran mayoría de productores depende de métodos tradicionales de gestión. Dentro de esta, el 88% corresponde a subsistencia, el 10,6% a intermedia y el 1,4% a consolidada, evidenciando que solo una pequeña parte de agricultores cuenta con mejores condiciones para integrarse a mercados exigentes.

Sin embargo, existe un potencial de mejora: un 36,6% de los agricultores de subsistencia ya destina más de la mitad de su producción a la venta, lo que demuestra que incluso dentro de este grupo existe interés por generar ingresos. Asimismo, un 29,7% de los agricultores familiares intermedios y consolidados transforma su producción para la venta, lo que evidencia un sector con disposición a mejorar sus procesos y dar valor agregado.

Estas cifras muestran que gran parte de la agricultura en el país carece de herramientas digitales que faciliten la organización y la trazabilidad. En este contexto, EcoTrack puede ser una solución útil al permitir que agricultores y agrónomos registren información, organicen sus actividades y generen reportes que respalden la calidad de la producción, mejorando la productividad y el acceso a mercados más competitivos.


### 1.2.2. Lean UX Process
El **Lean UX Process** es una metodología ágil que se centra en la colaboración, la experimentación rápida y el aprendizaje validado. En este proyecto se utiliza este enfoque para comprender las experiencias y problemáticas de agricultores y agrónomos, validando hipótesis mediante prototipos y retroalimentación constante.

##### 1.2.2.1. Lean UX Problem Statements

Nuestro sistema busca facilitar a los agricultores el registro de sus actividades agrícolas para mejorar la organización de su producción.

Hemos observado que muchos agricultores llevan sus registros de forma manual o dispersa, lo que dificulta el seguimiento de sus cultivos y la planificación futura.

**¿Cómo podemos lograr que los agricultores registren y gestionen sus actividades de manera más ordenada y confiable?**

El producto tiene como objetivo apoyar a los agrónomos con datos de campo que respalden sus recomendaciones técnicas.

Actualmente, los agrónomos no reciben información actualizada ni centralizada, lo que afecta la precisión de sus decisiones.

**¿Cómo podemos mejorar el acceso de los agrónomos a información confiable y en tiempo real para optimizar la asesoría técnica?**

Nuestro servicio está orientado a que los agricultores con parcelas reducidas optimicen la planificación de sus cultivos.

Sin embargo, observamos que muchos productores carecen de información organizada para proyectar rendimientos y tomar decisiones de siembra eficientes.

**¿Cómo podemos ayudar a los agricultores a planificar sus cultivos de forma más clara y estructurada para mejorar su productividad?**

##### 1.2.2.2. Lean UX Assumptions

#### Business Assumptions

1. **Creo que mis clientes necesitan** una forma confiable y sencilla de organizar, dar seguimiento y profesionalizar la gestión de sus cultivos.
2. **Estas necesidades se pueden resolver con** una aplicación web que integre registro productivo, alertas y asesoría especializada.
3. **Mis clientes iniciales serán** agricultores pequeños y medianos interesados en digitalizar su producción, y agrónomos que requieren datos de campo.
4. **EL valor más importante que el cliente quiere de mi servicio es** mejorar la productividad y reducir riesgos al tomar decisiones basadas en datos reales.
5. **El cliente también puede obtener estos beneficios adicionales:** acceso a alertas por clima e IoT, gestión de inventario, trazabilidad y asesoría profesional.
6. **Voy a adquirir la mayoría de mis clientes a través de** alianzas con asociaciones de agricultores, ferias agropecuarias, y marketing digital en redes sociales.
7. **Haré dinero a través de** un modelo de suscripción mensual con planes escalonados: AgroStart (5 USD), AgroSmart (25 USD) y AgroExpert (50 USD).
8. **Mi competencia principal en el mercado será** otras apps agrícolas de gestión y plataformas de IoT que ofrecen monitoreo de cultivos.
9. **Los venceremos debido a** un enfoque local adaptado al contexto peruano, facilidad de uso y el valor agregado de la asesoría profesional.
10. **Mi mayor riesgo de producto es que** los agricultores pequeños no adopten la aplicación por falta de familiaridad con la tecnología o baja disposición a pagar.
11. **Resolveremos esto a través de** capacitaciones simples, tutoriales dentro de la app, y un plan de entrada accesible (AgroStart) que facilite la adopción gradual.

#### User Assumptions

**¿Quién es el usuario?**

Los usuarios de Ecotrack son agricultores de diferentes escalas (pequeños y medianos) que buscan organizar y mejorar la gestión de sus cultivos, así como agrónomos que necesitan información de campo confiable y en tiempo real para optimizar sus recomendaciones técnicas.

**¿Qué problemas tiene nuestro producto que resolver?**

Ecotrack busca resolver la desorganización en el registro de actividades agrícolas, la falta de trazabilidad en la producción, la ausencia de alertas preventivas relacionadas con el clima o riesgos del cultivo y la baja adopción tecnológica que limita la eficiencia de los productores.

**¿Que caraterísticas son importantes?**

Las características clave son la posibilidad de registrar y dar seguimiento a los cultivos de manera sencilla, recibir alertas climáticas e integrar datos de IoT, gestionar inventarios agrícolas, mantener trazabilidad de la producción y, en planes avanzados, acceder a asesoría especializada de agrónomos.

**¿Dónde encaja nuestro producto en su trabajo o vida?**

El producto encaja en la rutina diaria de los agricultores como una herramienta que reemplaza los registros manuales y centraliza la información productiva, convirtiéndose en apoyo esencial para la planificación de cultivos, la toma de decisiones y la mejora continua de la productividad.

**¿Cuándo y cómo nuestro producto es usado?**

Ecotrack se utiliza en distintos momentos del ciclo agrícola: al planificar cultivos, registrar actividades de campo, gestionar inventario y recibir notificaciones relacionadas con el clima o posibles riesgos. Su uso principal es a través de una aplicación web accesible desde navegadores en computadoras o dispositivos móviles, lo que permite a los usuarios consultarla y actualizar información de manera práctica en cualquier lugar con conexión a internet.

**¿Cómo debe verse nuetro producto y cómo comportarse?**

El producto debe tener un diseño visual simple y claro, con iconos intuitivos y un lenguaje accesible que permita a los usuarios aprender a usarlo rápidamente; además, debe comportarse de forma ágil, confiable y proactiva, enviando notificaciones oportunas y garantizando una experiencia sin fricciones.

##### 1.2.2.3. Lean UX Hypothesis Statements

- **Hypothesis 01:**

  **Creemos que** los agricultores pequeños registrarán con mayor frecuencia sus actividades agrícolas si cuentan con una herramienta digital sencilla.

  **Sabremos que** hemos tenido éxito.

  **Cuando** los usuarios ingresen al menos dos registros semanales en la aplicación.


- **Hypothesis 02:**

  **Creemos que** los agricultores medianos reducirán pérdidas productivas si reciben alertas en tiempo real sobre el clima y condiciones críticas.

  **Sabremos que** hemos tenido éxito.

  **Cuando** los usuarios reporten menos incidentes climáticos en entrevistas y un 20% de reducción en pérdidas en sus cultivos.


- **Hypothesis 03:**

  **Creemos que** los agricultores aumentarán su eficiencia si pueden controlar su inventario agrícola desde la plataforma.

  **Sabremos que** hemos tenido éxito.

  **Cuando** los usuarios utilicen la función de inventario al menos una vez por semana y reporten mejoras en la gestión de insumos.


- **Hypothesis 04:**

  **Creemos que** los agricultores estarán más satisfechos y fidelizados si reciben asesoría directa de agrónomos desde la plataforma.

  **Sabremos que** hemos tenido éxito.

  **Cuando** la tasa de retención del plan AgroExpert supere el 80% después de seis meses de uso.


- **Hypothesis 05:**

  **Creemos que** los agrónomos podrán brindar recomendaciones más precisas y rápidas si tienen acceso a datos actualizados de los cultivos en Ecotrack.

  **Sabremos que** hemos tenido éxito.

  **Cuando** los agrónomos reporten en entrevistas que la aplicación mejora su trabajo diario y al menos el 60% use la plataforma para consultar datos antes de dar asesorías.


##### 1.2.2.4. Lean UX Canvas

El Lean UX Canvas es una herramienta visual que permite alinear al equipo en torno a problemas, usuarios e hipótesis de manera ágil. En este proyecto se utilizó para comprender mejor a los agricultores y agrónomos, identificar sus necesidades y definir cómo Ecotrack puede generar valor real en su trabajo diario.

Aquí se presenta el Lean UX Canvas desarrollado para Ecotrack:

**Figura 1. Lean UX Canvas de Ecotrack**

![Lean UX Canvas](./assets/images/screenshots/lean-ux-canvas.png)

**Enlace al Lean UX Canvas:** [*Ver en Miro*](https://miro.com/welcomeonboard/cFdpMVVSM1czSlJINm93ZFcyN3R0VWNrKyt1ZVA3K3NNa1BBNHhRdDJsQzFTcjRQbTVSRm1YMzBqaUswUnFieHQ3dHJsbk93eWVVVkovak9aeStNY2EvcDg3VGJkSDlsU1BUbVpLT3U1N3AxekZweHhDb1E0c1h6VjQxa0FxN3h3VHhHVHd5UWtSM1BidUtUYmxycDRnPT0hdjE=?share_link_id=945675870248)

## 1.3. Segmentos objetivo

En el análisis del segmento objetivo para                                                              , hemos previsto que nuestros principales usuarios serán **agricultores y agrónomos.**

### Agricultores

Según el Ministerio de Desarrollo Agrario y Riego (MIDAGRI, 2023) **el 78,5% de las unidades agropecuarias en Perú tienen menos de 5 hectáreas**, lo que refleja la prevalencia de productores de pequeña escala con limitaciones de organización y acceso a mercados. Este grupo requiere soluciones digitales simples que les permitan mejorar la gestión de sus cultivos y profesionalizar sus procesos productivos.

- **Edad:** 25 a 60 años.

- **Necesidad clave:** Organizar cultivos, prevenir riesgos climáticos y mejorar trazabilidad.

- **Nivel educativo:** Organizar cultivos, prevenir riesgos climáticos y mejorar trazabilidad.

- **Uso de tecnología:** Uso básico de teléfonos móviles o computadoras, con necesidad de soluciones adaptadas a su contexto.

### Agrónomos

De acuerdo con Puntel et al. (2022), la adopción de la agricultura digital en Sudamérica aún presenta limitaciones, lo que genera dificultades para acceder a datos confiables y actualizados en el campo. En este contexto, los agrónomos requieren plataformas que centralicen la información y les permitan brindar recomendaciones técnicas más precisas y oportunas.

- **Edad:** 28 a 5 años.

- **Necesidad clave:** Acceso a datos de campo confiables para optimizar asesorías.

- **Nivel educativo:** Profesionales con formación en agronomía o ciencias agrícolas.

- **Uso de tecnología:** Familiarizados con herramientas digitales, pero necesitan soluciones específicas para el sector agro.

# Capítulo II: Requirements Elicitation & Analysis
### 2.1. Competidores
#### Agroptima
Agroptima es una empresa que, desde 2014, desarrolla aplicaciones en la nube para el sector agrícola. Trabaja a la par de un equipo de agricultores, quienes prueban y cooperan en la actualización del programa, esto con la finalidad de poder garantizar su funcionalidad y cumplir con las leyes agrícolas que se encuentran vigentes.


El software Agroptima captura todos los datos del campo fácilmente y permite consultarlos al momento desde cualquier dispositivo independientemente si cuenta con conexión o no. El app permite el trabajo en el campo, donde no hay conexión a internet, y al volver a conectarse a internet se actualiza automáticamente.
#### Auravant
Auravant es una aplicación que proporciona facilidad para el seguimiento de cultivos y para la toma de decisiones, esto con el fin de poder eficientizar productiva, económica y sustentablemente la producción de cultivos.


Esta plataforma facilita el registro y análisis de la información agronómica, también permite el registro y análisis de la gestión para productores asesores y empresas vinculas a la agroindustria. Esto lo logra integrando diversas fuentes de datos como, imágenes satelitales, capas de información georreferenciada, pronósticos y registros de lluvias, entre otras fuentes. Toda esta información se procesa y analiza en una única herramienta, esto evita la duplicidad de datos y permite la trazabilidad de todo el proceso.
#### OneSoil
OneSoil es una plataforma de agricultura de precisión que facilita la gestión de lotes de la forma mas eficiente. OneSoil tiene una aplicación móvil llamada OneSoil Scouting, una aplicación web llama OneSoil y herramientas avanzadas de la versión PRO (Accesibles únicamente mediante suscripción). Estas aplicaciones trabajan de manera conjunta para poder realizar un mejor seguimiento del desarrollo de los cultivos mediante el Índice de Vegetación de Diferencia Normalizada (NDVI), planificar las tareas de campo, mejorar los rendimientos y ahorrar en insumos.


Ambas aplicaciones que ofrece OneSoil se basan en tecnologías de aprendizaje automático, utilizando imágenes de satélite multiespectrales y sus propios algoritmos y desarrollos técnicos.

#### 2.1.1. Análisis competitivo
| Competidor              |                          | EcoTrack                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | Agroptima                                                                                                                                                                                                                                                                                                                                                                                                                      | Auravant                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | OneSoil                                                                                                                                                                                                                                                                                                                                                                                                                        |
|:------------------------|:-------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Logo**                |                          | ![ecotrack](./assets/images/screenshots/ecotrack-logo.png)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | ![agroptima](./assets/images/screenshots/agroptima-logo.jpg)                                                                                                                                                                                                                                                                                                                                                                   | ![auravant](./assets/images/screenshots/auravant-logo.png)                                                                                                                                                                                                                                                                                                                                                                                                                   | ![onesoil](./assets/images/screenshots/onesoil-logo.png)                                                                                                                                                                                                                                                                                                                                                                       |
| **Perfil**              | Overview                 | Aplicación web que ofrece servicios para el seguimiento de cultivos, control de inventario y ganancias y recibir alertar climáticas. Incluyendo modo colaborativo y foros.                                                                                                                                                                                                                                                                                                                                                                     | Aplicación móvil y web en la nube que ofrece servicios para registrar labores, controlar inventario y calcular costos en el campo, incluso sin conexión a internet                                                                                                                                                                                                                                                             | Aplicación móvil y web que ofrece servicios para monitorear cultivos de manera satelital, gestionar datos agronómicos y herramientas de agricultura de precisión.                                                                                                                                                                                                                                                                                                            | Aplicación móvil y web que ofrece los servicios de Monitoreo satelital de cultivos, planificación agrícola y herramientas de precisión para ahorrar insumos y mejorar el rendimiento                                                                                                                                                                                                                                           |
|                         | Ventaja competitiva      | Posee un sistema que permite la gestión de cultivos, inventario y ganancias desde una misma plataforma. Además, ofrece alertas tanto climáticas como de humedad o temperatura, lo que facilita la toma de decisiones en tiempo real. Incorpora un modo colaborativo y foros que fomentan la cooperación entre agricultores. Asimismo, permite visualizar graficas de progreso poder analizar la rentabilidad                                                                                                                                   | Dispone de un cuaderno de campo digital que tiene funciones avanzadas de registro y filtrado de labores, insumos y costos, esto es adaptable a distintos tipos de cultivos. Además, cuenta con la facilidad del funcionamiento sin conexión a internet, lo que permite trabar en el capo y sincronizar los datos al recuperar la conexión a internet. Asimismo, también cuenta con reportes automáticos                        | Integra imágenes satelitales y datos georreferenciados en un sistema de monitoreo lo que permite identificar anomalías en los cultivos y filtrar información por cultivo, lote, índice de vegetación o fecha. Además, ofrece mapas de prescripción para fertilización siembra variable, lo que incrementa la eficiencia productiva                                                                                                                                           | Cuenta con un sistema gratuito y accesible de monitoreo satelital que permite filtrar información por lote, índice NDVI y estado del cultivo. Además, ofrece planificación agrícola mediante mapas de fertilización y siembra variable, ayudando a ahorrar insumos y mejorar el rendimiento. Su aplicación móvil posibilita registrar observaciones como fotos y problemas detectados en campo que complementan la versión web |
| **Perfil de marketing** | Mercado objetivo         | Pequeños y medianos agricultores que busquen digitalizar su producción, así como agrónomos que requieren datos de campo                                                                                                                                                                                                                                                                                                                                                                                                                        | Agricultores profesionales y empresas agrícolas, que buscan digitalizar su gestión de una manera eficiente                                                                                                                                                                                                                                                                                                                     | Productores agrícolas y agrónomos que buscan implementar agricultura de precisión, así como empresas vinculadas al sector agroindustrial                                                                                                                                                                                                                                                                                                                                     | Agricultores (pequeños, medianos y grandes) que estén interesados en implementar un monitoreo satelital.                                                                                                                                                                                                                                                                                                                       |
|                         | Estrategias de marketing | Publicidad en redes sociales, colaborar con expertos ambientales y lideres comunitarios, promover testimonios reales de agricultores.                                                                                                                                                                                                                                                                                                                                                                                                          | Colaboraciones con lideres de opinión en el sector agropecuario                                                                                                                                                                                                                                                                                                                                                                | Publicidad en redes sociales, alianzas con instituciones educativas y empresas del sector, participación en ferias y eventos del sector                                                                                                                                                                                                                                                                                                                                      | Trabaja junto con ONGs, colabora con expertos en tecnología y sostenibilidad para promover el uso de su plataforma, publicidad digital                                                                                                                                                                                                                                                                                         |
| **Perfil de producto**  | Productos y servicios    | Ofrece una plataforma web la cual permite la gestión agrícola de manera digita, conectando tanto a agricultores como productores con herramientas para el seguimiento de cultivos, control de inventario, ganancias y alertas climáticas                                                                                                                                                                                                                                                                                                       | Ofrece una plataforma web y móvil en la nube la cual cumple la función de cuaderno de campo digital, el cual permite registrar labores agrícolas, controlar inventarios y calcular los costos de una manera más eficiente                                                                                                                                                                                                      | Ofrece una plataforma web y móvil la cual permite monitorear los cultivos mediante imágenes satelitales, gestionar los datos agronómicos, tales como lluvias entre otros, generas mapas de prescripción y trazar procesos completos                                                                                                                                                                                                                                          | Ofrece una plataforma web y móvil que permite monitorear cultivos con el índice NDVI utilizando imágenes satelitales, también permite planificar tareas de campo, generar mapas de siembra y fertilización variable y analizar datos climáticos                                                                                                                                                                                |
|                         | Precios y costos         | Los precios varían dependiendo del plan de suscripción seleccionado, esto se adapta a las necesidades de los agricultores. Cuenta con 3 planes escalonados de suscripciones mensuales: AgroStart con un costo de 15 USD, cuenta con funciones básicas como seguimiento de cultivos y alertas climáticas, AgroSmart, el cual cuenta con un costo de 50 USD, este plan incluye más funcionalidades que AgroStart, y AgroExpert, el cual es el plan más completo con un costo de 100 USD, este plan incluye todas las funcionalidades de EcoTrack | Los precios que ofrecen varían dependiendo del número de hectáreas y los módulos contratados. Ofrecen un plan anual de 249 USD el cual incluye el cuaderno de campo digital, inventario y reportes, con actualizaciones en la nube. El registro inicial es gratuito y cuenta con una prueba gratuita por un tiempo limitado. Sin embargo, una vez finaliza este periodo de prueba, es necesario pagar una cuota de suscripción | Ofrecen un plan gratuito el cual cuenta con un acceso básico a imágenes satelitales y monitores de cultivos, también cuenta con planes de pago para poder acceder a funcionalidades más avanzadas como mapas de prescripción, gestión multiusuario y análisis avanzados. El registro, de igual manera, es gratuito y el acceso a la plataforma no tiene costo, pero las funciones avanzadas requieren una suscripción anual la cual va desde los USD 708 hasta los USD 2.028 | OneSoil ofrece un modelo mixto, cuenta con una versión estándar la cual es completamente gratuita, brinda acceso a imágenes satelitales, monitoreo NDVI y gestión básica de lotes. Para acceder a OneSoil PRO se requiere una suscripción de pago, el precio varia dependiendo de la cantidad de hectareas que se maneje, el precio por hectaria va desd los 2 USD hasta los 10 USD anuales.                                   |
|                         | Canales de distribucion  | Aplicaciones web                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Aplicaciones web y móvil                                                                                                                                                                                                                                                                                                                                                                                                       | Aplicaciones web y móvil                                                                                                                                                                                                                                                                                                                                                                                                                                                     | Aplicaciones web y móvil                                                                                                                                                                                                                                                                                                                                                                                                       |
| **análisis SWOT**       | Fortalezas               | Startup integral, accesible y enfocada en pequeños y medianos agricultores, cuenta con planes de pago escalonados que se pueden adaptar a todo tipo de usuarios                                                                                                                                                                                                                                                                                                                                                                                | Plataforma ya reconocida principalmente en Europa, fue desarrollada junto con agricultores reales, cuenta con un soporte confiable y algunas funcionalidades específicas para trazabilidad                                                                                                                                                                                                                                     | Marca en expansión internación gracias a la ayuda de su plan gratuito y la integración de datos satelitales y meteorológicos, además cuenta con alianzas estratégicas con instituciones y empresas agroindustriales                                                                                                                                                                                                                                                          | Ya cuenta con una base global de usuarios, tiene una versión gratuita accesible, es reconocida por su uso innovador de imágenes satelitales y algoritmos de aprendizaje para mejorar la precisión de cultivos                                                                                                                                                                                                                  |
|                         | Debilidades              | Poco reconocimiento y baja visibilidad en el mercado, fuerte competencia con experiencia internacional y sin alianzas que brinden una ventaja competitiva                                                                                                                                                                                                                                                                                                                                                                                      | Dependencia de una suscripción anual, lo que puede llegar a limitar la flexibilidad de pago, además su funcionalidades menos avanzadas en agricultura de precisión                                                                                                                                                                                                                                                             | Tiene una curva de aprendizaje elevada para usuarios que no tienen mucha experiencia en el mundo digital y foco menor en el aspecto financiero o inventario                                                                                                                                                                                                                                                                                                                  | Presencia limitada para soporte técnico en idiomas que no sean ingles o ruso, dependencia de una suscripción PRO para poder sostener su modelo de negocio                                                                                                                                                                                                                                                                      |
|                         | Oportunidades            | Aumento de la digitalización en sectores agrícolas de mercado emergente interesados en soluciones sostenibles, posibilidad de integrar nuevas tecnologías a futuro                                                                                                                                                                                                                                                                                                                                                                             | Incremento de las regulaciones en agricultura que requieren cuadernos digitales lo que le da facilidad para expandirse a nuevos mercados y genera una mayor demanda de soluciones                                                                                                                                                                                                                                              | Expansión a América Latina y Europa gracias al crecimiento de la demanda de soluciones de agricultura digital                                                                                                                                                                                                                                                                                                                                                                | Crecida de la demanda mundial por herramientas gratuitas, crecimiento de la agricultura de precisión en medianos y pequeños productores                                                                                                                                                                                                                                                                                        |
|                         | Amenazas                 | Competencia ya consolidada que cuenta con planes o pruebas gratuitos, posible resistencia tecnología de algunos agricultores                                                                                                                                                                                                                                                                                                                                                                                                                   | Aparición de nuevas plataformas mas económicas, dificultad de adopción digital para pequeños agricultores, creciente presión de competidores con más visibilidad                                                                                                                                                                                                                                                               | Competencia creciente en la agricultura satelital, riesgo de regulaciones con respecto al uso de datos geoespaciales, rápida innovación tecnológica                                                                                                                                                                                                                                                                                                                          | Fuerte competencia en el mercado del monitoreo satelital, depende de financiamiento externo para poder sostener algunas operaciones                                                                                                                                                                                                                                                                                            |

#### 2.1.2. Estrategias y tácticas frente a competidores

Las estrategias competitivas se basan básicamente en poder afrontar el miedo a la falta de seguridad que presentan nuestros segmentos objetivos. Para generar confianza, utilizaremos la transparencia y la comunicación. Lograremos esto al publicar nuestras políticas de privacidad y términos de servicio de manera clara, esto asegurara a los usuarios que nosotros no recopilamos información personal o sensible. De esta manera los usuarios podrán confirmar la seguridad de la aplicación ganando una mayor credibilidad y dándonos así una mejor visibilidad.


Para el lanzamiento, buscaremos principalmente llegar de manera directa al usuario, lograremos esto a través de una plataforma web. Esto nos va a permitir evitar cualquier proceso de aprobación con los que cuentan las tiendas de aplicaciones, además nos va a permitir ofrecer actualizaciones y funcionalidades nuevas de manera inmediata. La prioridad es que la aplicación pueda ser accesible desde cualquier dispositivo y navegador, sin necesidad de ninguna descarga. Esto nos permitirá abarcar un mayor segmento de mercado.


Para afrontar la amenaza de los competidores que ofrecen planes gratuitos, nuestra estrategia se diferenciara en nuestra propuesta de valor. Mientras la competencia ofrece servicios básicos sin costos para tratar de atraer usuarios, nosotros ofrecemos un plan escalonado y accesible que justifique su valor. Nuestra plataforma proporcionara funcionalidades como el seguimiento de cultivos, un control tanto de inventario y ganancias y un análisis de datos más profundo, así como alertas climáticas y un modo colaborativo, lo que nos diferenciara de aplicaciones como “Agroptima”, “Auravent” o “OneSoil”. Esta táctica nos permitirá capturar usuarios sensibles al costo, también podremos demostrar el retorno de inversión que obtienen al elegir nuestra aplicación, posicionándonos como una de las opciones mas rentables para los agricultores a largo plazo
## 2.2. Entrevistas

Esta sección expone la investigación basada en entrevistas realizadas a agricultores y agrónomos, segmentos clave del proyecto. A través de sus testimonios se buscó identificar las principales dificultades en la gestión agrícola y explorar cómo una solución digital podría responder de manera efectiva a sus necesidades.

### 2.2.1. Diseño de entrevistas

Las entrevistas fueron diseñadas con el objetivo de explorar en profundidad las prácticas, necesidades y dificultades de agricultores y agrónomos. A través de preguntas principales y complementarias se buscó obtener información demográfica, tecnológica y de gestión, que permita construir arquetipos representativos y validar la pertinencia de una solución digital como EcoTrack.

### Segmento 1: Agricultores

#### Gestión agrícola actual

- ¿Cómo organizas tus actividades en la parcela día a día?

- ¿Qué herramientas utilizas para registrar información sobre tus cultivos (libretas, Excel, ninguna)?

- ¿Sueles planificar la siembra, riego o cosecha con anticipación? ¿Cómo lo haces?

#### Monitoreo y control

- ¿Cómo haces seguimiento al crecimiento de tus plantas (conteo de hojas, botones, frutos,tamaño, etc.)?

- ¿Qué información te sería útil recibir en reportes para mejorar tu producción?

- ¿Qué tan fácil es para ti acceder a un agrónomo cuando necesitas apoyo en el campo?

#### Uso de tecnología

- ¿Usas el celular u otro dispositivo para apoyar tu trabajo agrícola?

- ¿Has probado alguna herramienta digital relacionada con agricultura? ¿Qué te gustó o no?

#### Dolores y frustraciones

- ¿Qué es lo más complicado de gestionar tus cultivos?

- ¿Cómo te afecta no tener datos organizados de tu parcela?

#### Expectativas 

- Si tuvieras una aplicación para apoyarte en la gestión agrícola, ¿qué problemas te gustaría que te ayude a resolver?

- ¿Qué tipo de información o apoyo te sería más útil recibir en una aplicación agrícola?

- ¿Estarías dispuesto a aprender a usar una aplicación si esta te ayuda a mejorar la gestión de tus cultivos?

- ¿Qué necesitarías para sentirte cómodo usando una aplicación agrícola (capacitación, soporte, facilidad de uso)?

### Segmento 2: Agrónomos

#### Trabajo actual

- ¿Cómo recopilas la información de las parcelas que supervisas?

- ¿Qué métodos usas para dar recomendaciones a agricultores?

- ¿Con qué frecuencia visitas a tus clientes o parcelas?

#### Herramientas y procesos

- ¿Qué herramientas digitales (si alguna) usas actualmente para tu trabajo?

- ¿Cómo te comunicas con los agricultores (WhatsApp, llamadas, correo)?

- ¿Qué tipo de reportes o datos sueles preparar para tus clientes?

#### Problemas y limitaciones

- ¿Qué es lo más difícil al dar asesoría a agricultores?

- ¿Qué consecuencias tiene para ti no contar con información confiable o actualizada?

- ¿Qué obstáculos encuentras al transmitir tus recomendaciones a agricultores?

#### Tecnología y digitalización 

- ¿Has probado apps o sistemas digitales para agricultura? ¿Cómo fue tu experiencia?

- ¿Qué funcionalidades valoras más en un sistema para dar asesoría técnica?

#### Expectativas

- Si contaras con una herramienta digital para tu labor, ¿qué funciones te facilitarían el trabajo con los agricultores?

- ¿Qué tipo de datos o reportes consideras indispensables para brindar recomendaciones más precisas?


### 2.2.2. Registro de entrevistas


### SEGMENTO AGRICULTOR:
#### Entrevista 1:

|              Atributo               | Detalle                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|:-----------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|               Nombre                | Rommer Tuesta                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|                Edad                 | 62 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|              Distrito               | Santiago de Surco                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|              Ocupación              | Emprendedor agricultor                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|         Fecha de entrevista         | 09 de Setiembre del 2025                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|               Timing                | 00:00:00 - 00:15:09                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|        Enlace a la grabación        | [*Ver en Microsoft Stream*](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g044_upc_edu_pe/EWIynez_N45IjdJ6JFNpOusBxo9mDCzON9DF0V6rEsRh9A?e=S7WqUn)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Captura de pantalla de la grabación | ![Entrevista-1](assets/images/agricultor_img_rommer.PNG)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|               Resumen               | Rommer comenta que utiliza principalmente la aplicación Whatsapp en su celular para mantener registro de los avances, trabajos, etc. que se realicen en las plantas, algunas veces, pasa la información de su celular a Excel o Word, pero que no cuenta con una aplicación determinada para esto. Con respecto al trabajo diario, manifiesta que se organizan de manera semanal para cumplir con las necesidades de cuidado de las plantas, asigna las tareas por medio de Whatsapp y manteniene record de esto mismo en la misma aplicación. Además, expresó que desearía conocer con exactitud la ubicación de cada planta con un tablero y mantener un registro de las caracteristicas principales de cada planta como tamaño, ramaje, etc. Cuenta con el trabajo de un agrónomo y a su vez con asesoría de un grupo de agrónomos que son proporcionados por la empresa que compra el producto cocechado. Finalmente, menciona que estaría dispuesto a utilizar una solución tecnológica si es que esta es sencilla y llamativa de usar. |

#### Entrevista 2:

|              Atributo               | Detalle                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|:-----------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|               Nombre                | Miguel Naito                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|                Edad                 | 53 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|              Distrito               | Lima                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|              Ocupación              | Paisajista                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|         Fecha de entrevista         | 10 de Setiembre del 2025                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|               Timing                | 00:15:10 - 00:40:46                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|        Enlace a la grabación        | [*Ver en Microsoft Stream*](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g044_upc_edu_pe/EWIynez_N45IjdJ6JFNpOusBxo9mDCzON9DF0V6rEsRh9A?e=S7WqUn)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Captura de pantalla de la grabación | ![Entrevista-2](assets/images/agricultor_img_miguel.PNG)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|               Resumen               | Miguel, comentó que durante la época de cultivo de arándanos se solía utilizar hojas impresas con los planos y posición de cada planta, en estas registraban las caracteristicas de cada una, esto debido a que existía la posibilidad de malograr los dispositivos electrónicos en el barro o averiar de alguna manera, lo cual generaría costo extra y posible pérdida de información valiosa; Realizaban la planificación de la siembra, cosecha, desplantación, abono, etc. anual, mensual y semanalmente. La tecnología que utilizaban eran sensores de tierra que mandaban alertas casi a tiempo real. Expresó que podria utilizar una aplicación dirigida a la gestión agrícola siempre y cuando sea fácil de usar, intuitiva, especifica para cada cultivo y rápida.|

#### Entrevista 3:

|              Atributo               | Detalle                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|:-----------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|               Nombre                | Erica Marin                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|                Edad                 | 45 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|              Distrito               | Santiago de Surco                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|              Ocupación              | Emprendedor agricultor - administrador                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|         Fecha de entrevista         | 12 de Setiembre del 2025                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|               Timing                | 00:00:00 - 00:15:09                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|        Enlace a la grabación        | [*Ver en Microsoft Stream*](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g044_upc_edu_pe/EWIynez_N45IjdJ6JFNpOusBxo9mDCzON9DF0V6rEsRh9A?e=S7WqUn)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Captura de pantalla de la grabación | ![Entrevista-3](.png)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|               Resumen               | Erica comenta que utiliza ocasionalmente Excel en su computadora para llevar el registro de los avances, tareas y actividades realizadas en las plantas. En ocasiones, complementa esta información trasladándola a documentos en Word. En cuanto a la organización del trabajo diario, explica que planifican las labores de forma semanal para atender las necesidades de cuidado de las plantas, asignando las tareas en Excel y manteniendo allí el registro de las mismas. Además, manifestó que le gustaría contar con un tablero que le permita visualizar con precisión la ubicación de cada planta y registrar sus principales características, como tamaño, ramaje, entre otras. Actualmente trabaja con un agrónomo y recibe asesoría de un grupo de especialistas proporcionados por la empresa compradora de la cosecha. Finalmente, mencionó que estaría dispuesto a adoptar una solución tecnológica siempre que sea sencilla y en el que no deba de invertir mucho en capacitación del personal.|




#### Segmento 2: Agrónomos

#### Entrevista 1:

|              Atributo               | Detalle                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|:-----------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|               Nombre                | Luis Mendoza                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|                Edad                 | 30 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|              Distrito               | Villa el Salvador                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|              Ocupación              | Ingeniero Agrónomo                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|         Fecha de entrevista         | 06 de Setiembre del 20245                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|               Timing                | 40:46 - 48:23                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|        Enlace a la grabación        | [*Ver en Microsoft Stream*](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g044_upc_edu_pe/EWIynez_N45IjdJ6JFNpOusBxo9mDCzON9DF0V6rEsRh9A?e=FnurJA&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6MjQ0OC4xfX0%3D)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Captura de pantalla de la grabación | ![Entrevista-2](assets/images/screenshots/entrevista-agronomo-3.png)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|               Resumen               | Luis comenta que utiliza su celular para anotar en el bloc de notas los conteos que realiza y luego transfiere la información a Excel. Señala que, en ocasiones, resulta complicado trabajar con los agrónomos, ya que muchos no cuentan con conocimientos especializados sobre el suelo y otros aspectos técnicos. Considera que lo ideal sería realizar visitas semanales, y en su labor prepara reportes sobre análisis de suelo, consumo de agua y estudios meteorológicos. También menciona que los agricultores suelen mostrarse reacios a incorporar nuevos conocimientos. En el pasado probó una aplicación que solo permitía registrar conteos, pero no le resultó útil porque funcionaba prácticamente como un bloc de notas. Para él, sería valioso contar con una aplicación que le permita registrar información más completa y que, además, facilite la comunicación directa con los agricultores. |


#### Entrevista 2:

|              Atributo               | Detalle                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|:-----------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|               Nombre                | Lucas Aliaga                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|                Edad                 | 24 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|              Distrito               | Jicamarca                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|              Ocupación              | Ingeniero Agrónomo                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|         Fecha de entrevista         | 05 de  Setiembre del 2025                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | 
|               Timing                | 48:23 - 01:05:59                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|        Enlace a la grabación        | [*Ver en Microsoft Stream*](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g044_upc_edu_pe/EWIynez_N45IjdJ6JFNpOusBxo9mDCzON9DF0V6rEsRh9A?e=hsBPPh&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6MjkwOS4yMn19)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| Captura de pantalla de la grabación | ![Entrevista-3](assets/images/screenshots/entrevista-agronomo-2.png)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|               Resumen               | Lucas comenta que, para recopilar información, debe necesariamente acudir al lugar. Su trabajo se enfoca en el control de plagas y en la selección de productos adecuados para resolver esos problemas. Generalmente, realiza visitas al campo una vez o cuando lo llaman. Actualmente no utiliza ninguna aplicación digital que le ayude a registrar sus datos y señala que resulta complicado conectar con los agricultores al intentar enseñarles nuevas prácticas. Sin embargo, percibe una oportunidad de mejora en los jóvenes, quienes muestran mayor disposición a adaptarse a los cambios y a mejorar los procesos. En el pasado probó una aplicación que brindaba información sobre insecticidas y sus componentes, pero no fue suficiente para sus necesidades. Para él, sería valioso contar con una aplicación que le permita conocer el tipo de suelo, las condiciones climáticas y la información básica de los cultivos en cada parcela. Además, considera útil que la app ofrezca gráficos de barras para representar los datos recopilados. |

#### Entrevista 3:


|              Atributo               | Detalle                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|:-----------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|               Nombre                | Sofia Riquez Esteban                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|                Edad                 | 25 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|              Distrito               | San Mateo de Otao                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|              Ocupación              | Ingeniera Agrónoma                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|         Fecha de entrevista         | 05 de Setiembre del 2025                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|               Timing                | 01:00:08 - 01:05:44                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|        Enlace a la grabación        | [*Ver en Microsoft Stream*](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g044_upc_edu_pe/EWIynez_N45IjdJ6JFNpOusBxo9mDCzON9DF0V6rEsRh9A?e=L84IuG&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6MzYwOS4zOH19)                                                                                                                                                                                                                                                                                                      |
| Captura de pantalla de la grabación | ![Entrevista-1](assets/images/screenshots/entrevista-agronomo-1.png)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|               Resumen               | Sofía comenta que realiza el recuento de datos utilizando plataformas como Excel y Python. Su trabajo se centra en identificar plagas, enfermedades de las plantas y en evaluar el estado del suelo de cada parcela. Generalmente, realiza visitas de campo cada 15 días o una vez al mes, lo que le lleva a manejar una gran cantidad de información por parcela. Sin embargo, enfrenta conflictos con los agricultores, ya que muchos suelen confiar únicamente en sus propios conocimientos. Además, las aplicaciones que ha probado hasta ahora no le han resultado útiles. Para ella, sería valioso contar con una aplicación que le permita registrar la información necesaria y recibir alertas sobre el clima. |


#### 2.2.3. Análisis de entrevistas

**Total de entrevistados:**  3
**Edades:** 62, 53, 45
**Distritos:** Santiago de Surco, Lima

#### Características objetivas

**Uso de herramientas digitales básicas (WhatsApp, Excel, Word):** 100% (3/3) utilizan herramientas simples para registrar y organizar datos, sin plataformas especializadas para el manejo de cultivos.

**Planificación y registro manual en campo:** 33% (1/3: Miguel) emplea hojas impresas con planos y registros físicos de cada planta para evitar daños a dispositivos electrónicos.

**Organización de tareas agrícolas planificada:** 100% (3/3) planifican las actividades agrícolas (siembra, cosecha, abono, etc.) de manera semanal, mensual o anual.

**Uso de tecnología de monitoreo ambiental:** 33% (1/3: Miguel) utiliza sensores de tierra que envían alertas casi en tiempo real sobre el estado del terreno.

**Asesoría profesional externa:** 100% (2/2) cuentan con agrónomos, Miguel es agrónomo de profesión, y asesores externos proporcionados por la empresa compradora en el caso de Rommer y Erica.

#### Características subjetivas

**Percepción de riesgo en el uso de dispositivos electrónicos en campo:** 33% (1/3: Miguel) evita dispositivos electrónicos en campo por temor a que se dañen y se pierda información valiosa.

**Deseo de centralizar y organizar la información agrícola:** 100% (3/3) expresan la necesidad de tener una plataforma única para registrar y consultar datos de sus plantas y tareas.

**Valoración de una interfaz sencilla, rápida y llamativa:** 100% (3/3) señalan que usarían una aplicación si es fácil de usar, intuitiva y visualmente atractiva.

**Interés en la identificación individual de plantas:** 100% (3/3) consideran importante registrar las características principales (tamaño, ramaje, etc.) y la ubicación exacta de cada planta.

**Valoración de baja necesidad de capacitación:** 33% (1/3: Erica) indica que adoptaría una solución tecnológica solo si no requiere invertir mucho en capacitar al personal.

**Disposición positiva hacia nuevas tecnologías agrícolas:** 100% (3/3) están abiertos a adoptar una solución tecnológica si satisface sus expectativas de usabilidad y simplicidad.



### Segmento: Agrónomos
**Total de entrevistados:** 3  
**Edades:** 25, 30, 24  
**Distritos:** San Mateo de Otao, Villa El Salvador, Jicamarca

#### Características objetivas
- **Uso de herramientas digitales básicas (Excel, bloc de notas, etc.):** 100% (3/3) usan herramientas simples para registrar datos, sin plataformas especializadas.
- **Visitas de campo frecuentes:** 100% (3/3) realizan visitas para recopilar información, aunque con distinta frecuencia (cada 15 días, semanal o cuando los llaman).
- **Enfoque en análisis técnico (plagas, suelo, clima, agua):** 100% (3/3) centran su labor en recopilar información técnica de los cultivos.
- **Aplicaciones digitales probadas sin éxito:** 100% (3/3) han probado apps, pero no les fueron útiles por ser limitadas o poco funcionales.

#### Características subjetivas
- **Conflicto con agricultores reacios al cambio:** 100% (3/3) mencionan que los agricultores suelen desconfiar o resistirse a nuevos conocimientos.
- **Valoración de una app más completa y práctica:** 100% (3/3) coinciden en que necesitan una app que les permita registrar datos relevantes (clima, suelo, plagas, cultivos).
- **Interés en funciones específicas adicionales:**
    - 67% (2/3) valoran información climática en tiempo real.
    - 33% (1/3) destaca la necesidad de comunicación directa con los agricultores.
    - 33% (1/3) menciona la utilidad de gráficos visuales (barras) para mostrar datos.
- **Reconocimiento de oportunidades en jóvenes agricultores:** 33% (1/3: Lucas) percibe que los jóvenes son más receptivos a adaptarse al cambio tecnológico.


## 2.3. Needfinding
### 2.3.1. User Personas
Segmento Objetivo #1: Agricultores

![Agricultores](./assets/images/screenshots/Juan%20Carlos.png)

Segmento Objetivo #2: Agrónomos

![Agrónomos](./assets/images/screenshots/Ana%20Morales.png)

### 2.3.2. User Task Matrix

Segmento Objetivo #1: Juan Carlos (Agricultor de pequeña escala)

| Tarea | Frecuencia | Importancia |
|-------|------------|-------------|
| Registrar labores agrícolas (riego, fertilización, cosecha) | Alta | Alta |
| Organizar costos de producción e insumos (semillas, fertilizantes, agua) | Media | Alta |
| Planificar cultivos y campañas agrícolas futuras | Media | Alta |
| Recibir alertas sobre clima y riesgos de plagas/enfermedades | Media | Alta |
| Registrar rendimientos de cosecha (volumen, calidad) | Media | Alta |
| Llevar el control de inventario de insumos | Media | Alta |
| Acceder a información de trazabilidad para comercialización | Baja | Alta |
| Consultar historial de actividades y compararlo con campañas anteriores | Baja | Media |
| Compartir información con agrónomos o asociaciones | Baja | Media |
| Revisar tutoriales o capacitaciones dentro de la app | Baja | Media |

Segmento Objetivo #2: Ana Morales (Ingeniera Agrónoma independiente)

| Tarea | Frecuencia | Importancia |
|-------|------------|-------------|
| Revisar datos de campo actualizados en tiempo real | Alta | Alta |
| Dar recomendaciones técnicas (riego, fertilización, control de plagas) | Alta | Alta |
| Generar reportes técnicos y de trazabilidad para clientes | Media | Alta |
| Comparar información entre distintos agricultores/cultivos | Media | Alta |
| Supervisar el cumplimiento de labores agrícolas registradas | Media | Alta |
| Centralizar información dispersa de múltiples clientes en un solo sistema | Media | Alta |
| Contactar agricultores para aclarar dudas o coordinar | Media | Media |
| Analizar alertas de clima o riesgos para anticipar problemas | Media | Alta |
| Organizar su agenda de visitas y asesorías | Alta | Media |
| Capacitar agricultores en buenas prácticas agrícolas | Baja | Media |
| Buscar nuevos agricultores para asesorar y ampliar su red de clientes | Baja | Media |

### 2.3.3. User Journey Mapping

Segmento Objetivo #1: Juan Carlos (Agricultor de pequeña escala)

![AgricultorMap](./assets/images/screenshots/UserJourneyMappingJuan.png)

Segmento Objetivo #2: Ana Morales (Ingeniera Agrónoma independiente)

![AgronomoMap](./assets/images/screenshots/UserJourneyMapping2.png)

### 2.3.4. Empathy Mapping

Segmento Objetivo #1: Juan Carlos (Agricultor de pequeña escala)

![AgricultorEmpathyMap](./assets/images/screenshots/Juan%20Carlos%20(3).png)

Segmento Objetivo #2: Ana Morales (Ingeniera Agrónoma independiente)

![AgronomoEmpathyMap](./assets/images/screenshots/Ana%20Morales%20(1).png)
## 2.4. Big Picture EventStorming

En esta sección se introduce y resume el proceso realizado por el equipo para el Big Picture Event Storming, que fue <br>
realizado mediante una llamada en discord y plasmado con la ayuda de la herramienta Miro. A continuación, se explica el proceso <br>

**1. Open:**<br>
En esta etapa el equipo se concentró en generar la mayor cantidad de eventos de dominio posibles (cosas que suceden <br>
en el negocio) escribiendo en los post-its naranjas.

![Step 1 Big Picture Event Storming](./assets/images/big-picture-event-storming/big-picture-event-storming-step-1.png)

**2. Explore:** <br>
Después de la anterior etapa, en esta se concentró en ordenar cronológicamente los eventos, eliminar los eventos repetidos,<br>
identificar sus actores y posibles sistemas externos, y finalmente algunos puntos de dolor en post-its morados.

![Step 2 Big Picture Event Storming](./assets/images/big-picture-event-storming/big-picture-event-storming-step-2.png)

**3. Close:** <br>
En esta última etapa, se documentaron en post-its rosados los problemas más relevantes detectados,junto con aspectos que <br>
debíamos investigar más a fondo o descartar según el alcance definido.

![Step 3 Big Picture Event Storming](./assets/images/big-picture-event-storming/big-picture-event-storming-step-3.png)

Luego de conversar un poco, el equipo descartó algunos eventos y identificó mejor un sistema externo:

![Final events of Big Picture Event Storming](./assets/images/big-picture-event-storming/big-picture-event-storming-final-events.png)

Finalmente, se presenta el Big Picture Event Storming:

![Big Picture Event Storming](./assets/images/big-picture-event-storming/big-picture-event-storming.png)

[Enlace del Miro donde se realizó el Big Picture Event Storming](https://miro.com/welcomeonboard/Tkt0b0FqK3BGdThsbmVRKytveUdDdTBMeHZtNW52aTcvaHBHQ3dKYTlCS2FzMlhLYVZhNnAwaHpkRHNhOTlTSzFLRVhFeW5JQlZJck5hUzNBSlMrbVpqbVB1M3ErOFNsY0hQTDNXbStrSXNJbm5hNzA1eStxcDJpN25MMGJDSy9nbHpza3F6REdEcmNpNEFOMmJXWXBBPT0hdjE=?share_link_id=550038408018)

Este proceso permitió al equipo obtener una visión de alto nivel de los principales eventos del negocio, identificar puntos <br>
críticos y definir prioridades para las siguientes etapas del proyecto

## 2.5. Ubiquitous Language

**Farmer(Agricultor)**  
Persona que se dedica a trabajar la tierra y cultivar alimentos, ya sea para una empresa o para sustento propio.


**Agronomist(Agrónomo)**  
Profesional que trabaja a par con los Agricultores y les brinda asesoría experta sobre técnicas de cultivo, fertilización, protección contra plagas y enfermedades. Así mismo, les ayuda a gestionar sus recursos y evalúan la salud y rendimiento de sus cultivos.

**Plot(Parcela)**  
Porción de tierra que mide entre 100 y 500 metros cuadrados, donde se siembra un tipo de cultivo y representa un espacio delimitado para registrar observaciones sobre los cultivos.


**Crop (Cultivo):**  
Conjunto de plantas de un mismo tipo sembradas en una parcela.

**Plant(Planta)**  
Ejemplar individual o muestra representativa de un cultivo en una parcela.  
Se utiliza para registrar observaciones específicas como altura o cantidad de hojas.

**Organization(Organización)**    
Espacio de trabajo colaborativo entre el agrónomo y varios agricultores asignados en varias parcelas

**Monitoring(Monitoreo)**  
Es la revisión del entorno donde crece el cultivo como la temperatura, humedad o pH del suelo.


**Activity management (Gestión de actividades)**  
Es la gestión de tareas dejadas por el agrónomo a realizar en una o varias parcelas, donde también se registra el material empleado dado el caso.

# Capítulo III: Requirements Specification
## 3.1. User Stories

Las user stories representan los *requisitos funcionales* de **Ecotrack** desde la perspectiva de los Agricultores y los Agrónomos. Cada historia de usuario desceribe una interaccion especifica que los usuarios necesitan realizar, como registrar cultivos o crear organizaciones. Estas historias se desglozan en tareas conceretas que guiaran el desarrollo de la plataforma, asegurando que se cumplan con las necesidades reales y expectativas de los usuarios finales, y que EcoTrack brinde una experiencia eficiente, justa y centrada en el valor de las conexiones profesionales

| User Story | Titulo                                        | Descripción                                                                                                                                                | Criterios de aceptación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | Epic ID |
|------------|-----------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------|
| US01       | Crear organización                            | Como Agrónomo, quiero crear una organización para centralizar miembros y parcelas                                                                          | Escenario 1: Organización creada<br/> Dado que el Agrónomo no tiene organizaciones y esta autenticado, cuando crea una organización con nombre a elección y datos validos obligatorios (rubro, país y nombre), entonces el sistema registra la organización con una organizationID y asigna el rol de Owner al Agrónomo<br/>  Escenario 2: Error e n la creación de la organización<br/> Dado que el Agrónomo esta autenticado, cuando envía el formulario sin nombre o con caracteres inválidos, entonces el sistema muestra “Algunos campos están vacíos o son incorrectos”                                                                                                                                                                        | EP02    |
| US02       | Invitar miembros a organización               | Como Agrónomo, quiero enviar invitaciones a los agricultores para poder sumarlos a mi organización                                                         | Escenario 1: Invitación enviada correctamente<br/> Dado que el Agrónomo es Owner de la organización, cuando selecciona desde la app a un Agricultor registrado en el sistema y envía una invitación, entonces el sistema crea la invitación con un estado Pendiente mostrando el mensaje “Invitación enviada”, y la invitación le aparece en la sección de notificaciones al Agricultor<br/>  Escenario 2: Agricultor acepta la invitación<br/> Dado que el Agricultor tiene una invitación pendiente en el app, cuando abre la invitación y presiona “Aceptar”, entonces el sistema agrega al Agricultor a la organización con el rol “Farmer”, y cambia el estado de la invitación a Aceptada, y notifica al Agrónomo que el Agricultor se unió.   | EP02    |
| US03       | Remover Agricultor de la organización         | Como Agrónomo, quiero eliminar a un agricultor para mantener el equipo al día                                                                              | Escenario 1: Remoción exitosa<br/> Dado que el Agrónomo es Owner y la organización tiene Agricultores, cuando el Agrónomo selecciona a un Agricultor y confirma la acción de eliminar, entonces el sistema lo elimina de la lista de miembros y muestra “Miembro eliminado”<br/>  Escenario 2: Cancelación de la eliminación<br/> Dado que el Agrónomo selecciona a un agricultor para eliminar, cuando cancela la acción en el cuadro de confirmación, entonces el sistema mantiene al Agricultor en la lista de miembros                                                                                                                                                                                                                           | EP02    |
| US04       | Bitácora de parcela                           | Como agricultor, quiero una bitácora por parcela para registrar riegos, fertilizaciones y labores, y asi llevar el control de lo que sucede en ese terreno | Escenario 1: Registrar actividad y adjuntar evidencia<br/> Dado que una parcela se encuentre activa, cuando se agregue una actividad como "Riego" con fecha, duración y volumen, y adjunto de una foto, entonces la actividad aparece en línea de tiempo de la parcela <br/> Escenario 2: Consulta cronológico<br/> Dado que el agricultor consulta la bitácora de una parcela, cuando visualiza la información, entonces puede ver todas las actividades ordenadas cronológicamente                                                                                                                                                                                                                                                                 | EP03    |
| US05       | Recomendaciones técnicas                      | Como agrónomo, quiero registrar recomendaciones vinculadas al cultivo para poder orientar al agricultor                                                    | Escenario 1: Registro<br/> Dado que selecciono un cultivo, cuando añado una recomendación, entonces el agricultor la visualiza en su perfil<br/>  Escenario 2: Organización por prioridad<br/> Dado que el agrónomo registra varias recomendaciones en un cultivo, cuando asigna un nivel de prioridad (alta, media o baja), entonces el agricultor puede visualizarla en orden según su prioridad                                                                                                                                                                                                                                                                                                                                                   | EP06    |
| US06       | Historial de cultivo                          | Como agricultor, quiero consultar el historial de un cultivo para poder demostrar su trazabilidad                                                          | Escenario 1: Visualización<br/> Dado que selecciono un cultivo cuando abro su historial veo todas las recomendaciones registradas, labores e insumos<br/>  Escenario 2: Filtrado de información<br/> Dado que el agricultor consulta el historial de un cultivo, cuando aplica un filtro, entonces puede visualizar actividades y/o datos por tipo de labor o rango de fechas                                                                                                                                                                                                                                                                                                                                                                        | EP03    |
| US07       | Alertas climáticas                            | Como agricultor, quiero recibir alertas por lluvia/helada/ola de calor para prevenir pérdidas.                                                             | Escenario 1: Recepción de alerta por umbral climático<br/> Dado que la temperatura máxima esté configurada Y el pronóstico local supere el límite, cuando el sistema evalúa el pronóstico, entonces se envía una notificación push y/o SMS con recomendación de acción<br/>  Escenario 2: Detalle de la alerta<br/> Dado que el agricultor recibe una alerta climática, cuando la abre, entonces visualiza la hora y el detalle que genero la alerta                                                                                                                                                                                                                                                                                                 | EP06    |
| US08       | Acceso multiplataforma                        | Como agricultor, quiero acceder a EcoTrack desde el celular y la computadora para consultar y registrar datos en cualquier lugar                           | Escenario 1: Inicio de sesión<br/> Dado que ingreso desde un navegador móvil o de PC, cuando ingreso a la URL puedo iniciar sesión y utilizar todas las funciones<br/>  Escenario 2: Sincronización de datos<br/> Dado que el agricultor accede desde distintos dispositivos, cuando genera algún cambio, entonces la información se mantiene sincronizada                                                                                                                                                                                                                                                                                                                                                                                           | EP05    |
| US09       | Ficha técnica de cultivo                      | Como agrónomo, quiero exportar fichas técnicas por cultivo con métricas y recomendaciones.                                                                 | Escenario 1: Generar una ficha<br/> Dado que se proporcionan datos históricos de clima, suelo y productividad, cuando se generé la ficha del cultivo, entonces el documento incluirá las anomalías presentes y recomendaciones.<br/>  Escenario 2: Envío por correo electrónico<br/>  Dado que el agrónomo genera una ficha técnica de cultivo, cuando selecciona la opción de compartir, entonces el sistema envía la ficha en formato PDF directamente al correo electrónico del agrónomo o del destinatario                                                                                                                                                                                                                                       | EP06    |
| US10       | Creación de parcela                           | Como Agrónomo, quiero crear un parcela para gestionar el cultivo y su monitoreo                                                                            | Escenario 1: Creación exitosa<br/> Dado que el Agrónomo tiene una organización, cuando completa el formulario de la parcela con nombre, área, y ubicación con datos válidos, entonces el sistema registra la parcela con un ID único y muestra el mensaje “Parcela creada”<br/>  Escenario 2: Datos inválidos<br/> Dado que el Agrónomo tiene una organización, cuando ingresa un área menor a 1 o deja algún campo vacío, entonces el sistema rechaza la creación y muestra el mensaje “Datos inválidos”                                                                                                                                                                                                                                            | EP03    |
| US11       | Modificación de parcela                       | Como Agrónomo, quiero modificar una parcela para mantener los datos correctos                                                                              | Escenario 1: Modificación exitosa<br/> Dado que la parcela ya existe en la organización, cuando el Agrónomo actualiza el área y/o la ubicación con datos válidos, entonces el sistema actualiza los datos guardando los cambios y muestra “Parcela actualizada”<br/>  Escenario 2: Datos inválidos<br/> Dado que la parcela existe, cuando el Agrónomo ingresa un área negativa o una ubicación invalida, entonces el sistema rechaza la acción y muestra “Datos de parcela inválidos”                                                                                                                                                                                                                                                               | EP03    |
| US12       | Registrar tipo de cultivo por parcela         | Como Agrónomo, quiero escoger un tipo de cultivo para personalizar el monitoreo y recomendaciones                                                          | Escenario 1: Asignación exitosa<br/> Dado que el Agrónomo tiene acceso a la parcela, cuando selecciona “Arándano” de la lista de cultivos disponibles, entonces el sistema asigna ese cultivo a la parcela y habilita configuraciones de monitoreo relacionadas<br/>  Escenario 2: Cultivo no valido<br/> Dado que la lista de cultivos disponibles no incluye “X”, cuando el agrónoma trata de seleccionarlo, entonces el sistema rechaza la acción y muestra “El cultivo seleccionado no es válido”  Escenario 3: Reasignación con historial Dado que la parcela ya tiene un cultivo asignado, cuando el Agrónomo quiere cambiar el tipo de cultivo, entonces el sistema actualiza el cultivo y guarda un historial de cambios con fecha y usuario | EP03    |
| US13       | Registro de Cultivo                           | Como agricultor, quiero registrar cultivos/parcelas y actividades diarias para organizar mi producción.                                                    | Escenario 1: Crear cultivo con metadatos mínimos<br/> Dado que ingrese a "Mis Cultivos", cuando registre un cultivo con nombre, ubicación, superficie y fecha de siembra, entonces se visualizará el cultivo en la lista con estado "Activo", y el sistema guardará la georreferenciación<br/>  Escenario 2: Confirmación de registro<br/> Dado que el agricultor finaliza el registro de un cultivo, cuando guarda los datos, entonces recibe un mensaje de confirmación indicando que el cultivo fue creado exitosamente                                                                                                                                                                                                                           | EP03    |
| US14       | Editar/Eliminar registro                      | Como Agricultor, quiero eliminar o editar algún registro para corregir errores                                                                             | Escenario 1: Edición valida<br/> Dado que existe un registro reciente, cuando el Agricultor actualiza la información, entonces el sistema guarda los cambios y conserva un historial de modificaciones<br/>  Escenario 2: Eliminación valida<br/> Dado que existe un registro propio, cuando el Agricultor confirma su eliminación, entonces el sistema lo elimina y muestra un mensaje de confirmación                                                                                                                                                                                                                                                                                                                                              | EP03    |
| US15       | Crear una checklist                           | Como Agrónomo, quiero crear una checklist para estandarizar labores en una parcela                                                                         | Escenario 1: Creación exitosa<br/> Dado que el Agrónomo tiene registrada una parcela y tiene acceso a ella, cuando registra una checklist con nombre e ítems, entonces el sistema guarda el checklist asociado a la parcela<br/>  Escenario 2: Datos incompletos<br/> Dado que el Agrónomo intenta crear una checklist, cuando no agrega ítems o nombre, entonces el sistema rechaza la acción y muestra un mensaje de error                                                                                                                                                                                                                                                                                                                         | EP04    |
| US16       | Creación de tareas                            | Como Agrónomo, quiero crear tareas (con responsable, fecha y prioridad) para poder planificar el trabajo                                                   | Escenario 1: Creación exitosa <br/>Dado que el Agrónomo tiene una parcela, cuando crea una tarea con responsable, fecha y prioridad, entonces el sistema guarda la tarea como pendiente y envía una notificación al Agricultor asignado<br/>  Escenario 2: Datos faltantes<br/> Dado que el Agrónomo crea una tarea, cuando no indica al responsable, la fecha o la prioridad, entonces el sistema rechaza la creación y muestra un mensaje de error                                                                                                                                                                                                                                                                                                 | EP04    |
| US17       | Recordatorio de tareas                        | Como agricultor, quiero recibir un recordatorio de actividades programadas para no olvidarlas                                                              | Escenario 1: Recordatorio<br/> Dado que el Agricultor programo una tarea con fecha, cuando se acerca el día, entonces recibo un recordatorio en una notificación push mostrando “La fecha de tu tarea se está acercando”<br/>  Escenario 2: Configuración de recordatorio<br/>  Dado que el agricultor programa una actividad, cuando define un intervalo de aviso (por ejemplo, 1 hora antes), entonces el sistema envía el recordatorio en el momento especificado                                                                                                                                                                                                                                                                                 | EP04    |
| US18       | Iniciar tarea                                 | Como Agricultor, quiero iniciar la tarea para registrar que empecé a ejecutarla                                                                            | Escenario 1: Aceptación e inicio<br/> Dado que existe una tarea pendiente asignada por el Agrónomo al Agricultor, cuando inicia esta tarea desde el app, entonces el sistema cambia el estado a “En proceso”<br/>  Escenario 2: Rechazo de tarea<br/> Dado que exista una tarea pendiente, cuando el Agricultor la rechaza indicando un motivo, entonces el sistema cambia el estado a “Rechazada” y notifica al Agrónomo                                                                                                                                                                                                                                                                                                                            | EP04    |
| US19       | Completar tarea                               | Como Agricultor quiero marcar la tara como completada para cerrar la labor                                                                                 | Escenario 1: Completar con checklist<br/> Dado que la tarea esta en proceso y tiene una checklist, cuando el Agricultor marca todos los ítems y completa la tarea, entonces cambia el estado a “Completada”<br/>  Escenario 2: Checklist Incompleta<br/> Dado que la tarea esta en progreso y tiene una checklist, cuando no se completan todos los ítems, entonces el sistema impide finalizar la tarea y muestra un mensaje de advertencia                                                                                                                                                                                                                                                                                                         | EP04    |
| US20       | Registrar materiales utilizados en tarea      | Como Agricultor, quiero registrar/editar/eliminar los materiales utilizados para el control de insumos                                                     | Escenario 1: Registro de material<br/> Dado que la tarea se encuentra En Progreso, cuando el Agricultor agrega un material con nombre y cantidad, entonces el sistema guarda el material en la tarea <br/> Escenario 2: Edición y eliminación<br/> Dado que ya existe un material registrado, cuando el Agricultor actualiza su cantidad o la elimina, entonces el sistema guarda estos cambios y actualiza la lista de materiales                                                                                                                                                                                                                                                                                                                   | EP04    |
| US21       | Reporte general                               | Como Agronomo, quiero solicitar un reporte general de la organización para ver indicadores globales                                                        | Escenario 1: Solicitud exitosa<br/> Dado que el Agronomo tiene el rol de Owner, cuando solicita el reporte general de un periodo, entonces el sistema inicia la generación del reporte<br/>  Escenario 2: Sin permisos<br/> Dado que el usuario no tiene el rolde Owner, cuando intenta solicitar el reporte, entonces el sistema rechaza la acción y muestra un mensaje de permisos insuficientes                                                                                                                                                                                                                                                                                                                                                   | EP02    |
| US22       | Registrar cuenta                              | Como usuario, quiero registrar mi cuenta con correo y contraseña para poder acceder a la plataforma                                                        | Escenario 1: Registro exitoso<br/> Dado que el usuario ingresa con correo valido y contraseña segura, cuando envia el formulario de registro, entonces el sistema crea la cuenta<br/>  Escenario 2: Error de registro<br/> Dado que el correo ya existe o la contraseña no cumple la política, cuando el usuario trata de registrarse, entonces el sistema rechaza la acción y muestra el motivo                                                                                                                                                                                                                                                                                                                                                     | EP01    |
| US23       | Iniciar sesión                                | Como usuario registrado, quiero iniciar sesión con mis credencial es para entrar de forma segura                                                           | Escenario 1: Inicio exitoso<br/> Dado que el usuario tiene cuenta activa, cuando ingresa el correo y contraseña correctamente, entonces el sistema le da acceso a la plataforma<br/>  Escenario 2: Error de inicio<br/> Dado que el usuario ingresa datos incorrectos, cuando intenta iniciar sesión, entonces el sistema rechaza la acción y muestra un mensaje con el motivo                                                                                                                                                                                                                                                                                                                                                                       | EP01    |
| US24       | Completar perfil                              | Como usuario recién registrado, quiero completar mi perfil con mis datos básicos (nombre, rol y contacto) para poder terminar de configurar mi cuenta      | Escenario 1: Completar datos básicos<br/> Dado que la cuenta fue creada, cuando el usuario agrega nombre, rol y datos de contacto, entonces el sistema guarda la información y marca el perfil como completo<br/>  Escenario 2: Datos incompletos<br/> Dado que el perfil esta en edición, cuando se omiten campos obligatorios, entonces el sistema rechaza la acción y muestra un mensaje de error                                                                                                                                                                                                                                                                                                                                                 | EP01    |
| US25       | Editar perfil                                 | Como usuario, quiero editar mi perfil en cualquier momento para mantener mis datos actualizado                                                             | Escenario 1: Edicion exitosa<br/> Dado que el perfil ya existe, cuando el usuario actualiza sus datos, entonces el sistema guarda los cambios y muestra un mensaje de confirmacion<br/>  Escenario 2: Datos inválidos<br/> Dado que el perfil ya existe, cuando el usuario ingresa información en formato invalido, entonces el sistema rechaza la acción y muestra un mensaje de error                                                                                                                                                                                                                                                                                                                                                              | EP01    |
| US26       | Adquirir suscripción                          | Como usuario, quiero adquirir un plan de suscripción para habilitar las funcionalidades disponibles según mi rol y plan contratado                         | Escenario 1: Compra exitosa<br/> Dado que el usuario tiene cuenta existente, cuando selecciona un plan y realiza el pago correctamente, entonces el sistema activa la suscripción y muestra un mensaje de confirmación<br/>  Escenario 2: Pago Fallido<br/> Dado que el usuario esta autenticado, cuando intenta pagar y el proceso falla, entonces el sistema no activa la suscripción y muestra un mensaje de error                                                                                                                                                                                                                                                                                                                                | EP01    |
| LPS01      | Información de la Landing Page                | Como visitante, quiero interactuar con una página del startup para entender cómo ayudará para la productividad del campo                                   | Escenario 1: Acceso inicial<br/> Dado que el visitante que ingresa a la landing page Cuando busca la página del startup, entonces un encabezado con la propuesta de valor clara, y un subtítulo explicando los beneficios clave.<br/>  Escenario 2: Información adicional<br/> Dado que el visitante navega hacia abajo en la landing page, cuando llega a la sección informativa, entonces visualiza un resumen del startup con sus objetivos propuestos.                                                                                                                                                                                                                                                                                           | EP05    |
| LPS02      | Visualizar información de la página.          | Como visitante, quiero ver una explicación breve sobre la plataforma, para comprender el producto y su propósito.                                          | Escenario 1: Mostrar explicación del producto<br/> Dado que navegue por las secciones, cuando presione en “About”, entonces se despliega esa parte de la página, y describe brevemente de la plataforma, y se incluyen gráficos o imágenes ilustrativas<br/>  Escenario 2: Metricas clave<br/> Dado que el visitante navega dentro de la sección “About”, cuando avanza en la lectura, entonces visualiza métricas calve que refuerzan las propuestas de valor                                                                                                                                                                                                                                                                                       | EP05    |
| LPS03      | Visualización de beneficios y características | Como visitante, quiero conocer los beneficios y características principales del producto, para evaluar si es útil para mis necesidades.                    | Escenario 1: Visualización de beneficios y características<br/> Dado que navegue por las secciones, cuando presione “Servicios”, entonces encontrará una lista de beneficios, y cada uno esté acompañado de un ícono o imagen ilustrativa.<br/>  Escenario 2: Detalle expandido<br/> Dado que el visitante visualiza la lista de beneficios, cuando selecciona un beneficio especifico, entonces se despliega información adicional con una explicación breve                                                                                                                                                                                                                                                                                        | EP05    |
| LPS04      | Consultar planes y precios                    | Como visitante, quiero ver claramente los planes y precios de la plataforma, para decidir cuál se ajusta a mis necesidades.                                | Escenario 1: Visualización de planes y precios<br/> Dado que navegue por las secciones, cuando presione "Planes y precios", entonces veo los planes con diferentes precios y características, y cada uno tendrá un botón de "Empezar".<br/>  Escenario 2: Acceso a FAQ sobre precios<br/> Dado que el visitante consulta la sección ”Planes y precios”, cuando selecciona un icono de ayuda junto al plan, entonces se despliega un menú con preguntas frecuentes sobre pagos y condiciones                                                                                                                                                                                                                                                          | EP05    |
| LPS05      | Formulario de contacto                        | Como visitante, quiero un formulario de contacto para enviar dudas respecto a la página y/o su plataforma.                                                 | Escenario 1: Envío de mensaje<br/> Dado que el visitante está en la sección "Contáctanos", cuando complete los datos requeridos, y presione el botón "Enviar", entonces recibo un mensaje de agradecimiento en pantalla, y mi mensaje se almacena en el sistema de soporte.<br/>  Escenario 2: Confirmación por correo<br/> Dado que el visitante envía el formulario de contacto, cuando el sistema procesa los datos, entonces recibe una confirmación en el correo electrónico ingresado                                                                                                                                                                                                                                                          | EP05    |
| LPS06      | Sección de testimonios                        | Como visitante, quiero poder ver testimonios de agricultores y agrónomos que utilizan EcoTrack para poder confiar más en la solución                       | Escenario 1: Visualización<br/> Dado que el visitante accede a la landing, cuando bajo a la sección de testimonios, entonces visualizo experiencias con nombres, foto y comentario de usuarios reales<br/> Escenario 2: Ampliar testimonio<br/>  Dado que el visitante accede a la sección de testimonio, cuando selecciona un testimonio especifico, entonces se despliega información ampliada con el comentario completo del usuario                                                                                                                                                                                                                                                                                                              | EP05    |
| LPS07      | Ver el sitio en varios idiomas                | Como visitante,  quiero cambiar el idioma de la landing page para poder entender el contenido en mi idioma preferido                                       | Escenario 1: Cambiar idioma <br/>Dado que el sitio tiene opción de idiomas, cuando selecciono otro idioma desde el menu, entonces todo el contenido visible cambia automaticamente al idioma seleccionado                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | EP05    |

Technical stories

| User Story | Titulo                                       | Descripción                                                                                                                                                                           | Criterios de aceptación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | Epic ID |
|------------|----------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------|
| TS01       | Registrar cuenta                             | Como desarrollador, quier implementar el endpoint de registro de usuario para permitir que suarios nueves creen su cuenta (POST /api/auth/register)                                   | Escenario 1: Registro exitoso<br/> Dado que el email no está registrado, cuando envío nombre, email y contraseña válidos, entonces el sistema responde con estado 201 y retorna el userID del nuevo usuario<br/>  Escenario 2: Email duplicado<br/> Dado que ya existe un usuario con el email registrado, cuando intento registrar con ese mismo email, entonces el sistema responde con estado 409 con mensaje “Correo ya registrado”<br/>  Escenario 3: Contraseña débil<br/> Dado que la contraseña ingresada no cumple con la política de seguridad (longitud mínima, caracteres requeridos), cuando intento registrar con esa contraseña, entonces el sistema responde 400 con mensaje “La contraseña no cumple política” | EP01    |
| TS02       | Iniciar sesión                               | Como desarrollador quiero implementar el endpoint de login, para autenticar usuarios y emitir un token seguro (POST /api/auth/login)                                                  | Escenario 1: Credenciales validas<br/> Dado que el usuario ya existe, cuando envío email y contraseña correctos, entonces el sistema responde 200 con token JWT <br/> Escenario 2: Credenciales invalidas<br/> Dado que el usuario existe, cuando envío una contraseña incorrecta, entonces el sistema responde 401 con error de autenticación                                                                                                                                                                                                                                                                                                                                                                                  | EP01    |
| TS03       | Completar perfil                             | Como desarrollador, quiero implementar el endpoint para completar el perfil, para registrar rol y datos básicos del usuario (PUT /api/users/{userID}/profile)                         | Escenario 1: Perfil completo<br/> Dado que el usuario esta autenticado, cuando envío rol y datos de contacto, entonces el sistema responde 200 y guarda “Perfil completado”<br/>  Escenario 2: Datos inválidos<br/> Dado que hay campos obligatorios faltantes, cuando intento guardar, entonces el sistema responde 400 con detalle de validaciones                                                                                                                                                                                                                                                                                                                                                                            | EP01    |
| TS04       | Adquirir suscripción                         | Como desarrollador, quiero implementar el endpoint de alta de suscripción, para activar planes y limites según el plan contratado (POST /api/subscriptions)                           | Escenario 1: Pago aprobrado<br/> Dado que el medio de pago es válido, cuando envió el planID y paymentInfo correctos, entonces el sistema responde 201 y emite “Suscripción adquirida” <br/> Escenario 2: Pago rechazado<br/> Dado que la tarjeta es rechazada, cuando se procesa el cobro, entonces el sistema responde 402 con el motivo del rechazo                                                                                                                                                                                                                                                                                                                                                                          | EP01    |
| TS05       | Crear organización                           | Como desarrollador, quiero implementar un endpoint para poder crear organizaciones (POST /api/organizations)                                                                          | Escenario 1: Creacion exitosa<br/> Dado que el agrónomo esta autenticado, cuando envía nombre, rubro y país válidos, entonces el sistema responde 201 con organizationID <br/> Escenario 2: Datos inválidos<br/> Dado que el formulario está incompleto, cuando intenta registrar, entonces el sistema responde 400 con mensaje “Datos invalidos”                                                                                                                                                                                                                                                                                                                                                                               | EP02    |
| TS06       | Invitar miembros a la organización           | Como desarrollador, quiero implementar un endpoint para enviar invitaciones a agricultores (POST /api/organization/{organizationID}/invitations)                                      | Escenario 1: Invitación enviada<br/> Dado que el Agrónomo es Owner, cuando envía una invitación valida, entonces el sistema responde 201 y crea la invitación con estado “Pendiente”<br/>  Escenario 2: Usuario no valido<br/> Dado que el email no existe, cuando se envía la invitación, entonces el sistema responde 404 con mensaje “Usuario no encontrado”                                                                                                                                                                                                                                                                                                                                                                 | EP02    |
| TS07       | Remover miembro                              | Como desarrollador, quiero implementar un endpoint para eliminar un miembro de una organización (DELETE /api/organizatiosn/{organizationID}/members/{userID})                         | Escenario 1: Remocion exitosa<br/> Dado que el Agronomo es Owner de la organización, cuando elimina a un miembro, entonces el sistema responde 200 con mensaje “Miembro eliminado”<br/>  Escenario 2: Miembro inexistente<br/> Dado que el miembro no existe en la organización, cuando se intenta eliminar, entonces el sistema responde 404 con el mensaje “Usuario no encontrado”                                                                                                                                                                                                                                                                                                                                            | EP02    |
| TS08       | Crear parcela                                | Como desarrollador, quier implementar un endpoint para crear una parcela, para poder gestionar cultivos y su monitoreo (POST /api/organizations}/{organizationID}/parcels)            | Escenario 1: Creación valida<br/> Dado que el Agronomo esta autenticado y con suscripción vigente y cupo disponible, cuando envia nombre, ubicación y área validos, entonces el sistema responde 201 y retorna parcelaID<br/>  Escenario 2: Limite alcanzado<br/> Dado que la organización alcanzo el máximo de parcelas del plan, cuando intento crear una nueva parcela, entonces el sistema responde 403 con “Limite de parcelas alcanzado”                                                                                                                                                                                                                                                                                  | EP03    |
| TS09       | Registrar datos de planta                    | Como desarrollador, quiero implementar un endpoint para registrar hojas y botones, para llevar el estado fenológico del cultivo (POST /api/parcels/{parcelID}/plant-records)          | Escenario 1: Registro valido<br/> Dado que el Agricultor tiene una parcela registrada, cuando envia hojas ≥ 0 y botones ≥ 0, entonces el sistema responde 201 y guarda el registro<br/>  Escenario 2: Valores invalidos<br/> Dado que ingreso hojas = -1, cuando envio el registro, entonces el sistema responde 400 con el mensaje “Los valores no pueden ser negativos”                                                                                                                                                                                                                                                                                                                                                       | EP03    |
| TS10       | Crear checklist                              | Como desarrollador, quiero implementar un endpoint para crear checklists y estandarizar las labores en una parcela (POST /api/parcels/{parcelaID}/checklists)                         | Escenario 1: Checklist creda<br/> Dado que no hay ítems vacíos, cuando envio titulo e ítems, entonces el sistema responde 201 con checkD<br/>  Escenario 2: Items vacíos<br/> Dado que la lista de ítems esta vacia, cuando intento crear, entonces el sistema responde 400 con el mensaje “Items requeridos”                                                                                                                                                                                                                                                                                                                                                                                                                   | EP04    |
| TS11       | Crear tarea                                  | Como desarrollador, quiero implementar un endpoint para creación de tareas y planificar el trabajo del agricultor (POST /api/parcels/{parcelaID}/tasks)                               | Escenario 1: Creacion valida<br/> Dado que el Agrónomo pertenecen a la organización, cuando envía título, fecha futura y respondableID, entonces el sistema responde 201 y notifica al responsable<br/>  Escenario 2: Responsable invalido<br/> Dado que el responsableID no existe dentro de los miembros de la organización, cuando intento crear la tarea, entonces el sistema responde 400 con el mensaje “Usuario responsable invalido”  Escenario 3: Fecha invalida Dado que la fecha ingresada es menor a hoy, cuando intento crear la tarea, entonces el sistema responde 400 con el mensaje “Fecha invalida”                                                                                                           | EP04    |
| TS12       | Cambiar estado de tarea (iniciar/completar)  | Como desarrollador, quiero implementar un endpoint para guardar el estado de las taras, para poder reflejar el avance (en proceso/completada) (PATCH /api/tasks/{taskID]/status)      | Escenario 1: Iniciar tarea<br/> Dado el Agricultor designado ingresa a la tarea, cuadno envia estado = in_progress, entonces el sistema responde 200 y registra startedAt<br/>  Escenario 2: Completar con checklist sin completar<br/> Dado que la tarea tiene la checklist con ítems sin marcar, cuadno envio = completed, entonces el sistema responde 400 con el mensaje “Completar checklist antes de completar la tarea”                                                                                                                                                                                                                                                                                                  | EP04    |
| TS13       | Registrar materiales usados para la tarea    | Como desarrollador, quiero implementar un endpoint para registrar los materiales utilizados por tarea y poder controlar los insumos (POST /api/tasks/{taskID}/materials)              | Escenario 1: Alta demanda<br/> Dado que la tarea se ecuentra en progreso, cuando envio nombre, cantidad y unidad validos, entonces el sistema responde 201 con marialID y almacena el material en la tarea<br/>  Escenario 2: Datos invalidos<br/> Dado que el Agricultor intenta registrar un material, cuando la cantidad es negativa o falta información, entonces el sistema responde 400 con mensaje “Datos invalidos”                                                                                                                                                                                                                                                                                                     | EP04    |
| T14        | Solicitar reporte general de la organización | Como desarrollador, quiero implementar el endpoint para generar un reporte general, mostrando indicadores globales de la organización (GER /api/organization/{organizationID}/report) | Escenario 1: Reporte general correcto<br/>Dado que la organización cuenta con parcelas y tareas activas, cuando solicita el reporte, entonces el sistema responde 200 con KPIs agregados<br/>  Escenario 2: Sin permisos<br/> Dado que el usuario no es miembro de la organización, cuando intenta solicitar el reporte, entonces el sistema responde 403 con el mensaje “Acceso denegado”                                                                                                                                                                                                                                                                                                                                      | EP02    |
| T15        | Bitacora de parcela                          | Como desarrollador quiero implementar un endpoint para poder visualiza todas las actividades registradas en una parcela (GET /api/parcels/{parcelaID}/logbook)                        | Escenario 1: Consulta exitosa<br/> Dado que la parcela tiene actividades registradas, cuando el agricultor consulta la bitácora, entonces el sistema responde 200 con la lista de actividades ordenadas cronológicamente <br/> Escenario 2: Sin actividades<br/> Dado que la parcela no tiene actividades registradas, cuando el Agricultor consulta la bitácora, entonces el sistema responde 200 con una lista vacia y con el mensaje “No hay actividades registradas”                                                                                                                                                                                                                                                        | EP03    |

### EPICS
Las Epics que identificamos son las siguientes:

***Desarrollo de las Epics:***

| Epic ID | Titulo                            | Descripción                                                                                                                                                                       |
|---------|-----------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| EP01    | Onboarding y cuentas de usuario   | Permitir que los usuarios puedan registrarse, iniciar sesión, completar y editar su perfil, además de adquirir planes de suscripción para acceder a funcionalidades según su rol  |
| EP02    | Organizaciones y miembros         | Facilitar a los Agrónomos la creación de organizaciones, la gestión de agricultores mediante invitaciones y eliminaciones, y el acceso a reportes generales de la organización    |
| EP03    | Parcelas y cultivos               | Brindar a los Agronomos herramientas para crear, modificar y gestionar parcelas, registrar cultivos y mantener la trazabilidad de las actividades realizadas en el campo          |
| EP04    | Tareas y checklist                | Permitir la planificación y gestión de tareas y checklists en parcelas, incluyendo recordatorios, ejecución y registro de insumos utilizado en las labores                        |
| EP05    | Informacion y comunicación        | Dar visibilidad a la propuesta de valor de la plataforma mediante la landing page, incluyendo secciones de información, beneficios, planes, testimonios y formularios de contacto |
| EP06    | Aleras y recomendaciones técnicas | Proporcionar asesoría a los agricultores a través de recomendaciones técnicas y fichas de cultivo, además de notificaciones sobre alertas climáticas para prevenir perdidas       |

## 3.2. Impact Mapping

Segmento Objetivo #1: Juan Carlos (Agricultor de pequeña escala)

<img src="./assets/images/impactmapping_juan.png">

Segmento Objetivo #2: Ana Morales (Ingeniera Agrónoma independiente)

<img src="./assets/images/impactmapping_ana.png">


## 3.3. Product Backlog

| #Orden |   ID   | Título                                     | Descripción                                                                                                    | Story Points |
|--------|--------|--------------------------------------------|----------------------------------------------------------------------------------------------------------------|--------------|
| 1 | LPS01 | Información de la Landing Page | Como visitante, quiero interactuar con una página del startup para entender cómo ayudará para la productividad del campo | 5 | 
| 2 | LPS02 | Visualizar información de la página. | Como visitante, quiero ver una explicación breve sobre la plataforma, para comprender el producto y su propósito. | 5 | 
| 3 | LPS03 | Visualización de beneficios y características | Como visitante, quiero conocer los beneficios y características principales del producto, para evaluar si es útil para mis necesidades. | 5 | 
| 4 | LPS04 | Consultar planes y precios | Como visitante, quiero ver claramente los planes y precios de la plataforma, para decidir cuál se ajusta a mis necesidades. | 5 | 
| 5 | LPS05 | Formulario de contacto | Como visitante, quiero un formulario de contacto para enviar dudas respecto a la página y/o su plataforma. | 3 | 
| 6 | LPS06 | Sección de testimonios | Como visitante, quiero poder ver testimonios de agricultores y agrónomos que utilizan EcoTrack para poder confiar más en la solución | 3 |
| 7 | LPS07	| Ver el sitio en varios idiomas | Como visitante, quiero cambiar el idioma de la landing page para poder entender el contenido en mi idioma preferido	| 3 |
| 8 | US01 | Crear organización | Como Agrónomo, quiero crear una organización para centralizar miembros y parcelas | 5 | 
| 9 | US02 | Invitar miembros a organización | Como Agrónomo, quiero enviar invitaciones a los agricultores para poder sumarlos a mi organización | 3 | 
| 10 | US03 | Remover Agricultor de la organización | Como Agrónomo, quiero eliminar a un agricultor para mantener el equipo al día | 2 | 
| 11 | US04 | Bitácora de parcela | Como agricultor, quiero una bitácora por parcela para registrar riegos, fertilizaciones y labores, y asi llevar el control de lo que sucede en ese terreno | 5 | 
| 12 | US05 | Recomendaciones técnicas | Como agrónomo, quiero registrar recomendaciones vinculadas al cultivo para poder orientar al agricultor | 3 | 
| 13 | US06 | Historial de cultivo | Como agricultor, quiero consultar el historial de un cultivo para poder demostrar su trazabilidad | 3 | 
| 14 | US07 | Alertas climáticas | Como agricultor, quiero recibir alertas por lluvia/helada/ola de calor para prevenir pérdidas. | 5 | 
| 15 | US08 | Acceso multiplataforma | Como agricultor, quiero acceder a EcoTrack desde el celular y la computadora para consultar y registrar datos en cualquier lugar | 5 | 
| 16 | US09 | Ficha técnica de cultivo | Como agrónomo, quiero exportar fichas técnicas por cultivo con métricas y recomendaciones. | 3 | 
| 17 | US10 | Creación de parcela | Como Agrónomo, quiero crear un parcela para gestionar el cultivo y su monitoreo | 3 |
| 18 | US11 | Modificación de parcela | Como Agrónomo, quiero modificar una parcela para mantener los datos correctos | 2 | 
| 19 | US12 | Registrar tipo de cultivo por parcela | Como Agrónomo, quiero escoger un tipo de cultivo para personalizar el monitoreo y recomendaciones | 2 | 
| 20 | US13 | Registro de Cultivo | Como agricultor, quiero registrar cultivos/parcelas y actividades diarias para organizar mi producción. | 5 | 
| 21 | US14 | Editar/Eliminar registro | Como Agricultor, quiero eliminar o editar algún registro para corregir errores | 2 | 
| 22 | US15 | Crear una checklist | Como Agrónomo, quiero crear una checklist para estandarizar labores en una parcela | 3 | 
| 23 | US16 | Creación de tareas | Como Agrónomo, quiero crear tareas (con responsable, fecha y prioridad) para poder planificar el trabajo | 3 | 
| 24 | US17 | Recordatorio de tareas | Como agricultor, quiero recibir un recordatorio de actividades programadas para no olvidarlas | 2 | 
| 25 | US18 | Iniciar tarea | Como Agricultor, quiero iniciar la tarea para registrar que empecé a ejecutarla | 1 | 
| 26 | US19 | Completar tarea | Como Agricultor quiero marcar la tara como completada para cerrar la labor | 1 | 
| 27 | US20 | Registrar materiales utilizados en tarea | Como Agricultor, quiero registrar/editar/eliminar los materiales utilizados para el control de insumos | 3 | 
| 28 | US21 | Reporte general | Como Agronomo, quiero solicitar un reporte general de la organización para ver indicadores globales | 5 | 
| 29 | US22 | Registrar cuenta | Como usuario, quiero registrar mi cuenta con correo y contraseña para poder acceder a la plataforma | 2 | 
| 30 | US23 | Iniciar sesión | Como usuario registrado, quiero iniciar sesión con mis credencial es para entrar de forma segura | 2 | 
| 31 | US24 | Completar perfil | Como usuario recién registrado, quiero completar mi perfil con mis datos básicos (nombre, rol y contacto) para poder terminar de configurar mi cuenta | 2 | 
| 32 | US25 | Editar perfil | Como usuario, quiero editar mi perfil en cualquier momento para mantener mis datos actualizado | 1 | 
| 33 | US26 | Adquirir suscripción | Como usuario, quiero adquirir un plan de suscripción para habilitar las funcionalidades disponibles según mi rol y plan contratado | 3 | 
| 34 | TS01 | Registrar cuenta | Como desarrollador, quier implementar el endpoint de registro de usuario para permitir que suarios nueves creen su cuenta (POST /api/auth/register) | 2 | 
| 35 | TS02 | Iniciar sesión | Como desarrollador quiero implementar el endpoint de login, para autenticar usuarios y emitir un token seguro (POST /api/auth/login) | 2 | 
| 36 | TS03 | Completar perfil | Como desarrollador, quiero implementar el endpoint para completar el perfil, para registrar rol y datos básicos del usuario (PUT /api/users/{userID}/profile) | 2 | 
| 37 | TS04 | Adquirir suscripción | Como desarrollador, quiero implementar el endpoint de alta de suscripción, para activar planes y limites según el plan contratado (POST /api/subscriptions) | 3 | 
| 38 | TS05 | Crear organización | Como desarrollador, quiero implementar un endpoint para poder crear organizaciones (POST /api/organizations) | 5 | 
| 39 | TS06 | Invitar miembros a la organización | Como desarrollador, quiero implementar un endpoint para enviar invitaciones a agricultores (POST /api/organization/{organizationID}/invitations) | 3 | 
| 40 | TS07 | Remover miembro | Como desarrollador, quiero implementar un endpoint para eliminar un miembro de una organización (DELETE /api/organizatiosn/{organizationID}/members/{userID}) | 2 | 
| 41 | TS08 | Crear parcela | Como desarrollador, quier implementar un endpoint para crear una parcela, para poder gestionar cultivos y su monitoreo (POST /api/organizations}/{organizationID}/parcels) | 5 | 
| 42 | TS09 | Registrar datos de planta | Como desarrollador, quiero implementar un endpoint para registrar hojas y botones, para llevar el estado fenológico del cultivo (POST /api/parcels/{parcelID}/plant-records) | 3 | 
| 43 | TS10 | Crear checklist | Como desarrollador, quiero implementar un endpoint para crear checklists y estandarizar las labores en una parcela (POST /api/parcels/{parcelaID}/checklists) | 3 |
| 44 | TS11 | Crear tarea | Como desarrollador, quiero implementar un endpoint para creación de tareas y planificar el trabajo del agricultor (POST /api/parcels/{parcelaID}/tasks) | 3 | 
| 45 | TS12 | Cambiar estado de tarea (iniciar/completar) | Como desarrollador, quiero implementar un endpoint para guardar el estado de las taras, para poder reflejar el avance (en proceso/completada) (PATCH /api/tasks/{taskID]/status) | 2 | 
| 46 | TS13 | Registrar materiales usados para la tarea | Como desarrollador, quiero implementar un endpoint para registrar los materiales utilizados por tarea y poder controlar los insumos (POST /api/tasks/{taskID}/materials) | 3 | 
| 47 | TS14 | Solicitar reporte general de la organización | Como desarrollador, quiero implementar el endpoint para generar un reporte general, mostrando indicadores globales de la organización (GER /api/organization/{organizationID}/report) | 5 | 
| 48 | TS15 | Bitacora de parcela | Como desarrollador quiero implementar un endpoint para poder visualiza todas las actividades registradas en una parcela (GET /api/parcels/{parcelaID}/logbook) | 5 | 

<img src="./assets/images/productbacklog.png">

Enlace del Product Backlog: <a href="https://www.google.com/](https://trello.com/b/CNfrjMHe/fs">Vista Previa de Product Backlog</a>


# Capítulo IV: Product Design
## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines

El propósito de esta sección es establecer las pautas generales de estilo que guiarán el desarrollo visual y comunicacional de EcoTrack, una plataforma digital diseñada para apoyar a agricultores y agrónomos en la gestión eficiente de sus cultivos, facilitando la trazabilidad, organización de labores agrícolas y toma de decisiones basadas en datos.
Estas directrices buscan asegurar la coherencia estética, funcional y de experiencia de usuario en todos los puntos de contacto de la plataforma web, empleando herramientas de diseño como Figma. Funcionan como una guía centralizada para el equipo de diseño, desarrollo y marketing, garantizando que la identidad de EcoTrack se mantenga consistente, accesible y alineada con sus valores de sostenibilidad, innovación y confianza.

### Branding:

El logotipo de EcoTrack es el principal símbolo de identidad de la marca y comunica el enfoque tecnológico y sostenible de la startup. El diseño del logo combina elementos naturales con un estilo moderno, utilizando tonos verdes y azules que evocan agricultura, confianza y tecnología.

<img src="assets/images/screenshots/logo%20(2).png" width="30%"/>

A continuación, se detallan las decisiones relacionadas con su uso y aplicación:

- Logo principal: Se debe usar en su versión completa siempre que sea posible, preferentemente sobre fondos claros o naturales que refuercen la conexión con la sostenibilidad.

- Adaptación en Figma: El logo debe almacenarse como un componente reutilizable con versiones de alta resolución y fondo transparente, lo que facilitará su implementación en distintas pantallas y materiales de comunicación.


### Typography:

La tipografía es uno de los elementos más importantes en la creación de una identidad visual coherente. Para EcoTrack , hemos seleccionado fuentes que transmiten tecnología, claridad y profesionalismo:

- Fuente principal: La fuente seleccionada es Poppins, moderna y legible, que comunica tecnología cercana y simple. Se usará en Bold para encabezados y títulos principales, y en Regular para el cuerpo de texto.
- Fuente secundaria:
  Para descripciones, subtítulos y formularios se recomienda Inter, una tipografía limpia y altamente legible en pantallas pequeñas, ideal para la experiencia móvil de agricultores y agrónomos.

### Colors:

La paleta de colores busca transmitir sostenibilidad, confianza y modernidad, alineada con la misión de Agromind de impulsar la digitalización agrícola.

- Color primario:

#2E7D32 (Verde Sustentable) – Representa el vínculo con la tierra, la productividad y la sostenibilidad. Será utilizado en botones principales, encabezados y elementos de énfasis.
- Color secundario:

#FFFFFF (Blanco) – Aporta limpieza y equilibrio. Servirá como color de fondo en la mayoría de interfaces, permitiendo claridad y foco en la información.
- Color terciario:

#1A1A1A (Negro Suave) – Se empleará para los textos principales sobre fondos claros, asegurando una excelente legibilidad.

- Color de realce:

#2196F3 (Azul Tecnológico) – Evoca confianza y tecnología. Se usará en botones secundarios, hipervínculos e iconos interactivos que requieran captar la atención del usuario.

- Color de alerta:

#FF7A00 (Naranja Cálido)
Para llamadas a la acción inmediatas o notificaciones relevantes, captando la atención de forma amigable


Aplicación en Figma:
Estos colores deben guardarse como Color Styles accesibles a todo el equipo, garantizando consistencia en cada componente y pantalla.


### Spacing: 

El uso correcto del espacio refuerza la claridad, simplicidad y organización que EcoTrack quiere transmitir a sus usuarios, facilitando una navegación sin fricciones.

- Padding y Márgenes:

Para mantener una sensación de estructura y simplicidad, se recomienda utilizar 60px de padding entre secciones .entre secciones principales en pantallas de escritorio. Entre bloques de contenido debe haber un espacio de alrededor de 40px , asegurando que cada componente tenga espacio para “respirar” y que la información pueda ser escaneada visualmente con facilidad.

- Espaciado entre Elementos:

El espacio entre elementos interactivos (botones, íconos y campos de entrada) debe ser de 20px . Esto mejora la legibilidad, facilita la interacción con el contenido y permite una experiencia fluida tanto en pantallas grandes como en resoluciones adaptativas.

- Aplicación en Figma:

En Figma, se utilizará el sistema de Auto Layout para mantener la consistencia en los espacios y asegurar que los elementos se ajusten correctamente en diferentes tamaños de pantalla. Los componentes deberán incluir valores predefinidos de padding y margen.

### Tono de comunicación:

El tono de EcoTrack debe reflejar cercanía, claridad y empoderamiento, alineado con el objetivo de acompañar al agricultor en su digitalización sin generar barreras.

- Cercano y accesible: El lenguaje debe ser sencillo, evitando tecnicismos innecesarios, de manera que agricultores con distintos niveles de experiencia tecnológica puedan comprender fácilmente la plataforma.


- Positivo y motivador: El tono debe transmitir confianza en que el agricultor puede mejorar su productividad y trazabilidad con pequeñas acciones dentro de la app.


- Profesional y confiable: En la comunicación hacia agrónomos, el estilo debe ser más técnico, reforzando la idea de datos confiables y soporte para decisiones estratégicas.

Aplicación en Figma:

En botones y mensajes interactivos se usarán verbos de acción como Registrar, Consultar, Optimizar.

Las alertas deben invitar a la acción sin ser alarmistas. Ejemplo: “Revisa el riego de tus cultivos hoy” en lugar de mensajes negativos.

### 4.1.2. Web Style Guidelines

- Typography

Tipografía principal: Poppins

Título principal (32px)

Subtítulo (24px)

Cuerpo de texto (16px)

Tipografía secundaria: Inter

Descripciones y textos pequeños (14px)

Etiquetas y formularios (12px)

- Colors

A continuación, presentaremos los colores elegidos junto a su respectivo código identificador en Figma.

Colores elegidos para la versión web

<img src="./assets/images/screenshots/colors.png" width="35%">

- Spacing

A continuación, presentaremos las decisiones de espaciado elegidas.

Espaciado elegido entre elementos de la plataforma web

<img src="assets/images/screenshots/spacing.png" width="25%">

- Assets

A continuación, mostraremos las imágenes referenciales de los assets elegidos.

Plantilla usada para la versión Desktop

<img src="./assets/images/screenshots/Plantilla_Landing.png" width="60%">

Pantalla de inicio

<img src="./assets/images/screenshots/inicio-landing.png" width="60%">

## 4.2. Information Architecture

En esta sección, presentaremos las decisiones y las razones que guían la manera en que se estructura el contenido de la experiencia web, incluyendo la página de inicio (Landing Page) y las aplicación. Estas propuestas se enfocan mayormente en garantizar que los usuarios puedan adaptarse fácilmente a las funcionalidades de cada producto y encuentren sin dificultad lo que busquen.

### 4.2.1. Organization Systems

Cuadro de cómo se estructura la información del landing page

<img src="./assets/images/screenshots/landing-org%20.png" width="70%">

Cuadro de cómo se estructura la información de la aplicación web
### 4.2.2. Labeling Systems

El sistema de etiquetado en **EcoTrack** está diseñado para ser intuitivo, breve y cercano al vocabulario agrícola. Se busca que las etiquetas comuniquen con pocas palabras la función de cada sección, evitando tecnicismos innecesarios y facilitando la adopción por parte de usuarios con distintos niveles de experiencia digital.

Las etiquetas se dividen según los dos perfiles principales de la plataforma: **agrónomos** (gestión y supervisión) y **agricultores** (ejecución de tareas y registro de datos).

#### Agrónomo (enfoque de gestión y control)
- **Panel de Control:** vista general con indicadores clave como parcelas activas, tareas pendientes y alertas recientes.
- **Organización:** gestión de miembros (invitar, asignar o remover agricultores).
- **Parcelas:** listado de todas las parcelas registradas con acceso al detalle de cada una.
- **Cultivos:** catálogo de cultivos existentes y opción de registrar nuevos.
- **Tareas:** planificación, asignación y seguimiento de laborgges agrícolas.
- **Alertas:** configuración de umbrales climáticos y recepción de notificaciones.
- **Reportes:** generación de reportes detallados por parcela o generales de la organización.

#### Agricultor (enfoque operativo y de ejecución)
- **Panel:** vista principal con las tareas asignadas y notificaciones inmediatas.
- **Mis Parcelas:** parcelas en las que está involucrado, con acceso al registro de datos del cultivo.
- **Tareas:** lista de tareas pendientes con la opción de aceptarlas, iniciarlas o marcarlas como completadas.
- **Registros:** formulario para ingresar datos fenológicos (hojas, botones) y condiciones ambientales (temperatura, humedad).
- **Materiales:** espacio para reportar y controlar insumos utilizados en cada labor.

---

### 4.2.3. SEO Tags and Meta Tags

Con el fin de aumentar la visibilidad de **EcoTrack** en buscadores y ofrecer una navegación más clara y optimizada, se han definido un conjunto de **SEO Tags y Meta Tags** que acompañarán tanto a la landing page como a la aplicación web.

Estas etiquetas cumplen un papel esencial en el **posicionamiento en motores de búsqueda**, la **adaptación a distintos dispositivos** y la correcta interpretación del contenido por parte de navegadores y servicios externos.

Cada etiqueta tiene un rol específico:
- **Title:** se muestra en la pestaña del navegador y aparece como título principal en los resultados de búsqueda.
- **Description:** ofrece un resumen breve y atractivo de la página, pensado para captar al usuario en segundos.
- **Author:** identifica al equipo responsable de la solución.
- **Viewport:** asegura que el contenido se ajuste a todo tipo de pantallas, desde móviles hasta monitores de escritorio.
- **Charset:** define el sistema de codificación de caracteres, en este caso UTF-8, garantizando compatibilidad global.
- **Keywords:** lista de palabras clave que facilitan la clasificación de la página por los motores de búsqueda.

#### Landing Page SEO Tags and Meta Tags
- **Title:** "EcoTrack - Plataforma inteligente para la gestión agrícola"
- **Description:** "EcoTrack ayuda a modernizar la agricultura con herramientas digitales que facilitan el manejo de parcelas, tareas y reportes en un solo lugar."
- **Author:** "Equipo EcoTrack"
- **Viewport:** configurado para ofrecer una experiencia fluida en móviles, tablets y computadoras.
- **Charset:** UTF-8 para soportar distintos alfabetos y símbolos.
- **Keywords:** "agricultura digital, ecotrack, gestión de parcelas, tareas agrícolas, reportes de cultivo"

```html
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>EcoTrack - Plataforma inteligente para la gestión agrícola</title>
  <meta name="description" content="EcoTrack ayuda a modernizar la agricultura con herramientas digitales que facilitan el manejo de parcelas, tareas y reportes en un solo lugar.">
  <meta name="keywords" content="agricultura digital, ecotrack, gestión de parcelas, tareas agrícolas, reportes de cultivo">
  <meta name="author" content="Equipo EcoTrack">
</head>
````

#### Web Application SEO Tags and Meta Tags
Web Application SEO Tags and Meta Tags

* **Title**: "EcoTrack App - Panel digital para agrónomos y agricultores"
* **Description**: "Gestiona tu trabajo agrícola con EcoTrack: controla parcelas, asigna tareas, registra condiciones del cultivo y recibe alertas climáticas desde cualquier dispositivo."
* **Author**: "Equipo EcoTrack"
* **Viewport**: preparado para que la aplicación sea completamente responsiva y usable en móviles, tablets y PC.
* **Charset**: UTF-8 como estándar de compatibilidad.
* **Keywords**: "ecotrack app, monitoreo agrícola, tareas del campo, reportes agrícolas, gestión digital de parcelas"

````html
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>EcoTrack App - Panel digital para agrónomos y agricultores</title>
  <meta name="description" content="Gestiona tu trabajo agrícola con EcoTrack: controla parcelas, asigna tareas, registra condiciones del cultivo y recibe alertas climáticas desde cualquier dispositivo.">
  <meta name="keywords" content="ecotrack app, monitoreo agrícola, tareas del campo, reportes agrícolas, gestión digital de parcelas">
  <meta name="author" content="Equipo EcoTrack">
</head>
````

### 4.2.4. Searching Systems

El sistema de búsqueda de EcoTrack se basa en mecanismos de filtrado y selección dentro de cada módulo, en lugar de un buscador global. Este enfoque facilita el acceso rápido a información específica y mantiene la simplicidad de la aplicación.

* Parcelas: filtros por nombre, cultivo y responsable asignado.
* Tareas: filtros por estado (pendiente, en ejecución, completada), prioridad y fecha de vencimiento.
* Registros: organización cronológica de datos fenológicos y ambientales, con posibilidad de acotar por rango de fechas.
* Reportes: criterios de selección por parcela o periodo de tiempo.

Este sistema asegura que los usuarios puedan acceder de manera ágil a los datos que requieren, evitando la saturación de la interfaz con funciones innecesarias.

### 4.2.5. Navigation Systems

El sistema de navegación de EcoTrack se ha diseñado con base en los principios de claridad, consistencia y adaptabilidad, de modo que los usuarios puedan desplazarse con facilidad tanto en la landing page como en la aplicación web.
Ambas experiencias están desarrolladas bajo un enfoque responsive design, lo que garantiza que la navegación sea fluida en distintos tamaños de pantalla (computadora, tablet o móvil).

* **Landing Page:** cuenta con un menú superior fijo que da acceso a las secciones principales: Inicio, Funcionalidades, Planes y Contacto. Este menú acompaña al usuario durante todo el recorrido, facilitando la exploración sin importar en qué parte de la página se encuentre.
* **Aplicación Web:** utiliza una barra lateral de navegación con accesos directos a las secciones clave: Panel de Control, Organización, Parcelas, Tareas, Alertas y Reportes. En vistas más específicas se integran breadcrumbs, que permiten al usuario mantener el contexto y regresar fácilmente a niveles superiores de la aplicación.

Este sistema asegura que la experiencia de navegación sea clara y consistente, reduciendo la curva de aprendizaje y facilitando la orientación del usuario en todo momento.

## 4.3. Landing Page UI Design

Esta sección se enfoca en el diseño de la interfaz de usuario (UI) de la Landing Page, que es esencial para captar la atención de los usuarios y comunicar de manera efectiva la propuesta de valor del sistema. A continuación, se presentan los wireframes y los mock-ups, dos etapas clave en el proceso de diseño que permiten visualizar y refinar la estructura y apariencia de la página.
### 4.3.1. Landing Page Wireframe
Con respecto a la arquitectura de la Landing Page, para versiones web hemos decidido adoptar un diseño estándar, como lo sería tener en la parte superior la barra de opciones como “Acerca de”, “Servicios”, “Testimonios”, "Contacto", " Iniciar sesión" y "Registrarse". Mientras que la posición de las estructuras de texto e imágenes es bastante amplia separadas lo suficiente una de la otra en su mayoría, aprovechando al máximo la cantidad de espacio que ofrece la visualización desde un monitor, lo que nos permite tener un gran espacio disponible que podemos rellenar con información pero sin llegar a exagerar y hacer ver como si estuviera sobrecargado.

Para su mejor visualización se adjunta el enlace del figma:
https://www.figma.com/design/lvoCw7poE1cnwIbnE23r0M/Aplicaciones-Web---Agromind?node-id=0-1&t=V7aVIZOy2DB1pbuc-1

- Ventana de inicio

<img src="./assets/images/screenshots/wireframe-landing-1.png" width="60%">

- Ventana de Acerca de

<img src="./assets/images/screenshots/wireframe-landing-2.png" width="60%">

- Ventana de Servicios

<img src="./assets/images/screenshots/wireframe-landing-3.png" width="60%">

- Ventana de Testimonios

<img src="./assets/images/screenshots/wireframe-landing-4.png" width="60%">

- Ventana de Contacto

<img src="./assets/images/screenshots/wireframe-landing-5.png" width="60%">

### 4.3.2. Landing Page Mock-up

- Ventana de inicio

<img src="./assets/images/screenshots/inicio-landing.png" width="60%">

- Ventana de Acerca de

<img src="./assets/images/screenshots/mockup-landing-1.png" width="60%">

- Ventana de Servicios

<img src="./assets/images/screenshots/mockup-landing-2.png" width="60%">

- Ventana de Testimonios

<img src="./assets/images/screenshots/mockup-landing-3.png" width="60%">

- Ventana de Contacto

<img src="./assets/images/screenshots/mockup-landing-4.png" width="60%">

## 4.4. Web Applications UX/UI Design

En el diseño de la interfaz de usuario de nuestra aplicación web "EcoTrack", nos enfocamos en ofrecer una experiencia intuitiva, eficiente y visualmente atractiva. Asimismo, seguimos las guías de diseño para optimizar el rendimiento y garantizar que cada parte de la aplicación se adapte de manera fluida a los clientes y trabajadores.

### 4.4.1. Web Applications Wireframes
- Vista de Inicio de Sesion

<img src="./assets/images/screenshots/wireframe1.jpg" width="60%">

- Vista de Crear Cuenta

<img src="./assets/images/screenshots/wireframe2.jpg" width="60%">

- Vista de Planes

<img src="./assets/images/screenshots/wireframe3.jpg" width="60%">

- Vista de Método de Pago

<img src="./assets/images/screenshots/wireframe4.jpg" width="60%">

- Vista de Inicio de Agrónomo

<img src="./assets/images/screenshots/wireframe5.jpg" width="60%">
<img src="./assets/images/screenshots/wireframe6.jpg" width="60%">
<img src="./assets/images/screenshots/wireframe7.jpg" width="60%">
<img src="./assets/images/screenshots/wireframe8.jpg" width="60%">
<img src="./assets/images/screenshots/wireframe9.jpg" width="60%">
<img src="./assets/images/screenshots/wireframe10.jpg" width="60%">
<img src="./assets/images/screenshots/wireframe11.jpg" width="60%">
<img src="./assets/images/screenshots/wireframe12.jpg" width="60%">
<img src="./assets/images/screenshots/wireframe13.jpg" width="60%">
<img src="./assets/images/screenshots/wireframe14.jpg" width="60%">
<img src="./assets/images/screenshots/wireframe15.jpg" width="60%">
<img src="./assets/images/screenshots/wireframe16.jpg" width="60%">
<img src="./assets/images/screenshots/wireframe17.jpg" width="60%">
<img src="./assets/images/screenshots/wireframe18.jpg" width="60%">

- Vista de Perfil del Agrónomo

<img src="./assets/images/screenshots/wireframe19.jpg" width="60%">

- Vista de Configuraciondes del Agrónomo

<img src="./assets/images/screenshots/wireframe20.jpg" width="60%">
<img src="./assets/images/screenshots/wireframe21.jpg" width="60%">

- Vista de Inicio del Agricultor

<img src="./assets/images/screenshots/wireframe22.jpg" width="60%">
<img src="./assets/images/screenshots/wireframe23.jpg" width="60%">
<img src="./assets/images/screenshots/wireframe24.jpg" width="60%">
<img src="./assets/images/screenshots/wireframe25.jpg" width="60%">
<img src="./assets/images/screenshots/wireframe26.jpg" width="60%">

- Vista del Perfil del Agricultor

<img src="./assets/images/screenshots/wireframe27.jpg" width="60%">

- Vista de Configuraciones del Agricultor

<img src="./assets/images/screenshots/wireframe28.jpg" width="60%">
<img src="./assets/images/screenshots/wireframe29.jpg" width="60%">

### 4.4.2. Web Applications Wireflow Diagrams
En esta seccion se presentan los Wireflows para cada objetivo del usuario. Por ello se considero de los User Persona correspondientes. Cada diagrama muerstra el flujo de interaccion

### Vista General

 Gestionar cuenta: Inicio de Sesión / Crear cuenta

El usuario desea registrarse o iniciar sesión en la plataforma para
acceder a sus funcionalidades. El usuario ve opciones para **"Iniciar
sesión"** o **"Registrarse"**. Si selecciona **"Registrarse"**, el usuario completa un formulario con
su nombre, correo electrónico y su contraseña. Finalmente, el sistema valida los datos ingresados y es redirigido al
apartado de planes, donde puede seleccionar el plan que mejor se le
acomode. Luego, es redirigido al apartado de pago, donde puede completar su
información bancaria. Una vez culmina todo el proceso de registro, es redirigido al

<img src="assets/images/screenshots/wireflow1.jpg" width="60%">

Edición de Perfil

En el apartado de **Perfil**, el usuario puede editar la información de
su perfil, como nombre, apellido, contraseña y correo, además de poder
subir o cambiar la foto registrada en el aplicativo.\
Al finalizar, puede guardar los cambios.

<img src="assets/images/screenshots/wireflow12.jpg" width="60%">

Configuraciones

En el apartado de **Configuración**, el usuario puede visualizar el plan
actual con el que cuenta, así como la fecha de pago.\
También puede realizar el cambio de idioma por el idioma de su
preferencia.

<img src="assets/images/screenshots/wireflow13.jpg" width="60%">

### Vista de Agrónomo

Crear una organización

El usuario registra una nueva organización para poder gestionar sus
parcelas y asignar agricultores.\
Completa un formulario con los datos de la organización como nombre,
descripción y ubicación, además le permite añadir miembros a la
organización y confirma su creación.

<img src="assets/images/screenshots/wireflow2.jpg" width="60%">

Gestionar Parcelas y cultivos

Desde la vista de la organización, el agrónomo puede crear parcelas.\
Completa un formulario con el nombre, área, ubicación y cultivo de la
parcela, además puede asignar encargados a dicha parcela y confirmar su
creación.

<img src="assets/images/screenshots/wireflow3.jpg" width="60%">

Asignar Tareas y checklist

Dentro de una parcela, el agrónomo puede crear tareas nuevas, asignarles
una checklist y delegar a un agricultor encargado de realizar dicha
tarea, todo dentro de una sola interacción.

<img src="assets/images/screenshots/wireflow4.jpg" width="60%">

Gestión de bitácoras

Dentro de una parcela, el agrónomo puede visualizar las bitácoras
existentes de dicha parcela, así como agregar nuevas actividades
completando un formulario.\
Una vez complete el nombre de la actividad, la duración, fecha, la
cantidad de insumos utilizados y suba una foto, puede guardar la
actividad y se reflejará en la bitácora de la parcela.

<img src="assets/images/screenshots/wireflow5.jpg" width="60%">

Editar Parcela

Al seleccionar una parcela existente, el agrónomo puede editar los datos
de la misma.\
Cuando complete el formulario con el área, ubicación y cultivo, puede
guardar los datos de la parcela y se actualizará en el sistema.

<img src="assets/images/screenshots/wireflow6.jpg" width="60%">

Gestión de Reportes

Dentro de la organización, el agrónomo puede visualizar y descargar los
reportes realizados anteriormente, así como solicitar un nuevo reporte.\
Para ello, llena un formulario con el intervalo de fechas para el que
desea el reporte.

<img src="assets/images/screenshots/wireflow7.jpg" width="60%">

Generar Ficha técnica

Dentro de la organización, el agrónomo puede solicitar una ficha técnica
únicamente indicando el nombre de la parcela sobre la cual desea dicha
ficha.

<img src="assets/images/screenshots/wireflow8.jpg" width="60%">

### Vista de Agricultor

Registrar cultivo

Desde el apartado de cultivo, el agricultor agrega un nuevo cultivo,
completando el nombre, la superficie, la ubicación y la fecha de
siembra.\
Una vez completos todos los datos, puede guardar el cultivo.

<img src="assets/images/screenshots/wireflow9.jpg" width="60%">

Visualizar Tareas

Desde el Dashboard, el agricultor puede visualizar las tareas que fueron
asignadas a él, dependiendo del estado de estas. Dentro del mismo flujo, puede visualizar tareas completadas, tareas en
curso y tareas pendientes. Asimismo, al ingresar a una tarea puede visualizar la checklist, de modo
que podrá ir completando todas las actividades pendientes y finalizar la
tarea. En caso la tarea se encuentre pendiente, puede iniciarla.

<img src="assets/images/screenshots/wireflow10.jpg" width="60%">

Visualización de bitácoras

Desde el Dashboard, el agricultor puede visualizar las bitácoras
registradas en la parcela de la cual se encuentra encargado.

<img src="assets/images/screenshots/wireflow11.jpg" width="60%">

### 4.4.2. Web Applications Mock-ups
Para su mejor visualización se adjunta el enlace del figma: https://www.figma.com/design/lvoCw7poE1cnwIbnE23r0M/Aplicaciones-Web---Agromind?node-id=0-1&t=V7aVIZOy2DB1pbuc-1

- Vista de Iniciar sesión

<img src="./assets/images/screenshots/mockup1.png" width="60%">

- Vista de Crear Cuenta
  
<img src="./assets/images/screenshots/mockup2.png" width="60%">

- Vista de Planes

<img src="./assets/images/screenshots/mockup3.png" width="60%">

- Vista de Método de pago

<img src="./assets/images/screenshots/mockup4.png" width="60%">

- Vista de Inicio del Agrónomo

<img src="./assets/images/screenshots/mockup5.png" width="60%">
<img src="./assets/images/screenshots/mockup6.png" width="60%">
<img src="./assets/images/screenshots/mockup7.png" width="60%">
<img src="./assets/images/screenshots/mockup8.png" width="60%">
<img src="./assets/images/screenshots/mockup9.png" width="60%">
<img src="./assets/images/screenshots/mockup10.png" width="60%">
<img src="./assets/images/screenshots/mockup11.png" width="60%">
<img src="./assets/images/screenshots/mockup12.png" width="60%">
<img src="./assets/images/screenshots/mockup13.png" width="60%">
<img src="./assets/images/screenshots/mockup14.png" width="60%">
<img src="./assets/images/screenshots/mockup15.png" width="60%">
<img src="./assets/images/screenshots/mockup16.png" width="60%">
<img src="./assets/images/screenshots/mockup17.png" width="60%">
<img src="./assets/images/screenshots/mockup18.png" width="60%">

- Vista de Perfil del Agrónomo

<img src="./assets/images/screenshots/mockup19.png" width="60%">

- Vista de Configuración del Agrónomo

<img src="./assets/images/screenshots/mockup20.png" width="60%">
<img src="./assets/images/screenshots/mockup21.png" width="60%">

- Vista de Inicio del Agricultor

<img src="./assets/images/screenshots/mockup22.png" width="60%">
<img src="./assets/images/screenshots/mockup23.png" width="60%">
<img src="./assets/images/screenshots/mockup24.png" width="60%">
<img src="./assets/images/screenshots/mockup25.png" width="60%">
<img src="./assets/images/screenshots/mockup26.png" width="60%">

- Vista de Perfil del Agricultor

<img src="./assets/images/screenshots/mockup27.png" width="60%">

- Vista de Configuración del Agricultor

<img src="./assets/images/screenshots/mockup28.png" width="60%">
<img src="./assets/images/screenshots/mockup29.png" width="60%">

### 4.4.3. Web Applications User Flow Diagrams
- User Flow – Agricultor Juan Carlos
  
        User goal: “Juan Carlos quiere organizar y dar seguimiento a sus cultivos de manera sencilla para mejorar el control de su producción y reducir pérdidas.”

<img src="./assets/images/screenshots/Userflow1.png" width="80%">

- Explicación de los flujos y condiciones

  - Inicio de sesión / acceso

        Ingresa con usuario y contraseña.

        Happy path: Accede correctamente al Dashboard.

        Unhappy path: Credenciales erróneas o error de conexión → mensaje de error con opción de reintentar.

  - Selección de cultivo

        En el Dashboard, selecciona el cultivo que quiere revisar.

        Happy path: Accede a la vista del cultivo.

        Unhappy path: No tiene cultivos registrados → mensaje “Agrega un cultivo para comenzar”.

  - Visualización de tareas del cultivo

        Ve una lista organizada de tareas pendientes: riego, fertilización, control de plagas, cosecha.

        Cada tarea incluye estado (pendiente, en proceso, completada).

        Happy path: Puede consultar y entender fácilmente las tareas.

        Unhappy path: No tiene tareas, pide crear tarea”.

  - Alertas asociadas al cultivo

        Consulta alertas relevantes (ej. clima extremo, plagas en la zona).

        Happy path: Visualiza alertas actualizadas que le permiten anticiparse a problemas.

        Unhappy path: Falla en la carga → mensaje de error y opción de reintentar.

- User Flow – Ingeniera Agrónoma (Ana Morales)


    - User Goal: Ana quiere gestionar y consultar información confiable de los agricultores y sus cultivos para garantizar la trazabilidad y brindar asesorías técnicas precisas.

<img src="./assets/images/screenshots/userflow2.png" width="80%">


- Explicación de los flujos y condiciones

  - Inicio de sesión / acceso

        Ana ingresa a la aplicación con sus credenciales.

        Happy path: Accede correctamente a su Dashboard.

        Unhappy path: Error en credenciales o conexión → mensaje de error con opción de reintentar.

  - Dashboard de agrónoma

        Visualiza las organizaciones creadas y la lista de agricultores a su cargo o que asesora.

        Desde aquí puede crear una nueva organización o seleccionar una existente para acceder a la información.

        Happy path: Accede al detalle de la organización seleccionada.

        Unhappy path: Error de carga de organizaciones → mensaje de reintento.

  - Creación de organización

        Ana puede registrar una organización y asociar agricultores.

        Happy path: Organización creada correctamente y agricultores vinculados.

        Unhappy path: Datos incompletos (ej. falta nombre) → mensaje de validación para corregir.

  - Creación de parcelas

        Dentro de la organización, Ana puede crear una parcela con nombre, área, ubicación y cultivo.

        Happy path: Parcela registrada y disponible en la lista de parcelas.

        Unhappy path: Datos incompletos o error de red → advertencia “No se pudo registrar la parcela”.

  - Visualización de parcelas y tareas

        Ana accede a la lista de parcelas creadas y selecciona una para visualizar sus tareas (riego, fertilización, control de plagas, etc.).

        Happy path: Visualiza las tareas organizadas por estado (pendiente, en proceso, completada).

        Unhappy path: Error de conexión o falta de datos → mensaje “No se pudieron cargar las tareas”.

  - Gestión de tareas

        Ana puede crear nuevas tareas dentro de la parcela o consultar las ya registradas.

        Happy path: La tarea se guarda correctamente y se actualiza la lista.

        Unhappy path: Datos faltantes (ej. sin fecha asignada) o error de carga → mensaje de advertencia.

  - Bitácora de actividades

        Dentro de la parcela, Ana accede al botón Bitácora para:

        Ver actividades realizadas previamente.

        Registrar nuevas actividades (ej. aplicación de fertilizante, fumigación).

        Happy path: La actividad se registra y queda guardada en el historial.

        Unhappy path: Falta de información (ej. sin fecha) o fallo de conexión → mensaje de error con opción de reintentar.

## 4.5. Web Applications Prototyping
## 4.6. Domain-Driven Software Architecture

En esta sección se presenta la arquitectura de software basada en el enfoque de Domain-Driven Design (DDD) para la solución propuesta. Se detallan los diagramas y modelos que reflejan la estructura y organización del sistema, alineados con los principios de DDD.

### 4.6.1. Design-Level EventStorming

En esta sección se explica y evidencia el proceso de Design-Level EventStorming, que sirvió para plantear una aproximación revisada y mejorada al modelado de nivel general para el dominio del problema.

**Step 1: Unstructured Exploration**  
![Step 1 Design Level Event Storming](./assets/images/design-level-event-storming/design-level-event-storming-step-1.png)  
En este paso el equipo comenzó con una lluvia de ideas de los eventos del dominio.

**Step 2: Timelines**  
![Step 2 Design Level Event Storming](./assets/images/design-level-event-storming/design-level-event-storming-step-2.png)  
En este segundo paso, el equipo ordeno los eventos de dominio en el orden que ocurren en el dominio empresarial.  
Se tuvo en cuenta los happy path y luego se agregaron los escenarios alternativos.

**Step 3: Pain Points**  
![Step 3 Design Level Event Storming](./assets/images/design-level-event-storming/design-level-event-storming-step-3.png)  
En este tercer paso, el equipo colocó dudas sobre el dominio o documentación faltante en algunas partes del flujo que ya había sido ordenado anteriormente.

**Step 4: Pivotal Points**  
![Step 4 Design Level Event Storming](./assets/images/design-level-event-storming/design-level-event-storming-step-4.png)  
En este cuarto paso, el equipo buscó eventos comerciales importantes que indiquen un cambio en el contexto y los marcó con una línea.

**Step 5: Commands**  
![Step 5 Design Level Event Storming](./assets/images/design-level-event-storming/design-level-event-storming-step-5.png)  
En este quinto paso, el equipo añadió comandos que desencadenen eventos o el flujo de eventos, junto a sus actores.

**Step 6: Policies**  
![Step 6 Design Level Event Storming](./assets/images/design-level-event-storming/design-level-event-storming-step-6.png)  
En este sexto paso, el equipo añadió policies, que son reglas de negocio que hace que se ejecuten comandos sin la necesidad de un actor.

**Step 7: Read Models**  
![Step 7 Design Level Event Storming](./assets/images/design-level-event-storming/design-level-event-storming-step-7.png)  
En este séptimo paso, el equipo añadió read models, que son como la vista de datos que el usuario usa para tomar la decisión de ejecutar un comando.

**Step 8: External Systems**  
![Step 8 Design Level Event Storming](./assets/images/design-level-event-storming/design-level-event-storming-step-8.png)  
En este octavo paso, el equipo identifico sistemas externos, en este caso solo se tiene uno que es la API que usaremos para el consumo de datos climáticos.

**Step 9: Aggregates**  
![Step 9 Design Level Event Storming](./assets/images/design-level-event-storming/design-level-event-storming-step-9.png)  
En este noveno paso, el equipo antes de agregar los agregados, discutió bastantes cosas sobre pasos anteriores y se decidió hacer algunos cambios en los read models, policies, eventos y commands.


**Step 10: Bounded Contexts**  
![Step 10 Design Level Event Storming](./assets/images/design-level-event-storming/design-level-event-storming-step-10.png)  
En este último paso, el equipo buscó agregados que estén relacionados entre sí mediante policies para luego identificar bounded contexts.  
[Ver en Miro](https://miro.com/welcomeonboard/Tkt0b0FqK3BGdThsbmVRKytveUdDdTBMeHZtNW52aTcvaHBHQ3dKYTlCS2FzMlhLYVZhNnAwaHpkRHNhOTlTSzFLRVhFeW5JQlZJck5hUzNBSlMrbVpqbVB1M3ErOFNsY0hQTDNXbStrSXZ0WnFBK2I3dlk0YXl0OFJwamdhcXB0R2lncW1vRmFBVnlLcVJzTmdFdlNRPT0hdjE=?share_link_id=129166886960)

### 4.6.2. Software Architecture Context Diagram

EcoTrack es una plataforma digital diseñada para optimizar la gestión agrícola, se tiene dos segmentos objectivos principales: el agronomo utiliza la plataforma para gestionar parcelas, asignar tareas y generar reportes, mientras que el agricultor se enfoca en ejecutar las labores asignadas y registrar datos fenológicos y ambientales. Además la aplicacion intercambia datos con servicios externos para obtener información climática en tiempo real y notificaciones.

![Context Diagram](./assets/images/software-architecture/context-diagram.png)

### 4.6.3. Software Architecture Container Diagrams

En el diagrama de contenedores de EcoTrack se representan los principales componentes del sistema y la forma en que interactúan entre sí. Los usuarios acceden inicialmente a través de la Landing Page, desde donde son redirigidos a la Single Page Application (SPA). En esta aplicación se gestionan funcionalidades clave como la creación de parcelas, la invitación de nuevos miembros, así como el registro y asignación de tareas.
La SPA se comunica con la API de EcoTrack, que a su vez realiza consultas a la base de datos para recuperar y administrar la información registrada en el sistema.

![Container Diagram](./assets/images/software-architecture/container-diagram.png)

### 4.6.4. Software Architecture Components Diagrams

En el diagrama de componentes de EcoTrack se muestran los distintos bounded contexts que conforman la arquitectura del sistema y sus interacciones. El contexto de Reports gestiona los reportes de cada parcela, Organization administra las organizaciones y la creación de parcelas, IAM maneja la autenticación y el control de accesos, Profile gestiona perfiles y suscripciones, y Monitoring & Control se encarga del monitoreo de las parcelas, integrándose con servicios externos como Open Weather Map. Todos estos contextos se comunican con la base de datos relacional, donde se almacena la información centralizada, y son consumidos por la Single Page Application, que actúa como interfaz principal para los usuarios.

![Component Diagram](./assets/images/software-architecture/component-diagram.png)

## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams
El diagrama representa una visión general del sistema Ecotrack, organizado en distintos bounded contexts que delimitan responsabilidades y entidades clave. En él se observa cómo los usuarios gestionan sus cuentas y perfiles, cómo las organizaciones administran parcelas, planes de suscripción y tipos de cultivos, y cómo se articulan los procesos de monitoreo y control mediante checklists, tareas, lecturas ambientales y alertas. Además, se incluyen objetos compartidos que permiten mantener coherencia en la identificación y manejo de valores comunes. En conjunto, este modelo refleja la estructura conceptual del dominio y la interacción entre sus principales componentes.

![Class Diagram](assets/images/software-architecture/class-diagram.png)


### IAM Bounded Context

Este diagrama corresponde al IAM Bounded Context, donde se gestiona la identidad y acceso de los usuarios. El agregado principal es User, que contiene atributos básicos como identificador, correo, contraseña cifrada, estado y rol asignado. Los roles pueden ser Agronomist o Farmer, mientras que el estado de la cuenta se define como Active, Inactive o Suspended. De esta manera, este contexto asegura el control de autenticación y autorización dentro del sistema.

![Class Diagram - IAM](assets/images/software-architecture/iam-diagram.png)


### Profile Bounded Context

Este diagrama representa el Profile Bounded Context, donde se gestionan los perfiles de los usuarios. El agregado principal es Profile, que contiene atributos como identificador, nombre completo, teléfono y foto de perfil. Cada perfil está asociado a un usuario específico mediante el userId. Este contexto permite almacenar y actualizar la información personal de los usuarios dentro del sistema.

![Class Diagram - Profile](assets/images/software-architecture/profile-diagram.png)


### Organization Bounded Context

Este diagrama corresponde al Organization Bounded Context, encargado de estructurar y administrar las organizaciones dentro del sistema. Aquí, el agregado principal Organization gestiona el nombre, estado, miembros, número máximo de parcelas y la suscripción activa. A su vez, las Plot representan las parcelas asociadas a la organización, con atributos como tamaño, ubicación y tipo de cultivo. Los cultivos se definen mediante la entidad PlantType, que puede vincularse a una lista de tipos predefinidos como papa, maíz, trigo, café, entre otros. Finalmente, el modelo incluye la entidad Subscription, que permite a la organización acceder a planes (AgroStart, AgroSmart, AgroExpert) y mantener control sobre la vigencia y estado de la suscripción. En conjunto, este contexto regula tanto la estructura organizacional como la gestión de recursos y servicios contratados.

![Class Diagram - Organization](assets/images/software-architecture/organization-diagram.png)

### Monitoring and Control Bounded Context

Este diagrama corresponde al Monitoring and Control Bounded Context, responsable de supervisar y gestionar las actividades y condiciones en campo. Aquí se incluyen los Checklists, que permiten organizar y dar seguimiento a las tareas (Task) asignadas a los perfiles, junto con fechas, materiales utilizados y su estado de avance. Asimismo, se registran lecturas ambientales (EnvironmentalReading) que son evaluadas frente a umbrales (Threshold) para detectar desviaciones en parámetros como temperatura, humedad o pH. Cuando se superan estos límites, se generan Alertas (Alert) con distintos niveles de severidad (INFO, WARNING, CRITICAL). Por otro lado, el contexto también incorpora sesiones de muestreo de plantas (PlantSamplingSession), que almacenan observaciones detalladas de altura, número de hojas y frutos, y permiten calcular promedios para análisis posteriores. En conjunto, este contexto asegura el control operativo mediante tareas planificadas, monitoreo en tiempo real y alertas tempranas que facilitan la toma de decisiones

![Class Diagram - Monitoring and Control](assets/images/software-architecture/monitoring-diagram.png)

### Reports Bounded Context

Este diagrama corresponde al Reports Bounded Context, encargado de la generación y gestión de reportes dentro del sistema. El agregado principal es Report, que contiene información sobre el usuario que lo solicita, la parcela asociada, el tipo de reporte, el rango de fechas, el estado del proceso y el contenido generado. Los reportes pueden ser de tipo Parcel o General, y su ciclo de vida se refleja en el ReportStatus, que abarca estados como REQUESTED, PROCESSING, GENERATED o FAILED. A través de este contexto, los usuarios pueden solicitar reportes, generar información consolidada y manejar errores en caso de fallos durante la generación.

![Class Diagram - Reports](assets/images/software-architecture/report-diagram.png)


## 4.8. Database Design
### 4.8.1. Database Diagrams

El diagrama de base de datos de EcoTrack refleja la estructura relacional del sistema, organizada en distintos esquemas que corresponden a los bounded contexts definidos previamente. Cada tabla contiene atributos clave y establece relaciones mediante claves foráneas para asegurar la integridad referencial.

![img_17.png](img_17.png)

# Capítulo V: Product Implementation, Validation & Deployment

El equipo ha definido un conjunto de herramientas para garantizar una configuración de entorno de desarrollo coherente; de esta maenra, se facilita una colaboración eficiente y el cumplimiento de los objetivos del proyecto. Estas herramientas abarcan diversas fases del ciclo de vida del producto.

## 5.1. Software Configuration Management

### Project Management

Trello: Utilizaremos Trello para gestionar el product backlog y planificar los sprints. Esta herramienta nos permitirá visualizar las tareas en tableros, asignar responsabilidades y hacer un seguimiento del progreso de manera clara y colaborativa.

Ruta de referencia: https://trello.com/

Whatsapp es la plataforma que usamos para la comunicación en tiempo real entre los miembros del equipo. A través de grupos organizados por temas y funciones, realizamos reuniones, coordinaciones diarias y soporte instantáneo durante todo el proceso de desarrollo.

### Product UX/UI Design

Figma se utiliza como la herramienta principal para el diseño de interfaces gráficas (UI) y la experiencia de usuario (UX). Permite la colaboración simultánea entre varios miembros del equipo en la creación de prototipos interactivos, estructuras visuales y pruebas de diseño.

Ruta de referencia: https://www.figma.com

UXPressia complementa el trabajo de UX al posibilitar la creación y documentación de User Personas, Customer Journey Maps y Empathy Maps. Esto ayuda al equipo a comprender mejor a los usuarios finales y a alinear las decisiones de diseño con sus necesidades.

Ruta de referencia: https://uxpressia.com

### Software Development

Rider es el entorno de desarrollo integrado (IDE) que emplean los desarrolladores del equipo para escribir y depurar código en tecnologías web. Su integración con sistemas de control de versiones, linters y herramientas modernas de desarrollo lo convierte en un entorno robusto.

Ruta de referencia: https://www.jetbrains.com/es-es/rider/

GitHub se utiliza como repositorio remoto centralizado para almacenar y sincronizar el código del proyecto. También se emplea para la revisión del código (pull requests), registro de incidencias, documentación del proyecto y automatización de tareas de despliegue.

Ruta de referencia: https://github.com

### Software Testing

Gherkin es un sistema de etiquetado utilizado para describir los criterios de aceptación de la estructura de una user story.

Ruta de referencia: https://cucumber.io/docs/gherkin

### 5.1.1. Software Development Environment Configuration

En esta sección se describen las herramientas de software seleccionadas para dar soporte a las distintas fases del ciclo de vida del producto digital. Se incluyen sus nombres, objetivos específicos dentro del proyecto y los enlaces de acceso o descarga, diferenciando entre soluciones SaaS y aplicaciones instalables.

* ### Gestión de Proyectos y Tareas

| **Herramienta**     | **Uso principal**                                                                                        | **Enlace / Ruta de Acceso**                              |
| ------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------- |
| **Trello**          | Organización de tareas y entregables mediante tableros ágiles, tanto a nivel individual como por módulo. | [https://trello.com](https://trello.com)                 |
| **Pivotal Tracker** | Seguimiento de proyectos con enfoque en historias de usuario, métricas de velocidad y predicción.        | [https://pivotaltracker.com](https://pivotaltracker.com) |


* ### Gestión de Requisitos

| **Herramienta**     | **Uso principal**                                                                                        | **Enlace / Ruta de Acceso**                              |
| ------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------- |
| **Trello**          | Organización de tareas y entregables mediante tableros ágiles, tanto a nivel individual como por módulo. | [https://trello.com](https://trello.com)                 |
| **Pivotal Tracker** | Seguimiento de proyectos con enfoque en historias de usuario, métricas de velocidad y predicción.        | [https://pivotaltracker.com](https://pivotaltracker.com) |

* ### Diseño de Experiencia y UI/UX

| **Herramienta** | **Uso principal**                                                            | **Enlace / Ruta de Acceso**                      |
| --------------- | ---------------------------------------------------------------------------- | ------------------------------------------------ |
| **Figma**       | Diseño colaborativo de wireframes, mockups y prototipos navegables.          | [https://figma.com](https://figma.com)           |
| **Lucidchart**  | Elaboración de user flows, wireflows y diagramas de procesos o arquitectura. | [https://lucidchart.com](https://lucidchart.com) |
| **UXPressia**   | Creación de User Personas, Empathy Maps, Journey Maps e Impact Maps.         | [https://uxpressia.com](https://uxpressia.com)   |
| **Miro**        | Diseño colaborativo en tiempo real de mapas de experiencia (As-Is y To-Be).  | [https://miro.com](https://miro.com)             |

* ### Pruebas de Software

| **Herramienta** | **Uso principal**                                                                                                                |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| **Gherkin**     | Lenguaje para definir criterios de aceptación de **User Stories** en un formato entendible por todos los integrantes del equipo. |


* ### Desarrollo de Software

| **Herramienta / Tecnología** | **Uso principal**                                                                                        | **Enlace / Ruta de Descarga**                                                                          |
| ---------------------------- | -------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| **WebStorm**                 | Desarrollo de la landing page con HTML5, CSS3, JavaScript y Tailwind CSS.                                | [https://www.jetbrains.com/webstorm](https://www.jetbrains.com/webstorm)                               |
| **IntelliJ IDEA**            | Creación y edición del archivo README.md para la documentación del proyecto.                             | [https://www.jetbrains.com/idea](https://www.jetbrains.com/idea)                                       |
| **HTML5**                    | Lenguaje de marcado para estructurar el contenido de la landing page.                                    | [https://developer.mozilla.org/docs/Web/HTML](https://developer.mozilla.org/docs/Web/HTML)             |
| **CSS3**                     | Lenguaje de estilos para definir la apariencia visual de la landing page.                                | [https://developer.mozilla.org/docs/Web/CSS](https://developer.mozilla.org/docs/Web/CSS)               |
| **JavaScript**               | Lenguaje de programación para manipular el DOM e implementar la internacionalización en la landing page. | [https://developer.mozilla.org/docs/Web/JavaScript](https://developer.mozilla.org/docs/Web/JavaScript) |

* ### Diseño de Arquitectura de Software

| **Herramienta**     | **Uso principal**                                                                             | **Enlace / Ruta de Acceso**                                |
| ------------------- | --------------------------------------------------------------------------------------------- | ---------------------------------------------------------- |
| **Structurizr DSL** | Modelado de arquitectura con el enfoque C4, mediante la técnica *Diagrams-as-Code*.           | [https://structurizr.com/dsl](https://structurizr.com/dsl) |
| **PlantUML**        | Creación de diagramas UML a partir de texto, compatible con Markdown y documentación técnica. | [https://plantuml.com](https://plantuml.com)               |
| **Vertabelo**       | Diseño visual y profesional de bases de datos relacionales.                                   | [https://vertabelo.com](https://vertabelo.com)             |

* ### Despliegue de Software
| **Herramienta / Plataforma** | **Uso principal**                                    | **Enlace / Ruta de Acceso**                        |
| ---------------------------- | ---------------------------------------------------- | -------------------------------------------------- |
| **Netlify**                  | Despliegue automático y gratuito de la landing page. | [https://www.netlify.com](https://www.netlify.com) |

* ### Documentación de Software

| **Herramienta / Recurso** | **Uso principal**                                                                                      | **Enlace / Ruta de Acceso**                                                                                        |
| ------------------------- | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ |
| **IntelliJ IDEA**         | Edición y mantenimiento del archivo README.md asociado a la documentación del proyecto.                | [https://www.jetbrains.com](https://www.jetbrains.com)                                                             |
| **GitHub**                | Repositorio con control de versiones, utilizado además como espacio de documentación en issues y PRs.  | [https://github.com](https://github.com)                                                                           |
| **Git**                   | Sistema distribuido de control de versiones para la gestión del código fuente.                         | [https://git-scm.com](https://git-scm.com)                                                                         |
| **GitFlow Workflow**      | Modelo de ramificación para mantener el código y la documentación organizados.                         | [https://nvie.com/posts/a-successful-git-branching-model](https://nvie.com/posts/a-successful-git-branching-model) |
| **Conventional Commits**  | Convención de mensajes de commit para mejorar la trazabilidad y facilitar la generación de changelogs. | [https://www.conventionalcommits.org](https://www.conventionalcommits.org)                                         |

### 5.1.2. Source Code Management

El equipo empleará GitHub como repositorio de alojamiento y Git como sistema de control de versiones para todos los entregables del proyecto Demy. Se aplicará la estrategia de ramificación GitFlow Workflow, con el uso de Semantic Versioning y mensajes estructurados bajo la convención de Conventional Commits.

#### Repositorios del Proyecto

| **Producto**              | **Repositorio GitHub**                                                                                                                           |
|---------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| **Organización Agromind** | [https://github.com/AgroMind-Aplicaciones-Web-7414](https://github.com/AgroMind-Aplicaciones-Web-7414)                                           |
| **Landing Page**          | [https://github.com/AgroMind-Aplicaciones-Web-7414/ecotrack-report](https://github.com/AgroMind-Aplicaciones-Web-7414/ecotrack-report)           |
| **Report**                | [https://github.com/AgroMind-Aplicaciones-Web-7414/ecotrack-landingpage](https://github.com/AgroMind-Aplicaciones-Web-7414/ecotrack-landingpage) |
| **Frontend**              | [https://github.com/AgroMind-Aplicaciones-Web-7414/ecotrack-frontend](https://github.com/AgroMind-Aplicaciones-Web-7414/ecotrack-frontend)       |
| **Backend**               | [https://github.com/AgroMind-Aplicaciones-Web-7414/ecotrack-backend](https://github.com/AgroMind-Aplicaciones-Web-7414/ecotrack-backend)         |
#### Modelo GitFlow
Se seguirá el enfoque planteado por Vincent Driessen, el cual define dos ramas principales:

* main: contiene las versiones estables listas para producción.
* develop: integra nuevas funcionalidades antes de pasar al entorno de producción.

  | **Tipo de rama** | **Uso principal**                                | **Convención de nombres**      | **Ejemplo**               |
  |------------------|--------------------------------------------------|--------------------------------|---------------------------|
  | **feature**      | Desarrollo de funcionalidades nuevas.            | `feature/<nombre-descriptivo>` | `feature/sprint1-salim`   |
  | **release**      | Preparación de una versión previa al despliegue. | `release/vX.Y.Z`               | `release/v1.0.0`          |
  | **hotfix**       | Corrección rápida de errores en producción.      | `hotfix/<problema>`            | `hotfix/fix-crash-navbar` |

#### Versionado Semántico

Se implementará el esquema Semantic Versioning 2.0.0, con el formato:

**MAJOR.MINOR.PATCH**

* **MAJOR**: cambios incompatibles con versiones anteriores.

* **MINOR**: incorporación de nuevas funciones compatibles.

* **PATCH**: corrección de errores o mejoras menores.

#### Conventional Commits

Los mensajes de commit seguirán el estándar Conventional Commits para asegurar trazabilidad y generar changelogs automáticos.

**Formato general:**
<tipo>(opcional-scope): descripción breve


* Tipos de commit definidos:

* feat: nueva funcionalidad

* fix: corrección de errores

* docs: cambios en documentación

* style: ajustes de formato (espacios, comas, etc.)

* refactor: modificaciones de código sin impacto en funciones o errores

* test: adición o modificación de pruebas

* chore: tareas de mantenimiento o generales

### 5.1.3. Source Code Style Guide & Conventions

Con el objetivo de mantener un código ordenado, consistente y fácil de mantener entre todos los miembros del equipo, se han definido las siguientes convenciones. Todas las variables, funciones, clases, archivos y elementos estarán en inglés.

- Se utilizará **inglés** como idioma único para nombres de variables, funciones, clases, comentarios y documentación.
- Se evitarán abreviaciones innecesarias y nombres genéricos como `data1`, `temp`, `info`, etc.

**HTML**
Atributos en minúsculas y nombres de clase con **kebab-case** (`section-title`, `main-container`).
- Estructura semántica clara: uso de etiquetas como `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`.
- Sangría con 2 espacios.
- Atributos ordenados de manera lógica: `id`, `class`, `type`, `name`, `placeholder`, `value`, `required`, etc.

**CSS**

- Para clases personalizadas: usar **kebab-case**.
- Se agruparán clases de utilidad por orden lógico (layout -> spacing -> color -> typography).

**Google TypeScript Style Guide**

Basado en el [Google TypeScript Style Guide](https://google.github.io/styleguide/tsguide.html), se adoptan las siguientes reglas para mantener un código limpio y coherente:

Nombres y sintaxis:
- **camelCase** para variables, funciones y parámetros.
- **PascalCase** para clases, interfaces, enums y tipos.
- Constantes con `UPPER_CASE_WITH_UNDERSCORES` si son globales.

Módulos y imports:
- Preferir **imports explícitos y ordenados**: primero bibliotecas externas, luego internas.
- Evitar `default exports`, usar siempre `export const` o `export class`.

Tipado y declaraciones:
- Siempre tipar explícitamente los parámetros y valores de retorno de funciones.
- Evitar `any` excepto cuando sea estrictamente necesario.
- Usar `readonly` para propiedades que no deben cambiarse.
- Interfaces en lugar de `type` cuando sea posible.

Buenas prácticas:
- Preferir `const` sobre `let`, y evitar `var`.
- Evitar usar `this` fuera de clases.
- No mezclar funciones y lógica en componentes — delegar a servicios.

**Vue.js**

- Seguir la [Vue 3 Style Guide (Oficial)](https://vuejs.org/style-guide/), especialmente las reglas **“Essentials”** y **“Strongly Recommended”**.
- Componentes deben nombrarse en **PascalCase** (`UserCard.vue`, `HeroSection.vue`).
- Archivos `.vue` deben tener una única raíz (`<template>`, `<script>`, `<style>`).
- Uso claro de `v-bind`, `v-model`, `v-if`.
- Eventos deben seguir `kebab-case` en los templates (`@form-submitted`).
- Evitar lógica compleja dentro de los templates.
- Separar componentes base (`BaseButton`, `BaseInput`) de componentes de dominio.

**Pruebas / Gherkin**

En caso de usar Gherkin (para especificaciones o pruebas): <br>
- Usaremos el formato Given When And Then


### 5.1.4. Software Deployment Configuration

*Figura 1.* Configuración de GitHub Pages en el repositorio de la landing page.

![Form](assets/images/deployment1.PNG)


*Figura 2.* Se ingresó a setting y luego a pages.

![Form](assets/images/deployment2.PNG)

*Figura 3.* seleccionamos la rama en la que se encuentre alojado el proyecto.

![Form](assets/images/deployment3.PNG)


*Figura 4.* Esperamos la URL autogenerada por githubpages.

![Form](assets/images/deployment5.PNG)

- Enlace de la landing page desplegada: [Evidencia landing page](https://agromind-aplicaciones-web-7414.github.io/ecotrack-landingpage/)

### 5.2. Landing Page, Services & Applications Implementation
#### 5.2.1. Sprint 1

##### 5.2.1.1. Sprint Planning 1

Esta sección describe los aspectos principales tratados durante el Sprint Planning Meeting que dio inicio al Sprint n.
En esta reunión, el equipo definió los objetivos específicos del sprint, seleccionó los elementos del Product Backlog que serían abordados y estableció un plan de trabajo que permitiera alcanzar los entregables comprometidos.

A continuación, se presenta el cuadro de resumen del Sprint Planning Meeting, el cual sintetiza los puntos clave acordados:

## Sprint Planning Background

| Campo                          | Contenido                                                                 |
|--------------------------------|---------------------------------------------------------------------------|
| **Sprint 1**                   | Sprint 1                                                                  |
| **Date**                       | 03/09/2025                                                                |
| **Time**                       | 15:00 PM                                                               |
| **Location**                   | Reunión realizada presencial (sede monterrico UPC)         |
| **Prepared By**                |  Amaro Villar, Anjali                                            |
| **Attendees (to planning meeting)** | Amaro Villar Anjali, Tuesta Marin Romina, Baquerizo Cirilo Aaron Santiago, Mostajo Orosco Maria Fernanda y Navarro Correa César Augusto |
| **Sprint 1 – 1 Review Summary** | No aplica (primer sprint) |
| **Sprint 1 – 1 Retrospective Summary** | No aplica (primer sprint) |

| Campo                          | Contenido                                                                 |
|--------------------------------|---------------------------------------------------------------------------|
| **Sprint 1 Goal**            | **Nuestro enfoque está** en establecer la estructura base y lanzar la versión inicial de la landing page del producto. **Creemos que** esto brindará claridad sobre el propósito del producto y servirá como primer punto de contacto con potenciales usuarios y partes interesadas. **Esto se confirmará** cuando la landing page esté disponible públicamente y muestre de forma clara la propuesta de valor, mientras que la documentación interna incluya los wireframes y diagramas aprobados que guiarán el desarrollo futuro.             |
| **Sprint 1 Velocity**        | 26 points |

## Cálculo de Story Points Totales del Sprint 1

| ID     | Historia                                          | Points |
|--------|--------------------------------------------------|--------|
| LPS01  | Información de la Landing Page                    | 5      |
| LPS02  | Visualizar información de la página               | 5      |
| LPS03  | Visualización de beneficios y características     | 5      |
| LPS04  | Consultar planes y precios                        | 5      |
| LPS05  | Formulario de contacto                            | 3      |
| LPS06  | Sección de testimonios                            | 3      |
| **TOTAL** |                                                | **26** |


| **Sum of Story Points**      | 26 story points |


##### 5.2.1.2. Aspect Leaders and Collaborators

| Team Member (Last Name, First Name)   | Github Username        | wireframes y MockUps landing |  Visualización beneficios y características | Consultar planes y precios | Formulario de contacto | Sección de testimonios | Despliegue de servicio |
|-----------|----------------------|-----------|----------------------|-----------|----------------------|-----------|-----------|
| Amaro Villar Anjali              |     njlmrvllr   |    (C)   |     (C)     |    (C)      |  (C)   |     (L)     |    (C)      |    (C)      |
|  Romina Alejanda Tuesta Marin    |     Romimi1     |    (C)   |     (L)     |    (L)      |  (C)   |     (C)     |    (L)      |    (L)      |
|  Baquerizo Cirilo Aaron Santiago |  AaronBaquerizo2005  |    (L)   |     (C)     |    (C)      |   (C)   |     (C)     |    (C)      |    (C)      |
|  Mostajo Orosco Maria Fernanda   |     Mafer-m30   |    (L)   |     (C)     |    (C)      |   (L)   |     (C)     |    (C)      |    (C)      |
| Navarro Correa César Augusto     |    csr555-ui    |    (C)   |     (C)     |    (C)      |   (C)   |     (C)     |    (C)      |    (C)      |



##### 5.2.1.3. Sprint Backlog 1

En este sprint se desarrollará y desplegará la Landing Page de EcoTrack, que servirá como punto de presentación del producto. Se crearán las secciones informativas clave (propuesta de valor, explicación del producto, beneficios, planes y precios, formulario de contacto y testimonios), estableciendo así las bases visuales y funcionales del proyecto.

Herramienta de control: Trello

<img alt="upc-logo" src="/assets/images/trello_sprint1.PNG" /><br>

URL del Board: [(Link trello)](https://trello.com/b/eZyvjxmL/sprint-1-ecotrack)


| User Story |                                               | Work-Item / Task |                                      |                                                                                         |                        |                  |                                                    |
| ---------- | --------------------------------------------- | ---------------- | ------------------------------------ | --------------------------------------------------------------------------------------- | ---------------------- | ---------------- | -------------------------------------------------- |
| **Id**     | **Title**                                     | **Id**           | **Title**                            | **Description**                                                                         | **Estimation (Hours)** | **Assigned To**  | **Status** (To-do / In-Process / To-Review / Done) |
| LPS01      | Información de la Landing Page                | T01              | Diseño de wireframe                  | Crear wireframe de la estructura inicial de la landing                                  | 4                      | Maria Mostajo | Done                                               |
|            |                                               | T02              | Desarrollo de encabezado y subtítulo | Implementar el encabezado con la propuesta de valor y subtítulo de beneficios clave     | 4                      |  Aaron Baquerizo | Done                                               |
| LPS02      | Visualizar información de la página           | T03              | Sección “About”                      | Implementar la sección About con descripción breve del producto y gráficos ilustrativos | 5                      |   Romina Tuesta | Done                                               |
|            |                                               | T04              | Métricas clave                       | Incluir métricas clave que refuercen la propuesta de valor                              | 5                      |   Aaron Baquerizo | Done                                               |
| LPS03      | Visualización de beneficios y características | T05              | Listado de beneficios                | Crear sección “Servicios” con lista de beneficios e íconos                              | 4                      |  Romina Tuesta | Done                                               |                                                                                    
| LPS04      | Consultar planes y precios                    | T07              | Sección de planes                    | Crear la sección con los diferentes planes, precios y botones “Start”                 | 5                      |  Maria Mostajo  | In-Process                                         |
|            |                                               | T08              | FAQ de precios                       | Añadir íconos de ayuda con menú FAQ sobre pagos y condiciones                           | 6                      |  Cesar Navarro  | To-do                                              |
| LPS05      | Formulario de contacto                        | T09              | Implementación del formulario        | Diseñar y desarrollar formulario de contacto con validaciones                           | 4                      |  Maria Mostajo | In-Process                                         |
|            |                                               | T10              | Confirmación por correo              | Configurar envío de correo de confirmación al visitante                                 | 5                      |  Anjali Amaro  | To-do                                              |
| LPS06      | Sección de testimonios                        | T11              | Diseño de testimonios                | Implementar testimonios con foto, nombre y comentario                       | 4                      | Romina Tuesta  | To-Review                                          |


##### 5.2.1.4. Development Evidence for Sprint Review

En esta sección se presentan los avances en la implementación de la solución EcoTrack, considerando los productos contemplados en el alcance del Sprint: Landing Page. Durante este periodo se trabajó principalmente en el desarrollo de la Landing Page, incorporando mejoras visuales, de usabilidad y funcionalidad. Entre los principales avances se encuentran la creación de la página principal, la integración de estilos y animaciones, la optimización del comportamiento de la navegación y la incorporación de nuevas funciones interactivas.

A continuación, se detallan los commits realizados en los repositorios vinculados a la implementación:

| Repository |   Branch    | Commit Id |  Commit Message  |   Commit Message Body    |   Commited on (Date)  |        
| ---------- | ----------- | --------- | ---------------- | ------------------------ | --------------------- | 
| Romini1/github.com/AgroMind-Aplicaciones-Web-7414/ecotrack-landingpage | develop     |   1bc1861   |    feat: add index.html as main page    |  Se creó el archivo index.html como la página principal de la landing, estructurando la base inicial del proyecto.                        |    18/09/25     | 
| Romini1/github.com/AgroMind-Aplicaciones-Web-7414/ecotrack-landingpage | develop     |   d9866fd   |    feat: update testimonials            | Se actualizaron las secciones de testimonios para mejorar la credibilidad y experiencia de usuario                         |    19/09/25     | 
| Romini1/github.com/AgroMind-Aplicaciones-Web-7414/ecotrack-landingpage | develop     |   c40012d   |  feat: add css and main.js for animations  |  Se añadieron los archivos style.css y main.js para implementar animaciones y mejorar la interacción visual                        |   19/09/25       | 
| Romini1/github.com/AgroMind-Aplicaciones-Web-7414/ecotrack-landingpage | develop     |   62b0113   |    fix: navbar on html                  |   Se corrigió el comportamiento del navbar para mejorar la navegación en la landing.                       |     19/09/25    | 
| Romini1/github.com/AgroMind-Aplicaciones-Web-7414/ecotrack-landingpage | develop     |   8b15636   |    fix: behavior of scrolling           |   Se ajustó el scroll de la página para hacerlo más fluido y mejorar la experiencia del usuario.                       |     19/09/25    | 
| Romini1/github.com/AgroMind-Aplicaciones-Web-7414/ecotrack-landingpage | develop     |   7fb18b8   |    feat: add new funtion for slider     |   Se implementó una nueva función en el slider para permitir transiciones más dinámicas entre secciones.                       |     19/09/25    | 


##### 5.2.1.5. Execution Evidence for Sprint Review

Durante este Sprint se avanzó de manera significativa en el desarrollo de la Landing Page del proyecto EcoTrack, la cual constituye el primer punto de contacto con los usuarios. Se implementó la estructura base con la página principal, se integraron estilos y animaciones, y se añadieron funcionalidades interactivas como el slider y un scroll más fluido. Asimismo, se realizaron correcciones en la navegación para garantizar una experiencia más clara e intuitiva, además se implementó exitosamente la funcionalidad del cambio de idioma, de español a ingles.

Con estos avances, se ha logrado contar con una primera versión navegable de la landing page, lo que permite mostrar la propuesta de valor de EcoTrack y establecer la base para siguientes mejoras visuales y técnicas.


*Figura 1.* Página principal con navbar y sección de bienvenida.

![Hero](assets/images/dep_hero.PNG)


*Figura 2.* Sección acerca de EcoTrack.

![About](assets/images/dev_about.PNG)


*Figura 3.* Sección acerca de servicios.

![Services](assets/images/dev_servicios.PNG)


*Figura 4.* Sección de testimonios.

![Testimonials](assets/images/dev_testimonios.PNG)
![numers](assets/images/dev_num.PNG)

*Figura 5.* Sección de planes y subscripción.

![Plans](assets/images/dev_planes.PNG)


*Figura 6.* Sección de formulario de contacto.

![Form](assets/images/dev_form.PNG)


#### Video demostrativo

Se preparó un video donde se ilustra la navegación en la landing page y se explican las funcionalidades desarrolladas en este Sprint:
https://upcedupe-my.sharepoint.com/:v:/g/personal/u202211706_upc_edu_pe/EVzKGDbWv11BtdsS_S72uEsBgyAfb5FxL1TbxndENcTm5A?e=MW9rDg

##### 5.2.1.6. Services Documentation Evidence for Sprint Review

En este Sprint, el trabajo realizado se centró en el desarrollo de la Landing Page de EcoTrack, implementada únicamente con HTML, CSS y JavaScript. Dado que se trata de una página estática cuyo alcance se limita a la presentación de información y a la interacción en el lado del cliente, no se definieron ni consumieron Web Services.

En consecuencia, durante este Sprint no corresponde la elaboración de documentación con OpenAPI (Swagger), ya que esta herramienta se utiliza exclusivamente para describir y documentar APIs REST que exponen endpoints de un backend. La integración con Web Services y su respectiva documentación será abordada en Sprints posteriores, cuando la solución incluya funcionalidades dinámicas que requieran intercambio de datos entre frontend y backend.



##### 5.2.1.7. Software Deployment Evidence for Sprint Review

Durante este Sprint se avanzó en los procesos de Deployment relacionados con la solución EcoTrack, con el objetivo de asegurar la disponibilidad de los productos desarrollados para su validación y demostración. Dentro de este Sprint, el esfuerzo principal estuvo orientado al despliegue de la Landing Page, que fue implementada con HTML, CSS y JavaScript.

El despliegue se realizó utilizando GitHub Pages, lo que permitió contar con un entorno accesible de manera pública sin necesidad de un proveedor de cloud externo. Esta estrategia fue seleccionada por su facilidad de integración con los repositorios de GitHub y por brindar un proceso automatizado de publicación a partir de la rama develop del proyecto.

Acciones realizadas en el proceso de Deployment

1. Creación y configuración del repositorio en GitHub.
   Se configuró el repositorio ecotrack-landingpage en la cuenta de GitHub del equipo.

2. Configuración de GitHub Pages.

- Se habilitó la opción de GitHub Pages en la sección de Settings.

- Se seleccionó la rama develop como fuente de publicación.

- Se configuró la carpeta raíz del proyecto como directorio base de la publicación.

3. Automatización de despliegue.
   Gracias a la integración nativa de GitHub Pages, cada nuevo commit realizado en la rama develop se despliega automáticamente en la URL pública asignada.

4. Validación del despliegue.
   Se realizó la verificación de la publicación, comprobando que la landing page se visualiza correctamente en la dirección generada por GitHub Pages.

#### Evidencia del Deployment

*Figura 1.* Configuración de GitHub Pages en el repositorio de la landing page.

![Form](assets/images/deployment1.PNG)


*Figura 2.* Se ingresó a setting y luego a pages.

![Form](assets/images/deployment2.PNG)

*Figura 3.* seleccionamos la rama en la que se encuentre alojado el proyecto.

![Form](assets/images/deployment3.PNG)


*Figura 4.* Esperamos la URL autogenerada por githubpages.

![Form](assets/images/deployment5.PNG)


#### Link a continuación:

https://agromind-aplicaciones-web-7414.github.io/ecotrack-landingpage/


##### 5.2.1.8. Team Collaboration Insights during Sprint

Dentro del insight during sprint presentamos los colaboradores del desarollo de la landing page y la cantidad de commits que realizaron:

![colaboratos](assets/images/C_INSIGHTS.PNG) 

Entre los tres colaboradores que podemos observar se encuentran Romina Tuesta, Anjali Amaro y Cesar Navarro, siendo Romina la que cuenta con la mayor cantidad de commits, continuado por Anjali y finalmente Cesar.

### 5.2.1. Sprint 2

#### 5.2.1.1. Sprint Planning 2

| **Campo** | **Contenido** |
|------------|----------------|
| **Sprint 2** | Sprint 2 |
| **Date** | 01/10/25 |
| **Time** | 15:00 PM |
| **Location** | Reunión virtual (discord) |
| **Prepared By** | Tuesta Marín, Romina |
| **Attendees (to planning meeting)** | Tuesta Marín Romina, Amaro Villar Anjali, Baquerizo Cirilo Aaron Santiago, Mostajo Orosco María Fernanda y Navarro Correa César Augusto |
| **Sprint 2 – 1 Review Summary** | Se completó la estructura base y el despliegue de la landing page del producto. Además, se aprobó la documentación técnica (wireframes, diagramas y guía de estilos) que servirá como referencia visual para el desarrollo de la interfaz del sistema. |
| **Sprint 2 – 1 Retrospective Summary** | Se identificó la necesidad de definir un flujo de commits más ordenado en GitHub y una mejor asignación de tareas por módulos. Se acordó establecer una convención de nombres para componentes y commits, además de reuniones de seguimiento cada 3 días. |

---

| **Campo** | **Contenido** |
|------------|----------------|
| **Sprint 2 Goal** |Nuestro enfoque se centra en entregar la primera versión funcional del front end de EcoTrack con Vue.js y Vite, implementando las vistas principales, el enrutamiento y una estructura de componentes reutilizables. Buscamos ofrecer una **interfaz coherente y dinámica**, validada mediante datos simulados. Esto se confirmará cuando los usuarios puedan navegar entre las vistas sin errores y el equipo de desarrollo pueda ampliar las funcionalidades sin alterar la estructura base.
 |
| **Sprint 2 Velocity** | 28 points |



#### 5.2.2.2. Aspect Leaders and Collaborators.

| Team Member (Last Name, First Name)   | Github Username        | wireframes y MockUps frontend | Vista Inicio de Sesión | Vista de Dashboard | Vista de perfil de usuario | Establecer estructura | Despliegue de servicio |
|-----------|----------------------|-------------------------------|------------------------|--------------------|----------------------------|-----------------------|------------------------|
| Amaro Villar Anjali              |     njlmrvllr   | (C)                           | (C)                    | (L)                | (C)                        | (L)                   | (L)                    |    (C)      |
|  Romina Alejanda Tuesta Marin    |     Romimi1     | (C)                           | (C)                    | (L)                | (C)                        | (L)                   | (C)                    |    (L)      |
|  Baquerizo Cirilo Aaron Santiago |  AaronBaquerizo2005  | (L)                           | (C)                    | (C)                | (C)                        | (C)                   | (C)                    |    (C)      |
|  Mostajo Orosco Maria Fernanda   |     Mafer-m30   | (L)                           | (L)                    | (C)                | (L)                        | (C)                   | (C)                    |    (C)      |
| Navarro Correa César Augusto     |    csr555-ui    | (C)                           | (C)                    | (C)                | (C)                        | (C)                   | (C)                    |    (C)      |

#### 5.2.2.3. Sprint Backlog 2.
En este sprint se desarrollará y desplegará la primera version del Front-end completo de EcoTrack. El equipo se enfocó en crear todas las vistas criticas del sistema utilizando una API simulada. Esto estableció las bases visuales y funcionales que permitieron la validación temprana de la experiencia de usuario.

Herramienta de control: Trello

![Trello](assets/images/screenshots/trello-sprint2.png)

URL del Board: [(Link trello)](https://trello.com/b/LNvUn7us/sprint2-ecotrack)




| User Story ID | User Story Title     | Task ID | Task Title                         | Description                                                                                                               | Estimation<br/>(Hours) | Asigned To | Status      |
|:--------------|:---------------------|:--------|:-----------------------------------|:--------------------------------------------------------------------------------------------------------------------------|:----------------------:|:-----------|:------------|
| US01          | Crear organización   | T03     | Desarrollo de Formulario Org       | Diseñar y maquetar el formulario de "Crear Organización" con validaciones FE.                                             |           6            | Maria      | Done        |
|               |                      | T04     | Implementar Flujo de Creación      | Desarrollar la lógica de creación y la visualización de la vista de inicio del Agrónomo.                                  |           6            | Maria      | Done        |
| US02          | Invitar miembros     | T06     | Desarrollo de Flujo de Invitación  | Diseñar e implementar la modal de "Invitar Miembro" y el flujo de envío de invitación simulada.                           |           9            | Maria      | Done        |
| US04          | Bitácora de parcela  | T08     | Desarrollo de Bitácora y Registro  | Diseñar e implementar la vista de la línea de tiempo y el formulario "Registrar Actividad".                               |           10           | Romina     | Done        |
| US06          | Historial de cultivo | T09     | Desarrollo de Historial/Filtros    | Diseñar e implementar la vista de "Historial de Cultivo" y los componentes de filtrado.                                   |           9            | Anjali     | In-Progress |
| US10          | Creación de parcela  | T05     | Desarrollo de Formulario Parcela   | Diseñar e implementar el formulario "Crear Parcela" con campos de datos y ubicación simulada.                             |           9            | Maria      | Done        |
| US13          | Registro de Cultivo  | T01     | Diseño de Formulario de Registro   | Diseñar e implementar el Front-end del formulario de registro (nombre, ubicación simulada, superficie, fecha de siembra). |           8            | Aaron      | Done        |
|               |                      | T02     | Implementar Lógica de Guardado     | Desarrollar la lógica de Front-end para guardar la información del cultivo con mensaje de confirmación (usando fake API). |           7            | Aaron      | Done        |
| US16          | Creación de tareas   | T10     | Desarrollo de Formulario Tarea     | Diseñar e implementar la modal "Crear Tarea" (responsable, fecha, prioridad, checklist).                                  |           9            | Romina     | Done        |
| US18          | Iniciar tarea        | T11     | Implementar Botón Iniciar          | Diseñar la interfaz de la tarea en detalle y la lógica del botón "Iniciar Tarea" (cambio de estado).                      |           5            | Aaron      | Done        |
| US19          | Completar tarea      | T12     | Implementar Checklist y Cierre     | Desarrollar la interacción de la checklist y el flujo de cierre (botón "Completar Tarea").                                |           5            | Aaron      | Done        |
| US21          | Reporte general      | T01     | Diseño e Implemntación de Reportes | Diseñar la interfaz de visualizacion de reportes y el flujo de solicitud de un nuevo reporte                              |           12           | Anjali     | Done        |
| US25          | Editar perfil        | T02     | Desarrollo de Edición              | Diseñar e implementar la pantalla de configuración y la lógica de actualización con fake API.                             |           9            | Cesar      | In-Progress |


#### 5.2.2.4. Development Evidence for Sprint Review.

En esta sección se presentan los avances del desarrollo de la página web y las mejoras implementadas en la solución EcoTrack, enfocadas principalmente en la Landing Page. Durante este periodo, el equipo trabajó en la consolidación del Front-End, incorporando nuevas funcionalidades, componentes reutilizables, simulaciones de datos mediante una Fake API, integración de servicios externos y optimización del código existente. Asimismo, se mejoraron los mecanismos de traducción, la organización del entorno de desarrollo y la documentación técnica del proyecto, fortaleciendo la arquitectura y la mantenibilidad del código.

<table border="1" cellspacing="0" cellpadding="6">
  <thead>
    <tr>
      <th>Repositorio</th>
      <th>Rama</th>
      <th>ID de Commit</th>
      <th>Mensaje de Commit</th>
      <th>Descripción del Commit</th>
      <th>Fecha de Commit</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ecotrack-frontend</td>
      <td>develop</td>
      <td>9558c83</td>
      <td>feat: upload bounded context</td>
      <td>-</td>
      <td>02/10/2025</td>
    </tr>
    <tr>
      <td>ecotrack-frontend</td>
      <td>develop</td>
      <td>021dd42</td>
      <td>feat: add user-organization  component</td>
      <td>-</td>
      <td>06/10/2025</td>
    </tr>
    <tr>
      <td>ecotrack-frontend</td>
      <td>feature/sprint-2-maria</td>
      <td>b643780</td>
      <td>chore: upload db.json</td>
      <td>-</td>
      <td>07/10/2025</td>
    </tr>
    <tr>
      <td>ecotrack-frontend</td>
      <td>feature/sprint-2-romina</td>
      <td>b643780</td>
      <td>chore: upload db.json</td>
      <td>-</td>
      <td>07/10/2025</td>
    </tr>
    <tr>
      <td>ecotrack-frontend</td>
      <td>feature/sprint-2-romina</td>
      <td>740f294</td>
      <td>chore: upload new files</td>
      <td>-</td>
      <td>07/10/2025</td>
    </tr>
    <tr>
      <td>ecotrack-frontend</td>
      <td>feature/sprint-2-aaron</td>
      <td>a261aa1</td>
      <td>feat: add task and cultivation components, and integrate external weather api</td>
      <td>-</td>
      <td>10/10/2025</td>
    </tr>
    <tr>
      <td>ecotrack-frontend</td>
      <td>feature/sprint-2-anjali</td>
      <td>5eaee94</td>
      <td>feat(fake-api): add json-server and configure fake api.</td>
      <td>-</td>
      <td>10/10/2025</td>
    </tr>
    <tr>
      <td>ecotrack-frontend</td>
      <td>feature/sprint-2-anjali</td>
      <td>c6401bd</td>
      <td>feat: add environment configuration and base API classes</td>
      <td>-</td>
      <td>10/10/2025</td>
    </tr>
    <tr>
      <td>ecotrack-frontend</td>
      <td>feature/sprint-2-aaron</td>
      <td>58f72f9</td>
      <td>feat: add initial API contract and frontend structure documentation</td>
      <td>-</td>
      <td>10/10/2025</td>
    </tr>
    <tr>
      <td>ecotrack-landingpage</td>
      <td>main</td>
      <td>ec1bc58</td>
      <td>feat: update translations and improve code</td>
      <td>-</td>
      <td>10/10/2025</td>
    </tr>
  </tbody>
</table>

#### 5.2.2.5. Execution Evidence for Sprint Review.

- Login 
![img_11.png](assets/images/sprint2/img_11.png)

- Register
![img_12.png](assets/images/sprint2/img_12.png)

- Organization 
![img_6.png](assets/images/sprint2/img_6.png)

- Plots
![img_10.png](assets/images/sprint2/img_10.png)

- Reports
![img_8.png](assets/images/sprint2/img_8.png)

- Tasks 
![img_7.png](assets/images/sprint2/img_7.png)

- Weather
![img_9.png](assets/images/sprint2/img_9.png)

#### 5.2.2.6. Services Documentation Evidence for Sprint Review.

Para este segundo sprint, solo nos enfocamos en el desarrollo del frontend de la aplicación, nos apoyamos de una herramienta que nos permitiera simular un backend falso.

Por ese motivo, hemos desplegaod un JSON Server en la plataforma de Azure y asi de esta manera poder simular un backend falso y asi poder consumir los datos desde nuestro frontend.

Link del JSON Server:  [mockapi](agrotrack-mockapi.azurewebsites.net)

| Endpoint          | Descripción                                                           |
|-------------------|-----------------------------------------------------------------------|
| `/users`          | Gestión de usuarios (registro, autenticación, perfil)                 |
| `/organizations`  | Gestión de organizaciones agrícolas                                   |
| `/plots`          | Gestión de parcelas (creación, edición, eliminación)                  |
| `/tasks`          | Gestión de tareas agrícolas (asignación, seguimien to, recordatorios) |
| `/reports`        | Generación y visualización de reportes agrícolas                      |



#### 5.2.2.7.  Deployment Evidence for Sprint Review.
Para la entrega de este segundo sprint, se implementó la web application de manera parcial.

Los pasos para la connexion del netlify con el github.

![img.png](assets/images/sprint2/img.png)
![img_1.png](assets/images/sprint2/img_1.png)
![img_2.png](assets/images/sprint2/img_2.png)
![img_3.png](assets/images/sprint2/img_3.png)
![img_4.png](assets/images/sprint2/img_4.png)
![img_5.png](assets/images/sprint2/img_5.png)

- Register
  ![img_12.png](assets/images/sprint2/img_12.png)

- Organization
  ![img_6.png](assets/images/sprint2/img_6.png)

- Plots
  ![img_10.png](assets/images/sprint2/img_10.png)

- Reports
  ![img_8.png](assets/images/sprint2/img_8.png)

- Tasks
  ![img_7.png](assets/images/sprint2/img_7.png)

- Weather
  ![img_9.png](assets/images/sprint2/img_9.png)

#### 5.2.2.8. Team Collaboration Insights during Sprint

![img_13.png](assets/images/sprint2/img_13.png)
![img_14.png](assets/images/sprint2/img_14.png)

### 5.2.3. Sprint 3

#### 5.2.3.1. Sprint Planning 3

#### 5.2.3.2. Aspect Leaders and Collaborators.

#### 5.2.3.3. Sprint Backlog 3.

#### 5.2.3.4. Development Evidence for Sprint Review.

#### 5.2.3.5. Execution Evidence for Sprint Review.

![img_2.png](img_2.png)

![img_3.png](img_3.png)

![img_4.png](img_4.png)

![img_7.png](img_7.png)

![img_8.png](img_8.png)


#### 5.2.3.6. Services Documentation Evidence for Sprint Review.

#### 5.2.3.7. Deployment Evidence for Sprint Review.

Para la entrega de este tercer sprint, se implementó el backend en swagger y se desplego con Render

Pasos para el despliegue del backend en Rendee:

1. Entrar a la pagina principal 

![img_5.png](img_5.png)

2. Iniciar sesión con github

![img_6.png](img_6.png)

3. Crear un nuevo proyecto

![img.png](img.png)


4. Seleccionar el repositorio correspondiente

![img_1.png](img_1.png)

5. ![img_2.png](img_2.png)

![img_3.png](img_3.png)

![img_4.png](img_4.png)

![img_7.png](img_7.png)

![img_8.png](img_8.png)


#### 5.2.3.8. Team Collaboration Insights during Sprint

![img_9.png](img_9.png)
![img_10.png](img_10.png)


## 5.3. Validation Interviews

### 5.3.1. Diseño de entrevistas

### Objetivo de las entrevista

El objetivo de las entrevistas es validar las hipótesis planteadas en la fase de descubrimiento, obteniendo retroalimentación directa de los usuarios potenciales sobre sus necesidades, desafíos y expectativas en relación con la gestión agrícola digital. Se busca comprender mejor el contexto de uso, identificar posibles mejoras en la propuesta de valor y evaluar la aceptación del producto EcoTrack.

### Landing page

Se diseñó una landing page que presenta de manera clara y atractiva la propuesta de valor de EcoTrack, destacando sus beneficios, características principales y planes de suscripción. La landing page incluye secciones informativas, testimonios de usuarios y un formulario de contacto para captar el interés de los visitantes.

#### Preguntas de validación

* ¿Qué tan claro te resultó entender qué es EcoTrack y qué beneficios ofrece?
* ¿El diseño, colores e imágenes te transmitieron confianza y profesionalismo?
* ¿Encontraste fácilmente la información que buscabas (funciones, beneficios, contacto)?
* ¿Los botones o llamados a la acción te motivaron a registrarte o pedir más información?
* ¿Qué mejorarías para que la página sea más atractiva o clara para nuevos usuarios?


### Aplicación web
Se preparó una demostración funcional de la aplicación web EcoTrack, enfocándose en las características clave que abordan las necesidades identificadas durante la fase de descubrimiento. La demo incluye flujos de trabajo típicos, como la creación de parcelas, el registro de cultivos y la gestión de tareas agrícolas.

#### Preguntas de validación

*Agricultor*

1. Inicio de sesión y acceso
    - ¿El proceso de inicio de sesión te pareció sencillo y rápido?
2. Seeleccion de cultivo
    - ¿Pudiste identificar y seleccionar fácilmente tu cultivo principal?
3. Visializacion de tareas
    - ¿Entendiste claramente las tareas pendientes y su estado actual?
4. Alertas asociadas al cultivo
    - ¿Las alertas mostradas te resultaron útiles y comprensibles para tomar decisiones?

*Agrónomo*


1. Inicio de sesión y acceso
    - ¿El proceso de inicio de sesión te pareció sencillo y rápido?
2. Dashboard de organización
    - ¿Pudiste navegar fácilmente por el dashboard y encontrar la información relevante?
3. Creacion de parcelas
    - ¿El proceso de creación de parcelas fue intuitivo y claro?
4. Visualizacion de tareas
    - ¿Te resultó fácil supervisar o actualizar las tareas de los agricultores?
5. Reportes generados
    - ¿Los reportes presentaron información útil y relevante para la gestión agrícola?
### 5.3.2 Registro de entrevistas

### Segmento: Agrónomos


|              Atributo               | Detalle                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|:-----------------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|               Nombre                | Luis Mendoza                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|                Edad                 | 30 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|              Distrito               | Villa El Salvador                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|              Ocupación              | Ingeniero Agrónomo                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|         Fecha de entrevista         | 10 de noviembre del 2025                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|               Timing                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|        Enlace a la grabación        | [*Ver en Microsoft Stream*]()                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| Captura de pantalla de la grabación | ![Entrevista-1](assets/images/entrevistas-validacion/img.png)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|               Resumen               | El agrónomo Luis Mendoza comentó que la landing page le permitió comprender de manera clara y rápida qué es EcoTrack y cuál es su propósito. No obstante, recalcó en varias oportunidades que la página carece de imágenes reales relacionadas directamente con el trabajo agrícola, lo cual considera un elemento importante para generar mayor confianza y conexión con los usuarios del sector. Sobre el proceso de inicio de sesión, mencionó que le resultó sencillo y accesible, señalando que esto sería especialmente beneficioso para agricultores que no están acostumbrados a utilizar herramientas digitales. Durante su recorrido por la aplicación web, indicó que la navegación fue fluida e intuitiva, y destacó como oportunidad de mejora la incorporación de gráficos y estadísticas que permitan visualizar mejor la información y apoyar la toma de decisiones en el manejo de cultivos y tareas.  |




|              Atributo               | Detalle                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|:-----------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|               Nombre                | Diego Armando Huamán Rojas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|                Edad                 | 27 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|              Distrito               | Ayacucho                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|              Ocupación              | Ingeniero Agrónomo                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|         Fecha de entrevista         | 10 de noviembre del 2025                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|               Timing                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|        Enlace a la grabación        | [*Ver en Microsoft Stream*]()                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Captura de pantalla de la grabación | ![Entrevista-2]()                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|               Resumen               | El agrónomo Diego Huamán señaló que la landing page le permitió entender claramente qué es EcoTrack y cuáles son sus beneficios principales. Mencionó que la explicación inicial fue suficiente para captar la propuesta de valor, aunque consideró que se podría reforzar con ejemplos reales de uso en el campo. También destacó que el diseño le transmitió profesionalismo y una buena primera impresión, pero sugirió incluir imágenes auténticas de cooperativas o parcelas para lograr una conexión más directa con usuarios agrícolas. Sobre los llamados a la acción, indicó que eran visibles y fáciles de identificar, aunque comentó que preferiría un botón pensado específicamente para solicitar una demostración. En cuanto a la aplicación web, Diego indicó que el proceso de inicio de sesión fue directo y sin dificultades, aunque sugirió integrar opciones como Google o correos institucionales para facilitar el acceso. El dashboard le pareció útil para obtener una vista general del estado de parcelas y tareas, pero consideró importante incorporar alertas críticas más visibles. Al crear parcelas, destacó que el flujo fue intuitivo y que los campos solicitados eran claros, aunque le gustaría contar con herramientas geográficas como mapas o la opción de cargar límites. Sobre la visualización de tareas, resaltó que la organización era adecuada, pero que filtros más rápidos por fecha o responsable mejorarían la experiencia. Finalmente, comentó que los reportes eran bastante completos. |



|              Atributo               | Detalle                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|:-----------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|               Nombre                | Renzo Sebastián Paredes Castillo                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|                Edad                 | 29 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|              Distrito               | Cusco                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|              Ocupación              | Ingeniero Agrónomo                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|         Fecha de entrevista         | 10 de noviembre del 2025                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|               Timing                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|        Enlace a la grabación        | [*Ver en Microsoft Stream*]()                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| Captura de pantalla de la grabación | ![Entrevista-3]()                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|               Resumen               | El agrónomo Renzo Paredes indicó que la landing page comunicaba de manera clara el valor de EcoTrack desde el primer vistazo, especialmente las partes relacionadas con trazabilidad y reportes, las cuales considera muy importantes en su labor. El diseño le pareció limpio, profesional y fácil de recorrer, aunque sugirió incorporar más ejemplos visuales reales del uso de la plataforma en contextos agrícolas para fortalecer la comprensión. También comentó que encontró rápidamente la información relevante y que quizá sería útil agregar un detalle más explícito sobre precios o planes. Dentro de la aplicación web, Renzo mencionó que el inicio de sesión funcionó bien y sin dificultades, aunque una opción de "recordar sesión" sería muy conveniente. Sobre el dashboard, destacó que ofrece una buena vista general, pero le gustaría ver más elementos visuales como gráficos rápidos o indicadores clave para facilitar la lectura del estado de la organización. En la creación de parcelas, el flujo le pareció rápido y práctico, aunque consideró necesaria una ayuda visual como un mapa para ubicar las parcelas de forma más precisa. En la visualización de tareas encontró útil la organización y el seguimiento de actividades, sugiriendo la incorporación de un calendario para optimizar la planificación. Con respecto a los reportes, opinó que están bien estructurados, pero que sería valioso poder personalizar métricas según cultivo o temporada. Concluyó que sí usaría EcoTrack, ya que podría reducir su carga administrativa y mejorar la supervisión del personal.  |



### Segmento: Agricultores


|              Atributo               | Detalle                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|:-----------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|               Nombre                | Luis Alberto Campos Salvatierra                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|                Edad                 | 25 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|              Distrito               | Chiclayo                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|              Ocupación              | Agricultor                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|         Fecha de entrevista         | 10 de noviembre del 2025                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|               Timing                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|        Enlace a la grabación        | [*Ver en Microsoft Stream*]()                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| Captura de pantalla de la grabación | ![Entrevista-4](assets/images/entrevistas-validacion/img2.png)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|               Resumen               | El agricultor Luis Campos mencionó que comprendió sin dificultad qué hace EcoTrack al revisar la landing page, ya que explica de manera sencilla cómo ayuda a organizar cultivos y tareas diarias. Indicó que la página le pareció confiable y ordenada, aunque preferiría ver ejemplos más concretos de cómo usar la plataforma en situaciones reales del campo. También señaló que estaría dispuesto a registrarse, pero comentó que inicialmente necesitaría apoyo porque no está acostumbrado a usar plataformas digitales. En la aplicación web, Luis señaló que el inicio de sesión fue sencillo, pero que él preferiría ingresar con su número de celular, ya que es su método más habitual. Sobre la selección de cultivos, indicó que pudo encontrar el suyo con facilidad, aunque fotos o iconos ayudarían a diferenciar cultivos con nombres similares. La visualización de tareas le resultó clara y útil, destacando especialmente que se indique qué actividades corresponden al día, aunque sugirió mejorar la identificación de tareas urgentes con colores. En cuanto a las alertas del cultivo, mencionó que fue la parte que más valor le generó, ya que lo ayudaría a evitar problemas, y agregó que sería ideal recibirlas también por WhatsApp. Concluyó que sí usaría EcoTrack si le facilita organizar su trabajo y si su agrónomo también adopta la plataforma. |


### 5.3.3. Evaluaciones según heuristicas

**CARRERA:** Ingeniería de Software  
**CURSO:** Aplicaciones Web  
**CLIENTE:** Usuarios agrícolas (Agricultores y Agrónomos)  
**AUDITOR:** Equipo del proyecto EcoTrack

---

### APP A EVALUAR
**EcoTrack – Plataforma Web para Gestión Agrícola**

---

### TAREAS EVALUADAS
Las tareas incluidas en la evaluación fueron:

1. Registro e inicio de sesión
2. Visualización del dashboard
3. Selección de cultivos
4. Creación de parcelas
5. Visualización y gestión de tareas
6. Revisión de alertas del cultivo
7. Generación y consulta de reportes
8. Uso de la landing page para conocer el producto

### TABLA DE ESCALA DE SEVERIDAD

| Nivel | Descripción                                                                                                                                         |
|-------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **1** | Problema superficial: puede ser superado fácilmente o ocurre con poca frecuencia. No necesita ser arreglado salvo que haya tiempo disponible.       |
| **2** | Problema menor: ocurre más frecuentemente o es algo más difícil para el usuario. Recomendado arreglarlo en un siguiente release con baja prioridad. |
| **3** | Problema mayor: ocurre frecuentemente o el usuario no puede resolverlo. Se debe corregir con prioridad alta.                                        |
| **4** | Problema muy grave: impide al usuario continuar. Debe corregirse antes del lanzamiento.                                                             |


---

### TABLA RESUMEN DE PROBLEMAS

| #  | Problema identificado                                          | Severidad | Heurística / Principio violado                   |
|----|----------------------------------------------------------------|-----------|--------------------------------------------------|
| 1  | Falta opción de inicio de sesión alternativo (Google, celular) | 2         | Usability – Flexibilidad y eficiencia            |
| 2  | Landing page sin imágenes reales del campo                     | 2         | Inclusive Design – Experiencias comparables      |
| 3  | Selección de cultivos sin apoyo visual (iconos/fotos)          | 3         | Usability – Reconocimiento mejor que recuerdo    |
| 4  | Alertas poco visibles; falta diferenciación por criticidad     | 3         | Usability – Visibilidad del estado del sistema   |
| 5  | Tareas urgentes no tienen color o jerarquía destacada          | 3         | Usability – Señalización y prioridades           |
| 6  | Dashboard con pocos gráficos o indicadores visuales            | 2         | Information Architecture – Is it understandable? |
| 7  | Crear parcelas sin mapa o soporte geográfico visual            | 3         | Usability – Correspondencia con el mundo real    |
| 8  | Falta opción “Recordar sesión”                                 | 1         | Usability – Minimizar carga del usuario          |
| 9  | Falta calendario para ver tareas                               | 2         | Usability – Control del usuario                  |
| 10 | Alertas importantes no enviadas por WhatsApp                   | 2         | Inclusive Design – Ajuste al contexto real       |

---
### DESCRIPCIÓN DETALLADA DE PROBLEMAS
---
## **Problema #1 – Falta opción de inicio de sesión alternativo**
**Severidad:** 2  
**Heurística violada:** Usability – Flexibilidad y eficiencia del uso

**Problema:**  
Los usuarios prefieren iniciar sesión con Google, correo institucional o número de celular, lo cual no está disponible y genera fricción.

**Recomendación:**  
Agregar login con Google, instituciones y celular.

---

## **Problema #2 – Falta de imágenes reales en la landing page**
**Severidad:** 2  
**Heurística violada:** Inclusive Design – Experiencias comparables

**Problema:**  
Las imágenes no representan el contexto real agrícola, lo que reduce conexión emocional.

**Recomendación:**  
Incluir fotografías reales del campo, cooperativas o agrónomos.

---

## **Problema #3 – Selección de cultivos sin apoyo visual**
**Severidad:** 3  
**Heurística violada:** Usability – Reconocimiento mejor que recuerdo

**Problema:**  
Los cultivos con nombres similares generan confusión sin iconos o fotos de referencia.

**Recomendación:**  
Añadir iconografía o imágenes pequeñas para cada cultivo.

---

## **Problema #4 – Alertas poco visibles**
**Severidad:** 3  
**Heurística violada:** Usability – Visibilidad del estado del sistema

**Problema:**  
Las alertas no destacan ni indican su severidad.

**Recomendación:**  
Usar colores por nivel, banners y señales visuales fuertes para alertas críticas.

---

## **Problema #5 – Tareas urgentes sin jerarquía visual**
**Severidad:** 3  
**Heurística violada:** Usability – Señalización y prioridades

**Problema:**  
Las tareas urgentes se ven idénticas a las normales.

**Recomendación:**  
Colores, etiquetas o iconos para urgencia.

---

## **Problema #6 – Dashboard con poca visualización gráfica**
**Severidad:** 2  
**Heurística violada:** Information Architecture – Is it understandable?

**Problema:**  
La vista inicial carece de indicadores gráficos que permitan interpretar rápidamente el estado de la organización.

**Recomendación:**  
Añadir KPIs, gráficos de barras, indicadores de cultivo y alertas activas.

---

## **Problema #7 – Crear parcelas sin soporte geográfico**
**Severidad:** 3  
**Heurística violada:** Usability – Correspondencia con el mundo real

**Problema:**  
Los usuarios necesitan ubicar parcelas en un mapa, no solo datos textuales.

**Recomendación:**  
Integrar mapas interactivos para delimitar la parcela.

---

## **Problema #8 – Falta opción “Recordar sesión”**
**Severidad:** 1  
**Heurística violada:** Usability – Minimizar carga del usuario

**Problema:**  
El usuario debe loguearse siempre, poco ideal en campo.

**Recomendación:**  
Implementar “Mantener sesión iniciada”.


---

## **Problema #9 – Falta calendario para visualizar tareas**
**Severidad:** 2  
**Heurística violada:** Usability – Control y eficiencia del usuario

**Problema:**  
No existe vista de calendario para planificar semanal o mensualmente.

**Recomendación:**  
Añadir calendario con vista semanal, mensual y por responsable.

---

## **Problema #10 – Alertas no enviadas por WhatsApp**
**Severidad:** 2  
**Heurística violada:** Inclusive Design – Adaptación al contexto

**Problema:**  
Los usuarios agrícolas dependen más de WhatsApp que del correo.

**Recomendación:**  
Integrar notificaciones vía WhatsApp API.

---

## 5.4. Video About the Product 


# Conclusiones

### TB1: 

**Validación del Problema y la Solución**

* Se confirmó la necesidad real en el sector agrícola peruano de herramientas digitales accesibles para la gestión de parcelas y cultivos
* EcoTrack se posicionó exitosamente como una solución que equilibra simplicidad tecnológica con conocimiento agrícola especializado
* Las entrevistas con 6 usuarios validaron las dificultades en la gestión manual y la apertura hacia soluciones digitales intuitivas

**Comprensión Profunda del Usuario**

* Los User Personas desarrollados reflejan con precisión las características demográficas, tecnológicas y de comportamiento identificadas
* Se confirmó que tanto agricultores como agrónomos valoran especialmente funcionalidades como alertas climáticas, recordatorios de tareas y reportes simplificados
* La investigación reveló la importancia de balancear funcionalidades avanzadas con simplicidad de uso

**Arquitectura de Información Efectiva**
* Se estableció una organización clara del contenido basada en sistemas jerárquicos, matriciales y por audiencia
* El sistema de etiquetado emplea vocabulario cercano al sector agrícola, reduciendo barreras de entrada
* Se implementaron estrategias SEO apropiadas para maximizar la visibilidad en buscadores especializados

**Diseño Visual Coherente**
* Se desarrolló una identidad visual que transmite confianza, naturaleza e innovación
* Los lineamientos de estilo aseguran consistencia visual entre la landing page y futuras funcionalidades
* Se priorizó la accesibilidad considerando las limitaciones tecnológicas del público objetivo

**Fundamentos Técnicos Establecidos**

* La arquitectura basada en Domain-Driven Design facilita el desarrollo escalable
* Se establecieron procesos claros de desarrollo y documentación para futuras entregas

Esta primera entrega ha sentado las bases necesarias para desarrollar una solución que responda efectivamente a las necesidades del sector agrícola peruano, con un enfoque centrado en el usuario y una arquitectura sólida para el crecimiento futuro.

### TP1: 

* Durante este periodo de desarrollo se alcanzaron avances significativos en la implementación de las principales funcionalidades del sistema. Se completó la mayor parte de las tareas planificadas, logrando consolidar componentes esenciales relacionados con la gestión de organizaciones, parcelas, cultivos, tareas y reportes.

* El equipo demostró una eficiente coordinación y cumplimiento de plazos, logrando finalizar casi la totalidad de las actividades dentro del tiempo estimado. Las tareas pendientes se encuentran en un estado avanzado, principalmente enfocadas en el perfeccionamiento de módulos complementarios y de personalización del sistema.

* En términos de desempeño, se evidenció una adecuada distribución del trabajo y una correcta estimación de esfuerzo, con la mayoría de tareas completadas dentro del rango planificado de horas. Las implementaciones desarrolladas muestran un buen nivel de calidad técnica y coherencia visual, reflejando una integración fluida entre diseño y lógica funcional.

* El avance obtenido permite contar con una base sólida del sistema, sobre la cual será posible realizar pruebas de integración y validación de flujos en el siguiente sprint. Asimismo, se establecen los cimientos para incorporar futuras mejoras orientadas a la usabilidad, gestión de datos y análisis de información.

# Bibliografía

Ministerio de Desarrollo Agrario y Riego [MIDAGRI]. (2023, julio 24). *El 75,6% de los productores son propietarios de al menos una parcela*. gob.pe. https://www.gob.pe/institucion/midagri/noticias/808115-midagri-el-75-6-de-los-productores-son-propietarios-de-al-menos-una-parcela

Puntel, L. A., Bolfe, É. L., Melchiori, R., Ortega, R., & otros. (2022). *How digital is agriculture in a subset of countries from South America? Adoption and limitations*. Crop and Pasture Science, 74(6), 555–572. https://doi.org/10.1071/CP21759

# Anexos

- Entrevistas: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g044_upc_edu_pe/EWIynez_N45IjdJ6JFNpOusBxo9mDCzON9DF0V6rEsRh9A?e=FnurJA&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6MjQ0OC4xfX0%3D
- Video de exposición TB1: [https://upcedupe-my.sharepoint.com/:f:/g/personal/u20221g044_upc_edu_pe/EnBMCQetX49InsIa-k2zH80B88s8QMV8U2lRuWD617qjPg?e=TOVs2m](https://upcedupe-my.sharepoint.com/:f:/g/personal/u20221g044_upc_edu_pe/EnBMCQetX49InsIa-k2zH80B88s8QMV8U2lRuWD617qjPg?e=TOVs2m)
- video de exposición TB2: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g044_upc_edu_pe/EfnWaw09L35ImJ-QMK4iKo0B6eQVa0-L24CLH8VgL6-YdA?e=Ren8dD](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g044_upc_edu_pe/EfnWaw09L35ImJ-QMK4iKo0B6eQVa0-L24CLH8VgL6-YdA?e=Ren8dD)
- Landing page: [https://agromind-aplicaciones-web-7414.github.io/ecotrack-landingpage/](https://agromind-aplicaciones-web-7414.github.io/ecotrack-landingpage/)
- Web app desplegada: [https://ecotrack-web-app.netlify.app/](https://ecotrack-web-app.netlify.app/) 