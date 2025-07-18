# 1. Use Java 17 base image
FROM eclipse-temurin:17-jdk

# 2. Set work directory
WORKDIR /app

# 3. Copy the built JAR
COPY target/order-0.0.1-SNAPSHOT.jar app.jar

# 4. Expose port (should match application.yml)
EXPOSE 8082

# 5. Run the app
ENTRYPOINT ["java", "-jar", "app.jar"]
