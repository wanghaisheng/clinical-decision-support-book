# kickoff



[原文链接](http://www.healthit.gov/buzz-blog/electronic-health-and-medical-records/interoperability-electronic-health-and-medical-records/standards-interoperability-framework-milestones-health-edecision-initiative-closeout-clinical-quality-framework-launch/?utm_source=feedburner&utm_medium=email&utm_campaign=Feed%3A+healthitbuzzblog+%28Health+IT+Buzz+Blog%29)

   历时21个月的Health eDecision(HeD)项目终于要收尾了，自2012年7月启动，在Ken Kawamoto, Tonya Hongsermeier, Aziz Boxwala, Bryn Rhodes and Jamie Parker等人的带领下，围绕着如下两个问题：

1.临床决策支持知识/制品的共享，也就是说如何以电子化的方式来共享已有的临床决策支持的规则，能够让异构的信息系统都可以使用
2.临床决策支持建议服务，也就是说从技术上如何利用数据向某个网站或某个服务获取针对过敏或其他复杂决策的最新建议

成果：通过对现有的CDS标准的评估和整合，形成了三份实施指导和六份标准文件

* Clinical Decision Support Knowledge Artifact Implementation Guide

* Decision Support Service Implementation Guide

* Virtual Medical Record (vMR) Logical Model

* vMR XML Specification

* vMR Templates

* Decision Support Service (DSS) Standard

CQF(clinical quality framework)临床质量框架将在HeD的基础上，对临床决策支持/CDS和电子化的临床质量测度标准进行整合。

1.地址  http://wiki.siframework.org/Clinical+Quality+Framework+Initiative

2.2014-03/21 正式启动
大概的时间节点为：
2014年三月: Pre-Discovery - 召集参与人员
2014年四月: Discovery - 甘特图、用例、功能需求分析
2014年5月-2015年11月: 实现 – 标准开发和评审
2014年6月-2015年11月: 试点
2015年12月: 评估

3.背景介绍
鉴于CDS和eCQM质控指标紧密相关，拥有很多共同的需求，但是二者所采用的标准则是各异的，主要是表达患者数据和计算机化处理逻辑的方法是不同的

| 类别 | 患者数据 | 处理逻辑 |
| -- | -- | -- |
| CDS | VMR | CDS knowledge artifact实施指南 |
| ECQM | 	quality reporting data architecture物理模型quality data model 逻辑模型 | Health quality measure format HQMF 物理模型Quality data model 逻辑模型 |



问题在于：

1.二者之间无法复用              
2.EHR/EMR系统要将自定义格式映射到这2类标准上去               

该项目旨在整合此2类标准

4.项目范围
* 定义、确定 整合一下几类CDS和eCQM的标准
    * A——mettadata元数据：确定两个领域公用的一些元数据，统一这些元数据的表达方式
    * B——患者数据模型:能够同时满足CDS和eCQM的需求
    * C——逻辑表达语言：开发一种能够表达两类逻辑的语言
* 对已有的CDS和eCQM标准进行重构，形成统一的标准
* 尽可能的对产生的标准进行试点并及时作出调整
* 利用临床质控人员的参与 提升产生的标准的可用性和严密性
* 支持这些标准在HL7的投票和发布
