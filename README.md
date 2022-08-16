To connect the local repository to a remote server, use the command below:

git remote add origin <host-or-remoteURL>

git checkout creates branches and helps you to navigate between them. For example, the following basic command creates a new branch and automatically switches you to it:

command git checkout -b <branch-name>

git push is used to send local commits to the master branch of the remote repository. Here’s the basic code structure:
git push origin <any branch name >

To switch from one branch to another, simply use:
git checkout <branch-name>

If you want to delete a branch, use:
git branch –d <branch-name>

git remote lets you view all remote repositories. The following command will list all connections along with their URLs:
git remote –v

git fetch allows users to fetch all objects from the remote repository that don’t currently reside in the local working directory.
git fetch origin


