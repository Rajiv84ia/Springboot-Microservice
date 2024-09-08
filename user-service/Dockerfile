FROM openjdk:11
COPY /target/*.jar ./
EXPOSE 9002
ENTRYPOINT [ "java", "-jar", "user-service.jar" ]