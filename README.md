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
docker inspect kubia-container
```

