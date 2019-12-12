FROM openjdk:8-jre-alpine
COPY ./payments-application/build/libs/payments-application.jar /payments-application.jar
EXPOSE 9002
ENTRYPOINT ["java", "-jar", "paymnets-application.jar", "--spring.profiles.active=docker"]