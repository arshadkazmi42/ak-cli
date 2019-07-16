### Restore locally deleted branch

This command is used for restoring a locally deleted branch

`git checkout -b {{BRANCH_NAME}} {{SHA_HASH}}`

- <b>BRANCH_NAME: </b>Branch name which needs to be restored
- <b>SHA_HASH: </b>Hash of the last commit on the branch, use - [Git Activity Trace](git-reflog.md) to get the hash

##### Example:

`git checkout -b ak-cli-dev 324ed3`

### Related

- [Git Activity Trace](git-reflog.md)