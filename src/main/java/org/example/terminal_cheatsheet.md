# Cheatsheet
## Size changes with '#'
### `backquotes to highlight`

`~` home directory

`cd` change directory

`pwd` print working directory

`ls` list
#### -l more detailed list
#### -a all (. infront of files means its hidden)
#### -la combined

`mkdir` make directory (folder)

`touch` make file

`mv` move

`cp` copy

`rm` remove
-r (rm my_directory will state it's a directory, you
need to do rm -r my_directory), -f bypasses confirmation

-rf + tilde (dont break the mac please)

`git init` initialise git repository

`git status` check if changes are staged for commit or not

`git add` add file

`git commit -m"present tense step taken"` commit message

`git add . or git commit -a` stage all changes in current directory

`git log` history of edits in repository

`git revert` undo a specific commit (ID of commit from log)

`git reset` undoes everything since a given commit

`git rebase` reverses commits and removes from history

`git remote add origin your/url/here` link local repository to GitHub (origin is primary remote, add is to make new link)

`git push origin main` upload from one to the other (main branch)

`git clone repository/url/here` allows others to get a copy, do not clone a repository inside another one

`git pull origin main` download changes from others if they upload to the repository