---
title: 新建项目
sidebar_position: 1
description: 使用Lightly创建C语言工程项目、C++工程项目、Java工程项目、Go工程项目、Python工程项目、HTML工程项目、PHP工程项目等不同语言项目。
keywords: [C语言项目, C++项目, Java项目, Golang项目, Python项目, HTML项目, 前端项目, PHP项目]

---

<head>
  <title>新建项目 - Lightly官方文档</title>
</head>
在项目列表页面，您可以点击 <code>新建项目</code> 按钮创建不同语言的工程项目，目前支持：<a href="#%E6%96%B0%E5%BB%BAc%E9%A1%B9%E7%9B%AE">C</a>、<a href="#%E6%96%B0%E5%BB%BAc%E9%A1%B9%E7%9B%AE-1">C++</a>、<a href="#%E6%96%B0%E5%BB%BAjava%E9%A1%B9%E7%9B%AE">Java</a>、<a href="#%E6%96%B0%E5%BB%BAgo%E9%A1%B9%E7%9B%AE">Go</a>、<a href="#%E6%96%B0%E5%BB%BApython%E9%A1%B9%E7%9B%AE">Python</a>、<a href="#%E6%96%B0%E5%BB%BAhtml%E9%A1%B9%E7%9B%AE">HTML</a>、<a href="#%E6%96%B0%E5%BB%BAphp%E9%A1%B9%E7%9B%AE">PHP</a>、<a href="#%E6%96%B0%E5%BB%BArust%E9%A1%B9%E7%9B%AE">Rust</a>、<a href="#%E6%96%B0%E5%BB%BAreact%E9%A1%B9%E7%9B%AE">React</a>、<a href="#%E6%96%B0%E5%BB%BAvue%E9%A1%B9%E7%9B%AE">Vue</a>。

## 新建C项目

在项目列表页面点击 <code>新建项目</code> 按钮，在弹出的对话框：

- 左侧语言类型选择“C”
- 根据需要修改“项目名称”
- 根据需要选择C语言标准，目前支持：C11、C99、C90
- 根据需要选择C语言模板，目前支持：空项目、CMake Project

即可完成C语言项目的创建。

![创建C语言](https://static01.teamcode.com/docs/202211181151757.png)

创建完成后会自动打开该项目，可以看到为您预设好的C语言模板。在左侧文件目录里单击某个文件，即可打开该文件进行编辑。

![C语言hello world模板](https://static01.teamcode.com/docs/202204260052795.png)

点击右上角的 <code>运行</code> 按钮，查看运行效果。

![运行C语言hello world代码](https://static01.teamcode.com/docs/202204260053181.png)



## 新建C++项目

在项目列表页面点击 <code>新建项目</code> 按钮，在弹出的对话框：

- 左侧语言类型选择“C++”
- 根据需要修改“项目名称”
- 根据需要选择C++标准，目前支持：C++17、C++14、C++11、C++98
- 根据需要选择C++语言模板，目前支持：空项目、CMake Project

即可完成C++项目的创建。

![image-20221118115155198](https://static01.teamcode.com/docs/202211181151339.png)

创建完成后会自动打开该项目，可以看到为您预设好的C++模板。在左侧文件目录里单击某个文件，即可打开该文件进行编辑。

![image-20221118115611672](https://static01.teamcode.com/docs/202211181156813.png)

点击右上角的 <code>运行</code> 按钮，查看运行效果。

![image-20221118115811073](https://static01.teamcode.com/docs/202211181158242.png)

## 新建Java项目

在项目列表页面点击 <code>新建项目</code> 按钮，在弹出的对话框：

- 左侧语言类型选择“Java”
- 根据需要修改“项目名称”
- 根据需要选择JDK的版本，目前支持：v1.8.0、v1.11.0、v1.17.0
- 根据需要选择Java语言模板，目前支持：空项目、Maven Project、SpringBoot 2

![image-20221118115847101](https://static01.teamcode.com/docs/202211181158246.png)

- 选择是否使用Maven进行“依赖管理”。如选择使用Maven，根据需要修改“Artifact ID”及“Version”的信息。

  为什么选择Maven？

  如今我们构建一个大型项目需要用到很多第三方的类库，一个项目Jar包的数量有时候多到让人吃惊。并且Jar包之间的关系错综复杂，一个Jar包往往又会引用其他Jar包，缺少任何一个Jar包都会导致项目编译失败。

  Maven就是一款帮助程序员构建项目的工具，我们只需要告诉Maven需要哪些Jar包，它会帮助我们下载所有的Jar，极大提升开发效率。

![image-20221118115937750](https://static01.teamcode.com/docs/202211181159899.png)

- 如选择使用SpringBoot 2，同样通过Maven进行“依赖管理”。根据需要修改“Artifact ID”及“Version”的信息。

![image-20221118120009344](https://static01.teamcode.com/docs/202211181200477.png)

即可完成Java项目的创建。

创建完成后会自动打开该项目，可以看到为您预设好的Java模板。在左侧文件目录里单击某个文件，即可打开该文件进行编辑。

![image-20221118120509581](https://static01.teamcode.com/docs/202211181205735.png)

点击右上角的 <code>运行</code> 按钮，查看运行效果。

![image-20221118120526923](https://static01.teamcode.com/docs/202211181205050.png)



## 新建Go项目

在项目列表页面点击 <code>新建项目</code> 按钮，在弹出的对话框：

- 左侧语言类型选择“Golang”
- 根据需要修改“项目名称”
- 根据需要选择Go语言版本，目前支持：Go 1.16、Go 1.17、Go 1.18

即可完成Go项目的创建。

![image-20221118120550504](https://static01.teamcode.com/docs/202211181205694.png)

创建完成后会自动打开该项目，可以看到为您预设好的Go语言模板。在左侧文件目录里单击某个文件，即可打开该文件进行编辑。

![Go hello world模板](https://static01.teamcode.com/docs/202204261819498.png)

点击右上角的 <code>运行</code> 按钮，查看运行效果。

![运行Go hello world代码](https://static01.teamcode.com/docs/202204261819097.png)

## 新建Python项目

在项目列表页面点击 <code>新建项目</code> 按钮，在弹出的对话框：

- 左侧语言类型选择“Python”
- 根据需要修改“项目名称”
- 根据需要选择Python版本，目前支持：python3.10、python3.9、python3.8、python3.7、python2.7

![image-20221118120608690](https://static01.teamcode.com/docs/202211181206823.png)

- 根据需要选择Python模板，目前支持：
  - Python with Turtle：使用Turtle库，可在Python中轻松开发图形相关的应用
  - Python Django Project：预装Django框架，可快速开发Web项目
  - Python Matplotlib Project：预装Matplotlib库，可用于数据图形化，提供多样化的输出格式
  - Python Pandas Project：预装Pandas库，可用于数据分析
  - Python Pygame Project：预装Pygame库，可创建功能齐全的游戏和多媒体程序


![image-20221118120632912](https://static01.teamcode.com/docs/202211181206042.png)

创建完成后会自动打开该项目，可以看到为您预设好的Python模板。在左侧文件目录里单击某个文件，即可打开该文件进行编辑。

以空项目为例：

![Python hello world模板](https://static01.teamcode.com/docs/202204261820120.png)

点击右上角的 <code>运行</code> 按钮，查看运行效果。

![运行Python hello world代码](https://static01.teamcode.com/docs/202204261821026.png)

以Python with Turtle为例，新建好项目可以看到预设的模板：

![image-20221118121240738](https://static01.teamcode.com/docs/202211181212895.png)

点击运行查看效果：

![image-20221118121317836](https://static01.teamcode.com/docs/202211181213014.png)



## 新建HTML项目

在项目列表页面点击 <code>新建项目</code> 按钮，在弹出的对话框：

- 左侧语言类型选择“HTML”
- 根据需要修改“项目名称”

即可完成HTML项目的创建。

![image-20221118121409792](https://static01.teamcode.com/docs/202211181214925.png)

创建完成后会自动打开该项目，可以看到为您预设好的CSS、JavaScript、HTML模板。在左侧文件目录里单击某个文件，即可打开该文件进行编辑。

点击html文件，会自动在IDE内展开预览窗口。

![image-20221118121508859](https://static01.teamcode.com/docs/202211181215002.png)

选中“index.html”文件后，点击右上角的 <code>预览</code> 按钮，您可以在弹出的窗口中预览运行结果。

![运行HTML hello world代码](https://static01.teamcode.com/docs/202204261835909.gif)



## 新建PHP项目

在项目列表页面点击 <code>新建项目</code> 按钮，在弹出的对话框：

- 左侧语言类型选择“PHP”
- 根据需要修改“项目名称”
- 根据需要选择PHP版本，目前支持：PHP 8.1、PHP 7.4

即可完成PHP项目的创建。

![image-20221118121613228](https://static01.teamcode.com/docs/202211181216362.png)

创建完成后会自动打开该项目，可以看到为您预设好的PHP项目模板文件。在左侧文件目录里单击某个文件，即可打开该文件进行编辑。

![PHP hello world模板](https://static01.teamcode.com/docs/202204261831922.png)

选中“index.php”文件，点击右上角的 <code>运行</code> 按钮，根据提示添加网络端口后，您可以预览运行结果。

![运行PHP hello world代码](https://static01.teamcode.com/docs/202204261835468.gif)



## 新建Rust项目

在项目列表页面点击 <code>新建项目</code> 按钮，在弹出的对话框：

- 左侧语言类型选择“Rust”
- 根据需要修改“项目名称”

即可完成Rust项目的创建。

![image-20221118121632045](https://static01.teamcode.com/docs/202211181216174.png)

创建完成后会自动打开该项目，可以看到为您预设好的Rust模板。在左侧文件目录里单击某个文件，即可打开该文件进行编辑。

![Lightly编辑Rust项目](https://static01.teamcode.com/docs/202207081529524.png)

点击右上角的 <code>运行</code> 按钮，查看运行效果。

![Lightly运行Rust项目](https://static01.teamcode.com/docs/202207081532182.png)



## 新建React项目

在项目列表页面点击 <code>新建项目</code> 按钮，在弹出的对话框：

- 左侧模板类型选择“React”
- 根据需要修改“项目名称”
- 根据需要选择脚本语言，目前支持：JavaScript、TypeScript

即可完成React项目的创建。

![image-20221118121651994](https://static01.teamcode.com/docs/202211181216130.png)创建完成后会自动打开该项目，可以看到为您预设好的React项目模板文件。在左侧文件目录里单击某个文件，即可打开该文件进行编辑。

![Lightly编辑React项目](https://static01.teamcode.com/docs/202206211918971.png)

如果是初次运行，需要先在终端窗口输入：`yarn`

![Lightly运行React项目](https://static01.teamcode.com/docs/202206212134989.gif)

安装成功后，或者已经安装过的项目，可以通过在终端窗口输入以下代码运行项目：`yarn dev`
若端口没有添加，会弹出添加端口的提示，点击“立即添加”后，在端口管理页面点击“查看”按钮，
即可在浏览器里打开前端项目。

![Lightly为React项目添加端口](https://static01.teamcode.com/docs/202206212224567.gif)



## 新建Vue项目

在项目列表页面点击 <code>新建项目</code> 按钮，在弹出的对话框：

- 左侧模板类型选择“Vue”
- 根据需要修改“项目名称”
- 根据需要选择脚本语言，目前支持：JavaScript、TypeScript

即可完成Vue项目的创建。

![image-20221118121718088](https://static01.teamcode.com/docs/202211181217225.png)

创建完成后会自动打开该项目，可以看到为您预设好的Vue项目模板文件。在左侧文件目录里单击某个文件，即可打开该文件进行编辑。

![Lightly编辑Vue项目](https://static01.teamcode.com/docs/202206212303002.png)

如果是初次运行，需要先在终端窗口输入：`yarn`

![Lightly运行Vue项目](https://static01.teamcode.com/docs/202206212233007.gif)

安装成功后，或者已经安装过的项目，可以通过在终端窗口输入以下代码运行项目：`yarn dev`
若端口没有添加，会弹出添加端口的提示，点击“立即添加”后，在端口管理页面点击“查看”按钮，
即可在浏览器里打开前端项目。

![Lightly添加Vue项目端口](https://static01.teamcode.com/docs/202206212235529.gif)



## 新建Node.js项目

在项目列表页面点击 <code>新建项目</code> 按钮，在弹出的对话框：

- 左侧语言类型选择“Node.js”
- 根据需要修改“项目名称”

即可完成Node.js项目的创建。

![image-20221118122039004](https://static01.teamcode.com/docs/202211181220161.png)

创建完成后会自动打开该项目，可以看到为您预设好的Node.js模板。在左侧文件目录里单击某个文件，即可打开该文件进行编辑。

![lightly-nodejs-edit](https://static01.teamcode.com/docs/202211101120758.png)

在终端输入 <code>node index.js</code> 并回车，查看运行效果。

![lightly-nodejs-run](https://static01.teamcode.com/docs/202211101121499.png)





## 更多操作及须知

1. 新建项目时，项目名称不能重名。

2. 在编辑界面点击鼠标右键，您将可以看到更多操作。
   您也可以查阅文档中的<a href="./preference-settings/shortcut-keys">快捷键说明</a>，进行快速操作。

   ![Lightly IDE快捷键说明](https://static01.teamcode.com/docs/202204261838027.png)

3. 在菜单栏处点击鼠标右键，可以对您项目中的文件进行管理，包含新建文件或文件夹、重命名、删除、下载、上传。您还可以通过拖拽来调整文件间的层级关系。

   ![Lightly IDE项目文件管理](https://static01.teamcode.com/docs/202204261838767.png)



