# go-grab-xkcd

From https://eryb.space/2020/05/27/diving-into-go-by-building-a-cli-application.html


* go.mod - Go Modules file used in Go for package management
* main.go - Main entrypoint of the application
* comic.go - Go representation of the data as a struct and operations on it
* xkcd.go - xkcd client for making HTTP calls to the API, parsing response and saving to disk

Run the program as follows-

```bash
$ go run main.go -n 323 -o json
```

Or build it as an executable binary for your laptop and then run-

```bash
$ go build .
$ ./go-grab-xkcd -n 323 -s -o json
```