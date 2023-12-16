FROM openjdk:17
EXPOSE 8089
ADD target/API-Gateway_Server-0.0.1-SNAPSHOT.jar Gateway.jar
ENTRYPOINT ["java","-jar","Gateway.jar"]