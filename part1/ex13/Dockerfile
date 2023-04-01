FROM golang:1.16.15

WORKDIR /app

COPY . .

RUN go build

CMD ./server

# command used:
# docker run - 8080:8080 <image-name>