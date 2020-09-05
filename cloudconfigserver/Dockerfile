FROM openjdk:8-jdk-alpine
EXPOSE 8080
ARG JAR_FILE=target/cloudconfigserver-0.0.1-SNAPSHOT.jar
ADD ${JAR_FILE} server-app.jar
ENTRYPOINT ["java","-jar","/server-app.jar"]
