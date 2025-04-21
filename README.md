# Configuración

## Ajustes generales

### 1. Iniciar sesión  .

Primero de todo iniciaremos sesión en el moodle con nuestro usuario y contraseña. Los primeros pasos seran cambiar nuestra foto de perfil, nuestro correo y nuestra contraseña.
Para ello entraremos en nuestro icono de perfil y nos saldra un boton llamado "Perfil" ahi podremos editar nuestras cosas a nuestro gusto. Debera de quedar asi:

<img src="Perfil.png" alt="">

### 2. Idioma 

Ahora haremos el cambio de idioma, para ello deberemos entrar en la administración del sitio webl, ir al apartado idioma y entrar en la pestaña parametros. Una vez alli cambiamos la pestaña donde nos sale idioma. Si no sale deberas instalarlo en el apartado paquetes de idioma.

<img src="Idioma.png" alt="">

### 3. Contraseñas 

Para el tercer paso deberemos cambiar la contraseña de nuestro portal. Añadiendo que como minimo tenga 4 letras, que haya una mayuscula y algun numero. Esto se hace desde administración, vamos al apartado de seguiridad y a las normativas del sitio.

En la siguiente imagen se vera donde debemos poner los parametros para conseguir lo que necesitamos 

<img src="Contraseña.png" alt="">

## Gestión de cursos

### Creación de cursos

Primero empezaremos creando el curso A, donde deberemos ponerle tres temas. Que esto se hace desde administración del sitio, en el apartado cursos y categorias o desde Navegación, en el apartado cursos y haciendo clic en añadir curso.

Después de haberlo creado, para añadir los temas dentro de curso nos saldra una pestaña donde pondra añadir temario o tareas. desde ahi añadimos los temas que necesitemos (en este caso 3) y deberia quedar asi.

<img src="Curso A.png" alt=""> 

Para el curso B haremos los mismos pasos que con con el pero en el momento de añadir temas en vez de 3 añadiremos 5. 

<img src="Curso B.png" alt="">

### Añadir material al curso

Para esto deberemos entrar en los temas previamente creados y hacer lo mismo que para crear los temas. Vamos al apartado de añadir dentro del tema seleccionado y nos saldra un menú

<img src="crear tarea 1.png" alt="">

Y aqui añadimos lo que queramos. 

<img src="Crear tarea 2.png" alt="">

Finalmente deberia verse asi.

<img src="Documentos en Curso.png" alt="">

## usuarios y alumnos

### Creación del primer usuario

Crearemos al alumno Bob. Esto lo podemos hacer en la administriación, en la pesatña usuarios, yendo a cuentas y a añadir usuario.

Desde alli nos saldra una serie de pasos que completar con la inforamción, contraseña y mas cosas para añadir al usuario. 

Cuando este añadido debera de quedar asi.

<img src="Creación primer usuario.png" alt="">

### Creación 10 alumnos (CSV)

Para crear 10 alumnos de manera inmediata, deberemos hacerlo desde un archivo CSV. 
Esto se indica de la siguiente manera, cogemos el archivo, ponemos que estructura queremos y completamos la estructura con los alumnos que queramos añadir.

Nuestra estructura sera nombre de usuario, primero nombre, apellido, correo electronico y contraseña

Seguidamente cargamos el archivo, yendo a administración - Usuarios - Cuentas - Añadir usuarios. Cargamos nuestro archivo y quedara así.

<img src="10 usuarios creados.png" alt="">

### Borrar un usuario

Esta tarea es bastante sencilla, pero iremos paso a paso.

Entraremos en la sección de usuarios desde la administración del sitio. Donde nos saldran los 10 usuarios. Seleccionamos el usuario que queremos borrar.


<img src="Borrar usuario 1 .png" alt="">

Seguidamente haremos clic en los tres puntos que salen al final del nombre del usuario seleccionado y nos saldra un recuadro con la opción de borrar. Hacemos clic en "Borrar".

<img src="Borrar usuario 2 .png" alt="">


Finalmente, saldra una confirmación de si estamos seguros de ejecutar la acción. Confirmamos y el usuario sera borrado.


<img src="Borrar usuario 3 .png" alt="">

## Matriculación y configuración de cursos

### 5. Matrícula y permisos en cursos

#### Configuración de métodos de inscripción

Para el curso A, desactivamos todas las inscripciones para que el acceso sea libre como visitante. Esto lo hacemos entrando a:

Administración del curso > Usuarios > Métodos de inscripción  
Desactivamos todos los métodos excepto Acceso como invitado y activamos la opción de entrada sin contraseña.

<img src="Curso A desbloqueada.png" alt="">

Para el curso B, habilitamos solo la inscripción manual. Así, solo nosotros como administradores podremos inscribir usuarios.

<img src="Curso B bloqueado" alt="">

#### Asignar roles

Asignamos a Bob como profesor del curso B entrando a:  
Administración del curso - Usuarios inscritos - Inscribir usuarios  
Buscamos a Bob y le asignamos el rol de Profesor.

<img src="cambio rol" alt="">


<img src="Hacer profesor gg.png" alt="">

Luego cargamos el archivo CSV con los 10 alumnos y los inscribimos manualmente al curso B con el rol de Estudiante.

<img src="Matriculacion 1.png" alt="">

Y despues de este paso selecionamos a los alumnos que queremos añdir y hacemos clic en "Añadir"

<img src="Matriculacion 2.png" alt="">

#### Comprobación del acceso

Entramos como visitante y comprobamos que el curso A se puede visualizar sin iniciar sesión. Como hemos visto anteriormente pero desdel punto de vista de un alumno.

<img src="Curso A desbloqueada.png" alt="">

Después, intentamos entrar al curso B sin iniciar sesión y Moodle nos pedirá autenticación.

<img src="Auto matricula" alt="">

### 6. Apariencia del sitio

Entramos a:  
Administración del sitio - Plugins - Instalar complemento 
Subimos el archivo `.zip` del nuevo tema descargado desde el sitio oficial de Moodle.

Una vez instalado, vamos a:  
Administración del sitio - Apariencia - Temas - Selector de temas  
Y seleccionamos el nuevo tema.

(En este paso mi moodle no podia cargar los temas, por ello la imagen solo muestra como hacerlo y no el resultado final.)

<img src="Temas.png" alt="">

### 7. Asignar profesor y alumnos al curso A

Asignamos un nuevo profesor al curso A repitiendo el proceso de inscripción manual desde:  
Administración del curso - Usuarios inscritos - Inscribir usuarios

<img src="Hacer profesor gg.png" alt="">

Luego añadimos manualmente a los alumnos (pueden ser los mismos del CSV o nuevos).

<img src="Matriculacion 2.png" alt="">


### 8. Añadir contenido desde el rol de profesor

Iniciamos sesión como el profesor asignado al curso A y activamos la edición.  
Agregamos actividades desde los temas ya creados.

<img src="crear tarea 1.png" alt="">

Creamos una Tarea que permita subir un archivo PDF con una fecha de entrega abierta:

- Tipo de entrega: Subida de archivos
- Formato permitido: PDF
- Fecha de entrega: configurada manualmente

<img src="Crear tarea 2.png" alt="">

Seguidamente seguimos los pasos que nos piden y guardamos los cambios

<img src="Crear tarea 3.png" alt="">

Finalmente el resultado es el siguiente

<img src="Crear tarea 4.png" alt="">

### 9. Entregar tarea como alumno

Entramos con un alumno registrado, accedemos al curso A y seleccionamos la tarea creada.  
Subimos un archivo PDF desde el botón "Agregar entrega".

Una vez entregado, se muestra la confirmación de entrega y el botón para modificar si es necesario.

<img src="confirmar si se puede entregar.png" alt="">

## Contenidos

### Crear una UF con 2 NF 

Entramos en el curso A y activamos la edición con el botón "Activar edición" (arriba a la derecha).

Cambiamos el formato del curso a "Temas" desde:  
Administración del curso > Editar ajustes > Formato del curso

Para crear una UF (Unidad Formativa):

- Añadimos una etiqueta con el nombre de la UF.
- Añadimos dos temas como NF debajo.
- Arrastramos los elementos hacia la derecha para jerarquizarlos visualmente dentro de la UF.

<img src="Uf y dos Nf.png" alt="">

## Calificación

### Completar tareas y calificar

Entramos con un alumno, accedemos al curso A y completamos todas las actividades evaluables (entrega de tarea y cuestionario).

Después, entramos como profesor y calificamos las tareas desde el libro de calificaciones o directamente en cada actividad.

Luego configuramos el calificador para que calcule automáticamente la nota de la UF:

<img src="Calificación correcta de tarea.png" alt="">

### Crear y otorgar una insignia

Vamos a:

Administración del sitio - Insignias - Añadir nueva insignia

Configuramos los criterios (por ejemplo, completar la UF o recibir una nota mínima).

Una vez creada, la otorgamos al alumno que ha completado todas las actividades.

<img src="Insignias.png" alt="">


## Cuestionarios

### Crear banco de preguntas y cuestionario

Primero entramos en:

Administración del curso - Banco de preguntas

Creamos varias categorías (por ejemplo: Teoría, Práctica) y dentro añadimos preguntas de tipo opción múltiple, verdadero/falso, respuesta corta, etc.

<img src="Banco de preguntas.png" alt="">

Luego creamos un cuestionario desde “Añadir actividad o recurso” y seleccionamos las preguntas desde el banco.

<img src="Banco de preguntas segunda catg.png" alt="">

Accedemos como alumno, respondemos al cuestionario, y luego como profesor vemos los resultados desde:

Administración del curso > Calificaciones

<img src="responder_cuestionario.png" alt="">
<img src="ver_calificacion_cuestionario.png" alt="">

---

## Importar y exportar un curso

### Exportar (copia de seguridad)

Desde:

**Administración > Copias de seguridad**

Seleccionamos qué partes del curso queremos guardar y descargamos el archivo generado `.mbz`.

<img src="exportar_curso.png" alt="">

Ese archivo se lo enviamos a un compañero.

### Importar curso de otro compañero

Vamos a:

**Administración > Restaurar**  
Subimos el archivo `.mbz` recibido y seguimos los pasos para importar el curso en nuestro Moodle.

<img src="importar_curso_externo.png" alt="">


















