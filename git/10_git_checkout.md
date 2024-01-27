# Git checkout
## Intro
`git checkout` is a command that allows you to switch between different versions of a target entity (files, commits, or branches) in Git. It can also be used to create, switch, and checkout remote branches, detached HEADs, and new branches. When used without any arguments, it lists all the local branches in the repository
## Steps
1. Open a terminal window.
2. Navigate to the directory where your Git repository is located.
3. Run the following command to view a list of branches in your repository:

```
git branch
```
4. Git will show you a list of branches, with an asterisk next to the current branch.
5. Run the following command to switch to a different branch:
```
git checkout <branch-name>
```
Replace `<branch-name>` with the name of the branch you want to switch to.
6. Git will switch to the new branch and update your working directory with the files from that branch.
7. You can now make changes to the files in the new branch.
8. Once you have made your changes, you can commit them using the `git commit` command.

