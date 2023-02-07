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
