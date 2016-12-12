---
title: git与github二三事
tags:
  - git & github
  - 持续更新
categories:
  - 项目开发
  - 版本管理
date: 2016-12-05 11:39:35
photo: 
images: http://i1.piimg.com/567571/568c17e5fde390f1.jpg

---
## 摘要
&ensp;&ensp;&ensp;&ensp;git是一张弓，github是靶子，你的源代码是箭（来自[Jacob Peng](https://www.zhihu.com/people/jacobpeng/answers)）。程序员对版本管理都不陌生，它可以用来记录项目的修改，项目成员之间的沟通和交流。
&ensp;&ensp;&ensp;&ensp;github是一个基于git的开源项目托管平台,它提供了web界面,你可以在上面创建资源仓库来存放你的项目，并用git在本地进行远程管理。
<!--more-->

<!-- HTML方式: 直接在 Markdown 文件中编写 HTML 来调用 -->
<!-- 其中 class="full-image" 是必须的 -->
<!--<a href="http://img.hb.aicdn.com/2495276fbb11a92d56901a0766fb3b53f154b5041c889c-IwBZY3_fw658" target="_blank">
<img src="http://img.hb.aicdn.com/2495276fbb11a92d56901a0766fb3b53f154b5041c889c-IwBZY3_fw658" class="full-image"/>
</a>-->

## 常用的git操作

### git连接github

```bash
$ ssh -T git@github.com
```
### 本地克隆repository

```bash
$ git clone [目标仓库链接地址]
```
### 代码提交

```bash
$ git add [.或file]
$ git commit -m "提交信息"
$ git pull [目标仓库链接地址]
$ git push [目标仓库链接地址]
```