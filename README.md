# Comandos

## Jenkins SSH
1. su - jenkins
2. ssh-keygen -t ed25519 -C "cristianvg9692@gmail.com"
3. Frase: cvillegas
3. cd ./ssh
4. ssh -T git@github.com con el usuario jenkins
4. eval `ssh-agent`
5. ssh-add ~/.ssh/id_rsa


----------------------------------------------


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

## Java timezone
1. https://docs.oracle.com/middleware/12211/wcs/tag-ref/MISC/TimeZones.html

## Instalar docker en ubuntu 20.04
1. https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04

## Instalar mysql y postgresql docker
1. https://avbravo-2.gitbook.io/docker/mysql-con-docker-compose
2. https://github.com/khezen/compose-postgres/blob/master/docker-compose.yml

## Resolver el tema de las rutas no encontradas con react
1. https://www.andreasreiterer.at/fix-browserrouter-on-apache/