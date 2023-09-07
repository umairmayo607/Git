# //To set username and email in Git to create new repository:

git config --global user.name 
git config --global user.email 
//To check username and email we use this command:
git config --list

# How to check All list of folder:

Use ls to watch all files and folder
use ls -a to watch hidden folders and file

# Clone & Status

Clone:
(git clone <Link of Repository>)
status:
(command: git status)

# 4 stages when we change our code:

1-Untrack
2-Modified
3-stages
4-unmodified(unchanged)

# Add & Commit

Add:
add new or change file in your workind directory to the git staging area:
(git add <file name>)
Commit:
(git commit -m "some message")

# Push Command:

push: upload LOCAL REPO content to REMOTE REPO
(command: git push origin main)

# INT COMMAND:

INIT: use to create a new git Repo:

# In all these steps we will also follow add & commit

1-(git init)
2-(git remote add origin <link of repo>)
3-(git remote -v) //to verify
4-(git branch) //to chech branch
5-(git branch -M (main ))
6-(git push origin main)
