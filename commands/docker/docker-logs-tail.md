### Tail Latest Logs from Container

`docker logs --tail {{LINES_COUNT}} -f {{CONTAINER_NAME}}`

- <b>LINES_COUNT: </b> Number of latest log lines to tail. (Remove this from command to tail from top)
- <b>CONTAINER_NAME: </b>Container name or container ID for which logs are needed

#### Example:

`docker logs --tail 100 -f ak-cli-container`
