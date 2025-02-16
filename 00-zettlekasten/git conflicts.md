***If conflict raises do to a difference between a remote branch update and your local branch when pushing:***

- When in conflict between branches choose the approach to deal with them: [[Git merge-rebase-forward]]
- pull first and merge/rebase/ff
```
git pull origin main
```
- check the status with 
```
git status
```
- open the file and add the changes
```
git add [yourfile]  
```
- then continue the rebase
```
git rebase --continue
```

If you want to see differences between files you can use 
```
git diff [yourfile]
```

If you want to keep or discard some changes that you see in the file pointed out in git diff use respectively
```
git add [yourfile]

git restore [yourfile] 
```

