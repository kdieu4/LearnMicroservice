FROM ubuntu:latest
LABEL authors="dieuhoang"

ARG JAR_FILE=target/*.jar

COPY ${JAR_FILE} api-gateway.jar

ENTRYPOINT ["java", "jar", "api-gateway.jar"]

#ENTRYPOINT ["top", "-b"]

EXPOSE 4953