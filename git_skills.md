git init: 初始化git仓库，进行版本管理
git status: 查看当前仓库的状态
git diff: 查看工作区和暂存区的差异
git branch: 查看当前所有分支
git log: 查看提交日志
git reflog: 查看所有分支的提交日志

git add: 将文件添加到暂存区
git restore: 将文件从暂存区恢复到工作区
git commit: 将暂存区的文件提交到仓库
git reset --hard HEAD^: 回退到上一个版本
git reset --hard: 回退到指定版本
git reset --soft: 回退到指定版本，保留工作区和暂存区的差异
git reset --mixed(默认状态): 回退到指定版本，保留工作区的差异

git remote add origin <url>: 添加远程仓库
git remote rm <url>: 删除远程仓库
git remote -v: 查看远程仓库的信息
git push -u origin master: 第一次推送代码到远程仓库
git clone <url>: 克隆远程仓库到本地