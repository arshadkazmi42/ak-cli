### Push the changes

`git push {{FROM}} {{BRANCH}}`

- <b>FROM: </b> Where to push(The repository cloned from)
- <b>BRANCH: </b> What to push(the new branch)

##### Example:

`git push origin newbranch`

#### Difference between:
`git push --force` & `git push --force-with-lease`

`force` overwrites a remote branch with your local branch. <br>

`--force-with-lease` is a safer option that will not overwrite any work on the remote branch if more commits were added to the remote branch (by another team-member working on the same repository). It ensures you do not overwrite someone elses work by force pushing.

[Click here to see the orginial git commit on the same.](https://github.com/git/git/commit/28f5d176110d2ed768a0a49159993c7a02d8cb15)


### Demo
![git-push](https://user-images.githubusercontent.com/116898892/227696642-8d6c2cf3-366f-48d4-b1f6-bacc286f84d0.gif)

### Related

- [Check status](git-status.md)
- [Switch Branch](git-switch-branch.md)
