---
layout: post
title:  浅谈MVC架构模式分析与设计
category: MVC
tag: [MVC]
date : 2016-09-01
excerpt: 浅谈MVC架构模式分析与设计
subtitle: "永不放弃"
author: "zhuiyi"
avatar: "img/authors/wferr.png"
image: "img/d.jpg"
---

******


<!-- more -->

MVC全名是Model View Controller ,是模型-视图-控制器的缩写。

```

视图：我们能能直观的看到的web界面。

控制器：向系统发出指令的工具和帮手。

模型：模型的工作是按要求从数据库取出数据。

```

学习MVC的目的：

```

1、快速上手各大主流PHP框架，列如YII框架、thinkphp、ci等

2、快速适应多数公司的web开发需求

3、逐步接触和了解web系统架构的知识、为日后成为系统架构的中坚力量做准备

```

MVC解决的问题：

```
在PHP还不支持面向对象之前，是过程化的方式来创建的，它们将 Model View Controller 三层的代码混在一起，十分混乱。

它解决的问题有：维护难、开发速度慢、二次开发难度高，工作量大

```

MVC的优势：

![MVC_1](/res/img/blog/PHP学习/MVC_1.jpg)

MVC的工作流程初步认识：

```

1、浏览者 -> 调用控制器，对它发出指令
2、控制器 -> 按指令选取一个合适的模型
3、模型 -> 安控制器指令去相应数据
4、控制器 -> 按指令选取相应视图
5、视图 -> 把第三步取到的数据按用户想要的样子显示出来

```

NVC的目录结构：

![MVC_2](/res/img/blog/PHP学习/MVC_2.jpg)