# Python with Node env to run tests

Base image with:
- python 2.7.12
- node v6.9.2
- npm v3.10.9
- yarn 0.18.1
- chromedriver 2.25
- phantomjs 2.1.1

# Docker hub

[joaovitor/python-gcloud-node](https://hub.docker.com/r/joaovitor/python-gcloud-node/)

# Commands


## Build the image
```
docker build -t joaovitor/python-gcloud-node:v2 .
```

## Push the image

```
docker push joaovitor/python-gcloud-node
```
