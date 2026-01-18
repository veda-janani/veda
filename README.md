mkdir file
cd file
git init
touch dot.txt
vi pk.txt
git add .
git status
git log
vi pk.txt
git add .
git commit -m"added a file"
git add .
git status
git log
--------2---------
git branch new
git branch
git checkout new
vi pk.txt
git add .
git stash
git checkout master
git merge new
git log
------3--------
git checkout new
vi pk.txt
git checkout master
git stash apply
git status
git add .
git status
git commit -m "stash apply"
git log
