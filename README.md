
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



[Back To Top](#table-of-contents)


In case if you made changes before git pull
--

| Command       | Description           | 
| ------------- |:-------------:| 
| git stash | Stach changes |
| git pull   |    | 
| git stash apply | Merge changes|
| git add . |  |
| git status | |
| git commit -m "typo" | |
| git push -u origin main | Merge to main branch|




Creating a branch
--

| Command       | Description           | 
| ------------- |:-------------:| 
| git pull | Pull before creating a new branch |
| git checkout -b (branchName)   | Creating a branch    | 
| git push origin (branchName) | Push the new branch on github |
| git checkout (branchName) | Switching to a different branch  |
| git branch -d (branchName) | Deleting a branch |


Pull
--
| Command       | Description           | 
| ------------- |:-------------:| 
| git pull     | pull request  |
| Hit "i"      | Type  message "Change styling" etc |
| :wq          | Escape    |
| Hit enter    |            |


Unstaging 
--

| Command       | Description           | 
| ------------- |:-------------:| 
| git rm --cached (file)    | Removing a file to unstage    | 
| git rm -r --cached .  | Removing everything from the repository     | 



--


Exclude a file globaly in all repositories:
git config --global core.excludesFile ~/.gitignore

Disconnecting from github:
git remote rm origin

Checking account detail:
git config --list

git config --global user.name "---"
git config --global user.email "---@gmail.com"

REMEMBER: If asked username and password, use User TOKEN instead of login password!!! 



