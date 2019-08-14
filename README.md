# Branching
Git branch practice

1. create a branch : </br>
``` git checkout -b <branchName> ``` 

2. move to another branch </br>
``` git checkout <branchName> ``` 

3. pull update from branch </br>
``` git pull origin <branchName> ```

4. push a branch into host </br>
``` git push origin <branchName> ```

5. merge a branch </br>
go to the branch where you want to merge then enter bellow command </br>
``` git merge <branchName> ```

6. delete a branch(local) </br>
``` git branch -d <branchName> ```

7. delete branch from remote </br> 
``` 
git push origin --delete <branch>  # Git version 1.7.0 or newer
git push origin :<branch>          # Git versions older than 1.7.0
```

# Commit 
1. Show log </br>
``` git log ```

2. Show a commit </br>
``` git show <commit_id> ``` 

3. Show a commit like log </br>
``` git show <commit_id> --no-patch ```

4. Show only commit message log </br>
``` git log --pretty=oneline --abbrev-commit ```

