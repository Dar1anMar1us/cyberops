# Anatomía del malware

El malware, o software malicioso, hace referencia a diversos programas de software malicioso que se pueden utilizar para causar daños en sistemas informáticos, robar datos y eludir medidas de seguridad.

El malware también puede atacar infraestructura crítica, deshabilitar servicios de emergencia, hacer que las líneas de ensamble fabriquen productos defectuosos, deshabilitar generadores eléctricos e interrumpir servicios de transporte. Los expertos en seguridad estiman que se lanzan más de un millón de amenazas de malware nuevas por día.

Entre algunos de los ejemplos de malware podemos incluir los siguientes: ``Ransomware, Troyanos, Hoax, Adware, Malware, PUP, Exploit, Exploit Kit``, etc.

- Rootkits <ul>
        <li>Un rootkit se usa habitualmente para esconder algunas aplicaciones que podrían actuar en el sistema atacado. Suelen incluir backdoors (puertas traseras) para ayudar al intruso a acceder fácilmente al sistema una vez que se ha conseguido entrar por primera vez.</li>
        <li>Los rootkits, al estar diseñados para pasar desapercibidos, no pueden ser detectados. Si un usuario intenta analizar el sistema para ver qué procesos están ejecutándose, el rootkit mostrará información falsa, mostrando todos los procesos excepto él mismo y los que está ocultando.</li>
        <li>Cuando el antivirus hagan una llamada al sistema operativo para comprobar qué ficheros hay, o cuando intente averiguar qué procesos están en ejecución, el rootkit falseará los datos y el antivirus no podrá recibir la información correcta para llevar a cabo la desinfección del sistema.</li>
        <li>Encontrar y eliminar rootkits no es una ciencia exacta, ya que pueden instalarse de varias formas. Incluso si limpia una máquina, el rootkit puede sobrevivir en algunos casos.</li>
    </ul>

- Ransomware <ul>
        <li>Es un tipo de malware que impide a los usuarios acceder a su sistema o a sus archivos personales y que exige el pago de un rescate para poder acceder de nuevo a ellos.</li>
        <li>Las primeras variantes de ransomware se crearon al final de la década de los 80, y el pago debía efectuarse por correo postal. Hoy en día los creadores de ransomware piden que el pago se efectúe mediante criptomonedas o tarjetas de crédito.</li>
        <li>``Scareware``:  Podría recibir un mensaje emergente que le informa de que se ha detectado malware y que la única forma de librarse de él es pagar. Si no lo hace, seguramente continuará siendo bombardeado con mensajes emergentes, pero sus archivos están básicamente a salvo.</li>
        <li>``Bloqueadores de pantalla``: Si un ransomware que bloquea la pantalla llega a su ordenador, le impedirá el uso de su PC por completo.</li>
        <li>``Ransomware de cifrado``:  La razón por la que este tipo de ransomware es tan peligroso es porque una vez que los ciberdelincuentes se apoderan de los archivos, no hay ningún software de seguridad ni restauración del sistema capaz de devolvérselos. A menos que pague el rescate, puede despedirse de sus archivos. E incluso si lo paga, no hay ninguna garantía de que los ciberdelincuentes le devuelvan los archivos.</li>
    </ul>

- Worms <ul>
        <li>Se replica para propagarse a otras computadoras. Este software malicioso suele utilizar una red informática para propagarse, aprovechando las fallas de seguridad en la computadora de destino para acceder a ella. </li>
        <li>El principal objetivo de los gusanos es propagarse y afectar al mayor número de dispositivos posible. Para ello, crean copias de sí mismos en el ordenador afectado, que distribuyen posteriormente a través de diferentes medios, como el correo electrónico o programas P2P entre otros.</li>
        <li>El primer gusano informático de la historia data de 1988, cuando el gusano Morris infectó una gran parte de los servidores existentes hasta esa fecha. Su creador, Robert Tappan Morris, fue condenado a tres años de prisión y obtuvo libertad condicional con 400 horas de servicios a la comunidad y una multa de 10.050 dólares, gracias a que su familia pagó la fianza.</li>
    </ul>

- Keyloggers <ul>
        <li>Es un tipo de software o un dispositivo hardware específico que se encarga de registrar las pulsaciones que se realizan en el teclado, para posteriormente memorizarlas en un fichero o enviarlas a través de internet.</li>
        <li>En algunas computadoras podemos darnos cuenta si están infectadas por un keylogger por el hecho de que el programa registrará cada una de nuestras teclas de la siguiente manera: FicheroLog = FicheroLog + UltimaTecla, este evento será ejecutado por el keylogger cada vez que el usuario presione una tecla. </li>
    </ul>