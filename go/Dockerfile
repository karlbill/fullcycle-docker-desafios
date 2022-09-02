FROM golang:1.18

WORKDIR /usr/src/app

RUN go mod init carlosabdalla/desafiogo

RUN go build -v -o /usr/local/bin/app ./

RUN go run ./hello.go

CMD ["app"]