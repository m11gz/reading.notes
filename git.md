# A GIT Tutorial 

# LVC 
When a developer would work on a project they would back it up on a local harddrive that stores changes to files

# CVS(Centralized Version Control) 
What CVS is is basically a cloud for a project to go on. In a worst case scenario, if something were to happen to the hard drive they working on it would still be safe. 
This means it would all be stored on a single server allowing mutliple clients to view or edit the ongoing project. 

# DVCS (Distributed Server Control) 
The beauty of DVCS is that you are able to mirro the entire codebase on every developers computer. In a bad situation where the server goes down it allows the developers 
to continue working on said projects. Changes to the program or files are still changed between computers. 

# How to install Git
The easiest way to download git is by going to the website [Github](http://windows.github.com)
After installing git you need to make some customization steps. 
Type the following into Terminal

git config --global user.name "Juan Smith"

git config --global user.email "example@email.com"

# Setting up a Git Repository 
Switching to the projects repository
$ cd test (cd = change directory)
$ git init
$ git add *.c
$ git add LICENSE
$ git commit -m "insert message" 

# How to clone your repository 
$ git clone https://github.com/test

# Tracker and Untracked Files
Tracked files can be modified because they were part of a recent snapshot. An untracked file is a file that has not yet been staged. 

# Commiting Changes 
"$git commit" allows you to take a snapsht of all recent changes. 

# Push
$git push origin master 
This command moves from local branch to another repo. 
