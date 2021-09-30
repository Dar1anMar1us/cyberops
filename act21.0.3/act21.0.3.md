# - Crear códigos Objetivos

Los códigos secretos se han empleado por miles de años. En la antigua Grecia y Esparta se utilizaba una escítala para codificar mensajes. Los romanos utilizaban un cifrado conocido como César para cifrar mensajes. Hace aproximadamente 100 años, los franceses utilizaban la clave Vigenère para codificar
mensajes. Actualmente se pueden codificar mensajes de muchas maneras.

Se pueden utilizar varios algoritmos de cifrado para cifrar y descifrar mensajes. Comúnmente, se utilizan Redes Privadas Virtuales (VPN, Virtual Private Network) para automatizar el proceso de cifrado y descifrado.

En esta práctica de laboratorio, trabajarán con un compañero y utilizarán una herramienta en línea para cifrar y descifrar mensajes.

### Buscar una herramienta de codificación y decodificación en línea.

En las redes modernas se utilizan muchos tipos diferentes de algoritmos de cifrado. Uno de los más seguros es el algoritmo de cifrado simétrico llamado Estándar de Cifrado Avanzado (Advanced Encryption Standard, AES). En nuestra demostración utilizaremos este algoritmo.

- Busquen “cifrar y descifrar AES en línea” en un navegador web. En los resultados de la búsqueda aparecerá una lista con varias herramientas. 

https://www.devglan.com/online-tools/aes-encryption-decryption

### Cifrar un mensaje y enviarlo por correo electrónico a su compañero.

- Escribir un mensaje en texto plano de su elección en el cuadro de texto. El mensaje puede ser muy breve o extenso. Deben asegurarse de que su compañero no vea el mensaje en texto plano.

    Usualmente se necesita una clave secreta (es decir, una contraseña) para cifrar un mensaje. La clave secreta se utiliza junto con el algoritmo de cifrado para cifrar el mensaje. Solamente quien conozca la clave secreta podrá descifrar el mensaje.

- Introducir una clave secreta. Es posible que algunas herramientas les pidan que confirmen la contraseña. En nuestro ejemplo utilizamos ``cyberops`` como clave secreta.

Este es el resultado: 

<pre>KqyuVrKmVUsKZpJt5nCLItLu5AhTAneGBEK5L5MZhBk=</pre>

- Enviar el mensaje cifrado a su compañero por correo

### Descifrar el texto cifrado

AES es un algoritmo de cifrado simétrico. Esto quiere decir que las dos partes que se están intercambiando mensajes cifrados deben conocer la clave secreta con antelación.

- Abrir el correo electrónico de su compañero.

- Copiar el texto cifrado y péguenlo en el cuadro de texto.

- Introducir la clave secreta previamente compartida.

Si utilizan una clave secreta incorrecta obviamente no se podrá descifrar el mensaje.