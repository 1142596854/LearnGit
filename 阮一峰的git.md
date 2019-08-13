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



#### 使用gitlog打印修改过的流程

![1565710752472](C:\Users\20201\AppData\Roaming\Typora\typora-user-images\1565710752472.png)

####  使用git log --pretty==oneline 可以只打印前面的版本号

![1565710871011](C:\Users\20201\AppData\Roaming\Typora\typora-user-images\1565710871011.png)

####  使用 git reset --hard HEARD^回退到上个版本

有几个^就回退几个版本

#### 使用 git reset --hard （commit id）回退到指定版本

#### 使用 git reflog来查看历史记录

