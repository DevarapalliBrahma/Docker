FROM almalinux:9
RUN dnf install nginx -y
#removing the file is for the default exiting file will be there
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]