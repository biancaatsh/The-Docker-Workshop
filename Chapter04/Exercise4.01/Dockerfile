FROM golang:1.22.4
WORKDIR /myapp
COPY welcome.go .
RUN go build -o welcome .
ENTRYPOINT ["./welcome"]

