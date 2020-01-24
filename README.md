docker pull mongo


docker run -d -p 27017:27017  -v /localdirectory/data:/data/db --name mongodb mongo

como arranco como demonio, no se detiene cuando se cierra la terminal

docker logs mongodb 

mestra los logs del contenedor

docker ps -a 

muestra los contenedores listos  para correr

docker insperct mongo

docker rm xxxxx

elimina el contenedor 

