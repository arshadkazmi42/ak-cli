### Login to docker registry

`docker login [-u {{USERNAME}}] [-p {{PASSWORD}}] [SERVER]`

- <b>SERVER: </b> Private registry URL. Ignoring this argument defaults to [Docker Hub](https://hub.docker.com).

#### Flags:

- <b>-u: </b> Username for Private registry
- <b>-p: </b> Password for Private registry
- <b>--password-stdin: </b> Takes password for Private registry from STDIN

#### Example:

`docker login`

`docker login -u admin -p nononeknows localhost:5000`
