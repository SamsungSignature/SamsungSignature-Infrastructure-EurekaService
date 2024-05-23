FROM eclipse-temurin:17-jdk-alpine
ARG JAR_FILE=build/libs/*.jar
WORKDIR /app
COPY ${JAR_FILE} eureka-service.jar
ENTRYPOINT ["java", "-jar", "/app/eureka-service.jar"]
