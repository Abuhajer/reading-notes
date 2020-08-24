# Version Control 
is a system that allows you to revisit various versions of a file or set of files by recording changes.

## There are type of version control

1. Local Version Control
2. Centralized Version Control
3. Distributed Version Control

# what is Git?
Git is a DVCS that stores data in a file system made up of snapshots, so its tracking changes, and keep you from loss data ,all that done localy
HISTORY OF GIT
GETTING STARTED

## How to download Git?
In order to use Git, your computer must have it available. If you already have Git on your computer, you should make sure you have the latest version.

Git can be installed in three ways:

1. Install as a package
2. Install via another installer
3. Download and compile the source code.

and u can found it in lunix,mac and windows

after download we need to set git config as Identity Setting
so in treminal we do like that 
git config --global user.name "Jane Smith"

git config --global user.email "example@email.com"
---------------------
## Text Editor 
in default Git will use the system’s default editor–most likely Vim
and third-party tools like code editors
and we can check the setting anytime using 
git config --list 
and if need help u can use
git command --help

So now you think how i will get my github project to my computer !?
its by using cloning,in easy way u just need to do that in your ubuntu treminal 
#### git clone https://github.com/test
 https://github.com/test (this is url of your project)
 
 after that you start working in yout project on your local devices but thier are Workflow for that called ACP
 
 But u need to know ##Local Repository Structure##
The local Git repository has three components:

1. Working Directory: The actual files reside here.
2. Index: The area used for staging
3. Head: Points to the most recent commit

# What ACP ?
ACP its Add,commit and push method 
so after we make the files or make our change to our project
we need to save change and back it to host with the new vesion

so first step its to add the changes to our local by using 
git add *
and we can see the changes using 
git status
so after that we need to save the vesion with a commen in out local and to make it ready to go to the host so we use
git commit -m “made change x,y,z”
and finaly we pushed to host and will ask about the github username and password using 
git push origin master 


# Stashing Changes
When you are **not ready to commit** changes but do not want to lose them either, **git stash** is a great option.
This command temporarily removes changes and hides them, giving you a clean working directory. When you are ready to continue working on the changes, simply use the git stash apply command to retrieve the hidden changes.

# Remote Repositories
In order to collaborate on Git projects, you must interact with remote repositories, versions of a project residing online or on a network. You can work with multiple repositories, for which you can have read/write or read-only privileges. Teams can use remote repositories to push information to and pull data from.

# Cloned Repositories
As mentioned earlier, for cloned repositories, Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local branch.
