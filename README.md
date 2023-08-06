[![Go Version](https://img.shields.io/badge/go-1.20-brightgreen.svg)](https://go.dev/)

* Go Web App using MySQL

Run tests:
```shell
go test ./cmd/web/
```

Run specific test:
```shell
go test -v -run="^TestPing$" ./cmd/web/
```

Run tests without cache:
```shell
go test -count=1 ./cmd/web
```

### How do I get set up? ###

* Install Go [https://go.dev/doc/install](https://go.dev/doc/install)
* Add GOPATH on macOS [https://tecadmin.net/install-go-on-macos/](https://tecadmin.net/install-go-on-macos/)
* on Ubuntu [https://www.cyberciti.biz/faq/how-to-install-gol-ang-on-ubuntu-linux/](https://www.cyberciti.biz/faq/how-to-install-gol-ang-on-ubuntu-linux/) 
* In GoLand [https://www.jetbrains.com/help/go/configuring-goroot-and-gopath.html](https://www.jetbrains.com/help/go/configuring-goroot-and-gopath.html)
