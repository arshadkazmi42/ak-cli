### Save Image as Package

`docker save -o {{OUTPUT_FILE}} {{IMAGE_NAME}}`

- <b>IMAGE_NAME: </b> Name or image id of the image to save
- <b>OUTPUT_FILE.tar: </b>Output file name (extension .tar or something similar can be used)

#### Example:

`docker save -o ak-cli.tar ak-cli`


#### Related Commands

- [Load Saved Image](docker-load.md)
- [List Images](docker-images-list.md)
- [Delete docker image](docker-image-rm.md)