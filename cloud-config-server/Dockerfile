FROM openjdk:11
COPY /target/*.jar ./
EXPOSE 9296
ENTRYPOINT [ "java", "-jar", "cloud-config-server.jar" ]
