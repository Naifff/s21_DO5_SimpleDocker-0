FROM nginx

USER root

RUN apt-get update && apt-get install -y \
    gcc \
    libfcgi-dev \
    spawn-fcgi

COPY ./miniserver.c ./s21/src/miniserver.c 
COPY ./nginx/nginx.conf etc/nginx/nginx.conf