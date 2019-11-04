FROM mariadb:10.4.8

ENV MYSQL_ROOT_PASSWORD 478zWPpxUtd4skPQGmI1
ENV MYSQL_DATABASE sampledb
ENV MYSQL_USER luke
ENV MYSQL_PASSWORD skywalker

COPY sampledb.sql /docker-entrypoint-initdb.d/

CMD ["mysqld"]
