FROM postgres:9.4
ENV POSTGRES_USER postgres
ENV POSTGRES_PASSWORD 123
ENV POSTGRES_DB testdb
ADD cargaDatos.sql /docker-entrypoint-initdb.d/cardaDatos.sql
EXPOSE 5432/tcp