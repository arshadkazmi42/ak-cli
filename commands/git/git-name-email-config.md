### Set the git name and email for current repository

Set user name and email information which will be used in every commit you do

`git config user.name "{{NAME}}"`

`git config user.email "{{EMAIL}}"`

- **NAME**: Specifies your name for authoring purposes
- **EMAIL**: Specifies your email for authoring and contacting purposes

#### Example:

`git config user.name "Mona Lisa"`

`git config user.email "monalisa@gmail.com"`

##### Using global flag:

- **--global**: can be used to set user name and/or email for all local repositories

`git config --global user.name "Mona Lisa"`

<img src="../../gifs/git-name-email-config.gif" alt="Git Config"/> <br>

### Related

- [Name Email Config Check](git-name-email-config-check.md)
- [Commit changes](git-commit.md)
- [Push changes](git-push.md)