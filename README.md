# Github Notes
Notes for github


## Windows
To Store credentials
```
git config --global credential.helper wincred
```

##Merging
Tortoisemert works well
git mergetool -t tortoisemerge

Merge config (kdiff3 not as good)
```
[merge]
        tool = kdiff3
[mergetool "kdiff3"]
        path = c:/Program Files/KDiff3/kdiff3.exe
[diff]
        tool = kdiff3
        guitool = kdiff3
[difftool "kdiff3"]
        path = c:/Program Files/KDiff3/kdiff3.exe
```

##Get all override local
```
git fetch --all
git reset --hard origin/master
```
