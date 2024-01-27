## Introduction
`git cherry-pick` is a command that allows you to apply a specific commit from one branch to another. This can be useful when you want to apply a change from one branch to another without merging the entire branch.
## Steps
1. First, let’s create a new branch called feature and switch to it:
```
git checkout -b feature
```
2. Next, let’s make some changes to the code and commit them:
```
git commit -am "Added new feature"
```

3. Now, let’s switch back to the master branch:
```
git checkout master
```
4. Let’s say we want to apply the changes we made in the feature branch to the master branch. We can do this using the git cherry-pick command:
```
git cherry-pick <commit-hash>
```
5. Replace <commit-hash> with the hash of the commit you want to apply to the master branch.
If there are any conflicts, resolve them and commit the changes.
Finally, push the changes to the remote repository:

```
git push origin master
```
