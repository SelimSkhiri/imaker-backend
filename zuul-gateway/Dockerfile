FROM openjdk:8-jdk-alpine
ADD /src/docker/zuul_gateway-0.0.1-SNAPSHOT.jar app.jar
CMD java -Dserver.port=$PORT -jar app.jar

