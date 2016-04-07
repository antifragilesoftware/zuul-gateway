# Sample Spring Boot Service that creates a Zuul Reverse Proxy Gateway

## To Build into Docker using Maven

First make sure you're running in an environment that has docker available to you. Then execute:

$ mvnw package docker:build

Once completed you will have an antifragilesoftware/zuul-gateway image available, as seen by executing:

$ docker images

```
REPOSITORY                         TAG                 IMAGE ID            CREATED             SIZE
antifragilesoftware/zuul-gateway   latest              6efd07dc12fc        5 seconds ago       667.1 MB
```
