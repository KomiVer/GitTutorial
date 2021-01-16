## Tutorial Git Repository

### Common workflow
1. git init  (initialize wd) 
2. git add <file name> or . (move file to stage step)
3. git commit -m "blah blah" (from stage to repo to commit file with comment)
4. git push origin master
5. git pull (in general) ** git clone (first time ever)

* git status (informs about file condition - completed or modified) <br>
* git remote -v ( presents all available "cloud" storages connected) <br>
* git remote add ... (connected cloud repo ... is smt additional)
* git log <br>

* git branch
* git branch -a
* git checkout -b new_branch_hname

* git checkout master
* git merge dev

* git checkout commitHashCode filename
* git push origin dev ... or
* git push --set-upstream origin dev (while in local branch setup remote repo once for all)
* git checkout --track origin/newsletter (for a remote branch to be shown in local branches as well)