OAuth 1.0 Library for Go
========================

Developing your own apps, with this library
-------------------------------------------

* First, install the library
    go get github.com/mrjones/oauth

* Then, check out the comments in oauth.go

* Or, have a look at the examples:

** Netflix
go run examples/netflix/netflix.go --consumerkey <key> --consumersecret <secret> --appname <appname>

** Twitter
go run examples/twitter/twitter.go --consumerkey <key> --consumersecret <secret>    

** The Google Latitude example is broken, now that Google uses OAuth 2.0

Contributing to this library
----------------------------

* Please install the pre-commit hook, which will run tests, and go-fmt before committing.
    ln -s $PWD/pre-commit.sh .git/hooks/pre-commit

* Running tests and building is as you'd expect:
    go test *.go
    go build *.go




