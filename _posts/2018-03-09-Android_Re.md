---
comments: true
date: 2018-03-09 17:42:32+00:00
layout: post
title: 重新入门Android开发
categories:
- Works
- Tech
tags: android
author: 夏涵
---

根据[Android官方培训课程中文版(v0.9.7)](http://hukai.me/android-training-course-in-chinese/index.html)的引导系统学习入门Android开发。

这之前我在假期尝试过一些安卓开发，修改了github上一个public通讯录项目，企图做一个记账的app。不过只做出增加查找就搁置了。

现在我参加了一个比赛需要做app，借此机会督促自己系统地学习Android开发。



今天我学习了第一章**建立第一个app**,刚创建就遇到一个bug：

控制台提示：

`Error:com.android.tools.aapt2.Aapt2Exception: AAPT2 error: check logs for details`

[解决方法](https://teamtreehouse.com/community/errorcomandroidtoolsaapt2aapt2exception-aapt2-error-check-logs-for-details)是：

在***gradle.properties***文件中添加一下一行设置:

`android.enableAapt2=false`

这样项目就成功创建了

接着我翻出来了我尘封一年的电信入网送的Android手机，密码忘了，还好能指纹解锁。



上学期为了跑跳一跳的python脚本，已经装好了ADB，假期做东西借爸妈的手机测试的时候也装好了其它东西。



我按教程写好了HelloWord，又接着创建了一个文本框和一个按钮，更改了相关的xml文件和java文件。

xml大概是用来布局app界面的，而创建Activity的时候对应生成的java文件则是处理后端事务的，此外字符串信息单独在strings.xml中配置，如教程所说是为了方便修改和本地化。



后来用intent打开新窗口，转发Message到新窗口时，在新建Activity这一步出现了偏差，我使用的AS版本和教程不一样，没找到Blank Activity，一开始选择了Basic Activity，运行崩溃。

后来查到应该选择Empty Activity,根据教程修改后，+id/content 的content无法在java文件中使用，后来发现是编译器的问题，重启一下就好了。

最后我成功地写出了***My First App***,现在很想记录一下，这时候突然想起了自己看的一些博客和我好朋友的博客，我决定从今天开始用博客记录自己每天的学习和工作，这样以后看起来会很有成就感吧。

我的腾讯云域名解析没有备案被封了，所以我决定在github上创建个人博客。

今天已经做了一些东西了，待会儿要去约会，博客明天再建。

今天的日志就写在本地的markdown文件里吧，说实话我还有点不太熟悉md,但是觉得它用起来很舒服，比word舒服文件名长度相除那么多倍。