# Python with Node env to run tests

Base image with:
- python 2.7.12
- node 4.4.5
- npm 2.14.5
- chromedriver 2.25
- phantomjs 2.1.1

# Docker hub

[joaovitor/python-gcloud-node](https://hub.docker.com/r/joaovitor/python-gcloud-node/)

# Commands


## Build the image
```
docker build -t joaovitor/python-gcloud-node:v1 .
```

## Push the image

```
docker push joaovitor/python-gcloud-node
```
