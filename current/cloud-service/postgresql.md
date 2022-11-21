---
title: PostgreSQL
sidebar_position: 2
description: 使用Lightly链接PostgreSQL云端服务。
keywords: [MongoDB, MySQL, PostgreSQL, Redis]


---

<head>
  <title>PostgreSQL - Lightly官方文档</title>
</head>

Lightly支持云端服务中间件。

云端服务是会员独享的权利，会员可以创建和使用MySQL、PostgreSQL、Redis等云端服务，并可通过本地客户端链接和管理。



## 服务入口

您可以在首页中切换至云端服务界面，查看云端服务列表：

![lightly-云端服务](https://static01.teamcode.com/docs/202208121745129.png)

您也可以在会员中心，跳转到云端服务页面：

![lightly-云端服务](https://static01.teamcode.com/docs/202208121747499.png)

在项目内，您可以点击侧边栏打开云端服务列表：

![lightly-云端服务](https://static01.teamcode.com/docs/202208121800909.png)



### 创建PostgreSQL云端服务

在云端服务列表页面点击 <code>新建服务</code> 按钮，在弹出的对话框：

- 名称：根据需要修改该服务名称
- 服务：选择“PostgreSQL 14”
- 时长：根据需要左右拖动按钮选择相应时长

点击<code>创建</code>并完成支付后，将自动创建服务。

![使用Lightly创建云端服务-PostgreSQL](http://static01.teamcode.com/docs/20220809135135.png)

在云端服务列表页面，点击刚创建的云端服务，查看详情。

![Lightly云端服务列表-PostgreSQL](http://static01.teamcode.com/docs/20220809135721.png)

您可以在这里看见云端服务的详细信息。

服务ID：如果您遇到数据库相关问题，请将该ID反馈给我们。

外网地址：您可以通过外网地址从本地链接和管理云端服务。

内网地址：您可以通过内网地址在应用中更快速的链接云端服务。![Lightly云端服务列表详情-PostgreSQL](https://static01.teamcode.com/docs/202208110216032.png)



## 启动服务

您可以在首页-云端服务界面中，查看服务列表，点击启动即可：

![lightly-启动云端服务](https://static01.teamcode.com/docs/202208121802168.png)

您也可以在项目内打开侧边栏的云端服务，启动服务：

![lightly-启动云端服务](https://static01.teamcode.com/docs/202208121825606.png)

启动中：

![lightly-云端服务启动中](https://static01.teamcode.com/docs/202208121803774.png)

启动成功：

![lightly-云端服务启动成功](https://static01.teamcode.com/docs/202208121803209.png)

## 停止服务

您可以在首页-云端服务界面中，查看服务列表，点击停止即可：

![lightly-停止云端服务](https://static01.teamcode.com/docs/202208121826800.png)

您也可以在项目内打开侧边栏的云端服务，停止服务：

![lightly-停止云端服务](https://static01.teamcode.com/docs/202208121825899.png)



## 时长计算

云端服务在启动后将自动开始计算时长，您可以在服务列表和服务详情页查看已使用时长和总时长：

![lightly-云端服务时长计算](https://static01.teamcode.com/docs/202208121828770.png)



## 续费

您可以点击服务详情，在该页面点击购买更多时长：

![lightly-云端服务续费](https://static01.teamcode.com/docs/202208121829606.png)

随后即会出现购买时长页面，您可以使用会员赠送时长购买，也可以单独购买：

![lightly-云端服务购买](https://static01.teamcode.com/docs/202208121829462.png)

按配置、时长购买，用完后可续费；

目前配置为基础型：0.5C1G + 500M，价格为每10小时3元。



## 会员权益

云端服务是会员独享的权利，仅会员才可以创建和使用云端服务。

如果不是会员开通会员后可使用，如果会员过期，续费恢复会员资格后可使用。



## 通过软件链接和管理服务

**安装PostgreSQL客户端**

此处以Navicat为例。<a href="http://www.navicat.com.cn/">点击下载客户端</a>，并进行安装。

打开客户端，新建连接，选择PostgreSQL。  ![客户端新建服务-PostgreSQL](http://static01.teamcode.com/docs/20220809140748.png)

进行配置：主机与端口均可直接复制云端服务详情页中的具体信息。
确认云端服务处于运行中的状态，点击<code>确定</code>，即完成数据库连接。

![客户端配置-PostgreSQL](http://static01.teamcode.com/docs/20220809144028.png)


左侧红框内即为已连接的PostgreSQL云端服务。

![客户端服务列表-PostgreSQL](http://static01.teamcode.com/docs/20220809140944.png)



## 在程序中链接服务

以Python语言环境下，连接MySQL数据库为例：

代码：

```python
# quick fix安装依赖 或者终端输入pip install pymysql
import pymysql

# 建立数据库链接
conn = pymysql.connect(
    host='cs-cn-east-dev-31.teamcode.com',  # 外网/内网地址
    port=5002,   # 端口
    user='root',  # 账号
    password='6ef0a6ba2376',  # 密码
    db='user',  # database名称
    charset='utf8'  # 编码格式
    )

# 拿到游标
cursor = conn.cursor()

# 执行sql语句
sql = 'select * from userinfo'
cursor.execute(sql)

# 获取执行结果
result = cursor.fetchall() # 获取所有查询的数据行
print(result)

cursor.close()
conn.close()

# 进行判断
if result:
    print('连接成功')
else:
    print('连接失败')

```

点击运行，此示例代码含义为查询指定数据库中的指定表的所有数据。

运行结果如下：

![image-20220811023932032](https://static01.teamcode.com/docs/202208110239346.png)