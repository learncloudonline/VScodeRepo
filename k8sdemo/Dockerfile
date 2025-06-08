FROM centos:7
MAINTAINER YOGESH KUMAR SHARMA
RUN yum install -y httpd zip unzip
#ADD source dest
#ADD https://www.free-css.com/assets/files/free-css-templates/download/page254/photogenic.zip /var/www/html/
WORKDIR /var/www/html/
#RUN unzip photogenic.zip
#RUN cp -rvf photogenic/ *.
#RUN rm -rf photogenic photogenic.zip
RUN echo '<html><head><title>My Dockerized HTML First </title></head><body><h1>Hello from Docker!</h1></body></html>' > /var/www/html/index.html
#RUN index.html /var/www/html/index.html
CMD ["/usr/sbin/httpd","-D", "FOREGROUND"]
EXPOSE 80 443 8080  3303