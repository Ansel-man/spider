

## 使用git 来管理本地的代码
## 使用git 来同步代码

<<<<<<< HEAD

# 创建远程仓库 创建本地仓库
- 关联本地仓库和远程仓库
```commandline
git remote add origin git@github.com:han
```

github 支持两种同步方式

 "https" 和 "ssh"
 
https每次提交的时,都需要验证身份

ssh 需要上传公钥
=======
## ssh push code 

.git/config https://github.com/Ansel-man/Algorithm

to 

git@github.com:Ansel-man/Algorithm

# 查看项目分支

```commandline
git branch  // 显示本地所有分支
git branch -r // 显示远程分支
git branch -a // 显示所有分支
```