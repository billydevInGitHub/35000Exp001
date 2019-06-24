FROM java:8
FROM maven:alpine

WORKDIR /app

COPY . /app

RUN mvn --version
RUN mvn clean install -DskipTests
LABEL maintainer="billydev@gmail.com"
ENTRYPOINT ["java","-jar","/app/target/35000_Exp001_BashJavaAgent-0.0.1-SNAPSHOT-jar-with-dependencies.jar"]


