# Cifrar y Descifrar Datos con OpenSSL

OpenSSL es un proyecto de código abierto que proporciona un kit de herramientas robusto, comercial ycompleto para los protocolos de Seguridad de capa de transporte (Transport Layer Security, TLS) y Capa de sockets segura (Secure Sockets Layer, SSL). También es una biblioteca de criptografía de uso general. En
esta práctica de laboratorio utilizarán OpenSSL para cifrar y descifrar mensajes de texto.

Esta práctica de laboratorio debe utilizarse solo con fines instructivos. Los métodos aquí presentados NO se deben emplear para asegurar datos realmente sensibles.

### Cifrar mensajes con OpenSSL

OpenSSL se puede utilizar como una herramienta independiente para el cifrado. Aunque pueden utilizarse muchos algoritmos de cifrado, esta práctica de laboratorio se enfoca en AES. Si quieren utilizar AES para cifrar un archivo de texto directamente desde la línea de comando utilizando OpenSSL, sigan los pasos que se indican a continuación:

- Iniciar sesión en la Máquina Virtual "CyberOPS Workstation."
- Abrir una ventana del terminal.
- El archivo de texto que se debe cifrar se encuentra en el directorio /home/analyst/lab.support.files/, cambie a ese directorio:

