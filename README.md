# learn_git

## Clone Repo
> git clone <link Repo>

## Create File Git
> git init

## Check Status of Working Dir
> git status

## Add Changing to Staging Area
> git add\
> git add . (Add all file)\
> git add <file_name> (Add any file with name)

## Show History Commit
> git log

## Show Detail a Commit
> git show <id_commit> (get from git log)

## Show Diffirent a Commit after change
> git diff <id_commit>

## Goto history Commit, Goto history File ( Unconfirm to Staging Area (git add .) )
> git checkout <id_commit>\
> git checkout <file_name>

## Goto history Commit (Confirm to Stagin Area (git add .))
> git reset <file_name>\
> git reset --soft <id_commit> : (goto confirm Staging Area)\
> git reset --mixed <id_commit> : (goto unconfirm Staging Area)

## Create a new Branch
> git checkout -b <name_branch>

## Goto branch
> git checkout <name_branch>

## Merge A -> B
> git checkout A\
> git merge B

## Push Repo to Github
> git remote add origin <link Repo Github>\
> git push\
> or\
> git push -u origin master

## Push Branch
> git push origin <name_branch>

## Delete Branch
> git branch -D <name_branch>

## Download Branch to Local to Run
> git fetch <name_branch>

