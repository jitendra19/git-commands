# git-commands

git commands:


1. to check current branch:

  -->  git branch

2. to switch branch:

  -->  git checkout <branchName>


3. to stash somthing:

  --> git stash  save "message"

  --> git stash list

  --> git stash apply <stash@{0}>

  --> git stash drop <stash@{0}>

  --> git stash clear

  --> git stash pop


4. create a new feature branch from specific branch(sprint10):

  --> git checkout -b feature/CMTK-642 Sprint11

5. how to reverse commit on git

  --> git reset --hard commit_number

6. delete branches

  --> git branch -d branch_name
  
  --> git branch -D branch_name

7. TO clear changes:

	--> git checkout -- .

8. To create a new Branch

	--> git checkout -b <name_of_your_new_branch>

9. To push the current branch and set the remote as upstream, use

	--> git push --set-upstream origin feature/MCPC_00000

10. to change branch name locally 
	
  --> git branch -m <oldname> <newname>

11. rename current branch name 
	
  --> git branch -m <newname>

12. merge develop to feature branch:
	
  a. goto develop branch and take latest pull
	b. then go to feature branch and put command 
  c. --> git rebase develop

13. delete merged branches expect develop and master
  
  --> git branch --merged | egrep -v "(^\*|master|dev)" | xargs git branch -d

14. How to list all the files in a commit?

  --> git diff-tree --no-commit-id --name-only -r <commit_number>


-----------------------------------------------------------------

Command promt command:

delete a folder : 
- goto path
-type RD /S /Q folderName


