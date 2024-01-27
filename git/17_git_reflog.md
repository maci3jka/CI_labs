# Git reflog
## Intro
`git reflog` is a command that manages the information recorded in the reflogs. Reflogs record when the tips of branches and other references were updated in the local repository. The command takes various subcommands, and different options depending on the subcommand. You can use `git reflog show` to see the log of the reference provided in the command-line (or HEAD, by default)
## Steps
1. Open your Git repository in the command prompt or terminal.
2. Type `git reflog` and press enter.
3. The Git reflog will display a list of all the recent changes made to the repository, including the commit hash, the author, the date, and the commit message.
4. You can use `git reflog <branch-name>` to view the reflog for a specific branch.
5.To undo a commit, use the command `git reset --hard <commit-hash>`. This will remove the commit and all the changes made in it.
6. To undo a commit and keep the changes, use the command `git revert <commit-hash>`. This will create a new commit that undoes the changes made in the specified commit.
