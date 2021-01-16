## Tutorial Git Repository

### Common workflow
1. git init  (initialize wd) 
2. git add <file name> or . (move file to stage step)
3. git commit -m "blah blah" (from stage to repo to commit file with comment)
4. git push origin master
5. git pull (in general) ** git clone (first time ever)

___
### Basic Commands
1. git status (informs about file condition - completed or modified)
2. git remote -v ( presents all available "cloud" storages connected)
3. git remote add ... (connected cloud repo ... is smt additional)
4. git log <br>
5. git checkout commitHashCode filename
___
### Branch related Commands
1. git branch
2. git branch -a
3. git checkout -b new_branch_hname
4. git checkout master
5. git merge dev
6. git push origin dev ... or
7. git push --set-upstream origin dev (while in local branch setup remote repo once for all)
8. git checkout --track origin/newsletter (for a remote branch to be shown in local branches as well)