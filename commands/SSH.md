## SSH

### Login to a remote server using SSH client


`ssh -i {{KEY_FILE}} {{USER}}@{{IP}}`


- <b>KEY_FILE</b>: *.pem file for authentication
- <b>USER</b>: Username for login to the remote machine
- <b>IP</b>: IP of the machine

#### Example

`ssh -i key.pem arshad@127.0.0.1`