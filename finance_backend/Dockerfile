FROM eclipse-temurin:21-jre-alpine

WORKDIR /app

COPY target/finance-service.jar finance-service.jar

RUN mkdir -p /app/logs

EXPOSE 8881

ENTRYPOINT ["java","-jar","finance-service.jar"]