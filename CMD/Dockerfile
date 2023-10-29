FROM almalinux:8
RUN yum install nginx -y
RUN echo "hello this is from linux nginx" > /usr/share/nginx/html/hello.html
# daemon off command makes our container running and attached to screen
CMD [ "nginx", "-g", "daemon off;" ]