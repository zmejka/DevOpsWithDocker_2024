FROM amazoncorretto:22-alpine-jdk

EXPOSE 8080

WORKDIR /usr/src/app

#Copy all of the source code
COPY . .

RUN ./mvnw package

CMD ["java", "-jar", "./target/docker-example-1.1.3.jar"]


