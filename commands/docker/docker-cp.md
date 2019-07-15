### Copy host to docker container

`docker cp {{SOURCE_DIRECTORY}} {{DOCKER_CONTAINER}}:{{DESTINATION_DIRECTORY}}`

- <b>SOURCE_DIRECTORY: </b> Source directory to upload
- <b>DOCKER_CONTAINER: </b>Docker container name or ID
- <b>DESTINATION_DIRECTORY: </b>Directory/path where to upload on docker container

#### Example:

`docker cp ak-cli arshad-docker-container:/uploads`

#### Related Commands

- [Login to docker container](docker-login.md)
- [Copy file from docker container](docker-cp-from-container.md)
