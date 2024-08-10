# Stage 1: Build Stage
FROM maven:3.8.7-openjdk-17 AS build

# Set the working directory inside the container
WORKDIR /app

# Copy the Maven project files to the working directory
COPY pom.xml .
COPY src ./src

# Build the application
RUN mvn clean package -DskipTests




# Stage 2: Runtime Stage
FROM openjdk:17-jdk-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the built JAR file from the build stage
COPY --from=build /app/target/*.jar app.jar

# Expose the application's port (optional)
EXPOSE 8080

# Set the command to run the application
CMD ["java", "-jar", "app.jar"]
