
# Git Notes

## Normal workday

init repo

- git init

add file to repo

- git add .
- git ci -m 'add file'

add edited file to repo

- edit files
- git ci -am 'edit file'


## Branching

create branch

- git co -b feature-branch

switch to branch

- git co feature-branch

prepare branch for merge

- git rebase master


## Merging

merge feature into master

- git merge --ff-only feature-branch
