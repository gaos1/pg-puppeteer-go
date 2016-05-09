# PostgreSQL Puppeteer

A tiny library for manipulating PostgreSQL databases and users written in go

## Installation

Install [govendor](https://github.com/kardianos/govendor).

```
$ go get github.com/altoros/pg-puppeteer-go
$ cd $GOPATH/src/github.com/altoros/pg-puppeteer-go
$ govendor sync
```

## Testing

```
$ export PG_SOURCE=postgresql://postgres:postgres@localhost?sslmode=disable
$ go test -v
```

