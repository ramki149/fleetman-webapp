FROM openjdk:8u191-jdk-alpine3.9

MAINTAINER Ramakrishnan Sundaramoorthy "ramki149@gmail.com"

EXPOSE 8080

WORKDIR /usr/local/bin/

COPY fleetman-0.0.1-SNAPSHOT.jar webapp.jar

CMD ["java", "-Dspring.profiles.active=docker-demo", "-jar", "webapp.jar"]