---
title: 存储空间
sidebar_position: 8
description: Lightly的项目资源均存储在云端，用户拥有一定的磁盘空间容量。
keywords: [算力资源，内存，存储空间]

---

<head>
  <title>存储空间 - Lightly官方文档</title>
</head>


Lightly的项目资源均存储在云端，用户拥有一定的存储空间容量。

免费版提供500M空间，订阅会员后个人版提供10G空间，更多空间的升级方案可以前往会员订阅中心：https://lightly.teamcode.com/pricing。




## 存储空间

总磁盘空间分为项目和云端服务两部分，每个项目的存储空间分为代码、依赖、制品三个模块。

项目资源：

- 代码：文件路径为 /workspace ，保存了您在当前项目内所写的全部代码。
- 依赖：文件路径为 /home/user ，保存着您所下载或安装的依赖，比如pip、maven的安装包等，也保存了您的个性化配置。
- 制品：文件路径为 /artifact ，保存着您在当前项目内构建的所有制品。

云端服务：保存着您创建的所有云端服务资源。




## 查看存储

您可以在首页查看存储的已占用容量和总容量。

![image-20221118163101580](https://static01.teamcode.com/docs/202211181631729.png)

也可以进入任一项目，查看算力、内存及存储空间的信息：

![image-20221118163033179](https://static01.teamcode.com/docs/202211181630435.png)

存储空间已满时系统自动提示，可能会导致写入或运行失败，建议及时清理存储空间：

![image-20221118163406638](https://static01.teamcode.com/docs/202211181634809.png)