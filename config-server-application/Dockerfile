FROM openjdk:11
ADD target/config-server-application-0.0.1-SNAPSHOT.jar config-server-app.jar
EXPOSE 8082
ENTRYPOINT ["java","-jar","config-server-app.jar"]
