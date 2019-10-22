FROM openjdk:11
ADD target/zuulservice-0.0.1-SNAPSHOT.jar zuulservice-app.jar
EXPOSE 8081
ENTRYPOINT ["java","-jar","zuulservice-app.jar"]
