FROM openjdk:8-jdk-alpine
EXPOSE 8080
ARG JAR_FILE=target/cloudconfigclient-0.0.1-SNAPSHOT.jar
ADD ${JAR_FILE} client-app.jar
ENTRYPOINT ["java","-jar","/client-app.jar"]
