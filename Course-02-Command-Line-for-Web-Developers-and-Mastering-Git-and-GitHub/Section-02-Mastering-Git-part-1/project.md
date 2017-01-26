### Name of a command
A one- or two sentence describing the command

Simple Example:
```
simple code
```
Comp;lex 
```
a more complex code
```
---
### Name of a command
A one- or two sentence describing the command

Simple Example:
```
simple code
```
Comp;lex 
```
a more complex code
```
---
### Git Config
```
The .git/config file in each repository is used to store the configuration for that repository, and $HOME/.gitconfig is used to store a per-user configuration as fallback values for the .git/config file.
```
### git init
```
This command creates an empty Git repository - basically a .git directory with subdirectories for objects , refs/heads , refs/tags , and template files. 
```
### git push
```
 git push "updates remote refs along with associated objects". it takes what is on your system and "pushes" it up to the cloud GUI
```

### git pull
```
opposite of git push, it brings a repository down from the cloud and onto your computer
 git pull runs git fetch with the given parameters and calls git merge to merge the retrieved branch heads into the current branch
```

### git clone
```
Cloning a git repository means that you create a local copy of the code provided by developer. You can simply do it with a command line: git clone git://github.com/moderndeveloper/learn
```
### git status
```
Displays paths that have differences between the index file and the current HEAD commit, paths that have differences between the working tree and the index ...

```
### git commit
```
saves the changes made to the repository on your local server
```
### git reset
```
It essentially undid the last commit you made. When you run git commit , Git will create a new commit and move the branch that HEAD points to up to it. When you reset back to HEAD~ (the parent of HEAD), you are moving the branch back to where it was without changing the Index (staging area) or Working Directory.
```
### git checkout

```
git checkout is to checkout your desired status of your repository (like branches or particular files). E.g., you are currently on master branch and you want to switch into develop branch.
```
### git branch
```
A branch in Git is simply a lightweight movable pointer to one of these commits. The default branch name in Git is master. As you initially make commits, you’re given a master branch that points to the last commit you made. Every time you commit, it moves forward automatically.
```
### git status
```
Displays paths that have differences between the index file and the current HEAD commit, paths that have differences between the working tree and the index 
```
### git merge
```
The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch. ... Again, this means that git merge is often used in conjunction with git checkout for selecting the current branch and git branch -d for deleting the obsolete target branch.
```
### git mv
```
git mv oldname newname. is just shorthand for: mv oldname newname git add newname git rm oldname. i.e. it updates the index for both old and new ...

```
### git rm
```
Remove files from the index, or from the working tree and the index. git rm will not remove a file from just your working directory.
```
### git add
```
 use git add to start tracking new files and also to stage changes to already tracked files, then git status and git diff to see what has been 
```
### git diff
```
Show changes between the working tree and the index or a tree, changes between the index and a tree, changes between two trees, changes between two blob objects, or changes between two files on disk. git diff [--options] [--] [<path>…
```

