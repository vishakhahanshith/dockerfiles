FROM almalinux:8
# almalinux is exactly same as centos
RUN yum install nginx -y
# Removing default html in the below line
RUN rm -rf /usr/share/nginx/html/hello.html
RUN echo "Hello, Welcome to Dockerfile. A way of creating own images" > /usr/share/nginx/html/hello.html
# daemon off command makes our container running and attached to the screen
CMD [ "nginx", "-g", "daemon off;" ]

# FROM run:v1
# RUN echo "Hello, Welcome to Dockerfile. A way of creating images" > /usr/share/nginx/html/hello.html
# daemon off command makes our container running and attached to the screen
# CMD [ "nginx", "-g", "daemon off;"]