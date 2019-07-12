---
title: "Setting up Git"
date: 2019-06-24T14:05:54+01:00
draft: true
weight: 15
author:
---


# Installing Git

Git is available for al major platforms. To install Git on Debian-based Linux distros such as Ubuntu or Mint:

```
$ sudo apt-get install git
```

When the installation process is completed, to see the installed version, type:


```
$ git --version
```

## Creating a local working directory
Once you have Git installed, the next step is set up your working directory. This is the folder you will create and manage files in for your project, and which you'll add to a repository in Github.

Start first by creating a folder for your project, cd into it and initialize it. For example:

```
$ mkdir my_git_project
$ cd my_git_project
$ git init
```
