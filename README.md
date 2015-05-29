# docker-golang-dev

> Docker image of Ubuntu 14.04 with Golang, MongoDB, Git, godep and node.js

[![Docker Repository on Quay.io](https://quay.io/repository/coverit/docker-golang-dev/status "Docker Repository on Quay.io")](https://quay.io/repository/coverit/docker-golang-dev)

## Features

- Golang 1.4.2
- Git 1.9.1
- MongoDB 3.0.3
- godep
- node.js 0.12.3 with npm 2.9.1
- lcov 1.10

## Getting Started

    docker run -it -v $PWD:/go/src/github.com/coverit/coverit coverit/golang-dev /bin/bash

## License

MIT license
