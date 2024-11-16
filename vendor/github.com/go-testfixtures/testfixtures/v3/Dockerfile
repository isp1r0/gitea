FROM golang:1.23.3-alpine

RUN apk update
RUN apk add alpine-sdk

WORKDIR /testfixtures
COPY . .

RUN go mod download
