# coding-project-template

Hands-on Lab: Introduction to Containers, Docker and IBM Cloud Container Registry 

To make a Local Docker, important commands in VS Code,

VS Code commands for local Docker:

docker images

docker build . -t myimage:v1

docker rmi -f my-node-image:v1 # to remove unwanted images

docker pull node:9.4.0-alpine  # to make the node displays in the docker images

docker run -dp 8080:8080 myimage:v1 # to run docker container in the 8080 port

curl http://localhost:8080

will be stating
Content           : Hello world from c4b1be69cb6c! Your app is up and running!
at http://localhost:8080

docker stop $(docker ps -q) # to stop the Docker run
