FROM golang:1.13.1-alpine3.10
EXPOSE 8080
COPY ./main.go ./
RUN go build -o ./go-app ./main.go
USER nobody
ENTRYPOINT ["./go-app"]



