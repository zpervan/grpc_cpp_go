[![Ubuntu](https://github.com/zpervan/grpc_cpp_go/actions/workflows/ubuntu.yml/badge.svg?branch=main)](https://github.com/zpervan/grpc_cpp_go/actions/workflows/ubuntu.yml)

# gRPC with C++ and Go

Template/example repository for gRPC in combination with C++ an Go.

## Currently, tested on Ubuntu 22.04 ##

### Prerequisites ###

- [Bazel 5.4.0](https://github.com/bazelbuild/bazel/releases/download/5.4.0/bazel_5.4.0-linux-x86_64.deb)
- [Go 1.19.4](https://go.dev/dl/go1.19.4.linux-amd64.tar.gz)
- Gcc 11.3.0

### Setup ###

Besides the above-mentioned prerequisites, also install the following dependencies:
```shell
sudo apt install build-essential autoconf libtool pkg-config
```

### Usage ###

Position your terminal at the root of your repository and execute the following commands:
```shell
bazel run //client:client # Builds and runs the client application
bazel run //server:server # Builds and runs the server application
```
