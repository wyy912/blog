---
title: "使用git lfs之后不能编译的问题"
date: 2022-07-21T00:05:09+08:00
draft: false
---

所有的文章都在告诉你怎么使用git lfs，但是却没有文章告诉你怎么还原git lfs之后的文件

`git lfs pull`

```
git lfs pull:
Fetch Git LFS changes from the remote & checkout any required working tree
files.
```
使用该命令让被git lfs的文件还原到原来的版本，是的能够正常编译
