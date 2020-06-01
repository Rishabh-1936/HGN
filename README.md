# HGN
## Git Commands

Git Important Commands:

Note: Without setting username and email we cannot commit as git doesnot know where to commit 
---------------------------------------------------------------------------------------------

## Three types of commit:

    Checkout commit (use to check the code at a particular past commit)
    Revert commit (use to revert the code changes at particular past commit)
    Reset commit (use to reset the commits)
----------------------------------------------------------------------------------------


Usage   |   Git Command  
--------|------------------
To check the version of git | git --version 
To add user name  | git config --global user.name "your name"
To add the email  | git config --global user.email "you@emaple.com"
To check user name  | git config user.name 
To check the email  | git config user.email 
To add the file in the staging area | git add file_name.txt
To add multiple files i.e all files in the staging area | git add .
To check the status of the git repositry  | git status
To clean the comand line(in git bash) | clear
To switch to particular commit  | git checkout id_of_commit
To switch to master branch  | git checkout master
To create a branch  | git branch branch_name
To check/see all the branches | git branch -a
Shortcut to create new branch and switch to it  | git checkout -b branch_name
To switch to another branch | git checkout branch_name
To delete a branch when it is not merged with master branch | git branch -D branch_name
To delete a branch when it is merged with master branch | git branch -d branch_name
To merging branches first be in that branch in which you want to merge the other branch | git merge branch_name
To pushing on github  | git push url_of_repo branch_name
To create a git repository in the folder specified  | git init foldername
To create git repository in the current folder | git init
Cloning the repository  git clone url
Cloning a specific branch | git clone cloning_project_url -b branch_name
To check the alias of the cloned repositories | git remote -v
Git Giving “fetch first” error when trying to push  | git push origin master --force
To add message to the new commit  | git commit -m "message..."
To check the commit history/log with the author details | git log
To check the commit history/log without the author details  | git log --oneline
To check the last commit history with all changes made  | git show
To add the unstaged file and commit directly use Express command  | git commit -a or git commit -am "message"
To unstage the recently staged file | git reset HEAD README.md
To creating an alias in git | git config --global alias.alias_name "command"
To see all the global variables and alias  |  git config --global --list
Rename and Delete files | git mv old-name new-name
Excluding the unwanted files  | notepad .gitignore


