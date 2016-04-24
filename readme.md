
# Git Notes

## Initializing

init repo

- git init



## Working with Staging Area

add to staging

- git add file
- git add .

remove from staging

- git reset file
- git reset

view staging

- git st



## Working with files

add untracked file to repo

- git add file
- git ci -m 'add file'

list tracked files

- git ls-files

list untracked files

- git status

update tracked file in repo

- git ci -am 'edit file'

delete tracked file

- git rm file

delete edits made in working directory

- git co .

delete edits made in a file

- git co file



## Working with Branches

create branch

- git co -b feature-branch

list branches

- git br

rename branch

- git br -m new-branch-name

delete branch

- git br -D feature-branch

switch to branch

- git co feature-branch

prepare branch for merge

- git rebase master



## Merging

merge feature into master

- git co master
- git merge feature-branch



## Working with Commits

list commits

- git lg

erase all commits after 0024fd4

- git reset --hard 0024fd4
