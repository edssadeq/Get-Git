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


##--------v13----------
### git stash 
store working directory
### git stash list
list stashes
### git stash pop
retrive stored work from the latest stash and delete it
##--------v14----------
### git stash save "label"
label a stash
### git stash apply 
retrive stored files from the last stash without deleting stash
### git stash pop [stash@{is}]
retrive stored files from a specific stash (and delete the stash)
### git stash drop 
delete the latest stash
### git stash drop [stash@{0}]
drop a specific stash
### git stash show
show stored files in the latest stash
### git stash show[stash@{0}]
show stored files in a specific stash
### git stash clear 
clear all stash and thier contents
### git stash branch <name>
This command creates a new branch with the latest stash,
 and then deletes the latest stash ( like stash pop).
 If you need a particular 
stash you can specify the stash id.
 
 
 ______________________________________
 #Some useful resources :
 [Stash tracks](https://www.freecodecamp.org/news/useful-tricks-you-might-not-know-about-git-stash-e8a9490f0a1a/#:~:text=stash%40%7B1%7D-,Git%20stash%20branch,can%20specify%20the%20stash%20id.&text=This%20will%20be%20useful%20when,latest%20version%20of%20your%20branch.)
 
 [git doc](https://git-scm.com/doc)
 
 [from dev docs](https://devdocs.io/git/)
 
 [Medium Artc](https://medium.com/@caroline.e.okun/a-guide-to-mastering-git-ce91ae05ed03)
 
