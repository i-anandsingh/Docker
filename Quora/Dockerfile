FROM openjdk:17-jdk-slim

WORKDIR /app

COPY Quora-0.0.1-SNAPSHOT.jar Quora.jar

EXPOSE 9094

ENTRYPOINT ["java", "-jar", "Quora.jar"]