## git gud

### To bring a repository from github onto your machine
git clone (repository url)

### To pull changes from the github
git pull

### To commit changes to the github (make sure you're on the correct branch)
(for all changes, for specific changes replace period with specific file names in quotation marks)  
git add .  
git commit -m "commit message"  
git push

### To make sure everything is ok
git status

### To view all local branches (branch with a star next to it is current working branch, add --all at the end to see remote branches as well)
git branch

### To change branches
git checkout "name of branch"

### To create a new branch
git checkout -b "name of new branch"

### To merge changes from branch a into branch b (note: does not delete branch a)
git checkout "branch_b"  
git merge "branch_a"

### To delete a branch
git branch -d "name of branch"

### Help I forgot the commands
git

## Navigating files in the terminal
*directory = folder*

### Going into a directory (slash is optional)
cd name-of-folder/

### Coming out of a directory
cd ..

### Where am I
pwd

### What's in this directory
dir

## AWESOME PRO TIP:
Right click > click more options > open git bash here  
to open git bash directly in whatever folder you want!!!

Or you could just use cmder.
https://cmder.app/
