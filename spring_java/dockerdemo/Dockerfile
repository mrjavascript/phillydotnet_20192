FROM amazoncorretto:8
VOLUME /tmp
COPY ./build/libs/dockerdemo-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]