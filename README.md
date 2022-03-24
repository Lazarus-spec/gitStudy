# gitStudy
git 学习

### 本地库
 ll -la 查看隐藏文件 <br>
 
### 设置项目级别
git config user.name <br>
git config user.email <br>
全局：git config --global

### key token
 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

### 如何关联github的sshkey链接
https://blog.csdn.net/weixin_44151974/article/details/106467579

### 历史版本
git reflog 查看版本（简略） <br>
git log 查看详细版本号 <br>
#### 版本穿梭 
回退到目标版本： <br>
git reset --hard 版本号 <br>
往前穿越同上，把指针指到目标版本即可

### 分支
查看分支 git branch -v <br>
创建分支 git branch branchName <br>
切换分支  git checkout branchName <br>
合并分支 git merge branchName <br>

### 创建远程仓库别名
查看当前远程别名 git remote -v <br>
创建别名 git remote add alias gitAddress <br>
本地推送到远程仓库 git push alias master <br>