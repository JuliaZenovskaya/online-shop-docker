FROM openjdk:8-jre-alpine
COPY ./orders-application/build/libs/orders-application.jar /orders-application.jar
EXPOSE 9000
ENTRYPOINT ["java", "-jar", "orders-application.jar", "--spring.profiles.active=docker"]