# Contributing

## Requirements for local development

- Docker

## Run locally

1. Git clone this repository
2. On the repository folder, build the docker image with `sh cli/blog.sh build-docker-image`
3. Start the server with `sh cli/blog.sh start-server`

To build the static content run `sh cli/blog.sh build-layout`. **On the first time or if there are changes in the static files, it is necessary to copy them to server/static.**

## Deploy

?