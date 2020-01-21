# portfolio

Git Commmands to remember:

git status: this will tell you the status of your local repo
git add <file>: this will allow you to add files to be staged to be committed - note: you can use git add . to add all modified files
git commit -m:  commit your changed files to your local repo that will eventually allow you to push to your remote repo. -m stands for message. Remmber to wrap your message in quatations ""

git push:  allows you to push your commits to remote repo

git fetch: allows you to view/grab commits/changes on your remote repo

git pull: allows you to pull those changes to your local repo to be up to date locally

Note: use git status often to get a sense of where your are in your local repo and in relation to your remote repo

git track: --- will explore later

Lesson 1:

Marcel, remember that you need to VS code to make changes to your files/code and Git Bash to interact with your local and remote repository via git commands.

Challenge: create a local develop branch

1. go to Git Bash and run this command => git branch

git branch: shows you a list of all of your local branches (including) master. It will also show your what branch you are on. You will notice this because it will likely be typed in green with an asterik (*) by it

2. create a new local branch named develop based on your master branch and "checkout" that branch => git checkout -b develop

git checkout <branch name>: allows you to switch to the branch you specify
git checkout -b <new branch name>: allows you to (1) create a new branch based on the branch you are currently on (2) switch to that new branch

note: you can always run git branch in order to see what branch you are on
