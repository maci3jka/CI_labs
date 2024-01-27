# Git push

## Intro
`git push` is a command used in Git version control system to upload local repository content to a remote repository. It sends the objects necessary to complete the given refs and updates remote refs using local refs. You can use `git push` command to update a branch, tag, or even multiple branches and tags at once
## Steps
1. Open a terminal window.
2. Navigate to the directory where your Git repository is located.
3. Make some changes to the files in your repository.
4. Run the following command to view the status of your repository:

git status

5. Git will show you a list of modified files.
6. Run the following command to stage the changes for commit:

```
git add <filename>
```
Replace `<filename>` with the name of the file you want to stage. You can also use `.` to stage all changes.
7. Run the following command to commit the changes:

```
git commit -m “Commit message”
```
Replace `"Commit message"` with a brief description of the changes you made.
8. Run the following command to push the changes to the remote repository:

```
git push
```
9. Git will upload your changes to the remote repository.
10. You can confirm that your changes have been uploaded by visiting the remote repository.

