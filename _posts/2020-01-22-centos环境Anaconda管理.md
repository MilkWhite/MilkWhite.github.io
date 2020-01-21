---
layout:     post                    # 使用的布局（不需要改）
title:      centos环境Anaconda管理  	    # 标题 
subtitle:   安装、卸载与环境管理 		# 副标题
date:       2020-01-22              # 时间
author:     MilkWhite               # 作者
header-img: img/post-bg-learn.jfif    	# 这篇文章标题背景图片
catalog: true                       # 是否归档
tags:                               #标签
    - Anaconda
---
# Anaconda安装
[Linux-Centos7下安装Anaconda（2019年新版）](https://zhuanlan.zhihu.com/p/64930395)
# Anaconda卸载
[Uninstalling Anaconda](https://docs.anaconda.com/anaconda/install/uninstall/)

# Anaconda环境管理
## 创建环境
`conda create -n py36 python=3.6 `

## 删除环境
`conda remove -n py36 --all`

## 激活环境
`conda activate py36`

## 退出环境
`conda deactivate`

# 清华镜像
[清华镜像使用帮助](https://mirror.tuna.tsinghua.edu.cn/help/anaconda/)