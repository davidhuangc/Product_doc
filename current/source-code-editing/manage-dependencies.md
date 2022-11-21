---
title: 依赖管理
sidebar_position: 3
description: 使用Lightly一键安装引用的依赖，导入的项目会自动检测并安装依赖，用户也可以手动打包依赖文件，手动下载和安装依赖。
keywords: [安装依赖, 自动安装依赖, 手动安装依赖, 下载依赖]

---

<head>
  <title>依赖管理 - Lightly官方文档</title>
</head>



## Python

### 一键安装引用的依赖

1.若您的项目文件中，import的部分标红，说明该依赖尚未安装。

![Lightly智能检测未安装的Python依赖](https://static01.teamcode.com/docs/202205171621710.png)

此时，若运行项目，将会报错“依赖缺失”。

![依赖缺失时智能报错](https://static01.teamcode.com/docs/202205171626321.png)

2.将鼠标悬停在标红的依赖上，系统会提示您该依赖缺失。点击“Quick Fix”。

![Lightly支持代码智能修复](https://static01.teamcode.com/docs/202205171622816.png)

3.确认安装缺失的依赖

![一键智能安装缺失依赖](https://static01.teamcode.com/docs/202205171624902.png)

4.安装完成后，系统会给出成功提示。

![成功安装引用依赖](https://static01.teamcode.com/docs/202205171631008.png)

5.重新运行项目，将可以成功运行

![使用Lightly成功安装依赖并运行](https://static01.teamcode.com/docs/202205171632176.png)

### 导入项目时，自动检测并安装依赖

导入Python项目时Lightly会自动检测是否包含“requirements.txt”文件，若包含则会自动下载和安装相关的依赖。

### 修改依赖文件后，一键安装

1.在requirements.txt中输入所需的依赖和版本号，检测到依赖文件更改后，系统会给出提示

![智能检测依赖文件更改](https://static01.teamcode.com/docs/202205171636573.png)

2.点击“重新加载依赖”，系统将会重新加载，并给出您所添加的依赖项的安装成功提示

![重新加载依赖并安装](https://static01.teamcode.com/docs/202205171638893.png)



### 手动打包依赖文件

在终端输入命令“pip freeze > requirements.txt”，生成requirements.txt文件。

![使用Lightly手动打包依赖文件](https://static01.teamcode.com/docs/202205171617472.png)

### 手动下载和安装依赖

1.在终端输入命令“pip install”，手动安装依赖

>如需要安装依赖包 numpy，可输入命令pip install numpy

![通过终端命令手动安装依赖](https://static01.teamcode.com/docs/202205171643494.png)

2.安装成功后，系统给出提示

![在Lightly手动安装依赖](https://static01.teamcode.com/docs/202205171643414.png)



## Java

### 修改依赖文件后，一键安装

1.在开发过程中修改pom.xml后，系统检测到更改，会给出提示

![Lightly自动检测Java依赖文件的修改](https://static01.teamcode.com/docs/202205171648868.png)

2.点击“重新加载依赖”，系统将会重新加载，并给出成功提示

![重新加载依赖并安装](https://static01.teamcode.com/docs/202205171649221.png)


### 导入项目自动检测和安装依赖

Lighlty支持使用Maven管理Java项目依赖，导入项目时Lightly会自动检测是否包含“pom.xml”文件，若有则会自动执行  <code>mvn install</code> 下载依赖和构建。



### 输入命令下载依赖并重新构建

可以手动在终端输入命令 <code>mvn install</code> 下载缺少的依赖和重新构建。

![通过终端命令手动安装Java依赖](https://static01.teamcode.com/docs/202204262150793.png)



## Go

### 修改依赖文件后，一键安装

1.在开发过程中修改go.mod后，系统检测到更改，会给出提示

![Lightly自动检测Go依赖文件的修改](https://static01.teamcode.com/docs/202205171707250.png)

2.点击“重新加载依赖”，系统将会重新加载，并给出成功提示





### 导入项目时，自动检测并安装依赖

导入Golang项目时Lightly会自动检测是否包含“go.mod”文件，若包含则会自动下载和安装相关的依赖。