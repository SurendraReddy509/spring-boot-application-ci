FROM eclipse-temurin:21-jdk
WORKDIR /app
COPY docker/app1-hello/springboot/hello-spring/target/*.jar app.jar
EXPOSE 8080
CMD ["java","-jar","app.jar"]