FROM golang:1.16

EXPOSE 8080

WORKDIR /app

COPY . .

RUN go build

RUN go test ./...

ENV REQUEST_ORIGIN=http://localhost:8080/ping

CMD ./server