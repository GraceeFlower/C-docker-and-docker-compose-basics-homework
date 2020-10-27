# Use JDK1.8 env as the image
FROM java:8

# Copy jar-package
COPY build/libs/alice-0.0.1-SNAPSHOT.jar alice.jar

# Do this when starts
ENTRYPOINT ["java", "-jar", "/alice.jar"]

# export port
EXPOSE 8080