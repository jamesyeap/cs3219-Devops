FROM openjdk:11.0.2-jre-slim

EXPOSE 8080

RUN mkdir /opt/app
COPY order-service-0.0.1-SNAPSHOT.jar /opt/app
CMD ["java", "-jar", "/opt/app/order-service-0.0.1-SNAPSHOT.jar"]

# docker build -t cs3219/order-service:1.0.0 ./order-service