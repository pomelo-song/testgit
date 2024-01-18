### This is a test file

This is a test file for git.

I hope it works.

Thanks!

### 这是一个新的修改提交，看一下github的相关情况
### 测试效果成功



### 本地——》暂存区-》本地仓库-》·远程仓库

### 本地仓库：保存了所有的文件，包括未提交的文件。

暂存区：保存了已提交的文件，但未推送到远程仓库。

远程仓库：保存了所有的文件，包括已提交的文件。  

### 1. 克隆远程仓库到本地

```
git clone https://github.com/username/repository.git
```

### 2. 切换分支

```
git checkout -b dev
```

### 3. 编辑文件

```
vim README.md
```

### 4. 添加文件到暂存区

```
git add README.md
```

### 5. 提交文件

```
git commit -m "add README.md"
```

### 6. 推送文件到远程仓库

```
git push origin dev
```

### 7. 创建pull request

```
git pull-request
```

### 8. 合并pull request

```
git merge dev
```

### 9. 删除分支

```
git branch -d dev
``` 

### 10. 同步远程仓库

```
git fetch origin
```

### 11. 合并远程仓库

```
git merge origin/dev
``` 

### 12. 推送本地仓库到远程仓库

```
git push origin master
``` 

### 13. 克隆远程仓库到本地

```
git clone https://github.com/username/repository.git
``` 

        