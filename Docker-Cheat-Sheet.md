# Docker Commands 

| Command                                      | Description                                 |
| -------------------------------------------- | ------------------------------------------- |
| `sudo service docker start`                  | starts docker deamon                        |
| `sudo service docker stop`                   | stops docker deamon                         |
| `sudo service docker status`                 | shows if docker deamon is running           |
| `docker-compose build --no-cache`            | installs docker container using docker file |
| `docker-compose up -d`                       | starts docker containers in background      |
| `docker-compose down`                        | stops docker container                      |
| `docker-exec`                                | to run a command in container               |
| `docker exec -it <container_name> <command>` | to run the command in container             |
| `docker exec -it <container_name> /bin/bash` | to run a bash terminal in container         |
| `docker ps -a`                               | shows the status of containers              |
| `docker rm $(docker ps -aq)`                 | deletes all containers                      |
| `docker stop $(docker ps -q)`                | stops all containers                        |
| `docker rmi $(docker images -q)`             | deletes all docker images                   |
| `docker system prune`                        | delete all related with docker              |
| `docker network ls`                          | list all docker networks                    |







