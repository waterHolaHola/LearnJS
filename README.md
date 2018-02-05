# LearnJS
学习js实践项目
使用git创建分支很容易
已经创建了分支，并在分支上做了修改
conflict_1 分支修改了
master 分支也做了修改，并提交了
两者合并产生了冲突，应该如何解决呢？

创建issue分支，并在该分支上修改了，使用普通合并，看看git log --graph后会出现什么?

stash 是什么？stash是现在工作区未提交到暂存区改变的快照，将工作区恢复到和分支一样并隐藏起来。
等修复了其余的问题，可以使用git stash list查看有些保存起来的快照。
可以使用git stash pop恢复最近的快照或者使用 git stash apply恢复，但是恢复后，stash内容并不删除，你需要用git stash drop来删除

---这是主线的修改
这里有个bug
---这是testStash的修改
第二次测试stash

创建一个dev分支，并推送到gitHub
修改dev分支上的内容


在本地修改了文件，是否会发生冲突