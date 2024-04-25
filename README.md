### **Capítulo IV: Product Design** 

## **4.1. Style Guidelines**

### **4.1.1. General Style Guidelines.**

**Branding:**

Nuestra aplicación está destinada al personal administrativo y profesores de instituciones educativas de educación básica, por ello el branding de nuestra marca busca transmitir seriedad y serenidad. Adicionalmente, como nos enfocamos en brindar soporte a los procesos de gestión del bienestar de estudiantes e infraestructura escolar, necesitamos que la aplicación no cuente con elementos distractores, por ello el diseño debe de ser lo más simple e intuitivo posible.

**Logo:**

Lo primero que definimos fue el logo de nuestra marca, ya que este representa nuestra identidad. El logo usa la fuente Roboto y los colores gris oscuro (#595959) y verde (#1EC089). El tamaño del logo dependerá de la pantalla en la que se muestre, ya que si se muestra en una computadora será más grande que si se muestra en un celular.

- Fuente: Roboto.

[](image-chapter-IV/Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.001.png)

Color palette:![ref1]

**Typography:**

1. Heading one: Roboto - 64px
1. Heading two: Roboto - 40px
1. Heading three: Roboto - 36px
1. Body: Roboto -20px
1. Body: Roboto - 14px

**Global Color Palette:**

La paleta de color que se usara en toda la aplicación estara conformada unicamente por dos colores. Esto se debe a que el usar muchos colores puede ser distractor y en nuestra aplicación eso sería contraproducente, ya que se trabaja con datos importantes y se usa para tomar decisiones.

**Los colores son los siguientes:**


![ref2]

Spacing:

Espacio entre líneas: 120%

Espacio de margen izquierdo y derecho: 160 px

Margen superior: 38 px

Margen inferior: 132 px

Espacio entre secciones:60 px

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.004.png)

Entre las opciones del menú: 32px

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.005.png)

Distancia entre cursos: 25.12 px

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.006.png)

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

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.007.png)

Desde un celular:

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.008.png)

## **4.2. Information Architecture.**

### **4.2.1. Organization Systems.**

El sistema de organización que nosotros usaremos es jerarquía visual con el objetivo de simplificar la interacción del usuario con la aplicación web y garantizar la accesibilidad a todos los servicios ofrecidos. ![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.009.png)

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

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.010.png)

### **4.2.3. SEO Tags and Meta Tags**

|**Tipo de Etiqueta**|**Descripción**|**Implementación**|
| :-: | :-: | :-: |
|<title>|Título de la Página|<title> RocketNotes</title>|
|<meta>|Metaetiqueta para información adicional|<meta name="description" content="Simplify the management of infrastructure and school processes with RoketNotes. Our platform offers comprehensive solutions for efficient and hassle-free administration.">|
|<meta>|Metaetiqueta para palabras clave|<meta name="keywords" content="Infrastructure Management, School Management, Management Web Application, School Administration Software, Educational Management Tools">|
|<meta>|Metaetiqueta para control de robots|<meta name="robots" content="index, follow">|
|<link>|Enlace canónico|<link rel="canonical" href="https://RocketNotes.com">|

### **4.2.4. Searching Systems.**

La búsqueda dentro de nuestra aplicación web es fundamental para que los usuarios tengan una experiencia satisfactoria, por ello desarrollaremos una barra de búsqueda con la característica de que estas darán sugerencias de autocompletado. Esta barra se encontrará en la parte superior derecha de la aplicación web.![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.011.png)

Respecto a la búsqueda en el landing page se hará por enlaces que se encuentran en la barra superior.

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.012.png)

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

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.013.png)

### **4.3.2. Landing Page Mock-up**

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.014.png)

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.015.png)

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.016.png)

LINK FIGMA: <https://www.figma.com/file/pBcefWno0VR16AEy7elc2m/Open-Source?type=design&node-id=0%3A1&mode=design&t=BmgtN82Ieketfpvn-1>

LINK LANDING PAGE:
<https://rocketnotes-open-source-sw57-grupo-3.github.io/RocketNotes-Landing-page/>

## **4.4. Web Applications UX/UI Design**

### **4.4.1. Web Applications Wireframes**

**User goal:** El usuario se registra, donde puede restablecer su contraseña o iniciar sesión en la aplicación.

Inicio de sesión

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.017.png)

Registro de nueva cuenta

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.018.png)

Restablecer la contraseña

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.019.png)

**User goal:** Presentación del home de la aplicación.

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.020.png)

**Wireframes para profesores:**

**User goal:** Registro de asistencia

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.021.png)

**User goal:** Agregar estudiante a la lista de asistencia

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.022.png)

**User goal:** Eliminar estudiante a la lista de asistencia

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.023.png)

**User goal:** Registro de notas

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.024.png)

**User goal:** Reporte de control psicológico

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.025.png)

**User goal:** Generar un reporte al staff del colegio

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.026.png)

**User goal:** Pasarela de pagos

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.027.png)

**User goal:** Enviar correo electrónico

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.028.png)

**User goal:** Calendario

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.029.png)

**User goal:** Configuraciones del perfil

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.030.png)

**Wireframes para staff:**

**User goal:** Registro de suscripciones

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.031.png)

**User goal:** Dashboard de todos los reportes

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.032.png)

**User goal:** Enviar notificaciones a profesores

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.033.png)

**User goal:** Lista de salones e información adicional

![Aplicación para staff
User goal: Lista de salones y su respectiva información
](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.034.png)

**User goal:** Agregar salon

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.035.png)

**User goal:** Eliminar salon

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.036.png)

### **4.4.2. Web Applications Wireflow Diagrams.**

**User goal:** Registro de un nuevo usuario, recuperación de contraseña o inicio de sesión a la aplicación.

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.037.png)

**Descripción**:

El usuario tiene la intención de realizar acciones relacionadas con la autenticación y la gestión de cuentas dentro de la aplicación. Esto puede incluir el registro de un nuevo usuario para obtener acceso a la aplicación, la recuperación de una contraseña perdida o el inicio de sesión en una cuenta existente.

**User goal:** Visualización de clases, creación de clases y borrado de clases.

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.038.png)

**Descripción**:

El objetivo del usuario es realizar operaciones relacionadas con la gestión de clases dentro de la aplicación. Esto incluye la visualización de clases existentes, la creación de nuevas clases según sea necesario y la capacidad de eliminar clases previamente creadas. 

User goal: Visualización de lista de asistencia, donde se muestran estudiantes y se pueden tanto agregar y eliminar estudiantes.

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.039.png)

**Descripción**:

El objetivo del usuario es interactuar con una lista de asistencia dentro de la aplicación. Esto implica la visualización de una lista de estudiantes inscritos, así como la capacidad de agregar nuevos estudiantes a la lista o eliminar estudiantes existentes según sea necesario.

**User goal:** Hacer uso del dashboard con el fin de acceder a configuración,  calendario, envío de correo, control psicológico.

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.040.png)

**Descripción**:

El objetivo del usuario es utilizar el panel de control (dashboard) para acceder a varias funcionalidades dentro de la aplicación como acceder a la configuración para ajustar las preferencias o configuraciones de la aplicación, consultar el calendario para ver fechas importantes, enviar correos electrónicos directamente desde el dashboard.

Además, acceder a herramientas relacionadas con el control psicológico.

**User goal:** Hacer uso del Home para visualizar, crear y notificar algún reporte. Además, se puede acceder al centro de ayuda.

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.041.png)

Descripción:

El objetivo del usuario es utilizar la página de inicio como punto de partida para diversas actividades relacionadas con la gestión de informes. Esto incluye la capacidad de visualizar informes existentes, crear nuevos informes según sea necesario y recibir notificaciones pertinentes relacionadas con los mismos. Además, el usuario busca acceder fácilmente al centro de ayuda desde la página de inicio para obtener asistencia adicional o resolver cualquier duda que pueda surgir.

**User goal:** Elegir una suscripción y realizar el pago.

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.042.png)

Descripción:

El usuario tiene la intención de seleccionar una suscripción dentro de la aplicación y completar el proceso de pago asociado a dicha suscripción. Esto implica la elección de un plan de suscripción que se ajuste a las necesidades del usuario y la finalización del pago correspondiente para activar la suscripción seleccionada.

4\.4.2. Web Applications Mock-ups.

**User goal:** El usuario se registra, restablecer su contraseña o inicia sesión en la aplicación

Inicio de sesión

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.043.png)

Registro de nueva cuenta

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.044.png)

Restablecer la contraseña

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.045.png)

Wireframes para profesores

**User goal:** Presentación del home de la aplicación

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.046.png)

**User goal:** Registro de asistencia

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.047.png)

**User goal:** Agregar estudiante a la lista de asistencia

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.048.png)

**User goal:** Eliminar estudiante a la lista de asistencia

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.049.png)

**User goal:** Registro de notas

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.050.png)

**User goal:** Reporte de control psicológico

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.051.png)

**User goal:** Generar un reporte al staff del colegio

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.052.png)

**User goal:** Registro de suscripciones

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.053.png)

**User goal:** Pasarela de pagos

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.054.png)

**User goal:** Enviar correo electrónico

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.055.png)

**User goal:** Calendario

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.056.png)

**User goal:** Configuraciones del perfil

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.057.png)

**Wireframes para staff:**

**User goal:** Dashboard de todos los reportes

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.058.png)

**User goal:** Enviar notificaciones a profesores

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.059.png)

**User goal:** Lista de salones y su respectiva información

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.060.png)

**User goal:** Agregar salon

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.061.png)

**User goal:** Eliminar salon

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.062.png)

### **4.4.3. Web Applications User Flow Diagrams.**

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.063.png)

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.064.png)

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.065.png)

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.066.png)

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.067.png)

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.068.png)

### **4.5. Web Applications Prototyping**

Acceda al prototipo de nuestra aplicación por medio de este enlace:
**<https://www.figma.com/file/TjxKSpJ88E1fyVr6BmBJhD/PROTOTYPING?type=design&mode=design&t=enuSSTjm6Q1VbWCf-1>**

## **4.6. Domain-Driven Software Architecture**

La Arquitectura de Software Orientada al Dominio enfatiza comprender el dominio del problema antes de diseñar el sistema. Este enfoque alinea la tecnología con las necesidades del negocio, reduciendo complejidad y mejorando la eficacia en el desarrollo de software. 

### **4.6.1. Software Architecture Context Diagram**

Este diagrama proporciona una vista de alto nivel de nuestro sistema de software y su entorno externo.

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.069.png)

### **4.6.2. Software Architecture Container Diagrams.**

Este diagrama se centra en descomponer el sistema en contenedores de alto nivel, que pueden ser aplicaciones, servicios web, bases de datos, etc.

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.070.png)

### **4.6.3. Software Architecture Components Diagrams.**

Estos diagramas profundizan en los contenedores identificados en los diagramas anteriores y descomponen cada contenedor en sus componentes individuales.

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.071.png)

## **4.7. Software Object-Oriented Design.**

### **4.7.1. Class Diagrams**

Bounded context: User Controller


![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.072.png)

Bounded context: Student Controller


![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.073.png)



Bounded context: Inventory Controller


![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.074.png)

Bounded context: Infrastructure Controller


![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.075.png)

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

![](Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.076.png) 

LINK VERTABELO:

<https://my.vertabelo.com/public-model-view/pOGF92Qrej8ON4jOc1ZvJLwV1H9yYViDPO6ppO7hmkc2om3xPQkS3tWLKbdLCtwV?x=2225&y=2354&zoom=0.3512> 

[ref1]: Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.002.png
[ref2]: Aspose.Words.3e46ae07-de12-4681-8397-de67a92d1ea1.003.png
