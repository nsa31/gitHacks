# gitHacks
My git tasks collection

## Adding an existing project to GitHub
```
git init
git add .
git commit -m '1st commit'
git remote add origin URL
git remote -v
git push origin master
```


## Delete branch in local
`git branch -d b1`

## Delete remote branch
`git push origin --delete b1`

## Delete local dir
```
git checkout master
git rm -r FolderDir
git commit -m "removed"
git push origin master
```
Remove from git repo but not file sys
```
git rm --cached sth.py
git rm --cached -r dir
git commit -m "removed sth.py and dir"
git push origin master
```



