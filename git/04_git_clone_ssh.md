# Git lone ssh

## Intro
`git clone` is a command that creates a copy of an existing Git repository. It can be used to clone a repository from a remote server or a local filesystem into a new directory. The command also creates remote-tracking branches, initial branches, and references. To clone a repository using SSH protocol, you need to set up SSH keys, add the public key to the service you want to connect to over SSH, and use the git clone command with the SSH protocol

## Prerequisites
Before starting this lab, you should have Git installed on your computer and an SSH key pair generated. If you don't have an SSH key pair, you can follow the instructions [here](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent).

## Steps
1. Open a terminal window.
2. Navigate to the directory where you want to clone the Git repository.
3. Identify the URL of the remote repository you want to clone.
4. Run the following command to clone the repository using SSH:

```
git clone git@<hostname>:<username>/<repository-name>.git
```
Replace `<hostname>` with the hostname of the remote repository, `<username>` with your username, and `<repository-name>` with the name of the repository you want to clone.
5. Git will prompt you to add the remote host to your list of known hosts. Type `yes` to continue.
6. Git will download the files from the remote repository to your computer.
7. You can now start working with the files in the local repository.
