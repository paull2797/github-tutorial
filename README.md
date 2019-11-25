# GitHub Tutorial

_by Paul Liu_

---
## Git vs. GitHub

Git is the version control, which keeps snapshots of the code. Git doesn't need Github. Github stores code, tracks changes made, and used to collaborate on files. Github needs Git to work.

---
## Initial Setup

Before you start using Github, you have to create an account. Go to [Github](https://github.com/) and click sign up. If you're an HSTAT student, it is recommended to use your HSTAT email (without the @hstat.org) as your username. Now that you've created your github account, you can use the [IDE](https://ide.cs50.io/). Make sure to use the SSH key, so the website doesn't keep asking for your login information.

---
## Repository Setup

In order to start using git, you first have to do "git init", which turns the directory into a repository. You only have to do this once. After any changes, you do "git add ." to add the changes to the stage. Then, you do "git commit -m "(message)" " to take a screenshot of the files on stage. Make sure the message describes what the screenshot is about. Before you push your changes to Github, you need to set up a remote. Follow the steps below.
  
1.) Go to [Github](github.com) 
2.) Select your repo
3.) Select clone and download
4.) Make sure it says "Clone with SSH" (to change click use SSH)
5.) Copy the link
6.) Do "git remote add origin (URL) "
7.) Do "git push -u origin master"
8.) Afterwards, you only have to do "git push" to push your changes.
---
## Workflow & Commands



---
## Rolling Back Changes