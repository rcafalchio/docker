FROM ubuntu

RUN apt-get update && apt-get install -y apache2

ADD ./app/ /var/www/html

EXPOSE 80

CMD ["usr/sbin/apachectl","-D","FOREGROUND"]
