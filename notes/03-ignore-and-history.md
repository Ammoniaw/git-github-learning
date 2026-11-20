# 第 3 课：忽略和历史

## 提交历史查看练习

1. `git log --oneline -5` 

   > 最近5条的提交历史记录，最新的一次提交(提交.gitignore文件)添加了忽略规则。

2. `git show --stat 47955b1`

   > 第2课的第1次提交涉及 02-staging-area.md

3. `git diff 47955b1 48a0c6c -- notes/02-staging-area.md`

   > 只看第 2 课笔记，从第一次到第二次提交新增了剩下的笔记内容

---

## 新增忽略规则

1. 新建了“example01.txt”,使用`git check-ignore -v ./example01.txt`验证规则

   > .gitignore:1:/scratch/  ./example01.txt

