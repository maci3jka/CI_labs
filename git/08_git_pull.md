# Git pull
## Intro
`git pull` is a command that integrates changes from a remote repository into the current branch. If the current branch is behind the remote, then by default it will fast-forward the current branch to match the remote. If the current branch and the remote have diverged, the user needs to specify how to reconcile the divergent branches with `--rebase` or `--no-rebase`
## Steps
1. Open a terminal window.
2. Navigate to the directory where your Git repository is located.
3. Run the following command to view the status of your repository:

```
git status
```
4. Git will show you a list of modified files.
5. Run the following command to fetch the changes from the remote repository:

```
git fetch
```
6. Git will download the changes from the remote repository to your computer.
7. Run the following command to merge the changes with your local repository:

```
git merge origin/master
```
Replace `origin/master` with the name of the branch you want to merge.
8. Git will merge the changes from the remote repository with your local repository.
9. Once you have merged the changes, you can commit them using the `git commit` command.
