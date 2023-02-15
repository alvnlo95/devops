# devops class
learning git from github

# GIT Commands

git init: to initialize and empty repository

git clone <repo url>: to clone the remote repository in to local machine
after cloning "cd reponame/directory"

git branch: to check which branch we are working on

git branch -a: to display all the branches

git checkout -b <branch name>: to create a NEW branch

Example: git checkout -b my_local_branch

git add . : to add the files (make the files into tracking from track mode)

git commit -m "commit message": to create the commit (version)

git push origin <branch name>: to push local changes to remote repository for the respective branch

git pull origin <branch name>: to pull branch into current branch

git diff: to see the difference in local machine (this has to be performed before git add)

git status: to check the current status of the files in repo (like untracked, added, any commits to be made)

git log: to view commit information

git push --set-upstream origin <branch name>

git push origin :<branch name> : to delete a branch from remote repo (example "git push origin :feature
/task-1")

git branch -d <branch name> : to delete the branch from local repository

Note: the difference between git fetch and git pull are, git fetch will update the references in local
repo with remote repe (example: if any new branch created, or any branch is updated with new commits)
whereas git pull will update the current branch content/changes

Create merge conflict scenario:
1. create branch task-1 from master 

2. create branch task-2 from master

3. Change a file on task-1 (local)

4. Change the same file from task-2 (remote + local)

5. Merge task-1 to master (local + remote)

6. Task-2 to master

Fix: git pull origin master in to your task-2 branch

Delete << and >> and == lines
