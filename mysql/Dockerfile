FROM mysql:latest
ENV MYSQL_ROOT_PASSWORD password
ENV MYSQL_DATABASE hospital_db
COPY ./hospital_db.sql /docker-entrypoint-initdb.d/ 
EXPOSE 3306
