FROM openjdk:8-jdk-alpine
VOLUME /tmp
COPY ./target/service-sms.jar service-sms.jar
ENTRYPOINT ["java","-jar","/service-sms.jar", "&"]