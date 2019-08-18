### git repo set up an practice

### create repo
- on github.com create a new repository with a readme.md file

### create local folder

### clone repo into local folder
- cd into local folder using PowerShell (terminal program)
- git clone <clone url>
	- example: https://github.com/casierea/PracticeRepo.git

### Common git commands
- `git status` returns the status of the current clone repository
- `git branch` shows which branch of the repository is active
- `git add <file name>` adds a local file to a commit
- `git commit -m "message"` adds a commit message and commits all added files
- `git push <remote> <branch>` pushes committed local files to remote branch on github
	- example: `git push origin master`
- `git init` turns on version tracking in a local folder. This does not automatically link to a github repository.
- `git remote -v` lists the repositorys remotes (these are the URLS to send and receive files to github) with verbose options
- `git checkout -b <branch name>` creates a new branch and makes it the active branch
- `git checkout <branch name>` checks out an existing branch of the repository
- `git pull <remote> <branch>` pulls down from github to local files the files present on github for the remote and branch 
	- example: `git pull origin master` pulls all files from the origin remote for the master branch
- `git remote add <remote name>` adds a new remote with chosen name. Remotes must be copied from a github URL
- `git remote rename <original remote name> <new remote name>` renames a remote
- `git remote remove <remote name>` removes a remote

### Common Bash commands
- `cd <directory>` changes the current active directory on the local file system
- `ls` lists files in current directory
- `mkdir <directory>` makes a new directory