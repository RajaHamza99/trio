FROM mysql
# Derived from official mysql image (our base image)


# Add a database
ENV MYSQL_DATABASE=flask-db
ENV MYSQL_ROOT_PASSWORD=root
# Add the content of the .sql file to your image
COPY ./CreateTable.sql ./docker-entrypoint-initdb.d
# All scripts in docker-entrypoint-initdb.d/ are automatically
# executed during container startup
