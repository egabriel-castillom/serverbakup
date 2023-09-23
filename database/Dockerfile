# Use the official image as a parent image
FROM mysql:latest

# Set the working directory in the container
WORKDIR /docker-entrypoint-initdb.d

# Add initialization scripts
ADD setup.sql .

# Use root user
ENV MYSQL_ROOT_PASSWORD=root

# Expose port 3306
EXPOSE 3306
