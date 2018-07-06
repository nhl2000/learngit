1.git config --global user.name "nhl2000"
  git config --global user.email "nhl2000@126.com"
2.pwd //查看目录
3.git init //添加git版本控制
4.git add readme.txt
5.git status
6.git commit -m '修改说明'
7.git diff readme.txt
8.git log --pretty=oneline
9.git reset --hard HEAD^ //版本前进 回退 HEAD为当前版本
10.git reflog //查看操作日志
11.git checkout -- readme.txt //让这个文件回到最近一次git commit或git add时的状态。
12.git reset HEAD readme.txt //可以把暂存区的修改撤销掉（unstage），重新放回工作区
13.git rm readme.txt //用于删除一个文件

14.ssh-keygen -t rsa -C "youremail@example.com" //创建远程ssh
15.git remote add origin https://github.com/nhl2000/learngit.git
15.git remote add origin git@github.com:nhl2000/learngit.git
16.git push -u origin master
17.git push origin master

18.git clone git@github.com:nhl2000/learngit.git

19.git branch //命令会列出所有分支，当前分支前面会标一个*号。
19.git branch dev //创建dev分支
20.git checkout dev //切换分支到dev
20.git checkout master //切换分支到master
21.git merge dev //合并 dev 分支
22.git branch -d dev //删除dev分支

23.git log --graph //可以看到分支合并图

24.