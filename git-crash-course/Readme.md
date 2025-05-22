## Git 

To initialize the git we should use the command below,

```sh
git init
```

## Cloning
    We have three ways to clone the Repo namely HTTPS, SSH, GitHub CLI

Since we are using the Codespaces we will create a temp directory in our workspace

``` sh
mkdir workspaces/temp
cd workspaces/temp
```


```sh
git clone https://github.com/SK-Codespace/GitHub_Examples.git
```

## HTTPS

## Commit

## Merge

## Branches

## Remotes

## Stashing

```sh
git stash # To move all uncommitted changes to stash

git stash save message # Add custom name to stash for identification

git stash pop # Move the all file to developement area and remove it from stash

git stash pop [index] # Move specific stash to developement area and remove only the file from stash

git stash show diff # Show the diffence in stash change and current change of working repo

git stash apply # Move the all file to developement area and retain the file in stash area

git stash apply [index] # Move the specific file to developement area and retain the file in stash area

git stash list # List all the existing stash

git stash branch branch_name [index] # create new branch from specific stash

git stash drop # Remove the recent stash 

git stash drop stash # Remove the most recent stash using identifier

git stash clear # clear all the stash from the list 

```
