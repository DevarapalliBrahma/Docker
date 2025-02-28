FROM almalinux
RUN dnf install nginx
CMD ["nginx","-g","daemon off;"]
COPY text.html /usr/share/nginx/html/text.html