FROM openjdk:8-jdk-alpine
VOLUME /tmp
COPY ./target/service-sso.jar service-sso.jar
ENTRYPOINT ["java","-jar","/service-sso.jar", "&"]