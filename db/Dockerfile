FROM mysql:latest

ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_DATABASE=db

COPY ./init.sql /docker-entrypoint-initdb.d/

