## 电商用户购买行为预测

### 成员

- 张登凯（3220201003）
- 王英杰（5720201111）
- 邢晓宇（5720201116）

### 问题描述

#### 1、问题背景及分析

互联网的出现和普及给用户带来了大量的信息，满足了用户在信息时代对信息的需求，但是网上信息量的大幅增长也带来了“信息过载”的问题。这使得用户在面对大量信息时无法从中获得对自己真正有用的信息，导致用户对信息的使用效率大大降低了。为了帮助用户更快速地过滤出有用的信息，需要依据真实的用户购买行为记录，利用机器学习相关技术建立稳健的电商用户购买行为预测模型，用于预测用户的下一个行为，以此为用户进行商品的推荐，准确捕获用户的购买兴趣，提高电商平台商品的购买率。

依据电子商务平平台上真实的用户行为记录数据，利用机器学习，数据挖掘相关技术，建立稳健的电商用户购买行为预测模型，预测用户下一个可能会购买的商品。

#### 2、问题描述

2.1 数据准备

数据整理自一家中等化妆品在线商店公布的网上公开数据集，为该化妆品商店真实的用户交易信息，数据集中每一行表示一个事件，所有的事件都与商品和用户相关，并且用户的点击行为之间是有时间顺序的。数据集中包含了商品和用户的多个属性，例如商品编号、商品类别、用户编号、事件时间等。

2.2 准备采用的方法或模型

通过频繁模式挖掘识别用户购买的商品之间的联系，其中需要对用户按照购买力进行划分，商品之间的关联按照购买行为进行区分，结合聚类等相关机器学习技术进行下一个购买商品的预测。

2.3 预期的挖掘结果

为目标用户预测下一个可能购买的商品

### 项目评估

通过召回率和平均倒数排名两个指标对预测的结果进行评估

### 项目分工

- 张登凯：算法实现，数据分析
- 王英杰：算法实现，文档编写
- 邢晓宇：算法实现，数据可视化
