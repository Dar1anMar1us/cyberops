# Log files

Los archivos de registro, son archivos que las computadoras utilizan para registrar eventos. Los programas de software, los procesos en segundo plano, los servicios o las transacciones entre servicios (incluido el propio sistema) pueden generar tales eventos. Los archivos de registro dependen de la aplicación que los genera. Cumplir con la convención de los archivos de registro es responsabilidad del desarrollador de la aplicación. La documentación del software debe incluir información sobre sus archivos de registro.

Podemos usar los commandos:

<pre>cat</pre>
Imprimir todo 
<pre>tail -n 5</pre>
Imprimir lo ultimo del log `-n` el numero de lineas que queremos(por defecto sin nada son 10)
<pre>more</pre>
Imprimir usando paginacion/siguente
<pre>less</pre>

`tail` Utilicen la opción –f para ordenarle a journalctl que siga un archivo de registro específico. Presionen Ctrl + C para salir

<b>Systemd</b> es un moderno sistema init diseñado para unificar la configuración y el comportamiento de los servicios de Linux en todas sus distribuciones, y cada ve fue más adoptado por las principales distribuciones de Linux. Arch Linux depende de systemd para la funcionalidad de init. La VM CyberOps Workstation también utiliza systemd.

system-journald (o simplemente journald) es el servicio de registro de eventos de systemd y utiliza archivos binarios "append-only" (solo anexar) que actúan como sus archivos de registro. Observen que journald no impide que el uso de otros sistemas de archivos de registro como syslog o rsyslog.

Journalctl incluye numerosas funcionalidades como desplazamiento de páginas y mensajes codificados por colores, entre otras. Utilicen las teclas de flechas hacia arriba y hacia abajo del teclado para desplazarse por la salida, una línea a la vez. Utilicen las teclas de las flechas hacia la izquierda/derecha del teclado para desplazarse lateralmente y mostrar entradas de registro que se extienden por fuera de los límites de la ventana del terminal. La tecla <b>INTRO</b> muestra la siguiente línea, mientras que la barra espaciadora muestra la siguiente página de la salida. Presionen la tecla q para salir de journalctl.

<i>Para ver las entradas relacionadas con el último arranque, agregue -1 al comando</i>

<pre>sudo journalctl –b -1</pre>

<i>Utilicen la opción --list-boots para generar una lista de los arranques anteriores</i>

<pre>sudo journalctl --list-boots</pre>

Utilice --since ``<time range>`` para especificar el intervalo de tiempo para el cual se deben mostrar entradas de registro. Los dos comandos que se indican a continuación muestran todas las entradas de registro generadas en las últimas dos horas y en el último día, respectivamente

<pre>sudo journalctl –-since "2 hours ago"</pre>

Journalctl también permite mostrar entradas de registro relacionadas con un servicio específico si se utiliza la opción ``–u``. El siguiente comando muestra entradas de registro relacionadas con nginx.

<pre>sudo journalctl –u nginx.service</pre>

Similar a ``tail -f``, journalctl también da soporte de monitoreo en tiempo real:

<pre>sudo journalctl -f</pre>