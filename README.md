## GitHomeWork
<p><b>git init			-></b>To create a new  git local repository on your PC.
<p><b>git status	 -></b>To view listed files you have changed and those file you still need to add or commit.
<p><b>git config --global user.name "Your name"-></b>declare who you are (onetime needed). 
<p><b>git config --global user.email “your email”-></b>declare your email (one time needed).
<p><b>git config –list	-></b>To see User name and user email which is use this repository. 
<p><b>git add	filename 	-></b>Add one(single) file to Staging.
<p><b>git add --a	   	-></b>Add all files to staging together.
<p><b>git log			-></b>This command is used to check the commit history on git.
<p><b>git log –oneline	-></b> To View log history shortly.
<p><b>git diff	-></b> use this command to different between working directory and staging area latest change.
<p><b>git diff –stage	-></b>after staging show what you change before.
<p><b>git show gitnumber	-></b>To show your changees which i done previously. To find gitnumber command: git log –oneline.
<p><b>git diff 1gitNum 2gitNum-></b>To show defferent(how ever change) between git 1 & git 2.
<p><b>git diff  head	-></b> use this command to different between working directory and local  repository.
<p><b>git commit -m "mass"	-></b>Commit changes to head locally final stage(but not yet to the remote repository).
<p><b>git push origin branchname	-></b>Send changes to the master branch of your remote repository(github);
<p><b>git pull origin branchname	-></b>To merge changes on the remote server to your local working directory on your PC.
<p><b>git fatch		-></b>from copy remote to local repo.
<p><b>git clone url		-></b>To Create a working copy of a git local repository from github.
<p><b>git remote		-></b>To check connectivity local working directory to remote server.
<p><b>git remote –v		-></b>To check connectivity remote repository.
<p><b>git brunch	-></b>To list all the branches in your repository, and also tell you what branch you're currently work.
<p><b>git branch branchname-></b>To create new branch.
<p><b>git checkout –b new branchname-></b>To create and checkin branch together.
<p><b>git checkout branchname -></b>Switch from one branch to another branch.
<p><b>git marge branchname 	-></b>To merge a different branch into your active branch.
<p><b>git brance –d branch name-></b> delete branch.
<p><b>git clean -f		-></b>To remove local file.
<p><b>git clean -fd		-></b>To remove from directories.
<p><b>git clean -fx		-></b>To remove ignored and non-ignored files.
<p><b>touch filename-></b> Create new file on local derectory.
<p><b>Rm filename		-> </b>Delete File From local derecority.
<p><b>git reset HEAD filename-></b>delete from staging area. After commit must.
<p><b>rm -rf .git	-></b>To remove a file from a Git repository and your working directory but not remove on pc.we can work again Git repository those file. 
<p><b>git fatch origin-></b>Instead, to drop all your local changes and commits, fetch the latest history from the server and point your local master branch at it, do this if connected with remote to github.
