## hello-go
#### go项目工程化实践的样板项目
```
// 新建文件夹
mkdir hello-go
```

```
// 初始化项目
go mod init github.com/fastbpmn/hello-go
```

```
// 启动项目
go run main.go
// 在Windows环境，也可以依次执行下面的命令启动
go build github.com/fastbpmn/hello-go
hello-go.exe
```

```
// 发送测试请求
curl localhost:9090 -d Test
curl localhost:9090/goodbye
```