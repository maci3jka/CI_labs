# Git branch
## Intro
`git branch` is a command that lists, creates, or deletes branches. It can also be used to rename branches or display the current branch. When used without any arguments, it lists all the local branches in the repository 
## Steps
1. Open a terminal window.
2. Navigate to the directory where your Git repository is located.
3. Run the following command to view a list of branches in your repository:

```
git branch
```
4. Git will show you a list of branches, with an asterisk next to the current branch.
5. Run the following command to create a new branch:

```
git branch <branch-name>
```
Replace `<branch-name>` with the name of the new branch.
6. Run the following command to switch to a different branch:

```
git checkout <branch-name>
```
Replace `<branch-name>` with the name of the branch you want to switch to.
7. Run the following command to delete a branch:

```
git branch -d <branch-name>
```
Replace `<branch-name>` with the name of the branch you want to delete.
