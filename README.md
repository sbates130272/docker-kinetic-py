## Seagate Kinetic Python Client API Dockerfile


This repository contains **Dockerfile** of [seagate/kinetic-py](https://github.com/Seagate/kinetic-py.git) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/sbates130272/kinetic-py) published to the public [Docker Hub Registry](https://registry.hub.docker.com/).


### Base Docker Image

* [dockerfile/ubuntu](http://dockerfile.github.io/#/ubuntu)


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://registry.hub.docker.com/u/sbates130272/kinetic-py/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull sbates130272/kinetic-py`

   (alternatively, you can build an image from Dockerfile: `docker build -t="sbates130272/kinetic-sim" github.com/sbates130272/docker-kinetic-sim`)

### Usage

1. Run this image in interactive mode using `docker run -it sbates130272/kinetic-py`
2. Run the simple test `python test/simple.py -i <IP> -p <PORT>` where `<IP>` and `<PORT>` point to either a real Kinetic drive or the simulator (for my docker image of the simulator see either [docker](https://registry.hub.docker.com/u/sbates130272/kinetic-sim/) or [github](https://github.com/sbates130272/docker-kinetic-sim.git).
