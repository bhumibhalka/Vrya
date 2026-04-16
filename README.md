# Vrya
This is a project. 
<br>
Author - Bhumi (Bhalka)

Git hub
Install git for Mac using home-brew 
git —version.
git config —global user.name “name”
git config —global user.email “your email”
git config —list ()
git clone <-link-> (to clone a repo on our local machine)
cd <- folder name->
Clear
ls -> to view files this means list files
ls -a -> to view hidden files we can only view them through terminal (it prints all files)
Git status -> for shows our code status

After modifying a files there is 2 step process -> 
1. Add —> commit

Status -> 
1. Untracked -> new files that git doesn’t yet track.
2. Modified -> changed files
3. Staged -> file is ready to be committed
4. Unmodified -> unchanged.

add(staged) -> commit (unchanged)


Add -> adds new or changed files in your working directory to the Git staging area
 
git add <-file name ->  or git add .

Commit -> It is the record of change.

git commit -m “some message”

Push Command 
Push-> upload local repo content to remote repo

git push origin main

bhumi@bhumikas-MacBook-Air Vrya % cd ..
bhumi@bhumikas-MacBook-Air Git_Demo % mkdir LocalRepo
bhumi@bhumikas-MacBook-Air Git_Demo % cd LocalReop
cd: no such file or directory: LocalReop
bhumi@bhumikas-MacBook-Air Git_Demo % cd LocalRepo
bhumi@bhumikas-MacBook-Air LocalRepo % 


git init -> initalizing a new git 

git branch -> to check the branch you are in 
git branch -M main (to rename branch)
git checkout <- branch name-> (to navigate)
git checkout -b <- new branch name -> (to create new branch)
git branch -d  <- new branch name ->  (delete branch) (cannot delete if you are in that branch)

git diff <-branch-> (to compare commits, branches & files & more) 
git merge <-merge->

pull request -> it lets you tell others about changes you have pushed to a branch in a repo on github

git pull origin main
used to fetch and download content from a remote repo and immediately update to local repo to match that content

git log (see all the commits)

undoing changes

case1: staged changes
git reset <-filename->
git reset

case2: commited changes (for one commit)
git reset HEAD-1

case 3: committed changes (for many committs)
git reset <-commit hash->
git reset --hard <-commit hash ->


