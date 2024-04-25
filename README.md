﻿# **Capítulo III: Requirements Specification**

## **3.1. To-Be Scenario Mapping.**

**Juan Quispe:**

![](Aspose.Words.a2067305-f689-47d5-8d76-971ef1bc2225.001.png)

**Ana Garcia:**

![](Aspose.Words.a2067305-f689-47d5-8d76-971ef1bc2225.002.png)

## **3.2. User Stories**

En esta sección, para estructurar nuestro proceso de desarrollo y asegurar que cubrimos todos los aspectos necesarios para nuestros usuarios, clasificamos las historias de usuario en epics. Cada epic captura un conjunto de funcionalidades relacionadas que, en conjunto, proporcionan un valor significativo a un segmento particular de usuarios o abordan una necesidad operativa crítica de la institución educativa.

A continuación, se detalla la relación entre las epics definidas y las historias de usuario asociadas, delineando claramente los objetivos, las funcionalidades esperadas y los beneficios tangibles que cada una trae a nuestra aplicación RocketNotes.

|Epic / Story ID|Título|Descripción|Criterios de Aceptación|Epic / Story ID|
| :- | :- | :- | :- | :- |
|<p></p><p>E1: Gestión de Aforo y Espacio</p><p></p><p>Como miembro del equipo administrativo o profesor,</p><p>Quiero administrar y optimizar el uso de aulas y espacios educativos,</p><p>Para garantizar un entorno de aprendizaje adecuado y cumplir con normativas de seguridad y salud.</p><p><br><br></p>||||<p></p><p>E1: Gestión de Aforo y Espacio</p><p></p><p>Como miembro del equipo administrativo o profesor,</p><p>Quiero administrar y optimizar el uso de aulas y espacios educativos,</p><p>Para garantizar un entorno de aprendizaje adecuado y cumplir con normativas de seguridad y salud.</p><p><br><br></p>|
|E1-US01|Gestión del aforo de las aulas.|<p>Como miembro del equipo administrativo,</p><p>Quiero gestionar de manera efectiva el aforo de las aulas,</p><p>Para optimizar el espacio disponible y asegurar un entorno de aprendizaje adecuado.</p>|<p></p><p>*Escenario 1: Visualización de aulas y su capacidad*</p><p>Dado que el usuario con permisos administrativos accede al sistema para gestionar el aforo de las aulas,</p><p>Cuando se solicita la visualización de la infraestructura actual,</p><p>Entonces, el sistema proporciona un listado de las aulas, con detalles como el nombre del aula (indicativo de su ubicación y número del aula), capacidad máxima permitida, estudiantes matriculados, piso y pabellón.</p><p>*Escenario 2: Añadir una nueva aula*</p><p>Dado que el usuario desea añadir una nueva aula al sistema.</p><p>Cuando envía los datos del aula, incluyendo nombre (siguiendo la nomenclatura establecida), capacidad máxima permitida, estudiantes matriculados y ubicación (piso y pabellón)</p><p>Y confirma la adición,</p><p>Entonces el sistema agrega el nuevo salón a la lista de aulas, permitiendo su gestión dentro de la plataforma.</p><p></p><p>*Escenario 3: Actualización de la información de un aula*</p><p>Dado que una aula existente necesita una actualización en su información de capacidad o disponibilidad.</p><p>Cuando el usuario proporciona los nuevos datos a actualizar,</p><p>Entonces el sistema aplica los cambios y verifica la actualización reflejando los nuevos datos del aula.</p><p></p><p>*Escenario 4: Consulta de aulas por piso o pabellón*</p><p>Dado que el usuario necesita encontrar aulas en una ubicación específica,</p><p>Cuando solicita aulas filtradas por piso o pabellón,</p><p>Entonces el sistema presenta únicamente las aulas que cumplen con el criterio de filtrado.</p><p></p>|E1-US01|
|E1-US02|Facilitación de la comunicación entre profesores y padres|<p>Como profesor,</p><p>Quiero comunicarme con los padres de mis estudiantes mediante un sistema de mensajería,</p><p>Para enviar correos electrónicos que informen sobre el progreso académico y asuntos relevantes relacionados con sus hijos.</p>|<p>*Escenario 1: Redacción del mensaje*</p><p>Dado que el profesor necesita enviar un correo a los padres de familia,</p><p>Cuando el profesor accede a la funcionalidad de mensajería </p><p>Y redacta un mensaje dirigido a los padres de los estudiantes especificados,</p><p>Entonces, el sistema ofrece una interfaz donde el profesor puede ingresar el contenido del mensaje</p><p>` `Y adjuntar cualquier documento relevante antes de enviarlo a los correos electrónicos asociados con los padres de los estudiantes seleccionados.</p><p></p><p>*Escenario 2: Confirmación de envío exitoso*</p><p>Dado que el profesor ha enviado un correo electrónico a través del sistema de mensajería,</p><p>Cuando el mensaje ha sido enviado exitosamente,</p><p>Entonces el sistema notifica al profesor la entrega exitosa del correo electrónico.</p><p></p><p>*Escenario 3: Registro de comunicaciones enviadas*</p><p>Dado que un correo electrónico ha sido enviado a los padres,</p><p>Cuando el envío se completa,</p><p>Entonces el sistema registra el correo electrónico en el historial de comunicaciones del estudiante para referencia futura.</p>|E1-US02|
|E1-US03|Registro de asistencias|<p>Como profesor,</p><p>Quiero registrar la asistencia de mis estudiantes</p><p>Para tener el registro de cada clase y un control eficiente de la presencia estudiantil. </p>|<p>*Escenario 1: Acceso a registro de asistencias por aula*</p><p>Dado que un profesor necesita registrar la asistencia en una clase específica,</p><p>Cuando accede a la función de asistencia dentro del sistema</p><p>Y solicita la lista de estudiantes de un aula determinada,</p><p>Entonces el sistema proporciona la lista actual de estudiantes asignados a esa aula.</p><p></p><p>*Escenario 2: Registro de asistencia de estudiantes*</p><p>Dado que el profesor accede a la lista de estudiantes de un aula específica,</p><p>Cuando marca la asistencia de los estudiantes</p><p>Y finaliza el proceso de registro,</p><p>Entonces, el sistema registra la asistencia de los estudiantes y confirma al profesor que el registro fue exitoso.</p><p></p><p>*Escenario 3: Edición de asistencias registradas*</p><p>Dado que un profesor identifica la necesidad de corregir un registro de asistencia previamente completado,</p><p>Cuando accede al registro específico y realiza los ajustes necesarios,</p><p>Y solicita realizar los cambios,</p><p>Entonces el sistema actualiza el registro de asistencia con la información corregida.</p><p></p><p>*Escenario 4: Visualización de historial de asistencias*</p><p>Dado que un profesor desea revisar el historial de asistencias de una clase o período específico,</p><p>Cuando solicita un informe de asistencias a través del sistema,</p><p>Entonces el sistema compila y muestra un reporte de las asistencias registradas.</p>|E1-US03|
|E1-US04|Gestión de las notas por aula|<p>Como profesor,</p><p>` `Quiero gestionar y registrar las notas de mis estudiantes de manera eficiente en cada evaluación. </p><p>Para asegurar un seguimiento preciso del rendimiento académico en las aulas asignadas</p>|<p>*Escenario 1: Acceso a evaluaciones y creación de nuevas*</p><p>Dado que un profesor necesita gestionar las notas en un aula designada,</p><p>Cuando accede a la sección de gestión de notas del sistema</p><p>` `Y consulta las evaluaciones para un aula específica,</p><p>Entonces el sistema muestra un listado de las evaluaciones existentes y ofrece la funcionalidad para añadir nuevas evaluaciones.</p><p></p><p>*Escenario 2: Registro de notas en una evaluación*</p><p>Dado que el profesor ha accedido a una evaluación específica,</p><p>Cuando ingresa las notas de cada estudiante </p><p>Y solicita el registro de las notas,</p><p>Entonces el sistema actualiza los registros de las nuevas notas de cada estudiante </p><p>Y notifica al profesor que las notas han sido guardadas exitosamente.</p><p></p><p>*Escenario 3: Actualización de notas existentes*</p><p>Dado que un profesor identifica la necesidad de modificar las notas de una evaluación previa,</p><p>Cuando accede a la evaluación, realiza las modificaciones necesarias y confirma los cambios,</p><p>Entonces el sistema actualiza los registros con las notas ajustadas y verifica la correcta aplicación de los cambios.</p><p></p><p>*Escenario 4: Consulta de historial académico de un estudiante*</p><p>Dado que el profesor desea revisar el desempeño académico de un estudiante,</p><p>Cuando solicita el historial de notas de un estudiante específico dentro de un aula,</p><p>Entonces, el sistema proporciona un resumen detallado de todas las evaluaciones y notas registradas para ese estudiante, permitiendo un análisis completo de su rendimiento académico.</p>|E1-US04|
|E1-US07|Exportación de Reportes de Rendimiento Estudiantil|<p>Como personal administrativo</p><p>Quiero exportar reportes de rendimiento estudiantil en formatos compatibles con otras herramientas de análisis</p><p>Para facilitar la revisión y el análisis de datos a nivel institucional.</p>|<p>*Escenario 1: Elección de formato para exportación*</p><p>Dado que el administrador necesita exportar un reporte de rendimiento estudiantil,</p><p>Cuando solicita la función de exportación de reportes,</p><p>Entonces el sistema presenta las opciones de formato disponibles y procesa la solicitud para preparar el reporte en el formato elegido.</p><p>*Escenario 2: Inicio de la descarga del reporte*</p><p>Dado que el administrador ha solicitado un reporte en un formato específico,</p><p>Cuando el sistema ha completado la preparación del reporte,</p><p>Entonces notifica al administrador que el reporte está listo para la descarga </p><p>Y procede con la descarga automática en la ubicación de almacenamiento designada.</p><p>*Escenario 3: Validación de contenido en el reporte descargado*</p><p>Dado que el reporte de rendimiento estudiantil se ha descargado,</p><p>Cuando el administrador consulta el reporte en su dispositivo,</p><p>Entonces verifica que el contenido del reporte refleja de manera precisa y completa el rendimiento estudiantil, según los criterios establecidos, en el formato de archivo seleccionado.</p><p>*Escenario 4: Generación de reporte con filtros aplicados*</p><p>Dado que el administrador busca un análisis detallado que requiere la aplicación de filtros específicos (como rango de fechas o categorías de rendimiento),</p><p>Cuando realiza la solicitud de exportación aplicando estos filtros,</p><p>Entonces el sistema genera y ofrece el reporte que coincide con los criterios de filtrado especificados, listo para su revisión y análisis posterior.</p>|E1-US07|
|E1-US08|Seguimiento de progreso individual del estudiante|<p>Como profesor,</p><p>` `Quiero realizar un seguimiento del progreso académico de cada uno de mis estudiantes a lo largo del año</p><p>Para identificar áreas de mejora y proporcionar apoyo adicional según sea necesario.</p><p></p>|<p>*Escenario 1: Consulta de lista de estudiantes por aula*</p><p>Dado que un profesor requiere revisar la composición de sus clases,</p><p>Cuando realiza una solicitud de información sobre una aula específica,</p><p>Entonces el sistema muestra un listado completo de los estudiantes matriculados en esa aula.</p><p>*Escenario 2: Acceso al historial académico para seguimiento individual:*</p><p></p><p>Dado que un profesor necesita evaluar el rendimiento de un estudiante individualmente,</p><p>Cuando solicita el perfil académico del estudiante dentro del sistema,</p><p>Entonces el sistema proporciona un resumen detallado del progreso académico, incluyendo evaluaciones y observaciones relevantes. </p><p>*Escenario 3: Identificación de estudiantes que requieren atención adicional:*</p><p>Dado que el profesor necesita identificar estudiantes que puedan necesitar apoyo adicional basado en su rendimiento académico,</p><p>Cuando revisa el rendimiento general de la clase a través del sistema,</p><p>Entonces el sistema resalta a los estudiantes que muestran signos de dificultades académicas</p><p></p>|E1-US08|
|E1-US10|Alertas de Indicadores de Rendimiento Bajo|<p>Como personal administrativo,</p><p>` `Quiero recibir alertas automáticas sobre estudiantes con rendimiento por debajo de lo esperado</p><p>Para facilitar intervenciones y apoyo adicional de manera oportuna.</p>|<p>*Escenario 1: Identificación de estudiantes con rendimiento bajo por grado*</p><p>Dado que el personal administrativo accede a la funcionalidad de rendimiento académico </p><p>Cuando el personal administrativo consulta los indicadores de rendimiento académico,</p><p>Entonces el sistema identifica y notifica sobre estudiantes con rendimientos bajos, proporcionando detalles específicos para facilitar el seguimiento.</p><p></p><p>*Escenario 2:Generación y envío de alertas de rendimiento:*</p><p></p><p>Dado la identificación de estudiantes que requieren atención adicional,</p><p>Cuando se alcanza un punto crítico que sugiere la necesidad de acciones correctivas,</p><p>Entonces el sistema genera y envía alertas automáticas al personal administrativo y docente correspondiente, detallando los pasos recomendados para apoyo.</p>|E1-US10|
|<p>E2: Mantenimiento y Operaciones de Infraestructura</p><p></p><p>Como miembro del equipo administrativo</p><p></p><p>Quiero gestionar y programar el mantenimiento de la infraestructura educativa</p><p></p><p>Para asegurar que las instalaciones y equipos se mantengan en óptimas condiciones y garantizar un entorno seguro para estudiantes y personal.</p><p></p>||||<p>E2: Mantenimiento y Operaciones de Infraestructura</p><p></p><p>Como miembro del equipo administrativo</p><p></p><p>Quiero gestionar y programar el mantenimiento de la infraestructura educativa</p><p></p><p>Para asegurar que las instalaciones y equipos se mantengan en óptimas condiciones y garantizar un entorno seguro para estudiantes y personal.</p><p></p>|
|E02-US11|Gestión del aforo de las instalaciones escolares.|<p>Como personal administrativo,</p><p>Quiero gestionar eficientemente la capacidad de las instalaciones escolares,</p><p>Para optimizar el espacio disponible, garantizar la seguridad y prevenir la sobrecarga en áreas comunes.</p>|<p>*Escenario 1: Acceso a información sobre aforo de instalaciones*</p><p>Dado que el personal administrativo requiere información actualizada sobre el aforo de las instalaciones,</p><p>Cuando accede a la herramienta de gestión de aforo dentro del sistema,</p><p>Entonces obtiene un listado actualizado de todas las instalaciones, incluyendo detalles sobre su capacidad máxima.</p><p>*Escenario 2: Modificación del aforo para una instalación*</p><p>Dado que se necesitan ajustes en la capacidad máxima permitida de una instalación debido a nuevas políticas o cambios estructurales,</p><p>Cuando el personal realiza y confirma los cambios en el sistema,</p><p>Entonces el sistema actualiza la información reflejando los nuevos límites de capacidad.</p><p>*Escenario 3: Incorporación de nueva instalación con su capacidad*</p><p>Dado que la institución cuenta con nuevas instalaciones que deben ser incorporadas al registro escolar,</p><p>Cuando el personal administrativo ingresa la información y capacidad de aforo de estas nuevas áreas,</p><p>Entonces el sistema agrega las nuevas instalaciones al listado, asegurando su gestión dentro del entorno escolar.</p><p></p>|E02-US11|
|E02-US14|Gestión de la frecuencia con la que se realiza el mantenimiento de infraestructuras.|<p>Como personal administrativo</p><p>Quiero administrar y configurar la frecuencia del mantenimiento de la infraestructura escolar</p><p>Para asegurar su óptimo estado y tomar decisiones basadas en un calendario de mantenimiento eficiente.</p>|<p>*Escenario 1: Acceso a configuración de mantenimiento*</p><p>Dado que el personal administrativo necesita gestionar el calendario de mantenimiento,</p><p>Cuando accede a la sección de gestión de infraestructuras,</p><p>Entonces puede consultar y ajustar la programación del mantenimiento regular para cada instalación escolar.</p><p>*Escenario 2: Registro y documentación de mantenimiento*</p><p>Dado que se ha completado una actividad de mantenimiento en una de las infraestructuras,</p><p>Cuando el personal administrativo ingresa los detalles de esta actividad, incluyendo la fecha, el alcance y cualquier observación relevante,</p><p>Entonces el sistema actualiza el registro de mantenimiento, asociando esta nueva entrada con la infraestructura correspondiente.</p><p>*Escenario 3: Generación de reportes de mantenimiento*</p><p>Dado que el personal administrativo necesita revisar el historial de mantenimiento de una infraestructura,</p><p>Cuando solicita un reporte de mantenimientos para esa infraestructura,</p><p>Entonces el sistema compila y muestra un reporte detallando todas las sesiones de mantenimiento realizadas, incluyendo fechas, horas y descripciones.</p><p></p>|E02-US14|
|E02-US15|Programación de mantenimiento preventivo de la infraestructura.|<p>Como personal administrativo,</p><p>Quiero programar y gestionar el mantenimiento preventivo de la infraestructura escolar,</p><p>Para asegurar su funcionamiento eficiente y prolongar su durabilidad.</p>|<p>*Escenario 1: Planificación de mantenimiento preventivo*</p><p>Dado que el personal administrativo necesita organizar el mantenimiento preventivo,</p><p>Cuando accede a la sección de gestión de mantenimiento y selecciona una infraestructura,</p><p>Entonces puede visualizar las opciones para programar y gestionar las actividades de mantenimiento preventivo para esa infraestructura.</p><p>*Escenario 2: Programación de una actividad de mantenimiento preventivo específica*</p><p>Dado que es necesario programar una nueva actividad de mantenimiento preventivo,</p><p>Cuando el personal administrativo detalla y agenda esta actividad, especificando la fecha, responsable y descripción de las tareas,</p><p>Entonces el sistema registra la actividad, asegurando su inclusión en el calendario de mantenimiento preventivo.</p><p>*Escenario 3: Establecimiento de intervalos para mantenimientos preventivos*</p><p>Dado que el mantenimiento preventivo requiere ser realizado en intervalos regulares,</p><p>Cuando el personal administrativo establece y programa estos intervalos para una infraestructura específica, incluyendo una descripción de las tareas de mantenimiento,</p><p>Entonces el sistema organiza automáticamente las actividades de mantenimiento preventivo para ejecutarse en los intervalos designados.</p><p></p>|E02-US15|
|<p>E03: Control efectivo del inventario de útiles escolares</p><p></p><p>Como miembro del personal administrativo,</p><p>Quiero implementar un control y gestión detallados sobre el mantenimiento y equipos escolares,</p><p>Para asegurar su óptimo funcionamiento y administrar eficientemente los recursos.</p><p></p>||||<p>E03: Control efectivo del inventario de útiles escolares</p><p></p><p>Como miembro del personal administrativo,</p><p>Quiero implementar un control y gestión detallados sobre el mantenimiento y equipos escolares,</p><p>Para asegurar su óptimo funcionamiento y administrar eficientemente los recursos.</p><p></p>|
|E3-US05|Control del inventario de útiles escolares|<p>Como miembro del equipo administrativo,</p><p>Quiero administrar y actualizar el inventario de útiles escolares de forma efectiva,</p><p>Para asegurar la disponibilidad de recursos para estudiantes y profesores y gestionar las solicitudes de forma eficiente.</p>|<p>*Escenario 1: Registro de nuevos ítems en el inventario*</p><p>Dado que se han adquirido nuevos útiles escolares,</p><p>Cuando el personal administrativo registra estos ítems en el sistema con su información correspondiente,</p><p>Entonces el sistema actualiza el inventario para incluir estas nuevas adiciones.</p><p>*Escenario 2: Actualización de la cantidad de ítems existentes*</p><p>Dado que es necesario modificar la cantidad disponible de un ítem en el inventario,</p><p>Cuando el personal administrativo realiza ajustes en las cifras de los ítems específicos,</p><p>Entonces el sistema refleja las cantidades actualizadas en el inventario.</p><p>*Escenario 3: Recepción y registro de solicitudes de útiles escolares*</p><p>Dado que un profesor solicita útiles escolares para su aula,</p><p>Cuando realiza una solicitud de útiles a través del sistema, indicando los ítems y cantidades requeridas,</p><p>Entonces el sistema registra la solicitud y notifica al equipo administrativo para su revisión.</p><p>*Escenario 4: Confirmación de la solicitud*</p><p>Dado que una solicitud de útiles escolares ha sido aprobada por el equipo administrativo,</p><p>Cuando los útiles son asignados para su entrega al profesor solicitante,</p><p>Entonces el sistema actualiza el inventario reflejando la salida de los ítems y notifica al profesor sobre la confirmación de la solicitud y la fecha estimada de entrega.</p>|E3-US05|
|E3-US12|Registro y Gestión del Mantenimiento de la Infraestructura|<p>Como personal administrativo,</p><p>Quiero registrar y actualizar el estado del mantenimiento de la infraestructura escolar,</p><p>Para mantener un entorno seguro y funcional para todos en la institución.</p>|<p>*Escenario 1: Consulta de infraestructuras con mantenimiento pendiente*</p><p>Dado que el personal administrativo busca información sobre el estado actual del mantenimiento de infraestructuras,</p><p>Cuando accede a la sección de "Mantenimiento" y luego a "Infraestructura",</p><p>Entonces visualiza una lista detallada de todas las infraestructuras con mantenimiento pendiente.</p><p>*Escenario 2: Registro de nueva necesidad de mantenimiento*</p><p>Dado que se identifica una nueva necesidad de mantenimiento en alguna infraestructura,</p><p>Cuando el personal administrativo procede a registrar esta infraestructura, especificando el nombre y los detalles del mantenimiento necesario</p><p>Entonces la infraestructura se agrega a la lista de pendientes con toda la información relevante.</p><p>*Escenario 3: Actualización del estado de mantenimiento*</p><p>Dado que se requiere actualizar la información de mantenimiento de una infraestructura específica,</p><p>Cuando el personal selecciona esta infraestructura y modifica los detalles necesarios,</p><p>Entonces el sistema actualiza el registro para reflejar los cambios aplicados.</p><p>*Escenario 4: Confirmación de mantenimiento completado*</p><p>Dado que se ha completado el mantenimiento de una infraestructura,</p><p>Cuando el personal administrativo marca la tarea como completada en el sistema,</p><p>Entonces el sistema actualiza el estado de la infraestructura a "Mantenimiento Completado" y notifica al personal correspondiente.</p>|E3-US12|
|E3-US13|Presupuestos para el Mantenimiento de la Infraestructura|<p>Como personal administrativo,</p><p>Quiero crear y gestionar presupuestos para el mantenimiento de la infraestructura,</p><p>Para asegurar una planificación financiera y la disponibilidad de fondos para las actividades de mantenimiento.</p>|<p>*Escenario 1: Consulta de gestión de presupuestos*</p><p>Dado que el personal administrativo busca administrar los recursos financieros destinados al mantenimiento,</p><p>Cuando accede a la sección de presupuestos de mantenimiento en el sistema y selecciona una infraestructura,</p><p>Entonces visualiza y puede crear nuevos presupuestos, además de gestionar los existentes para la infraestructura elegida.</p><p>*Escenario 2: Registro de un nuevo presupuesto de mantenimiento*</p><p>Dado que hay una necesidad de establecer un nuevo presupuesto para mantenimiento específico,</p><p>Cuando el personal introduce y envía los detalles del nuevo presupuesto, incluyendo su propósito, el monto asignado, y la duración,</p><p>Entonces el sistema registra este nuevo presupuesto, facilitando su seguimiento y la asignación efectiva de recursos.</p><p>*Escenario 3: Actualización de presupuestos de mantenimiento*</p><p>Dado que es necesario ajustar los detalles de un presupuesto de mantenimiento ya existente,</p><p>Cuando el personal administrativo selecciona el presupuesto específico y actualiza la información necesaria,</p><p>Entonces el sistema aplica los cambios, asegurando que la planificación financiera se mantenga al día con las necesidades actuales.</p><p>Escenario 4: Aprobación y seguimiento de presupuestos</p><p>Dado que se ha creado o modificado un presupuesto de mantenimiento,</p><p>Cuando el personal administrativo revisa y aprueba este presupuesto,</p><p>Entonces el sistema actualiza el estado del presupuesto a "Aprobado" y permite el seguimiento del gasto en comparación con el presupuesto asignado.</p><p></p>|E3-US13|
|E3-US16|Registro y Mantenimiento del Equipo Escolar|<p>Como personal administrativo,</p><p>Quiero registrar y gestionar el mantenimiento del equipo escolar dentro de la plataforma,</p><p>Para asegurar un seguimiento efectivo y mantener los activos de la institución en óptimo estado.</p>|<p>*Escenario 1: Consulta del inventario de equipo escolar*</p><p>Dado que el personal administrativo necesita gestionar el equipo escolar,</p><p>Cuando accede a la sección correspondiente dentro del sistema,</p><p>Entonces visualiza el inventario completo, incluyendo detalles sobre el estado actual de mantenimiento de cada equipo.</p><p></p><p>*Escenario 2: Registro de nuevo equipo escolar*</p><p>Dado que se ha adquirido nuevo equipo necesario para la institución,</p><p>Cuando el personal introduce la información del equipo, como el nombre y los requisitos de mantenimiento, en la plataforma,</p><p>Entonces el sistema añade el equipo al inventario, facilitando su futuro seguimiento y mantenimiento.</p><p></p><p>*Escenario 3: Actualización de información sobre el equipo*</p><p>Dado que existe la necesidad de actualizar la información de mantenimiento para cierto equipo,</p><p>Cuando el personal selecciona el equipo y modifica los datos pertinentes,</p><p>Entonces el sistema actualiza la información, asegurando que el registro se mantenga al día.</p><p></p><p>*Escenario 4: Verificación del mantenimiento completado*</p><p>Dado que se ha completado una actividad de mantenimiento para un equipo específico,</p><p>Cuando el personal marca la actividad como finalizada en el sistema,</p><p>Entonces el sistema actualiza el estado de mantenimiento del equipo, reflejando que está en condiciones óptimas para su uso.</p>|E3-US16|
|E3-US17|Presupuestos para el mantenimiento del equipo escolar|<p>Como personal administrativo,</p><p>Quiero crear y gestionar presupuestos para el mantenimiento de los equipos escolares,</p><p>Para asegurar una planificación financiera adecuada y la disponibilidad de fondos necesarios para el mantenimiento.</p>|<p>*Escenario 1: Consulta y gestión de presupuestos para mantenimiento*</p><p>Dado que el personal administrativo está planificando las actividades de mantenimiento,</p><p>Cuando accede a la sección para gestionar el mantenimiento de equipos escolares,</p><p>Entonces el sistema le ofrece una interfaz clara para visualizar, generar y ajustar presupuestos para cada equipo escolar.</p><p>*Escenario 2: Creación de un nuevo presupuesto de mantenimiento*</p><p>Dado que se identifica la necesidad de un nuevo presupuesto para el mantenimiento de un equipo específico,</p><p>Cuando el personal administrativo ingresa la información necesaria y confirma la creación del nuevo presupuesto,</p><p>Entonces el sistema registra el nuevo presupuesto, mostrando detalles como descripción, período de validez y monto asignado, facilitando así su seguimiento y ejecución.</p><p></p><p>*Escenario 3: Actualización de presupuestos de mantenimiento existentes*</p><p>Dado que es necesario actualizar un presupuesto debido a cambios en los requisitos o costos estimados,</p><p>Cuando el personal administrativo selecciona un presupuesto existente y edita su información,</p><p>Entonces el sistema actualiza los detalles del presupuesto para reflejar los cambios, asegurando así que la planificación financiera se mantenga precisa y relevante.</p><p>*Escenario 4: Confirmación y seguimiento de presupuestos asignados*</p><p>Dado que se ha finalizado la asignación o actualización de un presupuesto para el mantenimiento,</p><p>Cuando el proceso de creación o edición concluye,</p><p>Entonces el sistema notifica al personal administrativo que el presupuesto ha sido correctamente actualizado, ofreciendo herramientas para el seguimiento y la implementación efectiva del presupuesto en las actividades de mantenimiento planificadas.</p>|E3-US17|
|E3-US18|Gestión de la frecuencia con la que se realiza mantenimiento del equipo|<p>Como personal administrativo, </p><p>Quiero gestionar la frecuencia y el registro de mantenimientos realizados al equipo escolar</p><p>Para asegurar su funcionamiento eficiente y prolongar su vida útil, facilitando así la continuidad en el uso de recursos esenciales para el aprendizaje.</p>|<p>*Escenario 1: Configuración de la Frecuencia de Mantenimiento*</p><p>Dado que el personal administrativo necesita establecer rutinas de mantenimiento para el equipo escolar,</p><p>Cuando acceden al sistema para definir o actualizar la frecuencia de mantenimiento de equipos específicos,</p><p>Entonces el sistema permite programar y visualizar dicha frecuencia, asegurando una gestión efectiva del mantenimiento.</p><p>*Escenario 2: Registro de Actividades de Mantenimiento Realizadas*</p><p>Dado que se ha completado un mantenimiento en particular para el equipo escolar,</p><p>Cuando el personal administrativo registra esta actividad en el sistema, proporcionando detalles como fecha, hora y acciones realizadas,</p><p>Entonces el sistema actualiza el historial de mantenimiento del equipo, reflejando la nueva entrada y manteniendo un registro accesible y detallado.</p><p>*Escenario 3: Generación de Reportes de Mantenimiento*</p><p>Dado que el personal administrativo requiere revisar el historial de mantenimientos para realizar seguimientos o auditorías,</p><p>Cuando solicitan un informe de mantenimientos realizados para un período específico o para equipos determinados,</p><p>Entonces el sistema genera un reporte detallado que incluye todas las actividades de mantenimiento, ofreciendo así una herramienta útil para la planificación y evaluación de la gestión de equipos.</p>|E3-US18|
|E3-US19|Programación de mantenimiento preventivo del equipo|<p>Como personal administrativo, </p><p>Quiero establecer y gestionar un calendario de mantenimiento preventivo para el equipo escolar, </p><p>Para prevenir interrupciones y asegurar la operatividad continua y eficiente de los recursos educativos.</p>|<p>*Escenario 1: Programar Mantenimiento Preventivo*</p><p>Dado que el personal administrativo busca prevenir fallos o daños en el equipo escolar mediante un mantenimiento oportuno,</p><p>Cuando acceden a la plataforma para programar nuevas actividades de mantenimiento preventivo especificando el equipo, fecha y detalles relevantes,</p><p>Entonces el sistema permite la creación de estas actividades de mantenimiento preventivo, asegurando su registro y seguimiento adecuados.</p><p>*Escenario 2: Consulta de Programaciones de Mantenimiento*</p><p>Dado que es necesario verificar las programaciones de mantenimiento preventivo establecidas para asegurar la cobertura de todos los equipos,</p><p>Cuando el personal administrativo consulta el calendario de mantenimiento en el sistema,</p><p>Entonces el sistema muestra todas las actividades de mantenimiento programadas, facilitando la gestión y ajuste de las mismas según sea necesario.</p><p>*Escenario 3: Establecimiento de Intervalos Regulares para Mantenimiento Preventivo*</p><p>Dado que algunos equipos requieren mantenimientos en intervalos regulares para su óptimo funcionamiento,</p><p>Cuando el personal administrativo establece intervalos de mantenimiento preventivo para equipos específicos,</p><p>Entonces el sistema automatiza la programación de estas actividades de mantenimiento basándose en los intervalos definidos, mejorando así la eficiencia en la gestión del mantenimiento.</p>|E3-US19|
|<p>E4: Interfaz de Usuario y Experiencia de Cliente</p><p></p><p>Como personal administrativo o profesor,</p><p>Quiero interactuar con una plataforma intuitiva y gestionar eficientemente horarios y asignaciones,</p><p></p><p>Para optimizar las operaciones diarias y mejorar la experiencia educativa.</p>||||<p>E4: Interfaz de Usuario y Experiencia de Cliente</p><p></p><p>Como personal administrativo o profesor,</p><p>Quiero interactuar con una plataforma intuitiva y gestionar eficientemente horarios y asignaciones,</p><p></p><p>Para optimizar las operaciones diarias y mejorar la experiencia educativa.</p>|
|E4-US06|Interfaz de Usuario Eficiente y Accesible|<p>Como personal administrativo,</p><p>Quiero interactuar con una interfaz intuitiva y organizada,</p><p>Para acceder eficientemente a la información y herramientas necesarias en la gestión escolar.</p>|<p>*Escenario 1: Acceso Inmediato a Herramientas Clave*</p><p>Dado que el personal administrativo ha iniciado sesión en la plataforma,</p><p>Cuando ingresa al panel principal,</p><p>Entonces encuentra una disposición clara de herramientas y accesos directos esenciales, organizados para facilitar su uso cotidiano.</p><p>*Escenario 2: Navegación Eficaz por la Plataforma*</p><p>Dado que el personal administrativo requiere gestionar variados aspectos de la escuela,</p><p>Cuando explora las secciones disponibles a través del menú de navegación,</p><p>Entonces experimenta una transición fluida y directa a la sección deseada, promoviendo una experiencia de uso sin complicaciones.</p>|E4-US06|
|E4-US09|Optimización de la Asignación de Horarios y Profesores|<p>Como personal administrativo,</p><p>Quiero estructurar y asignar horarios detallados para cada nivel educativo, así como asignar profesores específicos a cada curso,</p><p>Para asegurar una organización eficaz que respalde tanto la instrucción académica como el bienestar estudiantil.</p>|<p>*Escenario 1: Configuración de Horarios por Nivel Educativo*</p><p>Dado que el personal administrativo está habilitado en el sistema,</p><p>Cuando realiza la configuración de nuevos horarios, detallando el nivel educativo, el grado y la sección correspondiente,</p><p>Entonces el sistema habilita la distribución de cursos, la lista de alumnos matriculados y la designación de profesores</p><p>*Escenario 2: Asignación Efectiva de Profesores*</p><p>Dado que se ha creado un horario para un nivel, grado y sección específicos,</p><p>Cuando el personal administrativo procede a asignar profesores a los cursos designados,</p><p>Entonces el sistema confirma la asignación y actualiza la información del curso con los detalles pertinentes, incluyendo la relación de estudiantes inscritos.</p><p></p><p>*Escenario 3: Notificación a profesores sobre asignaciones*</p><p>Dado que un profesor ha sido asignado a un curso específico,</p><p>Cuando la asignación es finalizada en el sistema,</p><p>Entonces el profesor recibe una notificación, con todos los detalles necesarios sobre el curso, grado, sección y estudiantes asignados, facilitando su preparación para el inicio de clases.</p><p></p><p>*Escenario 4: Preparativos para el Nuevo Ciclo Escolar*</p><p>Dado que se prepara el inicio de un nuevo ciclo escolar,</p><p>Cuando el personal administrativo planifica y confirma las asignaciones de horarios, grados, secciones y profesores de acuerdo a la nueva estructura académica,</p><p>Entonces el sistema actualiza y comunica todas las asignaciones a los profesores implicados, permitiéndoles una preparación adecuada para el nuevo ciclo.</p>|E4-US09|
|<p>E5: Landing Page y Adquisición de Usuarios</p><p></p><p>Como visitante interesado en la plataforma,</p><p>Quiero navegar por una Landing Page informativa y accesible,</p><p>Para comprender las características principales del producto, evaluar su credibilidad a través de testimonios, entender las opciones de precios y facilidades de contacto.</p>||||<p>E5: Landing Page y Adquisición de Usuarios</p><p></p><p>Como visitante interesado en la plataforma,</p><p>Quiero navegar por una Landing Page informativa y accesible,</p><p>Para comprender las características principales del producto, evaluar su credibilidad a través de testimonios, entender las opciones de precios y facilidades de contacto.</p>|
|E5-US20|Características del Producto|<p>Como visitante interesado,</p><p>Quiero conocer las características principales de RocketNotes,</p><p>Para entender cómo puede facilitar la gestión en mi institución educativa.</p>|<p>*Escenario 1:Acceso a Información sobre el Producto*</p><p>Dado que un visitante accede a la Landing Page buscando información,</p><p>` `cuando consulta la sección "About our product", </p><p>entonces descubre descripciones detalladas de características como "Quality Products", "Optimized platform", y "Purchase insurance".</p>|E5-US20|
|E5-US21|Confirmación de la Confiabilidad a través de Reseñas|<p>Como potencial cliente,</p><p>Quiero ver testimonios y calificaciones de otros usuarios,</p><p>Para evaluar la credibilidad de RocketNotes.</p>|<p>*Escenario 1:Confirmación de la Confiabilidad a través de Reseñas*</p><p>Dado que un potencial cliente visita la Landing Page y desea validar la confiabilidad de RocketNotes, </p><p>cuando explora la sección "What our clients say about us",</p><p>` `Entonces encuentra testimonios y calificaciones positivas de usuarios actuales.</p>|E5-US21|
|E5-US22|Evaluación de Planes y Precios|<p>Como administrador escolar,</p><p>Quiero comprender las opciones de precios y sus beneficios,</p><p>Para seleccionar el mejor plan para mi escuela.</p>|<p>*Escenario 1: Consulta de Opciones de Planes*</p><p>Dado que el administrador escolar busca información sobre los planes disponibles, </p><p>Cuando accede a la sección "Affordable pricing" de la Landing Page, </p><p>Entonces visualiza una comparativa clara de los planes "Basic", "Premium", y "Expert", destacando precios y características incluidas.</p>|E5-US22|
|E5-US23|Facilidad de Contacto con la Empresa|<p>Como potencial cliente interesado en el producto,</p><p>Quiero contactar fácilmente a RocketNotes,</p><p>Para resolver mis dudas o recibir asesoramiento personalizado.</p><p></p>|<p>*Escenario 1: Acceso a Información de Contacto*</p><p>Dado que un visitante tiene preguntas o necesita asistencia, cuando busca cómo contactar a RocketNotes en la sección "Contact Us" de la Landing Page, entonces encuentra fácilmente datos de contacto como número de teléfono, dirección de correo electrónico y dirección física.</p>|E5-US23|
|E5-US24|Navegación Intuitiva en la Landing Page|<p>Como visitante interesado,</p><p>Quiero tener una navegación intuitiva en la Landing Page,</p><p>Para explorar fácilmente la información sobre RocketNotes.</p>|<p>*Diseño Claro y Accesible*</p><p>Dado que un visitante accede a RocketNotes por primera vez, </p><p>Cuando navega por la Landing Page, </p><p>Entonces se encuentra con un diseño que intuitivamente guía su atención hacia elementos clave como la barra de navegación, destacando secciones de información esenciales como características, precios y contacto, mediante el uso de iconografía familiar y etiquetas claras.</p><p>*Feedback Visual al Interactuar:* </p><p>Dado que un visitante interactúa con la barra de navegación o menús desplegables</p><p>Cuando elige una opción, </p><p>Entonces recibe feedback visual inmediato, como cambios de color o subrayado, que confirma su selección y le ayuda a navegar por la página sin confusión*.*</p>|E5-US24|
|E5-US25|Selección de Idioma en la Landing Page|<p>Como visitante internacional,</p><p>Quiero seleccionar mi idioma preferido en la Landing Page,</p><p>Para entender mejor la información sobre RocketNotes y sentirme más cómodo navegando</p>|<p>*Escenario 1:Visualización del Idioma Predeterminado*</p><p>*Dado que un visitante accede a la Landing Page de RocketNotes por primera vez,*</p><p>*Cuando este visitante observa la interfaz de usuario,*</p><p>*Entonces el sitio deberá mostrar el contenido en inglés por defecto, ofreciendo claramente la opción de cambiar el idioma a través de un selector visible.*</p><p></p><p>*Escenario 2:Cambio de Idioma a Español:*</p><p>*Dado que un visitante desea leer la información en su idioma preferido,*</p><p>*Cuando selecciona "Español" del selector de idioma en la Landing Page,*</p><p>*Entonces el contenido de la página, incluidas todas las secciones y menús, cambiará instantáneamente al español.*</p><p></p>|E5-US25|

## **3.3. Impact Mapping**

En esta sección, presentamos el Impact Mapping como herramienta estratégica para conectar las acciones de los User Personas con los objetivos del negocio digital. A través de fichas para cada persona, se identifican objetivos de negocio y se define cómo los User Personas deben cambiar o actuar para alcanzarlos. Las acciones del negocio para influir en estos cambios se detallan, y las Historias de Usuario resultantes orientan el desarrollo de las características del producto.

**Profesores**

Brindar un servicio de gestión, registro de notas y asistencia de los alumnos

![](Aspose.Words.a2067305-f689-47d5-8d76-971ef1bc2225.003.png)

Incrementar la eficiencia un 10% en la gestión, registro de notas y asistencia de los alumnos

![](Aspose.Words.a2067305-f689-47d5-8d76-971ef1bc2225.004.png)

**Administradores**

Brindar un servicio de gestión administrativa

![](Aspose.Words.a2067305-f689-47d5-8d76-971ef1bc2225.005.png)

Incrementar en un 10% la cantidad de administradores interesado en la aplicación

![](Aspose.Words.a2067305-f689-47d5-8d76-971ef1bc2225.006.png)

## **3.4. Product Backlog**

En este apartado del informe, nos adentramos en el concepto y la relevancia del Product Backlog en la metodología ágil. Descubrimos que el Product Backlog es una lista en constante cambio y priorizada de elementos que representan el trabajo futuro necesario para desarrollar un producto. Analizamos cómo se organiza y prioriza esta lista según el valor y las necesidades del negocio, así como su función esencial en la planificación de sprints y la toma de decisiones estratégicas para el desarrollo ágil de productos.

A continuación, se muestra nuestro Product Backlog elaborado:


![](Aspose.Words.a2067305-f689-47d5-8d76-971ef1bc2225.007.png)

**Trello:  [Product Backlog | Trello](https://trello.com/b/fHKD9Uys/product-backlog)**

|# Orden|User Story ID|Título|Descripción|Story Points (1 / 2 / 3 / 5/ 8)|
| :- | :- | :- | :- | :- |
|1|US24|Navegación Intuitiva en la Landing Page|<p>Como visitante interesado,</p><p>Quiero tener una navegación intuitiva en la Landing Page,</p><p>Para explorar fácilmente la información sobre RocketNotes.</p>|3|
|2|US22|Evaluación de Planes y Precios|<p>Como administrador escolar,</p><p>Quiero comprender las opciones de precios y sus beneficios,</p><p>Para seleccionar el mejor plan para mi escuela.</p>|3|
|3|US20|Características del Producto|<p>Como visitante interesado,</p><p>Quiero conocer las características principales de RocketNotes,</p><p>Para entender cómo puede facilitar la gestión en mi institución educativa.</p><p></p>|3|
|4|US23|Facilidad de Contacto con la Empresa|<p>Como potencial cliente interesado en el producto,</p><p>Quiero contactar fácilmente a RocketNotes,</p><p>Para resolver mis dudas o recibir asesoramiento personalizado.</p>|3|
|5|US06|Interfaz de Usuario Eficiente y Accesible|<p>Como personal administrativo,</p><p>Quiero interactuar con una interfaz intuitiva y organizada,</p><p>Para acceder eficientemente a la información y herramientas necesarias en la gestión escolar.</p>|5|
|6|US04|Gestión de las notas por aula|<p>Como profesor,</p><p>` `Quiero gestionar y registrar las notas de mis estudiantes de manera eficiente en cada evaluación. </p><p>Para asegurar un seguimiento preciso del rendimiento académico en las aulas asignadas</p>|3|
|7|US08|Seguimiento de progreso individual del estudiante|<p>Como profesor,</p><p>` `Quiero realizar un seguimiento del progreso académico de cada uno de mis estudiantes a lo largo del año</p><p>Para identificar áreas de mejora y proporcionar apoyo adicional según sea necesario.</p><p></p>|5|
|8|US07|Exportación de Reportes de Rendimiento Estudiantil|<p>Como personal administrativo</p><p>Quiero exportar reportes de rendimiento estudiantil en formatos compatibles con otras herramientas de análisis</p><p>Para facilitar la revisión y el análisis de datos a nivel institucional.</p>|3|
|9|US01|Gestión del aforo de las aulas|<p>Como miembro del equipo administrativo,</p><p>Quiero gestionar de manera efectiva el aforo de las aulas,</p><p>Para optimizar el espacio disponible y asegurar un entorno de aprendizaje adecuado.</p>|5|
|10|US10|Alertas de Indicadores de Rendimiento Bajo|<p>Como personal administrativo,</p><p>` `Quiero recibir alertas automáticas sobre estudiantes con rendimiento por debajo de lo esperado</p><p>Para facilitar intervenciones y apoyo adicional de manera oportuna.</p>|3|
|11|US02|Facilitación de la comunicación entre profesores y padres|<p>Como profesor,</p><p>Quiero comunicarme con los padres de mis estudiantes mediante un sistema de mensajería,</p><p>Para enviar correos electrónicos que informen sobre el progreso académico y asuntos relevantes relacionados con sus hijos.</p>|3|
|12|US09|Optimización de la Asignación de Horarios y Profesores|<p>Como personal administrativo,</p><p>Quiero estructurar y asignar horarios detallados para cada nivel educativo, así como asignar profesores específicos a cada curso,</p><p>Para asegurar una organización eficaz que respalde tanto la instrucción académica como el bienestar estudiantil.</p>|5|
|13|US03|Registro de asistencias|<p>Como profesor,</p><p>Quiero registrar la asistencia de mis estudiantes</p><p>Para tener el registro de cada clase y un control eficiente de la presencia estudiantil. </p>|1|
|14|US05|Control del inventario de útiles escolares|<p>Como miembro del equipo administrativo,</p><p>Quiero administrar y actualizar el inventario de útiles escolares de forma efectiva,</p><p>Para asegurar la disponibilidad de recursos para estudiantes y profesores y gestionar las solicitudes de forma eficiente.</p>|3|
|15|US16|Registro y Mantenimiento del Equipo Escolar|<p>Como personal administrativo,</p><p>Quiero registrar y gestionar el mantenimiento del equipo escolar dentro de la plataforma,</p><p>Para asegurar un seguimiento efectivo y mantener los activos de la institución en óptimo estado.</p>|5|
|16|US12|Registro y Gestión del Mantenimiento de la Infraestructura|<p>Como personal administrativo,</p><p>Quiero registrar y actualizar el estado del mantenimiento de la infraestructura escolar,</p><p>Para mantener un entorno seguro y funcional para todos en la institución.</p>|5|
|17|US15|Programación de mantenimiento preventivo de la infraestructura|<p>Como personal administrativo,</p><p>Quiero programar y gestionar el mantenimiento preventivo de la infraestructura escolar,</p><p>Para asegurar su funcionamiento eficiente y prolongar su durabilidad.</p>|5|
|18|US11|Gestión del aforo de las instalaciones escolares|<p>Como personal administrativo,</p><p>Quiero gestionar eficientemente la capacidad de las instalaciones escolares,</p><p>Para optimizar el espacio disponible, garantizar la seguridad y prevenir la sobrecarga en áreas comunes.</p>|3|
|19|US14|Gestión de la frecuencia con la que se realiza el mantenimiento de infraestructuras|<p>Como personal administrativo</p><p>Quiero administrar y configurar la frecuencia del mantenimiento de la infraestructura escolar</p><p>Para asegurar su óptimo estado y tomar decisiones basadas en un calendario de mantenimiento eficiente.</p>|3|
|20|US19|Programación de mantenimiento preventivo del equipo|<p>Como personal administrativo, </p><p>Quiero establecer y gestionar un calendario de mantenimiento preventivo para el equipo escolar, </p><p>Para prevenir interrupciones y asegurar la operatividad continua y eficiente de los recursos educativos.</p>|3|
|21|US18|Gestión de la frecuencia con la que se realiza mantenimiento del equipo|<p>Como personal administrativo, </p><p>Quiero gestionar la frecuencia y el registro de mantenimientos realizados al equipo escolar</p><p>Para asegurar su funcionamiento eficiente y prolongar su vida útil, facilitando así la continuidad en el uso de recursos esenciales para el aprendizaje.</p>|5|
|22|US17|Presupuestos para el mantenimiento del equipo escolar|<p>Como personal administrativo,</p><p>Quiero crear y gestionar presupuestos para el mantenimiento de los equipos escolares,</p><p>Para asegurar una planificación financiera adecuada y la disponibilidad de fondos necesarios para el mantenimiento.</p>|3|
|23|US13|Presupuestos para el Mantenimiento de la Infraestructura|<p>Como personal administrativo,</p><p>Quiero crear y gestionar presupuestos para el mantenimiento de la infraestructura,</p><p>Para asegurar una planificación financiera y la disponibilidad de fondos para las actividades de mantenimiento.</p>|3|
|24|US21|Confirmación de la Confiabilidad a través de Reseñas|<p>Como potencial cliente,</p><p>Quiero ver testimonios y calificaciones de otros usuarios,</p><p>Para evaluar la credibilidad de RocketNotes.</p>|3|
|25|US25|Selección de Idioma en la Landing Page|<p>Como visitante internacional,</p><p>Quiero seleccionar mi idioma preferido en la Landing Page,</p><p>Para entender mejor la información sobre RocketNotes y sentirme más cómodo navegando.</p>|1|

﻿### **Capítulo IV: Product Design** 

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
