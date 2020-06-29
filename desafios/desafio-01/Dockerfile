#iagem Base
FROM golang:1.14-alpine
#mantedor da imagem
LABEL maintainer="Gêneses Lopes"
#Pasta do projeto
RUN mkdir /app
#definindo pasta padrão do container
WORKDIR /app
#copiando código go
COPY hello.go .
#compilando código
RUN go build -o hello -v ./hello.go
#executando comando
CMD [ "./hello" ]