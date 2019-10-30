### Git command





git init # in the current folder and initialized the current folder as working directory

git log

git add ... && git commit -m '...'





git status

git diff

git reflog

git reset --hard HEAD^(HEAD-100; commit id)





![image-20191022132822745](Git command.assets/image-20191022132822745.png)

第一次修改 -> `git add`-> 第二次修改 -> `git add`-> `git commit`



```git
git checkout -- filename 
```

##一种是`readme.txt`自修改后还没有被放到暂存区，现在，撤销修改就回到和版本库一模一样的状态；

## 一种是`readme.txt`已经添加到暂存区后，又作了修改，现在，撤销修改就回到添加到暂存区后的状态。



`git checkout`其实是用版本库里的版本替换工作区的版本，无论工作区是修改还是删除，都可以“一键还原”。



git rm file

git commit -m 'comment'

