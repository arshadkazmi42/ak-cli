# CLI Commands
List of some daily used commands for tech geeks.

## SSH

### Login to a remote server using SSH client


`ssh -i KEY_FILE USER@IP`


- <b>KEY_FILE</b>: *.pem file for authentication
- <b>USER</b>: Username for login to the remote machine
- <b>IP</b>: IP of the machine

#### Example

`ssh -i key.pem arshad@127.0.0.1`


## SCP

### Local Machine to Server

`scp  -i KEY_FILE FILE_TO_COPY USER@IP:UPLOAD_LOCATION`

- <b>KEY_FILE</b>: *.pem file for authentication
- <b>FILE_TO_COPY</b>: File name which  needs to be copied
- <b>USER</b>: Username for login to the remote machine
- <b>IP</b>: IP of the machine
- <b>UPLOAD_LOCATION</b>: Destination path on the server where file needs to be copied to.

#### Example:

`scp -i key.pem commands.zip arshad@0.0.0.0:/home/arshad`

### Server to Local Machine

`scp -i KEY_FILE USER@IP:FILE_PATH LOCAL_PATH`

- <b>KEY_FILE</b>: *.pem file for authentication
- <b>USER</b>: Username for login to the remote machine
- <b>IP</b>: IP of the machine
- <b>FILE_PATH</b>: Path of the file on server
- <b>LOCAL_PATH</b>: Path to store file in local machine

#### Example

`scp -i key.pem arshad@0.0.0.0:/home/arshad/commands.zip /home/arshad/oss/commands.zip`