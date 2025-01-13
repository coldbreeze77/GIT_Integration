This is sample read-only file. Using this for GitHub demo.

1. git init  ==> initialized git repositorygit 
2. git config --global user.name "AbdullahS"
3. git config --global user.email "coldbreeze77@outlook.com"
4. git add .  ==> this will add all the files to the git staging area
5. git status  ==> let me know status of the current git branch (main)
6. git commit -m "this is an initial commit"  ==> commiting files from staging area to git repoexit
7. git rm file2.txt  => remove file from git

Create a branch:
1. git checkout -b "Feature1"  
2. git add "file3.txt"
3. git commit -m "file 3 added to the feature 1 branch"

Swith to the main branch
1. git checkout main

Merge new branch to main
git merge Feature1


Publish to remore repo
git remote add origin https://github.com/coldbreeze77/GIT_Integration.git
git push -f origin main


Remove orignal repository
git remote -v
git remote remove origin


If you want to integrate the remote changes, use 'git pull' before pushing again
