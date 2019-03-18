### Build Docker Image Using Dockerfile

Creates a new image of using the `Dockerfile`. Run the below command inside your project directory where `Dockerfile` is present

`docker build -t {{IMAGE_NAME}} .`

- <b>IMAGE_NAME: </b>Name for the new image which will get build

#### Example:

`docker build -t ak-cli .`

#### Related Commands

- [Commit docker container](docker-container-commit.md)
- [Create container using image](docker-container-create.md)
- [List Images](docker-images-list.md)