
A practical reference for commonly used **Docker CLI commands**, explaining what each command does and how it’s typically used during development and container management.

---
### `Structure`

##### ==`Images`==

- `docker build -t <name>:<tag> .` — build image from Dockerfile
- `docker images` — list local images
- `docker rmi <image>` — remove image
- `docker pull <image>:<tag>` — download image from registry
- `docker push <image>:<tag>` — upload image to registry
- `docker tag <image> <new-name>:<tag>` — tag image


##### ==`Containers`==

- `docker run <image>` — run container from image
- `docker run -it <image> /bin/bash` — run interactively with shell
- `docker run -d <image>` — run in background (detached)
- `docker run -p <host>:<container> <image>` — map ports
- `docker run --name <name> <image>` — assign container name
- `docker ps` — list running containers
- `docker ps -a` — list all containers
- `docker stop <container>` — stop container
- `docker start <container>` — start container
- `docker restart <container>` — restart container
- `docker rm <container>` — remove container


##### ==`Execution & Debugging`==

- `docker exec -it <container> /bin/bash` — open shell inside container
- `docker logs <container>` — view logs
- `docker logs -f <container>` — stream logs
- `docker inspect <container>` — detailed container info


##### ==`Volumes`==

- `docker volume create <name>` — create volume
- `docker volume ls` — list volumes
- `docker volume rm <name>` — remove volume
- `docker run -v <volume>:/app <image>` — mount named volume
- `docker run -v $(pwd):/app <image>` — bind mount current directory


##### ==`Networking`==

- `docker network ls` — list networks
- `docker network create <name>` — create network
- `docker network rm <name>` — remove network
- `docker run --network <network> <image>` — connect container to network


##### ==`Compose`==

- `docker compose up` — start services
- `docker compose up -d` — start in background
- `docker compose down` — stop and remove services
- `docker compose build` — build services


##### ==`Cleanup`==

- `docker system prune` — remove unused data (containers, images, networks)
- `docker container prune` — remove stopped containers
- `docker image prune` — remove unused images
- `docker volume prune` — remove unused volumes


##### ==`Common Flags`==

- `-d` — detached mode
- `-it` — interactive terminal
- `-p` — port mapping
- `-v` — volume mount
- `--name` — assign container name
- `--rm` — auto-remove after stop

---
### `Connected Notes`

- [[Docker]]