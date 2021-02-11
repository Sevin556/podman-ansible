FROM  centos:8
RUN yum update -y && yum install httpd httpd-tools -y
COPY ./index.html /var/www/html 
# index as volume
EXPOSE  80
CMD ["/usr/sbin/httpd","-D","FOREGROUND"]

