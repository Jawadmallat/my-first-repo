What command shows you the current state of your repository?
A: git status
What command stages readme.txt for commit?
A: git add .
What command commits with the message "Add readme file"?
A: git commit -m "Add readme file"
What command shows your commit history?
A: git log 

The "git status" command explains that modifications have been made to the readme.txt file, but they have not been commited
and pushed yet. 

git log shows 2 commits, the initial commit and the readme commit 

git diff: shows the differences in the repo since the last push 

git log --oneline: this command shows each commit in one line (and the message with the commit)


git branch: shows all local branches 
git branch -a: shows all local and remote branches 
git branch -r: shows only remote branches
git branch feature-script: What command creates a new branch called feature-script
git checkout feature-script: What command switches to the feature-script branch
git checkout -b dev:  creates and switches to a new branch called dev
git checkout feature-script: Switch back to the feature-script branch
git branch: verify we are on the correct branch
