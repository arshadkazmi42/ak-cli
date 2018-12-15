### Create and run mongo

`docker run -p {{PORT}}:{{PORT}} --name {{CONTAINER_NAME}} -d mongo:{{TAG}}`

- <b>PORT: </b> Port on which mongo will be running/accesed
- <b>CONTAINER_NAME: </b>Name to assign to the container
- <b>TAG: </b>Tag of the mongo DB from [docker hub](https://hub.docker.com/_/mongo?tab=tags)

#### Example:

`docker run -p 27017:27017 --name mongo-server -d mongo:3.2`

### Create and run redis

`docker run -d -p {{PORT}}:{{PORT}} --name {{CONTAINER_NAME}} redis`

- <b>PORT: </b> Port on which redis will be running/accessed
- <b>CONTAINER_NAME: </b>Name to assign to the container

#### Example

`docker run -d -p 6379:6379 --name redis redis`

### Create and run Postgres

`docker run -p {{PORT}}:{{PORT}} --name {{CONTAINER_NAME}} -e POSTGRES_DB={{DB_NAME}} -e POSTGRES_USER={{DB_USER_NAME}} -e POSTGRES_PASSWORD={{DB_PASSWORD}} -d postgres`

- <b>PORT: </b> Port on which postgres will be running/accesed
- <b>CONTAINER_NAME: </b> Name to assign to the container
- <b>DB_NAME: </b> Databse name which needs to be created.
- <b>DB_USER_NAME: </b> Username for database login
- <b>DB_PASSWORD: </b> Password for the above database login user

#### Example
`docker run -p 5432:5432 --name postgres-server -e POSTGRES_DB=ak-cli -e POSTGRES_USER=arshad -e POSTGRES_PASSWORD=arshad -d postgres`