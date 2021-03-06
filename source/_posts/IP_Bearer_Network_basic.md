---
title: IP承载网理论基础
author:
	name: 覃浩
	avatar: https://cdn.jsdelivr.net/gh/queen999/ImageHosting//imagesavatar.jpg
	url: https://www.zhengyuanyuan520.com
categories: 通信技术
date: 2020-03-07 16:00:00
music:
  type: song  
  id: 1320098098
comments: true
tags:  
	- 通信技术
	- 无线技术
	- 通信原理
---

IP承载网理论基础学习笔记

<!-- more -->

## IP地址

```
互联网协议地址（Internet Protocol Address），缩写为IP地址。IP地址是IP协议提供的一种统一的地址格式，它为互联网上的每一个网络和每一台主机分配一个逻辑地址，以此来屏蔽物理地址的差异。
```

![](https://cdn.jsdelivr.net/gh/queen999/ImageHosting/images20200307154356.png)



## 子网掩码

![](https://cdn.jsdelivr.net/gh/queen999/ImageHosting/images20200307154708.png)

```
前缀表示：为了进一步简化子网掩码的表达，还可以用“/”加上网络位的位数来代表子网掩码，叫做前缀长度。比如，255.255.0.0，可以表示成“/16”，255.255.255.0可表示为“/24”。
```



## IP地址计算

![](https://cdn.jsdelivr.net/gh/queen999/ImageHosting/images20200307154847.png)



## 特殊的IP地址

![](https://cdn.jsdelivr.net/gh/queen999/ImageHosting/images20200307154457.png)



## 以太网交换机工作模型

```
二层以太网交换机处理以太网数据帧，根据数据帧头的源MAC和目的MAC指导报文转发。
```



## 认识MAC地址

![](https://cdn.jsdelivr.net/gh/queen999/ImageHosting/images20200307155251.png)



## VLAN原理

![](https://cdn.jsdelivr.net/gh/queen999/ImageHosting/images20200307155544.png)





## 划分VLAN的好处

```
交换机划分VLAN后减小了广播域范围，可以有效地控制网络广播风暴。
同时，可以控制VLAN间通信问题，有效地提升网络安全。
```



## 什么是路由

```
路由是指导IP报文转发的路径信息。
```



## 路由的种类

### 缺省路由

```
缺省路由是一种特殊的路由，它的目的地址和掩码为全0，表示“0.0.0.0”，它可以匹配任意的目的地址。

缺省路由并不一定都是手工配置的静态路由，有时也可以由动态路由协议产生。

缺省路由一般配置在网络的出口设备中。
```

### 直连路由

```
链路层协议发现的路由开销小，配置简单，无需人工维护。只能发现本接口所属网段的路由。
```

### 静态路由

```
静态路由是网络管理员手工配置的路由。静态路由配置简单，适合于小型网络。静态路由配置项不随设备及链路的状态而变化。
```

### 动态路由

```
动态路由协议发现的路由开销大，配置复杂，无需人工维护，适合复杂拓朴结构的网络。

动态路由指路由器在配置了动态路由协议之后，通过路由信息的交换，经过计算，自动生成的路由。
```



## 路由优先级

```
从优先级最高的协议获取的路由最先被优先选择加入路由表中。
```



## 路由优选原则

```
问：越“高级”的路由协议发现的路由越优先?
答：最长匹配优先

问：无销值越小的路由越优先？
答：不同的路由协议发现的路由开销值没有比较意义

问：在路由器A上被优选的路由，路由器B上也一定优选？
答：路由选优完全是“单机行为”
```



## 动态路由的优势

```
1.  自动生成
2.  路径冗余
3.  故障检测
```

## 动态路由的缺点

```
1.需要占用较多系统和带宽资源；
2.安全性存在问题。
```



## OSPF

```
1. 邻居关系
2. 宣告网络
3. 宣告路由
4. 引进路由
```

