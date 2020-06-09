FROM centos:7

MAINTAINER Wiktor Ziółkowski

RUN yum update -y && \
      yum install httpd -y

COPY site/index.html /var/www/html/

CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]

EXPOSE 80
