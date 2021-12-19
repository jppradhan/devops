## Docker compose commands

```
Docker compose up starts up all the containers.

Docker compose ps checks the status of the containers managed by docker compose.

Docker compose logs outputs colored and aggregated logs

for the compose-managed containers.

Docker compose logs with -f option outputs appended log when the log grows.

Docker compose logs with the container name,

in the end, outputs the logs of a specific container.

Docker compose stop stops all the running containers without removing them.

Docker compose rm removes all the containers.

Docker compose build rebuilds all the images.
```

### Create a none network
`docker run -d --net none busybox sleep 1000`

### create a bridge network
`docker network create --driver bridge my_bridge_network`

#### connect with bridge network
`docker network connect bridge container_3`



### Overlay network
