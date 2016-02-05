# docker-python27

A Docker image running Ubuntu:trusty with Python 2.7, used as based for

  - https://github.com/ampervue/docker-python27-ffmpeg

  - https://github.com/ampervue/docker-python27-opencv


### To Build

~~~~
docker build -t <imageName> .
~~~~

### To pull and run from hub.docker.com

Docker Hub: https://registry.hub.docker.com/u/dkarchmervue/python27

Source and example: https://github.com/ampervue/docker-python27

~~~~
docker pull dkarchmervue/python27
docker run --rm -ti dkarchmervue/python27 python --version
docker run --rm -ti -v ${PWD}:/work dkarchmervue/python27 python your-python-script.py
docker run --rm -ti dkarchmervue/python27 bash
~~~~

## Python 3.4

For Python 3.4, use https://github.com/ampervue/docker-python34


