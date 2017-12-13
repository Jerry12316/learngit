##Git Tutorial

1. 初始化一个文件夹作为一个Git仓库，在这个文件夹目录下使用：

`git init`

2. 添加文件到git仓库：
```
git add filename

git commit -m "此次操作的描述"
 ```

3. 查看工作区的状态
`
git status`

4. 查看提交历史，确定要退回到哪个版本
`git log`

5. 确定回到未来哪个版本，删错了
`git reflog`

6. 回到某个具体的版本
`git reset --hard 版本号`

7. 当你想放弃对工作区的某个文件的修改时候，可以使用
`git checkout --filename`

8. 当你想放弃对暂存区的某个文件的修改时， 分为两步
```
   git reset HEAD filename

   git checkout --filename
   ```

9. 删除一个文件
`git rm`

10. 提交了本地文件以后，如何上传到远程仓库
`git push origin master`

