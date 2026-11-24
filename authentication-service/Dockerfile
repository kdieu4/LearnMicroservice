FROM ubuntu:latest
LABEL authors="dieuhoang"

ARG JAR_FILE=target/*.jar

COPY ${JAR_FILE} auth-service.jar

ENTRYPOINT ["java", "jar", "auth-service.jar"]

#ENTRYPOINT ["top", "-b"]

EXPOSE 8081