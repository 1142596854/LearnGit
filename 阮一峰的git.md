# 初始化仓库

使用git init

# 添加文件到git仓库

#### 1、 使用命令`git add <file>`，注意，可反复多次使用，添加多个文件

#### 2、使用命令  git commit -m<修改了哪些内容>,完成

```
$ git commit -m "wrote a readme file"
[master (root-commit) eaadf4e] wrote a readme file
 1 file changed, 2 insertions(+)
 create mode 100644 readme.txt
```

#### `git commit`命令执行成功后会告诉你，`1 file changed`：1个文件被改动（我们新添加的readme.txt文件）；`2 insertions`：插入了两行内容（readme.txt有两行内容）。

# 版本回退



