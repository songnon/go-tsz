# go-tsz

The original source code was cloned from [github](https://github.com/dgryski/go-tsz/tree/master). Some change was made to
support:

- millisecond timestamp
- 1 hour time window in milliseconds


## Description
 
Package tsz implement the  Gorilla Time Series Databasetime-series compression as described in:
http://www.vldb.org/pvldb/vol8/p1816-teller.pdf


## Getting started

This application is written in Go language, please refer to the guides in https://golang.org for getting started.

This project include a Makefile that allows you to test and build the project with simple commands.
To see all available options:
```bash
make help
```

## Running all tests

Before committing the code, please check if it passes all tests using
```bash
make qa
```
