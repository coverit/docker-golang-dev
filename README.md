# docker-golang-dev

> Docker image of Ubuntu 14.04 with Golang, godep, MongoDB

## Features

- Go 1.4.2
- MongoDB 3.0.3
- godep
- node.js 0.12.3 with npm 2.9.1

## Getting Started

    docker run coverit/golang-dev /bin/bash

boot2docker ssh "echo $'EXTRA_ARGS=\"--registry-mirror=http://c3de84d2.m.daocloud.io\"' | sudo tee -a /var/lib/boot2docker/profile && sudo /etc/init.d/docker restart"'"
## License

MIT license
