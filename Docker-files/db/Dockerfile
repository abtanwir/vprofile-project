FROM mysql:8.0.33
LABEL "Project"="Vprofile"
LABEL "Author"="atanwir"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"
RUN rm -rf /var/lib/mysql/*

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql

