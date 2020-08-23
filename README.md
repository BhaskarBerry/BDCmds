# BDCmds
Git commndas used frequently 
SBT commnads
pwoershell commands

-------------------------------------
--Git setup

1. Configure  your name and email
> git config --global user.name "berry"
> git config --global user.email "berry@email.com"

2. Repositories
> git init  # intialize .git

> git status # Tracks the repo

> git add filename # staged in local repo

> git add . # adds all the chnages

> git commit -m "message " # commits to local repo

> git log # history of commit

> git checkout <hash> # goes to previous commit

> git push # to remote branch 
 
3. Branches
> git branch # list all the branches

> git branch <featurebranch name>

> git checkout newbranchname

> git merge develop # you are in featurebranch and mergeing the develop branch to feature branch