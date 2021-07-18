# Getting Started

This project was created with html

## Build the Docker Image for the HTML Server

Run the following command: 
### `docker build -t html-server-image:v1 .`
You can confirm that this has worked by running the command: 
### `docker images`

## Run the Docker Container
Run the following command to run the HTML container server:

### `docker run -d -p 80:80 html-server-image:v1`

## Test the Port with curl
### `curl localhost:80`
You can also view it in the browser now by going to [localhost:80](localhost:80) and you should see the HTML file.

## Docker Repository
[https://hub.docker.com/repository/docker/bukunmi00/sca-cloud-school-application](https://hub.docker.com/repository/docker/bukunmi00/sca-cloud-school-application)