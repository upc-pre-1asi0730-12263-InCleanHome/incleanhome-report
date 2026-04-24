# InCleanHome Report



<p align="center">
    <img src="./assets/logo-upc.png" alt="upc-logo" width="80px" height="80px"/>
</p>

<h1 align="center">
    Universidad Peruana de Ciencias Aplicadas
</h1>

<h3 align="center">
    Carrera: Ingeniería de Software
    <br> <br>
    Curso: 1ASI0730 - Aplicaciones Web
    <br> <br>
    Sección: 12263 
    <br> <br>
    Profesor: Castro Veramendi, Rafael Oswaldo
    <br> <br>
    Ciclo: 2026-01 
    <br> <br>
    Informe de Trabajo Final
    <br> <br>
    Startup: HomeMatch
    <br> <br>
    Producto: InCleanHome
</h3>

<div align="center">

| <div style="width:300px">Alumno</div>       | <div style="width:125px">Código</div> |
|:-------------------------------------------:|:-------------------------------------:|
|  Choy Robles, Vanessa May Lang              |              u202317450               |
|  Espino Rossi, Victor Manuel                |              u202411567               |
|  Garcia Cerpa, Braden Raid                  |              u202415618               |
|  Valverde Portuguez, Natalia Ximena         |              u20231a816               |
|  Vara Velásquez, Oscar Fernando             |              u202411622               |

</div>

<div align="center"> Abril 2026 </div>


## Registro de Versiones del Informe



## Project Report Collaboration Insights  


# Tabla de Contenidos

- Capítulo I: Introducción
  - [1.1 Startup Profile](#11-startup-profile)
    - [1.1.1 Descripción de la Startup](#111-descripcion-de-la-startup)
    - [1.1.2 Perfiles de Integrantes del Equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2 Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y Problemática](#121-antecedentes-y-problematica)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1 Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2 Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3 Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4 Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3 Segmentos Objetivos](#13-segmentos-objetivos)

- Capítulo II: Requirements Elicitation & Analysis
  - [2.1 Competidores](#21-competidores)
    - [2.1.1 Análisis competitivo](#211-analisis-competitivo)
    - [2.1.2 Estrategias y tácticas frente a competidores](#212-estrategias-y-tacticas-frente-a-competidores)
  - [2.2 Entrevistas](#22-entrevistas)
    - [2.2.1 Diseño de entrevistas](#221-diseno-de-entrevistas)
    - [2.2.2 Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3 Análisis de entrevistas](#223-analisis-de-entrevistas)
  - [2.3 Needfinding](#23-needfinding)
    - [2.3.1 User Personas](#231-user-personas)
    - [2.3.2 User Task Matrix](#232-user-task-matrix)
    - [2.3.3 User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4 Empathy Mapping](#234-empathy-mapping)
  - [2.4 Big Picture EventStorming](#24-big-picture-eventstorming)
  - [2.5 Ubiquitous Language](#25-ubiquitous-language)

- Capítulo III: Requirements Specification
  - [3.1 User Stories](#32-user-stories)
  - [3.2 Impact Mapping](#33-impact-mapping)
  - [3.3 Product Backlog](#34-product-backlog)

- Capítulo IV: Product Design
  - [4.1 Style Guidelines](#41-style-guidelines)
    - [4.1.1 General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2 Web Style Guidelines](#412-web-style-guidelines)
  - [4.2 Information Architecture](#42-information-architecture)
    - [4.2.1 Organization Systems](#421-organization-systems)
    - [4.2.2 Labeling Systems](#422-labeling-systems)
    - [4.2.3 SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4 Searching Systems](#424-searching-systems)
    - [4.2.5 Navigation Systems](#425-navigation-systems)
  - [4.3 Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1 Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2 Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4 Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1 Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2 Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3 Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4 Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5 Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6 Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1 Software Architecture Context Diagrams](#461-software-architecture-context-diagrams)
    - [4.6.2 Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3 Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
  - [4.7 Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1 Class Diagrams](#471-class-diagrams)
    - [4.7.2 Class Dictionary](#472-class-dictionary)
  - [4.8 Database Design](#48-database-design)
    - [4.8.1 Database Diagram](#481-database-diagram)

- Capítulo V: Product Implementation, Validation & Deployment
  - [5.1 Software Configuration Management](#51-software-configuration-management)
    - [5.1.1 Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2 Source Code Management](#512-source-code-management)
    - [5.1.3 Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4 Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2 Landing Page, Services & Applications Implementation](#52-landing-page-services-applications-implementation)
    - [5.2.1 Sprint 1](#521-sprint-1)
      - [5.2.1.1 Sprint Planning 1](#5211-sprint-planning-1)
      - [5.2.1.2 Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3 Sprint Backlog 1](#5213-sprint-backlog-1)
      - [5.2.1.4 Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5 Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6 Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7 Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8 Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
      
  - [6. Conclusiones](#conclusiones)
  - [7. Bibliografía](#bibliografia)
  - [8. Anexos](#anexos)




**ABET – EAC - Student Outcome 5**

La capacidad de funcionar efectivamente en un
equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de
colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos. 
En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo,
que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 5.


| Criterio específico | Acciones Realizadas | Conclusiones |
|---------------------|-----------------------------|--------------|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta | **Choy Robles, Vanessa May Lang**<br>**TB1**<br> Lideró la transición del análisis de entrevistas hacia la especificación técnica de requerimientos, asegurando que el Product Backlog y las User Stories reflejaran fielmente las necesidades detectadas en el Needfinding . <br><br>**Espino Rossi, Victor Manuel**<br>**TB1**<br> Se colaboró con el equipo <br><br>**Garcia Cerpa, Braden Raid**<br>**TB1**<br> realizar web application en grupo <br><br>**Valverde Portuguez, Natalia Ximena**<br>**TB1**<br> Dirigió la fase inicial de alineación estratégica, definiendo la misión, visión y el Lean UX Canvas, proporcionando el marco conceptual necesario para que el resto del equipo desarrollara las especificaciones técnicas. <br><br>**Vara Velásquez, Oscar Fernando**<br>**TB1**<br> Se trabajó de manera proactiva <br><br> |El equipo demostró un liderazgo distribuido y efectivo al asignar responsables para cada fase del proyecto, desde la investigación estratégica inicial hasta la arquitectura de software y el diseño de base de datos. Esta estructura permitió que las decisiones técnicas estuvieran siempre alineadas con la misión de formalizar el sector doméstico, garantizando una transición coherente entre el análisis de necesidades y la implementación de soluciones de seguridad y confianza.
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos | **Choy Robles, Vanessa May Lang**<br>**TB1**<br> Estableció hitos críticos para la entrega de los Capítulos II y III, coordinando con los integrantes la validación del Big Picture EventStorming y el Impact Mapping para garantizar un diseño de solución coherente . <br><br>**Espino Rossi, Victor Manuel**<br>**TB1**<br> Se aportó ideas <br><br>**Garcia Cerpa, Braden Raid**<br>**TB1**<br> participacion activa en reuniones virtuales <br><br>**Valverde Portuguez, Natalia Ximena:**<br>**TB1**<br> Planificó las tareas de investigación de antecedentes y segmentación de objetivos (Capítulo I), facilitando un entorno inclusivo al integrar los perfiles de todos los miembros y definir el problema central de manera compartida. <br><br>**Vara Velásquez, Oscar Fernando**<br>**TB1**<br> Se cumplió con los plazos de entrega <br><br> |Se consolidó un entorno de colaboración de alto rendimiento mediante la planificación y ejecución del primer Sprint, integrando disciplinas de UX/UI, arquitectura DDD y desarrollo de software. El cumplimiento de los objetivos se evidencia en la entrega de un producto que no solo es técnicamente viable, sino que responde a las métricas de confianza y eficiencia demandadas por los usuarios, logrando transformar los hallazgos del Needfinding en una aplicación funcional con estándares profesionales de despliegue.



## Capítulo I: Introducción

### 1.1. Startup Profile-

#### 1.1.1. Descripción de la Startup
HomeMatch ofrece una solución innovadora con el aplicativo "InCleanHome" en la búsqueda de la trabajadora del hogar ideal para el hogar de los clientes según las necesidades específicas que requiere el cliente del personal a contratar. Mediante una interfaz intuitiva y con buena usabilidad, los clientes pueden buscar y elegir su empleado ideal a través de filtros que facilitan su búsqueda como por ejemplo, distritos donde laboran, tipo de casa que limpian, si realizan servicio de cocina, limpieza, jardín, edad, género,etc. Además, en la aplicación puedes revisar comentarios o reviews de otros clientes que han hecho uso del servicio de una persona en específico.
InCleanHome sería una aplicación gratuita y tendría una ganancia al cobrar un 10% de cada servicio realizado.
El objetivo de este proyecto es facilitar la búsqueda de un empleado del hogar a la familia con todos los requisitos que solicite y según la tarifa que este puede ofrecer, y que a su vez sea una persona segura y de confianza.


**Misión:** Brindar una plataforma digital confiable y accesible que conecte a clientes con trabajadoras del hogar verificadas, facilitando la contratación de servicios domésticos de manera segura, rápida y eficiente.

**Visión:** Ser la plataforma líder en servicios domésticos en Perú, reconocida por mejorar la calidad de vida de los usuarios y promover la formalización laboral de las trabajadoras del hogar mediante el uso de tecnología.


#### 1.1.2. Perfiles de Integrantes del Equipo

<p align="center">
    <img src="assets/integrantes/Choy.jpeg" alt="Choy" width="170px"/>
    
- Choy Robles, Vanessa May Lang - u202317450 (Ingeniería de Software)
<p>Soy estudiante de Ingeniería de Software con experiencia en distintos lenguajes de programación, diseño UX/UI y trabajo bajo metodologías ágiles como Scrum. Aporto al equipo una visión orientada tanto a la funcionalidad como a la experiencia del usuario, contribuyendo en el desarrollo y mejora continua del producto. Me caracterizo por mi responsabilidad, cumplimiento de plazos y participación activa en el trabajo colaborativo. 
</p>


<p align="center">
    <img src="assets/integrantes/Espino.jpg" alt="Espino" width="170px"/>
</p>
- Espino Rossi, Victor Manuel - u202411567 (Ingenieria de Software)
- Soy un estudiante de Ingenieria de Software, tengo 19 años. Cuento con sólidas habilidades para el trabajo en equipo y una gran capacidad para aprender rápido y adaptarse a nuevos retos. Comprometido con entregar resultados de calidad y siempre dispuesto a colaborar para que el equipo alcance sus objetivos.

  <p align="center">
    <img src="assets/integrantes/Garcia.jpg" alt="Garcia" width="170px"/>
</p>
- Garcia Cerpa, Braden Raid - u202415618 (Ingeniería de Software)
-Soy estudiante de Ingeniería de Software con interés en el desarrollo de soluciones tecnológicas. Me enfoco en aplicar buenas prácticas de programación y trabajo en equipo para resolver problemas reales. En este proyecto, busco aportar ideas innovadoras para lograr resultados de alta calidad.

<p align="center">
    <img src="assets/integrantes/Valverde.png" alt="Valverde" width="170px"/>
</p>

- Valverde Portuguez, Natalia Ximena - u20231a816 (Ingeniería de Software)
<p>
Estudiante de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Cuento con conocimientos de Marketing y estoy interesada en el UX Design y data analysis. Experiencia en trabajos de creación de startups en el ámbito laboral, lo que fortalece mis capacidades tanto en trabajos grupales e individuales como para las bases de un proyecto.
</p>

<p align="center">
    <img src="assets/integrantes/Vara.jpeg" alt="Vara" width="170px"/>
</p>
- Vara Velásquez, Oscar Fernando - u202411622 (Ingeniería de Software)-Enfocado en crear soluciones tecnológicas de acuerdo a las necesidades de los usuarios. Cuento una rápida adquisición de conocimientos y trabajo en equipo.



### 1.2. Solution Profile

#### 1.2.1. Antecedentes y problemática

En el Perú, el trabajo doméstico remunerado continúa siendo un sector altamente informal y vulnerable, especialmente en Lima Metropolitana. Según datos recientes de la Encuesta Nacional de Hogares (ENAHO) y reportes del 2026, más de 441,000 personas se dedican a labores domésticas, de las cuales aproximadamente el 95% son mujeres; sin embargo, pese a la existencia de la Ley N.º 31047 que regula sus derechos laborales, alrededor del 95% de estas trabajadoras aún se encuentra en situación de informalidad y solo un pequeño porcentaje cuenta con contrato formal, acceso a beneficios sociales o seguridad laboral . Esta realidad evidencia una problemática estructural caracterizada por la precariedad laboral, la falta de regulación efectiva y la ausencia de soluciones digitales que faciliten un proceso de contratación seguro, eficiente y transparente.

**What**  
El problema central es la dificultad para encontrar y contratar personal doméstico confiable, calificado y disponible, debido a la falta de plataformas digitales seguras que permitan validar información, comparar opciones y garantizar un proceso de contratación transparente.

**When**  
El problema se manifiesta en el momento en que los usuarios necesitan contratar servicios domésticos o cuando las trabajadoras del hogar buscan empleo, especialmente en contextos de urgencia o necesidad inmediata.

**Where**  
Esta problemática se presenta principalmente en Lima Metropolitana, donde existe una alta demanda de servicios domésticos y una gran concentración de trabajadoras del hogar, aunque también puede replicarse en otras ciudades del país.

**Who**  
La problemática involucra principalmente a dos grupos: por un lado, personas que requieren servicios domésticos, como familias, profesionales con poco tiempo y adultos mayores; y por otro lado, trabajadoras del hogar que buscan oportunidades laborales estables y seguras, muchas de las cuales se encuentran en condiciones de informalidad.

**Why**  
Esta situación ocurre debido a la falta de digitalización del sector, la informalidad predominante, la ausencia de mecanismos de verificación de identidad y experiencia, y la limitada implementación de normativas laborales que protejan a las trabajadoras.

**How**  
Actualmente, el proceso de contratación se realiza mediante recomendaciones, redes sociales o contactos personales, lo que implica entrevistas manuales y decisiones basadas en información incompleta, generando riesgos, pérdida de tiempo y baja confianza.

**How much**  
La problemática tiene un alto impacto, ya que implica pérdida de tiempo en la búsqueda, inseguridad en la contratación, baja calidad del servicio en algunos casos y una alta tasa de informalidad laboral que afecta tanto a empleadores como a trabajadoras del hogar.

#### 1.2.2. Lean UX Process

##### 1.2.2.1. Lean UX Problem Statements

Actualmente, en Lima Metropolitana, muchas personas que necesitan servicios domésticos enfrentan dificultades para encontrar personal confiable, disponible y verificado. La mayoría de procesos se realiza de manera informal mediante recomendaciones, redes sociales o contactos personales, lo que genera incertidumbre, pérdida de tiempo y riesgos en la contratación.
Asimismo, las trabajadoras del hogar enfrentan limitadas oportunidades laborales formales, ya que no cuentan con una plataforma centralizada que les permita mostrar sus habilidades, experiencia y disponibilidad de manera confiable.
Hemos observado que no existe una herramienta digital especializada que conecte de forma segura a clientes con trabajadoras del hogar, permitiendo filtrar perfiles, validar información, revisar reseñas y realizar contrataciones con garantía.

**¿Cómo podríamos facilitar que los usuarios encuentren y contraten personal doméstico confiable, verificado y disponible de manera rápida y segura, al mismo tiempo que se generan más oportunidades laborales para las trabajadoras del hogar?**

**¿QUIÉN ES EL USUARIO?**
Nuestros usuarios son personas que necesitan servicios domésticos, como familias, profesionales con poco tiempo o adultos mayores. También incluye a trabajadoras del hogar que buscan oportunidades laborales seguras y estables.

**¿DÓNDE ENCAJA NUESTRO PRODUCTO EN SU VIDA?**
El producto se integra en la vida diaria de los usuarios como una herramienta digital que facilita la contratación de servicios domésticos de forma rápida. Puede ser utilizado en momentos de necesidad inmediata o como parte de la organización semanal del hogar.

**¿QUÉ PROBLEMAS TIENE NUESTRO PRODUCTO Y CÓMO SE PUEDE RESOLVER?**
Los usuarios enfrentan procesos informales, falta de confianza y dificultad para encontrar personal adecuado. Las trabajadoras, por su parte, tienen acceso limitado a oportunidades formales.

Para resolverlo, la plataforma permitirá a los usuarios buscar perfiles verificados, aplicar filtros, revisar reseñas y contratar servicios de forma segura. Las trabajadoras podrán crear perfiles, gestionar su disponibilidad y acceder a más clientes.

**¿CUÁNDO Y CÓMO ES USADO NUESTRO PRODUCTO?**
La plataforma es utilizada cuando los usuarios necesitan contratar servicios domésticos, ya sea de forma urgente o planificada. También puede ser usada de manera recurrente para agendar servicios periódicos y gestionar tareas del hogar.

**¿QUÉ CARACTERÍSTICAS SON IMPORTANTES?**
- Filtros de búsqueda personalizados
- Perfiles verificados
- Sistema de reseñas
- Pagos digitales seguros
- Mensajería interna
- Gestión de disponibilidad

**¿CÓMO DEBE VERSE Y COMPORTARSE EL PRODUCTO?**
El producto debe ser intuitivo, seguro y fácil de usar. Visualmente debe transmitir confianza y profesionalismo. Su comportamiento debe ser rápido, confiable y enfocado en brindar una experiencia fluida tanto para clientes como trabajadoras.

##### 1.2.2.2. Lean UX Assumptions

**Business Assumptions**
- Creemos que la dificultad para encontrar personal doméstico confiable es un problema frecuente en Lima Metropolitana.
- Creemos que los usuarios estarán dispuestos a pagar por servicios domésticos a través de una plataforma digital segura.
- Creemos que existe una demanda creciente de servicios domésticos debido al estilo de vida ocupado de los usuarios.
- Creemos que una solución tecnológica permitirá formalizar y mejorar las condiciones laborales de las trabajadoras del hogar.

**Business Outcomes**
- Creemos que al implementar una plataforma digital para la contratación de servicios domésticos, podremos aumentar la cantidad de servicios contratados en un 30%.
- Creemos que al incluir perfiles verificados y reseñas, incrementaremos la confianza de los usuarios en un 40%.
- Creemos que al ofrecer pagos digitales seguros, aumentaremos la tasa de transacciones completadas en un 25%.
- Creemos que al facilitar la conexión directa entre clientes y trabajadoras, reduciremos el tiempo de contratación en un 35%.

**User Assumptions**
- Creemos que los usuarios necesitan una forma rápida y confiable de encontrar personal doméstico.
- Creemos que los clientes valoran la seguridad y la verificación de perfiles antes de contratar.
- Creemos que las trabajadoras del hogar buscan mayor estabilidad laboral y acceso a más oportunidades.
- Creemos que los usuarios prefieren soluciones digitales simples y fáciles de usar.
- Creemos que la posibilidad de ver reseñas influye en la decisión de contratación.

**User Outcomes**
- Creemos que al ofrecer filtros de búsqueda personalizados, los usuarios podrán encontrar servicios más rápido y de forma eficiente.
- Creemos que al implementar perfiles verificados, los clientes se sentirán más seguros al contratar.
- Creemos que al incluir un sistema de reseñas, los usuarios podrán tomar decisiones más informadas.
- Creemos que al ofrecer pagos digitales, los usuarios podrán realizar transacciones de manera rápida y segura.
- Creemos que al permitir la gestión de disponibilidad, las trabajadoras podrán organizar mejor su tiempo y aumentar sus oportunidades laborales.

**Feature Assumptions**
- Creemos que un sistema de búsqueda con filtros (ubicación, habilidades, disponibilidad) mejorará la experiencia del usuario.
- Creemos que los perfiles verificados con documentos aumentarán la confianza en la plataforma.
- Creemos que la mensajería interna facilitará la coordinación entre cliente y trabajadora.
- Creemos que el sistema de pagos digitales reducirá el riesgo y facilitará la contratación.
- Creemos que el sistema de verificación de trabajadoras garantizará mayor seguridad y calidad del servicio.

##### 1.2.2.3. Lean UX Hypothesis Statements

1. **Creemos que** implementando perfiles verificados con reseñas y calificaciones, los usuarios podrán confiar más en el proceso de contratación y tomar decisiones informadas.

**Sabremos que** tendremos éxito cuando:
Se incremente en un 20% la tasa de contratación y aumente en un 25% la interacción con los perfiles dentro de la plataforma en los primeros 3 meses.

2. **Creemos que** al incluir filtros personalizados (ubicación, habilidades y disponibilidad), los usuarios podrán encontrar más rápido el servicio que necesitan.

**Sabremos que** tendremos éxito cuando:
Se reduzca en un 30% el tiempo promedio de búsqueda y aumente en un 20% la cantidad de servicios contratados.

3. **Creemos que** al implementar un sistema de pagos digitales seguros, los usuarios se sentirán más confiados al realizar transacciones dentro de la aplicación.

**Sabremos que** tendremos éxito cuando:
Se incremente en un 25% el número de pagos realizados dentro de la plataforma y disminuyan en un 15% las cancelaciones de servicios.

##### 1.2.2.4. Lean UX Canvas

<p align="center">
  <img src="./assets/leanuxcanvas/leanuxcanvas.png" alt="Lean UX Canva" width="550">
</p>

### 1.3. Segmentos Objetivos

### Segmento Objetivo 1: 
**Clientes (Usuarios que demandan servicios domésticos)**
Este segmento está conformado por personas que requieren apoyo en tareas del hogar, incluyendo profesionales, familias con niños y adultos mayores que necesitan asistencia frecuente.

**Características demográficas:**
- Edad: entre 25 y 65 años
- Ubicación: Lima Metropolitana
- Nivel socioeconómico: medio y medio-alto
- Ocupación: profesionales, trabajadores dependientes, independientes, familias y adultos mayores
- Nivel educativo: técnico o universitario

**Características conductuales:**
- Tienen poco tiempo para realizar labores domésticas o requieren apoyo constante.
- Buscan servicios confiables, seguros y de calidad.
- Valoran reseñas, calificaciones y verificación de perfiles.
- Utilizan aplicaciones móviles o prefieren soluciones simples y accesibles.
- En el caso de adultos mayores o familias con niños, priorizan confianza y continuidad del servicio.

**Sustento estadístico:**

Según el Instituto Nacional de Estadística e Informática (INEI), una gran proporción de la población en Lima se encuentra laboralmente activa, lo que incrementa la necesidad de externalizar tareas del hogar. Además, el crecimiento de la población adulta mayor en el Perú ha generado una mayor demanda de servicios de apoyo doméstico y cuidado personal.

### Segmento Objetivo 2: 
**Trabajadoras del hogar (Oferta de servicios)**

Este segmento está compuesto por personas que brindan servicios domésticos y buscan oportunidades laborales más estables y formales.

**Características demográficas:**
- Edad: entre 20 y 60 años
- Ubicación: Lima Metropolitana y zonas periféricas
- Nivel socioeconómico: bajo y medio
- Nivel educativo: primaria o secundaria completa

**Características conductuales:**
- Buscan empleo constante y mejores ingresos
- Tienen experiencia en limpieza, cocina y cuidado del hogar
- Muchas trabajan en condiciones informales
- Están interesadas en acceder a más oportunidades laborales y mejorar su estabilidad

**Sustento estadístico:**
De acuerdo con el Ministerio de Trabajo y Promoción del Empleo, en el Perú existen más de 400,000 trabajadoras del hogar, de las cuales la mayoría se encuentra en situación de informalidad, lo que evidencia la necesidad de soluciones que promuevan su formalización laboral.

## Capítulo II: Requirements Elicitation & Analysis

### 2.1. Competidores

#### 2.1.1. Análisis competitivo


| **Competitive Analysis Landscape** |  |  |  |  |  |
|-------------------------|--|--|--|--|--|
| ¿Por qué llevar a cabo este análisis?  | El objetivo de este análisis es identificar las fortalezas, debilidades, oportunidades y amenazas de los principales competidores en el mercado de servicios domésticos, con el fin de definir la ventaja competitiva de InCleanHome y su posicionamiento en el mercado peruano. |  |  |  |  |  |
|  |  | **InCleanHome**<br><img src="./assets/competidores/incleanhome.png" alt="InCleanHome" width="1000"> | **Zolvers**<br><img src="./assets/competidores/zolvers.png" alt="Zolvers" width="200"> | **TuAliada**<br><img src="./assets/competidores/tualiada.png" alt="TuAliada" width="450"> | **Servicios Informales (Facebook, etc)**<br><img src="./assets/competidores/facebook.webp" alt="Facebook" width="75"> |
| **Perfil** | Overview | Plataforma digital que conecta usuarios con trabajadoras del hogar mediante filtros avanzados y sistema de reseñas. | Plataforma digital que conecta usuarios con personal doméstico verificado en LATAM.| Empresa formal que brinda servicios de limpieza con personal contratado. | Medio informal para contactar trabajadoras del hogar sin intermediarios formales. |
| | **Ventaja competitiva**<br>¿Qué valor ofrece a los clientes? | Alta personalización, seguridad, filtros avanzados y adaptación al mercado peruano. | Personal verificado y sistema de reputación consolidado. | Servicio confiable con personal capacitado. | Bajo costo y fácil acceso. |
| **Perfil de marketing** |  |  |  |  |  |
| | **Mercado objetivo** | Hogares peruanos que buscan servicios domésticos confiables y personalizados. | Hogares urbanos de ingresos medios y altos en LATAM. | Hogares y oficinas en Lima que buscan servicios formales.  | Público general que busca soluciones rápidas y económicas. |
| | **Estrategias de marketing** | Marketing digital, redes sociales, enfoque en confianza y seguridad. | Publicidad digital, posicionamiento de marca y reputación online. | Branding formal, alianzas y marketing tradicional/digital. | Publicaciones en grupos y boca a boca. |
| **Perfil de Producto** |  |  |  |  |  |
| | **Productos & Servicios** | Plataforma web/móvil para contratar trabajadoras del hogar con filtros y reviews. | Plataforma digital para contratación de servicios domésticos. | Servicio de limpieza gestionado por la empresa. | Contacto directo con trabajadoras del hogar. |
| | **Precios & Costos** | Transparencia de precios, competitivos y accesibles. | Tarifas moderadas con comisión por servicio. | Costos más altos por servicio formal. | Bajos costos pero variables. |
| | **Canales de distribución** |  Canales de distribución (Web y/o Móvil) | Web y móvil | Web y móvil | Web y contacto directo | Redes sociales (Facebook, WhatsApp) |
| **Análisis SWOT** |  |  |  |  |
| | **Fortalezas** | Alta personalización, seguridad, sistema de reseñas, adaptación local. | Marca posicionada, sistema de reputación, experiencia internacional. | Servicio confiable, personal capacitado, formalidad. | Bajo costo, accesibilidad, rapidez. |
| | **Oportunidades** | Startup nueva, menor reconocimiento de marca. | No totalmente adaptado a Perú, costos relativamente altos. | Baja personalización, poca flexibilidad. | Falta de seguridad, informalidad, sin verificación. |
| | **Debilidades** | Crecimiento del mercado digital, formalización del sector, alta demanda insatisfecha. | Expansión en nuevos mercados. | Crecimiento del sector servicios en Perú. | Alta demanda en sectores informales. |
| | **Amenazas** | Competencia consolidada | Nuevas startups locales más adaptadas. | Plataformas digitales más innovadoras. | Regulación futura o desconfianza del usuario. |



#### 2.1.2. Estrategias y tácticas frente a competidores

InCleanHome adoptará una estrategia de diferenciación basada en la confianza, la personalización y la adaptación al mercado peruano, con el objetivo de posicionarse como una alternativa superior frente a plataformas digitales existentes y servicios informales.
Frente a Zolvers, la startup se diferenciará mediante una mayor personalización del servicio y adaptación local, implementando filtros avanzados y ofreciendo precios más accesibles y transparentes. En comparación con Aliada, se priorizará un modelo tipo marketplace que brinde mayor control al usuario, junto con un sistema de reseñas que fortalezca la confianza y permita una mejor toma de decisiones.
Respecto a los servicios informales, la estrategia estará enfocada en la formalización del servicio mediante herramientas tecnológicas como la verificación de identidad y sistemas de calificación, reduciendo los riesgos asociados a este tipo de contratación.
Asimismo, InCleanHome aprovechará el crecimiento del uso de plataformas digitales y la alta demanda de servicios confiables mediante estrategias de marketing digital y posicionamiento online. Frente a amenazas como la competencia consolidada o la desconfianza inicial, se apostará por la innovación continua y la generación de confianza a través de la experiencia del usuario.

### 2.2. Entrevistas

#### 2.2.1. Diseño de entrevistas

### Segmento 1: Clientes (Usuarios que demandan servicios domésticos)

1. ¿Con qué frecuencia necesitas servicios domésticos y que tipo de servicio sueles contratar (limpieza del hogar, de oficina de trabajo, etc)?
2. ¿Tienes alguna preferencia en cuanto a la persona que contratas ( edad, género o experiencia)?
3. ¿Qué dificultades encuentras al buscar personal doméstico y hay algunos factores que te generan inseguridad al contratarlos?
4. ¿Usas alguna plataforma digital para buscar personal doméstico y si es así qué aspectos valoras más en una plataforma para contratar servicios domésticos?
5. ¿Qué funcionalidades consideras imprescindibles en una plataforma para encontrar personal doméstico?
6. ¿Qué te motivaría a usar una plataforma digital para contratar servicios domésticos con regularidad?
7. ¿Qué te haría confiar más en una plataforma digital para contratar a una trabajadora del hogar?

---

### Segmento 2: Trabajadoras del hogar (Oferta de servicios)

1. ¿Qué tipo de servicios domésticos ofreces (limpieza, cocina, cuidado de niños, etc)?
2. ¿Cuantos años de experiencia tienes en trabajos domésticos?
3. ¿Qué dificultades encuentras al buscar trabajo de forma independiente?
4. ¿Qué tan importante es para ti trabajar en un entorno donde se valoren tus habilidades y experiencia?
5. ¿Estás interesada en acceder a una plataforma digital para ofrecer tus servicios domésticos? ¿Por qué?
6. ¿Qué características consideras importantes para que una plataforma digital sea útil para ti como trabajadora del hogar?
7. ¿Te gustaría tener la opción de comunicarte directamente con los clientes a través de la plataforma? ¿Qué ventajas verías en aquello?
8. ¿Qué te motivaría a usar una plataforma digital para ofrecer tus servicios?
9. ¿Qué funcionalidades crees que podrían mejorar tu experiencia laboral si estuvieras trabajando a través de una plataforma digital?

---

#### 2.2.2. Registro de entrevistas

#### Entrevista 1


<p align="center">
  <img src="./assets/entrevistas/videos/entrevista1.jpg" alt="entrevista1" width="400">
</p>

| **Detalle**          | **Información**                                                                 |
|----------------------|---------------------------------------------------------------------------------|
| **Entrevistador**    | Braden G.                                                     |
| **Entrevistado**     | Eduardo Chacarías Aminallo C.                                                        |
| **Edad**             | 26 años                                                  |
| **Inicio entrevista**| 00:00:00                                                      |
| **Duración**         | 00:02:25                                                   |
- Perfil: Ingeniero eléctrico residente en La Molina que trabaja en San Isidro.
- Necesidades: Requiere limpieza general del hogar una vez por semana y prefiere personal con experiencia y buenas referencias.
- Retos: Presenta inseguridad al contratar desconocidos y teme la falta de garantías ante incidentes.
- Expectativas: Valora la verificación de identidad, un sistema de reseñas y la facilidad para agendar.


#### Entrevista 2

<p align="center">
  <img src="./assets/entrevistas/videos/Entrevista5.png" alt="entrevista2" width="400">
</p>

| **Detalle**          | **Información**                                                                 |
|----------------------|---------------------------------------------------------------------------------|
| **Entrevistador**    | - Oscar Fernando Vara Velasquez                                                     |
| **Entrevistado**     | - Elvira Vara Velasquez                                                       |
| **Edad**             | - 23  años                                                 |
| **Inicio entrevista**| - 0:25                                                     |
| **Duración**         | - 5:41                                                  |
- Perfil: Usuario que busca limpieza profunda (muebles, cortinas) cada 7 o 15 días.
- Retos: Depende exclusivamente del "boca a boca" y la confianza en conocidos para encontrar personal.
- Expectativas: Sugiere que la plataforma realice filtros rigurosos como antecedentes penales, entrevistas y test psicológicos.

#### Entrevista 3

<p align="center">
  <img src="./assets/entrevistas/videos/entrevista3.jpg" alt="entrevista3" width="400">
</p>

| **Detalle**          | **Información**                                                                 |
|----------------------|---------------------------------------------------------------------------------|
| **Entrevistador**    |- Victor Espino Rossi                                                     |
| **Entrevistado**     | - Gianella Hermoza                                                        |
| **Edad**             | - 25   años                                                |
| **Inicio entrevista**| - 0:00                                                     |
| **Duración**         | - 2:08                                                  | 
- Perfil: Contrata servicios de limpieza y cocina mensualmente.
- Expectativas: Se centra en la importancia de las reseñas del personal y en contar con una plataforma funcional para agilizar el proceso.

#### Entrevista 4

<p align="center">
  <img src="./assets/entrevistas/videos/entrevista4.jpg" alt="entrevista4" width="400">
</p>

| **Detalle**          | **Información**                                                                 |
|----------------------|---------------------------------------------------------------------------------|
| **Entrevistador**    | Braden G.                                                     |
| **Entrevistado**     | Lupe D.                                                        |
| **Edad**             | 22 años                                                  |
| **Inicio entrevista**| 00:00:00                                                      |
| **Duración**         | 00:04:22                                                   |
- Perfil: Residente de San Juan de Lurigancho con un año y medio de experiencia en limpieza y cuidado de niños.
- Retos: Dificultad para encontrar ofertas constantes (esperas de hasta un mes) y problemas con clientes que piden tareas no pactadas (como cocinar) sin pago extra.
- Expectativas: Desea una comunicación directa con los clientes para negociar precios y servicios de forma clara.

#### Entrevista 5

<p align="center">
  <img src="./assets/entrevistas/videos/Entrevista2.png" alt="entrevista5" width="400">
</p>

| **Detalle**          | **Información**                                                                 |
|----------------------|---------------------------------------------------------------------------------|
| **Entrevistador**    | - Oscar Fernando Vara Velasquez                                                   |
| **Entrevistado**     | - Rosa Chavez                                                       |
| **Edad**             | - 31 años                                                  |
| **Inicio entrevista**| - 0:21                                                     |
| **Duración**         | - 5:08                                                    |
- Perfil: Ofrece limpieza integral de espacios del hogar con 2 años de experiencia laboral.
- Retos: La dificultad de darse a conocer de forma independiente y la lentitud de depender solo de recomendaciones personales.
- Expectativas: Busca una herramienta que le permita organizar sus horarios y contar con valoraciones (reviews) para atraer clientes más fácilmente.

#### Entrevista 6

<p align="center">
  <img src="./assets/entrevistas/videos/entrevista6.jpg" alt="entrevista6" width="400">
</p>

| **Detalle**          | **Información**                                                                 |
|----------------------|---------------------------------------------------------------------------------|
| **Entrevistador**    | - Victor Espino Rossi                                                     |
| **Entrevistado**     | - Romina Hermoza                                                        |
| **Edad**             | - 24  años                                                  |
| **Inicio entrevista**| - 0:00                                                     |
| **Duración**         | - 2:50                                                  |- Perfil: Ofertante de servicios domésticos interesada en la digitalización.
- Expectativas: Valora la capacidad de programar servicios y, al igual que sus colegas, destaca la necesidad de un canal de comunicación directo y fluido con el cliente a través de la aplicación.

**Link Entrevistas** 

 https://upcedupe-my.sharepoint.com/:v:/g/personal/u202317450_upc_edu_pe/IQB4sWvXGFrJT51Xtaludz0bAQtj2ECqeyWvBBIk5x_p6a8?e=XxVqfT&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D


#### 2.2.3. Análisis de entrevistas

1. Segmento #1: Clientes (Usuarios que demandan servicios domésticos)

Las entrevistas revelan que los usuarios jóvenes (23-26 años) demandan servicios domésticos con una frecuencia que varía desde una vez por semana hasta una vez al mes , priorizando la limpieza general, limpieza profunda de muebles y cocina. Actualmente, dependen de métodos informales como el "boca a boca" a través de conocidos o grupos de Facebook , debido a una profunda desconfianza hacia los desconocidos y al temor por la seguridad del hogar. El factor crítico de decisión para utilizar una plataforma digital es la existencia de un filtro riguroso que incluya verificación de antecedentes penales, pruebas psicológicas y un sistema de reseñas basado en experiencias previas.
En conclusión, la oportunidad para la aplicación reside en transformar la informalidad del sector en un servicio de confianza mediante la transparencia de datos. La solución debe actuar como un filtro de seguridad que mitigue el miedo al incumplimiento o la inseguridad. Para que el proyecto sea viable, la propuesta de valor debe centrarse en el ahorro de tiempo y la "paz mental" del cliente , ofreciendo soporte al cliente y un sistema de reputación que replique la fiabilidad de las recomendaciones tradicionales en un entorno digital eficiente.

2. Segmento #2: Trabajadoras del hogar (Oferta de servicios)

Las entrevistas con las trabajadoras revelan que su principal desafío es la inestabilidad laboral; Lupe (1.5 años de experiencia) y Rosa (2 años de experiencia) coinciden en que la búsqueda independiente es lenta, pudiendo pasar semanas o meses sin contratos nuevos. Además, enfrentan abusos donde los clientes exigen tareas no pactadas (como cocinar cuando se contrató limpieza) amparados en que "ya se pagó". Ambas muestran un alto interés en una plataforma digital que actúe como un respaldo profesional , permitiéndoles gestionar sus horarios de forma ordenada y ampliar su mercado más allá de sus zonas de residencia para encontrar ofertas más factibles y cercanas.
En conclusión, para que la aplicación sea exitosa, debe funcionar como una herramienta de empoderamiento y protección laboral. Los hallazgos sugieren que las funcionalidades críticas deben incluir un sistema de comunicación directa para negociar términos y precios claramente , un calendario integrado para organizar servicios y un perfil profesional donde se valore su experiencia mediante reseñas. La plataforma tiene el potencial de profesionalizar el sector al reducir la brecha de desconfianza y facilitar que la trabajadora no tenga que "recomendarse a sí misma" constantemente, sino que su trabajo hable por ella a través del sistema.

1. Frecuencia de uso vs disponibilidad laboral:
<p align="center">
  <img src="./assets/entrevistas/estadisticas/frecuencia.png" alt="Frecuencia de uso vs disponibilidad laboral" width="550">
</p>

2. Factores de confianza (clientes vs trabajadoras)
<p align="center">
  <img src="./assets/entrevistas/estadisticas/confianza.png" alt="Factores de confianza" width="550">
</p>

3. Uso y aceptación de plataformas digitales
<p align="center">
  <img src="./assets/entrevistas/estadisticas/aceptacion.png" alt="Uso y aceptación de plataformas" width="550">
</p>

4. Principales dificultades (oferta vs demanda)
<p align="center">
  <img src="./assets/entrevistas/estadisticas/dificultades.png" alt="Principales dificultades" width="550">
</p>

5. Funcionalidades clave esperadas
<p align="center">
  <img src="./assets/entrevistas/estadisticas/funcionalidades.png" alt="Funcionalidades clave esperadas" width="550">
</p>

### 2.3. Needfinding

#### 2.3.1. User Personas
La presente sección expone las fichas de User Persona, herramientas fundamentales que representan los arquetipos de nuestros usuarios objetivo: los clientes que demandan servicios domésticos y las trabajadoras del hogar que ofrecen dichos servicios. Estos artefactos se han construido a partir de los hallazgos clave obtenidos en la fase de entrevistas y considerando el análisis competitivo del mercado. Frente a un mercado caracterizado por la informalidad y la falta de verificación en alternativas informales , nuestros User Personas reflejan la necesidad imperativa de confianza, seguridad y flexibilidad. Para los clientes, el arquetipo prioriza la validación de perfiles mediante antecedentes y reseñas ; mientras que, para las trabajadoras, el arquetipo subraya la búsqueda de un entorno seguro, pagos puntuales y control sobre su disponibilidad. A continuación, se detallan los perfiles modelados utilizando la herramienta UXPressia.


*Segmento 1: El Cliente (Segmento Demanda)*

<p align="center">
  <img src="./assets/needfinding/userpersonas/segmento1cliente.jpg" alt="Segmento 1: El Cliente" width="550">
</p>

*Segmento 2: Trabajadora del Hogar (Segmento Oferta)*

<p align="center">
  <img src="./assets/needfinding/userpersonas/segmento2trabajadora.jpg" alt="Segmento 2: Trabajadora del Hogar" width="550">
</p>


#### 2.3.2. User Task Matrix

##### Introducción:
El siguiente User Task Matrix presenta las principales tareas que realizan los dos segmentos de usuarios identificados. Para este proyecto, consideramos dos segmentos principales: los Clientes 
(quienes demandan los servicios) y las Trabajadoras del hogar (quienes ofrecen los 
servicios). Se identifican actividades clave para cada grupo, evaluadas según su frecuencia e importancia, considerando su experiencia actual sin el uso de la solución propuesta.

| **Tareas (Tasks)**                     | **Clientes** |  | **Trabajadoras** |  |
| -------------------------------------- | ------------------------- | -------------------------- | ----------------------------- | ------------------------------ |
| | Frecuencia | Importancia | Frecuencia |Importancia|
| Buscar referencias o recomendaciones   | A veces                   | Alta                       | A veces                       | Media                          |
| Evaluar confiabilidad / antecedentes   | A veces                   | Alta                       | A veces                       | Media                          |
| Coordinar fechas, horarios y tareas    | Siempre                   | Alta                       | Siempre                       | Alta                           |
| Negociar tarifas / pago                | A veces                   | Media                      | A veces                       | Alta                           |
| Ejecutar labores domésticas            | -                         | -                          | Siempre                       | Alta                           |
| Supervisar el trabajo realizado        | A veces                   | Media                      | -                             | -                              |
| Realizar / cobrar el pago              | Siempre                   | Alta                       | Siempre                       | Alta                           |
| Recomendar / solicitar recomendaciones | A veces                   | Media                      | A veces                       | Media                          |
| Buscar oportunidades de trabajo        | -                         | -                          | A veces                       | Alta                           |

#### Explicación:

Las tareas con mayor frecuencia e importancia en ambos segmentos son la coordinación de horarios y tareas y el proceso de pago, lo que evidencia que la organización y la seguridad en la transacción son aspectos críticos en la interacción entre clientes y trabajadoras del hogar.

Desde la perspectiva de los clientes, destacan como altamente importantes la búsqueda de referencias y la evaluación de la confiabilidad, aunque no se realizan siempre, lo que refleja una preocupación constante por la seguridad al contratar. En contraste, las trabajadoras del hogar asignan mayor importancia a la negociación del pago y a la búsqueda de oportunidades laborales, lo que evidencia su enfoque en la estabilidad económica.

Una diferencia clave es que los clientes realizan tareas de supervisión, mientras que las trabajadoras se enfocan en la ejecución del servicio, mostrando roles claramente complementarios. Asimismo, ambos coinciden en la importancia de las recomendaciones, lo que indica que la reputación y confianza son elementos centrales en este mercado.

En conjunto, el análisis evidencia una oportunidad para soluciones que reduzcan la desconfianza, faciliten la coordinación y mejoren la visibilidad de la reputación, alineando las necesidades de ambos segmentos.

#### 2.3.3. User Journey Mapping

*Segmento 1: El Cliente (Segmento Demanda)*

<p align="center">
  <img src="./assets/needfinding/journeymapping/segmento1cliente.png" alt="Segmento 1: El Cliente" width="550">
</p>

*Segmento 2: Trabajadora del Hogar (Segmento Oferta)*

<p align="center">
  <img src="./assets/needfinding/journeymapping/segmento2trabajadora.png" alt="Segmento 2: Trabajadora del Hogar" width="550">
</p>



#### 2.3.4. Empathy Mapping

*Segmento 1: El Cliente (Segmento Demanda)*

<p align="center">
  <img src="./assets/needfinding/empathymapping/segmento1cliente.jpg" alt="Segmento 1: El Cliente" width="550">
</p>

*Segmento 2: Trabajadora del Hogar (Segmento Oferta)*

<p align="center">
  <img src="./assets/needfinding/empathymapping/segmento2trabajadora.jpg" alt="Segmento 2: Trabajadora del Hogar" width="550">
</p>

### 2.4. Big Picture EventStorming 

<p align="center">
  <img src="./assets/eventstorming/eventstorming.jpg" alt="EventStorming" width="550">
</p>

### 2.5. Ubiquitous Language

Este será el lenguaje común utilizado en la plataforma de servicios domésticos, permitiendo que todos los miembros del equipo y stakeholders comprendan claramente los conceptos clave del dominio del negocio.

#### Customer
Usuario que solicita servicios domésticos a través de la plataforma, como limpieza, cocina o cuidado del hogar.

#### Domestic Worker
Persona que ofrece servicios domésticos mediante la plataforma, incluyendo limpieza, cocina, cuidado de niños u otras tareas del hogar.

#### Service
Actividad doméstica acordada entre el cliente y la trabajadora, con condiciones específicas como tareas, duración, ubicación y horario.

#### Service Request 
Petición inicial realizada por el cliente para contactar a una trabajadora y proponer la realización de un servicio.

#### Booking
Confirmación formal del servicio entre cliente y trabajadora, incluyendo fecha, hora y condiciones acordadas.

#### Availability
Información proporcionada por la trabajadora sobre los días y horarios en los que puede ofrecer sus servicios.

#### Profile
Conjunto de información del usuario (cliente o trabajadora), que incluye datos personales, experiencia, habilidades, reseñas y calificaciones.

#### Rating
Puntuación otorgada por un usuario (cliente o trabajadora) después de la realización de un servicio.

#### Review
Comentario cualitativo que acompaña la calificación, basado en la experiencia del servicio realizado.

#### Reputation
Valor acumulado basado en las calificaciones y reseñas de un usuario, que refleja su confiabilidad dentro de la plataforma.

#### Payment
Transacción económica realizada por el cliente a cambio del servicio brindado por la trabajadora.

#### Payment Confirmation
Validación de que el pago fue realizado correctamente y recibido por la trabajadora.

#### Service History
Registro de todos los servicios realizados por un usuario dentro de la plataforma.

#### Matching
Proceso mediante el cual la plataforma conecta clientes con trabajadoras en función de criterios como ubicación, disponibilidad, experiencia y calificaciones.

#### Filter
Herramienta utilizada por el cliente para refinar la búsqueda de trabajadoras según criterios específicos.

#### Notification
Mensaje automático enviado por la plataforma para informar sobre solicitudes, confirmaciones, recordatorios o actualizaciones.

#### Cancellation
Acción de anular un servicio previamente acordado por parte del cliente o la trabajadora.

#### Agreement
Condiciones definidas entre cliente y trabajadora antes de ejecutar el servicio, incluyendo tareas, pago y horario.

#### Security
Percepción de confianza del usuario al utilizar la plataforma, relacionada con la verificación de perfiles, pagos y evaluaciones.

#### Trust
Nivel de credibilidad que un usuario tiene sobre otro, basado en reputación, reseñas y experiencia previa.

#### Support
Asistencia brindada a los usuarios para resolver dudas, problemas o inconvenientes relacionados con el servicio.


## Capítulo III: Requirements Specification

### 3.1. User Stories


| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|----------------|--------|------------|--------------------------|----------------------------|
| EP-01 | Gestión de usuarios | Como usuario, deseo gestionar mi cuenta para acceder de forma segura al sistema | - | - |
| EP-02 | Búsqueda y filtrado | Como cliente, deseo buscar y filtrar trabajadoras para encontrar opciones adecuadas | - | - |
| EP-03 | Perfiles y reseñas | Como cliente, deseo visualizar perfiles y reseñas para tomar decisiones informadas | - | - |
| EP-04 | Contratación y pagos | Como cliente, deseo contratar servicios para gestionar solicitudes y pagos | - | - |
| EP-05 | Comunicación y notificaciones | Como usuario, deseo comunicarme y recibir notificaciones para coordinar servicios | - | - |
| EP-06 | Gestión de disponibilidad | Como trabajadora, deseo gestionar mi disponibilidad para organizar mis horarios | - | - |
| EP-07 | Seguridad y cumplimiento | Como usuario, deseo proteger mis datos para garantizar privacidad | - | - |
| US-01 | Registro de cliente | Como cliente, deseo registrarme para acceder a la plataforma | Given que el cliente ingresa datos válidos, when envía el formulario, then el sistema crea la cuenta. <br><br> Given que los datos son inválidos, when envía el formulario, then el sistema muestra error. | EP-01 |
| US-02 | Inicio de sesión cliente | Como cliente, deseo iniciar sesión para acceder a mi cuenta | Given que las credenciales son correctas, when inicia sesión, then el sistema permite acceso. <br><br> Given que son incorrectas, when inicia sesión, then el sistema rechaza acceso. | EP-01 |
| US-03 | Editar perfil cliente | Como cliente, deseo actualizar mis datos para mantener información correcta | Given que los datos son válidos, when guarda cambios, then el sistema actualiza la información. <br><br> Given que son inválidos, when guarda cambios, then el sistema muestra error. | EP-01 |
| US-20 | Recuperar contraseña cliente | Como cliente, deseo recuperar mi contraseña para acceder nuevamente | Given que el correo está registrado, when solicita recuperación, then el sistema envía enlace. <br><br> Given que no está registrado, when solicita recuperación, then el sistema muestra error. | EP-01 |
| US-04 | Filtrar por ubicación | Como cliente, deseo filtrar por ubicación para encontrar trabajadoras cercanas | Given que existen resultados, when realiza búsqueda, then el sistema muestra coincidencias. <br><br> Given que no existen resultados, when busca, then el sistema informa ausencia. | EP-02 |
| US-06 | Filtrar por habilidades | Como cliente, deseo filtrar por habilidades para encontrar opciones adecuadas | Given que existen coincidencias, when aplica filtros, then el sistema muestra resultados. <br><br> Given que no existen coincidencias, when aplica filtros, then el sistema muestra lista vacía. | EP-02 |
| US-07 | Filtrar por disponibilidad | Como cliente, deseo filtrar por horario para encontrar disponibilidad | Given que hay disponibilidad, when busca, then el sistema muestra resultados. <br><br> Given que no hay disponibilidad, when busca, then el sistema informa ausencia. | EP-02 |
| US-10 | Ordenar resultados | Como cliente, deseo ordenar resultados para elegir mejor opción | Given que selecciona criterio, when aplica orden, then el sistema ordena resultados. | EP-02 |
| US-05 | Ver perfiles | Como cliente, deseo visualizar perfiles para evaluar opciones | Given que el perfil está completo, when accede, then el sistema muestra información. <br><br> Given que está incompleto, when accede, then el sistema muestra advertencia. | EP-03 |
| US-09 | Ver reseñas | Como cliente, deseo ver reseñas para tomar decisiones informadas | Given que existen reseñas, when accede, then el sistema las muestra. <br><br> Given que no existen, when accede, then el sistema lo indica. | EP-03 |
| US-14 | Calificar servicio | Como cliente, deseo calificar servicios para compartir experiencia | Given que el servicio finalizó, when registra calificación, then el sistema guarda la evaluación. | EP-03 |
| US-17 | Reportar trabajadora | Como cliente, deseo reportar perfiles sospechosos para mejorar seguridad | Given que detecta perfil sospechoso, when envía reporte, then el sistema lo registra. | EP-03 |
| US-08 | Contratar servicio | Como cliente, deseo contratar servicios para agendar atención | Given que hay disponibilidad, when agenda servicio, then el sistema registra solicitud. <br><br> Given que no hay disponibilidad, when agenda, then el sistema rechaza operación. | EP-04 |
| US-11 | Método de pago | Como cliente, deseo seleccionar método de pago para completar servicio | Given que el servicio está activo, when selecciona método, then el sistema lo registra. | EP-04 |
| US-12 | Generar comprobante cliente | Como cliente, deseo recibir comprobante para validar pago | Given que el pago se completa, when finaliza servicio, then el sistema genera comprobante. | EP-04 |
| US-15 | Cancelar servicio | Como cliente, deseo cancelar servicio para reorganizarme | Given que está dentro del plazo, when cancela, then el sistema procesa cancelación. <br><br> Given que no está permitido, when cancela, then el sistema rechaza. | EP-04 |
| US-16 | Historial cliente | Como cliente, deseo ver historial para revisar servicios | Given que existen registros, when accede, then el sistema muestra historial. | EP-04 |
| US-13 | Mensajería cliente | Como cliente, deseo comunicarme para coordinar servicios | Given que existe conexión, when envía mensaje, then el sistema lo entrega. | EP-05 |
| US-18 | Notificaciones cliente | Como cliente, deseo recibir notificaciones para estar informado | Given que ocurre evento, when se genera, then el sistema envía notificación. | EP-05 |
| US-21 | Registro trabajadora | Como trabajadora, deseo registrarme para ofrecer servicios | Given que datos válidos, when envía formulario, then el sistema crea cuenta. | EP-01 |
| US-22 | Completar perfil trabajadora | Como trabajadora, deseo completar perfil para ser visible | Given que datos completos, when guarda, then el sistema marca perfil completo. | EP-03 |
| US-23 | Verificación trabajadora | Como trabajadora, deseo ser verificada para ofrecer servicios | Given que datos válidos, when se revisa, then el sistema aprueba cuenta. | EP-03 |
| US-24 | Login trabajadora | Como trabajadora, deseo iniciar sesión para gestionar servicios | Given que credenciales válidas, when inicia sesión, then el sistema permite acceso. | EP-01 |
| US-25 | Editar perfil trabajadora | Como trabajadora, deseo actualizar datos para mantener información correcta | Given que datos válidos, when guarda cambios, then el sistema actualiza información. | EP-01 |
| US-26 | Gestión de disponibilidad | Como trabajadora, deseo gestionar disponibilidad para organizar agenda | Given que modifica disponibilidad, when guarda cambios, then el sistema actualiza calendario. | EP-06 |
| US-27 | Mensajería trabajadora | Como trabajadora, deseo comunicarme para coordinar servicios | Given que envía mensaje, when existe conexión, then el sistema lo entrega. | EP-05 |
| US-28 | Reportar cliente | Como trabajadora, deseo reportar clientes para mejorar seguridad | Given que detecta perfil sospechoso, when reporta, then el sistema registra reporte. | EP-03 |
| US-29 | Comprobante trabajadora | Como trabajadora, deseo recibir comprobante para validar ingresos | Given que servicio finaliza, when se procesa pago, then el sistema genera comprobante. | EP-04 |
| US-30 | Notificaciones trabajadora | Como trabajadora, deseo recibir notificaciones para estar informada | Given que ocurre evento, when se genera, then el sistema envía notificación. | EP-05 |
| US-31 | Historial trabajadora | Como trabajadora, deseo ver historial para registrar servicios | Given que existen registros, when accede, then el sistema muestra historial. | EP-04 |
| US-32 | Seguridad trabajadora | Como trabajadora, deseo proteger mis datos para garantizar privacidad | Given que se transmiten datos, when ocurre comunicación, then el sistema usa cifrado. | EP-07 |
| US-33 | Recuperar contraseña trabajadora | Como trabajadora, deseo recuperar contraseña para acceder nuevamente | Given que correo válido, when solicita recuperación, then el sistema envía enlace. | EP-01 |
| US-34 | Ver comisión | Como trabajadora, deseo ver comisión para conocer pagos a plataforma | Given que existen servicios, when consulta, then el sistema calcula comisión. | EP-04 |
| US-35 | Descuento comisión | Como trabajadora, deseo pagar comisión automáticamente para cumplir obligaciones | Given que hay fondos, when se ejecuta cobro, then el sistema descuenta comisión. | EP-04 |
| US-L01 | Visualizar servicio | Como usuario, deseo conocer el servicio para entender la plataforma | Given que accede al sitio, when carga la página, then el sistema muestra información. | EP-02 |
| US-L03 | Entender proceso | Como usuario, deseo ver cómo funciona para saber cómo contratar | Given que accede a sección, when navega, then el sistema muestra proceso. | EP-02 |
| US-L05 | Navegación | Como usuario, deseo navegar para explorar contenido | Given que interactúa con la página, when selecciona sección, then el sistema permite navegación. | EP-02 |
| TS-01 | API registro | Como developer, deseo registrar usuarios para crear cuentas | Given datos válidos, when request, then responde 201. | EP-01 |
| TS-02 | API login | Como developer, deseo autenticar usuarios para acceso | Given credenciales válidas, when request, then responde token. | EP-01 |
| TS-04 | API búsqueda | Como developer, deseo buscar con filtros para obtener resultados | Given datos existentes, when consulta, then retorna lista. | EP-02 |
| TS-05 | API crear servicio | Como developer, deseo registrar servicios para contrataciones | Given datos válidos, when request, then crea servicio. | EP-04 |
| TS-06 | API cancelar servicio | Como developer, deseo cancelar servicios para gestión | Given cancelación válida, when request, then cancela servicio. | EP-04 |
| TS-10 | API notificaciones | Como developer, deseo enviar notificaciones para eventos | Given evento, when ocurre, then envía notificación. | EP-05 |

### 3.2. Impact Mapping
A continuación se visualiza el **Impact Map** del proyecto, donde se muestra la relación entre el *Business Goal* definido, los **User Personas** identificados, los **Impactos** esperados en su comportamiento, los **Deliverables** que como negocio digital podemos ofrecer y las **User Stories** asociadas que permitirán implementar las funcionalidades necesarias en la aplicación web y la landing page. Este mapa busca asegurar la alineación entre los objetivos estratégicos y el desarrollo de la solución digital.


<p align="center">
  <img src="./assets/impactmapping/impactmapping.png" alt="Impact Mapping" width="700">
</p>

Link: https://drive.google.com/file/d/1BR5BatpnbY6CP7mPb5e2RJWy8tfnCuxR/view?usp=sharing 


### 3.3. Product Backlog

| # Orden | User Story ID | Título | Descripción | Story Points |
|--------|--------------|--------|------------|--------------|
| 1 | US-L01 | Visualizar servicio | Como usuario, deseo conocer el servicio para entender la plataforma | 3 |
| 2 | US-L03 | Entender proceso | Como usuario, deseo ver cómo funciona para saber cómo contratar | 3 |
| 3 | US-L05 | Navegación | Como usuario, deseo navegar para explorar contenido | 2 |
| 4 | US-05 | Ver perfiles | Como cliente, deseo visualizar perfiles para evaluar opciones | 5 |
| 5 | US-09 | Ver reseñas | Como cliente, deseo ver reseñas para tomar decisiones informadas | 3 |
| 6 | US-04 | Filtrar por ubicación | Como cliente, deseo filtrar por ubicación para encontrar trabajadoras cercanas | 5 |
| 7 | US-06 | Filtrar por habilidades | Como cliente, deseo filtrar por habilidades para encontrar opciones adecuadas | 5 |
| 8 | US-07 | Filtrar por disponibilidad | Como cliente, deseo filtrar por horario para encontrar disponibilidad | 5 |
| 9 | US-10 | Ordenar resultados | Como cliente, deseo ordenar resultados para elegir mejor opción | 2 |
| 10 | US-01 | Registro de cliente | Como cliente, deseo registrarme para acceder a la plataforma | 5 |
| 11 | US-02 | Inicio de sesión cliente | Como cliente, deseo iniciar sesión para acceder a mi cuenta | 3 |
| 12 | US-03 | Editar perfil cliente | Como cliente, deseo actualizar mis datos para mantener información correcta | 3 |
| 13 | US-20 | Recuperar contraseña cliente | Como cliente, deseo recuperar mi contraseña para acceder nuevamente | 2 |
| 14 | US-08 | Contratar servicio | Como cliente, deseo contratar servicios para agendar atención | 8 |
| 15 | US-11 | Método de pago | Como cliente, deseo seleccionar método de pago para completar servicio | 5 |
| 16 | US-12 | Generar comprobante cliente | Como cliente, deseo recibir comprobante para validar pago | 3 |
| 17 | US-15 | Cancelar servicio | Como cliente, deseo cancelar servicio para reorganizarme | 3 |
| 18 | US-16 | Historial cliente | Como cliente, deseo ver historial para revisar servicios | 3 |
| 19 | US-13 | Mensajería cliente | Como cliente, deseo comunicarme para coordinar servicios | 5 |
| 20 | US-18 | Notificaciones cliente | Como cliente, deseo recibir notificaciones para estar informado | 3 |
| 21 | US-21 | Registro trabajadora | Como trabajadora, deseo registrarme para ofrecer servicios | 5 |
| 22 | US-22 | Completar perfil trabajadora | Como trabajadora, deseo completar perfil para ser visible | 5 |
| 23 | US-23 | Verificación trabajadora | Como trabajadora, deseo ser verificada para ofrecer servicios | 8 |
| 24 | US-24 | Login trabajadora | Como trabajadora, deseo iniciar sesión para gestionar servicios | 3 |
| 25 | US-25 | Editar perfil trabajadora | Como trabajadora, deseo actualizar datos para mantener información correcta | 3 |
| 26 | US-26 | Gestión de disponibilidad | Como trabajadora, deseo gestionar disponibilidad para organizar agenda | 5 |
| 27 | US-27 | Mensajería trabajadora | Como trabajadora, deseo comunicarme para coordinar servicios | 5 |
| 28 | US-28 | Reportar cliente | Como trabajadora, deseo reportar clientes para mejorar seguridad | 2 |
| 29 | US-29 | Comprobante trabajadora | Como trabajadora, deseo recibir comprobante para validar ingresos | 3 |
| 30 | US-30 | Notificaciones trabajadora | Como trabajadora, deseo recibir notificaciones para estar informada | 3 |
| 31 | US-31 | Historial trabajadora | Como trabajadora, deseo ver historial para registrar servicios | 3 |
| 32 | US-33 | Recuperar contraseña trabajadora | Como trabajadora, deseo recuperar contraseña para acceder nuevamente | 2 |
| 33 | US-14 | Calificar servicio | Como cliente, deseo calificar servicios para compartir experiencia | 2 |
| 34 | US-17 | Reportar trabajadora | Como cliente, deseo reportar perfiles sospechosos para mejorar seguridad | 2 |
| 35 | US-34 | Ver comisión | Como trabajadora, deseo ver comisión para conocer pagos a plataforma | 3 |
| 36 | US-35 | Descuento comisión | Como trabajadora, deseo pagar comisión automáticamente para cumplir obligaciones | 5 |
| 37 | TS-04 | API búsqueda | Como developer, deseo buscar con filtros para obtener resultados | 5 |
| 38 | TS-05 | API crear servicio | Como developer, deseo registrar servicios para contrataciones | 5 |
| 39 | TS-06 | API cancelar servicio | Como developer, deseo cancelar servicios para gestión | 3 |
| 40 | TS-10 | API notificaciones | Como developer, deseo enviar notificaciones para eventos | 3 |
| 41 | TS-01 | API registro | Como developer, deseo registrar usuarios para crear cuentas | 5 |
| 42 | TS-02 | API login | Como developer, deseo autenticar usuarios para acceso | 3 |
| 43 | US-L01 | Registro de trabajador | Como profesional de limpieza, deseo registrarme mediante un formulario modal ingresando mis datos y preferencias (correo, contraseña, ubicación, tipo de servicio, idioma) para ofrecer mis servicios en la plataforma. | 5 |
| 44 | US-L02 | Registro de cliente | Como cliente potencial, deseo crear una cuenta a través de un modal ingresando mis datos personales (nombre, apellidos, DNI, celular, correo) para poder contratar personal doméstico. | 5 |
| 45 | US-L03 | Inicio de sesión unificado | Como usuario registrado (cliente o trabajador), deseo iniciar sesión desde la barra de navegación con mi correo y contraseña para acceder a mi panel de gestión. | 3 |
| 46 | US-L04 | Recuperación de credenciales | Como usuario, deseo tener acceso a la opción "¿Olvidaste tu contraseña?" en el modal de inicio de sesión para restablecer mi acceso mediante un flujo seguro de correo electrónico. | 3 |
| 47 | US-L05 | Búsqueda paramétrica de servicios | Como cliente, deseo utilizar un motor de búsqueda inteligente en la página principal filtrando por ubicación, tipo de servicio, disponibilidad, calificación e idioma para encontrar profesionales altamente compatibles. | 8 |
| 48 | US-L06 | Navegación por categorías | Como cliente, deseo filtrar el motor de búsqueda principal mediante pestañas de categorías (Limpieza, Cocina, Jardín, Cuidados) para delimitar mi requerimiento de forma rápida. | 2 |
| 49 | US-L07 | Suscripción a Newsletter | Como visitante, deseo suscribirme al boletín ingresando mi correo electrónico en el footer para recibir actualizaciones de la plataforma, validando previamente el formato de mi correo. | 2 |
| 50 | US-L08 | Visualización de propuesta de valor | Como visitante, deseo visualizar los beneficios clave (antecedentes verificados, pagos seguros, reservas flexibles) en la sección "Features" para entender las garantías de la plataforma. | 3 |
| 51 | US-L09 | Consumo de testimonios | Como visitante, deseo leer reseñas de otros clientes verificados para evaluar la confiabilidad del servicio antes de tomar una decisión de registro o compra. | 2 |
| 52 | US-L10 | Adaptabilidad móvil (Menú Hamburguesa) | Como usuario de dispositivos móviles, deseo acceder a un menú colapsable interactivo para poder navegar por las distintas secciones de la página de forma ergonómica. | 3 |


<p align="center">
  <img src="./assets/productbacklog/productbacklog.png" alt="Product Backlog" width="700">
</p>

Link: https://trello.com/invite/b/69e53cf162d5cd735ac20f75/ATTI28be5c17f5cd08eeea20dd1e0e323b79C619AC52/product-backlog-a


## Capítulo IV: Product Design

### 4.1. Style Guidelines

#### 4.1.1. General Style Guidelines


InCleanHome establece un sistema de diseño coherente que refleja los valores centrales de la plataforma: confianza, limpieza, seguridad y accesibilidad. Las decisiones visuales buscan transmitir profesionalismo y calidez simultáneamente, generando confianza en los usuarios al momento de contratar personal doméstico.

**Branding**
<p align="center">
    <img src="./assets/logo/logo-InCleanHome.png" alt="InCleanHome-logo" width="150px" height="150px"/>
</p>


El nombre "InCleanHome" comunica de manera directa el propósito del producto: conectar hogares con personal de limpieza de confianza. El logotipo es una casa junto al nombre en tipografía Nunito Black, combinando cercanía y modernidad. La identidad visual apuesta por un estilo limpio y contemporáneo, evitando la sobrecarga visual.

**Paleta de colores**

<p align="center">
    <img src="./assets/color-palette//paleta-colores.png" alt="Paleta de colores" width="390px" height="390px"/>
</p>

| Token          | Valor HEX | Uso principal                                      |
|----------------|-----------|----------------------------------------------------|
| `--green`      | `#00b272` | Color primario de marca, botones CTA, iconos       |
| `--green-dark` | `#009960` | Estado hover de elementos primarios                |
| `--green-light`| `#e6f9f2` | Fondos secundarios, destacados suaves              |
| `--navy`       | `#1a2e4a` | Títulos, texto de alto contraste, footer           |
| `--text`       | `#3a4a5c` | Texto de cuerpo general                            |
| `--text-light` | `#7a8fa6` | Texto secundario, etiquetas, placeholders          |
| `--bg`         | `#f7fafc` | Fondo de tarjetas y secciones alternas             |
| `--white`      | `#ffffff` | Fondo principal, superficies de componentes        |
| `--border`     | `#e2edf5` | Bordes de tarjetas, inputs, divisores              |

El verde `#00b272` fue seleccionado por su asociación cultural con la naturaleza, limpieza y crecimiento, mientras que el azul marino `#1a2e4a` transmite autoridad, seguridad y profesionalismo, creando un equilibrio visual entre frescura y confianza.

**Tipografía**

- **Nunito** (pesos 400, 600, 700, 800, 900): tipografía principal para títulos, logotipo, botones y elementos de navegación. Su forma redondeada aporta cercanía y modernidad.
- **Inter** (pesos 400, 500, 600): tipografía secundaria para texto de cuerpo, párrafos descriptivos y etiquetas de formulario. Optimizada para legibilidad en pantalla.

La escala tipográfica usa `clamp()` para adaptación fluida entre dispositivos:
- Headings principales: `clamp(32px, 5vw, 52px)`
- Headings de sección: `clamp(26px, 4vw, 38px)`
- Cuerpo de texto: 14–16px
- Etiquetas y texto auxiliar: 12–13px

**Espaciado y forma**

El sistema de espaciado utiliza múltiplos de 4px como base. Los radios de borde son:
- `--radius: 12px` — para tarjetas, inputs y elementos medianos
- `--radius-lg: 20px` — para contenedores de mayor jerarquía visual

Las sombras siguen una escala de elevación:
- `--shadow`: `0 4px 24px rgba(26,46,74,0.08)` — sombra suave para hover
- `--shadow-lg`: `0 12px 40px rgba(26,46,74,0.14)` — sombra de alta elevación

**Tono de comunicación**

InCleanHome adopta un tono **formal pero cercano**, con un lenguaje claro y directo. Se evita el tecnicismo innecesario. Los mensajes destacan la seguridad y verificación como valores centrales, generando confianza sin resultar intimidantes. La comunicación es **entusiasta pero serena**, transmitiendo seguridad en lugar de urgencia.

---
#### 4.1.2. Web Style Guidelines

Las guías de estilo web definen los estándares de interacción y presentación para las interfaces responsivas de InCleanHome, aplicables tanto al Landing Page como a la futura Web Application.

**Botones**

Se definen cuatro variantes de botón con comportamientos hover estandarizados:

- **Primary** (`btn-primary`): fondo verde `#00b272`, texto blanco. En hover: `#009960` con elevación de `translateY(-1px)` y sombra verde.
- **Outline** (`btn-outline`): borde azul marino, texto azul marino. En hover: relleno sólido azul marino con texto blanco.
- **White** (`btn-white`): fondo blanco con texto verde oscuro. Usado sobre fondos oscuros.
- **Outline White** (`btn-outline-white`): borde semitransparente blanco. Usado en el banner CTA.

Todos los botones comparten: `padding: 12px 24px`, `border-radius: 8px`, `font-weight: 700`, fuente Nunito y `transition: 0.3s cubic-bezier(0.4,0,0.2,1)`.

**Tarjetas (Cards)**

Las tarjetas de características y reseñas utilizan fondo `#f7fafc`, borde `1px solid #e2edf5` y `border-radius: 20px`. En hover aplican `translateY(-4px)` con sombra aumentada, generando sensación de elevación interactiva.

**Formularios**

Los inputs y selects siguen un estilo unificado: fondo `#f7fafc`, borde `1.5px solid #e2edf5`, `border-radius: 8px`. En estado focus el borde cambia a verde `#00b272` y el fondo a blanco, señalizando claramente el campo activo. Las etiquetas usan texto en mayúsculas de 12px con letra `#7a8fa6`.

**Navegación**

La navbar es sticky con `z-index: 100`, fondo blanco y sombra que se incrementa al hacer scroll (manejada por JavaScript). En mobile (≤768px) los enlaces se ocultan y aparece un botón hamburger animado que despliega un menú vertical.

**Animaciones y transiciones**

Los elementos con `[data-animate]` inician con `opacity: 0` y `translateY(24px)`, y al entrar al viewport reciben la clase `visible` que los anima a su posición final. El `IntersectionObserver` aplica un stagger de 120ms entre elementos hermanos. La transición base es `0.3s cubic-bezier(0.4,0,0.2,1)` para una sensación fluida y moderna.

**Responsive Breakpoints**

| Breakpoint | Cambios principales                                                    |
|------------|------------------------------------------------------------------------|
| ≤ 1024px   | Footer de 4 columnas pasa a 2 columnas                                 |
| ≤ 768px    | Nav colapsa a hamburger, hero pasa a 1 columna, grids a 1 col          |
| ≤ 480px    | Título hero a 28px, botones hero en columna, formulario en 1 columna   |

---

### 4.2. Information Architecture


#### 4.2.1. Organization Systems


InCleanHome organiza su contenido bajo los siguientes principios:

**Organización jerárquica (Visual Hierarchy):** La estructura del Landing Page sigue una jerarquía descendente de importancia: hero con propuesta de valor → beneficios clave (features) → buscador de servicios → testimonios → llamada a la acción. Esta secuencia guía al usuario desde el descubrimiento hasta la conversión de manera progresiva.

**Organización por audiencia (Audience-based):** El contenido está diferenciado según dos segmentos objetivo:
- *Familias y hogares* que buscan contratar personal doméstico verificado.
- *Trabajadores del hogar* que desean registrarse como proveedores de servicios.

El CTA principal ("Buscar ahora") dirige a familias al buscador. El CTA secundario ("Ser un/a limpiador/a") dirige a trabajadores al formulario de registro.

**Organización por categoría temática:** Los servicios se agrupan en cuatro categorías identificadas con tabs: Limpieza, Cocina, Jardín y Cuidados, permitiendo al usuario filtrar contenido según su necesidad específica.

**Organización secuencial:** El proceso de búsqueda sigue pasos claros: selección de ciudad → tipo de servicio → disponibilidad → calificación mínima → idioma → búsqueda. Esta secuencia reduce la carga cognitiva.

---

#### 4.2.2. Labeling Systems


Las etiquetas de InCleanHome siguen el principio de mínima cantidad de palabras con máxima claridad:

| Etiqueta               | Contexto de uso                         | Significado para el usuario                     |
|------------------------|-----------------------------------------|-------------------------------------------------|
| Cómo Funciona          | Navbar                                  | Proceso explicado paso a paso                   |
| Servicios              | Navbar                                  | Catálogo de tipos de servicios disponibles       |
| Nosotros               | Navbar                                  | Información sobre la empresa y el equipo         |
| Iniciar sesión         | Navbar (acción)                         | Acceso a cuenta existente                        |
| Ser un/a limpiador/a   | Navbar (CTA secundario)                 | Registro como proveedor de servicios             |
| Busca ahora            | Hero (CTA primario)                     | Acceso directo al formulario de búsqueda         |
| Antecedentes Verificados | Feature card                          | Validación de identidad del trabajador           |
| Pagos Digitales Seguros | Feature card                           | Sistema de cobro sin efectivo                    |
| Reservas Flexibles     | Feature card                            | Gestión de horarios sin restricciones            |
| Ubicación              | Filtro de búsqueda                      | Ciudad del usuario para resultados relevantes    |
| Calificación Min.      | Filtro de búsqueda                      | Umbral mínimo de estrellas del profesional       |
| Buscar profesionales   | Botón de búsqueda                       | Ejecutar la búsqueda con los filtros aplicados   |
| ✓ Verificada / ✓ Recurrente | Badge en reseñas                 | Credencial de confianza del reseñador            |

---

#### 4.2.3. SEO Tags and Meta Tags


**Title:** InCleanHome – Encuentra Personal Doméstico Confiable y Verificado

**Description:** Conecta con personal doméstico verificado para tu hogar. Reserva servicios de
limpieza, cocina, jardín y cuidados en minutos, con pagos digitales seguros y trabajadores con
antecedentes verificados.

**Keywords:** Personal doméstico, servicio de limpieza, limpieza del hogar, trabajadora doméstica
verificada, contratar limpiadora, servicio de cocina a domicilio, cuidado del hogar, reserva de
servicios domésticos, plataforma doméstica online

**Meta Tags:** - Viewport: width=device-width, initial-scale=1.0 - Charset: UTF-8 - Author:
InCleanHome Team - Robots: index, follow - Language: es-419, en-US


#### 4.2.4. Searching Systems

InCleanHome proporciona un sistema de búsqueda estructurado que guía al usuario mediante filtros predefinidos, evitando la búsqueda por texto libre que podría resultar en confusión o resultados irrelevantes.

**Búsqueda filtrada (sección Search del Landing Page):**

El formulario de búsqueda ofrece los siguientes filtros combinables:

| Filtro              | Tipo de control | Opciones disponibles                                          |
|---------------------|-----------------|---------------------------------------------------------------|
| Ubicación           | Select          | Selecciona tu ciudad / CDMX / Guadalajara / Monterrey / Lima / Bogotá |
| Tipo de Servicio    | Select          | Limpieza profunda / Limpieza regular / Limpieza de mudanza   |
| Disponibilidad      | Date picker     | Selección de fecha en calendario                              |
| Calificación Mínima | Select          | Todas / 4+ estrellas / 4.5+ estrellas                        |
| Idioma              | Select          | Inglés/Español / Solo Español / Solo Inglés                   |

Los resultados se presentan en menos de 30 segundos según la promesa de la plataforma. El botón de búsqueda incluye feedback visual (spinner animado) durante la carga.

**Categorías por tabs:** La sección de búsqueda incluye tabs para Limpieza, Cocina, Jardín y Cuidados, permitiendo categorización previa antes de aplicar filtros.

**Presentación de resultados:** Los profesionales encontrados se muestran con nombre, foto, calificación en estrellas, especialidad y disponibilidad, ordenados por relevancia y calificación.

---

#### 4.2.5. Navigation Systems


InCleanHome implementa los siguientes mecanismos de navegación:

**Navegación principal (Navbar sticky):** Accesible desde cualquier punto del scroll, incluye los enlaces Cómo Funciona, Servicios y Nosotros, además de las acciones Iniciar sesión y Ser un/a limpiador/a. En mobile se convierte en menú hamburger animado.

**Navegación por anclas (Smooth scroll):** Los CTAs del hero ("Busca ahora") y el enlace "Ver cómo funciona" utilizan scroll suave hacia secciones específicas de la página (`#search`), mejorando la orientación del usuario sin recargar la página.

**Navegación por tabs:** La sección de búsqueda implementa un sistema de tabs que filtra visualmente el tipo de servicio, con estado activo resaltado en azul marino sobre fondo oscuro.

**Navegación al footer:** El footer actúa como mapa de sitio secundario con agrupación en columnas: Plataforma (Cómo funciona, Servicios, Precios, Para trabajadores) y Soporte (Centro de ayuda, FAQ, Reportar problema, Estado del servicio).

**Llamadas a la acción (CTA) como navegación:** Los botones "Buscar ahora" del banner CTA y el hero guían al usuario hacia el formulario de búsqueda. "Registrarse como trabajador" dirige al flujo de onboarding de proveedores.

---

### 4.3. Landing Page UI Design


#### 4.3.1. Landing Page Wireframe
{<img src="./assets/capturas landing/wireframe1.png" alt="wireframe1" width="550"/>}
{<img src="./assets/capturas landing/wireframe2.png" alt="wireframe2" width="550"/>}
{<img src="./assets/capturas landing/wireframe3.png" alt="wireframe3" width="550"/>}
{<img src="./assets/capturas landing/wireframe4.png" alt="wireframe4" width="550"/>}

#### 4.3.2. Landing Page Mock-up
{<img src="./assets/capturas landing/mockup1.png" alt="mockup1" width="550"/>}
{<img src="./assets/capturas landing/mockup2.png" alt="mockup2" width="550"/>}
{<img src="./assets/capturas landing/mockup3.png" alt="mockup3" width="550"/>}
{<img src="./assets/capturas landing/mockup4.png" alt="mockup4" width="550"/>} 


### 4.4. Web Applications UX/UI Design

#### 4.4.1. Web Applications Wireframes
  <img src="./assets/web application/wireframes web application/waw1.jpg" alt="wireframes web application 1" width="400">
  <img src="./assets/web application/wireframes web application/waw2.jpg" alt="wireframes web application 2" width="400">
  <img src="./assets/web application/wireframes web application/waw3.jpg" alt="wireframes web application 3" width="400">
  <img src="./assets/web application/wireframes web application/waw4.jpg" alt="wireframes web application 4" width="400">
  <img src="./assets/web application/wireframes web application/waw5.jpg" alt="wireframes web application 5" width="400">
  <img src="./assets/web application/wireframes web application/waw6.jpg" alt="wireframes web application 6" width="400">
  <img src="./assets/web application/wireframes web application/waw7.jpg" alt="wireframes web application 7" width="400">
  <img src="./assets/web application/wireframes web application/waw8.jpg" alt="wireframes web application 8" width="400">
  <img src="./assets/web application/wireframes web application/waw9.jpg" alt="wireframes web application 9" width="400">

#### 4.4.2. Web Applications Wireflow Diagrams

##### inicio de sesión: 


##### recuperación de contraseña


##### registro de usuario


##### edición de datos personales

##### actualización de documentos


##### registro de objetos protegidos


##### solicitud de teleconsulta


##### historial de reclamos


##### prevenciones y recordatorios


##### reeclamos en curso


#### 4.4.3. Web Applications Mock-ups
  <img src="./assets/web application/mock ups web application/wam1.jpg" alt="mock ups web application 1" width="400">
  <img src="./assets/web application/mock ups web application/wam2.jpg" alt="mock ups web application 2" width="400">
  <img src="./assets/web application/mock ups web application/wam3.jpg" alt="mock ups web application 3" width="400">
  <img src="./assets/web application/mock ups web application/wam4.jpg" alt="mock ups web application 4" width="400">
  <img src="./assets/web application/mock ups web application/wam5.jpg" alt="mock ups web application 5" width="400">
  <img src="./assets/web application/mock ups web application/wam6.jpg" alt="mock ups web application 6" width="400">
  <img src="./assets/web application/mock ups web application/wam7.jpg" alt="mock ups web application 7" width="400">
  <img src="./assets/web application/mock ups web application/wam8.jpg" alt="mock ups web application 8" width="400">
  <img src="./assets/web application/mock ups web application/wam9.jpg" alt="mock ups web application 9" width="400">



#### 4.4.4. Web Applications User Flow Diagrams


##### inicio de sesión: 


##### registro de usuario:


##### recuperación de contraseña


##### edición de datos personales


##### actualización de documentos
-

##### registro de objetos protegidos
-

##### solicitud de teleconsulta
-

##### historial de reclamos
-

##### prevenciones y recordatorios
-

##### reeclamos en curso
-
### 4.5. Web Applications Prototyping
-
### 4.6. Domain-Driven Software Architecture

#### 4.6.1. Software Architecture Context Diagrams

<img src="./assets/C4Diagram/Context_Diagram.png" alt="Context_Diagram" width="550"/>


#### 4.6.2. Software Architecture Container Diagrams

<img src="./assets/C4Diagram/Container_Diagram.png" alt="Container_Diagram" width="550"/>


#### 4.6.3. Software Architecture Components Diagrams

<img src="./assets/C4Diagram/Componets_Diagram.png" alt="Componets_Diagram" width="550"/>

#### 4.7.1. Class Diagram


<img src="assets/class-diagram/class-diagram.png" alt="class diagram" width="570px"/>




### 4.8. Database Design

#### 4.8.1. Database Diagram

<img src="./assets/C4Diagram/Digrama.png" alt="Diagrama" width="550"/>

## Capítulo V: Product Implementation, Validation & Deployment

### 5.1. Software Configuration Management

 En esta sección, el equipo establece las decisiones y convenciones para mantener la consistencia durante el ciclo de vida del desarrollo del software. Estos procesos son cruciales para asegurar el uso adecuado de herramientas, el despliegue correcto y la aplicación de buenas prácticas en la codificación.

---

#### 5.1.1. Software Development Environment Configuration
 En esta sección se presentan las distintas herramientas utilizadas por el equipo para el desarrollo del proyecto **InCleanHome**.

##### UX/UI Design
- **UXPressia**: Utilizada para la creación de *User Persona*, *Empathy Maps*, *Journey Maps* e *Impact Maps*, permitiendo una mejor comprensión del usuario objetivo.
- **Figma**: Herramienta de diseño empleada para la creación de *wireframes* y *mockups* del sistema.
- **Miro**: Utilizada para la elaboración de *As-Is* y *To-Be Scenario Maps*, facilitando la planificación visual.

##### Software Development
- **Visual Studio Code**: Entorno de desarrollo para la implementación de la landing page usando HTML5, CSS, JavaScript y Vue.
- **Rider**: IDE utilizado para el desarrollo en C# con la plataforma .NET, especialmente para la creación de Web Services con ASP.NET.
- **GitHub**: Plataforma de alojamiento de repositorios para la gestión del código fuente.
- **Git**: Sistema de control de versiones para el seguimiento de cambios y trabajo colaborativo.

#####  Project Management & Collaboration
- **Lucidchart**: Herramienta para la creación de diagramas UML, *wireflows* y *user flows*.
- **Structurizr**: Utilizada para modelar la arquitectura mediante diagramas C4 (contexto, contenedores y componentes).

#####  Software Testing & Documentation
- **Markdown**: Lenguaje de marcado ligero utilizado para documentar el proyecto dentro del repositorio.

---
#### 5.1.2. Source Code Management
-La gestión del código fuente es fundamental en el desarrollo del proyecto, ya que permite registrar cambios, colaborar en equipo y recuperar versiones anteriores del código.

En **InCleanHome**, se utiliza:
- **Git** como sistema de control de versiones.
- **GitHub** como plataforma para alojar los repositorios.

#####  URL de los repositorios
- **Organización**: *https://github.com/upc-pre-1asi0730-12263-InCleanHome*
- **Project Report**: *https://github.com/upc-pre-1asi0730-12263-InCleanHome/incleanhome-report*
- **Landing Page**: *https://upc-pre-1asi0730-12263-incleanhome.github.io/InCleanHome-website/*

---

#### 5.1.3. Source Code Style Guide & Conventions
-Para el desarrollo del proyecto se establecieron normas que aseguran un código consistente, mantenible y fácil de entender. Estas convenciones se aplican en:

- **Landing Page**: HTML, CSS y JavaScript
- **Web Applications**: Vue + JavaScript
- **RESTful Web Services**: ASP.NET Core + C#

Algunas prácticas incluyen:
- Uso de nombres descriptivos para variables y funciones.
- Indentación consistente.
- Separación clara de responsabilidades (frontend/backend).
- Uso de comentarios cuando sea necesario.
- Aplicación de buenas prácticas según cada tecnología.

---
#### 5.1.4. Software Deployment Configuration
- En esta seccion se detalla la configuración necesaria para el despliegue de nuestra solución, incluyendo los pasos clave para lograr su publicación satisfactoria de la landing page, servicios web y aplicaiones frontend usando GitHub para poder verificar cada commit de la landing page.

Explicaremos los pasos para poder desplegar nuestra landing page.

- Verificamos que todas las ramas estan actualizadas.
- Dentro de la seccion settings buscamos la opcion pages, aqui podremos configurar el despliegue de la pagina desde una rama especifica del repositorio.
- Configuramos la rama o elegimos la rama principal (main o master), luego guardamos para iniciar el proceso de despliegue.
- Finalmente se podrá acceder a la pagina mediante el enlace que GitHub nos otorgará.



### 5.2. Landing Page, Services & Applications Implementation
En esta sección se describe el proceso de implementación del producto **InCleanHome**, considerando el avance correspondiente a la primera entrega del proyecto (AV1), enfocado principalmente en la construcción de la Landing Page y la documentación inicial.

---
#### 5.2.1. Sprint 1
El Sprint 1 estuvo orientado al desarrollo de la **Landing Page** y la consolidación de los artefactos de análisis y diseño del proyecto.

---
##### 5.2.1.1. Sprint Planning 1
**Sprint Goal:**
Desarrollar una Landing Page funcional que comunique la propuesta de valor del producto InCleanHome y refleje el diseño definido en los mockups.

**Duración del Sprint:**
2 semanas

**Alcance del Sprint:**
- Implementación de la Landing Page
- Estructura base del proyecto frontend
- Integración del diseño UX/UI previamente definido

**User Stories seleccionadas:**
- US01: Como visitante, deseo conocer el servicio para entender su propuesta de valor.
- US02: Como visitante, deseo navegar entre secciones para explorar el contenido.
- US03: Como visitante, deseo ver información clara y organizada para generar confianza.

| Sprint # | Sprint 1 |
| :--- | :--- |
| **Sprint Planning Background** | Desarrollo de la Landing Page y consolidación de artefactos de análisis y diseño. |
| **Date** | 2026-04-23 |
| **Time** | 16:00 |
| **Location** | Server Report |
| **Prepared by** | Team Leader |
| **Attendees** | All members |
| **Sprint Review Summary** | Se implementó con éxito la estructura base del frontend, el diseño responsive y la propuesta de valor, cumpliendo con las 4 User Stories priorizadas. |
| **Sprint Goal** | Desarrollar una Landing Page funcional que comunique la propuesta de valor del producto InCleanHome y refleje el diseño definido en los mockups. |
| **Sprint Velocity** | 100% |
| **Sum of Story Points** | 4 US (US-L07, US-L08, US-L09, US-L10) |


---
##### 5.2.1.2. Aspect Leaders and Collaborators

| Team Member | GitHub Username | Landing Page leader(L) collaborator(C)  |
| :--- | :--- | :--- |
| Garcia Cerpa, Braden Raid | BradenGarcia | C |
| Espino Rossi, Victor Manuel | Vmer140 | C |
| Vara Velasquez, Oscar Fernando | Varometro159 | C |
| Choy Robles, Vanessa May Lang | VMLCR | C |
| Valverde Portuguez, Natalia Ximena | NatValverde15 | L |

**Nota:**  
Debido al alcance del primer avance, todos los integrantes participaron en conjunto en las actividades de desarrollo y documentación.

---



##### 5.2.1.3. Sprint Backlog 1

El Sprint Backlog se definió a partir de las User Stories priorizadas en el Product Backlog.  
Cada historia fue descompuesta en tareas técnicas para facilitar su implementación y asignación dentro del equipo.

| US ID | User Story / Tareas Técnicas | Responsable | Estado |
| :--- | :--- | :--- | :--- |
| **US-L08** | **Visualización de propuesta de valor** | **Equipo** | **Completado** |
| | Diseñar sección "Features" en base a mockups | Equipo | Hecho |
| | Implementar estructura HTML | Equipo | Hecho |
| | Aplicar estilos CSS | Equipo | Hecho |
| | Ajustar diseño responsive | Equipo | Hecho |
| **US-L09** | **Consumo de testimonios** | **Equipo** | **Completado** |
| | Diseñar sección de testimonios | Equipo | Hecho |
| | Implementar cards de testimonios | Equipo | Hecho |
| | Aplicar estilos visuales | Equipo | Hecho |
| **US-L07** | **Suscripción a Newsletter** | **Equipo** | **Completado** |
| | Implementar input de correo en footer | Equipo | Hecho |
| | Validar formato de email (frontend) | Equipo | Hecho |
| | Diseñar sección footer | Equipo | Hecho |
| **US-L10** | **Adaptabilidad móvil** | **Equipo** | **Completado** |
| | Implementar menú hamburguesa | Equipo | Hecho |
| | Configurar estilos responsive | Equipo | Hecho |
| | Probar visualización en móviles | Equipo | Hecho |
---

###  Desglose por User Stories

#### US-L08: Visualización de propuesta de valor
| Tarea | Responsable |
|------|------------|
| Diseñar sección "Features" en base a mockups | Equipo |
| Implementar estructura HTML | Equipo |
| Aplicar estilos CSS | Equipo |
| Ajustar diseño responsive | Equipo |

---

####  US-L09: Consumo de testimonios
| Tarea | Responsable |
|------|------------|
| Diseñar sección de testimonios | Equipo |
| Implementar cards de testimonios | Equipo |
| Aplicar estilos visuales | Equipo |

---

####  US-L07: Suscripción a Newsletter
| Tarea | Responsable |
|------|------------|
| Implementar input de correo en footer | Equipo |
| Validar formato de email (frontend) | Equipo |
| Diseñar sección footer | Equipo |

---

####  US-L10: Adaptabilidad móvil
| Tarea | Responsable |
|------|------------|
| Implementar menú hamburguesa | Equipo |
| Configurar estilos responsive | Equipo |
| Probar visualización en móviles | Equipo |

---

###  Resumen del Sprint Backlog

| ID | User Story | Estado |
|----|-----------|--------|
| US-L07 | Newsletter | Completado |
| US-L08 | Propuesta de valor | Completado |
| US-L09 | Testimonios | Completado |
| US-L10 | Adaptabilidad móvil | Completado |

---

##### 5.2.1.4. Development Evidence for Sprint Review

Durante el Sprint 1 se desarrolló la Landing Page basada en los diseños definidos previamente.

**Incluye:**
- Estructura HTML de la página
- Estilos CSS para el diseño visual
- Componentes básicos de la interfaz
- Capturas de código
<img src="./assets/capturas landing/HTML.jpeg" alt="HTML" width="550"/>
<img src="./assets/capturas landing/CSS.jpeg" alt="CSS" width="550"/>
<img src="./assets/capturas landing/JS.jpeg" alt="JS" width="550"/>
- Link al repositorio GitHub: https://github.com/upc-pre-1asi0730-12263-InCleanHome 
- Historial de commits
<img src="./assets/Commits/Vara.png" alt="Vara" width="550"/>
<img src="./assets/Commits/Espino.png" alt="Espino" width="550"/>
<img src="./assets/Commits/Garcia.png" alt="Garcia" width="550"/>
<img src="./assets/Commits/Choy.png" alt="Choy" width="550"/>

---
##### 5.2.1.5. Execution Evidence for Sprint Review

Se realizaron pruebas básicas de ejecución en navegador para validar el funcionamiento de la Landing Page.

**Validaciones realizadas:**
- Correcta visualización de secciones
- Navegación fluida
- Diseño responsive 


- Screenshots de la página en ejecución
<img src="./assets/capturas landing/mockup1.png" alt="mockup1" width="550"/>
<img src="./assets/capturas landing/mockup2.png" alt="mockup2" width="550"/>
<img src="./assets/capturas landing/mockup3.png" alt="mockup3" width="550"/>


---
##### 5.2.1.6. Services Documentation Evidence for Sprint Review

En este sprint **no se implementaron servicios backend**, ya que el enfoque estuvo en la Landing Page.

Sin embargo, se definieron de manera preliminar:
- Posibles endpoints del sistema
- Estructura futura de los servicios REST

Esto servirá como base para los siguientes sprints.

---

##### 5.2.1.7. Software Deployment Evidence for Sprint Review

Se realizó una ejecución local de la Landing Page para validación.

**Estado:**
- Aplicación funcional en entorno local

- Link de despliegue: 

---
##### 5.2.1.8. Team Collaboration Insights during Sprint

Durante el Sprint 1, el equipo trabajó de forma colaborativa en el desarrollo de la Landing Page y la documentación del proyecto.

**Aspectos positivos:**
- Trabajo conjunto en el desarrollo frontend
- Organización para completar la documentación requerida
- Uso de GitHub para control de versiones

**Aspectos a mejorar:**
- Mejor distribución de tareas
- Mayor planificación del tiempo
- Incrementar la frecuencia de commits

**Conclusión:**
El equipo logró cumplir con los objetivos del Sprint 1, estableciendo una base sólida del proyecto mediante la implementación de la Landing Page y la documentación necesaria para el avance.

## 6. Conclusiones y Recomendaciones
#### Conclusiones
- A diferencia de nuestros competidores en el mercado, nuestro proyecto, InCleanHome, se posiciona más con un enfoque de personalización profunda y un sistema de verificación de antecedentes y seguros contra daños, lo cual responde directamente a las necesidades de los segmentos objetivos de nuestro proyecto, que son las trabajadoras del hogar y los clientes que buscan servicios domésticos.

- La definición de requisitos funcionales, no funcionales y las historias de usuarios indican que el proyecto tiene viabilidad técnica y operativa, está listo para una transición continua hacia las fases de diseño de arquitectura y desarrollo que se implemente en el siguiente avance.

- InCleanHome enfrenta una problemática real que sucede en Lima Metropolitana, que es la informalidad que supera el 95% en el sector de servicios domésticos y la inseguridad en cuanto a la contratación de aquellos mismos. El análisis profundo e investigación que se realizó en este proyecto demuestra que sí existe una disposición en los clientes que necesitan servicios domésticos y las trabajadoras del hogar adoptar esta solución digital que actúa como una plataforma de confianza para resolver sus necesidades.

#### Recomendaciones

- Optimización de Logística por Geolocalización: Debido a que las trabajadoras encuentran dificultades cuando las ofertas son lejos de su hogar , se recomienda priorizar en el algoritmo de búsqueda los emparejamientos por cercanía geográfica para reducir costos y tiempos de traslado.


- Incentivar el Sistema de Reputación: Para mitigar la dependencia del "boca a boca" tradicional , se debe motivar a los usuarios a dejar reseñas detalladas mediante beneficios en la plataforma, ayudando a trabajadoras a construir una marca personal digital sólida.

- Proporcionar un turorial de uso de la plataforma: Dado que el 100% de los segmentos utiliza métodos informales y busca simplicidad , se recomienda incluir tutoriales interactivos dentro de la aplicación para que las trabajadoras del hogar gestionen su perfil y calendario sin barreras tecnológicas.


## 7. Bibliografía

- Congreso de la República del Perú. (2020). Ley N.º 31047, Ley de las Trabajadoras y Trabajadores del Hogar. Diario Oficial El Peruano.

- Instituto Nacional de Estadística e Informática [INEI]. (2026). Encuesta Nacional de Hogares (ENAHO): Informe sobre el empleo y la situación laboral en Lima Metropolitana. Lima, Perú.

- Ministerio de Trabajo y Promoción del Empleo [MTPE]. (2026). Reporte sobre la informalidad en el sector del trabajo doméstico remunerado en el Perú. Lima, Perú.

## 8. Anexos
