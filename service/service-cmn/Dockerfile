FROM openjdk:8-jdk-alpine
VOLUME /tmp
COPY ./target/service-cmn.jar service-cmn.jar
ENTRYPOINT ["java","-jar","/service-cmn.jar", "&"]