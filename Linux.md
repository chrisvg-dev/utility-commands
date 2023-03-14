## Desactivar root de ssh
1. Abrir el archivo /etc/ssh/sshd_config
2. En la línea PermitRootLogin yes, sustituye la palabra Yes por la palabra No.
3. reiniciar el servicio con "service ssh restart" 