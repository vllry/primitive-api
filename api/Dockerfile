FROM golang:1.10
# https://hub.docker.com/_/golang/

WORKDIR /go/src/app
COPY . .

RUN go get -d -v ./...
RUN go install -v ./...

CMD ["app"]
