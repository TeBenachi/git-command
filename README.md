# git-command
Personal cheat sheet

git init  

git add . OR git add <file name> 

git status 

git commit -m 'First Commit'

git push origin master


#Pull

(1) git pull

(2) Hit "i"

(3) Type merge message => Change styling...etc

(4) Hit esc

(5) :wq

(6) Hit enter





Removing a file to unstage:
git rm --cached <file>  

Removing everything from the repository:
git rm -r --cached .

Exclude a file globaly in all repositories:
git config --global core.excludesFile ~/.gitignore

Create .gitignore :
touch .gitignore

Creating a branch:
git branch login

Get out of a main branch:
git remote rm origin

Switching to a different branch:
git checkout login

Disconnecting from github:
git remote rm origin

Checking account detail:
git config --list

git config --global user.name "---"
git config --global user.email "---@gmail.com"

REMEMBER: If asked username and password, use User TOKEN instead of login password!!! 
