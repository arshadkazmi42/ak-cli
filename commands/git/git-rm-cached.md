### Remove gitignored files from remote

This will stash a specific file

`git rm -r --cached {{DIRECTORY_NAME}}`

- <b>DIRECTORY_NAME</b>: Name of file/directory, which is added to gitignore and needs to be removed from remote also

#### Example:

`git rm -r --cached node_modules`

### Related

- [Commit changes](git-commit.md)
- [Stage](git-stage.md)
- [Push changes](git-push.md)