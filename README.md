## Git List of Commands

### Common workflow
- git init  (initialize wd)
- git add <file name> or . (move file to stage step)
- git commit -m "blah blah" (from stage to repo to commit file with comment)
- git push origin master
- git pull (in general) ** git clone (first time ever)

___
### Basic Commands
- git status (informs about file condition - completed or -dified)
- git remote -v ( presents all available "cloud" storages -nnected)
- git remote add ... (connected cloud repo ... is smt -ditional)
- git log <br>
- git checkout commitHashCode filename
- git rm -r cached filename

___
### Branch related Commands
- git branch
- git branch -a
- git checkout -b new_branch_name
- git checkout master
- git merge dev (while in master merge dev, i.e. bring dev -anges into master)
- git branch -d (or -D) branch_name ; git push origin --delete -anch_name
- git push origin dev ... or
- git push --set-upstream origin dev (while in local branch -tup remote repo once for all)
- git checkout --track origin/newsletter (for a remote branch to be shown in local branches as well)
- git branch --merged

___
### Stash related Commands
- git stash save "stash message" ; stash uncommited changes
- git stash list ; list stashes
- git stash apply stash{0}
- git stash pop ; or git stash pop stash{1}
- git stash clear

___
### DiffMerge related Commands
- git difftool origin/master
- git difftool --dir-dif -y -g -t meld
- git mergetool --tool=meld
