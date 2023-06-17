---
title: "Top 10 Git commands that Everyone Should Know"
date: 2021-05-29
description: "In this article, I will share and explain the top 10 Git commands that every developer should know"
cover:
  image: "images/Gitcommands.png"
  alt: "Top 10 Git Commands"
tags: [open-source, git]
---

Hello Everyone 👋,

Git is an important part of daily programming (especially if you're working with a team) and is widely used in the software industry.

Since there are many various commands you can use, mastering Git takes time. But some commands are used more frequently (some daily). So in this post, I will share and explain the top 10 Git commands that every developer should know.

**1. Git Init**

The git init command is used to initialize a blank repository. It creates a .git folder in the current working directory

```
$ git init

```

The above command will create an empty .git repository. Suppose we want to make a git repository on our desktop. To do so, open Git Bash on the desktop and run the above command.

The above command will create a new subdirectory named .git that holds all necessary repository files. The .git subdirectory can be understood as a Git repository skeleton.

An empty repository .git is added to my existing project. If we want to start version-controlling for existing files, we have to track these files with git add command, followed by a commit.

**2. Git Commit**

The git commit command is used to save the changes to the local repository. This command will help you keep a record of all the changes made. We also need to write a short message to explain what we have developed or changed in the source code.

```
$ git commit

```

The above command will prompt a default editor and ask for a commit message. We have made a change to the whole project and want it to commit it.

As we run the command, it will prompt a default text editor and ask for a commit message.

Press the Esc key and after that 'I' for insert mode. Type a commit message whatever you want. Press Esc after that ':wq' to save and exit from the editor. Hence, we have successfully made a commit.

**3. Git Status**

The git status command is used to display the state of the current repository & staging area.

We can gather information these information using git status command:

i) Whether the current branch is up to date

ii) Whether there is anything to commit, push or pull

iii)Whether there are files staged, unstaged or untracked

iv) Whether there are files created, modified, or deleted

```
$ git status

```

The list of all untracked files is displayed by the git status command. We can track all the untracked files by Git Add command.

**4. Git Add**

When we create, modify or delete a file, these changes will happen in our local and won't be included in the next commit (unless we change the configurations).

We need to use the git add command to include the changes of a file(s) into our next commit.

To add a single file:

```
$ git add <file name>

```

To add everything at once:

```
$ git add -A

```

The above command will add all the files available in the repository and put them into staging .

**5. Git Merge**

When you've completed development in your branch and everything works fine, the final step is merging the branch with the parent branch (dev or master). This is done with the git merge command.

The git merge command is used to integrate different branches into a single branch. It's important to remember that you first need to be on the specific branch that you want to merge with your feature branch.

```
$ git merge <branch-name>

```

**6. Git Push**

After committing your changes, the next thing you want to do is send your changes to the remote server. Git push uploads your commits to the remote repository.

```
$ git push <remote> <branch-name>

```

When you create a new branch, you must also upload it:

```
$ git push --set-upstream <remote> <name-of-your-branch>

```

**7. Git Pull**

The git pull command allows you to download updates from a remote repository. Using this command, you execute both git fetch and git merge operations, which means local changes are updated and updates are uploaded to remote repositories

```
$ git pull <remote>

```

**8. Git Clone**

Git clone is a command for downloading existing source code from a remote repository (like Github, for example). In other words, Git clone basically makes an identical copy of the latest version of a project in a repository and saves it to your computer.

```
$ git clone <https://name-of-the-repository-link>

```

**9. Git branch**

Branches are highly important in the git world. By using branches, several developers are able to work in parallel on the same project simultaneously. We can use the git branch command for creating, listing and deleting branches

```
$ git branch <branch name>

```

This command will create branch project locally in the Git directory.

**10. Git Checkout**

This is also one of the most used Git commands. To work in a branch, first you need to switch to it. We use git checkout mostly for switching from one branch to another. We can also use it for checking out files and commits.

```
$ git checkout <branchname>

```

So these are my 10 most-used git commands that I come across in my daily programming. I hope you find it useful. If yes then let me know in the comments.

**Also if you got any question feel free to ping me on [Twitter](https://twitter.com/muthuannamalai_)**

> You can now extend your support by buying me a Coffee.😊👇

[Buy Me A Coffee](https://www.buymeacoffee.com/muthuannamalai)

Thanks for Reading 😊
