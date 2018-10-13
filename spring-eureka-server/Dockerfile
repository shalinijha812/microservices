FROM openjdk:10
EXPOSE 8761
ADD target/spring-eureka-server-0.0.1-SNAPSHOT.jar /usr/src/spring-eureka-server-0.0.1-SNAPSHOT.jar
WORKDIR usr/src
ENTRYPOINT ["java","-jar","spring-eureka-server-0.0.1-SNAPSHOT.jar"]
