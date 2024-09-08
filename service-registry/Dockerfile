FROM openjdk:11
COPY /target/*.jar ./
EXPOSE 8761
ENTRYPOINT [ "java", "-jar", "service-registry.jar" ]