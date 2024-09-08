FROM openjdk:11
COPY /target/*.jar ./
EXPOSE 9295
ENTRYPOINT [ "java", "-jar", "hystrix-dashboard.jar" ]