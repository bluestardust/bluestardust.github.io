---
layout: post
title: 重新整理Google Blogger
date: 2016-09-24 10:30
author: zhaohao
comments: true
categories: [weblog]
---
整理电脑，又发现了多年前修改的Google Blogger的模板，发现自己仍旧是对极简风格比较钟爱。

稍微整理了一下，改了下引用图片的路径，又将之套在了blogger上。

Blogger上的博文比较乱，尤其是用IFTTT自动转发的文章，由于转发不是即时触发，使得发布时间都是一坨坨的。

强迫症又发作，清理博文，把原来的文章全部删掉，导出Wordpress备份，转换为Blogger的格式，导入到Blogger。

过程中遇到了接二连三的问题，在线转换工具Wordpress2blogger不支持导出大于1M 的文件，意味着要分块转换，此是一坑。

深圳电信连外部VPS的速率让人捉急，导入Blogger时候的超时问题加“人机验证”问题导致多次多次出错，此是二坑。

导入文章时候结果只有部分文章导入成功，有一部分文章缺失，又无错误log可查，此又是坑。只能手工检查缺失时间段，还好都是连续时间段未导入。

因为导入出错多次为求稳妥添添删删，后面又遇到当天导入数量超过限额的问题，过了0点后终于完成最后一块的导入。

终于解决强迫症之所急，完成了清理。现在Wordpress加静态Jekyll加Blogger三个博客系统的存档一致了。