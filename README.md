George-and-Marthas
==================
$ mkdir ~/George-and-Marthas
# Creates a directory for your project called "George-and-Marthas" in your user directory

$ cd ~/George-and-Marthas
# Changes the current working directory to you newly created directory

$ git init
# Sets up the necessary Git files
Initialized empty Git repository in /Users/your/George-and-Marthas/.git/

$ touch README
# Creates a file called "README" in your George-and-Marthas directory

Hello World!

$ git add README
# Stages your README file, adding it to the list of files to be committed

$ git commit -m 'first commit'
# Commits your files, adding the message "first commit"

$ git remote add origin https://github.com/matthewmorton/George-and-Marthas.git
# Creates a remote named "origin" pointing at your GitHub repository

$ git push origin master
# Sends your commits in the "master" branch to GitHub
