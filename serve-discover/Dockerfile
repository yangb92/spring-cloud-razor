FROM openjdk:8-jre

MAINTAINER yangb <http://yangb.xyz>

COPY target/serve-discover-0.0.1-SNAPSHOT.jar /app/app.jar

ENTRYPOINT ["java","-jar","/app/app.jar"]

EXPOSE 35001