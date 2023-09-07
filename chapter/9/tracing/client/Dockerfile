
FROM golang:1.21.0
COPY . /usr/src/client/
WORKDIR /usr/src/client/
RUN go env -w GOPROXY=direct
RUN go install ./main.go
CMD ["/go/bin/main"]
