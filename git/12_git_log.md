# Git log
## Intro
`git log` is a command that displays the commit logs in reverse chronological order. It lists all the commits that are reachable by following the parent links from the given commit(s), but excludes commits that are reachable from the one(s) given with a `^` in front of them. The output can be customized with options and paths 
## Steps
1. Open your Git repository in the command prompt or terminal.
2. Type `git log` and press enter.
3. The Git log will display all the commits made to the repository, along with their commit messages, author, date, and time.
4. You can use various options with the `git log` command to filter the results. For example, you can use `git log --author=<author-name>` to display only the commits made by a specific author.
5. You can also use `git log --since=<date>` to display only the commits made after a specific date.
6. If you want to see the changes made in a specific commit, you can use the `git show <commit-hash>` command.

That's it! You have successfully learned how to use Git log to view the commit history of your repository. If you encounter any issues, feel free to refer to the official GitLab documentation on Git log for more information.