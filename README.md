
### Table of Contents

* [Initializing a new Git repo](#initializing-a-new-git-repo)

* [Creating a branch](#creating-a-branch)

* [Unstaging](#unstaging)


```


*First thing first*,  `touch .gitignore` to create .gitignore on local machine and add untracked files


```


Initializing a new Git repo
--

| Command       | Description           | 
| ------------- |:-------------:| 
| git init            | Initializing git | 
| git add .           | Adding the files    |  
| git status          | Checking the files     | 
| git commit -m 'Initial Commit' | Add note to commit     | 
| git push origin master   | Pushed into a repo     | 


<div align="right"> [Back To Top](#table-of-contents)</div>

Creating a branch
--

| Command       | Description           | 
| ------------- |:-------------:| 
| git checkout (branchName) | Get out of  branch |
| git branch (branchName)   | Creating a branch    | 
| git checkout (branchName) | Switching to a different branch  |
| git branch -d (branchName) | Deleting a branch |



Unstaging 
--

| Command       | Description           | 
| ------------- |:-------------:| 
| git rm --cached (file)    | Removing a file to unstage    | 
| git rm -r --cached .  | Removing everything from the repository     | 



--

#Pull

(1) git pull

(2) Hit "i"

(3) Type merge message => Change styling...etc

(4) Hit esc

(5) :wq

(6) Hit enter

Exclude a file globaly in all repositories:
git config --global core.excludesFile ~/.gitignore

Disconnecting from github:
git remote rm origin

Checking account detail:
git config --list

git config --global user.name "---"
git config --global user.email "---@gmail.com"

REMEMBER: If asked username and password, use User TOKEN instead of login password!!! 



