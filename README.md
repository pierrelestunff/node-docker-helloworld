# node-docker-helloworld

```
# build the image
$ docker build -t <your username>/node-docker-helloworld .

# get the list of the images on the docker-machine
$ docker images

# run the image
$ docker run -p 49160:8080 -d <your username>/node-docker-helloworld

# push the image to docker hub
$ docker push
```
