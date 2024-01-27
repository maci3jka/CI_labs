# Git reset
## Intro
`git reset` is a command that allows you to reset the current branch head to a specified state. It can be used to reset the index and working tree entries for all or some paths that match the current HEAD to a different state `git reset` can be used with different modes such as `--soft`, `--mixed`, `--hard`, `--merge`.
## Steps
1. To undo the last commit, use the command `git reset HEAD~1`. This will remove the last commit from the branch, but keep the changes in the working directory.
2. To undo the last commit and discard the changes, use the command git reset --hard HEAD~1.
3. To undo a specific commit, use the command `git revert <commit-hash>`. This will create a new commit that undoes the changes made in the specified commit.
4. To undo a merge, use the command `git reset --hard <commit-hash>`. This will remove the merge and all the changes made in it.
5. To undo a merge and keep the changes, use the command `git revert -m 1 <commit-hash>`. This will create a new commit that undoes the changes made in the merge.