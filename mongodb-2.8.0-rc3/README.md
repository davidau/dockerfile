## mongodb 2.8.0-rc3 Dockerfile


This repository contains **Dockerfile** of [mongodb](http://www.mongodb.org/) 2.8.0-rc3 for Linux based systems for use with [Docker](https://www.docker.com/).


### Base Docker Image

* [ubuntu:14.04](https://registry.hub.docker.com/u/library/ubuntu/)


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://registry.hub.docker.com/u/davidau/mongo/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull davidau/mongo`

   (alternatively, you can build an image from Dockerfile: `docker build -t="davidau/mongo:2.8.0-rc3" github.com/davidau/dockerfile/mongodb-2.8.0-rc3`)


### Usage

    docker run -it davidau/mongo:2.8.0-rc3 /bin/bash
    root@bff709b3b521:/# mongod --fork --syslog
    root@bff709b3b521:/# mongo

### Docker Repository

You can find the built image on this Docker Hub Registry repository: https://registry.hub.docker.com/u/davidau/mongo/