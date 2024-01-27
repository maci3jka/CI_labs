# Git stash
## Intro
`git stash` is a command that allows you to temporarily save changes made to your working directory and index, without committing them. It is useful when you want to switch to another branch or work on a different feature without losing your current progress. You can list, apply, drop, and create stashes with `git stash list`, `git stash apply`, `git stash drop`, and `git stash create`, respectively.


## Steps
1. Open your Git repository in the command prompt or terminal.
2. Type git stash and press enter. This will save your changes to a stash.
3. You can use git stash list to view all the stashes you have created.
4. To apply the changes from a stash, use git stash apply <stash-name>.
5. If you want to apply the changes and remove the stash, use git stash pop <stash-name>.
6. To remove a stash, use git stash drop <stash-name>.

