

**Merge** is the common approach to resolve conflictive branches where the local branch merges all the new features to the next commit of the remote branch

**Rebase** updates the local branch with the updates from the remote branch

```
git config pull.rebase false  # merge
git config pull.rebase true   # rebase
git config pull.ff only       # fast-forward only
```



