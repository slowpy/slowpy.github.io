---
layout:     post
title:      Git指令整理
subtitle:   不适合阅读的整理的一些个人常用的 Git 指令
date:       2024-04-15
author:     slowpy
header-img: img/post-bg-ios9-web.jpg
catalog: true
tags:
    - Mac
    - 终端
    - Git
---

>随便整理的一些自用的Git指令


# GitHub创建仓库提示代码

	echo "# 项目名" >> README.md
	git init
	git add README.md
	git commit -m "first commit"
	git remote add origin git@github.com:qiubaiying/项目名.git
	git push -u origin master

若仓库存在直接push

	git remote add origin git@github.com:qiubaiying/test.git
	git push -u origin master


# 常用操作

#### 环境配置
	套件下载地址
	https://docs.partner.android.com/tv/test/tvts/run?hl=zh-cn#install
	dev套件下载地址
	https://ci.android.com/builds/branches/git_master-tv-dev/grid?legacy=1
	

	
#### 其他

	# 压缩包
	$ 