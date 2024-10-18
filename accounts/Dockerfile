FROM openjdk:17-jdk-slim

MAINTAINER nguyentaijs

COPY target/account*.jar accounts.jar

ENTRYPOINT ["java", "-jar", "accounts.jar"]