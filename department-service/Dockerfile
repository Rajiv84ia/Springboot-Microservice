FROM openjdk:11
COPY /target/*jar ./
EXPOSE 9001
ENTRYPOINT [ "java", "-jar", "department-service.jar" ]