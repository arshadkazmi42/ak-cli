### Create and run redis

`docker run -d -p {{PORT}}:{{PORT}} --name {{CONTAINER_NAME}} redis`

- <b>PORT: </b> Port on which redis will be running/accessed
- <b>CONTAINER_NAME: </b>Name to assign to the container

#### Example

`docker run -d -p 6379:6379 --name redis redis`

## Related

- [Create and run Mongo](docker-mongo-create.md)
- [Create and run Postgres](docker-postgres-create.md)