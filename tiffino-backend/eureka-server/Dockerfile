FROM eclipse-temurin:17-jdk-alpine
WORKDIR /app
COPY target/eureka-server-0.0.1-SNAPSHOT.jar eureka-server-0.0.1-SNAPSHOT.jar
EXPOSE 8990
CMD ["java", "-jar", "eureka-server-0.0.1-SNAPSHOT.jar"]
