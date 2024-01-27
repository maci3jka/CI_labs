# Git add
## Intro
`git add` is a command used in Git version control system to add new or changed files in your working directory to the Git staging area. This step allows you to choose what files to commit. After adding the files, you can commit them using `git commit` command.
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

```
git add <filename>
```
Replace `<filename>` with the name of the file you want to stage. You can also use `.` to stage all changes.
7. Run the `git status` command again to confirm that the changes have been staged.
8. Once you have staged your changes, you can commit them using the `git commit` command.
