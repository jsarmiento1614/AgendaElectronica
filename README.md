# AgendaElectronica
Alumnos del III de Informática del instituto Hosanna2018, implementaran metodologia Scrumm para organizarse y desarrollar el proyecto agenda electronica, el cual consiste en llevar el control personal de los eventos. 

1.Definición del problema.
-------------------------------------------Agenda Electrónica --------------------------------------------

                                    Controlar y administrar eventos
2. Análisis del problema.
La agenda electrónica tiene el propósito de controlar y administrar eventos, el usuario podrá
iniciar sesión con una clave maestra dada por el departamento de IT del software, en caso de que
el usuario ingrese una contraseña equivocada a la permitida, el sistema dará un mensaje de alerta
a la falla de la contraseña ingresada y le notificará que solo cuenta con 3 intentos de inicio de
sesión, al completar los intentos permitidos el sistema se bloqueará por 2 minutos, de continuar
con el mismo error de inicio de sesión, volverá a bloquearse por 5, 30, 1000000 minutos.
Al acertar con la clave correcta el usuario accederá al sistema, el usuario se encontrará con una
ventana de: “BIENVENIDO AL SISTEMA ERES EL USUARIO #__”.
Diciéndole el número de usuario que ha accedido al sistema y habrá una opción que dirá “INICIAR
AHORA S/N”.
Al ingresar “N” saldrá al menú de inicio de sesión (Ojo, sin cerrar la ejecución del programa), si la
opción es “S” accederá al sistema, ya dentro, el usuario se encontrará con un menú que constará
de lo siguiente.

Agenda Electrónica

Inst. Hosanna 2018
Menú de control de eventos:
1) Crear eventos.
2) Ver eventos.
3) Salir
Opción crear evento:
Contará con los siguientes campos:
Fecha del Evento: Validará si la fecha ingresada es correcta. (La fecha ingresada no cumple el
formato o es una fecha pasada).
Título del evento:
Detalles del evento:
Ubicación del Evento
Hora Inicio del Evento: (Validará si la hora es válida, utilice el formato 24 horas).
Hora Fin del Evento: (Validará si la hora es válida, utilice el formato 24 horas).
Luego de introducir la información, se le preguntará al usuario si la información introducida es
correcta. De no ser así volverá a introducirla nuevamente.
Eje: ¿Su información es correcta?, Desea Registrarla. (S/N)
Si es correcta toda esa información será almacenada en un array, para luego ser utilizada más
adelante (Recuerde que esa información estará en el array mientras el programa este corriendo de
no ser así se perderá).
NOTA: Recomiendo utilizar una clase única donde almacenara todas las variables y array para una
mejor claridad en la programación.
Opción ver eventos:
Mostrará todos los eventos introducidos por el usuario que inició sesión de forma ordenada (Se
mostrará estilo tabla).
Opción Salir
Cerrará la sesión que inició el usuario, pero no terminará el programa.
REALIZAR: Se exige utilizar clases, constructores, getter y setter, en el desarrollo del
proyecto, almacenado las variables en esa clase creándolas todas privadas y mandándole
los parámetros a través de los setter o constructores y retornándolas a través de los
getter.

3. Diseño del problema.
a. (Utilizar diagrama de flujo y seudocódigo para representar el algoritmo del
problema). Recomiendo PseInt para realizar el seudocódigo y Diagrama,
(Buscar en Youtube).

Inst. Hosanna 2018
4. Desarrollo del software.
a. Realizarlo en el lenguaje java a base de consola.
5. Pruebas del software.
a. En esta etapa realizarán el Testín completo del software antes de su
implementación, velarán que el código haga lo que está declarado en las rúbricas
de desarrollo.

6. Implementación del software.
a. En esta fase mostrarán el software completo y sin errores, defendiendo su
desarrollo tanto el código (Software Source, Github) como organización (Scrum).
Culminando con la presentación del software.
Nota: defender significa explicar a detalle todo el proceso llevado para realizar su
proyecto, ¡¡¡ojo!!! No es una explicación cualquiera.

Metodologías a usar en el desarrollo del software.

Scrum

Utilizar el cliente Scrum canbanflow para trabajar en el proyecto de forma ordenada y
dividiendo a la más mínima tarea su problema. Recomiendo utilizar esta metodología de
desarrollo, recuerden lo visto en la exposición. Ustedes decidirán quién será el Scrum
Master, y elijan a un miembro del Team para que tome el rol de testing del software.

GitHub

Utilizar el repositorio de código, para ir subiendo los avances de su proyecto y trabajar más
ordenadamente en el desarrollo del mismo.
El Scrum Master será el encargado de crear la rama master y añadir a los miembros del
Team, (Debe de darle privilegios como colaboradores a los miembros del Team “Buscar
Youtube”).

Defensa del Proyecto

----------------------------------------------- Diapositiva -----------------------------------------------
---Diapositivas no cargadas de información solo se permiten 2 reglones por Slide.

Inst. Hosanna 2018
-- Deberá de contener la misma fuente para el texto. (Solo los títulos puede ser fuente diferente)
-- Contará con ilustración agradable cada Slide, evitando Imágenes estiradas, Imágenes con fondo,
(Usar preferiblemente PNG), e imágenes pixeladas.
-- El texto debe ser claro visualmente, así como su sintaxis.

Nota: Espero que cumplan en su totalidad las rubricas para una mejor experiencia de desarrollo.
