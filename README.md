# Text2Action
[![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/icra2018/logos.svg)](https://hub.docker.com/r/icra2018/text2action)
<a href="#how-to-run-with-docker"><img src="https://img.shields.io/badge/Docker-instructions-brightgreen.svg"></a>
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ICRA-2018/Text2Action/master?urlpath=lab%2Ftree%2FREADME.ipynb)

# How to Run with Docker
Tested on:
* Ubuntu 16.04.6 with [Docker 18.06.1-ce](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
* macOS Mojave 10.14.3 with [Docker Desktop for Mac 2.0.0.3 (engine: 18.09.2)](https://hub.docker.com/editions/community/docker-ce-desktop-mac)
* Windows 10 Education with [Docker Desktop for Windows 2.0.0.3 (engine: 18.09.2)](https://hub.docker.com/editions/community/docker-ce-desktop-windows)

1. Open a terminal in Linux/macOS or a PowerShell in Windows and run the command:
```
docker run --rm -p 8888:8888 icra2018/text2action:latest
```
2. Run a web browser and open the link: [http://localhost:8888/lab/tree/README.ipynb](http://localhost:8888/lab/tree/README.ipynb)
