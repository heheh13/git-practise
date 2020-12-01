
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
