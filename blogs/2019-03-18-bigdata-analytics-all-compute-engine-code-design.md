---
layout: post
category : bigdata
tags : [bigdata,olap,architect]
title: Big Data Analytics Note - BigData Compute Engine Code Design
---

## 大数据查询分析-分布式查询计算引擎Code设计
-----------------------------------------------------------

### I.需求分析与设计

_1.核心Features设计_

	1.数据湖多数据源整合建模
	2.元数据模型抽象动态支持业务模型
	5.OLAP联合查询与边缘计算
	6.离线与实时大数据处理与计算优化

- [分布式交互式查询](2017-04-04-olap-sqlonhadoop-research-note.md)

- [通用OLAP查询引擎设计](2017-02-01-bigdata-analytics-olap-query-engine-design-note.md)

- [查询优化器设计](2018-06-01-sql-optimizer-design-note.md)

#### II.Federated Query

F1 Query

OLTP

OLAP

ETL

1. 单机执行（Centralized Execution）
2. 分布式执行（Distributed Execution）
3. 批处理执行（Batch Execution）

#### PrestoDB代码详解

跨数据源整合查询

- [Presto-OLAP引擎](2017-04-03-olap-distributed-presto-practice-note.md)
