## git本地工作原理

对于任何一个文件，在git内部存在三种区域：**工作区，暂存区和本地仓库**。

工作区表示新增或修改了某个文件，但是还没有提交保存。

暂存区表示已经把新增或修改提交到下次要保存的清单中了。

本地仓库则保存着已经被安全保存的文件。

涉及到的概念包括pull、push、merge、pull request、merge和clone

##### 初始化本地仓库

`pwd`

##### 查看当前所在目录

`git init`

在当前目录下初始化git仓库

hooks目录：脚本文件目录

info目录：保存了不希望在.gitignore文件中管理的忽略模式的全局可执行文件

logs目录：日志目录

objects目录：储存所有的数据内容

refs目录：储存指向数据提交对象的指针

config目录：文件包含了特有的配置选项

Head文件指向当前分支

##### 设置签名信息（只针对当前库）

```
git config user.name <姓名>

git config user.email <邮箱>
```

##### 查看配置中的文件

`cat .git/config`

##### 查看工作区、暂存区状态

`git status`











