# Git rebase
## Init
`git rebase` is a command that allows you to apply changes from one branch onto another. It is useful when you want to integrate changes from one branch into another and create a new commit that incorporates the changes from both branches `git rebase` can be used to replay changes from one line of work onto another in the order they were introduced, whereas `git merge` takes the endpoints and merges them together
## Steps
1. Open your Git repository in the command prompt or terminal.
2. Type `git checkout <branch-name>` to switch to the branch you want to rebase.
3. Type `git rebase <target-branch>` to rebase your branch onto the target branch.
4. Resolve any conflicts that arise during the rebase process.
6. Use `git add <file-name>` to stage the changes you have resolved.
7. Use `git rebase --continue` to continue the rebase process.
8. Use `git push --force-with-lease` to push the rebased branch to the remote repository.