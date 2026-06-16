FROM eclipse-temurin:11-jre

ARG artifact=target/spring-boot-web.jar

WORKDIR /opt/app

COPY ${artifact} app.jar

EXPOSE 8081

ENTRYPOINT ["java","-jar","app.jar"]
