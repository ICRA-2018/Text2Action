# Text2Action
[![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/icra2018/logos.svg)](https://hub.docker.com/r/icra2018/text2action)
<a href="#how-to-run-with-docker"><img src="https://img.shields.io/badge/Docker-instructions-brightgreen.svg"></a>
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ICRA-2018/Text2Action/master?urlpath=lab%2Ftree%2FREADME.ipynb)

# How to Run with Docker
## Linux / macOS
Tested on:
* Ubuntu 16.04.6 with Docker 18.06.1-ce
* macOS Mojave 10.14.3 with Docker Desktop for Mac 2.0.0.3 (engine: 18.09.2)

1. Open a terminal and run the command:
```
docker run --rm -p 8888:8888 icra2018/text2action:latest
```
2. Run a web browser and open the link: [http://localhost:8888/lab/tree/README.ipynb](http://localhost:8888/lab/tree/README.ipynb)

## Windows
Tested on Windows 10 Home with Docker Toolbox (client: 18.03.0-ce, server: 18.09.3).
1. Open Docker Quickstart Terminal and run the command:
```
docker run --rm -p 8888:8888 icra2018/text2action:latest
```
2. Run a web browser and open the link: [http://192.168.99.100:8888/lab/tree/README.ipynb](http://192.168.99.100:8888/lab/tree/README.ipynb)
(if necessary, replace 192.168.99.100 with the IP address of your Docker machine, as given by the command `docker-machine ip`)
