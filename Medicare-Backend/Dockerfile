FROM openjdk:17-slim

COPY target/ app.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","app.jar"]