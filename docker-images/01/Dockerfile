FROM centos
RUN yum install httpd -y
EXPOSE 80
COPY index.html /var/www/html/index.html
CMD /usr/sbin/httpd -DFOREGROUND 
