# angular

Dentro de la carpeta angular-app correr los comandos:

sudo docker build --pull --rm -f "Dockerfile" -t angular-app:v1 "."

sudo docker run --rm -d -p 80:80 angular-app:v1
