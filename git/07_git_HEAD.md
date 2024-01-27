# git HEAD

## Intro

In Git, HEAD is a pointer to the current branch or commit you are working on. It is essentially a reference to the last commit in the current branch. When you create a new branch, Git sets HEAD to point to the new branch.


### Checking Out a Branch
To switch to a different branch, you can use the git checkout command followed by the name of the branch you want to switch to. For example, to switch to the develop branch, you would run the following command:
```
git checkout develop
```
This will update HEAD to point to the develop branch.

Checking Out a Specific Commit
You can also use HEAD to check out a specific commit. This is useful if you want to view the state of your code at a specific point in time. To do this, you can use the git checkout command followed by the commit hash. For example, to check out the commit with the hash abc123, you would run the following command:
```
git checkout abc123
```
This will update HEAD to point to the specified commit.

Detached HEAD State
When you check out a specific commit, Git enters a detached HEAD state. This means that HEAD is no longer pointing to a branch, but to a specific commit instead. In this state, any changes you make will not be associated with a branch. To return to a branch, you can use the git checkout command followed by the name of the branch you want to switch to. For example, to switch to the master branch, you would run the following command:
```
git checkout master
```
This will update HEAD to point to the master branch.
