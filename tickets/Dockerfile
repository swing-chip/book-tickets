# Base image
FROM openjdk:17-jdk-slim

# Set the working directory
WORKDIR /app


# Copy the Spring Boot jar to the container
COPY build/libs/*.jar /app/app.jar

# Expose the port that the application will run on
EXPOSE 8081

# Command to run the Spring Boot application
ENTRYPOINT ["java", "-jar", "app.jar"]

