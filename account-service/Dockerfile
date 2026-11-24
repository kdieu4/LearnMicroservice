FROM ubuntu:latest
LABEL authors="dieuhoang"

ARG JAR_FILE=target/*.jar

COPY ${JAR_FILE} account-service.jar

ENTRYPOINT ["java", "jar", "account-service.jar"]

#ENTRYPOINT ["top", "-b"]

EXPOSE 4953