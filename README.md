# learning_git
Repo for learning how to use GitHub
![local-remote](https://user-images.githubusercontent.com/68257208/201480039-bc5f8948-8911-4227-ac00-e11ff84699de.png)

## git status
To chech status and untracked files or edits

## git add *
To add all of your changes to staging area

## git reset head (fileName).(with extension)
To unstage a file from staging Area

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

