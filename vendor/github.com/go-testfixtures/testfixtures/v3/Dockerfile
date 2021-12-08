FROM golang:1.16.8-alpine

RUN apk update
RUN apk add alpine-sdk

WORKDIR /testfixtures
COPY . .

RUN go mod download
