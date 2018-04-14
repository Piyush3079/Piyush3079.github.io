---
layout: post
title: Introduction to Git
date: 2018-04-13 01:30:30 +0530
categories: GitHub
---

#### **What is Git ?**

Git is the free open source distibuted version control system. Git keeps track of changes to the content ie, source code files, and provides you mechanism for sharing that content with others.<br />
Git helps you contributing in some of the most famous open source projects like facebook-react, phpMyAdmin, Microsoft-vscode, Mozilla and so on. You can make contibutions by poviding solutions to some of the known bugs or by providing new bugs or suggestions for the improvements.

Documentation: [https://git-scm.com/](https://git-scm.com/ "Git SCM Docs")<br /><br />


#### **How to install git in linux?**
`sudo apt-get install git`<br />

#### **Git basic configurations:**
Your Name: `git config --global user.name "John Doe"`<br />
Your Email: `git config --global user.email johndoe@example.com`<br />
Checking you Global Settings: `git config --list`<br />
Checking git version `git --version`<br />
Git help `man git`<br /><br />


#### **Github:**
[Github](https://help.github.com/) is a hosting service which provides you repositories for version control. So github is basically an online storage of you git repositories.

#### **Git Repository:**
A repository (usually abbreviated to “repo”) is a location where all the files for a particular project are stored. Each project has its own repo, and you can access it with a unique URL.

#### **Forking a Repo:**
“Forking” is when you create a new project based off of another project that already exists. This is an amazing feature that vastly encourages the further development of programs and other projects. If you find a project on GitHub that you’d like to contribute to, you can fork the repo, make the changes you’d like, and release the revised project as a new repo. If the original repository that you forked to create your new project gets updated, you can easily add those updates to your current fork.

#### **Pull requests:**
You’ve forked a repository, made a great revision to the project, and want it to be recognized by the original developers—maybe even included in the official project/repository. You can do so by creating a pull request. The authors of the original repository can see your work, and then choose whether or not to accept it into the official project. Whenever you issue a pull request, GitHub provides a perfect medium for you and the main project’s maintainer to communicate.<br /><br />

#### **Adding public key to github**
Generating SSH Key: `ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`<br />
When you're prompted to "Enter a file in which to save the key," press Enter. This accepts the default file location.<br />
Enter the passphrase to be used to unlock the public key when used for the first time. <br />
Adding ssh key to ssh agent:
``` sh
$ eval "$(ssh-agent -s)"
$ ssh-add ~/.ssh/id_rsa
```
Getting ssh key: `cat ~/.ssh/id_rsa.pub`<br />
After running above script copy your ssh key.
Now login to your github account. Go to __Settings->SSH and GPG keys->New SSH Key__. Add desired title for the ssh key and then paste the copied ssh key to the 2nd input box and click on Add SSH Key.<br/>
After successfull addition of the ssh key, you key will be shown up in the __SSH and GPG Keys__ section.

Some useful git commands:

| Command | Usage |
|`git init`| Initialising a git repository in the woking directory. |
| `git remote add origin` | Adding origin for the repository on github. |
| `git remote -v` | To know about the remote origins of the repo. |
