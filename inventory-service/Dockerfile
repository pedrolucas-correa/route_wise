FROM openjdk:17-jdk-slim

ENV SPRING_PROFILES_ACTIVE=prod

WORKDIR /app

COPY target/inventory-service-0.0.1-SNAPSHOT.jar app.jar

EXPOSE 8081

ENTRYPOINT ["java", "-jar", "app.jar"]
