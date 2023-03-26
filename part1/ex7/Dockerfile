FROM ubuntu:20.04

WORKDIR /usr/src/app

COPY website.sh .

RUN apt-get update
RUN apt-get -y install curl

CMD bash ./website.sh