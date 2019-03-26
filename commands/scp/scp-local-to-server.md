
### Local Machine to Server

`scp  -i {{KEY_FILE}} {{FILE_TO_COPY}} {{USER}}@{{IP}}:{{UPLOAD_LOCATION}}`

- <b>KEY_FILE</b>: *.pem file for authentication
- <b>FILE_TO_COPY</b>: File name which  needs to be copied
- <b>USER</b>: Username for login to the remote machine
- <b>IP</b>: IP of the machine
- <b>UPLOAD_LOCATION</b>: Destination path on the server where file needs to be copied to.

#### Example:

`scp -i key.pem commands.zip arshad@0.0.0.0:/home/arshad`

#### Related

- [Copy from server to local](scp-server-to-local.md)