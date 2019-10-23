# The README.md document
This document is used to describe or elaborate or include specific notes/references related to your repository. In this repository, the readme gives some important commands and links for starting use of git.

## Important git commands

### Branch commands
git branch => check available and active branches on local

git branch -r	=> check available and active branches on remote

git checkout -b newBranchName	=> create new branch from master

git checkout newBranchName => go to branch newBranchName

git checkout -B newBranchName	=> go to existing or create new branch newBranchName

### File tracking
git status => check untracked files

### Local machine to Staging area
git add fileName => add given fileName to staging area

git add -A => add all files from all directories

git add .	=> add all files from present directory

### Creating a local commit
git commit -m "msg"	=> create a commit for all files in staging area

### Git pull requests
git pull origin branch2	=> pull all files from remote branch2 to current local branch

git pull origin => maps metadata of all branches from remote to pulls it to local, eg branch2 and branch3

git checkout branch2 => creates branch2 locally and pulls all files from remote branch2 into local branch2

### Some other commands
git diff => compares all added or committed files with current local files for modification - previous vs current version

git diff fileName => compares added or committed fileName with current version of fileName on local

git remote -v => gives aliases and their associated URLs 
