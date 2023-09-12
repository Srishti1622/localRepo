Learned how to push existing project folder into github.<br>
Step 1: new that project folder in vs code using mkdir <folder-name>
Step 2: go inside to that folder using cd <folder-name>
Step 3: use command "ls -Hidden" to check .git if it's present means that is present in github also else not
Step 4: now initiate the process of add that folder to github using "git init"
Step 5: check the status of folder using "git status"
Step 6: to add the folder use command "git add <file-name>" or "git add ." to add all files in the folder in one go.
Step 7: commit the changes using "git commit -m 'write message'"
Step 8: to add the folder to git first make one repo in github and then use that repo link in the command "git remote add origin <link>"
Step 9: to verify remote use command "git remote -v"
Step 10: to check branch use command "git branch"
Step 11: to rename the branch name use command "git branch -M <new-name>
Step 12: to push the changes to github use command "git push origin main" here if we know like we are going to push the changes again and again to same branch the we can use the command "git push -u origin main" here -u is basically we are providing a flag to set upstream then after this we can only use "git push" command to puch the changes.
