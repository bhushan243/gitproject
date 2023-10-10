FROM openjdk:11

COPY /target/ticketingSystem-0.0.1-SNAPSHOT.war /usr/app/

EXPOSE 8080

WORKDIR /usr/app

ENTRYPOINT ["java", "-jar", "ticketingSystem-0.0.1-SNAPSHOT.war"]
