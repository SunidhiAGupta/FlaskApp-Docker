# FlaskApp-Docker


## Build command

```bash
cd container
docker build -t test-image:0.0.1 .
```

## Run command

```bash
 docker run -it test-image:0.0.1
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


