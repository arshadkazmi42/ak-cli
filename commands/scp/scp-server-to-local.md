
### Server to Local Machine

`scp -i {{KEY_FILE}} {{USER}}@{{IP}}:{{FILE_PATH}} {{LOCAL_PATH}}`

- <b>KEY_FILE</b>: *.pem file for authentication
- <b>USER</b>: Username for login to the remote machine
- <b>IP</b>: IP of the machine
- <b>FILE_PATH</b>: Path of the file on server
- <b>LOCAL_PATH</b>: Path to store file in local machine

#### Example

`scp -i key.pem arshad@0.0.0.0:/home/arshad/commands.zip /home/arshad/oss/commands.zip`

#### Related

- [Copy from local to server](scp-local-to-server.md)