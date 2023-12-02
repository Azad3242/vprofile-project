FROM mysql:8.0.33
LABEL "project"="vprofile"
LABEL "auther"="azad"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/ db-backup.sql
