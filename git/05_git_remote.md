# Git remote

## Intro
`git remote` is a command used in Git version control system to manage the set of repositories whose branches you track. It allows you to create, view, and delete connections to other repositories in Git.

## Steps
1. First, create a new repository on your local machine using the command `git init`. Then, create a new repository on GitHub or GitLab.
2. Next, add the remote repository to your local repository using the command `git remote add origin <remote repository URL>`. This will allow you to push your changes to the remote repository.
3. To verify that the remote repository has been added, use the command `git remote -v`. This will display a list of all the remote repositories that are associated with your local repository.
4. Now, you can push your changes to the remote repository using the command `git push -u origin master`. This will push your changes to the master branch of the remote repository.
5. To pull changes from the remote repository to your local repository, use the command `git pull origin master`.
6. Finally, to remove a remote repository from your local repository, use the command `git remote rm <remote repository name>`.