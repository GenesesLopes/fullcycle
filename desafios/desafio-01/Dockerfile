FROM golang:1.14-alpine

RUN mkdir /app

WORKDIR /app

COPY hello.go .

RUN go build -o hello -v ./hello.go

CMD [ "./hello" ]