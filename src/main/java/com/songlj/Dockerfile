FROM java:8

VOLUME /tmp

MAINTAINER songlj

ADD docker-0.0.1-SNAPSHOT.jar app.jar

EXPOSE 8088

ENTRYPOINT ["java","-jar","/app.jar"]