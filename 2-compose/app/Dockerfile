FROM dockette/debian:buster

RUN apt update && apt dist-upgrade -y

RUN apt install -y php

ADD index.php /srv/index.php

CMD php -S 0.0.0.0:8000 /srv/index.php
