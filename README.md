# FlaskApp-Docker


## Build command

```bash
cd container
docker build -t test-image:0.0.1 .
```

## Run command

```bash
 docker run -it test-image:0.0.1
 docker run -it -p <container port>:<host port> test-image:0.0.1 
 ```

 ## Exec command (This command is used to run commands inside a container)

 ```bash
 docker exec -it <container id> <command>
 docker exec -it <container id> bash
 ```

 ## To look inside the container

 ```bash
 docker log <container-id>
  ```

  ## To push a docker image to docker hub

  ```bash
  docker tag <image-id> <docker hub user-name>/<image-name>:<version>
  docker push <docker hub user-name>/<image-name>:<version>
  ```

  ## To pull image from docker hub
  ```bash
  docker pull <image name>
  ```


