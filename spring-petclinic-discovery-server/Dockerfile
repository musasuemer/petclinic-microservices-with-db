FROM amazoncorretto:11
ENV SPRING_PROFILES_ACTIVE docker
COPY ./target/*.jar /app.jar
EXPOSE 8761
ENTRYPOINT ["java", "-jar", "./app.jar"]