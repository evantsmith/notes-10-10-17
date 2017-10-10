git init : creat a git repository (look for the .git folder). you'll need to run this command ONCE for every project you do. 

// git is a hidden folder so must use ls -a 

//whenever you want to save your work
git add -A : add all files to the staging area (prepare them to be committed)
git commit -m 'initial commit' 
git status

git log: look at history of commits 

git remote add origin <repo URL> : adds another reposotory as a remote of the local repo, so you can sync your code. You can call the remote anything you want, but it is very conventional to call the first remote origin

git remote rm origin : remove the remote called 'origin'
git push origin master : update the origin remote (probably github) with the code from your local repo
git pull origin master : update your local repository with the code from the origin remote (probably github)


git init: once per project
git remote add origin: once per project

// type these commands at least every hour

git add -A
git commit -m 'i did work'
git push origin master

git clone <repo URL> : copy a remote repo to your local machine that you do not already have locally

