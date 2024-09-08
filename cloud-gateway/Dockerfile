FROM openjdk:11
COPY /target/*.jar ./
EXPOSE 9191
ENTRYPOINT [ "java", "-jar", "cloud-gateway.jar" ]