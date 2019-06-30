# 1. 预装

mkdocs
 
git
 
python

注册一个github账号

# 2. 建立本地仓库

在本地电脑建立文件夹：A；

在终端界面（win+R，输入cmd）进入文件夹A， 

输入命令（有部分系统需在git bash 命令窗输入）：git clone https://liwy2019.github.io/github.io/

在A目录下会生成名字为github.io的文件夹，进入该文件夹。该文件夹即为本地仓库。

# 3. 下载和上传
下载：

git pull * (将github仓库中的内容与本地仓库对比并下载)

也可以直接进入https://github.com/Liwy2019/github.io，点击clone or download 即可

git merge (合并本地仓库的更新内容与github仓库内容合并)

上传：

git add -A 将所有文件添加到版本管理器

git commit -m "message" 提交到本地的版本控制库，“”内为本次提交说明

git push origin master 将命令提交到远程github中，第一次之后的提交只需要git push 即可

登录https://github.com/Liwy2019/github.io可以查看提交的代码了

# 4. 使用（有更简单的使用办法，但小白我木有研究出来）

请将https://github.com/Liwy2019/github.io网页下面所有文件按3中方式下载到A/github.io文件夹下面

进入命名为Websiteori文件夹下进行内容更新（.md文件）

.md文件编辑使用：直接用markdown打开，右边窗口有参考效果图。

![](/Websiteori/picture/mkdown.PNG)

在终端进入Websiteori文件夹，输入：mkdocs serve 会得到一个仅在本机有效地网址，一般为http://127.0.0.1:8000； 本机进入该网页，可以实时看到最新更新结果，建议在本机网页确定修改更新无误（无404）之后再上传到github

![](/Websiteori/picture/mdocsserve.PNG)

在修改.md文件完成之后，在终端输入：mkdocs build； 在Websiteori文件夹下会生成一个名字为site的文件夹，将site文件夹中所有内容复制到github.io文件夹下，按3中方式上传即可。
 


----------






