
Exp1 This line is locally committed using Git add and Commit exp1
```
git add README.md
git commit -m "expermient 1"
```
 
## Exp2 we created new branch and switched
```
git branch basicstructures
git checkout basicstructures
```
above lines are typed inside this branch and committed using git add and commit
 
now switch to master and merge exp2 ends  
## exp6 is same as exp2 only addition is Merge with message
```
git merge basicstructures -m "merge with messgae"
```
 
## Exp5 Git Push and Git Pull
Confirm upstream and push
```
git branch -vv
git push    
```
Suppose this line and below few lines are the work done by another employee say Ravi
now this work can be pulled to local machine using below command
```
git pull
```
 
## Exp7
Suppose now we have decided to release our product
now we can give tag to our latest commit a tag say version ver1.0 or release1.0
first to see list of all commits use
```
git log --oneline
```
Now to give tag to the latest commit,which will be in the top of the list use
```
git tag version1.0
```
 
## Exp9
To see details of commit with ID version 1.0 use
```
git show version1.0
```
 
## EXp 10
To See the commits made by author between two dates use
```
git log --oneline --author=ShivaMaradi
```
 
## Exp 11
To see the last 5 commits use
```
git log --oneline -n 5
```
 
## Exp 12
you already know we use git add and commit to save our modification
To revert the latest commit use git revert
step1 do another commit
```
git add README.MD  
git commit -m "Exp 12"
git revert
```
 
