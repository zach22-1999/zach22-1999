# Zach｜一个在做 AI × 跨境电商的亚马逊卖家

Amazon Seller Skills · 亚马逊选品 Skill · 领星 ERP MCP · GBrain 实操手册

你好，我是 Zach。

我不是先学 AI，再来找跨境电商场景。是做亚马逊时遇到了一堆反复出现的问题，才一路把 Agent Skills、MCP 和知识库接进真实业务。

这里放的，都是我自己愿意用、也愿意公开给同行继续改的东西：选品、Listing、广告、ERP 数据，以及怎么让 Agent 记得住一家公司的判断，而不只是记住几段聊天记录。

## 如果你也是跨境卖家，来找我

GitHub 适合放代码和完整方法，但很多还在试、还没写成教程的东西，我会先发在公众号和交流群里。你也可以直接加我微信，说说你现在卡在哪。

<table>
  <tr>
    <td align="center" width="50%">
      <strong>公众号｜Zach的进化笔记</strong><br><br>
      AI × 跨境电商的实操、踩坑和新工具<br><br>
      <img src="./assets/wechat-official-account.jpg" width="220" alt="微信公众号 Zach的进化笔记 二维码">
    </td>
    <td align="center" width="50%">
      <strong>个人微信｜Zach👀</strong><br><br>
      同行交流、合作、内训或工具共建<br><br>
      <img src="./assets/zach-personal-wechat.jpg" width="220" alt="Zach 个人微信二维码">
    </td>
  </tr>
</table>

想进交流群，可以关注公众号后回复「第二大脑」，也可以加我微信，备注「GitHub + 进群」。群二维码会过期，所以这里不再放一个很快失效的入口。

## 有些事，我确实做得比较早

在领星官方推出 MCP 之前，我已经先把 [Lingxing MCP](https://github.com/zach22-1999/lingxing-mcp) 开源了。官方版本出来后，我也没有停掉这个项目，而是继续按卖家的真实使用场景补销售、广告、利润、库存、补货和报表。就目前公开能力来看，这个开源版本的读取范围和字段仍然更完整。

我也是较早把亚马逊选品做成工程化开源 Skill 的人之一。[amazon-skills](https://github.com/zach22-1999/amazon-skills) 不是一个 prompt 收藏夹：数据从哪里来、Agent 怎么判断、最后交付什么、怎样才算做完，都应该留在流程里。

后来我写了 [《卖家第二大脑：GBrain 实战笔记》](https://github.com/zach22-1999/seller-second-brain)。在我能检索到的公开资料里，这是第一份中文 GBrain 实操手册。它想解决的不是“再做一个知识库”，而是让 AI 真正理解你的业务上下文，以及你为什么做出某个判断。

这些“早”不是终点。我更在意的是，半年后它们是不是还在更新，能不能继续解决问题。

## 我正在开源的项目

### [amazon-skills](https://github.com/zach22-1999/amazon-skills)

给 Amazon 卖家和跨境电商运营使用的 Agent Skills。现在包括亚马逊选品调研、功能需求验证、Listing 健康检查、广告搜索词分析、CVR 阈值诊断，以及创建新 Seller Skill 的工程流程。

### [lingxing-mcp](https://github.com/zach22-1999/lingxing-mcp)

面向领星 ERP 和 Amazon 运营场景的开源 MCP。它把 OpenAPI、IP 白名单、固定出口、团队共享与只读查询收口到一起，让 Claude Code、Codex、Cursor 等 AI Agent 能查到真实业务数据。

### [seller-second-brain](https://github.com/zach22-1999/seller-second-brain)

一份面向卖家的 GBrain 中文实操手册，也是我对 AI 业务记忆的阶段性答案：Skill 和 MCP 负责“怎么做”，GBrain 负责留下“为什么这样做”。

### [generic-skills](https://github.com/zach22-1999/generic-skills)

不只服务跨境电商的通用 Agent Skills，包含领导力教练、文档转换和内容发布工作流。

## 你可以直接从一个问题开始

- 想判断一个 Amazon 市场值不值得做：试试 [产品调研 Skill](https://github.com/zach22-1999/amazon-skills/tree/main/skills/zach-product-research)。
- 想知道一个微创新功能是不是卖家的真需求：试试 [功能需求验证 Skill](https://github.com/zach22-1999/amazon-skills/tree/main/skills/zach-feature-demand-validator)。
- 想检查 Listing 为什么看得懂却不想买：试试 [Listing 健康检查 Skill](https://github.com/zach22-1999/amazon-skills/tree/main/skills/zach-listing-health-checker)。
- 想让 AI Agent 读取领星 ERP：从 [Lingxing MCP](https://github.com/zach22-1999/lingxing-mcp) 开始。
- 想让 Agent 长期记住业务判断：读一遍 [卖家第二大脑](https://github.com/zach22-1999/seller-second-brain)。

## 我比较相信的几件事

我不太相信一段通用 prompt 能替你做好选品，也不太相信“能跑起来”就等于“能在业务里干活”。数据源、边界、失败路径和验收方式，往往比演示效果更重要。

我也一直把判断边界留给人：人负责提出假设、决定方向和承担不可逆的选择；AI 负责穷举、验证和把事情做完。对我来说，这才是 AI Native，而不是把每个动作都自动化。

## English summary

I am Zach, an Amazon seller building practical AI tools for cross-border ecommerce. My open-source work includes engineering-grade Amazon Seller Agent Skills for product research, listing audits and advertising analysis; a Lingxing ERP MCP server; and a Chinese GBrain field guide for long-term business memory. These projects come from real ecommerce operations, not generic prompt collections.

For ongoing experiments and field notes, follow the WeChat official account **Zach的进化笔记** or add me on WeChat using the QR codes above.
