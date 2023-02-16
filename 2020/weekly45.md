---
title: 攻城狮周刊：第45期
comments: false
categories:
  - weekly
tags:
  - weekly
keywords:
  - Newsletter
date: 2020-05-31 15:16:59
---



这里记录过去一周，我看到的值得分享的东西。
<!--more-->




# 教程

## 1. [](https://www.nginx.com/blog/help-the-world-by-healing-your-nginx-configuration/)
NGINX 官方的博客文章，教大家五个小技巧，通过改进配置来节省带宽、提高性能。
# 工具

## 1. [Consul-template](https://github.com/hashicorp/consul-template)

Consul template 是 Consul 周边的一个配置渲染的工具，和 confd 类似，可以从 Consul 的 kv 存储里读取数据，渲染成各种格式的文件来让 Prometheus、Nginx等等工具来读取。使用的文档可以参考：
https://www.bookstack.cn/read/consul-guide/11_consul_template.md#使用
## 2. [Confd](https://github.com/kelseyhightower/confd)
Confd 是一个使用模板来管理本地应用配置文件，可以从 consul 和 etcd 读取数据，和 consul-template 类似，使用模板渲染好配置文件后，也可以通过命令来重启或重载应用，使配置文件生效。但是该项目在 2018 年 7 月 16 日以后就没有新的代码提交。当前最新的版本是 v0.16.0 ，发布于 2018 年 5 月 5 日。

## 3. [Gossip](https://pearmini.gitee.io/gossip/)
一个制作幻灯片的在线工具，只需要少量拖拽和对齐操作，就可以生成通过浏览器播放的幻灯片,比较炫酷。
## 4. [javaagent](https://github.com/dingjs/javaagent)
基于javaagent开发的APM工具，收集方法的执行次数和执行时间，定时输出成json格式的日志。
# 资源

## 1. [阿里云藏经阁](https://developer.aliyun.com/topic/ebook)
阿里云开发者社区——藏经阁系列电子书，汇聚了一线大厂的技术沉淀精华，爆款不断。
======================
由于无法及时收到评论内容，所以关闭评论功能。
大家有问题欢迎发邮件到 erdong@mail.erdong.site ，或者 https://github.com/erdong/erdong.github.io/issues 提 Issue ，我会及时回复>。
======================
Erdong, A Linux user !

