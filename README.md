# odiJuanAlberto
U3 Entorno de Desarrollos - Práctica Odisea en el repositorio

Objetivo

    Crear una cuenta en la plataforma github para utilizarla durante el curso.
    Conocer el uso de la plataforma github.
    
    Tarea

1.- Crea una nueva cuenta en la plataforma GitHub.

Crea un nuevo repositorio llamado odi+tu_nombre .El respositorio se aconseja que sea público gratuito.

Recuerda las claves de acceso.

Tarea II

Crea un nuevo proyecto HTML5/js en el IDE NetBeans (posiblemente sea necesario instalar el complemento indicado en una tarea anterior).

En la carpeta "site root" raiz del proyecto, crea una nueva carpeta llamada "datos".

Recuerda que la estructura del proyecto que se muestra en la parte derecha de NetBeans, corresponde a una organización de diferentes documentos que forman el proyecto.

Utiliza las diferentes vístas que permite ("proyectos", "archivos", "prestaciones") para localizar la carpeta creada.

Inicia el control de versiones con Git en el proyecto. Botón derecho sobre el nombre del proyecto, opción "versioning" y luego "Initialize Git repository...".

Se habrán añadido al control de versiones todos ficheros del proyecto. Aparecen de color verde, y si colocas el ratón sobre ellos, aparece una etiqueta con el mensaje en verde "Added/".

Crea un nuevo fichero vacío de texto, con el nombre "viaje.txt", dentro de la carpeta datos.

Añade el nuevo fichero "viaje.txt" al repositorio. Pulsa con el botón derecho sobre él fichero "Git" - "Add". Comprueba que cambia de color, ahora se muestra verde.

Realiza un commit con el comentario "Primera versión".

Crea una nueva rama llamada "mas_alla". Utiliza la opción del menú "Team" - "Branch/Tag" - "Create branch...".

Situado en la rama "mas_alla", copia los versos 1 y siguientes, y los versos 13 y siguientes en el documento viaje.txt. Realiza un commit con los cambios, con el comentario "Llegando a tierra".

Copia, a continuación, en el fichero viaje.txt los versos 51 y siguientes. Realiza un commit con el comentario "Primer encuentro".

Crea una nueva rama llamada "magia". Trabajando en esta, añade al documento viaje.txt, entre el segundo y tercer párrafo, los versos 23 y siguientes.

Realiza un commit con el comentario "Procedimiento adecuado".

Cambia a la rama "mas_alla". "Team" - "Branch/Tag" - "Switch to branch... " y selecciona la rama de la lista.

Trabajando en esta última rama, copia el verso 404 y siguientes al final del documento viaje.txt.

Realiza un commit y pon el comentario "Agamemnon".

Crea una nueva rama llamada "madre".

Trabajando en la rama "madre", copia el verso 181 y siguientes antes del último párrafo, en el fichero viaje.txt.

Realiza un commit con el comentario "primera informacion".

Cambia a la rama "mas_alla". Crea una nueva rama llamada "guerreros".

Trabajando en la rama "guerreros".  Copia el verso 477 y siguientes al final del documento viaje.txt.

Realiza un commit con el comentario "Aquileo".

Trabajando en la rama "guerreros".  Copia el verso 553 y siguientes al final del documento viaje.txt.

Realiza un commit con el comentario "Ayante".

Cambia a la rama "mas_alla". Unifica o mezcla esta rama con la rama "guerreros". "Team" - "Branch/Tag" - "Merge revision...". Aparece una ventana donde es posible indicar las opciones para realizar la mezcla de las ramas. Utilizando el botón "Select" elige la rama "guerreros".

El resultado de la mezcla (o merge), será una versión del fichero "viaje.txt" que contiene toda los datos de las dos ramas (sin conflictos).

De manera similar a la anterior operación. Realiza la mezcla de la rama "mas_alla" con la rama "madre".

En este caso ocurre un conflicto, es decir hay líneas del documento que tienen diferente contenido en las versiones de cada rama.

Aparece un aviso. No es un error, es un aviso para resolver el conflicto de manera manual.

Atención, en este punto de aviso, aparecen 3 opciones para resolver las líneas en conflicto, pero hay que tener en cuenta que las líneas que no tienen conflicto y sí pueden mezclarse se mezclan !!!

Elige el botón "Resolve", para resolverlos manualmente. Aparece una ventana con los fragmentos en conflicto de cada la versión del fichero en cada rama. Las decisiones se toman por bloques. En este caso hay varias líneas en conflicto. Pulsando sobre los botones superiores, podemos observar cuál será el resultado final en cada caso.

El botón "Aceptar", elige una de las dos opciones y descarta la otra. No utilices esta opción.

El botón "Accept both" coloca primero en fichero el la versión seleccionada y a continuación la otra versión.

El botón "Aceptar y siguiente", elige una de las líneas y localiza el siguiente bloque de conflicto.

Pulsa el botón "Accept Both" en la versión de la rama "madre". Observa que quede duplicada la línea que comienza por "Así le dije..."

Acepta, parte inferior derecha.

Ahora seguimos en la rama "mas_alla", edita el fichero viaje.txt para eliminar la línea duplicada.

Realiza un commit con el comentario que aparece debido a la mezcla.

De manera similar realiza la mezcla de las ramas "mas_alla" y "magia".

Cambia a la rama "master".

Mezcla la rama "master" con la rama "mas_alla".

Realiza un Push para enviar tu repositorio local a github.

"Team" - "Remote" - "Push"

Copia la ruta del repositorio creado al principio, y pegala en la venta, e indica los datos de usuario de tu cuenta github.

En la siguiente pantalla selecciona la 5 ramas locales. Manten el mismo nombre para las ramas remotas.

Finalmente, nos indicará y queremos vincular la rama actual con la rama remota correspondiente. Respondiendo que sí.

