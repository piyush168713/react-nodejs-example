## Push image to Private Repository (Docker Hub)

### Login to docker hub
```sh
  docker login
```

### Create Docker image
```sh
  docker build -t 6.0 .
```

### Tag the image
```sh
  docker tag 6.0:latest username/repo-name:6.0
```

### Check the Docker image locally
```sh
  docker images
```

### Push image to Docker Hub
```sh
  docker push username/repo-name:6.0
```
