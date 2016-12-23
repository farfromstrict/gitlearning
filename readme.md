# Git
#### 学习笔记

<br/>
## 创建本地库

- 空白 clone
    1. git clone https://github.com/farfromstrict/gitlearning.git
- 本地已有文件 (1)
    1. git clone --no-checkout https://github.com/farfromstrict/gitlearning.git tmp
    2. mv tmp/.git some_dir_with_files
    3. cd some_dir_with_files
    4. git pull
    5. rm -rf tmp/
- 本地已有文件 (2)
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
- git config --global credential.helper cache ```缓存密码(默认15分钟)```

<br/>
## 信息查询

- git help
	- git help *cmd*
- git remote
	- git remote ```远端名```
	- git remote -v ```远端名&地址```
	- git remote rm origin
	- git remote add origin git@github.com:farfromstrict/gitlearning.git
	- git remote set-url origin git@github.com:farfromstrict/gitlearning.git
- git branch
	- git branch -a ```全部分支```
	- git branch -r ```远端分支```
	- git branch -vv ```分支跟踪关系&提交状态```
- git status
	- git status -s ```简短模式```
- git log
	- git log --pretty=oneline
	- git log --oneline
- git ls-remote
- git ls-files
- git ls-tree
- git cat-file

<br/>
## 跟踪文件
git branch1


<br/>
