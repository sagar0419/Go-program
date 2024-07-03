
FROM golang:1.21.11
COPY . /usr/src/server/
WORKDIR /usr/src/server/
RUN go install
CMD ["/go/bin/petstore", "--grpcTraces", "--traceSampling=.1"]
