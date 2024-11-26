
# Use the official OpenJDK image from Docker Hub
FROM openjdk:11-jre-slim

# Set the working directory inside the container
WORKDIR /app

# Copy your Java file into the container
COPY target/hello-world-1.0-SNAPSHOT.jar /app/

# Compile the Java file
#RUN java hello-world-1.0-SNAPSHOT.jar

# Command to run the Java program
CMD ["java", "-jar", "hello-world-1.0-SNAPSHOT.jar"]
