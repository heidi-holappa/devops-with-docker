# BUILD: docker build . -t example-backend
# RUN: docker run -p 3000:8080 example-backend

FROM golang:1.16

WORKDIR /usr/src/app

COPY . . 

RUN go build

CMD ["./server"]


