FROM openjdk:17-jdk-alpine
MAINTAINER ondubovickaya
EXPOSE 8070
COPY target/Cars-0.0.1-SNAPSHOT.jar cars.jar
ENTRYPOINT ["java","-jar","./cars.jar"]
