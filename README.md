## Git and Git Branching Cheat Sheet


### Basic Commands
* git init - initialize current directory with repository

* git branch -M main - Rename your branch from master to main or whatever you want.

* git add . -add all new or changed files in current directory to get index, staging them for commit

* git commit -m"message here" - commit staged changes to local repository

* git status - show status of current working directory
* git log - list commit history
* git log --oneline - list commit history (compact commit hash code)
* git branch - list local branches, places asterisk next to current branch
* git branch nameYouWant - creates a new branch to work on, sequestered from main
* git checkout nameYouPicked - switches the branch you're working on. Commits will not be put on the main branch
* git checkout -b otherBranch - switch to branch (otherBranch), creating it if it doesn't already exist.
*
