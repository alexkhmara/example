example
=======

Example repository to show how Git works

What to show
------------


1. git clone
2. Usual work
3. git status
	- stage
	- git add -p
	- git add -e
	- git commit
	- git commit --amend
4. git log
5. Branches
	- create - git checkout -b
	- change branch - git checkout
	- show - git branch
	- push to server
	- get branch from server
	- merge:
		- merge main branch: git fetch origin/master, git merge origin/master
		- merge feature branch to master: git checkout master; git merge feature-branch
	- conflicts:
		- edit files
		- git add
6. Stash
	- git stash save
	- git stash list
	- git stash show
7. workflow:
