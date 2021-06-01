​
下载地址：http://ym.maptoface.com/2021/06/01/%e7%bd%91%e4%b8%8a%e6%b0%b4%e6%9e%9c%e8%b6%85%e5%b8%82%e7%9a%84%e8%ae%be%e8%ae%a1%e4%b8%8e%e5%ae%9e%e7%8e%b0%e6%af%95%e4%b8%9a%e8%ae%ba%e6%96%87javassm%e9%a1%b9%e7%9b%ae%e6%ba%90%e7%a0%81%e5%8f%8amys/
摘  要
近年来，随着Internet的迅速崛起，互联网已日益成为收集提供信息的最佳渠道并逐步进入传统的流通领域。于是电子商务开始流行起来，越来越多的商家在网上建起在线商店，向消费者展示出一种新颖的购物理念。

网上水果超市系统作为电子商务的前端商务平台，在其商务活动全过程中起着举足轻重的作用。本文主要考虑的是如何建设B2C的网上水果超市系统。

网上水果超市是一种具有交互功能的商业信息系统。它向用户提供静态和动态两类信息资源。所谓静态信息是指那些比经常变动或更新的资源，如公司简介、管理规范和公司制度等等；动态信息是指随时变化的信息，如水果报价，会议安排和培训信息等。网上水果超市系统具有强大的交互功能，可使商家和用户方便的传递信息，完成电子贸易或EDI交易。这种全新的交易方式实现了公司间文档与资金的无纸化交换。

本系统主要由微信小程序客户端、服务器、数据管理端构成，客户端采用微信小程序的MINA框架和微信Web开发工具，后台管理采用Java技术，SSM框架和Mysql数据库。客户端的页面实现通过网络与服务器REST API接口通信获取MySQL数据。

关键词：网络购物；水果超市；电子商务；SSM

Design and implementation of online fruit supermarket

Abstract
As the rapid rise of Internet in recent years, the Internet has increasingly become the best channel to collect and provide information and gradually enter the traditional circulation domain. So e-commerce began to become popular, more and more businesses set up online stores to show consumers a novel shopping concept.

As the front-end business platform of e-commerce, the online fruit supermarket system plays an important role in the whole process of its business activities. How to build a B2C online fruit supermarket system is considered in this paper.

The online fruit supermarket is a kind of business information system with interactive function. It provides users with both static and dynamic information resources. The so-called static information refers to those resources that are more frequently changed or updated, such as company profiles, management norms and company systems, etc.; dynamic information refers to information that changes at any time, such as fruit quotations, meeting arrangements and training information. Internet fruit supermarket system has powerful interactive function, can make merchants and users convenient to transfer information, complete electronic trade or EDI transactions. This new way of trading realizes the paperless exchange of documents and funds between companies.

The system is mainly composed of WeChat Mini Program client, server, data management end, the client adopts the MINA framework of WeChat Mini Program and WeChat Web development tools, background management uses Java technology, SSM framework and Mysql database. The page implementation of the client obtains the MySQL data through the communication REST API the interface between the network and the server.

Keywords: online shopping; fruit supermarket; e-commerce; SSM;


目  录
摘  要 I

Abstract II

目  录 IV

第一章 引言 1

1.1 系统开发背景 1

1.2 系统开发意义 1

1.3论文的主要结构 2

第二章 系统设计工具介绍 3

2.1 平台选择 3

2.2 系统开发工具 3

2.2.1 开发语言—JSP 3

2.2.2 数据库—MySQL 4

第三章 网上水果超市需求分析 5

3.1 网上水果超市系统的现状 5

3.2 可行性分析 6

3.3 系统实现的目标 6

3.4 系统功能需求 6

3.4.1 功能概述 6

3.4.2 功能描述 7

3.4.3 功能划分 8

3.4.3 功能用例 8

第四章 网上水果超市系统设计 14

4.1 项目规划 14

4.1.1 系统功能结构图 14

4.1.2 处理流程 15

4.2 系统设计 16

4.2.1 设计目标 16

4.2.2 系统开发环境 16

4.3 数据库设计 17

第五章 网上水果超市系统实现 23

5.1 系统各部分的实现方法 23

5.1.1 创建与数据库的连接 23

5.1.2 访问数据库的JavaBean 23

5.2 网站前台设计 24

5.2.1前台框架设计 24

5.2.2 网站首页 25

5.2.3 产品详情页 26

5.2.4 评价 27

5.3网站后台设计 27

5.3.1 后台主页 27

5.3.2 后台评价管理 28

5.3.3 水果管理 29

5.3.4水果信息修改 29

5.3.5 水果分类管理 30

5.3.6 订单管理 30

5.3.7 购物车管理 31

第六章 系统测试与评价分析 32

6.1 测试环境简介 32

6.2 系统的不足及修改方法 32

6.3 系统的评价分析 33

6.3.1 实用性 33

6.3.2 可维护性 33

6.3.3 可扩展性 33

结论 34

参考文献 35

致谢 37

  转存失败重新上传取消                       

摘  要
近年来，随着Internet的迅速崛起，互联网已日益成为收集提供信息的最佳渠道并逐步进入传统的流通领域。于是电子商务开始流行起来，越来越多的商家在网上建起在线商店，向消费者展示出一种新颖的购物理念。

网上水果超市系统作为电子商务的前端商务平台，在其商务活动全过程中起着举足轻重的作用。本文主要考虑的是如何建设B2C的网上水果超市系统。

网上水果超市是一种具有交互功能的商业信息系统。它向用户提供静态和动态两类信息资源。所谓静态信息是指那些比经常变动或更新的资源，如公司简介、管理规范和公司制度等等；动态信息是指随时变化的信息，如水果报价，会议安排和培训信息等。网上水果超市系统具有强大的交互功能，可使商家和用户方便的传递信息，完成电子贸易或EDI交易。这种全新的交易方式实现了公司间文档与资金的无纸化交换。

本系统主要由微信小程序客户端、服务器、数据管理端构成，客户端采用微信小程序的MINA框架和微信Web开发工具，后台管理采用Java技术，SSM框架和Mysql数据库。客户端的页面实现通过网络与服务器REST API接口通信获取MySQL数据。

关键词：网络购物；水果超市；电子商务；SSM

Design and implementation of online fruit supermarket

Abstract
As the rapid rise of Internet in recent years, the Internet has increasingly become the best channel to collect and provide information and gradually enter the traditional circulation domain. So e-commerce began to become popular, more and more businesses set up online stores to show consumers a novel shopping concept.

As the front-end business platform of e-commerce, the online fruit supermarket system plays an important role in the whole process of its business activities. How to build a B2C online fruit supermarket system is considered in this paper.

The online fruit supermarket is a kind of business information system with interactive function. It provides users with both static and dynamic information resources. The so-called static information refers to those resources that are more frequently changed or updated, such as company profiles, management norms and company systems, etc.; dynamic information refers to information that changes at any time, such as fruit quotations, meeting arrangements and training information. Internet fruit supermarket system has powerful interactive function, can make merchants and users convenient to transfer information, complete electronic trade or EDI transactions. This new way of trading realizes the paperless exchange of documents and funds between companies.

The system is mainly composed of WeChat Mini Program client, server, data management end, the client adopts the MINA framework of WeChat Mini Program and WeChat Web development tools, background management uses Java technology, SSM framework and Mysql database. The page implementation of the client obtains the MySQL data through the communication REST API the interface between the network and the server.

Keywords: online shopping; fruit supermarket; e-commerce; SSM;


目  录
摘  要 I

Abstract II

目  录 IV

第一章 引言 1

1.1 系统开发背景 1

1.2 系统开发意义 1

1.3论文的主要结构 2

第二章 系统设计工具介绍 3

2.1 平台选择 3

2.2 系统开发工具 3

2.2.1 开发语言—JSP 3

2.2.2 数据库—MySQL 4

第三章 网上水果超市需求分析 5

3.1 网上水果超市系统的现状 5

3.2 可行性分析 6

3.3 系统实现的目标 6

3.4 系统功能需求 6

3.4.1 功能概述 6

3.4.2 功能描述 7

3.4.3 功能划分 8

3.4.3 功能用例 8

第四章 网上水果超市系统设计 14

4.1 项目规划 14

4.1.1 系统功能结构图 14

4.1.2 处理流程 15

4.2 系统设计 16

4.2.1 设计目标 16

4.2.2 系统开发环境 16

4.3 数据库设计 17

第五章 网上水果超市系统实现 23

5.1 系统各部分的实现方法 23

5.1.1 创建与数据库的连接 23

5.1.2 访问数据库的JavaBean 23

5.2 网站前台设计 24

5.2.1前台框架设计 24

5.2.2 网站首页 25

5.2.3 产品详情页 26

5.2.4 评价 27

5.3网站后台设计 27

5.3.1 后台主页 27

5.3.2 后台评价管理 28

5.3.3 水果管理 29

5.3.4水果信息修改 29

5.3.5 水果分类管理 30

5.3.6 订单管理 30

5.3.7 购物车管理 31

第六章 系统测试与评价分析 32

6.1 测试环境简介 32

6.2 系统的不足及修改方法 32

6.3 系统的评价分析 33

6.3.1 实用性 33

6.3.2 可维护性 33

6.3.3 可扩展性 33

结论 34

参考文献 35

致谢 37

转存失败重新上传取消  转存失败重新上传取消 转存失败重新上传取消 转存失败重新上传取消  转存失败重新上传取消 转存失败重新上传取消 转存失败重新上传取消 转存失败重新上传取消  转存失败重新上传取消 转存失败重新上传取消 转存失败重新上传取消 转存失败重新上传取消 转存失败重新上传取消 转存失败重新上传取消 转存失败重新上传取消 转存失败重新上传取消 转存失败重新上传取消  转存失败重新上传取消 转存失败重新上传取消 转存失败重新上传取消 转存失败重新上传取消 转存失败重新上传取消

​
