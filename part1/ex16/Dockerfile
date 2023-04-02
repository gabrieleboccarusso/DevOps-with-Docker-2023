FROM openjdk:17-jdk-slim

WORKDIR /app

COPY . . 

EXPOSE 8080

# security parameters
ARG USERNAME
ARG PASSWORD

RUN ./mvnw clean package
CMD java -jar ./target/boccarusso-3.0.0.jar

# description
# this dockerfile is used to deploy the backend of my
# personal website wrote in spring boot. It simply
# gets the code and uses the maven wrapper to create
# the package for then running the jar created into
# the target container

# link
# https://boccarusso.com/
# looking into the website it is possible to see that
# every image and content is downloaded from the
# deployed backend. I have not put the link directly
# to the backend as I may change service in the 
# future