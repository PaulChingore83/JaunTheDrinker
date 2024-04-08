FROM openjdk:21

# Copy the JAR file from the root directory into the image
COPY juan-the-drinker.jar /app/juan-the-drinker.jar

# Set the working directory
WORKDIR /app

# Expose the port your application uses
EXPOSE 8080

# Run the Java application
CMD ["java", "-jar", "juan-the-drinker.jar"]
