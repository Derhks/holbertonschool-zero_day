# Vagrant

In this project we will talk about:

* What is a zero-day?
* What is a virtual machine?
* What is Vagrant?
* What is Ubuntu?
* What does “Ubuntu” mean?
* What does the command uname do?
* What is source code management?
* What is Git?
* What is GitHub?
* What is the difference between Git and GitHub?



## What is a zero-day?

Is a computer-software vulnerability. Until the vulnerability is mitigated, hackers can exploit it to adversely affect computer programs, data, additional computers or a network. "Day Zero" is the day on which the vendor learns of the vulnerability.

## What is a virtual machine?

A virtual machine (VM) is an emulation of a computer system. Virtual machines are based on computer architectures and provide functionality of a physical computer. They provide functionality needed to execute entire operating systems.

```
Example: VirtualBox or VMware
```

## What is Vagrant?

Vagrant is a tool for building and managing virtual machine environments in a single workflow. Vagrant provides easy to configure, reproducible, and portable work environments. If you are a developer, Vagrant will isolate dependencies and their configuration within a single disposable, consistent environment, without sacrificing any of the tools you are used to working with (editors, browsers, debuggers, etc.).


## What is Ubuntu?

Ubuntu is a complete Linux operating system. Tthe Ubuntu community is built on the ideas enshrined in the Ubuntu Manifesto: that software should be available free of charge, that software tools should be usable by people in their local language and despite any disabilities, and that people should have the freedom to customize and alter their software in whatever way they see fit.

## What does “Ubuntu” mean?

Ubuntu is an ancient African word meaning ‘humanity to others’. It is often described as reminding us that ‘I am what I am because of who we all are’. We bring the spirit of Ubuntu to the world of computers and software. The Ubuntu distribution represents the best of what the world’s software community has shared with the world.


## What does the command uname do?

Prints system information, such as the kernel name, kernel version, or machine hardware, on the screen.


```
Example:

vagrant@vagrant-ubuntu-trusty-64:~$ uname -s
Linux

or

vagrant@vagrant-ubuntu-trusty-64:~$ uname -r
3.13.0-170-generic

or

vagrant@vagrant-ubuntu-trusty-64:~$ uname -m
x86_64

```

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
## Authors

* **Julián Sandoval** - [Derhks](https://twitter.com/Derhks)


## Acknowledgments

I thank the following pages for the information I have extracted from them to make this README.md.

* https://en.wikipedia.org/wiki/Zero-day_(computing)
* https://en.wikipedia.org/wiki/Virtual_machine
* https://www.vagrantup.com/intro/index.html
* https://help.ubuntu.com/lts/installation-guide/s390x/ch01s01.html
* https://ubuntu.com/about
* https://www.atlassian.com/git/tutorials/source-code-management
* https://techcrunch.com/2012/07/14/what-exactly-is-github-anyway/