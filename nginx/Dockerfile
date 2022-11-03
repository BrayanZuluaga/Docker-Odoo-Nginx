FROM nginx:1.18

USER root
# Se actualizar debian y se instala nano.
RUN apt update
#RUN apt upgrade
RUN apt install nano
# Se crea la carpeta dentro del contenedor con Nginx donde se almacena los certificados ssl.
RUN mkdir -p /etc/ssl/nginx/