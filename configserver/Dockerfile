FROM openjdk:17 as build
MAINTAINER allweb
COPY target/configserver-0.0.1-SNAPSHOT.jar configserver.jar
ENTRYPOINT ["java","-jar","configserver.jar"]