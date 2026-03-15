FROM mysql:8.0
RUN MYSQL_ROOT_PASSWORD=ExpenseApp1
ENV MYSQL_ROOT_PASSWORD=ExpenseApp1
COPY scripts/*.sql /docker-entrypoint-initdb.d
