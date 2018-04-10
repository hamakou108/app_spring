FROM httpd:2
LABEL maintainer="hamakou108 <kosuke1602177mteitm19@gmail.com>"

COPY --chown=root:www-data ./httpd.conf /usr/local/apache2/conf/
COPY --chown=root:www-data ./proxy-ajp.conf /usr/local/apache2/conf/extra/
