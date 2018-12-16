### Stage and commit



#### Check the status

`git status`

It tells us:

* The branch we are on
* File we have modified
* Is there anything to commit



#### Stage the changes

`git add {{FILE}}`

- <b>FILE: </b> File to commit

##### Example:

`git add commands.md`

**OR**

`git add .`

To commit all changes



#### Commit the changes

`git commit -m {{MESSAGE}}`

- <b>MESSAGE: </b> The message on the commmit

##### Example:

`git commit -m "Changed the name"`



#### Push the changes

`git push {{FROM}} {{BRANCH}}`

- <b>FROM: </b> Where to push(The repository cloned from)
- <b>BRANCH: </b> What to push(the new branch)

##### Example:

`git push origin newbranch`



