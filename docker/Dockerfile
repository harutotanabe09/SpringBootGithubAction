FROM openjdk:13-alpine

# Create Work Directory
RUN mkdir /usr/app
WORKDIR /usr/app

# Copy Jar
COPY ./*.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]