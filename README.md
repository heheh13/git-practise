
# git-practise

------------

# git ignore

* need to create  a .gitingore file
* need to untrack a tracked file to ignore it git rm --cached FILENAME

## *.a

ignore all files with extention .a

but do track lib.a, even though you're ignoring .a files above

## !lib.a

## /TODO

only ignore the TODO file in the current directory, not subdir/TODO

## build/

ignore all files in any directory named build

## doc/*.txt

ignore doc/notes.txt, but not doc/server/arch.txt

## doc/**/*.pdf

ignore all .pdf files in the doc/ directory and any of its subdirectories
