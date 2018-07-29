# 空文件夹关联远程git仓库步骤
## git remote add origin http://xxxx
## git pull origin master
## 更改文件之后
## git add -A
## git commit -m 'xx'
## git push --set-upstream origin master

# 删除远程master重新push时候
## 执行git push -u origin master -f