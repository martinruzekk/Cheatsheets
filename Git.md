# Git Cheatsheet

### Basic Commands

* $ git init
  * Initilize Local Git Repo
* $ git add \<file\>
  * Add file(s) to Index
  * git add .
    * Přidá všechny soubory
  * git add *.html
    * Adds all html files
* $ git status
  * Check status of working tree
* $ git commit
  * Commit changes in local repo
  * $ git commit -m 'what changed since last time'
* $ git push
  * Push to remote repo (GitHub)
* $ git pull
  * pull latest form remote repo
* $ git clone
  * Clone repo into a new directory
* $ git remote
  * shows list of all remote repos
  * copy this from GitHub

### Branches

* $ git branch \<name\>
  * Creates new branch
  * $ git checkout \<name\>
    * Redirects to different branch
  * $ git merge \<name of other branch\>
    * merges two branches together 