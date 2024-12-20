# [Go](https://go.dev)
> 2024

## Setup

Follow: https://go.dev/doc/install

```sh
sudo apt update
curl -O https://dl.google.com/go/go1.23.4.linux-amd64.tar.gz
rm -rf /usr/local/go && tar -C /usr/local -xzf go1.23.4.linux-amd64.tar.gz
export PATH=$PATH:/usr/local/go/bin
source ~/.bashrc
go --version
```

## Run

```sh
go run hello_world.go
Hello World!
```