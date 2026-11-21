**Aplicar directivas al grupo del dominio**

Restringir a los usuarios del grupo informática lo siguiente:

1.  Acceder al panel de control

Vamos a Herramientas – administración de directivas de grupo

<img src="./media/image1.png" style="width:4.424in;height:2.79159in" />

Seleccionamos “objetos de directiva de grupo” y creamos una nueva
objeto y le damos un nombre

<img src="./media/image2.png" style="width:3.86073in;height:2.696in" alt="Interfaz de usuario gráfica El contenido generado por IA puede ser incorrecto." />

<img src="./media/image3.png" style="width:3.864in;height:2.72749in" alt="Interfaz de usuario gráfica, Aplicación El contenido generado por IA puede ser incorrecto." />

Editamos el nuevo objeto de directiva de grupo

<img src="./media/image4.png" style="width:4.01847in;height:2.24in" />

Vamos a editar la configuración de ususario

<img src="./media/image5.png" style="width:4.00694in;height:1.48in"
alt="Interfaz de usuario gráfica, Aplicación El contenido generado por IA puede ser incorrecto." />

Directivas

<img src="./media/image6.png" style="width:4.03681in;height:1.488in" />

Plantillas Administrativas

<img src="./media/image7.png" style="width:3.99132in;height:1.256in" />

Panel de control

<img src="./media/image8.png" style="width:4.01667in;height:1.568in"
 alt="Interfaz de usuario gráfica, Aplicación El contenido generado por IA puede ser incorrecto." />

Editamos la opcion de “prohibir el acceso a configuración de PC y
Panel de Control”

<img src="./media/image9.png" style="width:5.2403in;height:2.776in" />

Habilitamos y aplicamos

<img src="./media/image10.png" style="width:3.49785in;height:3.336in" />

2.  Acceder al símbolo del sistema

Vamos a sistema y a la opción de “impedir acceso al símbolo del
sistema” y editamos

<img src="./media/image11.png"
style="width:4.5974in;height:2.57757in" />

Habilitamos y aplicamos

<img src="./media/image12.png"
style="width:2.59703in;height:2.43472in" />

3.  Cambiar el fondo de pantalla

Desde personalización elegimos la opción “impedir cambiar el protector
de pantalla” y editamos

<img src="./media/image13.png"
style="width:4.56938in;height:2.54545in" />

Habilitamos y aplicamos

<img src="./media/image14.png"
 style="width:2.98701in;height:2.80413in" />

4.  Busca otras directivas y aplícalas.

Se elige impedir la instalación y desinstalación de programas

Vamos a “panel de control” y editar “quitar agregar o quitar
 programas” y lo habilitamos

<img src="./media/image15.png"
 style="width:4.28044in;height:2.40909in" />

 <img src="./media/image16.png"
 style="width:2.77922in;height:2.57467in" />

Ahora, hay que asignar las políticas a los usuarios. Desde la
administración de directivas de grupo y vinculamos la GPO que creamos

<img src="./media/image17.png"
style="width:4.34637in;height:2.94156in" />

Elegimos la directiva de grupo y aceptamos

<img src="./media/image18.png"
style="width:2.67532in;height:2.48149in" />
<img src="./media/image19.png" style="width:3.59658in;height:2.46697in"
alt="Interfaz de usuario gráfica, Texto, Aplicación El contenido generado por IA puede ser incorrecto." />

Se observa que al reiniciar la maquina conectada a la red, e ejecutar la
aplicación de configuración del sistema, esta intenta abrir, pero se
cierra al poco tiempo sin llegar a mostrarse completamente.

<img src="./media/image20.png"
style="width:3.38961in;height:2.27863in" />

Si se intenta acceder al panel de control nos muestra una notificación
de restricción

<img src="./media/image21.png"
style="width:3.8989in;height:1.44156in" />

Igualmente, al intentar ejecutar el símbolo del sistema nos impide
realizar cualquier acción

<img src="./media/image22.png"
style="width:4.39324in;height:0.7987in" />

Si se intenta cambiar el fondo de pantalla nos notifica un error

<img src="./media/image23.png"
style="width:1.50975in;height:1.55195in" />
<img src="./media/image24.png" style="width:4.34927in;height:1.19466in"
alt="Imagen de la pantalla de un video juego El contenido generado por IA puede ser incorrecto." />
