# Git tag
## Intro
`git tag` is a command that allows you to create, list, delete, and share tags in a Git repository. Tags are used to mark specific points in Git history, such as release points. There are two types of tags: lightweight and annotated. Lightweight tags are just pointers to specific commits, while annotated tags are stored as full objects in the Git database and contain additional information such as the tagger name, email, and date.
## Steps
1. Create a new repository on your local machine using the command `git init`.
2. Create a new file in the repository and add some content to it.
3. Add the file to the staging area using the command `git add <filename>`.
4. Commit the changes using the command `git commit -m "Initial commit"`.
5. Create a new tag using the command `git tag <tagname>`. Replace <tagname> with the name of your tag.
6. Push the tag to the remote repository using the command `git push origin <tagname>`. This will push the tag to the remote repository.
7. Verify that the tag has been pushed to the remote repository using the command `git ls-remote --tags origin`.