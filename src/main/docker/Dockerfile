FROM java:8
VOLUME /tmp
ADD zuul-gateway-0.0.1-SNAPSHOT.jar microservice.jar
RUN bash -c 'touch /service.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/microservice.jar"]