# express_docker

## About

Used tutorial [Dockerizing a Node.js web app](https://nodejs.org/en/docs/guides/nodejs-docker-webapp/)

## Use

docker build . -t hmi:0.1

docker run -p 49160:8080 -d hmi:0.1