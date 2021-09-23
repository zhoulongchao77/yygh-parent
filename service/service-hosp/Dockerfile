FROM openjdk:8-jdk-alpine
VOLUME /tmp
COPY ./target/service-hosp.jar service-hosp.jar
ENTRYPOINT ["java","-jar","/service-hosp.jar", "&"]