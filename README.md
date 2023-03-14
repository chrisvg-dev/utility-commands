# Comandos

## Jenkins SSH
1. su - jenkins
2. ssh-keygen -t ed25519 -C "cristianvg9692@gmail.com"
3. Frase: cvillegas
3. cd ./ssh

"

SHA256:WQtJKaHCM/+d8YgDz5djwZnkrI2dcqtHkMyt7CwJhgU cristianvg9692@gmail.com
The key's randomart image is:
+--[ED25519 256]--+
|      ....       |
|E.   .....       |
| .= .o ++ .      |
|  .=  ==.* .     |
| o  o. oS .      |
|. o  =oB.O       |
| . . +X.& .      |
|    o o*.o       |
|     ..o.        |
+----[SHA256]-----+

"
4. ssh -T git@github.com con el usuario jenkins
4. eval `ssh-agent`
5. ssh-add ~/.ssh/id_rsa


## Desactivar root de ssh
1. Abrir el archivo /etc/ssh/sshd_config
2. En la línea PermitRootLogin yes, sustituye la palabra Yes por la palabra No.
3. reiniciar el servicio con "service ssh restart" 

# Direcciones
1. cvillegas-dev.com -> 70.35.204.135

## Configuraciones
 1. Apache y host virtuales https://www.digitalocean.com/community/tutorials/how-to-install-the-apache-web-server-on-ubuntu-20-04-es
 2. JDK8 en ubuntu https://www.fosstechnix.com/install-oracle-java-8-on-ubuntu-20-04/

## Instalar Node en ubuntu
1. https://itslinuxfoss.com/install-node-js-npm-ubuntu-22-04/

## Jenkins pipeline
1. https://geekflare.com/es/create-jenkins-pipeline/