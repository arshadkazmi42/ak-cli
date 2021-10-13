<div align="center">

<img src='https://github.com/arshadkazmi42/ak-cli/blob/master/assets/akcli.png' height="80">

List of some daily used commands for tech geeks.

<a href="https://www.buymeacoffee.com/arshadkazmi42" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>
<a href="https://www.patreon.com/bePatron?u=15454240" target="_blank"><img src="https://c5.patreon.com/external/logo/become_a_patron_button.png" alt="Become a Patron!" height="40"></a>

Please consider donating, if you like my work

Give us a :star: if you like our work :heart:

</div>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![Github Repo Size](https://img.shields.io/github/repo-size/arshadkazmi42/ak-cli.svg)](https://github.com/arshadkazmi42/ak-cli)
[![LICENSE](https://img.shields.io/github/license/arshadkazmi42/ak-cli.svg)](https://github.com/arshadkazmi42/ak-cli/LICENSE)
[![Contributors](https://img.shields.io/github/contributors/arshadkazmi42/ak-cli.svg)](https://github.com/arshadkazmi42/ak-cli/graphs/contributors)
[![Commit](https://img.shields.io/github/last-commit/arshadkazmi42/ak-cli.svg)](https://github.com/arshadkazmi42/ak-cli/commits/master)
[![Issues](https://img.shields.io/github/issues/arshadkazmi42/ak-cli.svg)](https://github.com/arshadkazmi42/ak-cli/issues)
[![Pull Requests](https://img.shields.io/github/issues-pr/arshadkazmi42/ak-cli.svg)](https://github.com/arshadkazmi42/ak-cli/pulls)

## Contents

- [Docker](#docker)
- [Git](#git)
- [Heroku](#heroku)
- [Kafka](#kafka)
- [Linux](#linux)
- [Mongo](#mongo)
- [NPM](#npm)
- [PSQL](#psql)
- [Python](#python)
- [SCP](#scp)
- [SSH](#ssh)
- [tar](#tar)
- [zip](#zip)
- [pm2](#pm2)


## Docker

- [Build image](commands/docker/docker-build-image-with-dockerfile.md) - Build docker image using `Dockerfile`.
- [Commit container](commands/docker/docker-container-commit.md) - Commit current state of docker container to save as a new image.
- [Copy to container](commands/docker/docker-cp.md) - Copy file/directory to docker container.
- [Copy from container](commands/docker/docker-cp-from-container.md) - Copy file/directory from docker container.
- [Create and run mongo](commands/docker/docker-mongo-create.md) - Pull mongo docker image from docker registry and create & run mongo container.
- [Create and run postgres](commands/docker/docker-postgres-create.md) - Pull postgres docker image from docker registry and create & run postgres container.
- [Create and run redis](commands/docker/docker-redis-create.md) - Pull redis docker image from docker registry and create & run redis container.
- [Create container](commands/docker/docker-container-create.md) - Create container using a docker image.
- [Delete container](commands/docker/docker-container-rm.md) - Delete a stopped docker container.
- [Delete image](commands/docker/docker-image-rm.md) - Delete an unused docker image.
- [Get Container IP](commands/docker/docker-container-ip.md) - Get docker container's local IP Address.
- [Import image](commands/docker/docker-import.md) - Import docker image from a tar ball package.
- [Inspect Container](commands/docker/docker-inspect.md) - Inspect docker container to list down complete configuration.
- [List Containers](commands/docker/docker-container-list.md) - List all the running & stopped containers
- [List Images](commands/docker/docker-images-list.md) - List all the docker images available locally
- [Load Saved Image](commands/docker/docker-load.md) - Load a docker image from a tar ball package.
- [Login to container](commands/docker/docker-login.md) - Login to docker container bash.
- [Login to docker registry](commands/docker/docker-registry-login.md) - Login to docker registry in local terminal.
- [Push docker image](commands/docker/docker-push.md) - Push docker image to remote registry.
- [Rename container](commands/docker/docker-rename.md) - Rename a running or stopped docker container
- [Run docker container](commands/docker/docker-run.md) - Run a docker container using docker image id.
- [Save docker image](commands/docker/docker-save.md) - Save a docker image into a tar package.
- [Tail container logs](commands/docker/docker-logs-tail.md) - Tail running or stopped docker container logs.


## GIT

- [Clone repository](commands/git/git-clone-repo.md) - Clone a repository to any location.
- [Commit changes](commands/git/git-commit.md) - Commit the local changes.
- [Configure Author](commands/git/git-name-email-config.md) - Configure author name and email.
- [Configured Author](commands/git/git-name-email-config-check.md) - Check configured author name or email.
- [Create branch](commands/git/git-new-branch.md) - Create a new branch.
- [Delete branch](commands/git/git-delete-branch.md) - Delete a branch from remote git repository.
- [Git RefLog](commands/git/git-reflog.md) - Gives the complete activity trace of the repository.
- [Modify Commit](commands/git/git-commit-amend.md) - Modify last commit details (commit message, author...).
- [Pull changes](commands/git/git-pull.md) - Pull remote changes to local repository.
- [Push changes](commands/git/git-push.md) - Push changes from local respository to remote.
- [RM Cached](commands/git/git-rm-cached.md) - Remove cached files which are added in .gitignore later.
- [Reset File](commands/git/git-reset.md) - Reset committed changes of a file.
- [Restore Branch](commands/git/git-restore-branch.md) - Restore a deleted branch.
- [Status](commands/git/git-status.md) - Git status to check the file list in which changes are made.
- [Stage](commands/git/git-stage.md) - Stage (add) the new changes done to commit those changes.
- [Stash](commands/git/git-stash.md) - Stash all the current changes, pushes all the changes to stash stack and goes back to last commit.
- [Stash File](commands/git/git-stash-file.md) - Stash a particular file, push changes done to a file into stash stack and goes back to last commit for that file.
- [Stash List](commands/git/git-stash-list.md) - Check stash stack list.
- [Stash Revert](commands/git/git-stash-revert.md) - Revert stashed changes from stash stack.
- [Switch Branch](commands/git/git-switch-branch.md) - Switch current working branch.

## Heroku

- [List dynos](commands/heroku/heroku-ps.md) - List all the running dynos


## Kafka

- [Create Topic](commands/kafka/kafka.md) - Create a new topic in zookeeper to be used by Kafka.


## Linux

- [Clear Terminal](commands/linux/clear.md) - Clear current visible terminal.
- [Get Flavor & Version](commands/linux/get-linux-flavor-version.md) - Get current running Linux OS flavor and version details.
- [List contents of directory](commands/linux/list.md) - List all the contents of the current directory
- [Search Application Process](commands/linux/search-application-process.md) - Search for running application process by name.
- [Tail File](commands/linux/tail-one-file.md) - Live tail any file.
- [Tail Multiple Files](commands/linux/tail-multiple-files.md) - Live tail multiple files in a directory.


## Mongo

- [Dump collection from MongoDB](commands/mongo/mongo-dump-collection.md) - Dump all the collections of all the databases from Mongo to a directory in JSON files.
- [Dump database from MongoDB](commands/mongo/mongo-dump-database.md) - Dump all the collections of a single database from Mongo to specified location.
- [Restore collection to MongoDB](commands/mongo/mongo-restore-collection.md) - Restore all database with all of its dumped collection from a specified location to Mongo.
- [Restore database to MongoDB](commands/mongo/mongo-restore-database.md) - Restore a particular database and all of its collection from specified location to Mongo.


## NPM

- [Login](commands/npm/npm-login.md) - Login to NPM in your terminal.
- [Init](commands/npm/npm-init.md) - Initialze a `npm` project.
- [Publish](commands/npm/npm-publish.md) - Publish a package to npm repository.


## PM2

- [pm2 start](commands/pm2/pm2-start.md) - Start an application using pm2


## PSQL

- [Login to database](commands/psql/login-database.md) - Login to a database using username / password.
- [Import Dump](commands/psql/import-dump.md) - Import SQL dump to a database in Postgres.
- [Export Dump](commands/psql/export-dump.md) - Export a database to a SQL dump file.


## Python

- [Build python project](commands/python/python-build.md) - Build the python project to deploy on pypi.
- [Python deploy to pypi](commands/python/python-deploy-pypi.md) - Deploy the build python project to pypi.


## SCP

- [Copy from local to server](commands/scp/scp-local-to-server.md) - Copy files from local system to remote server.
- [Copy from server to local](commands/scp/scp-server-to-local.md) - Copy files from remote server to local system.


## SSH

- [Login Remote Server](commands/ssh/ssh-server.md) - Login into a remote server.


## tar

- [Tar Extract](commands/tar/extract.md) - Extract a tar package to specified location.


## zip

- [Zip directory](commands/zip/zip-command.md) - Pack a directory into a zip package.
- [Zip directory Encryption](commands/zip/zip-command-encryption.md) - Pack a directory into a zip package with encryption.
- [Unzip file](commands/zip/unzip-command.md) - Unzip a zip package to a specified location.

# Contributing Guide

Interested in contributing to this project, check some of our open issues [here](https://github.com/arshadkazmi42/ak-cli/issues).

Read our contrubtion guide [here](CONTRIBUTING.md).

# Help us

We would love to get some suggestions or feedbacks for this project.

If you have any suggestion about the project, let us know by adding a comment [here](https://github.com/arshadkazmi42/ak-cli/issues/39)

# Contributors

Thank you to all the contributors who have helped us in making this project better 🙌

<a href="https://github.com/arshadkazmi42"><img src="https://github.com/arshadkazmi42.png" width="30" /></a><a href="https://github.com/SakshayMahna"><img src="https://github.com/SakshayMahna.png" width="30" /></a><a href="https://github.com/alpha-gamma"><img src="https://github.com/alpha-gamma.png" width="30" /></a><a href="https://github.com/sinumohan"><img src="https://github.com/sinumohan.png" width="30" /></a><a href="https://github.com/7jones"><img src="https://github.com/7jones.png" width="30" /></a><a href="https://github.com/xFreed0m"><img src="https://github.com/xFreed0m.png" width="30" /></a><a href="https://github.com/iDG772Mn"><img src="https://github.com/iDG772Mn.png" width="30" /></a><a href="https://github.com/ryserCar"><img src="https://github.com/ryserCar.png" width="30" /></a><a href="https://github.com/AmishNick"><img src="https://github.com/AmishNick.png" width="30" /></a><a href="https://github.com/Logik-Dev"><img src="https://github.com/Logik-Dev.png" width="30" /></a><a href="https://github.com/JeremyManuel"><img src="https://github.com/JeremyManuel.png" width="30" /></a><a href="https://github.com/KurtLehnardt"><img src="https://github.com/KurtLehnardt.png" width="30" /></a><a href="https://github.com/marieram"><img src="https://github.com/marieram.png" width="30" /></a><a href="https://github.com/Rafaellarsa"><img src="https://github.com/Rafaellarsa.png" width="30" /></a><a href="https://github.com/ssd71"><img src="https://github.com/ssd71.png" width="30" /></a>
