## Node Vue Bulletin Board

This code is for the Docker intro session given at ACM@UC.

## Installation

1. Run `npm install`.
2. Run `node server.js`.
3. Visit [http://localhost](http://localhost).

## RESTful API

1. **Use Node.js & Express for backend server and router.**
2. **RESTful requests towards the server to simulate CRUD on *events* model, instead of local hardcoded ones.**

## Docker

1. To build this app as a Docker image, run `docker built --tag username/image-name .`.
2. To run the image as a Docker container, run `docker run --detach --publish 80:80 --name container-name username/image-name`.
3. To push the image to Docker Hub, run `docker push username/image-name`.
4. To pull the image from Docker Hub, run `docker pull username/image-name`.
