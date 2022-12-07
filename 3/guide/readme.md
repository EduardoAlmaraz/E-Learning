# Guía 3er Parcial

## Índice

- [Guía 3er Parcial](#guía-3er-parcial)
  - [Índice](#índice)
  - [Moodle](#moodle)
    - [Configuración de Moodle](#configuración-de-moodle)
      - [Cambiar el nombre del sitio y la información de los cursos](#cambiar-el-nombre-del-sitio-y-la-información-de-los-cursos)
    - [Categorías](#categorías)
      - [Añadiendo una categoría](#añadiendo-una-categoría)
    - [Cursos](#cursos)
      - [Añadir un curso](#añadir-un-curso)
      - [Eliminar un curso](#eliminar-un-curso)
      - [Actividades](#actividades)
        - [Tareas](#tareas)
        - [BigBlueButton](#bigbluebutton)
        - [Chat](#chat)
        - [Elección (Consulta en el Español internacional)](#elección-consulta-en-el-español-internacional)
        - [BasedeDatos](#basededatos)
        - [Retroalimentación](#retroalimentación)
        - [Foro](#foro)
        - [Glosario](#glosario)
        - [H5P](#h5p)
        - [Lección](#lección)
        - [(LTI) Herramienta externa](#lti-herramienta-externa)
        - [Examen (Cuestionario en el Español internacional)](#examen-cuestionario-en-el-español-internacional)
        - [SCORM](#scorm)
        - [Encuesta predefinida](#encuesta-predefinida)
        - [Wiki](#wiki)
        - [Taller](#taller)
    - [Usuarios](#usuarios)
      - [Roles](#roles)
        - [Roles Estándar](#roles-estándar)
    - [Participantes](#participantes)

## Moodle

### Configuración de Moodle

#### Cambiar el nombre del sitio y la información de los cursos

1. Ingrese con su cuenta de administrador
2. En el panel izquierdo (el Cajón de Navegación) haga clic en Administración del sitio
3. Baje hasta la sección de Portada y haga clic en Configuraciones de Portada
4. Cambie aquí el **nombre largo** y el **nombre corto** de su sitio.
5. Decida cuales ítems serán mostrados a los usuarios que no hayan ingresado al sitio y a los que ya hayan ingresado de los dos menúes desplegables.
6. Haga Clic en Guardar cambios

### Categorías

Las categorías de cursos organizan cursos para todos los participantes del sitio Moodle. La categoría de curso predeterminada en un nuevo sitio de Moodle es "Top" (aunque se le puede cambiar el nombre) Un Creador de curso, Administrador o Mánager puede poner todos los cursos en la categoría Top. Sin embargo, a los profesores y estudiantes les resultará más fácil encontrar sus clases si están organizadas en categorías descriptivas.

La lista de cursos dentro de una categoría por defecto muestra los profesores y el resumen de cada curso. Si el número de cursos dentro de una categoría supera los 9 (10 o más), se muestra una lista breve sin profesores y un resumen.

#### Añadiendo una categoría

La mayoría de las personas organizan sus cursos por departamentos y colegios, o por temas. Asegúrese de probar los esquemas organizacionales con unos pocos usuarios, antes de registrar una gran cantidad de cursos, para ahorrar tiempo moviéndolos luego

Añadir categorías es muy fácil:

Ir a "Administración" > "Administración del sito" > "Cursos" > "añadir una categoría"
Complete los detalles requeridos y de clic en "Crear categoría"
Otra forma de lograrlo es yendo a "Administración" > "administración de sitio" > "Administrar cursos y categorías" y de clic en el link "Crear una nueva categoría".

### Cursos

Los cursos son los espacios de Moodle en donde los profesores añaden materiales para el aprendizaje para sus alumnos. Los cursos son creados por administradores, creadores de curso o mánagers. Los maestros pueden entonces añadir el contenido y re-organizarlos de acuerdo a sus propias necesidades.

#### Añadir un curso

Por defecto, un maestro regular no puede añadir un nuevo curso. Para añadir un nuevo curso a Moodle se requiere tener derechos de Administrador, Creador de curso o Mánager (gestor). Para añadir un curso:

Desde el enlace de la Administración del sitio, haga clic en Cursos > Gestionar cursos y categorías

Haga clic en Nuevo curso en la página de categoría a la derecha
Elija la categoría en donde Usted quiere poner su curso. Para más información, vea Categorías de curso
Elija el enlace para "Nuevo curso"
Entre a Configuraciones del curso, y después, elija o bien, el botón para "Guardar y regresar" para regresar al curso, o elija "Guardar y mostrar" para ir a la pantalla siguiente
newcoursesavereturn.png

En la pantalla siguiente, si Usted ha elegido "Guardar y mostrar" elija a sus alumnos y maestros para asignarlos al curso.

#### Eliminar un curso

Los maestros no pueden eliminar cursos. Los administradores y mánagers (gestores) (usuarios con un rol que tenga permitida la capacidad de moodle/course:delete permitida) pueden eliminar cursos y los creadores de cursos pueden eliminar los cursos que ellos mismo ha creado, pero solamente dentro de las 24 horas de haber creado el curso. esto es para que los cursos que hubieran sido creados por error puedan ser eliminados sin necesidad de pedírselo a un administrador.

> Los administradores siempre pueden eliminar cursos.

Para eliminar un curso (como administrador o Mánager):

1. Desde el enlace de la Administración del sitio, haga clic en Cursos > Gestionar cursos y categorías
2. Haga clic en la categoría del curso y elija el curso en la pantalla a la derecha..
3. Haga clic en el ícono para Eliminar.

Usted puede eliminar varios cursos al:

- Crear una nueva categoría (temporal). Le puede llamar "Para ser eliminados".
- Seleccionar y mover los cursos que serán eliminados a la categoría "Para ser eliminados" .
- Eliminar la categoría ( "Para ser eliminados") y elegir "Eliminar TODO - no puede deshacerse".

> No hay una interfase de usuario para que los creadores de curso puedan eliminar los cursos que hayan creado. Sin embargo, pueden hacerlo al editar la URL del curso de http://susitiomoodle.net/course/view.php?id=N a http://susitiomoodle.net/course/delete.php?id=N (remplazando 'view' (ver) por 'delete' (eliminar)).

#### Actividades

Actividades
Una actividad es un nombre general para un grupo de características en un curso Moodle. Usualmente una actividad es algo que un estudiante hará, que interactúa con otros estudiantes o con el maestro.

En la terminología de Moodle, una Actividad, como por ejemplo, Foro o Examen, significa propiamente algo a lo que los estudiantes pueden contribuir directamente, y a menudo es contrastada con un recurso, como por ejemplo un archivo o una página, el cual es presentado por el profesor a los alumnos. Sin embargo, el término actividad en ocasiones por conveniencia también es usado para referirse tanto a Actividades como Recursos como un grupo.

Hay 15 diferentes tipos de actividades en Moodle 2.x y 3.x estándar, y se pueden encontrar cuando Usted activa la edición y elige el enlace para Añadir una actividad o recurso, que invocará al Selector de actividades.

Los administradores pueden decidir si es que desean o no forzar a los profesores a que añadan descripciones para cada actividad al habilitar o deshabilitar una configuración para todo el sitio en Administración > Plugins > Módulos de actividad > Configuraciones comunes

##### Tareas

Les permite a los maestros calificar y hacer comentarios sobre archivos subidos y tareas creadas en línea y fuera de línea

##### BigBlueButton

Haga sesiones de video conferencias en vivo dentro de Moodle

##### Chat

Les permite a los participantes tener una discusión sincrónica en tiempo real

##### Elección (Consulta en el Español internacional)

Un maestro hace una pregunta y especifica una variedad de respuestas de opción múltiple

##### BasedeDatos

Les permite a los participantes crear, mantener y buscar dentro de un banco de entradas de registros

##### Retroalimentación

Para crear y conducir sondeos para colectar retroalimentación (En versiones anteriores a Moodle 3.3 el administrador necesitaba habilitar esto).

##### Foro

Les permite a los participantes tener discusiones asincrónicas.

##### Glosario

Les permite a los participantes crear y mantener una lista de definiciones, a semejanza de un diccionario

##### H5P

Permite que el contenido H5P creado en el Banco de contenido o en h5p.com o con la [lumi App App Lumi] sea fácilmente añadido a un curso como una actividad..

##### Lección

Para proporcionar contenido en formas flexibles.

##### (LTI) Herramienta externa

Les permite a los participantes interactuar con recursos y actividades de enseñanza compatibles con LTI en otros sitios web.

##### Examen (Cuestionario en el Español internacional)

Le permite al maestro diseñar y armar exámenes, que pueden ser calificados. automáticamente o se puede dar retroalimentación o mostrar las respuestas correctas.

##### SCORM

Permite que se incluyan paquetes SCORM como contenido del curso.

##### Encuesta predefinida

Para recolectar datos de los estudiantes, para ayudarle a los maestros a conocer sus alumnos y reflexionar sobre su enseñanza.

##### Wiki

Una colección de páginas web en donde cualquiera puede añadir o editar.

##### Taller

Habilita la evaluación por pares.
Adicionalmente pueden instalarse complementos (plugins adicionales) desde la base de datos del subdirectorio de Plugins de Moodle para añadirlos a su sitio.

### Usuarios

Un administrador puede realizar varias tareas relacionadas con cuentas de usuario en Configuraciones > Administración del sitio > Usuarios > Cuentas. Estas son algunas tareas que puede realizar:

- Ojear lista de usuarios - cómo buscar, encontrar y editar cuentas de usuarios.
- Acciones masivas con usuarios - cómo mandar mensajes, confirmar, descargar, o realizar otras acciones globalmente, sobre un gran grupo de usuarios.
- Añadir un nuevo usuario - cómo crear una cuenta individual de usuario.
- Campos del perfil de los usuarios - cómo crear campor personalizados de perfil.
- Subir usuarios - cómo crear nuevas cuentas de usuarios de manera masiva a través de un archivo CSV.
- Subir imágenes de usuarios - cómo subir en lotes imágenes de usuarios para sus perfiles
- Campos de nombre adicionales

#### Roles

##### Roles Estándar

|Rol|Atribuciones|
|-|-|
|Administrador del sitio|puede "hacer todo" en el sitio|
|Mánager (Gestor)|un rol de administrador menor|
|Creador de curso|puede crear cursos|
|Profesor (maestro)|puede gestionar y añadir contenidos a los cursos|
|Profesor no-editor (maestro sin permiso de edición)|puede calificar dentro de los cursos, pero no puede editarlos|
|Estudiante|puede acceder y participar en cursos|
|Invitado|puede ver cursos, pero no participa|
|Usuario autenticado (usuario identificado)|el rol que tienen todos los usuarios que ingresaron al sitio|
|Rol de usuario autentificado en la portada|un rol de usuario que ingresó al sitio, pero solamente para la portada del sitio|

### Participantes

Preguntas acerca de cómo ver los participantes de un curso y cómo agregarlos.