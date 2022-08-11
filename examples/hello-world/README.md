# hello-world

初始化 Go 程序：

```bash
go mod init main
```

接下来，创建 `main.go` 为程序的入口：

```go
package main

import "fmt"

func main() {
	fmt.Println("Hello, World!")
}
```

> 入口文件的 `package` 必须是 `main`。

## 构建

```bash
go build main
```

## 安装

```bash
go install main
```

> 安装在 `$GOPATH/pkg` 目录下。
