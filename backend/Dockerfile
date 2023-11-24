FROM postgres:latest

ENV POSTGRES_USER super_admin
ENV POSTGRES_PASSWORD mysecretpassword
ENV PGDATA /data/client-restaurant-system-management
ENV POSTGRES_DB client-restaurant-system-management

EXPOSE 5433

VOLUME /data/client-restaurant-system-management

CMD ["postgres"]
