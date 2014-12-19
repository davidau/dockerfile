## mongodb 2.8.0-rc3 Dockerfile


This repository contains [Docker](https://www.docker.com/) **Dockerfile** of [mongodb](http://www.mongodb.org/) 2.8.0-rc3 for Linux based systems.


### Base Docker Image

* [ubuntu:14.04](https://registry.hub.docker.com/u/library/ubuntu/)


### Installation

1. Install [Docker](https://www.docker.com/).

2. You can build the image from Dockerfile: `docker build -t="mongo:2.8.0-rc3" github.com/davidau/dockerfile/mongodb-2.8.0-rc3`)


### Usage

    docker run -it mongo:2.8.0-rc3 /bin/bash