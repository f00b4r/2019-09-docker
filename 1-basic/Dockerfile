FROM debian:buster

LABEL maintainer=Felix

RUN apt update 
RUN apt dist-upgrade -y
RUN apt install -y php

USER felix

# ADD php.ini /etc/php/7.3/cli/conf.d/999-custom.ini

WORKDIR /srv

EXPOSE 9000

CMD php -v

#ENTRYPOINT ["php"]
#CMD ["-v"]
