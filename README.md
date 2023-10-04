```
本地仓库的代码上传到github远程仓库

打开Git Bash 进入要上传的该路径

git init

git add .

git commit -m “xxf”

git remote add origin git@github.com:xxf185/xxxxx.git

git push -u origin master

解决git报错：

git config --global --unset http.proxy 

git config --global --unset https.proxy

查看代理命令

git config --global --get http.proxy 

git config --global --get https.proxy

------------------------------------------------------------------------------------

------------------------------------------------------------------------------------

删除Github中的文件（夹）

1.首先将该仓库克隆到本地

git clone git@github.com:xxf185/xxxxx.git

2.打开 Git Bash，查看当前目录下文件

ls

3.进入到本地仓库

cd xxxxx

4.删除指定定文件

git rm 要删除的文件名

git rm -r 要删除的文件夹名

git push origin --delete 要删除的分支名

5.提交操作说明

git commit -m 'xxf'

6.将本次更改更新到github项目上去

git push
```
