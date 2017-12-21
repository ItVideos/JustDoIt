---
title: Elasticsearch顶尖高手系列-快速入门篇
categories: 大数据
tags: Elasticsearch入门
---

## 课程介绍

![](http://static.roncoo.com/lecturer/9f2feb3b95e9463a9773514142d2c988.jpg)

<!--more-->

Elasticsearch，是目前行业中非常热门的一个技术。Elasticsearch是一种分布式的海量数据搜索与分析的技术，可以用于电商网站、门户网站、企业IT系统等各种场景下的搜索引擎，也可以用于对海量的数据进行近实时的数据分析。相较于Lucene来说，Elasticsearch天然的分布式特性，让其可以支持海量的、PB级的大数据搜索。相对于Spark Streaming、Storm等大数据实时计算引擎来说，Elasticsearch天生为分布式执行数据分析操作而生的架构，海量数据量级下的近实时（秒级）性能支持，以及无比强大的搜索和聚合分析的语法支持，让ES更加适合进行大数据场景下的数据分析应用。

Spark Streaming进行实时数据分析，有天然的无法全量多数据流join、内核shuffle过程大量基于磁盘落地等缺陷，导致其实时数据分析功能较差，实时数据分析性能也较差。Storm则作为实时计算引擎的鼻祖，由于其对SQL的支持很弱，导致其非常不适合进行实时数据分析，开发成本巨大。而Elasticsearch克服了上述大数据技术的缺点，更加适合进行大数据场景下的数据分析操作。

本课程深入浅出剖析了Elasticsearch的核心基础知识，带着大家一步一步，从快速入门，到理解Elasticsearch的工作原理、内核级原理，再到动手实战操作Elasticsearch的各种核心功能，到最后可以基于Java开发基本的搜索和分析应用程序。

课程特点如下：

1、基于Elasticsearch最新版本，5.2版本，进行课程的讲解，让大家学好技术后，绝对不会落伍。而市面上的书籍和视频，使用的Elasticsearch版本都非常陈旧，一般都是1.x，或者2.x，即使学了，也完全跟现在最新的版本无法兼容，无法让同学们学以致用。

2、大白话讲解各种复杂知识点，不用太官方和学术的语言照着ppt简单讲解，而是采用与朋友聊天式的方式，进行对话和讲解，尽量采用最通俗的语言来解释各种复杂的技术问题，还有底层原理。

3、课程知识体系设计的足够详细，将一门技术的各个知识点和技术点，全部包含在课程中，一点一点的细致剖析和展开讲解，绝不让大家遗漏任何有用的知识点，尽量做到，课程知识体系完整，系统化，有广度，而且也有深度。比如说本套课程中，既全面包括了从入门使用，到分布式文档系统操作，到搜索引擎操作，到索引管理，最后到Java API使用，这样完整的知识体系。同时还细致到包含很多独家的知识点，比如说Elasticsearch如何突破扩容瓶颈，search timeout机制，如何定位不合法的搜索，等等。

4、包含很多独家的核心知识点和技术，比如乐观锁并发控制，写一致性与quorum机制，bulk api底层性能优化，deep-paging性能问题，大数据量零停机重建索引，等等。

5、课程的原理性讲解足够深入，一直剖析到ES的内核层面，而且几乎所有原理知识点的讲解100%都使用现场一点一点手工画图的方式来剖析和讲解。比如ES容错机制，document数据路由，object类型底层结构，相关度评分TF/IDF算法，doc value，type底层数据结构，内核级数据写入流程，index segment、memory buffer、filesystem cache、flush、commit等内核级原理。

6、大量的上机动手实验，几乎所有功能都会带着大家上机动手实战操作，演练，掌握功能的使用。比如入门级的电商网站商品管理案例，基于版本号进行乐观锁并发控制的实验，mget+bulk批量处理的实验，scoll滚动搜索大量数据的实验，scoll+bulk+alias零停机重建索引的实验，基于Java开发的员工管理案例，等等。

本套课程学完以后能够达到的效果：

1、快速掌握Elasticsearch的各种使用，包括document管理，索引管理，搜索，聚合分析，等等。

2、细致掌握Elasticsearch的各种高级核心知识点，包括乐观锁并发控制，mget+bulk批处理，零停机场景下重建索引，dynamic mapping模板定制，分词器定制，等等。

3、深入理解Elasticsearch的各种核心原理，包括分布式架构原理，分布式文档系统原理，分布式搜索引擎原理，内核级原理。

4、快速掌握基于Java来开发Elasticsearch的简单应用程序，实现包括document增删改查，常见的搜索操作，常见的聚合分析操作。

5、基于上述4点的掌握，可以为更加进一步深入学习Elasticsearch这门技术打好基础。

## 课程目录

http://www.roncoo.com/course/view/03b0916b225f4feb995586ab3e975c8f#boxTwo

## 更多教程

教程不断整理更新中，以上截图仅供参考，如需了解更多视频教程的详细信息请到如下地址查看：

[教程分类说明](https://itvedios.github.io/categories/)：<https://itvedios.github.io/categories/>

## 获取方式

[关于教程、获取方式、温馨提示](https://itvedios.github.io/about/)