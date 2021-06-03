# GOPATH := ${PWD}
# export GOPATH

all: setup build vet

setup:
	go get github.com/go-sql-driver/mysql
	go get github.com/gorilla/sessions
	go get github.com/jmoiron/sqlx
	go get github.com/labstack/echo
	go get github.com/labstack/echo-contrib/session
	go get github.com/labstack/echo/middleware

build:
	go build

vet:
	go vet ./isubata.go
