# Allenczj.github.io
这里是笔记

第一节课：

Lecture Notes-4.29

github pages

-静态展示页面的服务

通常使用html、markdown文件

需要条件：username.github.io

静态站点建站系统

-octpress (ruby)

-pelican(python)

-hexo (node.js)

安装过程：

-node.js npm(包管理器，相当于python中的pip)

-sudo npm install -g hexo-cli

使用

-初始化：hexo init

-创建：hexo n "标题“

-生成：hexo g

-预览：hexo s

发布到git

-使用hexo一键发布: hexo d

-手动push方式: 将publish目录，git push origin master

Hexo安装：http://ms.zjer.cn/index.php?r=studio/post/view&sid=531&id=2380781

Markdown简明教程：https://github.com/Melo618/Simple-Markdown-Guide


第二节课：

Chocolatey安装与使用 1、安装
最简单的方式是以管理员身份运行cmd，输入：

@powershell -NoProfile -ExecutionPolicy unrestricted -Command "iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin

安装成功的话，输入choco，会显示chocolatey的版本号。

2、使用

安装软件：choco install 软件包名

升级软件：choco upgrade 软件包名

删除软件：choco uninstall 软件包名

考虑到Windows的权限问题，建议用管理员身份运行cmd或者powershell，再运行。

3、可视化操作

建议安装chocolateygui 包，在可视化环境下使用。
