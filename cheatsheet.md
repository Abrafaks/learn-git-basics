# Git Command Cheat Sheet

##### Cloning your remote directory
        git clone <remote directory>

##### Pulling down all branches in a remote repo, not just the default branch
        git fetch --all

##### Checking that status of your local repository - shows changed but not added files in red
	git status

##### Creating a new branch for you to work on
        git branch <new branch name>

##### See all branches in your remote repository
	git branch -a

##### Moving onto a branch
        git checkout <branch name>

##### Deleting a branch
	git branch -d <branch name>

##### Moving your changes to the staging area
        git add <file name>

##### Committing your changes
        git commit -m '<commit message here>'

##### Merging changes from another branch, to your current branch
        git merge <branch you want to merge with your current branch>

##### Pulling remote changes into your local repo
        git pull origin <branch name>

##### Moving files while preserving git history
	git mv <source> <destination>

##### Creates a branch, and moves you onto it AT THE SAME TIME
	git checkout -b <new branch name>

##### Creates, names and pushes existing branch to GitHub
	git push origin <branch name>

##### Git is not seeing changes in GitHub:
	git fetch --all
	git reset --hard origin/master
