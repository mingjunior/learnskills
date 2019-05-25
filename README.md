gitskills
===

git command

basic
---

commond|meaning|example
-|-|-
`git init`|初始化仓库
`git status`|查看仓库状态

branch
---

commond|meaning|example
-|-|-
`git branch`|查看分支
`git branch <name>`|创建分支
`git checkout <name>`|切换分支
`git checkout -b <name>`|创建+切换分支
`git merge <name>`|合并某分支到当前分支
`git branch -d <name>`|删除分支
`git log --graph --pretty=oneline --abbrev-commit`|查看分支合并情况
`git merge --no-ff -m "merge with no-ff" dev`|强制禁用Fast forward模式，Git就会在merge时生成一个新的commit，这样，从分支历史上就可以看出分支信息
