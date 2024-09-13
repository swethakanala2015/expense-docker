FROM mysql:8.0
#not a human, only for system
RUN adduser -r expense
RUN chown -R expense:expense /var/lib/mysql /var/run/mysqld
COPY scripts/*.sql /docker-entrypoint-initdb.d/