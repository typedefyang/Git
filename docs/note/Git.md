# GIT 常用

- git init 初始化仓库

- git status 查看文件夹信息
- git add <filename> 单个文件存入暂存区
- git add . 全部文件加入暂存区
- git commit -m <message> 提交加描述
- git log 查看日志


!> 首次新建的文件都是untracked状态（未跟踪），此时需要git add到暂存区，Git便会在暂存区中生成一个该文件的索引，文件此时处于uncommited状态，需要git commit生成版本库。