FROM golang:1.16

WORKDIR /usr/src/app

COPY . . 

# ENV REQUEST_ORIGIN=http://localhost

RUN go build

# CMD ["./server", "REDIS_HOST=redis"]

CMD ["./server"]