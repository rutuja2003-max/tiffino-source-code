FROM eclipse-temurin:17-jdk-alpine
WORKDIR /app
COPY target/api-gateway-0.0.1-SNAPSHOT.jar api-gateway-0.0.1-SNAPSHOT.jar
EXPOSE 8800
CMD ["java", "-jar", "api-gateway-0.0.1-SNAPSHOT.jar"]
