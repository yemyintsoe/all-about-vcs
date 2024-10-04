### DELETING BRANCHS
##### Delete local brach
``` 
git branch -d <brandName>
```

###### For some reason, you have to use -D instead of -d
```
D:\code\static\ooredoo-portal>git branch -d login
error: The branch 'login' is not fully merged.
If you are sure you want to delete it, run 'git branch -D login'.

D:\code\static\ooredoo-portal>git branch -D login
Deleted branch login (was 611f9f0).
```

##### Delete remote branch
``` 
git push -d origin <branchName>
```

### CHANGE REMOTE URL
##### Check remote url
``` 
git remote -v
```

##### Change URL
```
git remote set-url origin https://github.com/yemyintsoe/repository-1.git
```


Ref: https://kodekloud.com/blog/change-remote-origin-in-git/
