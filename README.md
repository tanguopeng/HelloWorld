操作说明：
1.克隆远程库到本地(需要输入用户/密码，如果执行失败，可以再执行一次)
git clone https://github.com/tanguopeng/HelloWorld

2.查看当前状态
git status

3.使用vscode创建一个文件test.py

4.查看当前状态
git status

5.添加到本地暂存区
git add test.py

6.提交到本地库
git commit -m '第一次提交'

7.更新到远程库（可能需要输入密码）
git push

也可以修改 .git目录下的 config文件为
[remote"origin"]

    url = https://用户名:密码@github.com/用户名/仓库名.git