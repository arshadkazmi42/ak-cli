### To Run an image

`docker run -it {{IMAGE_ID}}`

- <b>IMAGE_ID: </b> Docker image ID

#### Flags

`docker run -v {{INPUT_FILE}}:{{CONTAINER_FILE_LOCATION}} {{IMAGE_ID}}`

- <b>-v</b>: This flag takes a file input which will be added to the container

- <b>INPUT_FILE: </b>File to add in the container
- <b>CONTAINER_FILE_LOCATION: </b>Location where file will be stored in the container
- <b>IMAGE_ID: </b> Docker image ID

#### Example

`docker run -it hello-world`

`docker run -v ~/configuration.json:/root/configuration.json hello-world`

<img src="../../gifs/docker-run.gif" alt="Docker run"/> 

#### Related Commands

- [Login to docker container](docker-login.md)
