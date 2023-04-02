FROM golang:1.16.15

EXPOSE 8080

WORKDIR /app

COPY . .

ENV REQUEST_ORIGIN=http://localhost:5001

RUN go build

CMD ./server

# used command 
# docker run -p 8080:8080 <image-name>