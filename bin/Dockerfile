# FROM openjdk:8
# EXPOSE 8080
# ADD target/docker-jenkins-integration-sample.jar docker-jenkins-integration-sample.jar
# ENTRYPOINT [ "java","-jar","/docker-jenkins-integration-sample.jar" ]

FROM openjdk:11
EXPOSE 4567
COPY target/bootjar.jar bootjar.jar
ENTRYPOINT ["java","-jar","/bootjar.jar"]