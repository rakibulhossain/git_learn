				GIT CHEAT-SHEET


git init // create git repo on local directory

git clone <remote url> <directory name> // clone an existing repo from the remote to a local dir

git remote add <remote name> <remote url> // to add a remote to a local existing  repo folder

git add <file name> // use . for all

git reset HEAD <file name> // unstage a file

git commit -m "your commit message" // commit with message

git commit -a -m "your commit message" // git add + git commit

git commit --amend -m "your commit message" // after adding a forgotten file and replacing previous commit 

git status // to check the status of the local file 

git log // check the commit status

git push <remote name> <branch name> // to push the unmodified file to the remote server

git branch <branch name> // creating a branch

git checkout <branch name> // switch to an existing branch

git checkout - // switch to previous branch

git checkout -b <branch name> // create and switch to a branch

git log <branch name> // to see the status of a specific branch

git log --all // to see the status of all branch

git log --oneline --decorate --graph --all // to see the branch graph


