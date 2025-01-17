---
title: "主机应用防火墙规则"
description: 本小节主要介绍青立方® 超融合易捷版 主机应用防火墙规则。 
keywords: 青立方® 超融合易捷版，主机应用防火墙规则
weight: 15
collapsible: false
draft: false
---


本小节主要介绍如何应用防火墙到主机。

## 操作步骤

1. 登录 青立方® 超融合易捷版。
2. 选择 **虚拟资源** > **安全**，进入安全管理列表。
3. 勾选目标防火墙，点击**应用防火墙规则**，弹出选择主机窗口。
4. 选择一台或者多台主机。如下示例勾选 `docs-demo` 和 `ip-test` 将两台主机绑定至当前防火墙规则。

   ![选择主机](../../../_images/firewall_host.png)

5. 确认配置信息无误后，点击 **确定**，返回防火墙列表页面

   进入防火墙详情页面，查看操作日志，即可确认该条规则已绑定两台主机。

   ![选择主机](../../../_images/firewall_host2.png)
