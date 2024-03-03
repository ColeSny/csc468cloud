FROM mysql/mysql-server:latest

COPY cattle_data.csv /docker-entrypoint-initdb.d/cattle_data.csv

CMD ["mysqld"]
EXPOSE 3306
