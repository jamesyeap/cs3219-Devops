FROM openjdk:11.0.2-jre-slim

EXPOSE 8080

RUN mkdir /opt/app
COPY catalog-service-0.0.1-SNAPSHOT.jar /opt/app
CMD ["java", "-jar", "/opt/app/catalog-service-0.0.1-SNAPSHOT.jar"]

# docker build -t cs3219/catalog-service:1.0.0 ./catalog-service