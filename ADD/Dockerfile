FROM almalinux:latest

RUN dnf install nginx -y

RUN rm -rf /usr/share/nginx/html/index.html

ADD https://raw.githubusercontent.com/Giribabu1492/docker-course/refs/heads/main/RUN/Dockerfile /usr/share/nginx/html/index.html

RUN chmod +r /usr/share/nginx/html/index.html

CMD ["nginx", "-g", "daemon off;"]

