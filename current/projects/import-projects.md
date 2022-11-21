---
title: 导入项目
sidebar_position: 2
description: Lightly桌面版支持导入本地C语言、C++、Java、Go、PHP、Python、HTML项目到云端。导入的本地项目将存储在云端，不会占用本地资源。
keywords: [本地项目, 导入本地项目, Lightly桌面版, 云端存储, C++, C语言, Java, Go, PHP, Python, HTML]

---

<head>
  <title>导入项目 - Lightly官方文档</title>
</head>


Lightly支持导入项目。导入的项目将存储在云端，不会占用本地资源。

Lightly桌面版导入项目可以选择两种来源：本地文件夹，Git仓库。

Lightly网页版及iPad版仅支持从Git仓库导入。

本地文件夹：您可以将本地存储的项目导入到Lightly。点击 <code>本地导入</code> 并选择项目所在的文件夹，即可将该项目加入您的项目列表。

![image-20221118122634607](https://static01.teamcode.com/docs/202211181226786.png)

从Git仓库导入：

![image-20221118122850813](https://static01.teamcode.com/docs/202211181228974.png)

公开访问：输入要访问的项目地址，点击`检测代码仓库`，系统将会自动检测地址是否通过。

![image-20221118123003842](https://static01.teamcode.com/docs/202211181230008.png)

授权访问：Lightly支持关联Github账号与Gitee账号获取授权。

![image-20221118123031671](https://static01.teamcode.com/docs/202211181230808.png)

点击后将跳转显示授权网页，授权成功后，即可访问账号内的公开项目和私密项目。

![image-20221118123430397](https://static01.teamcode.com/docs/202211181234582.png)

导入成功后：

1. Lightly会自动检测该项目的编程语言。如未能检测成功，则需要您在左侧菜单栏手动选择语言。

2. 更改或使用默认的项目名称（系统会自动提取您项目的文件夹名称），并进行相应信息的设置。

3. 项目成功导入后会自动跳转到编码页面，您可以继续优化项目并运行。

![image-20221118123710729](https://static01.teamcode.com/docs/202211181237906.png)

## 导入C/C++项目

如果您选择导入普通C/C++项目，导入成功后，从左侧菜单中选择文件即可进行编辑及运行。

![Lightly桌面版导入C/C++项目](https://static01.teamcode.com/docs/202204262233436.png)

如果您的项目包含其他配置信息，导入后，系统将会自动识别项目文件夹中的“CMakeLists.txt”文件，并进行构建，显示在右下角进度条里。



## 导入Java项目

如果您选择导入普通Java项目，导入成功后，从左侧菜单中选择文件即可进行编辑及运行。

![image-20220712103259938](https://static01.teamcode.com/docs/202207121033149.png)

如果您的Java项目由Maven进行管理，在导入时，系统会自动识别“pom.xml”文件，并进行mvn install打包到本地仓库，显示在右下角进度条里。



## 导入Go项目

从本地文件中选择Go项目，导入成功后，从左侧菜单选中相应文件即可进行编辑及运行。

![Lightly桌面版导入Go项目](https://static01.teamcode.com/docs/202204262241840.png)

若您导入的项目包含其他配置信息，导入后，系统将自动识别“go.mod”文件，并安装相应的包，显示在右下角进度条里，显示在右下角进度条里。



## 导入Python项目

如果您选择导入普通Python项目，导入成功后，从左侧菜单中选择文件即可进行编辑及运行。

![Lightly桌面版导入Python项目](https://static01.teamcode.com/docs/202204262242599.png)

如果您的项目包含其他配置信息，导入后，系统将会自动识别项目文件夹中的“requirements.txt”文件，并执行pip install，显示在右下角进度条里。



## 导入HTML项目

导入HTML项目时，系统将自动识别CSS、JS、HTML文件，并在左侧的菜单栏呈现。您可以依次点开它们，编译及预览自己的项目。

![Lightly桌面版导入HTML项目](https://static01.teamcode.com/docs/202204262242387.png)



## 导入PHP项目

导入PHP项目时，系统将自动识别CSS、JS、PHP文件，并在左侧的菜单栏呈现。您可以依次点开它们，编译及预览自己的项目。

![Lightly桌面版导入PHP项目](https://static01.teamcode.com/docs/202204262243195.png)

若您导入的项目包含其他配置信息，导入后，系统将自动识别“composer.json”文件，并安装相应的包，显示在右下角进度条里。



## 导入Rust项目

导入Rust项目时，系统将自动识别RS、TOML文件，并在左侧的菜单栏呈现。导入成功后，从左侧菜单中选择文件即可进行编辑及运行。

![Lightly导入Rust项目](https://static01.teamcode.com/docs/202207081540985.png)



## 导入React项目

导入React项目时，系统将自动识别CSS、JSX、HTML文件，并在左侧的菜单栏呈现。您可以依次点开它们，编译及预览自己的项目。

![Lightly导入React项目](https://static01.teamcode.com/docs/202206212300431.png)



## 导入Vue项目

导入Vue项目时，系统将自动识别CSS、JS、VUE文件，并在左侧的菜单栏呈现。您可以依次点开它们，编译及预览自己的项目。

![Lightly导入Vue项目](https://static01.teamcode.com/docs/202206212303773.png)



## 导入Node.js项目

导入Node.js项目时，系统将自动识别JS文件，并在左侧的菜单栏呈现。您可以依次点开它们，编译及预览自己的项目。

![lightly-nodejs-edit](https://static01.teamcode.com/docs/202211101128288.png)