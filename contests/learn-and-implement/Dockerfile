FROM nginx:latest

RUN apt-get update -y &&\
    apt-get install nano -y
ADD ./learn ./usr/share/nginx/html

EXPOSE 80
