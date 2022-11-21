---
title: 常见问题FAQ
sidebar_position: 45
description: 解答Lightly使用过程中遇到的常见问题，如安装报错、如何打包Java项目、安装Python依赖、预览HTML网页效果等
keywords: [Lightly常见问题, 安装报错, 如何打包项目, 如何安装依赖, 预览网页效果]
---

<head>
  <title>常见问题FAQ - Lightly官方文档</title>
</head>



## 如何运行项目？

在Lightly代码编辑页面，双击可运行的文件后，右上角 <code>运行</code> 按钮就会激活，点击即可运行。

![通过运行按钮运行代码](https://static01.teamcode.com/docs/202204292315091.gif)

打开代码文件后，也可以在编码区域右击，选择“运行当前文件”。

![选择运行当前文件代码](https://static01.teamcode.com/docs/202204292317838.gif)

您也可以在 <code>运行</code> 按钮左侧的“运行设置”中指定某个文件为当前项目的运行入口。

![从指定文件运行](https://static01.teamcode.com/docs/202204292328480.png)

更多细节可查看<a href="./running-and-debugging/running">《运行项目》</a>



## 如何安装Python的依赖？

在开发过程中如果发现缺少依赖包，可以再终端手动输入 <code>pip install</code> 安装依赖包。

> 例如：需要安装依赖包 networkx，可输入命令：<code>pip install networkx</code>


![通过终端手动安装Python依赖](https://static01.teamcode.com/docs/202204121304780.png)


安装成功后终端将显示版本号和其他成功的信息。

![使用Lightly安装Python依赖](https://static01.teamcode.com/docs/202204121228883.png)


更多细节可查看<a href="./source-code-editing/manage-dependencies">《安装依赖》</a>




## 如何预览HTML网页效果？
在项目编辑页面，打开你要预览的HTML页面，点击右上角的预览按钮

![Lightly可在线预览前端效果](https://static01.teamcode.com/docs/202204292326572.gif)


## 如何打包Java项目？

打开终端，在“终端”输入“mvn install”命令进行打包。

![通过Lightly终端打包Java项目](https://static01.teamcode.com/docs/202204111408397.png)

## 我的代码会被其他人看到吗？

不同用户之间是相互隔离的，除了自己和您邀请的项目成员，其他人无法访问您的代码。

您可以手动创建分享链接，获得链接的用户可以查看、复制和在自己的工作空间里运行。


## 项目会实时同步吗？

是的，目前所有的资源都会同步到云端，您在任何地方登录都可以访问到最新的代码并快速开始编码。


## Windows7安装报错“无法找到入口”怎么办？

如您的电脑是windows7系统，在安装时弹出报错提示“无法找到入口-无法定位程序输入点EventSetInformation于动态链接库advapi32.dll上”，可尝试通过下载和安装补丁解决：https://static01.teamcode.com/packages/Windows6.1-KB3080149-x64.msu

## Windows10安装报错2502、2503怎么办？

Windows 10如果遇到安装报错2502、2503可以按以下步骤解决：
1. 以管理员身份运行 命令提示符（cmd）
2. 输入 “msiexec /package 安装文件地址" 然后回车安装即可