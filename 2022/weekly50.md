# weekly50


title: 攻城狮周刊：第50期
comments: true
categories:
  - weekly
keywords:
  - Newsletter

这里记录过去一周，我看到的值得分享的东西。



# 工具

## 1. [OpenHPC](https://github.com/openhpc/ohpc)
官网地址： https://openhpc.community

这个站点提供了部署和管理HPC Linux集群所需的各种常见的预构建组件，包括配置工具、资源管理、I/O客户端、运行时、开发工具、容器和各种科学库。

目前有两个发行版系列: 1.3.x 和2.x ,它们针对不同的主要Linux OS发行版。1.3.x 系列的目标是CentOS7和SLES12，而2.x系列瞄准CentOS8和Leap15。

对于 CentOS 7 

```
wget https://github.com/openhpc/ohpc/releases/download/v1.3.GA/ohpc-release-1.3-1.el7.x86_64.rpm
yum install ohpc-release-1.3-1.el7.x86_64.rpm
```
对于 CentOS 8
```
wget http://repos.openhpc.community/OpenHPC/2/CentOS_8/x86_64/ohpc-release-2-1.el8.x86_64.rpm
yum install ohpc-release-2-1.el8.x86_64.rpm
```

安装好这个 OpenHPC 的仓库以后，安装 PBSPro 或者其他的 HPC 组件会非常方便。比如：

```
yum install pbspro-server-ohpc
```

## 2. [PromU](https://github.com/prometheus/promu)

使用介绍文档
https://www.lujianxin.com/x/art/mwuvnoldjj83

## 3. [BLEUnlock](https://github.com/ts1/BLEUnlock)
BLEUnlock 是一个可以通过可通过 iPhone，Apple Watch 或任何其他低功耗蓝牙设备锁定和解锁你的 macOS 系统，且无需下载 iPhone 应用，并适用于任何定期发送信号的BLE设备

## 4. [Prometheus Exporter](https://github.com/prometheus/prometheus/wiki/Default-port-allocations)

最全官方 Prometheus Exporter 列表，这个列表本来是列举 Prometheus Exporter 的端口，端口都有了，Exporter 还会缺少么？比官网集成页面里列举了大约 180+ 的 Exporter, Default-port-allocations 里边列举了接近 1000 个 Exporter 的地址，多太多了。

# 资源

## 1. [Visio Cafe ](http://www.visiocafe.com/index.htm)

一个 Visio 的图库，里边有各种网络设备、服务器的 Visio 图，可以下载以后在 Visio 或者 OmniGraffle Professional  的绘图软件中使用。

## 2. [salaryfly](https://salaryfly.com)

该网站列举了大部分互联网公司的职级和薪酬，便于进行横向对比。很有意思。

## 3. [devops-exercises](https://github.com/bregman-arie/devops-exercises)

运维相关的面试技术问题。

# 教程
## 1.[微软的 Golang 教程](https://docs.microsoft.com/zh-cn/learn/paths/go-first-steps/)




======================
由于无法及时收到评论内容，所以关闭评论功能。
大家有问题欢迎发邮件到 erdong@mail.erdong.site ，或者 https://github.com/erdong/erdong.github.io/issues 提 Issue ，我会及时回复>。
======================
Erdong, A Linux user !
