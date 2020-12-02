
# git-practise

------------

# git ignore

* need to create  a .gitingore file
* need to untrack a tracked file to ignore it git rm --cached FILENAME


## *.a

Ignore all files with extention .a

But do track lib.a, even though you're ignoring .a files above

## !lib.a

## /TODO

Only ignore the TODO file in the current directory, not subdir/TODO

## build/

Ignore all files in any directory named build

## doc/*.txt

Ignore doc/notes.txt, but not doc/server/arch.txt

## doc/**/*.pdf

Ignore all .pdf files in the doc/ directory and any of its subdirectories

# Git Log

## git log

show log

## git log -p -2

show the patch output upto 2 commits

## git log --pretty=format

## git log --pretty=oneline

logs hash and  commit messages

## git log --pretty=format:"%h - %an, %ar : %s"

logs hash,user,time,commit messege

# modifing things
------------------------

# Working with remote

`git remote -v` show the urls git stored

`git remote add <name> <url>`

`git fetch`  download the upadtes from remote to local
`git pull` fetch and merge remote to local

`git remote rename <name> <name>`  
`git remote remove <name>`

# git Tag

`git tag <version> -m 'commit message'`

`git show <version>`

*git does not implicly push tags on remote

`git push origin <tagname>`

`git push origin --tags`

`git tag -d <tagname>` to delete from local

`git push origin --delete <tagname>` from remote

# Branching

`git checkout -b <branchName>`

`git branch -d <branchName>`

`git branch --move bad-branch-name corrected-branch-name`

`git push origin --delete bad-branch-name`
