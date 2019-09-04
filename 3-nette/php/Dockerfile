FROM dockette/debian:buster

RUN apt update && apt dist-upgrade -y
RUN apt install -y php php-fpm

ADD php-fpm.conf /etc/php/7.3/fpm/php-fpm.conf

CMD php-fpm7.3 -F -R -y /etc/php/7.3/fpm/php-fpm.conf
