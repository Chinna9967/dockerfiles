FROM alamalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILD ADD index.html
CMD [ "nginx", "-g", "daemon off;" ]