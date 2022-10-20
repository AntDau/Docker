FROM maven:3.5-jdk-11 AS build
WORKDIR /svc
COPY pom.xml .
COPY src ./src
RUN mvn clean install -DskipTests
CMD ["java", "-jar", "target/Projet_Docker-0.0.1-SNAPSHOT.jar"]  



