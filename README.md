# GITHUB COMMANDS

## to config a local git repository
> git init 

## add files 
> git add "path"

## config username and email before commit

> git config --global user.name "name"

> git config --global user.email "email"

## commit files
> git commit -m "message"

## status of modified and untracked / staged files
> git status

> git status -s

## adding or connecting a repository
> git remote add origin "repository url"

## printing all origins and branches
> git remote -v

## cloning a repository
> git clone "repository url"

## listing saved points 
> git log 

> git log --oneline

## going back to previous save point
> git reset [--hard] [--soft] [--mixed] head~[number]

## remove git
> rm -rf .git

## know current branch name
> git branch

## list all branches
> git branch -a

## list all remote branches
> git branch -r

## create new branch
> git branch branch-name

## switch between branches
> git switch branch-name

> git checkout branch-name

## merge branch with another branch
> git merge branch-name

## delete branch
> git branch -d branch-name