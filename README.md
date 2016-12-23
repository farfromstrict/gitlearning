# Git
#### 学习笔记

<br/>
## 创建本地库

1. 空白 clone
    1. git clone https://github.com/farfromstrict/gitlearning.git
2. 本地已有文件 (1)
    1. git clone --no-checkout https://github.com/farfromstrict/gitlearning.git tmp
    2. mv tmp/.git some_dir_with_files
    3. cd some_dir_with_files
    4. git pull
    5. rm -rf tmp/
3. 本地已有文件 (2)
	1. cd some_dir_with_files
    2. git init
    3. git remote add origin https://github.com/farfromstrict/gitlearning.git
    4. git pull origin master

<br/>
## 全局配置

- git config --global --list ```显示全局配置```
- git config --global user.name "xxx"
- git config --global user.email "xxx@yyy.com"
- git config --global color.ui "auto" ```彩色显示```
- git config --global alias.ci "commit" ```别名```

<br/>
## 信息查询

- git help
	- git help *cmd*
- git remote
	- git remote ```远端名```
	- git remote -v ```远端名&地址```
- git branch
	- git branch -a ```全部分支```
	- git branch -r ```远端分支```
	- git branch -vv ```分支跟踪关系&提交状态```
- git status
	- git status -s ```简短模式```
- git log
- git ls-remote
- git ls-files
- git ls-tree
- git cat-file

<br/>
## 跟踪文件



<br/>
