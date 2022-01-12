Version Control System
======================
1.CentralVCS
2.Distributed VCS

Distributed VCS - Git
===================
--Distribution revison control and source code management system

For First time Git user
===================
git config --global user.name "Betsy Jaise"
git config --global user.email betsyjaise2015@gmail.com

2ways to use Git
=================
1. New Project
2. Existing Project

1.New Project
-----------
--->git init

 --.git folder is there(hidden)
 --dir/a to show hidden file
 --tree to show files in git ,..it's hidden
 --Add some file eg.index.html
 --move to the new folder

 --->git status

Project in git Repository/Repo
------------------------------
==>create a version to git repository
--->git add -- tempory cache
---> git add --all
--->git commit -m "Initial Commit"
--->git log
--->git log --all
--->git checkout commitId

Branching ( To create a new feature)
---------

--->git branch branchname
--->git branch
--->git checkout feature

Merging ( Merge features to master)
-------
--->git merge feature
