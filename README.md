# grocery_mart





PS D:\20240331\grocery_mart> git branch
* main
PS D:\20240331\grocery_mart> git branch grocery_store_local_branch
PS D:\20240331\grocery_mart> git branch
  grocery_store_local_branch
* main
PS D:\20240331\grocery_mart> git checkout grocery_store_local_branch
Switched to branch 'grocery_store_local_branch'
PS D:\20240331\grocery_mart> git status
On branch grocery_store_local_branch
Your branch is up to date with 'origin/grocery_store_local_branch'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
PS D:\20240331\grocery_mart>



git checkout is used to check in into new branch
Git Commands:


clone repo: 
git clone <project_url> —>it will clone the project to your local machine 

Check working branch:
 git branch —-> it will give you in which branch you are now

Create Branch:
 git branch <branchName>

Switch to branch:
 git checkout <branchName>

Add modified file to commit: 
git  add .
git  add fileName
git  add *

Check status of your branch:
git  status 

Commit changes:
git  commit -m “your comment message”
