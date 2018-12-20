### Commit container and create a new image

Creates a new image of the container with current changes of the container

`docker commit {{CONTAINER_NAME}} {{IMAGE_NAME}}:{{TAG}}`

- <b>CONTAINER_NAME: </b>Name of the container to commit
- <b>CONTAINER_NAME: </b>Name of the new image which will be created
- <b>TAG: </b>Tag for the commit, which will be assigned to the new image

#### Example:

`docker commit ak-cli ak-cli-new:version2.0`
