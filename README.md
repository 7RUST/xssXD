# xssXD

A tool made to detect xss vulnerablities in a list of urls. It takes input from the stdin.

# How to install 
```go get github.com/noobexploiter/xssXD```

# How to use
```
Usage of ./xssXD:
  -c int
        Set the Concurrency  (default 50)
  -s string
        Specify the payload to use (default "none")
```
* Set Concurrency according to your need, default 50
* Specify the payload to use. If not specified, it will check for characters <'"> by default

`cat urls.txt | xssXD -c 100`

# Additional Info

The list of urls must be in the format ```protocol://subdomain/path?querys```
