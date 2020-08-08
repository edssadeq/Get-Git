# Get-Git
This Repo is for make a friendship relation with github 
# So this is the largest heading
## let's test the second one
### is this one the 3th ?
##### OOOh this is the smallest heading , so fun!!

### It seems that you would like to master Markdown, take a look here
https://guides.github.com/features/mastering-markdown/ - automatic!
[mastering-markdown](https://guides.github.com/features/mastering-markdown/)

#Got Commands
### git clone [link].git
clone repo (from remote ==> local)
### git status
### git add [files]
to add untracked files to staging area
(stage files)
### git restore --staged [file]
unstage file
### git commit -m "message"
send changes to local remote
##-----------------
### git branch
to list all branches (master is the parent branch)
### git remote -v
to list remote
### git push [remoteName] [branchName]
push commited changes to remote repo

##--------v6----------
### git pull [remoteName]
to get changes from Remote Repo


##--------v7----------
### git config -l 
### git config --list
listing my configuration
### git help config
open the manual 
### git --global user.name
### git --global user.email
get configured values for username & user email
### git --global user.name "name"
### git --global user.email "name@exemple.xyz"
set configuration values
### git config -l --show-origin 
listing my configurations and thier sources (where they came from ?)
________________________________________________
| exemple :
|	file:C:/Program Files/Git/etc/gitconfig 
|
|________________________________________________

### git config --global --unset user.name
delete a configuration
### git config --global --edit

##--------v11----------
### git config --global alias.st status
make 'st' a shortcut for status 
[git st === git status]
### git config --global alias.st 
show what 'st' stands for 
### git config --global alias.cm "commit -m"
for commands with spaces
open configuration into an editor 
### git help [commit,config...]
open the manual 
##--------v8----------
create a repo using an existing project

### git init
to inisialize an empty git repo

### git remote add origin _git_@_github._com_/_username_/repo-name_.git
### git push -u origin master

push an existing repository from the command line  
[-u] do pull before push
##--------v12----------
### git branch 
listing all branches in the Repo
### git branch [name]
create a nex branch called name
### git checkout [name]
switch to the branch called name
### git branch -d [name]
safe delete a branch (will not be deleted if there are unmerged changes)
### git branch -D [name]
force deleting a branch (will be deleted whatever)
### git checkout -b dark-mode
Switched to a new branch 'dark-mode' (create + switch)
### git branch -m [new name]
rename the branch we switched into
### git merge [name]
merging branch (name) with the swetched into branch

