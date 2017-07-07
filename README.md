# This repository was created as part of the <Terminal & Git: Developing your work flow> Meetup I attended.
# Where: Rithm School
# Description of Meetup: 
Have you been teaching yourself to code?One of the biggest ways to increase your speed as a developer is to master the command line. Come spend a few hours learning how to use the terminal and explore Git & GitHub for your project’s version control. Beginners welcome! We’ll have a mini-lecture and guided activity for everyone to work through.
#Outcome:
Through the command line, I can now initialize an empty git reposity, stage files, commit, and push to GitHub!

#Notes from meetup:
Git: a version control. A way to save snapshots of your work. ori

> git init 
//initializes an empty Git repository

> git add .
//will take everything in the working directory and is going to add it to staging
> git add <file>
//add specific file to staging

> git commit -m “”
//takes a snapshot of your current work


> git status
//check current status of what has been committed or not.

>git log
//shows list of commits

Github is a place to remotely store a repository

Got go github.com/new to create a new repository
Let your local computer know about the remote repository where you can store copy of data by adding origin.

> git remote add origin https://github.com/maribelduran/learn_git.git

>git remote

>git remote -v
Shows the remote location where you are pushing and pulling data for repository

>git push origin master

> git checkout -b intern
//creates a new branch called intern

> git checkout master

>git merge feature

Fastword merging. No conflicting merge to master.

