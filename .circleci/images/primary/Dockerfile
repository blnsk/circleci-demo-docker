FROM golang:1.8.0

ADD /tmp/build/arr.tar.gz arr.tgz

RUN apt-get update && apt-get install -y netcat
RUN go get github.com/jstemmer/go-junit-report
