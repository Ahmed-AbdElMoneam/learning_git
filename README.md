# learning_git
Repo for learning how to use GitHub
![local-remote](https://user-images.githubusercontent.com/68257208/201480039-bc5f8948-8911-4227-ac00-e11ff84699de.png)

## git status
To chech status and untracked files or edits

## git add *
To add all of your changes to staging area

# Look there

## git reset head (fileName).(with extension)
To unstage a file from staging Area

## git restore --staged (fileName).(with extension)
To unstage a file from staging Area

## git restore --staged *
To unstage all files from staging Area

## git commit -m "(commitDescription)"
To make a commit

## git branch
To list all the branches in the project

## git remote -v
To know the remote name to  be used in push

## git push (remoteName) (branchName)
### Ex: git push origin master
To push your commits

## git pull (remoteRepo or remoteName)
### Ex: git pull origin
To pull all files or changes from the remote

## git config -l
To show all configs in our config

## git help config
To show documentation of config

## git config --global (configName)
### Ex: git config --global user.email
To get the value of one of the configs

## git config --global (configName) "(The value)"
### Ex: git config --global user.email "ali@gmail.com"
To set the value of one of the configs

## git config -l --show-origin
To show the origin of the configs

## git config --global --unset (configName)
### Ex: git config --global --unset user.name
To remove a value from a config

## git config --global --edit
To edit the configs in the editor

# May this video about Generate And Test Github Public Key be useful
https://youtu.be/KhYK0cczeSY

## git init 
To initialize a repo

## Adding locally hosted code to GitHub
```
git init
git add *
git commit -m "(commitDescription)"
git remote add origin (URL of the repo)
git push -u origin master
```
### -u tells the git to do pull first then do push

# Pull Requests Video
https://youtu.be/n43bagVuJPU

## git config --global alias.(wantedName) (realName)
### Ex: git config --global alias.st status
To set the alias for the command --> git status
### To use that alias --> git st

## git config --global alias.(wantedName)
### git config --global alias.st
To get the real name of an aliased command

## git branch (branchName)
To create a branch

## git checkout (branchName)
To switch to that branch

## git branch -d (branchName)
To delete that branch

## git checkout -b (branchName)
To create and switch to that branch

## git branch -m (branchName)
To rename the current branch to that new name

## git merge (branchName)
### Ex: git merge development
To merge that development branch to the current branch (master for example)

## git stash
To save my edits and files(that's in the staging area) to the stash

## git stash pop
To restore the last stash done that contains my files and edits which was hidden or saved for a future usage. 
Now that stash isn't in the stash list

## git stash apply
To restore the last stash done that contains my files and edits which was hidden or saved for a future usage. 
Now that stash is in the stash list

## git stash list
To list all my stashes

## git stash save "(message)"
To save your files and edits with a message or a title

## git stash pop stash@{(idOfStash)}
To pop a specific stash with its id

## git stash drop
To delete the last added stash

## git stash drop stash@{(idOfStash)}
To delete a specific stash with its id

## git stash show
To show contents of stash

## git stash show stash@{(idOfStash)}
To show contents of stash

## git stash clear
To delete alllllllllll the staches

## git clean -n
To show files you are about to delete

## git clean -f
To delete these files you have seen with the previous command



