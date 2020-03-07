# git-command
Personal cheat sheet

git init  

git add . OR git add <file name> 

git status 

git commit -m 'First Commit'

git push origin master

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

Switching to a different branch:
git checkout login

Disconnecting from github:
git remote rm origin

Checking account detail:
git config --list

git config --global user.name "---"
git config --global user.email "---@gmail.com"

REMEMBER: If asked username and password, use User TOKEN instead of login password!!! 
