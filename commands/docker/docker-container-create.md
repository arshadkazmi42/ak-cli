### Create docker container using image

Creates a new docker container using a loaded image

`docker create -p {{PORT}}:{{PORT}} --env-file {{ENV_FILE}} --name {{CONTAINER_NAME}} {{IMAME_ID}}`

- <b>PORT: </b>Port on which container needs to be run
- <b>ENV_FILE: </b>ENV file to set environment variables inside docker container
- <b>CONTAINER_NAME: </b>Name which will be assigned to the newly created container

#### Example:

`docker create -p 8080:8080 --env-file ak-cli-prod.env --name ak-cli ak-cli-image`

**Note:** `--env-file` and `--name` flags are optional

#### Related Commands

- [Commit docker container](docker-container-commit.md)
- [Copy file to docker container](docker-cp.md)
- [Delete docker container](docker-container-rm.md)
- [List Containers](docker-container-list.md)
- [Login to docker container](docker-login.md)
- [Tail docker container logs](docker-logs-tail.md)
