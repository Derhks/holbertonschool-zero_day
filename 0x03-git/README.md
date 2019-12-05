# Git

In this project we will talk about:

* What is source code management?
* What is Git?
* What is GitHub?
* What is the difference between Git and GitHub?
* What is a README?
* How to commit?
* How to push code?
* How to pull updates?
* How to merge branches?


## What is source code management?

Source code management (SCM) is used to track modifications to a source code repository. SCM tracks a running history of changes to a code base and helps resolve conflicts when merging updates from multiple contributors. SCM is also synonymous with Version control.

## What is Git?

Git is a mature, actively maintained open source project originally developed in 2005 by Linus Torvalds, the famous creator of the Linux operating system kernel. Git is an example of a DVCS (hence Distributed Version Control System). Rather than have only one single place for the full version history of the software as is common in once-popular version control systems like CVS or Subversion (also known as SVN), in Git, every developer's working copy of the code is also a repository that can contain the full history of all changes.

## What is GitHub?

GitHub is a Git repository hosting service, but it adds many of its own features. GitHub provides a Web-based graphical interface. The flagship functionality of GitHub is “forking” – copying a repository from one user’s account to another. These three features – fork, pull request and merge – are what make GitHub so powerful.

## What is the difference between Git and GitHub?

```
Git is a version control system that lets you manage and keep track of your source code history.
```

```
GitHub is a cloud-based hosting service that lets you manage Git repositories
```

## What is a README?

A README is a text file that introduces and explains a project. It contains information that is commonly required to understand what the project is about.

## How to commit?

To make a commit and have it help describe what you have done to your code, we can follow these simple steps:

The commit must not exceed 50 characters
The first letter of the commit must be uppercase
You should not end the commit with a period
The message you want to give with the commit must be written in imperative mode

```
Example: git commit -m "The varialbe cnt1 is eliminated"
```

## How to push code?

To push the code to GitHub, we must use the following Git command:

```
git push origin master "filename"
```

## How to pull updates?

To pull the updates made in GitHub, we'll use the Git command:

```
git pull
```

## How to merge branches?

To merge branches we must be located on the main branch, then we will write the command:

```
git merge "branch"
```

In branch we will write the name of the branch we want to merge with our main branch.


## Authors

* **Julián Sandoval** - [Derhks](https://twitter.com/Derhks)


## Acknowledgments

I thank the following pages for the information I have extracted from them to make this README.md.

* https://www.makeareadme.com/
* https://chris.beams.io/posts/git-commit/#seven-rules
* https://backlog.com/git-tutorial/branching/merge/