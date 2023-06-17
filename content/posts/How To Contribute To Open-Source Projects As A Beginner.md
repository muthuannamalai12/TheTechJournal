---
title: "How To Contribute To Open-Source Projects As A Beginner"
date: 2021-06-19
description: "In this article we will learn about how to contribute to open source as a beginner"
cover:
  image: "images/How to Contribute To Open Source.png"
  alt: "How To Contribute To Open Source"
tags: [open-source, git]
---

This article is about getting started with open source and more specifically how to contribute to open source as a beginner contributing to open source projects is a great way of improving your programming skills and contributing to the community also. It's important to understand that contributing to open source projects is not all about coding you can contribute in other ways such as improving the documentation, organizing the project, designing stuff reviewing code, and so on. Before moving on further I would advise everyone to read the contribution guidelines and the code of conduct they describe the workflow required to make contributions.

The first step is to find a project where you can contribute as we know finding a project to contribute is a difficult task for beginners as a result. I advise you to start small and pick a small project at first and you may ask why should I do that the reason is that things move faster in a small project and it's more likely to get your first contributions moving further there are lots of websites where you can find projects to contribute to but in this article, I want to recommend four of them which are suited for beginners. The websites are:

1.  [good first issues.com](https://goodfirstissues.com/)

2.  [good first issue.dev](https://goodfirstissue.dev/)

3.  [up-for-grabs.net](https://up-for-grabs.net/#/)

4.  [github.com/explore](https://github.com/explore)

The 4th one here is more general than the other three and it's not targeted only to beginners so you have to do a little bit more work here. Moving forward these four websites should be more than enough to find a project if not pick a tool that you use daily and contribute to that tool if it's open-source alternatively you can follow this article where I will show you a repo where you can make a very simple contribution

This article assumes basic knowledge of git and the git workflow we will be using is as follows:

1. Fork the repository to your GitHub account

2. Clone the project on your machine

3. Create a branch before making changes

4. Make your changes

5. Commit and push your changes

6. Open a pull request

The above workflow is the most basic one and it's enough to contribute to open source projects

- The **first step** is to fork the project you chose so all you have to do is to go to this URL which you can find in the description and click on the fork button and then you have to wait for forking to be finished now you might ask why fork it first and not clone it directly when you fork a project you make a copy of it in your account, as a result, you can work on it without affecting the original repository. Forking creates a separate copy whereas cloning downloads the project on your machine also you cannot make changes to the repository if you only clone it the reason is that only authorized people can make changes to a repository by forking the project you can make changes and submit put a request as you can see after the forking is complete it will redirect you to your copy of the project it's made of your GitHub username/repository name

- The **next step** is to clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the copy to clipboard icon.

![clone.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1624093193646/8ZBdSqEBZ.png)

Open a terminal and run the following git command:

```
git clone "URL you just copied"

```

where "URL you just copied" (without the quotation marks) is the URL to this repository (your fork of this project). See the previous steps to obtain the URL.

![copy-to-clipboard.png]
(https://cdn.hashnode.com/res/hashnode/image/upload/v1624093224527/wt1cqeK_N.png)

For example:

```
git clone https://github.com/this-is-you/Open-Source-Contribution.git

```

where where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

- The **next step** to create a new branch that allows people to work on the project without getting into conflict with each other. Also, each branch is independent of others so the changes from your branch are not visible in another branch unless they are merged of course. In the simplest words, your branch holds the changes you make to the project. Also, read the branch naming convention of each project they tell how you should name your branches some examples are your name/issue fix. For Example: muthu/add-name-1 which is my name slash issue fix. You can create a new branch as follows:

Change to the repository directory on your computer (if you are not already there):

```
cd Open-Source-Contribution

```

Now create a branch using the `git checkout` command:

```
git checkout -b your-new-branch-name

```

For Example:

```
git checkout -b add-muthu-annamalai

```

> The name of the branch does not need to have the word add in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.

- The **next step** is to Make necessary changes and commit those changes. The changes you make to each project depending on what the project is about and about what issues you are working on however using this example GitHub repository we will add our Name in the `Contributors.md` file and commit our changes to our branch. Commit messages must be concise and descriptive as possible at the same time, it doesn't mean you should write a novel so let's write something short like added my name as a commit message

Now open the `Contributors.md` file in a text editor, add your name to it and save the file.

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add Contributors.md

```

Now commit those changes using the `git commit` command:

```
git commit -m "Add <your-name> to Contributors list"

```

replacing `<your-name>` with your name.

- The **next step ** is to Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin <add-your-branch-name>

```

replacing <add-your-branch-name> with the name of the branch you created earlier.

- The **next step** is to Submit your changes for review

If you go to your repository on GitHub, you'll see a Compare & pull request button. Click on that button.

![compare-pull-request.jpeg](https://cdn.hashnode.com/res/hashnode/image/upload/v1624093866881/CuD__MFQa.jpeg)

Now submit the pull request.

![submit-pull-request.jpeg](https://cdn.hashnode.com/res/hashnode/image/upload/v1624093841841/H78BMEVhS.jpeg)

Soon the project admin will be merging all your changes into the master branch of their project. You will get a notification email once the changes have been merged.

If you had followed the article up to here you should be able to make your open source contributions no matter the complexity of the project. I'm curious to see if you found this article useful please let me know in the comments

If you want to contribute to open-source for the first time you can do it in my repository. I would be happy to help you to make your first contribution to Open-Source.

Link to the GitHub Repository: https://github.com/muthuannamalai12/Open-Source-Contribution

**I hope you found this article valuable. If yes do let me know in the comments 😊**

**Also if you got any question feel free to ping me on [Twitter](https://twitter.com/muthuannamalai_)**

> You can now extend your support by buying me a Coffee.😊👇

[Buy Me A Coffee](https://www.buymeacoffee.com/muthuannamalai)

Thanks for Reading 😊
