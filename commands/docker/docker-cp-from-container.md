### Copy from docker container to host

`docker cp {{DOCKER_CONTAINER}}:{{SOURCE_LOCATION}} {{DESTINATION_LOCATION}} `

- <b>DOCKER_CONTAINER: </b>Source docker container name or ID
- <b>SOURCE_LOCATION: </b>Absolute file path on docker container
- <b>DESTINATION_LOCATION: </b>Relative file path on host

#### Example:

`docker cp arshad-docker-container:/downloads/ak-cli.zip ak-cli.zip`

#### Related Commands

- [Login to docker container](docker-login.md)
- [Copy file to docker container](docker-cp.md)
