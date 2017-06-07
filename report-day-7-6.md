# Daily report about Git
7/6/2017
## Introduce Git

> Git is a code manage system use manage and control open souce versions in developve souce. 

## Git basic
- **New repository**: make a 
- **Git clone**:Clone a repository into a new directory
- **Git add**: Add file contents 

	>`git add develop.txt`
	
- **Git commit**: Stores the current contents in a new commit along with a message about change
	>`git commit -m "Change text file to develop.txt"`
- **Git push**:  push file from local to sever
	>`git push  -u origin master`
- **Git pull**:  Fetch from and integrate with another repository or a local branch

	>`git pull master `
	- pull files from sever to local
- **Git checkout**: change branch 
	>` git checkout FeatureA`
	- Change from present branch to FeatureA

- **Git checkout -b **: new branch
	> `git checkout -b FeatureB `
	-   make a new branch is FeatureB
- **Git status **: Show the working status
	>`git status`
- **Git log** Show commit logs

    > `git log`

- **Pull request**: 
## Git advance
- **Git  merge**:  Join two or more development histories together
	
	- s1: git check out master
	- s2: git pull origin master
	- s3: git checkout  feature B
	- s4: 
			- git merge master: create a last commit merge from branch master  to recently branch. Commits sorted by time.
			- git rebase master:  not create merge commit, commit of master sorted before


- **git fetch** : take branchs from serve to local
>`git fetch`

