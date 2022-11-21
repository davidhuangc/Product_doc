---
title: 调试
sidebar_position: 2
description: 在Lightly Debug模式下，可以自由设置断点。开启Debug调试，程序会在运行到断点时暂停，方便分析当前的运行情况。支持Python、Java等语言代码Debug断点调试。
keywords: [Debug, 断点调试, 代码调试, Python Debug, Java Debug]

---

<head>
  <title>调试 - Lightly官方文档</title>
</head>

在Debug模式下，您可以自由设置断点。开启Debug调试，程序会在运行到断点时暂停，让您可以分析当前的运行情况。


## 设置断点

在编辑区域左侧，可以给想要调试的代码行打上断点

![使用Lightly Debug打断点](https://static01.teamcode.com/docs/202205120018883.png)



## 开始调试

点击右上角 <code>调试</code> 按钮，或在编码区域的右键菜单中选择“调试当前文件”，开始Debug调试。

![在Lightly中Debug调试代码](https://static01.teamcode.com/docs/202205120021196.png)


## 调试功能介绍

### 跳到下一断点

点击此按钮，跳到下一个符合中断条件的断点处

![Debug调试功能之跳到下一断点](https://static01.teamcode.com/docs/202205120026496.png)

### 步过

点击此按钮，在方法内逐行执行，结束该方法的执行后跳转到下一个断点

![Debug调试功能之步过](https://static01.teamcode.com/docs/202205120028879.png)

### 停止调试

点击此按钮，或右上角 <code>停止</code> 按钮，停止调试

![停止Debug调试](https://static01.teamcode.com/docs/202205120029187.png)

### 断点列表管理

在“断点列表”区域显示当前所有的断点，格式为：[文件名:断点所在行号]

### 查看变量值

在“变量”区域显示中断所在行的所有变量的值