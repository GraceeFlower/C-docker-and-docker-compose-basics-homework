# Use JDK1.8 env as the image
FROM Java:8

# Copy jar-package
COPY build/libs/bob-0.0.1-SNAPSHOT.jar bob.jar

# Do this when starts
ENTRYPOINT ["java", "-jar", "/bob.jar"]

# export port
EXPOSE 8081