FROM mysql:5.7

COPY crearBBDD.sql /docker-entrypoint-initdb.d/crearBBDD.sql
COPY insertarDatos.sql /docker-entrypoint-initdb.d/insertarDatos.sql

EXPOSE 3306