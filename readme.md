git init  
git status  
git commit -m "some commit message"  
git log  
git lg  
git add  
git diff some_file       (diffs vs what's been committed)  

Contents of ~/.gitconfig
```
[alias]
	lg = log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit
[diff]
	tool = vimdiff
[core]
	excludesfile = /Users/dol4/.gitignore
[user]
	email = davidlignell@byu.edu
	name = David Lignell
[init]
	defaultBranch = master

```
