# guiCalc

## a simple web-based GUI Calculator

### designed using python language and flask framework

# Run as a Docker Container
-- create Dockerfile
-- build Dockerfile 
$ docker build .
-- tag docker image 
$ docker tag image-ID guicalc:v1
-- run docker container 
$ docker container run -itd --name guicalc -p 7000:7000 guicalc:v1

#Test app on browser
$ curl host-IP:7000


