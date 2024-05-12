FROM eclipse-temurin:21

RUN mkdir /opt/app
WORKDIR /opt/app
EXPOSE 8080

COPY . /opt/app

RUN apt update

RUN apt install net-tools

CMD ["java", "-jar", "bff-0.0.1-SNAPSHOT.jar"]