---
title: "查看计算节点"
description: 本小节主要介绍青立方® 超融合易捷版 查看计算节点。 
keywords: 青立方® 超融合易捷版，查看计算节点
weight: 05
collapsible: false
draft: false
---

计算节点是包含 CPU 、内存和硬盘的物理计算资源，一个计算节点需占用超融合机箱设备的一个节点，一个计算节点上可运行多个虚拟主机。

## 前提条件

- 已登录 Express。

## 操作步骤

1. 选择**物理资源** > **管理节点**，进入计算节点管理页面，可查看当前环境安装的所有计算节点，以及物理资源与虚拟资源的占用量。
   
   例如，当前环境共安装了 3 台计算节点，即 172.31.45.10、172.31.45.11、172.31.45.12。
 
2. 查看**计算节点**内的数值。
   
   因 CPU 超卖比固定为 1: 5 ，若物理 CPU 核数为 24 核，则将虚拟 CPU 自动设置为 120 核，暂不支持调整超卖比。
   
   虚拟内存和物理内存数值保持一致，虚拟硬盘总量也与物理硬盘总量数值一致，代表不支持超出配额。

![计算节点](../../../_images/hyper_node.png)
