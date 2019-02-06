### Create and run mongo

`docker run -p {{PORT}}:{{PORT}} --name {{CONTAINER_NAME}} -d mongo:{{TAG}}`

- <b>PORT: </b> Port on which mongo will be running/accesed
- <b>CONTAINER_NAME: </b>Name to assign to the container
- <b>TAG: </b>Tag of the mongo DB from [docker hub](https://hub.docker.com/_/mongo?tab=tags)

#### Example:

`docker run -p 27017:27017 --name mongo-server -d mongo:3.2`

## Related

- [Create and run Redis](docker-redis-create.md)
- [Create and run Postgres](docker-postgres-create.md)