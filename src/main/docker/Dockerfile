FROM java:8
MAINTAINER Gordon Kelly <gordon.kelly@idoxgroup.com>

VOLUME /tmp
ADD hello-world-@project.version@.jar app.jar
RUN bash -c 'touch /app.jar'
ENTRYPOINT ["java","-jar","/app.jar"]