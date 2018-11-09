# golang-raspbian-docker

Has a dockerfile that downloads and install golang version 11.0 on a raspberry pi!

This is linked to [dockerhub/askmike/golang-raspbian](https://hub.docker.com/r/askmike/golang-raspbian).

<pre>
$ git clone https://github.com/redtree0/golang-raspbian-docker.git
$ cd golang-raspbian-docker
$ docker build -t redtree941/golang-raspbian-docker .
</pre>

## Usage

Download:
8
    docker pull askmike/golang-raspbian

Use in a dockerfile that requires golang:

    FROM askmike/golang-raspbian
