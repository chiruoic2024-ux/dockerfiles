FROM almalinux:9
RUN dnf install nginx  -y
RUN rm -rf /usr/share/nginx/html/default.html
ONBUILD COPY index.html /usr/share/nginx/html/default.html
CMD ["nginx", "-g", "daemon off;"]

