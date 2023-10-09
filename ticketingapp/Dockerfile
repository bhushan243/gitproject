FROM openjdk:11

COPY ticketingapp/target/ticketingSystem-0.0.1-SNAPSHOT.war /usr/app

WORKDIR /usr/app

ENTRYPOINT ["java", "-jar", "ticketingSystem-0.0.1-SNAPSHOT.war"]