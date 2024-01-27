# Git commit

## Intro
`git commit` is a command used in Git version control system to save changes to the local repository. It creates a snapshot of the changes made to the files in the staging area and records a message that describes the changes. The command is followed by a message that briefly describes the changes made to the files 

## Steps
1. Open a terminal window.
2. Navigate to the directory where your Git repository is located.
3. Make some changes to the files in your repository.
4. Run the following command to view the status of your repository:

```
git status
```
5. Git will show you a list of modified files.
6. Run the following command to stage the changes for commit:

git add <filename>

Replace `<filename>` with the name of the file you want to stage. You can also use `.` to stage all changes.
7. Run the following command to commit the changes:

```
git commit -m “Commit message”
```
Replace `"Commit message"` with a brief description of the changes you made.
8. Git will create a new commit with the changes you staged.
9. Once you have committed your changes, you can push them to the remote repository using the `git push` command.

## Conclusion
In this lab, you learned how to use the `git add` command to stage changes for commit in your Git repository. By following the steps outlined in this lab, you should now be able to use `git add` to prepare changes for committing.