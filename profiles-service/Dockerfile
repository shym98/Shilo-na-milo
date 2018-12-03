FROM openjdk:8-jdk-alpine
ADD build/libs/0.0.1-SNAPSHOT.jar user_profile.jar
EXPOSE 8091
ENTRYPOINT ["java", "-jar", "user_profile.jar"]