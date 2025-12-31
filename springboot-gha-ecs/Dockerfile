# Use lightweight JRE image
FROM eclipse-temurin:17-jre

# Create app directory
WORKDIR /app

# Copy the jar built by Maven
COPY target/*.jar app.jar

# Expose app port
EXPOSE 8080

# Run the application
ENTRYPOINT ["java", "-jar", "app.jar"]

