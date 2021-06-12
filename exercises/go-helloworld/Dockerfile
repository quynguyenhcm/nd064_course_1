FROM golang:alpine
LABEL maintainer="Quy Nguyen"
WORKDIR /go/src/app
ADD . .
RUN go mod init 
RUN go build  -o helloworld
EXPOSE 6111
CMD ["./helloworld"]