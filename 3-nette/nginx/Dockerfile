FROM dockette/debian:buster

RUN apt update && apt dist-upgrade -y
RUN apt install -y nginx

ADD nginx.conf /etc/nginx/nginx.conf

CMD nginx -g 'daemon off;'
