---
layout: default
title: Amanda's Resume
category: coding
comments: true
---
<div>
<img src="images/IMG_0693.jpg" width=130 style="float:right;display:block;clear:both;"></src>
<lable style="float:left;font-size:40px">唐羽‘s 简历</lable>
</div>
</br>
#####<strong style="background:lightgray">联系方式
- 手机：18569510464 （湖南长沙）
- Email：amandatang333@outlook.com
- QQ：116078126

#####<strong style="background:lightgray">个人信息
- 唐羽 / 女 / 1991-6-28
- 硕士/ 中南大学 信息科学与工程学院 计算机系
- 个人小站：http://amandatang.github.io/rookiecoder/

#####<strong style="background:lightgray">教育经历
- 本科（2009 - 2013） --- 中南大学 计算机科学与技术专业
- 硕士（保送）（2013 - 2016）--- 中南大学 计算机系 数据挖掘分析与应用开发

#####<strong style="background:lightgray">个人信息
- 熟练掌握Spring，SOFA（支付宝自主框架），ibatis等J2EE开发技术
- 熟练掌握Java，Swing，Eclipse RCP等桌面端开发技术
- 熟悉Mysql、OceanBase等数据库的使用
- 熟悉银行业务以及网上支付业务流程与底层技术原理
- 熟悉多种网络聚类算法，中心度（Centrality）计算算法
- 了解LINUX下开发环境的基本维护
- 发表SCI论文一篇，另有一篇在投，以及发表CSCD一篇

#####<strong style="background:lightgray">实习经历 
- 实习时间：2015年6月23日-2015年9月2日
- 实习企业：蚂蚁金服-浙江网商银行
- 项目名称：蚂蚁金服-浙江网商银行-信用付受理平台
- 项目描述：该项目即将交付上线，实现类似于京东白条的功能，为用户提供信用抵换信贷额度的功能，并可以实现抵押票据之间的传递。
  整个项目采用支付宝自主开发框架SOFA MVC（**基于Spring**）进行开发，数据库则采用分布式数据库OceanBase进行数据存储。
- 我的工作：我在其中负责的接口主要分为两个方面：对外服务接口和页面查询接口。
  其中对外服务接口有支付关闭接口；支付关闭接口为我们提供给外部的远程服务接口，主要采用**异步调用**的方式将数据库中支付单状态进行修改；页面查询接口有付款、收款页面中总额与票据的查询接口，主要通过**SOFA TR**远程调用外部服务，实现数据查询；然后利用**SOFA MVC**技术实现前台信息聚合的功能；
  在完成了自己负责的接口的开发和单元测试之后，我利用**Spring AOP**原理实现了对外接口层和业务层的测试服务拦截器，利用RPC原理实现了远程调用对外接口调试组件，以及LINUX开发环境调试，修复bug。

#####<strong style="background:lightgray">个人作品
######CytoCluster
- 生物网络聚类分析及可视化软件
- http://apps.cytoscape.org/apps/cytocluster
- 使用语言： Java
- 该软件主要应用于生物网络中的稠密子图探测，实现了6种聚类算法以及子图可视化形式。基于Cytoscape平台，使用maven进行项目管理，以OSGi框架中bundle模式进行开发。界面及系统设计以及英文应用手册编写等均由我一人完成。上线以来下载使用约有四千余次。
- 由于该软件开发需要应用到Cytoscape开发API，而在国内并没有很多相关知识或者中文文档，只能从英文官网上的API文档以及源码、某些开源程序来学习，对于我对英文以及技术文档的阅读能力有了很大的提升。由于聚类算法对于数据结果的精准度要求较高，而且生物网络大多规模较大，对于算法的运行时间以及开销也有限制，如何实现这些算法要研究各种容器集合，使我对Java语言有了更深的理解。

######CytoNCA
- 生物网络中心度（Centrality）计算以及可视化综合分析软件
- http://apps.cytoscape.org/apps/cytonca
- 使用语言： Java
- 该软件主要应用于生物网络中不同中心度的计算，实现了带权以及不带权16种计算算法以及评估和可视化模式。基于Cytoscape平台，使用maven进行项目管理，以OSGi框架中bundle模式进行开发。界面及系统设计以及英文应用手册编写等均由我一人完成。上线以来下载使用约有两千余次。
- 上线初期很多人反馈软件运行大规模网络时会卡死，后来我发现由于软件中多个算法需要应用到矩阵中特征向量，计算将数十万节点的生物网络转为邻接矩阵需要消耗大量的内存，而Cytoscape的JVM内存默认过小，出现堆内存溢出错误。最后为了解决这个问题，在程序抛出堆内存溢出错误时将一部分数据写入磁盘而不是内存，虽然牺牲了一些计算时间，但确实没有再在大规模网络卡死现象。

######C-DEVA
- 生物网络聚类以及评估、可视化平台 
- https://code.google.com/p/c-deva/
- 使用语言： Java
- 该软件主要应用于生物网络稠密子图挖掘以及结合多元生物信息进行评估及可视化。使用Eclipse RCP进行主要平台开发，JPF进行插件管理。界面及系统设计以及英文应用手册编写等均由我一人完成。

#####<strong style="background:lightgray">文章论文
- CytoNCA: A cytoscape plugin for centrality analysis and evaluation of protein interaction networks 【SCI】
 - http://www.sciencedirect.com/science/article/pii/S0303264714001944)
- 基于Cytoscape的蛋白质网络可视化聚类分析插件【CSCD】
 - http://www.cnki.com.cn/Article/CJFDTotal-XXSW201401007.htm
- C-DEVA: detection, evaluation, visualization and annotation of clusters from biological networks【SCI】
 - accepted but unpublished

#####<strong style="background:lightgray">所获的奖励和荣誉
- 研究生
 - 研究生全额奖学金
 - 研究生一等助学金
 - 中南大学研究生自主探索创新基金
- 本科
 - 国家励志奖学金（两次）
 - 中南大学本科生优秀毕业论文
  
####致谢
**感谢您花时间阅读我的简历,期待能有机会和您共事。**









