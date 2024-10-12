# Use the official OpenJDK image
FROM openjdk:17-jdk

# Set the working directory
WORKDIR /app

# Copy the Calculator.java file to the container
COPY Calculator.java .

# Compile the Java program
RUN javac Calculator.java

# Command to run the Java program
CMD ["java", "Calculator"]
