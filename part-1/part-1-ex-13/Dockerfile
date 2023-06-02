# BUILD: docker build . -t ex-backend
# RUN: docker run -p 3000:8080 ex-backend

FROM golang:1.16

WORKDIR /usr/src/app

COPY . . 

RUN go build

CMD ["./server"]


