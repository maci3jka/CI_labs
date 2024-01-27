# Git rebase -i
## Intro
`git rebase -i` is a command that allows you to interactively rebase commits. It opens an editor that displays a list of commits and their SHA-1 hashes. You can then edit the list to reorder, squash, fixup, or drop commits before applying them to the target branch 
## Steps
1. Open your Git repository in the command prompt or terminal.
2. Type `git checkout <branch-name>` to switch to the branch you want to rebase.
3. Type `git rebase -i <target-branch>` to start an interactive rebase. This will open a text editor with a list of commits.
4. In the text editor, you can choose which commits to keep, edit, or squash. You can also reorder the commits by changing their order in the list.
5. Save and close the text editor to apply the changes.
6. Resolve any conflicts that arise during the rebase process.
7. Use `git add <file-name>` to stage the changes you have resolved.
8. Use `git rebase --continue` to continue the rebase process.
9. Use `git push --force-with-lease` to push the rebased branch to the remote repository.
