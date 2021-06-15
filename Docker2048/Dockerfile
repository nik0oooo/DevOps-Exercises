FROM alpine
ENV TZ=UTC
RUN apt install -y apache2
COPY ./index.html /var/www/html
EXPOSE 80
