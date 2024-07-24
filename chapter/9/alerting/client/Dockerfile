
FROM golang:1.23rc2-bookworm

COPY . /usr/src/client/
WORKDIR /usr/src/client/
RUN go env -w GOPROXY=direct
RUN go install ./main.go
CMD ["/go/bin/main"]
