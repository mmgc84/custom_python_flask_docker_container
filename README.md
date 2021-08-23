# Custom python flask docker container

Note: Check Dockerfile used to generate the new image

To build an image run:

$ docker build -t IMAGE_NAME .

To start a container exposing an external port run:

$ docker run --name CONTAINER_NAME -d -p 5001:5000 IMAGE_NAME


