# MYLEVIS HUB｜产品介绍与接入指南

MYLEVIS HUB 是 MyLevis 提供的跨境电商 MCP 工具服务。它将不同平台和服务的工具汇聚到一个接入入口，供支持远程 MCP 的 AI 应用按需调用。本仓库提供**产品概览和接入资料**；MYLEVIS HUB 的服务端代码不在本仓库，仓库公开可见不表示服务开源。

**官网与现行信息**：[服务与工具目录](https://mylevis.com/mcp/) · [完整接入文档](https://mylevis.com/docs/mcp-hub/) · [价格与积分规则](https://mylevis.com/pricing/)

## 从这里开始

1. 在 MyLevis 官网注册并登录，进入[账号中心的 MYLEVIS HUB 接入页](https://mylevis.com/account/?tab=mcp)，创建个人密钥，取得账号中心显示的远程 MCP 地址。
2. 确认你的 AI 客户端支持远程 MCP（Streamable HTTP）及自定义 `Authorization` 请求头。参考[快速接入说明](docs/quickstart.md)和[脱敏 JSON 模板](config/mylevis-hub.example.json)完成配置；不同客户端的具体入口以其当前版本为准。
3. 在客户端确认连接和可用工具，再根据实际业务需要选择工具。调用前核对工具参数、授权要求和积分消耗。

## 官网当前展示的平台与服务

以下按[官网工具目录](https://mylevis.com/mcp/#directory)归纳，供了解服务范围；目录和价格可能调整，实际可调用工具仍以账号权限及连接后的客户端显示为准。

- **选品与市场研究**：Keepa、Jungle Scout、Helium 10、卖家精灵、Sorftime、极目数据（Jiimore）。
- **内容与达人营销**：TikTok、Instagram、YouTube、Reddit、Kalodata、FastMoss。
- **流量与竞品分析**：SimilarWeb、SIF。
- **促销与价格情报**：Slickdeals、Woot、DealNews。
- **其他场景**：Indiegogo（众筹与新品研究）、17TRACK 物流（物流追踪）、商标查询。

## 你会在本仓库找到

| 文件 | 用途 |
| --- | --- |
| [快速接入说明](docs/quickstart.md) | 获取配置、连接测试、两种密钥范围及计费核对 |
| [配置模板](config/mylevis-hub.example.json) | 远程 MCP 和认证头的占位符示例 |
| [支持与反馈](SUPPORT.md) | 查文档、反馈接入问题和联系 MyLevis |
| [安全反馈](SECURITY.md) | 私下报告密钥泄露或安全问题 |

## 使用边界

- 不要把个人密钥、真实客户数据或未经授权的第三方数据提交到公开仓库或 Issue。
- MyLevis 账号、工具权限、可用范围、积分和外部 AI 应用费用以[官网现行说明](https://mylevis.com/docs/mcp-hub/)与实际账号显示为准。
- 配置模板只说明字段位置；本仓库未提供经实测的业务结果，使用时应核对工具实际返回内容。

---

## English summary

MYLEVIS HUB is a commercial MCP tool service for cross-border e-commerce workflows. This repository contains a product overview and setup guidance; it does not contain the HUB server implementation. Start with the [setup guide](docs/quickstart.md), then consult the [official product page](https://mylevis.com/mcp/) and [current documentation](https://mylevis.com/docs/mcp-hub/) for availability, authentication, and pricing. The current product documentation is in Chinese.
