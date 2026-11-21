# Compartir carpetas en Windows Server

En Windows Server 2019, se pide:

1.  Añadir un disco externo (Virtualbox)

2.  Crear una carpeta de acceso público

3.  Crear una carpeta de privada de un usuario

4.  Una vez finalizado, sube a la plataforma un documento con capturas
    de pantalla, que muestren los pasos realizados.

Agregamos a Windows Server un nuevo disco

<img src="./media/image1.png"
style="width:2.64929in;height:1.70726in" />

En el panel del servidor vamos a Administración de equipos

<img src="./media/image2.png" style="width:2.7795in;height:1.14692in" />

Nos pedira que inicalicemos el disco agregado

<img src="./media/image3.png"
style="width:3.71944in;height:1.91667in" />

Creamos un nuevo volumen simple

<img src="./media/image4.png"
style="width:3.28646in;height:1.30208in" />

Le seleccionamos la mitad del disco

<img src="./media/image5.png"
style="width:1.99073in;height:1.57812in" />
<img src="./media/image6.png" style="width:1.99589in;height:1.58333in"
alt="Interfaz de usuario gráfica, Aplicación, Word El contenido generado por IA puede ser incorrecto." />
<img src="./media/image7.png" style="width:1.95313in;height:1.57256in"
alt="Interfaz de usuario gráfica, Aplicación, Word El contenido generado por IA puede ser incorrecto." />

Creamos una nueva carpeta en el disco local llamda Datos de usuario

<img src="./media/image8.png" style="width:3.11719in;height:1.1875in" />

Configuramos el resto del disco montado en la carpeta de Datos de
usuario

<img src="./media/image9.png" style="width:2.5339in;height:1.24951in" />
<img src="./media/image5.png" style="width:1.86928in;height:1.47361in"
alt="Interfaz de usuario gráfica, Aplicación El contenido generado por IA puede ser incorrecto." />
<img src="./media/image10.png" style="width:1.90054in;height:1.49444in"
alt="Interfaz de usuario gráfica, Aplicación El contenido generado por IA puede ser incorrecto." />

<img src="./media/image11.png"
style="width:1.90625in;height:1.49029in" />
<img src="./media/image12.png" style="width:1.85367in;height:1.49965in"
alt="Interfaz de usuario gráfica, Aplicación El contenido generado por IA puede ser incorrecto." />
<img src="./media/image13.png" style="width:1.90104in;height:1.49752in"
alt="Interfaz de usuario gráfica, Aplicación El contenido generado por IA puede ser incorrecto." />

G<img src="./media/image14.png"
style="width:1.61458in;height:1.28274in" />

Se observa que el icono de la carpeta Datos de usuario ha cambiado y
mostrando el tamaño asignado al disco montado

<img src="./media/image15.png"
style="width:2.96875in;height:1.21354in" />

Dentro de la carpeta “datos de usuario”, creamos una carpeta llamada
“acceso publico”

<img src="./media/image16.png"
style="width:3.2665in;height:1.11458in" />

Agregamos un nuevo Rol

<img src="./media/image17.png"
style="width:2.38539in;height:1.17187in" />
<img src="./media/image18.png" style="width:2.37207in;height:1.67708in"
alt="Interfaz de usuario gráfica, Texto, Aplicación El contenido generado por IA puede ser incorrecto." />
<img src="./media/image19.png" style="width:2.34667in;height:1.67339in"
alt="Interfaz de usuario gráfica, Texto, Aplicación El contenido generado por IA puede ser incorrecto." />

<img src="./media/image20.png" style="width:2.56131in;height:1.81668in"
alt="Interfaz de usuario gráfica, Texto, Aplicación, Correo electrónico El contenido generado por IA puede ser incorrecto." />
<img src="./media/image21.png" style="width:2.77301in;height:2.10972in"
alt="Interfaz de usuario gráfica El contenido generado por IA puede ser incorrecto." />
<img src="./media/image22.png" style="width:1.77276in;height:1.87059in"
alt="Interfaz de usuario gráfica, Texto El contenido generado por IA puede ser incorrecto." />

<img src="./media/image23.png"
style="width:2.79127in;height:2.11032in" />
<img src="./media/image24.png" style="width:3.53773in;height:2.11043in"
alt="Interfaz de usuario gráfica, Aplicación El contenido generado por IA puede ser incorrecto." />

Esperamos a que finalice la instalación

<img src="./media/image25.png" style="width:2.72393in;height:1.98155in"
alt="Interfaz de usuario gráfica, Aplicación El contenido generado por IA puede ser incorrecto." />

Accedemos a servicio de archivos de almacenamiento desde el panel del
servidor

<img src="./media/image26.png"
style="width:5.15951in;height:2.21472in" />

Y seleccionamos recursos compartido

<img src="./media/image27.png" style="width:7.20245in;height:2.17178in"
alt="Interfaz de usuario gráfica, Texto, Aplicación El contenido generado por IA puede ser incorrecto." />

Desde tareas vamos a crear un nuevo recurso compartido

<img src="./media/image28.png"
style="width:5.97175in;height:1.44172in" />

Seleccionamos recurso compartido SMB – Rápido y agregamos una ruta de
acceso personalizada

<img src="./media/image29.png" style="width:3.47786in;height:2.11611in"
alt="Interfaz de usuario gráfica, Texto, Aplicación, Correo electrónico El contenido generado por IA puede ser incorrecto." />
<img src="./media/image30.png"
style="width:3.48399in;height:2.11611in" />

Agegamos la carpeta de datos de usuario

<img src="./media/image31.png"
style="width:3.14322in;height:2.10952in" />
<img src="./media/image32.png" style="width:3.48399in;height:2.10998in"
alt="Interfaz de usuario gráfica, Texto, Aplicación, Correo electrónico El contenido generado por IA puede ser incorrecto." />

Le agregamos un nombre al recurso compartido y lo llamamos Acceso
publico y habilitamos “enumeración basada en acceso”

<img src="./media/image33.png" style="width:3.54533in;height:2.10998in"
alt="Interfaz de usuario gráfica, Texto, Aplicación, Correo electrónico El contenido generado por IA puede ser incorrecto." />
<img src="./media/image34.png"
style="width:3.52495in;height:2.10996in" />

Continuamos sin realizar cambios y creamos

<img src="./media/image35.png" style="width:3.47155in;height:2.10373in"
alt="Interfaz de usuario gráfica, Texto, Aplicación El contenido generado por IA puede ser incorrecto." />
<img src="./media/image36.png"
style="width:3.47765in;height:2.10371in" />

Cerramos la ventana al finalizar

<img src="./media/image37.png"
style="width:3.49044in;height:2.12246in" />

Desde el nuevo recurso creado seleccionamos propiedades

<img src="./media/image38.png"
style="width:4.15833in;height:1.32515in" />

En propiedades de administración activamos Archivos de usuario y
agregamos

<img src="./media/image39.png"
style="width:2.5453in;height:2.22646in" />

Desde otra maquina conectada a la red verificamos el acceso a la carpeta
de acceso publico

Al intentar acceder a la red desde la maquina, nos da un error debido a
que no tiene activa la deteccion de redes, pero podemos acceder a la
carpeta si colocamos la direccion en la barra de direcciones, en este
caso seria:

“\\Servidor-1956.redinterna.local\Acceso publico “

<img src="./media/image40.png"
style="width:4.43558in;height:1.79522in" />

<img src="./media/image41.png"
style="width:4.29448in;height:2.15897in" />

Para probar que tenemos acceso completo, creamos una carpeta y un
archivo dentro

<img src="./media/image42.png"
style="width:3.47902in;height:1.80315in" />
<img src="./media/image43.png" style="width:3.09816in;height:1.8175in"
alt="Interfaz de usuario gráfica, Aplicación, Word El contenido generado por IA puede ser incorrecto." />

**Crear una carpeta de privada de un usuario**

Vamos a crear una carpeta que sea accesible para cada miembro del
dominio (privada).

En primera partición creada en el disco que estamos utilizando para
compartir, creamos las carpetas de los usuarios.

<img src="./media/image44.png"
style="width:3.57055in;height:1.4517in" />
<img src="./media/image45.png" style="width:3.52405in;height:1.43438in"
alt="Interfaz de usuario gráfica, Aplicación El contenido generado por IA puede ser incorrecto." />

Vamos a Servicios de archivos y de almacenamiento y seleccionamos
Recursos compartidos y creamos un nuevo recurso compartido

<img src="./media/image46.png"
style="width:5.25512in;height:1.42945in" />

seleccionamos recurso compartido avanzado y seguimos el mismo proceso
anterior

<img src="./media/image47.png"
style="width:3.44771in;height:2.06739in" />

Seleccionamos una ruta personalizada

<img src="./media/image48.png"
style="width:2.87076in;height:2.10398in" />
<img src="./media/image49.png" style="width:2.99675in;height:2.0977in"
alt="Interfaz de usuario gráfica, Aplicación El contenido generado por IA puede ser incorrecto." />

Siguiente y personalizamos permisos

<img src="./media/image50.png"
style="width:2.87061in;height:2.07933in" />
<img src="./media/image51.png" style="width:2.85191in;height:2.10363in"
alt="Interfaz de usuario gráfica, Texto, Aplicación El contenido generado por IA puede ser incorrecto." />

Para poder quitar los permisos debemos primero deshabilitar la herencia
y convertir en permisos explicitos

<img src="./media/image52.png" style="width:2.96319in;height:1.99422in"
alt="Interfaz de usuario gráfica, Aplicación El contenido generado por IA puede ser incorrecto." />
<img src="./media/image53.png" style="width:2.57999in;height:1.33695in"
alt="Interfaz de usuario gráfica, Texto, Aplicación El contenido generado por IA puede ser incorrecto." />

Ahora podemos quitar los permisos de los usuarios y dejar los de
administradores

<img src="./media/image54.png" style="width:2.85827in;height:1.98731in"
alt="Interfaz de usuario gráfica, Aplicación El contenido generado por IA puede ser incorrecto." />
<img src="./media/image55.png"
style="width:2.90734in;height:1.97504in" />

Agregaremos un permiso para el Usuario1, seleccionamos una entidad de
seguridad, escribimos el nombre de la cuenta, “Usuario1” y comprobar
nombre, seleccionamos la opción que nos muestra y aceptamos

<img src="./media/image56.png"
style="width:3.83119in;height:1.80974in" />
<img src="./media/image57.png" style="width:2.77178in;height:1.80882in"
alt="Interfaz de usuario gráfica, Texto, Aplicación, Correo electrónico El contenido generado por IA puede ser incorrecto." />

<img src="./media/image58.png"
style="width:2.80982in;height:1.65757in" />
<img src="./media/image59.png" style="width:2.81907in;height:1.6438in"
alt="Interfaz de usuario gráfica, Texto, Aplicación El contenido generado por IA puede ser incorrecto." />

Seleccionamos control total y aceptamos, vamos a la pestaña compartir

<img src="./media/image60.png"
style="width:3.45929in;height:2.22655in" />
<img src="./media/image61.png" style="width:3.28861in;height:2.22017in"
alt="Interfaz de usuario gráfica, Texto, Aplicación El contenido generado por IA puede ser incorrecto." />

eliminamos los permisos y agregamos el permiso al Usuario1

<img src="./media/image62.png"
style="width:2.70552in;height:1.85538in" />
<img src="./media/image63.png" style="width:3.07585in;height:1.8395in"
alt="Interfaz de usuario gráfica, Aplicación El contenido generado por IA puede ser incorrecto." />

y le damos control total, aplicamos y aceptamos y seguimos la creacion
del recurso compartido

<img src="./media/image64.png" style="width:3.4652in;height:2.2203in" />
<img src="./media/image65.png" style="width:3.25138in;height:2.21372in"
alt="Interfaz de usuario gráfica, Texto, Aplicación El contenido generado por IA puede ser incorrecto." />

Seleccionamos Archivos de ususario, y siguiente, no agregamos cuotas

<img src="./media/image66.png"
style="width:2.90128in;height:2.1284in" />
<img src="./media/image67.png" style="width:2.90113in;height:2.12829in"
alt="Interfaz de usuario gráfica, Aplicación El contenido generado por IA puede ser incorrecto." />

Creamos el recurso compartido

<img src="./media/image68.png" style="width:2.43558in;height:1.79269in"
alt="Interfaz de usuario gráfica, Aplicación El contenido generado por IA puede ser incorrecto." />
<img src="./media/image69.png" style="width:2.47239in;height:1.80884in"
alt="Interfaz de usuario gráfica, Aplicación El contenido generado por IA puede ser incorrecto." />

<img src="./media/image70.png" style="width:3.97399in;height:1.19018in"
alt="Interfaz de usuario gráfica, Texto, Aplicación, Correo electrónico El contenido generado por IA puede ser incorrecto." />

Desde la maquina con el Usuario1 se observa que la nueva carpeta creada
es visible

<img src="./media/image71.png" style="width:3.65644in;height:1.29511in"
alt="Imagen que contiene Texto El contenido generado por IA puede ser incorrecto." />

Y comprobamos que podemos acceder a la carpeta y crear archivos

<img src="./media/image72.png" style="width:3.72393in;height:1.69939in"
alt="Interfaz de usuario gráfica, Texto, Aplicación, Word El contenido generado por IA puede ser incorrecto." />

Si intentamos acceder desde una cuenta distinta nos informará que no
podemos acceder al recurso compartido

<img src="./media/image73.png"
style="width:4.66258in;height:2.07976in" />
