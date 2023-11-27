FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
#RUN echo "Hello, Welcome to Dockerfile. A way of creating own images" > /usr/share/nginx/html/hello.html
ONBUILD ADD index.html /usr/share/nginx/html/index.html
CMD [ "nginx", "-g", "daemon off;" ]

