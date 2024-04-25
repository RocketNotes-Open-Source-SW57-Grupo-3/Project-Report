### **Capítulo IV: Product Design** 

## **4.1. Style Guidelines**

### **4.1.1. General Style Guidelines.**

**Branding:**

Nuestra aplicación está destinada al personal administrativo y profesores de instituciones educativas de educación básica, por ello el branding de nuestra marca busca transmitir seriedad y serenidad. Adicionalmente, como nos enfocamos en brindar soporte a los procesos de gestión del bienestar de estudiantes e infraestructura escolar, necesitamos que la aplicación no cuente con elementos distractores, por ello el diseño debe de ser lo más simple e intuitivo posible.

**Logo:**

Lo primero que definimos fue el logo de nuestra marca, ya que este representa nuestra identidad. El logo usa la fuente Roboto y los colores gris oscuro (#595959) y verde (#1EC089). El tamaño del logo dependerá de la pantalla en la que se muestre, ya que si se muestra en una computadora será más grande que si se muestra en un celular.

- Fuente: Roboto.

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.001.png)

Color palette:![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.002.png)

**Typography:**

1. Heading one: Roboto - 64px
1. Heading two: Roboto - 40px
1. Heading three: Roboto - 36px
1. Body: Roboto -20px
1. Body: Roboto - 14px

**Global Color Palette:**

La paleta de color que se usara en toda la aplicación estara conformada unicamente por dos colores. Esto se debe a que el usar muchos colores puede ser distractor y en nuestra aplicación eso sería contraproducente, ya que se trabaja con datos importantes y se usa para tomar decisiones.

**Los colores son los siguientes:**


![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.003.png)

Spacing:

Espacio entre líneas: 120%

Espacio de margen izquierdo y derecho: 160 px

Margen superior: 38 px

Margen inferior: 132 px

Espacio entre secciones:60 px

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.004.png)

Entre las opciones del menú: 32px

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.005.png)

Distancia entre cursos: 25.12 px

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.006.png)

### **4.1.2. Web Style Guidelines.**

Nuestra aplicación usará un diseño web responsivo, es decir tendremos una única versión que se adaptará a los diferentes dispositivos. Se ha tomado en cuenta las siguientes características:

Visuales:

- Redimensión de elementos: En el caso de las pantallas de menor tamaño, los textos, elementos decorativos e imágenes se ajustan para que se visualicen de forma completa y sin perder la funcionalidad.
- Flexibilidad en la disposición de los elementos: Se consideró la reorganización de los elementos en diferentes dispositivos y tamaños de pantalla. Los textos que acompañan a las imágenes de forma horizontal, al proyectarse en celulares se visualizan de forma vertical, es decir el texto se coloca arriba o abajo de la imagen según sea necesario.
- Imágenes y contenido multimedia adaptado: Se optimizaron las imágenes para que el tiempo de carga sea el menor posible.

Interacción:

- Navegación intuitiva: La navegación de nuestra aplicación es similar en todos los tamaños de pantalla, sin embargo, se toma en consideración elementos como los menús que necesitan ser flotantes para que sea más cómodo e intuitivo para los usuarios que se encuentren en el celular.
- Touch-friendly design: Realizamos un diseño con botones visibles y espaciados entre otros elementos para asegurarnos de que al pasar a pantallas de celulares se puedan usar con el touch sin dificultad.

Evidencia:

Desde una computadora:

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.007.png)

Desde un celular:

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.008.png)

## **4.2. Information Architecture.**

### **4.2.1. Organization Systems.**

El sistema de organización que nosotros usaremos es jerarquía visual con el objetivo de simplificar la interacción del usuario con la aplicación web y garantizar la accesibilidad a todos los servicios ofrecidos. ![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.009.png)

Además, se implementará una organización secuencial en procesos como el registro de usuarios y la configuración de perfiles, asegurando que los pasos a seguir sean claros y fáciles de completar.

Para la búsqueda de contenido, se utilizará una organización matricial mediante filtros, permitiendo a los usuarios buscar por nombre o fecha.

### **4.2.2. Labeling Systems.**

Hemos desarrollado un Labeling System con un vocabulario con el que nuestros usuarios se comunican dentro del rubro de la educación. Adicionalmente, mantuvimos un lenguaje simple e intuitivo en botones que realizan acciones comunes como agregar o eliminar. A continuación, se presentan las etiquetas clave que guían la experiencia del usuario en nuestra aplicación.

- Home: Sección donde se muestran los cursos y la opción de pagar la suscripción.
- Register attendance: Se muestran los cursos que tienen los maestros y luego la lista de alumnos dentro. Se registra y visualiza la asistencia de los estudiantes.
- Grade book: Se muestran los cursos que tienen los maestros y luego la lista de alumnos dentro. Se registran y visualizan las notas de los estudiantes.
- Psychological controles: Se muestran los grados que hay en la escuela, luego los salones y por último los estudiantes. Se registran y visualizan los controles psicológicos de los estudiantes.
- Maintenance: Permite realizar reportes sobre la infraestructura o incidentes con los equipos de trabajo. 
- Send an email: Permite al usuario enviar correos desde la app.
- Calendar: Muestra el calendario.
- Settings: Se muestran las opciones de configuración.
- Help & Center: Muestra información sobre funcionalidades.

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.010.png)

### **4.2.3. SEO Tags and Meta Tags**

|**Tipo de Etiqueta**|**Descripción**|**Implementación**|
| :-: | :-: | :-: |
|<title>|Título de la Página|<title> RocketNotes</title>|
|<meta>|Metaetiqueta para información adicional|<meta name="description" content="Simplify the management of infrastructure and school processes with RoketNotes. Our platform offers comprehensive solutions for efficient and hassle-free administration.">|
|<meta>|Metaetiqueta para palabras clave|<meta name="keywords" content="Infrastructure Management, School Management, Management Web Application, School Administration Software, Educational Management Tools">|
|<meta>|Metaetiqueta para control de robots|<meta name="robots" content="index, follow">|
|<link>|Enlace canónico|<link rel="canonical" href="https://RocketNotes.com">|

### **4.2.4. Searching Systems.**

La búsqueda dentro de nuestra aplicación web es fundamental para que los usuarios tengan una experiencia satisfactoria, por ello desarrollaremos una barra de búsqueda con la característica de que estas darán sugerencias de autocompletado. Esta barra se encontrará en la parte superior derecha de la aplicación web.![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.011.png)

Respecto a la búsqueda en el landing page se hará por enlaces que se encuentran en la barra superior.

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.012.png)

Cada uno de estos enlaces dirige al usuario a la sección deseada.

### **4.2.5. Navigation Systems.**

El sistema de navegación que emplea nuestra aplicación web inicia en la página principal. Nuestros usuarios que ingresan como profesor cuentan con una sidebar en la que pueden ingresar a las siguientes secciones:

- Home
- Register attendance
- Grade book
- Psychological controls
- Maintenance
- Send an email
- Calendar 
- Settings
- Help & Center

Al seleccionar cada una de estas secciones los usuarios se pueden dirigir a distintos apartados.

Register attendance: Se puede visualizar los cursos que dicta cada profesor. Al seleccionar un curso la página los dirige a la tabla de asistencias de los estudiantes. 

Grade book: Se tiene acceso un listado de salones por curso, que al seleccionarlos dirigen al usuario a las tablas de calificaciones de cada estudiante. En la parte superior derecha de la página hay un botón que despliega un formulario para agregar a un estudiante.

Psychological controls: Se visualizan los estudiantes que tuvieron un control psicológico con el psicólogo del colegio y en la parte superior derecha hay un botón que despliega un formulario para registrar información de un nuevo control.

Maintenance: Se despliega un formulario para agregar observaciones respecto a el estado de la infraestructura o incidentes con los equipos de trabajo. Tienen dos botones con los que cancelan o envían el reporte. 

Send an email: Despliega la página para enviar un email. Luego el usuario selecciona el botón enviar o cancelar.

Calendar: Muestra el calendario en el que al apretar una casilla el usuario registra un evento.

Settings: El usuario observa un formulario donde debe de confirmar su correo y contraseña. Luego al seleccionar save se muestran diferentes opciones de configuración.

Help & Center: Muestra información sobre funcionalidades. Solo se puede leer. 

Los usuarios que ingresan como administradores cuentan con las siguientes secciones en el sidebar:

- All reports: Se despliegan los reportes más recientes. El usuario puede eliminarlos seleccionando el icono a en la derecha de la fila.
- Classroom capacity: Se muestra una tabla de salones, estudiantes y capacidad. Presionando el icono de la derecha el usuario elimina la información de la fila. Seleccionando el botón de la derecha superior de la página el usuario puede añadir un salón.
- Settings: El usuario observa un formulario donde debe de confirmar su correo y contraseña. Luego al seleccionar save se muestran diferentes opciones de configuración.
- Help & Center: Muestra información sobre funcionalidades. Solo se puede leer. 

## **4.3. Landing Page UI Design**

### **4.3.1. Landing Page Wireframe**

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.013.png)

### **4.3.2. Landing Page Mock-up**

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.014.png)

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.015.png)

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.016.png)

LINK FIGMA: <https://www.figma.com/file/pBcefWno0VR16AEy7elc2m/Open-Source?type=design&node-id=0%3A1&mode=design&t=BmgtN82Ieketfpvn-1>

LINK LANDING PAGE:
<https://rocketnotes-open-source-sw57-grupo-3.github.io/RocketNotes-Landing-page/>

## **4.4. Web Applications UX/UI Design**

### **4.4.1. Web Applications Wireframes**

**User goal:** El usuario se registra, donde puede restablecer su contraseña o iniciar sesión en la aplicación.

Inicio de sesión

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.017.png)

Registro de nueva cuenta

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.018.png)

Restablecer la contraseña

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.019.png)

**User goal:** Presentación del home de la aplicación.

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.020.png)

**Wireframes para profesores:**

**User goal:** Registro de asistencia

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.021.png)

**User goal:** Agregar estudiante a la lista de asistencia

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.022.png)

**User goal:** Eliminar estudiante a la lista de asistencia

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.023.png)

**User goal:** Registro de notas

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.024.png)

**User goal:** Reporte de control psicológico

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.025.png)

**User goal:** Generar un reporte al staff del colegio

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.026.png)

**User goal:** Pasarela de pagos

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.027.png)

**User goal:** Enviar correo electrónico

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.028.png)

**User goal:** Calendario

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.029.png)

**User goal:** Configuraciones del perfil

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.030.png)

**Wireframes para staff:**

**User goal:** Registro de suscripciones

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.031.png)

**User goal:** Dashboard de todos los reportes

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.032.png)

**User goal:** Enviar notificaciones a profesores

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.033.png)

**User goal:** Lista de salones e información adicional

![Aplicación para staff
User goal: Lista de salones y su respectiva información
](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.034.png)

**User goal:** Agregar salon

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.035.png)

**User goal:** Eliminar salon

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.036.png)

### **4.4.2. Web Applications Wireflow Diagrams.**

**User goal:** Registro de un nuevo usuario, recuperación de contraseña o inicio de sesión a la aplicación.

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.037.png)

**Descripción**:

El usuario tiene la intención de realizar acciones relacionadas con la autenticación y la gestión de cuentas dentro de la aplicación. Esto puede incluir el registro de un nuevo usuario para obtener acceso a la aplicación, la recuperación de una contraseña perdida o el inicio de sesión en una cuenta existente.

**User goal:** Visualización de clases, creación de clases y borrado de clases.

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.038.png)

**Descripción**:

El objetivo del usuario es realizar operaciones relacionadas con la gestión de clases dentro de la aplicación. Esto incluye la visualización de clases existentes, la creación de nuevas clases según sea necesario y la capacidad de eliminar clases previamente creadas. 

User goal: Visualización de lista de asistencia, donde se muestran estudiantes y se pueden tanto agregar y eliminar estudiantes.

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.039.png)

**Descripción**:

El objetivo del usuario es interactuar con una lista de asistencia dentro de la aplicación. Esto implica la visualización de una lista de estudiantes inscritos, así como la capacidad de agregar nuevos estudiantes a la lista o eliminar estudiantes existentes según sea necesario.

**User goal:** Hacer uso del dashboard con el fin de acceder a configuración,  calendario, envío de correo, control psicológico.

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.040.png)

**Descripción**:

El objetivo del usuario es utilizar el panel de control (dashboard) para acceder a varias funcionalidades dentro de la aplicación como acceder a la configuración para ajustar las preferencias o configuraciones de la aplicación, consultar el calendario para ver fechas importantes, enviar correos electrónicos directamente desde el dashboard.

Además, acceder a herramientas relacionadas con el control psicológico.

**User goal:** Hacer uso del Home para visualizar, crear y notificar algún reporte. Además, se puede acceder al centro de ayuda.

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.041.png)

Descripción:

El objetivo del usuario es utilizar la página de inicio como punto de partida para diversas actividades relacionadas con la gestión de informes. Esto incluye la capacidad de visualizar informes existentes, crear nuevos informes según sea necesario y recibir notificaciones pertinentes relacionadas con los mismos. Además, el usuario busca acceder fácilmente al centro de ayuda desde la página de inicio para obtener asistencia adicional o resolver cualquier duda que pueda surgir.

**User goal:** Elegir una suscripción y realizar el pago.

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.042.png)

Descripción:

El usuario tiene la intención de seleccionar una suscripción dentro de la aplicación y completar el proceso de pago asociado a dicha suscripción. Esto implica la elección de un plan de suscripción que se ajuste a las necesidades del usuario y la finalización del pago correspondiente para activar la suscripción seleccionada.

4\.4.2. Web Applications Mock-ups.

**User goal:** El usuario se registra, restablecer su contraseña o inicia sesión en la aplicación

Inicio de sesión

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.043.png)

Registro de nueva cuenta

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.044.png)

Restablecer la contraseña

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.045.png)

Wireframes para profesores

**User goal:** Presentación del home de la aplicación

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.046.png)

**User goal:** Registro de asistencia

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.047.png)

**User goal:** Agregar estudiante a la lista de asistencia

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.048.png)

**User goal:** Eliminar estudiante a la lista de asistencia

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.049.png)

**User goal:** Registro de notas

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.050.png)

**User goal:** Reporte de control psicológico

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.051.png)

**User goal:** Generar un reporte al staff del colegio

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.052.png)

**User goal:** Registro de suscripciones

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.053.png)

**User goal:** Pasarela de pagos

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.054.png)

**User goal:** Enviar correo electrónico

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.055.png)

**User goal:** Calendario

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.056.png)

**User goal:** Configuraciones del perfil

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.057.png)

**Wireframes para staff:**

**User goal:** Dashboard de todos los reportes

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.058.png)

**User goal:** Enviar notificaciones a profesores

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.059.png)

**User goal:** Lista de salones y su respectiva información

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.060.png)

**User goal:** Agregar salon

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.061.png)

**User goal:** Eliminar salon

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.062.png)

### **4.4.3. Web Applications User Flow Diagrams.**

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.063.png)

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.064.png)

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.065.png)

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.066.png)

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.067.png)

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.068.png)

### **4.5. Web Applications Prototyping**

Acceda al prototipo de nuestra aplicación por medio de este enlace:
**<https://www.figma.com/file/TjxKSpJ88E1fyVr6BmBJhD/PROTOTYPING?type=design&mode=design&t=enuSSTjm6Q1VbWCf-1>**

## **4.6. Domain-Driven Software Architecture**

La Arquitectura de Software Orientada al Dominio enfatiza comprender el dominio del problema antes de diseñar el sistema. Este enfoque alinea la tecnología con las necesidades del negocio, reduciendo complejidad y mejorando la eficacia en el desarrollo de software. 

### **4.6.1. Software Architecture Context Diagram**

Este diagrama proporciona una vista de alto nivel de nuestro sistema de software y su entorno externo.

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.069.png)

### **4.6.2. Software Architecture Container Diagrams.**

Este diagrama se centra en descomponer el sistema en contenedores de alto nivel, que pueden ser aplicaciones, servicios web, bases de datos, etc.

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.070.png)

### **4.6.3. Software Architecture Components Diagrams.**

Estos diagramas profundizan en los contenedores identificados en los diagramas anteriores y descomponen cada contenedor en sus componentes individuales.

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.071.png)

## **4.7. Software Object-Oriented Design.**

### **4.7.1. Class Diagrams**

Bounded context: User Controller


![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.072.png)

Bounded context: Student Controller


![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.073.png)



Bounded context: Inventory Controller


![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.074.png)

Bounded context: Infrastructure Controller


![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.075.png)

### **4.7.1. Class Dictionary.**


**Bounded Context User Controller:**

**AuthenticationService class:** Esta clase es el servicio central para manejar la autenticación de los usuarios en el sistema. Provee una instancia estática, siguiendo el patrón singleton para asegurar un único punto de autenticación en toda la aplicación. Sus responsabilidades incluyen la gestión del inicio y cierre de sesión, así como la verificación de credenciales.

**Atributos:**

- Instance: Instancia estática para el acceso al servicio.

**Métodos:**

- AuthenticationService(): Constructor de la clase.
- GetInstance(): Método estático que devuelve la instancia única del servicio.
- ` `Login(): Permite a los usuarios iniciar sesión.
- Logout(): Permite a los usuarios cerrar sesión.
- ` `VerifyCredentials(): Verifica las credenciales de los usuarios.

**AccountFactory class:** Actúa como una fábrica para la creación de cuentas de usuario. Utiliza los detalles proporcionados por los usuarios para crear una nueva cuenta y asociarla con la entidad de User.

**Métodos:**

- CreateUserAccount(): Crea y devuelve una nueva instancia de User.

**User class:** Representa a un usuario del sistema con toda la información esencial para su identificación y gestión dentro del sistema.

**Atributos:**

- username: Nombre de usuario para el acceso.
- password: Contraseña del usuario.

**Métodos:**

- Update(): Actualiza la información del usuario.
- ChangePassword(): Permite cambiar la contraseña.
- UpdateProfile(): Actualiza el perfil del usuario.

**MessagingSystem class:** Esta clase se encarga de manejar el envío de mensajes dentro del sistema. Utiliza el patrón Decorator para modificar o extender las funcionalidades de los mensajes.

**MessageComponent interface:** Define una interfaz para los componentes del mensaje que permitirá obtener su contenido.

**Message class:** Modela un mensaje dentro del sistema con todos los detalles necesarios, incluyendo el contenido, el remitente, los destinatarios y cualquier adjunto relacionado.

**Atributos:**

- content: El contenido del mensaje.
- sender: El usuario que envía el mensaje.
- receivers: La lista de usuarios que recibirán el mensaje.
- attachments: La lista de adjuntos del mensaje.

**Métodos:**

- GetMessageContent(): Devuelve el contenido del mensaje.
- AddAttachment(): Añade un adjunto al mensaje.

**Attachment class:** Representa un adjunto dentro de un mensaje y contiene la información necesaria para su manejo.

**MessageSearchStrategy interface:** Define la estrategia de búsqueda para los mensajes, permitiendo la implementación de distintas maneras de buscar mensajes basados en diferentes criterios.

**BySenderSearchStrategy class:** Implementa la estrategia de búsqueda de mensajes por remitente, proporcionando la funcionalidad necesaria para encontrar mensajes de un remitente específico.

**Métodos:**

- Search(): Busca en la lista de mensajes aquellos que coincidan con el remitente especificado.

**ByContentSearchStrategy class:** Implementa la estrategia de búsqueda de mensajes por contenido, permitiendo encontrar mensajes que contengan un texto específico.

**Métodos:**

- Search(): Busca en la lista de mensajes aquellos que contengan el contenido especificado.

**EncryptedMessageDecorator class:** Aplica el patrón Decorator para extender los mensajes con funcionalidades de encriptación, asegurando que el contenido del mensaje se mantenga seguro y privado durante el tránsito.

**Atributos:**

- messageComponent: El componente del mensaje original que se va a decorar.

**Métodos:**

- GetMessageContent(): Devuelve el contenido encriptado del mensaje.

**Bounded Context Student Controller:**

**IObserver interface:** Define la operación de actualización que los observadores deben implementar para recibir notificaciones de los cambios en el objeto que están observando.

**Métodos:**

- Update(student: Student): Actualiza el observador con la información más reciente del estudiante.

**CommunicationService class:** Encargada de la gestión de comunicaciones hacia los contactos parentales, maneja el envío de notificaciones por correo electrónico y SMS.

**Métodos:**

- SendEmail(message: String, contact: ParentContact): Envía un correo electrónico al contacto parental.
- SendSMS(message: String, contact: ParentContact): Envía un SMS al contacto parental.

**ProgressTracker class:** Actúa como un observador del progreso de los estudiantes, rastreando y actualizando los registros de progreso académico de los estudiantes.

**Métodos:**

- Update(student: Student): Recibe actualizaciones sobre el progreso de los estudiantes y modifica los registros correspondientes.

**StudentFactory class:** Fábrica que se especializa en la creación de objetos de la clase Student, instanciando estudiantes con detalles específicos y asociaciones necesarias.

Métodos:

- CreateStudentDetails(studentDetails: StudentDetails, parentContact: ParentContact): Crea una nueva instancia de un estudiante con los detalles proporcionados.

**Student class:** Representa a un estudiante en el sistema educativo, manteniendo información personal, académica y registros de asistencia.

**Atributos:**

- studentId: Identificador único del estudiante.
- name: Nombre del estudiante.
- level: Nivel educativo del estudiante.
- parentContact: Información de contacto del padre o tutor.
- academicRecords: Lista de registros académicos.
- attendanceRecords: Lista de registros de asistencia.

**Métodos:**

- AddAcademicRecord(record: AcademicRecord): Agrega un registro académico al estudiante.
- AddAttendanceRecord(record: AttendanceRecord): Agrega un registro de asistencia al estudiante.

**ParentContact class:** Contiene información de contacto de los padres o tutores y ofrece un método para enviarles notificaciones.

**Atributos:**

- emailAddress: Dirección de correo electrónico para enviar notificaciones.
- phoneNumber: Número de teléfono para enviar mensajes.

**Métodos:**

- SendNotification(message: String): Envía una notificación al contacto parental.

**AcademicRecord class:** Almacena información sobre el desempeño académico de un estudiante, incluyendo asignaturas y calificaciones.

**Atributos:**

- subject: Asignatura del registro académico.
- grade: Calificación obtenida en la asignatura.
- date: Fecha del registro.

**EducationalLevel class:** Representa el nivel educativo de un estudiante y contiene secciones de clases.

**Atributos:**

- name: Nombre del nivel educativo.
- sections: Lista de secciones de clase dentro del nivel educativo.

**Métodos:**

- AddSection(section: Section): Agrega una sección al nivel educativo.

**Section class:** Agrupa estudiantes en secciones o clases y gestiona sus grados.

**Atributos:**

- name: Nombre de la sección.
- grades: Lista de grados asociados a la sección.

**Métodos:**

- AddGrade(grade: Grade): Agrega un grado a la sección.

**Grade class:** Representa el grado o año escolar de los estudiantes y mantiene una lista de cursos.

**Atributos:**

- name: Nombre del grado escolar.
- courses: Lista de cursos asociados al grado.

**Métodos:**

- AddCourse(course: Course): Agrega un curso al grado.

**Course class:** Modela un curso educativo, incluyendo su nombre, código y el profesor que lo imparte.

**Atributos:**

- name: Nombre del curso.
- code: Código único del curso.
- instructor: Profesor que imparte el curso.

**Teacher class:** Representa a un profesor dentro del sistema, incluyendo los cursos que enseña.

**Atributos:**

- name: Nombre del profesor.
- courses: Lista de cursos que el profesor imparte.

**Métodos:**

TeachCourse(course: Course): Asocia un curso al profesor para enseñarlo.

**ClassSession class:** Representa una sesión de clase y administra el registro de asistencia a través de estrategias definidas.

**Atributos:**

- sessionDate: Fecha en la que ocurre la sesión de clase.
- recordedAttendances: Lista de registros de asistencia de la sesión.

**Métodos:**

- SetAttendanceStrategy(strategy: AttendanceStrategy): Establece la estrategia de registro de asistencia.

**AttendanceStrategy interface:** Define un método para registrar la asistencia de los estudiantes en una sesión de clase.

**Métodos:**

- RecordAttendance(student: Student, session: ClassSession): Registra la asistencia de un estudiante en una sesión de clase.

**ManualAttendanceStrategy class:** Implementa la interfaz AttendanceStrategy permitiendo el registro manual de la asistencia de los estudiantes.

**Métodos:**

- RecordAttendance(student: Student, session: ClassSession): Registra manualmente la asistencia de un estudiante en una sesión de clase.

**RFIDAttendanceStrategy class:** Implementa la interfaz AttendanceStrategy utilizando la tecnología RFID para registrar automáticamente la asistencia de los estudiantes.

**Métodos:**

- RecordAttendance(student: Student, session: ClassSession): Registra automáticamente la asistencia de un estudiante en una sesión de clase mediante RFID.

**Bounded Context Inventory Controller:**

**InventoryService class:** Esta clase gestiona el servicio de inventario de la aplicación, siguiendo el patrón singleton para garantizar una única instancia que maneje todas las operaciones de inventario. Facilita la adición y eliminación de elementos, así como la recuperación y el informe de elementos de inventario.

**Atributos:**

- instance: Instancia estática que asegura un punto único de manejo del inventario.

**Métodos:**

- InventoryService(): Constructor de la clase.
- GetInstance(): Retorna la instancia única del servicio de inventario.
- AddItem(): Agrega un elemento al inventario.
- RemoveItem(): Elimina un elemento del inventario.
- GetItemById(): Obtiene un elemento por su identificador.
- ExportReport(): Exporta un informe del inventario.

**InventoryItemFactory class:** Funciona como una fábrica para crear elementos de inventario, simplificando el proceso de creación y asegurando que todos los elementos se construyan de manera consistente.




- **Métodos:**

  CreateItem(): Crea y devuelve una nueva instancia de InventoryItem.

**InventoryItem class:** Modela un elemento dentro del inventario, con propiedades como identificación, nombre y cantidad, y mantiene una lista de observadores para cualquier cambio en sus datos.

**Atributos:**

- id: Identificador único del elemento.
- name: Nombre del elemento.
- quantity: Cantidad del elemento en inventario.
- updateStrategy: Estrategia actual de actualización de la cantidad.

**Métodos:**

- SetUpdateStrategy(): Establece la estrategia de actualización del elemento.
- UpdateQuantity(): Actualiza la cantidad del elemento en inventario.
- Attach(): Agrega un observador a la lista de observadores.
- Detach(): Elimina un observador de la lista de observadores.
- NotifyObservers(): Notifica a todos los observadores de los cambios.

**IObserver interface:** Define la interfaz que deben implementar los observadores para recibir actualizaciones sobre los cambios en los elementos del inventario.

**Métodos:**

- Update(): Actualiza el observador con la información del elemento de inventario.

**IUpdateStrategy interface:** Establece el método que las estrategias de actualización de inventario deben implementar para cambiar la cantidad de un elemento.

**Métodos:**

- UpdateQuantity(): Actualiza la cantidad de un elemento de inventario.

**InventoryChangeLogger class:** Observador concreto que registra cualquier cambio en los elementos del inventario para propósitos de seguimiento o auditoría.

**Métodos:**

- Update(): Registra los cambios realizados en un elemento de inventario.

**IncrementalUpdateStrategy class:** Estrategia concreta que implementa la interfaz IUpdateStrategy para actualizar la cantidad de un elemento de manera incremental.

**Métodos:**

- UpdateQuantity(): Aumenta o disminuye la cantidad de un elemento del inventario según la cantidad proporcionada.

**SchoolSupplies class y Equipment class:**

Subclases concretas de InventoryItem que representan diferentes tipos de elementos en el inventario, como suministros escolares o equipos.

**Bounded Context Infrastructure Controller:**

**ClassroomFactory class:** Esta clase es una fábrica que se especializa en la creación de instancias de la clase Classroom. Proporciona un método para crear nuevos salones de clase con un nombre y una capacidad especificada.

**Métodos:**

- CreateClassroom(name: String, capacity: Int): Crea y devuelve una nueva instancia de la clase Classroom con el nombre y la capacidad proporcionados.

**ReportGenerator class:** Es responsable de generar informes basados en la lista de aulas proporcionadas. Utiliza los datos de las aulas para compilar un informe detallado.

**Métodos:**

- GenerateReport(classrooms: List<Classroom>): Genera y devuelve un informe sobre las aulas proporcionadas.

**Classroom class:** Modela un aula dentro del sistema, manteniendo su nombre y capacidad. Ofrece métodos para agregar, actualizar y listar aulas, así como filtrarlas según estrategias de filtrado.

**Atributos:**

- name: Nombre del aula.
- capacity: Capacidad del aula en términos de número de personas que puede albergar.

**Métodos:**




- AddClassroom(): Añade un nuevo aula al sistema.
- UpdateClassroomInfo(): Actualiza la información de un aula existente.
- ListClassrooms(): Lista todas las aulas disponibles en el sistema.
- FilterClassrooms(strategy: FilterStrategy): Filtra las aulas utilizando una estrategia de filtrado proporcionada.

**FilterStrategy interface:** Define un contrato para las estrategias de filtrado que se pueden aplicar a las listas de aulas.

**Métodos:**

- Filter(classrooms: List<Classroom>): Devuelve una lista de aulas filtradas según el criterio de la estrategia.

**LocationFilterStrategy class y CapacityFilterStrategy class:** Implementaciones concretas de la interfaz FilterStrategy. Proporcionan lógica para filtrar aulas por ubicación y capacidad, respectivamente.

**Métodos:**

Filter(classrooms: List<Classroom>): Filtra y devuelve aulas basándose en la ubicación o capacidad.

**BudgetingSystem class:** Gestiona el presupuesto asociado a cada aula, permitiendo crear, actualizar y obtener presupuestos, así como aprobar presupuestos para las aulas.

**Atributos:**

- budgets: Un mapa que asocia aulas con un valor presupuestario.

**Métodos:**

- CreateBudgetForClassroom(): Crea un nuevo presupuesto para un aula.
- UpdateBudgetForClassroom(): Actualiza el presupuesto asignado a un aula.
- GetBudgetForClassroom(): Obtiene el presupuesto actual para un aula.
- ApproveBudgetForClassroom(): Aprueba el presupuesto para un aula.

**Observer interface:** Define la funcionalidad para las clases que deben ser notificadas de cambios en las aulas que están observando.

**Métodos:**




- Update(classroom: Classroom): Actualiza el observador con la información más reciente de un aula.

**ClassroomCapacityObserver class:**

Un observador concreto que monitorea los cambios en la capacidad de las aulas y reacciona ante estos cambios.

**Métodos:**

- Update(classroom: Classroom): Registra los cambios en la capacidad de un aula específica.

**Command interface:**

Define operaciones para ejecutar comandos, así como para deshacer los comandos ejecutados anteriormente.

**Métodos:**

- Execute(): Ejecuta el comando.
- Undo(): Deshace el comando.

**AddClassroomCommand class y UpdateClassroomInfoCommand class:** Clases concretas que implementan la interfaz Command. Estos comandos añaden nuevas aulas y actualizan la información de las aulas existentes, respectivamente, con la capacidad de deshacer estas operaciones.

## **4.8. Database Design**

### **4.8.1. Database Diagram**

![](images-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.076.png) 

LINK VERTABELO:

<https://my.vertabelo.com/public-model-view/pOGF92Qrej8ON4jOc1ZvJLwV1H9yYViDPO6ppO7hmkc2om3xPQkS3tWLKbdLCtwV?x=2225&y=2354&zoom=0.3512> 
=======
﻿# **Capítulo V: Product Implementation, Validation & Deployment**

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


