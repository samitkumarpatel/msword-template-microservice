FROM openjdk:8-jdk-alpine
VOLUME /tmp
CMD mkdir /template /download
COPY target/api-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8081
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]