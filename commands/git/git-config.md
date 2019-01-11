### Set the git name and email for current repository

`git config user.name "{{NAME}}"`

`git config user.email "{{EMAIL}}"`

#### Example:

`git config user.name "Mona Lisa"`

`git config user.email "monalisa@gmail.com"`

Also `--global` can be used to set user name and/or email for all local repositories

#### Example command for setting user name globally:

`git config --global user.name "Mona Lisa"`

What it does:

* Set user name and email information which will be used in every commit you do

### Check git name and email

`git config user.name`

`git config user.email`