## 工程文件


### vscode 安装go插件

#### 1. Ubuntu环境

* sudo vi ~/.bashrc

```
export GOPATH=/home/xxx/gopath
```

* 下载插件

```
go get -u -v github.com/sqs/goreturns
go get -u -v github.com/mdempsky/gocode
go get -u -v github.com/uudashr/gopkgs/cmd/gopkgs
go get -u -v github.com/ramya-rao-a/go-outline
go get -u -v github.com/acroca/go-symbols
go get -u -v golang.org/x/tools/cmd/guru
go get -u -v golang.org/x/tools/cmd/gorename
go get -u -v github.com/go-delve/delve/cmd/dlv
go get -u -v github.com/stamblerre/gocode
go get -u -v github.com/rogpeppe/godef
go get -u -v golang.org/x/lint/golint
```

* 将已经下载好的插件, vscode的go环境目录, 比如 "C:\Users\Administrator\go\src"

```
gopath.tar.gz
```

* 手动安装插件

```
go install github.com/sqs/goreturns
go install github.com/mdempsky/gocode
go install github.com/uudashr/gopkgs/cmd/gopkgs
go install github.com/ramya-rao-a/go-outline
go install github.com/acroca/go-symbols
go install golang.org/x/tools/cmd/guru
go install golang.org/x/tools/cmd/gorename
go install github.com/go-delve/delve/cmd/dlv
go install github.com/stamblerre/gocode
go install github.com/rogpeppe/godef
go install golang.org/x/lint/golint
```

* 懒人模式, 直接将 "lproj\tar.gz\bin\*.exe" 复制到 "C:\Users\Administrator\go\src\bin"

```
gopath.tar.gz
```
