FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf usr/share/nginx/html/index.html
RUN COPY index.html usr/share/html/index.html
CMD ["nginx", "-g", "daemon off;"]


