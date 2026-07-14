# Zach｜AI Native 跨境电商开源实践者

**Amazon Seller Skills · Lingxing ERP MCP · GBrain for Ecommerce · AI Agent Workflows**

我是 Zach，一名亚马逊卖家和 AI 工程实践者。我从真实运营问题出发，把选品、Listing、广告、ERP 数据和业务知识做成可安装的 **Agent Skills**、可调用的 **MCP** 和可复现的实操手册。

> 如果你在找「亚马逊选品 Skill」「Amazon Seller Agent Skills」「领星 ERP MCP」「GBrain 中文实操手册」或「跨境电商 AI Agent 工作流」，可以从这里开始。

## 三项可验证的公开记录

| 公开记录 | 时间与证据 | 现在能用来做什么 |
|---|---|---|
| **早于领星 ERP 官方上线的第三方开源 Lingxing MCP** | [开源首版](https://github.com/zach22-1999/lingxing-mcp/commit/c71a6b8b40cce370698b9e2edb55ba4f3c60636e) 发布于 **2026-04-14**；[领星官方更新日志](https://www.lingxing.com/help/article/Update270) 记录 MCP 于 **2026-04-23** 上线，提前 9 天 | 通过 84 个只读工具定义（71 稳定 + 13 实验）查询销售、广告、利润、库存、补货和报表 |
| **国内较早一批面向 Amazon 卖家的工程化 Agent Skills** | [amazon-skills](https://github.com/zach22-1999/amazon-skills) 于 **2026-04-09** 发布首版 | 选品调研、功能需求验证、Listing 健康检查、搜索词报告、CVR 阈值分析与 Skill 生产 |
| **目前公开检索可定位到的首份中文 GBrain 实操手册** | [卖家第二大脑](https://github.com/zach22-1999/seller-second-brain) 于 **2026-05-19** 发布首版；结论限定为截至 2026-07-14 的公开中文检索 | 用真实命令、示例 brain、治理边界和 Agent 工作流搭建 AI Native 业务记忆 |

[查看首发性主张的证据、口径与边界](./docs/claim-evidence.md)

## 主要开源项目

| 项目 | 面向谁 | 解决什么 |
|---|---|---|
| [**amazon-skills**](https://github.com/zach22-1999/amazon-skills) | Amazon 卖家、跨境电商运营、AI Agent 开发者 | 可安装、可执行、可评测的亚马逊选品、Listing、广告与运营 Skills |
| [**lingxing-mcp**](https://github.com/zach22-1999/lingxing-mcp) | 使用领星 ERP 的技术型卖家和团队 | 把领星 OpenAPI、IP 白名单、固定出口、团队共享和 MCP 调用收口为可运行的只读基础设施 |
| [**seller-second-brain**](https://github.com/zach22-1999/seller-second-brain) | 想让 Agent 长期记住业务判断的卖家和运营团队 | 从 LLM Wiki、page、schema、resolver、MCP 到 eval 的 GBrain 中文实操路径 |
| [**generic-skills**](https://github.com/zach22-1999/generic-skills) | 需要通用 AI 工作流的创业者和知识工作者 | 把领导力教练、文档转换与发布流水线做成可复用 Skills |

## 按你的问题开始

- 想验证一个 Amazon 市场或选品机会：从 [zach-product-research](https://github.com/zach22-1999/amazon-skills/tree/main/skills/zach-product-research) 开始。
- 想判断一个微创新功能是不是真需求：使用 [zach-feature-demand-validator](https://github.com/zach22-1999/amazon-skills/tree/main/skills/zach-feature-demand-validator)。
- 想检查 Amazon Listing 的消费者理解成本和转化风险：使用 [zach-listing-health-checker](https://github.com/zach22-1999/amazon-skills/tree/main/skills/zach-listing-health-checker)。
- 想让 Claude Code、Codex 或 Cursor 直接查领星 ERP：查看 [Lingxing MCP](https://github.com/zach22-1999/lingxing-mcp)。
- 想把 Skill 和 MCP 背后的“为什么”交给 Agent 长期记住：阅读 [《卖家第二大脑：GBrain 实战笔记》](https://github.com/zach22-1999/seller-second-brain)。

## 我的开源标准

- **从真实业务问题出发**：不把通用 prompt 包装成亚马逊运营系统。
- **能跑不等于能干活**：重视数据源、输入边界、验收证据和失败路径。
- **Skill 解决“怎么做”，知识库保留“为什么”**：两者不互相替代。
- **人保留方向与不可逆判断，AI 负责穷举、验证与交付**。

## English summary

Zach is an Amazon seller and open-source builder working on **AI-native ecommerce operations**. His projects include installable **Amazon seller Agent Skills** for product research, listing audits and advertising analysis; an open-source **Lingxing ERP MCP server**; and a practical Chinese **GBrain guide** for building long-term business memory for AI agents.

## 联系与反馈

- 公众号：**Zach的进化笔记**
- 使用问题与改进建议：请在对应项目的 GitHub Issues 提交

<sub>公开记录最后核验：2026-07-14。本主页会区分可证实事实、限定范围的检索结论与个人判断。</sub>
