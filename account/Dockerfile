# Start with a base image containing Java runtime
FROM openjdk:17-jdk-slim

# Add Maintainer Info
MAINTAINER wemeka.com

# Copy jar file from local to Docker container which is generated
# Add the application's jar to the image
COPY target/account-0.0.1-SNAPSHOT.jar account-0.0.1-SNAPSHOT.jar

# Execute the application
ENTRYPOINT ["java","-jar","/account-0.0.1-SNAPSHOT.jar"]