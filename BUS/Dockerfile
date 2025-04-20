FROM almalinux:9

RUN command -v nginx || yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html

COPY bus_booking.html /usr/share/nginx/html/index.html

CMD [ "nginx", "-g", "daemon off;" ]

