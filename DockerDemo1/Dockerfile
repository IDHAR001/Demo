FROM nginx:1.21.1
WORKDIR /DockerDemo1
RUN rm /etc/nginx/conf.d/default.conf
ADD default.conf /etc/nginx/conf.d/default.conf
ADD index.html /usr/share/nginx/html
EXPOSE 80