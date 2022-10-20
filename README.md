# インストール方法
```
go get github.com/takeruun/go-library-sample
```

# 使い方
```go
package main

import (
	sample "github.com/takeruun/go-library-sample"
)

func main() {
	sample.Say()
	sample.SayV1("message")
}
```
```
$ go run main.go
This is sample go libray
Message: message
```
