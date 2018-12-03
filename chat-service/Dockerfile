 
FROM openjdk:8-jdk-alpine
ADD target/chat-0.0.1-SNAPSHOT.jar chat.jar
EXPOSE 8092
ENTRYPOINT ["java", "-jar", "chat.jar"]
