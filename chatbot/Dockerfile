# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk-alpine

# Set the working directory in the container
WORKDIR /app

# Copy the specific jar file into the container
COPY target/chatbot-0.0.1-SNAPSHOT.jar app.jar

# Expose the port on which the Spring Boot application will run
EXPOSE 8080

# Command to run the jar file
ENTRYPOINT ["java", "-jar", "app.jar"]
