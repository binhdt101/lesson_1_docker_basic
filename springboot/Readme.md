gradle build && java -jar build/libs/s-spring-boot-docker-0.1.0.jar
gradle build docker
docker run -p 8080:8080 -t springio/gs-spring-boot-docker
