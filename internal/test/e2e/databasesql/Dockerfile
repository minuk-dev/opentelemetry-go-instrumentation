FROM golang:1.21.6
WORKDIR /sample-app
COPY . .
RUN go mod init go.opentelemetry.io/auto/internal/test/e2e/databasesql && go mod tidy && go build -o main
