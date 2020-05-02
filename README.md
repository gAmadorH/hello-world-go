# hello-world-go

[![license](https://img.shields.io/github/license/gAmadorH/hello-world-go.svg?color=blue)](https://github.com/gAmadorH/hello-world-go/blob/master/LICENSE)

a simplest hello world program using go/golang programming language

## code

to code a hello world program, just create a `main.go` file  
with this code in it:

```go
package main

import "fmt"

func main() {
  fmt.Println("hello world!!!")
}

```

## build a program

to build a compiled executable file of your code, just run the next command in your terminal:

```bash
# go build <file-name.go>
go build main.go
```

it only compiles your code, generating a executable file (without running it)  
you can execute it by running:

```bash
# ./executable-file-name
./main
$ hello world!!!
```

if you just run your program quickly just:

```bash
# go run <file-name.go>
go run main.go
$ hello world!!!
```

it only runs your code and shows the output without generating a compiled file

## License

[MIT.](./LICENSE) Copyright (c)
