Instalamos Armitage en Kali Linux usando la terminal con el comando
“sudo apt install armitage”

<img src="./media/image1.png"
style="width:5.69351in;height:3.62338in" />

Durante el inicio de Armitage hubo un error con la base de datos
Postgresql así que hubo que iniciar el servicio desde la terminal usando
“service postgres start”

Iniciamos Armitage

<img src="./media/image2.png"
style="width:6.06458in;height:2.84044in" />

Realizamos un escaneo de la red con Nmap, siguiendo Nmap Scan \> intense
scan y se pedirá el rango de IPs a escanear

<img src="./media/image3.png"
style="width:5.68333in;height:2.65458in" />

<img src="./media/image4.png"
style="width:5.68664in;height:0.87592in" />

Al finalizar nos mostrará un mensaje y las maquinas encontradas

<img src="./media/image5.png" style="width:4.40462in;height:2.08056in"
alt="Interfaz de usuario gráfica, Aplicación El contenido generado por IA puede ser incorrecto." />

Seleccionamos la maquina a vulnerar, previamente se inició
Metasploitable2, y se usa el comando attack \> find attacks

<img src="./media/image6.png"
style="width:6.18941in;height:1.31693in" />

Nos mostrara el siguiente mensaje al finalizar

<img src="./media/image7.png"
style="width:3.52055in;height:1.23121in" />

Para esta prueba seleccionamos el script
“exploit/multi/samba/usermap_script” y hacemos doble clic para editar
las opciones y lanzamos.

<img src="./media/image8.png"
style="width:5.74566in;height:1.17561in" />

<img src="./media/image9.png"
style="width:2.83815in;height:1.71104in" />

El icono de la maquina cambiara al culminar el script si esta fuel
vulnerada.

<img src="./media/image10.png"
style="width:2.16185in;height:1.35069in" />

En este caso se podemos acceder al Shell de la máquina, colocándonos
sobre el icono de la maquina con botón derecho del mouse y seleccionar
la opción “Shell \> interact”

<img src="./media/image11.png"
style="width:2.0289in;height:1.65981in" />

En el panel inferior se abrirá una pestaña llamada “shell 1” donde
podemos escribir comandos en la maquina vulnerada, ejecutamos el comando
“ifconfig” para verificar.

<img src="./media/image10.png"
style="width:3.1992in;height:2.07514in" />

Ahora intentaremos vulnerar una maquina metasploitable3 de Windows,
escaneamos la red y ubicamos el icono de la maquina y veremos el mensaje
siguiente

<img src="./media/image12.png"
style="width:4.65896in;height:1.82639in" />

Realizamos un análisis de los posible ataques, desde “Attacks \> find
attacks” en el menú mostrándose el siguiente mensaje al finalizar

<img src="./media/image13.png"
style="width:2.59484in;height:1.48555in" />

En el listado de scripts nos movemos a
“**exploit/multi/http/jenkins_script_console” doble clic sobre el nombre
y abrirá las opciones del script, hacemos los cambios como se muestra en
la imagen siguiente, y lanzamos el script.**

<img src="./media/image14.png"
style="width:2.95208in;height:2.45069in" /><img src="./media/image15.png" style="width:2.85972in;height:2.40972in"
alt="Interfaz de usuario gráfica, Aplicación El contenido generado por IA puede ser incorrecto." />

Al finalizar podemos ver que el icono de la maquina ha cambiado,
notificando que el script ha podido vulnerar la máquina.

<img src="./media/image16.png"
style="width:5.43353in;height:2.56805in" />

Y podremos abrir un Shell en la máquina para ejecutar comandos

<img src="./media/image17.png"
style="width:4.74897in;height:1.44509in" />
