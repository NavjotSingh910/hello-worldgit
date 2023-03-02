# hello-world
Hello World repository for Git tutorial
This is an example repository for the Git tutoial on https://www.w3schools.com

This repository is built step by step in the tutorial.


 git status

 git add index.html
git add --all
git add -A


git status --short //for see changes in short form

//Note: Short status flags are:

            ?? - Untracked files
            A - Files added to stage
            M - Modified files
            D - Deleted files


git commit -m "Message"
git commit -a -m "Updated index.html with a new line without staging"

//history of commits 
git log

//help command
git command -help //-  See all the available options for the specific command
git help --all //-  See all possible commands

//branches
git branch hello-world-images
git branch //see how many branches are there 
-b option on checkout 
git branch -d  branchname //delete branch

git merge branchname

//connect git hub make repo and copy link 
 git remote add origin https://github.com/NavjotSingh910/test.git //create remote Git repository named "origin"
 
 git push --set-upstream origin master 
 git remote rm origin //delete origin
 
 
 //pull is a combination of 2 different commands:
       fetch
       merge
git fetch origin
git log origin/master

git diff origin/master  //differences between our local master and origin/master
git merge origin/master



