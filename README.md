# default-python-flask

## Description
This project contain the most minimal python flask application that build with docker.

## Dependency
```
python 3.8
flask 2.1.2
```

## Function
This flask application listen on port `5000` and has only one endpoint `GET /` that return `Hello World` message.

## Installation
There are two methods to run this application.

1. Download and run this repo
   - Download this repo.
   - Run `docker-compose up -d` at root directory.

2. Download and run from docker hub
   - Run `docker pull puttimeth/default-python-flask`
   - Run `docker run -p 5000:5000 -d puttimeth/default-python-flask`
