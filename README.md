# express_docker

## About

Used tutorial [Dockerizing a Node.js web app](https://nodejs.org/en/docs/guides/nodejs-docker-webapp/)

https://blog.risingstack.com/how-to-debug-a-node-js-app-in-a-docker-container/

## Use

docker build . -t hmi:0.1

docker run -p 49160:8080 -d hmi:0.1

docker logs cool_moore

docker logs -f cool_moore

docker kill cool_moore

docker exec -it agitated_ellis /bin/bas