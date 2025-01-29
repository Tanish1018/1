# vishnuex1
#ex1
git init
git vi file_name.txt
git add file_name.txt
git commit -m "message commit"
git log --oneline --decorate

#ex2
git checkout master
git checkout -b feature-branch
git add .
git commit -m "the message"
git checkout master 
git merge feature-branch

#ex3
git checkout -b "new-branch"
vi file-name.txt
git add file-name.txt
git stash save"message"
git checkout master
git stash apply 

#exp4
git clone url(paste)

#exp5
git init
git remote add origin<git repo url>
git rebase origin/main
git log --oneline

#exp6
git checkout -b feature-branch
vi file-name.txt
git add file-name.txt
git commit -m "merge"
git checkout master
git merge feature-branch -m "message"
git log 


#exp7
git tag v1.0 <commit-SHA>  (hash value)

#exp8
git cherry-pick abc123^..def456 (these are start and end commmits)

#exp9
git show abc123
git log -n1 abc123   (abc123 - commit value)

#exp10
git log --author"vishnu" --since="2023-01-01" --until="2024-12-31"

#exp11
git log -n 5

#exp12
git revert abc123
