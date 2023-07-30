
FROM golang:1.21rc3
COPY . /usr/src/server/
WORKDIR /usr/src/server/
RUN go install
CMD ["/go/bin/petstore", "--grpcTraces", "--traceSampling=.1"]
