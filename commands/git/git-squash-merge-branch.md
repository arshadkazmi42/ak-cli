### Squash Merge a branch to the master

Merge branch to the master by combining all commits of the branch and merging as a single commit

`git merge --squash {{BRANCH}}`

- <b>BRANCH: </b> Branch which needs to be squash merged to the master

#### Example:

`git merge --squash feature-add-dashboard`

This will merge the branch 'feature-add-dashboard' to the master, and will squash all branch commits into a single commit in master
