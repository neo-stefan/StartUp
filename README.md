### This is where i will be jotting down Git basics stuff
### git status will display whether git is keeping track of your files

### git init will make that folder a git repository by making a hidden 
# .git file in that folder

### git status and the files are red in color just means that they are 
# not being tracked by git as files in the repository 

### git add will make the files tracked thus adding it to the repository 
# it also helps to track changes made to a file that has been added and 
# committed before to the git repository after which we can then commit 
# those changes

### git commit -m "commit numbr or a id" this will save the changes we 
# made for this version so next time we modify and commit we get a 
# different version and stuff saved with the previous saved commit still 
# available

### git log will display all your commits 
### git checkout and first seven digits of the commit (get this in the 
# log) we want to go back to will show us the previous commit doing so 
# will take us out of the master branch and leave us floating so if we 
# want to save that commit we would have to use the git checkout -b and 
# specify a new branch name where this edition can be saved 

### branch is like a folder where the commits are kept
### git branch will display the brach where we are

### to switch between branches use git checkout branchname to go to and 
# boom we are there 

### git remote -v shows us the repository we have on our server github 
# nothing shows just use git remote add name ssh copied from the github 
# repository we copied   
