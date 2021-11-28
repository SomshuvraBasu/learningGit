**Git Notes**

git  -- version

git config -- global user.name "Your Name"

git config -- global user.email "Your Email"

ALITER 

git config -- global -- edit

"This opens the editor for the config file"

git init       ==  initialise git

git add <file>    ==  staging a file, starts getting tracked

git rm --cached <file> == remove from staging

git commit -m "initial commit"

git add . == all files get into staging area

git checkout <commit hash code/branch name> this makes us enter the specified branch

git checkout master == returns to master 

 git branch <branchname>

git checkout -b <branchname> == make branch and check   it out

Once you are inside a branch now if you make changes or add/delete anything to your project it will be in this newly created branch

git merge <branch name> == do this inside the branch in which you want to merge

gitignore == the files which you don't want to be in git ecosystem like secret keys

touch .gitignore

touch filename.extension == creates file in the branch

a gitignore file is created , the files/folders you enter in it aren't included in the ecosystem

**GITHUB**

in shell

git remote -v == blank means still not linked otherwise fetch and push origin is shown

git remote add origin <paste the HTTPS link address>

to push master branch into GitHub repo

1. git branch -M master
2. git push -u origin master

use personal access token in password
