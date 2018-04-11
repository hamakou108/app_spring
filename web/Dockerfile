FROM httpd:2
LABEL maintainer="hamakou108 <kosuke1602177mteitm19@gmail.com>"

COPY --chown=root:www-data ./conf/httpd.conf /usr/local/apache2/conf/
COPY --chown=root:www-data ./conf/proxy-ajp.conf /usr/local/apache2/conf/extra/
