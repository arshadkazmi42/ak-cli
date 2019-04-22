### Get Container IP

`docker inspect -f '{{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}' {{CONTAINER_NAME}}`

- <b>CONTAINER_NAME: </b> Name or ID of the container

#### Example:

`docker inspect -f '{{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}' ak-cli-container`


#### Related Commands

- [Create container using image](docker-container-create.md)
- [Run docker container using an image id](docker-run.md)