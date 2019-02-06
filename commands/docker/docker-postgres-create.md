### Create and run Postgres

`docker run -p {{PORT}}:{{PORT}} --name {{CONTAINER_NAME}} -e POSTGRES_DB={{DB_NAME}} -e POSTGRES_USER={{DB_USER_NAME}} -e POSTGRES_PASSWORD={{DB_PASSWORD}} -d postgres`

- <b>PORT: </b> Port on which postgres will be running/accesed
- <b>CONTAINER_NAME: </b> Name to assign to the container
- <b>DB_NAME: </b> Databse name which needs to be created.
- <b>DB_USER_NAME: </b> Username for database login
- <b>DB_PASSWORD: </b> Password for the above database login user

#### Example
`docker run -p 5432:5432 --name postgres-server -e POSTGRES_DB=ak-cli -e POSTGRES_USER=arshad -e POSTGRES_PASSWORD=arshad -d postgres`

## Related

- [Create and run Mongo](docker-mongo-create.md)
- [Create and run Redis](docker-redis-create.md)