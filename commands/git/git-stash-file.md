### Stash specific file

This will stash a specific file

`git stash push -m {{COMMENT_MESSAGE}} {{FILE_NAME}}`

- <b>COMMENT_MESSAGE</b>: Message needs to be added to the stash.  
- <b>FILE_NAME</b>: Name or path of the file, which needs to be stashed

#### Example:

`git stash push -m "ak-cli-file" ak-cli/commands/git/git-stash-file.md`

### Related

- [Check status](git-status.md)
- [Stash](git-stash.md)
- [Stash List](git-stash-list.md)
- [Stash Revert](git-stash-revert.md)