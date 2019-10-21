### To Push an image to registry

`docker push {{IMAGE_NAME}}`

- <b>IMAGE_NAME: </b> Docker image name

#### Prerequisites

- If authentication is enabled in registry. In oder to push images into registry, [login](docker-registry-login.md) is required.
- <b>Name of the docker image :</b> If you are intend to push an image into a Private registry, the name should be `{{REGISTRY_HOST:REGISTY_PORT/IMAGE_NAME}}`. You can use [docker tag](docker-tag.md) command to rename the image to the specified format.
  - <b>REGISTRY_HOST: </b>Hostname of docker Registry.
  - <b>REGISTRY_PORT: </b>Port on which docker Registry is listening.

#### Example

`docker push hello-world`

`docker push localhost:5000/hello-world`

#### Related Commands

- [Login to docker container](docker-registry-login.md)
- [Tag/Rename a docker image](docker-tag.md)
