FROM openjdk:8-jdk-alpine
ADD build/libs/gs-rest-service-0.1.0.jar products.jar
EXPOSE 8090
ENTRYPOINT ["java", "-jar", "products.jar"]