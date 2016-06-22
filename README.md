# Git Basics

## Initializing A Git Repo
git init

git add -A

git commit -am "a message for your git commit"

git remote add origin https://github.com/youraccount/reponame.git

git push -u origin master


## Normal Git Cycle

git add -A

git commit -am "a message for your git commit"

git push


## Group Branching

### Create

git branch (This will tell you what branch you are on)
git branch melsbranch
git checkout melsbranch
#### After you have completed your changes
git add -A
git commit-am"commiting branch changes"
git checkout master
git pull
#### Merge Time
git merge melsbranch



