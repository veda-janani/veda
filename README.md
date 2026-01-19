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
-------4-------
mkdir clone
cd clone
git clone https://
cd vedajanani
git fetch origin
git rebase origin
git log
cd ..
cd ..
git checkout new
vi pk.txt
git add .
git commit -m "edited a file"
git checkout master
git log
git tag v1.0
git tag v1.0 7cdef
git show tag v1.0
git branch
git checkout source-branch
vi pk.txt
git add .
git commit -m "this is edited source branch"
vi pk.txt
git add .
git commit -m "this is edited source branch"
git log
git checkout master
git cherry-pick 9b28ac
git show d73b32f25
git log --author="vedajanani" --since"2024-11-17" --until="2024-11-19"
git log -s
git revert 9b28ac
git log
