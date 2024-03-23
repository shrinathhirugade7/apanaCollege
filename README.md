# apanaCollege
This my first Git Repository
Hello dosto

Author- Shrinath Hirugade

Download GIT CSM

Github Commands
in git Bash first we have to configur the git for git website
git config --global user.name 'Username'
git config --global user.email 'email'
git config --list

Then come to the terminal
cd 
git clone URl
ls
git status

// WE have two steps add and Commit

git add index.html
git add . (for all files)
git commit -m "all commands are added into Readme.md"
git push origin main


//mkdir newrepo

Code first approch
git init
git remote add origin https://github.com/shrinathhirugade7/LocalRepo.git
git remote -v
git branch
git branch -m main (change the branch name to main)
git push origin main
git push -u origin main

#Branch Commands
git branch
git branch -M <renamed name> (git branch -M main)
git checkout -b feature1 (create new branch having name as feature1)
git checkout main (To switch to main branch)
git branch -d feature1(To delete the branch feature 1)
simillarly for second

git push origin feature1 (we have pushed the changes on feature1 branch)

# Merge two branches
git diff main
git merge main
# second way of merging the Branches are
create PR
compaire and pull request button on git hub

//we have merged the branches with website but changes are not seen on VS code
write ->
git pull origin main

//Resolving Merge Conflict
git add .
git commit -m ""
git merge main (Conflict, we have resolve it)
git checkout main -> git merge feature1
// Conflict solved


// UnDoing changes
delete the line
add it
git reset index.html
git reset (This is for all)

// part second for commit
delete the line
add change
commit change
now we want to undo
git reset HEAD~1 (undo the recent change)
git log (to check all our commits)
git reset b0704b39b7c4ed08c044bb02f44a4584bd65766f =>To go multiple steps piche to undo
git reset --hard  b0704b39b7c4ed08c044bb02f44a4584bd65766f (This will give the previous change reflected in VS CODE)

# Fork
it means that copy repositories of others into our repository

Course has been Finished