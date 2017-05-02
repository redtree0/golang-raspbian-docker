# golang-raspbian-docker

Has a dockerfile that downloads and install golang version 1.8 on a raspberry pi!

This is linked to [dockerhub/askmike/golang-raspbian](https://hub.docker.com/r/askmike/golang-raspbian).

## Usage

Download:

    docker pull askmike/golang-raspbian

Use in a dockerfile that requires golang:

    FROM askmike/golang-raspbian