# Proyecto Docker (Nginx)

## Comandos

# 1) Construir la imagen

docker build -t proyecto-docker .

# 2) Ejecutar el contenedor (usa el puerto 80 del contenedor)

docker run -d -p 80:80 --name contenedor-docker proyecto-docker

# Si el 80 de tu PC ya está ocupado, usa:

# docker run -d -p 8080:80 --name contenedor-docker proyecto-docker

# 3) Probar en el navegador

# http://localhost (o http://localhost:8080 si usaste 8080)

# 4) Detener y eliminar

# docker stop contenedor-docker

# docker rm contenedor-docker
