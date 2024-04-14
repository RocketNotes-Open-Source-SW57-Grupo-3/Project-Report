# **Capítulo V: Product Implementation, Validation & Deployment**

## **5.1. Software Configuration Management.** 

### 5.1.1. Software Development Environment Configuration. 

A continuación, presentaremos los programas de software que hemos utilizado en el desarrollo de nuestro proyecto.

**Project Management**

- **Whatsapp:** <https://web.whatsapp.com/>

  Se utilizó la plataforma de WhatsApp para organizar las tareas del equipo y proporcionar apoyo mutuo durante el trabajo.

**Product UX/UI Design**

- **Miro:** <https://miro.com/es/>

  Empleamos Miro para desarrollar el Lean UX Canvas.

- **Uxpressia:** <https://uxpressia.com/>

  Utilizamos Uxpressia para crear User Personas, Empathy maps y Journey maps.

- **Figma: <https://www.figma.com>**

  Figma fue nuestra herramienta principal para diseñar wireframes, wireflows, mockups del landing page y para la creación de prototipos de aplicaciones web.

- **LucidChart:** <https://www.lucidchart.com/pages/>

  Para crear los Impact maps

**Software Development**




- **Landing Page:** Para la creación de nuestra página de inicio, hemos empleado HTML5, CSS y Javascript.

**Software Testing**

Hemos realizado pruebas de software en el landing page y la aplicación web utilizando las herramientas de desarrollo de los navegadores web como Google Chrome y Brave.

**IDE's de desarrollo**

- **Webstorm: <https://www.jetbrains.com/webstorm/>**

  Utilizamos Webstorm, un IDE centrado en el desarrollo frontend, por su variedad de herramientas que agilizan el proceso de desarrollo.

**Software Deployment**

- **Github Pages:** <https://pages.github.com/>

  Utilizamos Github Pages para desplegar nuestro landing page, vinculando el repositorio de GitHub para que se encargue automáticamente del despliegue.

**Software Documentation**

- **Google Docs: <https://docs.google.com/document/u/0/>**

  Esta plataforma fue utilizada para enviar el progreso de las tareas asignadas. Semanalmente se enviaban las asignaciones de cada integrante para el informe final.




- **Github: <https://github.com/>**

  Utilizamos GitHub para la documentación del proyecto y el landing page, aprovechando su capacidad de desarrollo colaborativo y su registro de commits para demostrar la contribución de cada miembro.




- **Visual Paradigm:** Utilizamos Visual Paradigm para crear diagramas C4 de nuestro proyecto.




- **Vertabelo:** <https://vertabelo.com/>

  Vertabelo fue utilizado para diseñar la estructura de nuestra base de datos, siendo una aplicación web colaborativa.

### **5.1.2. Source Code Management**

La administración y estructuración de las múltiples modificaciones se realizaron mediante la creación de un repositorio en GitHub para el proyecto. Nuestra organización se estructuró de la siguiente manera:

**Organización:**

<https://github.com/RocketNotes-Open-Source-SW57-Grupo-3>

**LandinPage:**

<https://rocketnotes-open-source-sw57-grupo-3.github.io/RocketNotes-Landing-page/>

**Ramas principales:**

**Rama “main”:** En esta rama se almacenan las versiones oficiales de nuestro repositorio para pasarlas a producción. Rama “develop”: Esta rama se utilizará como punto de integración para las ramas de “feature”. Una vez que el  “head” sea estable y el equipo lo considere listo para el lanzamiento, se fusionará con la rama “release”.

**Ramas auxiliares:**

- **Rama “release”:** La rama “release” se emplea para la preparación del lanzamiento de una nueva versión en la rama “main” ayudando a controlar las versiones de código. Aquí se pueden solucionar errores menores y preparar los datos para la versión. Esta rama permitirá liberar a la rama “develop” de est as tareas preparatorias y evita demoras en el desarrollo mientras se prepara para el lanzamiento. 
- **Rama “feature”:** En las ramas “feature” se desarrollan las características generales que se integrarán en la rama “develop”. Estas características son aquellas funcionalidades solicitadas por los usuarios tanto en la página de inicio como en la aplicación web. Por ejemplo, la rama feature/navbar.
- **Rama “hotfix”:** Esta rama se utiliza para corregir urgentemente errores en la última versión de la rama “main” que no pueden esperar hasta el próximo lanzamiento para ser solucionados.

### **5.1.3. Source Code Style Guide & Conventions**

- Utilizaremos el lenguaje de etiquetas HTML para el desarrollo principal de nuestra Landing page.
- Utilizaremos el lenguaje CSS, que nos permitirá realizar los estilos de la estructura de nuestra Landing Page
- Implementaremos el lenguaje de JavaScript para brindar las funcionalidades a nuestra Landing page. 
- Utilizaremos el lenguaje Gherkin que se usará para realizar los diseños de prueba de cada historia de usuario contando con su estructura básica. 

### **5.1.4. Software Deployment Configuration.**

**Markdown:**

Creamos un repositorio en la organización de nuestro grupo en GitHub y subimos los

archivos necesarios para que el servidor pueda mostrar la landing page. Utilizamos

Github Pages para el despliegue.

1. Cargamos los archivos necesarios para subirlo al repositorio. 

![](Aspose.Words.2abd0e8b-f3ab-4e86-82f8-3ed74940eaf3.001.png)

2. Posteriormente nos dirigimos a settings y ubicamos el apartado, Pages. En Branch seleccionamos la rama main y posteriormente, guardar. 

![](Aspose.Words.2abd0e8b-f3ab-4e86-82f8-3ed74940eaf3.002.png)

3. Luego de cierto tiempo, github nos envía el enlace de nuestra página. 

![](Aspose.Words.2abd0e8b-f3ab-4e86-82f8-3ed74940eaf3.003.png)

## **5.2. Landing Page, Services & Applications Implementation.**

### **5.2.1. Sprint**

#### **5.2.1.1. Sprint Planning 1**

A continuación, se mostrará el primer sprint planning, en el cual se exhibirán las pruebas de planificación e implementación del landing page. Además, de los progresos del proyecto y los insights sobre la colaboración del equipo utilizando Github.

|Sprint #|Sprint 1|
| :- | :- |
|Sprint Planning Background||
|Date|12 de abril del 2023|
|Time|11:55 horas (GMT -5)|
|Location|Modalidad remota por Whatssap|
|Prepared By|FiveStars|
|Attendees (to planning meeting)|Todos los miembros del grupo FiveStars|
|Sprint n – 1 Review Summary|Dado que se trata del primer sprint, no hay un review summary de un sprint anterior.|
|Sprint n – 1 Retrospective Summary|Dado que se trata del primer sprint, no hay un retrospective summary de un sprint anterior.|
|Sprint Goal & User Stories||
|Sprint 1 Goal|<p>En el presente sprint, nuestro objetivo es desarrollar nuestro landing page. Por ello, se discutió el contenido textual y el diseño previamente elaborado en Figma para el landing. Al concluir este sprint, se espera que la página esté publicada en Github Pages, permitiendo que cualquier usuario pueda visitarla mediante el enlace proporcionado.</p><p></p>|
|Sprint 1 Velocity|4|
|Sum of Story Points|4|

#### **5.2.1.2. Sprint Backlog 1**

En esta sección se presentan los tasks realizados durante el actual Sprint.

![](Aspose.Words.2abd0e8b-f3ab-4e86-82f8-3ed74940eaf3.004.png)

**Trello: [Product Backlog | Trello**](https://trello.com/b/fHKD9Uys/product-backlog)**

<table><tr><th colspan="2" valign="top">Sprint #</th><th colspan="6" valign="top">Sprint 1</th></tr>
<tr><td colspan="2" valign="top">User story</td><td colspan="6" valign="top">Work Item / Task</td></tr>
<tr><td valign="top">Id </td><td valign="top">Title </td><td valign="top">Id </td><td valign="top">Title </td><td valign="top">Description </td><td valign="top">Estimation (Hours)</td><td valign="top">Assigned To</td><td valign="top">Status (To-do InProcess ToReview Done)</td></tr>
<tr><td rowspan="6" valign="top">E5-US20</td><td rowspan="6" valign="top">Características del Producto</td><td>T1</td><td valign="top">Hacer el navbar</td><td rowspan="6">1h</td><td rowspan="6">Abraham</td><td rowspan="6">HECHO</td><td valign="top"></td></tr>
<tr><td>T2</td><td valign="top">Hacer el navbar responsive</td><td valign="top"></td></tr>
<tr><td>T3</td><td valign="top">Hacer el Home</td><td valign="top"></td></tr>
<tr><td>T4</td><td valign="top">Hacer el Home</td><td valign="top"></td></tr>
<tr><td>T5</td><td valign="top">Hacer el article de características del producto</td><td valign="top"></td></tr>
<tr><td>T6</td><td valign="top">Hacer el article de características del producto responsive</td><td valign="top"></td></tr>
<tr><td rowspan="2" valign="top">E5-US21</td><td rowspan="2" valign="top">Confirmación de la Confiabilidad a través de Reseñas</td><td rowspan="2">T7</td><td valign="top">Hacer el article de reviews</td><td rowspan="2">0\.2h</td><td rowspan="2">Belén</td><td rowspan="2">HECHO</td><td valign="top"></td></tr>
<tr><td valign="top">Hacer el article de reviews responsive</td><td valign="top"></td></tr>
<tr><td rowspan="2" valign="top">E5-US22</td><td rowspan="2" valign="top">Evaluación de Planes y Precios</td><td>T8</td><td valign="top">Hacer el article de pricing</td><td rowspan="2">0\.3h</td><td rowspan="2">Nelson</td><td rowspan="2">HECHO</td><td valign="top"></td></tr>
<tr><td>T9</td><td valign="top">Hacer el article de pricing responsive</td><td valign="top"></td></tr>
<tr><td rowspan="2" valign="top">E5-US23</td><td rowspan="2" valign="top">Facilidad de Contacto con la Empresa</td><td>T10</td><td valign="top">Hacer el article de contact</td><td rowspan="2">0\.3h</td><td rowspan="2">Mateo</td><td rowspan="2">HECHO</td><td valign="top"></td></tr>
<tr><td>T11</td><td valign="top">Hacer el article de contact responsive</td><td valign="top"></td></tr>
<tr><td valign="top">E5-US24</td><td valign="top">Navegación Intuitiva en la Landing Page</td><td>T12</td><td valign="top">Optimización de elementos UI de la landing page</td><td>0\.5h</td><td rowspan="2">Frida</td><td>HECHO</td><td valign="top"></td></tr>
<tr><td valign="top">E5-US25</td><td valign="top">Selección de Idioma en la Landing Page</td><td>T13</td><td valign="top">` `Cambiar algunos detalles de la web de español a ingles</td><td>0\.4h</td><td>HECHO</td><td valign="top"></td></tr>
</table>





#### **5.2.1.3. Development Evidence for Sprint Review.**



<table><tr><th valign="top">Repository</th><th valign="top">Branch</th><th valign="top">Commit Id </th><th valign="top">Commit Message</th><th valign="top">Commit Message Body</th><th valign="top">Committed on (Date)</th></tr>
<tr><td rowspan="8" valign="top">RocketNotes-Landing-page</td><td rowspan="8" valign="top">Main</td><td valign="top">01f7dd71c6e502def67d2d06307ce983f8f66f96</td><td valign="top">Initial commit</td><td valign="top"></td><td valign="top">03/04/2024</td></tr>
<tr><td valign="top">137b258a5b503a9852d504989259caded17193c8</td><td valign="top">Added images for landing page</td><td valign="top"></td><td valign="top">03/04/2024</td></tr>
<tr><td valign="top">7cb8081a93639e0f115f37dad8962843884d5be5</td><td valign="top">Added logo for landing page</td><td valign="top"></td><td valign="top">03/04/2024</td></tr>
<tr><td valign="top">bceec27e93267b3572aebab8a4428fae3acb6828</td><td valign="top">Added landing page index.html structure</td><td valign="top"></td><td valign="top">03/04/2024</td></tr>
<tr><td valign="top">297e80a10014e7f4e327e893047884102c71dd76</td><td valign="top">Added landing page styles.css</td><td valign="top"></td><td valign="top">03/04/2024</td></tr>
<tr><td valign="top">38f7596295848c750b7e2c990433855280fbe13b</td><td valign="top">Added landing page main.js</td><td valign="top"></td><td valign="top">03/04/2024</td></tr>
<tr><td valign="top">2f8d6526777f29392583d16185770172e55cfa3b</td><td valign="top">update</td><td valign="top"></td><td valign="top">03/04/2024</td></tr>
<tr><td valign="top">64ddec6293d5839ad0f0416a7d1ee1cf9f7dd21f</td><td valign="top">update index.html</td><td valign="top"></td><td valign="top">03/04/2024</td></tr>
</table>



#### ***5.2.1.4. Testing Suite Evidence for Sprint Review.**

**Directo en markdown:**

Durante este sprint, se han integrado las pruebas de aceptación utilizando Gherkin. El repositorio que contiene estas pruebas están en el siguiente enlace: [https://github.com/RocketNotes-Open-Source-SW57-Grupo-3/RocketNotes-acceptance-tests](*https://github.com/RocketNotes-Open-Source-SW57-Grupo-3/RocketNotes-acceptance-tests*)

<table><tr><th valign="top">Repository</th><th valign="top">Branch</th><th valign="top">Commit Id</th><th valign="top">Commit Message</th><th valign="top">Commited on (Date)</th></tr>

<tr><td rowspan="7" valign="top">RocketNotes-acceptance-tests</td><td rowspan="7" valign="top">main</td><td valign="top">16fb4e50d6382ae6fc3d88de54610f7861915566</td><td valign="top">initial commit</td><td valign="top">14/04/2024</td></tr>

<tr><td valign="top">637809787379bd475704c9e4b2a22c71b967b8b8</td><td valign="top">feat: epic 1 added</td><td valign="top">14/04/2024</td></tr>

<tr><td valign="top">3a4e17f1c60d865e91e90b59409299c2f35a3354</td><td valign="top">feat: epic 2 added</td><td valign="top">14/04/2024</td></tr>

<tr><td valign="top">56888135b0d151a386f8709b38fea7039337baea</td><td valign="top">feat: epic 3 added</td><td valign="top">14/04/2024</td></tr>

<tr><td valign="top">89e55ba1d13bd793a55b16e7c5780ddb5f59c446</td><td valign="top">feat: epic 4 added</td><td valign="top">14/04/2024</td></tr>

<tr><td valign="top">02af9c233f465590e1aac985b58a6f5b410b1dfb</td><td valign="top">feat: epic 5 added</td><td valign="top">14/04/2024</td></tr>

</table>

#### **5.2.1.5. Execution Evidence for Sprint Review.**

A continuación se mostrarán capturas de evidencia de lo logrado para el primer sprint, que fue crear y desplegar la landing page con las secciones más importantes.

Primero el banner de presentación de nuestro servicio, diseñado en inglés y completamente responsive. 

![](Aspose.Words.2abd0e8b-f3ab-4e86-82f8-3ed74940eaf3.005.png)![](Aspose.Words.2abd0e8b-f3ab-4e86-82f8-3ed74940eaf3.006.png)

Luego la sección donde mostramos características de producto y algunas funciones.

![](Aspose.Words.2abd0e8b-f3ab-4e86-82f8-3ed74940eaf3.007.png)

Una sección de comentarios de clientes. Esto ayudará a generar confianza en los nuevos usuarios.

![](Aspose.Words.2abd0e8b-f3ab-4e86-82f8-3ed74940eaf3.008.png)

Luego tenemos el apartado de precios, con grandes botones llamativos e información concisa de los beneficios de cada plan.

![](Aspose.Words.2abd0e8b-f3ab-4e86-82f8-3ed74940eaf3.009.png)

Por último, la sección de contacto con nuestra empresa. Con información concisa e intuitiva para el usuario.

![](Aspose.Words.2abd0e8b-f3ab-4e86-82f8-3ed74940eaf3.010.png)

#### **5.2.1.6. Services Documentation Evidence for Sprint Review.**

Para la elaboración del sprint 1, se ha desarrollado únicamente el landing page, por lo cual no se emplea el desarrollo de web services o web applications.

#### **5.2.1.7. Software Deployment Evidence for Sprint Review.**

En el primer sprint, se completó la creación del landing page. Para llevar a cabo el despliegue de este landing page, se emplearon las siguientes herramientas:

- **Git:** Un sistema de control de versiones que simplificó el trabajo de realizar la landing page.
- **Git Flow:** Un flujo de trabajo que apoyó en la coordinación de cada integrante del equipo en el desarrollo del landing page.
- **GitHub:** Plataforma para la colaboración en equipo y así almacenar las versiones actualizadas.
- **Github Pages:** Plataforma que nos permitió alojar y desplegar nuestro landing page.

#### **5.2.1.8. Team Collaboration Insights during Sprint.**

Durante este sprint para proteger la rama “main” creamos una rama “develop” de la que cada integrante de nuestro grupo creó su propia sub-rama “feature“ para subir un capítulo del reporte siguiendo las convenciones antes señaladas(conventional commit y git flow).




Conclusiones

- Realizar un producto de esta magnitud significó un desafío para todo el equipo debido a la alta competitividad en otros sectores. Sin embargo, logramos hacer un producto destacable e interesante en la industria. Gracias a la landing page que captará la atención de gente interesada en ver nuestro producto, hay altas posibilidades de contactarnos para trabajar en equipo y así aumentar nuestra visibilidad en la industria. Por supuesto para ello se investigó y analizó la competencia más destacable para nosotros y así ofrecer funciones interesantes o cuanto menos, prácticas para lograr destacarse y hacer un negocio rentable.




- A lo largo de este proceso, hemos empleado técnicas avanzadas de mapeo de experiencia del usuario como son el As-is y To-be Scenario Mappings, así como User Journey Mapping, para profundizar en las necesidades y desafíos enfrentados por nuestros usuarios ideales. Estas herramientas han sido fundamentales para identificar y abordar puntos críticos, facilitando la iteración y mejora continua de plataformas de gestión escolar. Permitiéndonos diseñar soluciones más efectivas y centradas en el usuario, mejorando significativamente la interacción con las herramientas digitales en el ámbito educativo.




- Para concluir, este proyecto de "RocketNotes" ha demostrado ser una amalgama de innovación, colaboración y compromiso, resultando en una herramienta significativamente transformadora para la gestión educativa. La aplicación no solo aborda los desafíos contemporáneos de las instituciones educativas mediante la automatización y optimización de procesos, sino que también empodera a profesores y administradores al simplificar las tareas administrativas y académicas. La validación a través de pruebas de usabilidad ha confirmado la eficacia de la interfaz y la experiencia del usuario, reflejando una mejora notable en la eficiencia y satisfacción de los usuarios finales. Este proyecto no solo ha cumplido con las expectativas establecidas, sino que ha sentado un precedente sobre cómo la tecnología aplicada inteligentemente puede revolucionar el entorno educativo, anticipando una adopción más amplia en futuras aplicaciones educativas.







**Bibliografía**

Smith, J., & Doe, J. "Enhancing Efficiency in Education through Learning Management Systems: A Case Study of the Blackboard System." Educational Technology Research and Development, vol. 65, no. 4, 2017, pp. 1023-1039. 

**Anexos**

C4model: <http://c4model.com>

LINK FIGMA: <https://www.figma.com/file/pBcefWno0VR16AEy7elc2m/Open-Source?type=design&node-id=0%3A1&mode=design&t=BmgtN82Ieketfpvn-1>

LINK LANDING PAGE:
<https://rocketnotes-open-source-sw57-grupo-3.github.io/RocketNotes-Landing-page/>

LINK TRELLO:

<https://trello.com/b/fHKD9Uys/product-backlog>

LINK LEAN UX CANVAS: <https://miro.com/welcomeonboard/NEdsWTNwa0FKdWVGUmlFUEJ6R3dldkpBRHNxRmNIeEdhNWVDNHhoRnBlZENuSElYbm1hN3JjNFNwOUJpdUIzWHwzNDU4NzY0NTIzMzkyNDUwNjk1fDI=?share_link_id=776423401253>

