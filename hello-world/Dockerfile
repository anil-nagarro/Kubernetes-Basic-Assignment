# Use OpenJDK image to run the application
FROM openjdk:17
WORKDIR /app
COPY target/hello-world-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]