# Git merge
## Intro
`git merge` is a command that integrates changes from one branch into another. It is used to combine the changes made in two branches and create a new commit that incorporates the changes from both branches `git merge` can be used to merge branches with a fast-forward merge or a three-way merge, depending on whether the branches have diverged.

## Steps
1. Create a new branch in your Git repository using the command `git branch <branch-name>`.
2. Switch to the new branch using the command `git checkout <branch-name>`.
3. Make some changes to the files in the new branch.
4. Commit the changes using the command `git commit -m "commit message"`.
5. Switch back to the main branch using the command `git checkout main`.
6. Merge the changes from the new branch into the main branch using the command `git merge <branch-name>`.