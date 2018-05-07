# kubernetes-in-action

Code from Kubernetes in Action book

## Commands from Chapter 2

* Build the Docker image:

```
docker build -t kubia .
```

where `kubia` was the tag name adopted in the book.

* Listing locally stored images

```
docker images
```

* Running the container image

```
docker run --name kubia-container -p 8080:8080 -d kubia
```

* List running containers

```
docker ps
```

* Get additional info about a container

```
docker inspect <container_name>
```

* Running a shell inside a container

```
docker exec -it <container_name> bash
```

* Stop a container

```
docker stop <container_name>
```

* List all containers

```
docker ps -a
```

* Remove a container

```
docker rm <container_name>
```

* Add a tag to a image

```
docker tag <source_image>[:tag] <target_image>[:tag]
```

* List Docker images

```
docker images
```

* Login to DockerHub via terminal

```
docker login
```

* Push image to DockerHub: `<image>` needs to start with `<user_id>/`

```
docker push <image>
```

