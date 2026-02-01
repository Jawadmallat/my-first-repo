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
we have two commits: the initial commit and the add readme commit 

git diff shows the difference between current version and the one since the last push
git log --oneline shows all commits, each in one line 

What command lists all branches in your repository? : git branch -a
What command creates a new branch called feature-script?: git branch feature-script 
What command switches to the feature-script branch? : git checkout feature-script
What single command creates and switches to a new branch called dev? git checkout -b dev
Switch back to the feature-script branch : git checkout feature-script
Verify you are on the correct branch: git branch 

install.sh is not present because we are in the main branch, and the file is in the feature-script branch

What command merges feature-script into main?: git merge feature-script (we have to go back to the main branch) 

