FROM almalinux:8
RUN yum install nginx -yum
# Expose is not adding any functionality, this is just for information
EXPOSE 80/tcp
CMD [ "nginx", "-g", "daemon off;"]