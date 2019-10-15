### Cleaning up docker to reclaim disk space

When the disk space was "leaking” somewhere and you're not able to tell where it went,
clean the unused storage of the docker using this command :

`docker system prune`

#### Example:

`docker system prune` <br>
                     
WARNING! This will remove:<br>
- all stopped containers
- all networks not used by at least one container
- all dangling images
- all build cache<br>

Are you sure you want to continue? `[y/N]` y
                     
Deleted Containers:
- f44f9b81948b3919590d5f79a680d8378f1139b41952e219830a33027c80c867
- 792776e68ac9d75bce4092bc1b5cc17b779bc926ab04f4185aec9bf1c0d4641f
                     
Deleted Networks:
- network1
- network2
                     
Deleted Images:
- untagged: hello-world@sha256:f3b3b28a45160805bb16542c9531888519430e9e6d6ffc09d72261b0d26ff74f
- deleted: sha256:1815c82652c03bfd8644afda26fb184f2ed891d921b20a0703b46768f9755c57
- deleted: sha256:45761469c965421a92a69cc50e92c01e0cfa94fe026cdd1233445ea00e96289a
                     
Total reclaimed space: 1.84kB


#### Related Commands

- `docker volume prune`
- `docker container prune`
- `docker image prune`
- `docker network prune`
