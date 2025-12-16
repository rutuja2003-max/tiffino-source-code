FROM eclipse-temurin:17-jdk-alpine
WORKDIR /app
COPY target/userservice-0.0.1-SNAPSHOT.jar userservice-0.0.1-SNAPSHOT.jar
EXPOSE 8890
CMD ["java", "-jar", "userservice-0.0.1-SNAPSHOT.jar"]
