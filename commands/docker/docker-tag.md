### Provide new tag to docker image

`docker tag {{EXISTING_IMAGE_NAME[:TAG]/ID}} {{NEW_IMAGE_NAME[:TAG]}}}`

- <b>EXISTING_IMAGE_NAME[:TAG]/ID: </b> Name with tag or image id of the image
- <b>NEW_IMAGE_NAME[:TAG]: </b>New name for the existing image. If `[:TAG]` is not provided, by default `:latest` tag will be added.

#### Example:

`docker tag ubuntu ubuntu:new`

#### Related Commands

- [List Images](docker-images-list.md)
