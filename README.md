# Branching
Git branch practice

1. create a branch : </br>
``` git checkout <branchName> ``` </br>
if the branch <branchName> is not present then it will create new branch 

2. pull update from branch </br>
``` git pull origin <branchName> ```

3. push a branch into host </br>
``` git push origin <branchName> ```

4. merge a branch </br>
go to the branch where you want to merge then enter bellow command </br>
`` git merge <branchName> ``

5. delete a branch </br>
``` git branch -d <branchName> ```

6. delete branch from host </br> 
`` git push branch :<branchName> ``

# Commit 
1. Show log </br>
`` git log ``

2. Show a commit </br>
`` git show <commit_id> `` 

3. Show a commit like log </br>
`` git show <commit_id> --no-patch `` 
