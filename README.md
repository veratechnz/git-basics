# Git Basics

## Initializing A Git Repo
git init

git add -A

git commit -am "a message for your git commit"

git remote add origin https://github.com/youraccount/reponame.git

git push -u origin master


## Normal Git Cycle For Pushing

git add -A

git commit -am "a message for your git commit"

git push


## Group Branching

#### Create
git branch (This will tell you what branch you are on)

git branch melsbranch

git checkout melsbranch

#### After you have completed your changes commit them to the branch
git add -A

git commit-am"commiting branch changes"

#### Then go back to the master, Pull the master to get the latest update. Finally merge it with your branch/changes
git checkout master

git pull

git merge melsbranch

#### Then commit and push the updated master to the remote (Git Servers)
git add -A

git commit-am"commiting branch changes"

git push





