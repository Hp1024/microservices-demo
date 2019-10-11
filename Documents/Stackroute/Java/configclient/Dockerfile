FROM openjdk:11
ADD ./target/configclient-0.0.1-SNAPSHOT.jar /usr/src/configclient-0.0.1-SNAPSHOT.jar
WORKDIR usr/src
ENTRYPOINT ["java","-jar", "configclient-0.0.1-SNAPSHOT.jar"]