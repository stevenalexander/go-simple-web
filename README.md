# Go simple web example

Simple [Golang](https://golang.org/) web example application, based on this [tutorial](https://www.sohamkamani.com/blog/2017/09/13/how-to-build-a-web-application-in-golang/).

## Requires

* [Go](https://golang.org/)

## Run

```
go build
./go-simple-web # runs on http://localhost:8080
```

## Test

```
go test ./...
```

## Notes

* Used [dep](https://github.com/golang/dep) for dependency management
* Commited `vendor` folder as it seems to be the common practise for small projects to include all resolved dependencies