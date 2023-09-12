Learned how to push existing project folder into github.<br>
Step 1: new that project folder in vs code using mkdir folder-name or if the repo is already there in github then we need to clone it using command "git clone link-of-repo"<br>
Step 2: go inside to that folder using cd folder-name<br>
Step 3: use command "ls -Hidden" to check .git if it's present means that is present in github also else not<br>
Step 4: now initiate the process of add that folder to github using "git init"<br>
Step 5: check the status of folder using "git status"<br>
Step 6: to add the folder use command "git add file-name" or "git add ." to add all files in the folder in one go.<br>
Step 7: commit the changes using "git commit -m 'write message'"<br>
Step 8: to add the folder to git first make one repo in github and then use that repo link in the command "git remote add origin link-of-repo"<br>
Step 9: to verify remote use command "git remote -v"<br>
Step 10: to check branch use command "git branch"<br>
Step 11: to rename the branch name use command "git branch -M new-name<br>
Step 12: to push the changes to github use command "git push origin main" here if we know like we are going to push the changes again and again to same branch the we can use the command "git push -u origin main" here -u is basically we are providing a flag to set upstream then after this we can only use "git push" command to puch the changes.<br>


Commands for branch:
1: git branch (to check branch)
2: git branch -M new-name (to rename branch)
3: git checkout branch-name (to navigate to mentioned branch name)
4: git checkout -b new-branch-name (to create new branch with mentioned new-branch-name)
5: git branch -d branch-name (to delete mentioned name branch) here we can't delete the branch in which we are currently so if we want to do so then first we have to go to some other branch

Merge two branch:
1: git diff branch-name (to compare commits, branches, files and more, here it will compare mentioned branch-name with current branch in which we are)
2: git merge branch-name (to merge two branches i.e., mentioned branch-name and current branch)
one more way is there that is : create a PR (pull request- it lets you tell others about changes you have pushed to a branch in a repository on github)

Pull command:
git pull origin main - used to fetch and download content from a remote repo and immediately update the local repo to match that content.