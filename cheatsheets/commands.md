# Git command cheatsheet

## Setup
`git --version` · `git config --global user.name "Name"` · `git config --list`

## Start / copy
`git init` · `git clone URL`

## Inspect
`git status` · `git diff` · `git diff --staged` · `git log --oneline --graph --all` · `git show`

## Stage / commit
`git add FILE` · `git add -p` · `git commit -m "message"`

## Branch
`git branch` · `git switch -c NAME` · `git switch main` · `git merge NAME`

## Remote
`git remote -v` · `git fetch` · `git pull` · `git push -u origin BRANCH`

## Recover
`git restore --staged FILE` · `git restore FILE` · `git revert COMMIT` · `git reflog`

## Tags
`git tag -a v1.0.0 -m "Release"` · `git push origin v1.0.0`
