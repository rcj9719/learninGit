# LearninGit notes

## The README.md document
This document is used to describe or elaborate or include specific notes/references related to your repository. In this repository, the readme gives some important commands and links for starting use of git.

## Important git commands

### Branch commands
`git branch` => check available and active branches on local

`git branch -r`	=> check available and active branches on remote

`git checkout -b newBranchName`	=> create new branch from master

`git checkout newBranchName` => go to branch newBranchName

`git checkout -B newBranchName`	=> go to existing or create new branch newBranchName

### File tracking
`git status` => check untracked files

### Local machine to Staging area
`git add fileName` => add given fileName to staging area

`git add -A` => add all files from all directories

`git add .`	=> add all files from present directory

### Creating a local commit
`git commit -m "msg"`	=> create a commit for all files in staging area

### Git pull
`git pull origin branch2`	=> pull all file references(metadata) from remote branch2 to current local branch

`git pull origin` => maps metadata of all branches from remote to pulls it to local

### Some other commands
`git diff` => compares all added or committed files with current local files for modification - previous vs current version

`git diff fileName` => compares added or committed fileName with current version of fileName on local

`git remote -v` => gives aliases and their associated URLs

`git restore <file>`	=> to discard changes in working directory

`git stash` => stashes untracked local commits in a stack so that remote metadata can be pulled for up to date references

`git stash pop` => pops out untracked local commits stashed previously
