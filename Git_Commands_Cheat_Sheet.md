				GIT CHEAT-SHEET

	Git Intialization
   
git init // create git repo on local directory

git clone <remote url> <directory name> // clone an existing repo from the remote to a local dir

git remote add <remote name> <remote url> // to add a remote to a local existing  repo folder

	File Add (Unstaged>> Staged)
    
git add <file name> // use . for all

git reset HEAD <file name> // unstage a file

git rm <file name> // remove a file // use --cached to remove file from staged and from remote

cat .gitignore // create git ignore file to ignore specific local file 

	Commiting Staged Files
    
git commit -m "your commit message" // commit with message

git commit -a -m "your commit message" // git add + git commit

git commit --amend -m "your commit message" // after adding a forgotten file and replacing previous commit 

git status // to check the status of the local file // use -s for short

git log // check the commit status

git diff // shows you the exact lines added and removed // use --staged for staged files

	Push & Pull To Remote

git push <remote name> <branch name> // to push the unmodified file to the remote server

git pull <remote name> <branch name> // to pull files from an existing repo to local

	Branching

git branch <branch name> // creating a branch

git branch // local branch list

git branch --all // local + remote branch list

git checkout <branch name> // switch to an existing branch

git checkout - // switch to previous branch

git checkout -b <branch name> // create and switch to a branch

git log <branch name> // to see the status of a specific branch

git log --all // to see the status of all branch

git log --oneline --decorate --graph --all // to see the branch graph

git checkout -d <branch name> // locally delete a branch

git push origin --delete <branch name> // delete a branch from remote

git merge <branch name> // merge current branch to another branch

git branch --merged <branch name> // merged branches with the branch (default current branch)

git branch --no-merged <branch name> // not merged branches with the branch (default current branch)

git branch --move <previous branch_name> <new_branch_name> // change local branch name

git push --set-upstream <remote name> <branch> // changed the branch name in the remote too




