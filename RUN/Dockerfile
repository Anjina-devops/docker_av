FROM almalinux:9

RUN yum install nginx -y

RUN rm -rf /etc/usr/share/nginx/html/index.html

RUN echo "<h1>Welcome to Nginx on Amazon Linux 9</h1>" > /usr/share/nginx/html/index.html