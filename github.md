github

1 ssh-keygen -t rsa -C "youremail@example.com"



2 Add ssh key to github



3 creat a repo called learngit



4 git remote add origin git@github.com:Badgerliu/learngit.git

```
git push -u origin master # push origin to master in github
```

把本地库的内容推送到远程，用`git push`命令，实际上是把当前分支`master`推送到远程。

由于远程库是空的，我们第一次推送`master`分支时，加上了`-u`参数，Git不但会把本地的`master`分支内容推送的远程新的`master`分支，还会把本地的`master`分支和远程的`master`分支关联起来，在以后的推送或者拉取时就可以简化命令。