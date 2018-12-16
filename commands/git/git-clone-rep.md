### Copy from local machine to docker container

`docker cp {{SOURCE_DIRECTORY}} {{DOCKER_CONAINER}}:{{DESTINATION_DIRECTORY}}`

- <b>SOURCE_DIRECTORY: </b> Source directory to upload
- <b>DOCKER_CONAINER: </b>Docker container name or ID
- <b>DESTINATION_DIRECTORY: </b>Directory/path where to upload on docker container

#### Example:

`docker cp ak-cli arshad-docker-container:/uploads`
