---
title: 攻城狮周刊：第43期
comments: false
categories:
  - weekly
tags:
  - weekly
keywords:
  - Newsletter
date: 2020-01-12 15:16:59
---



这里记录过去一周，我看到的值得分享的东西。
<!--more-->


# 工具

## 1. [dockerfile_lint](https://github.com/projectatomic/dockerfile_lint)
截止到2019年12月底，社区比较出色的dockerfile扫描工具有：hadolint、dockerlint和红帽推出的dockerfile_lint。总体上来说这三个工具其实都不完善，基本上处于alpha之前的状态。

hadolint是目前为止成熟最高的一个工具，一共支持60多条的自带规则。而且hadolint还支持对Run命令中带的shell命令进行审计。这一点功能是目前其他竞品不具备的。不过hadolint使用Haskell语言编写，且目前不支持规则文件导入。
如果有新的规则需要编程实现。
dockerlint 使用coffee_script语言编写，自带规则数量小于hadolint；也不支持规则文件导入功能。
dockerfile_lint 红帽发布，使用node.js编写的一个dockerfile扫描工具。支持的规则数量小于hadolint，但是支持通过yaml文件方式导入用户自定义规则。

从以上分析来看，我认为dockerfile_lint其实更具潜力，因为dockerfile扫描规则其实是不固定的。每个用户都可以有自己的dockerfile扫描规范，所以通过脚本添加规则其实是一种刚需。 hadolint和dockerlint恰恰不具备这个能力，所以我最终选择了dockerfile_lint作为扫描工具。

======================
Erdong, A Linux user !

