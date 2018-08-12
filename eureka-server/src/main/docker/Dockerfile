FROM java
VOLUME /tmp
ADD eureka-server-0.0.1-SNAPSHOT.jar eureka-server.jar
RUN bash -c 'touch /eureka-server.jar'
EXPOSE 8761
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/eureka.jar"]