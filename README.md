Git Cheat Sheet
===================

- - - - 
# Config

## List your config ##

    $ git config --list

## Change your name

    $ git config --global user.name "[name]"

## Change your e-mail

    $ git config --global user.email "[email]"

# Create

## Initialize a git repository inside a directory

    $ git init

## Clone an existing repository

### **HTTPS**

    $ git clone [url]

### **GitHub CLI**

    $ gh repo clone [username]/[repository]

# Status

## Show changed files in working directory

    $ git status

# Add

## Add all modified files to the next commit

    $ git add .

## Add only one file to next commit

    $ git add [file]

# Commit

## Commit added files

    $ git commit -m "[descriptive message]"

## Get information about the last commit

    $ git log

## **Shortcut**

## Add & Commit all modified files

    $ git commit -a -m "[descriptive message]"
