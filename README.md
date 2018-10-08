Try-git： git bash under a folder containing SVM.pdf
===================

### 1. First establish on local.
----------
`git init`

`git add SVM.pdf (your file)`

`git config --global user.email "youremail@expample.com"`

`git config --global uer.name "your name"`

`git commit -m "first commit"`

`git remote add origin https://github.com/CrazyStoneonRoad/try-git.git`

`git push -u origin master`

### 2. If changes made on local.
---------
`git pull --rebase origin master`

注意：上面这一步很重要，要一直重复，直到看到 Current branch master is already up to date.

`git add ...`

`git commit ...`

`git push -u origin master`
