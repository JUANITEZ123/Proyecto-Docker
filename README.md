# Proyecto Docker 
ECHO est  activado.
## Comandos para correr el proyecto 
docker build -t proyecto-docker . 
docker run -d -p 8080:80 --name contenedor-docker proyecto-docker 
