# 第 7 课：远程仓库

- 记录状态1 - `git fetch origin`

  > From https://github.com/Ammoniaw/git-github-learning
  >    3bfd9d0..b912e7a  main       -> origin/main

- 记录状态2 - `git merge --ff-only origin/main` 

  - ```bash
    Fast-forward
     README.md           | 3 ++-
     notes/07-remotes.md | 0
     2 files changed, 2 insertions(+), 1 deletion(-)
     create mode 100644 notes/07-remotes.md
    ```

    

- 为什么`fetch`已经让你能看到新提交，原仓库的工作区里却还没有第 7 课笔记？

  > 因为`fetch`只是更新状态，但是并不是直接更改本地的文件内容，因此还没有新的笔记出现
