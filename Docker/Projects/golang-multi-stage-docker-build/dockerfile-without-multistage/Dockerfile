# BASE IMAGE ######

FROM ubuntu AS build

Run apt-get update && apt-get install -y golang-go

ENV GO111MODULE=OFF

COPY

RUN CGO_ENABLED-0 go build -o /app .

ENTRYPOINT ["/app"]
