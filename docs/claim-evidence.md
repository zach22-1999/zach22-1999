# 公开记录与首发性主张证据

> 最后核验：2026-07-14

这份记录用来约束 GitHub 主页、项目 README、采访和对外内容中的“首发”表述。目标不是把每个项目都写成第一，而是让真正成立的领先记录经得起反向搜索。

## 结论摘要

| 主张 | 证据等级 | 建议表述 |
|---|---|---|
| 领星 ERP 官方 MCP 上线前已开源第三方 Lingxing MCP | 强：双方都有可定位日期的一手记录 | “我们的开源 Lingxing MCP 比领星官方 MCP 上线早 9 天” |
| 开源 Lingxing MCP 的当前公开工具面更广 | 强，但必须带日期和口径 | “截至 2026-07-14，开源仓库包含 84 个只读工具定义，领星官方帮助页公开列出 29 个工具” |
| 最早开源的工程化选品 Skill | 不成立：已找到更早的公开同类仓库 | “国内较早一批面向 Amazon 卖家的工程化 Agent Skills” |
| 全网第一份 GBrain 实操手册 | 中强：在当前公开中文检索范围内未找到更早反例 | “目前公开检索可定位到的首份中文 GBrain 实操手册” |

## 1. Lingxing MCP：早于官方 9 天

### 开源仓库记录

- 仓库：[github.com/zach22-1999/lingxing-mcp](https://github.com/zach22-1999/lingxing-mcp)
- 首个公开提交：[`c71a6b8`](https://github.com/zach22-1999/lingxing-mcp/commit/c71a6b8b40cce370698b9e2edb55ba4f3c60636e)
- 提交时间：2026-04-14 18:01:18 +08:00
- 提交说明：`feat: initial public release of lingxing mcp`

### 领星官方记录

- 一手来源：[领星 ERP 2026 年 4 月版本更新](https://www.lingxing.com/help/article/Update270)
- 官方日志：2026-04-23 ERP V3.8.2 上线
- 日志原文事实：“AI 助手：领星 MCP 上线”

两个公开日期相差 9 天，因此“早于官方上线”成立。为避免歧义，不把它写成“领星第一个 MCP”；更精确的说法是“早于官方上线的第三方开源 Lingxing MCP”。

## 2. Lingxing MCP：84 个只读工具定义

对当前公开代码中 `LingxingMCPApplication.list_tools()` 的实际返回结果计数：

- 总数：84
- 稳定工具：71
- `lingxing_exp_*` 实验工具：13
- 代码入口：[`lib/lingxing_openapi/mcp.py`](https://github.com/zach22-1999/lingxing-mcp/blob/main/lib/lingxing_openapi/mcp.py) 与 [`endpoint_specs.py`](https://github.com/zach22-1999/lingxing-mcp/blob/main/lib/lingxing_openapi/endpoint_specs.py)

[领星官方 MCP 帮助页](https://www.lingxing.com/help/article/mcp) 在 2026-07-14 公开列出 29 个 Tool。这个对比只证明“当前公开工具目录更广”，不直接证明每个同名工具的返回字段更齐全。两者定位也不同：本项目坚持只读、OpenAPI 和固定出口工程路线，官方 MCP 还包含若干写操作。

## 3. Amazon 选品 Skill：不写绝对“第一”

### 我们的发布记录

- 仓库：[github.com/zach22-1999/amazon-skills](https://github.com/zach22-1999/amazon-skills)
- 首个公开提交：[`5fa17ee`](https://github.com/zach22-1999/amazon-skills/commit/5fa17ee500e7927e995338ae7b1e1e8d7cf2f1b5)
- 提交时间：2026-04-09 15:01:59 +08:00
- 仓库中的选品入口：[`zach-product-research`](https://github.com/zach22-1999/amazon-skills/tree/main/skills/zach-product-research)

### 反向检索结果

GitHub 代码与仓库检索可找到 2026 年 3 月已建立的 Amazon product research / Sorftime / Agent Skill 同类仓库。因此，目前证据不支持“全网最早开源工程化选品 Skill”。

可以稳定成立的差异化是：从真实数据源出发，同时提供 Skill 入口、依赖、输出契约、安装文档和发布闸门。建议对外表述为“国内较早一批面向 Amazon 卖家的工程化 Agent Skills”。

## 4. GBrain 实操手册：限定中文公开检索范围

### 我们的发布记录

- 仓库：[github.com/zach22-1999/seller-second-brain](https://github.com/zach22-1999/seller-second-brain)
- 首个公开提交：[`21fbba5`](https://github.com/zach22-1999/seller-second-brain/commit/21fbba55d7afb93d5b5645b628fe5d5797897a35)
- 提交时间：2026-05-19 16:09:07 +08:00
- 形态：不是单篇介绍，而是同时提供 Markdown、HTML、PDF、真实命令输出和示例 brain 的中文实操手册。

### 检索边界

在 2026-07-14 使用“GBrain 实操手册”、“GBrain 中文教程”、“GBrain 实战指南”及 GitHub 定向检索，未找到 2026-05-19 之前发布的中文 GBrain 实操手册。能找到一篇 2026-05-23 发布的繁体中文入门文章，时间晚于本手册。

因为“全网第一”无法穷尽所有未收录页面、私域内容和后续补发时间，对外统一用带范围的说法：

> 截至 2026-07-14，《卖家第二大脑》是目前公开中文检索可定位到的首份 GBrain 实操手册。

## 口径维护规则

1. 所有“首发”表述都链接到一手时间记录。
2. 检索性结论必须带日期和检索范围。
3. 发现更早的反例时，立即收窄口径，不通过重新定义“工程化”来维持第一。
4. 工具数、字段数和官方功能会变，每次重要对外发布前重新核对。
