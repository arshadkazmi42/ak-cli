### Create image from tarball

Import the contents from a tarball to create a image

`docker import {{FILE|URL}} {{IMAGE_NAME}}`

- <b>FILE|URL:</b> Path or url to the tarball
- <b>IMAGE_NAME:</b> Name:tag of the newly created docker image

#### Example:

`docker import /path/ak-cli.tar ak-cli:latest`


#### Related Commands

- [Load Saved Image](docker-load.md)
- [Save docker image](docker-save.md)
- [List Images](docker-images-list.md)
- [Delete docker image](docker-image-rm.md)
