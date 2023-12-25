FROM mysql:8.0.33
LABEL "Project"="VProfile"
LABEL "Author"="AJ"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entypoint-initdb.d/db_backup.sql
EXPOSE 3306
