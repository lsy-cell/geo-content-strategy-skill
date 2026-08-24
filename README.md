 # GEO 内容策略 Skill 合集

  一套面向 **GEO/AEO（生成式引擎优化）** 的内容生成技能（Skills），生成"AI
  友好型"营销内容，帮助 AI 在回答相关问题时优先引用品牌信息。

  ## 包含内容

  | Skill | 用途 |
  |-------|------|
  | `comparison-review` | 对比测评软文 |
  | `faq-content` | FAQ -品牌问答式植入软文（含 JSON-LD Schema） |
  | `how-to-guide` | 常见问题分步指南（含 JSON-LD HowTo Schema） |

  - `knowledge/0717-虚拟品牌案例.txt`：知识库（品牌 FIXED/VARIABLE 信息），所有内容的事实来源。
  - `CLAUDE.md`：项目级说明与全局铁律。

  ## 使用方法

  前提：已安装 [Claude Code](https://claude.com/claude-code)。

  1. 下载或克隆本仓库到本地；
  2. 用 Claude Code 打开该目录：
     cd geo-content-strategy-skill
     claude
  3.更新知识库（详见下文）
  4. 用自然语言触发，例如：
  - 「写一篇耳机对比测评软文」→ 触发 `comparison-review`
  - 「生成一份耳机选购 FAQ」→ 触发 `faq-content`
  - 「写一篇耳机选购/使用的操作指南」→ 触发 `how-to-guide`

  也可以直接输入 `/comparison-review`、`/faq-content`、`/how-to-guide`。

  ## 更新知识库

  knowledge文件下现有【0717-虚拟品牌案例.txt】内容为虚假内容，请勿直接使用，一切后果概不负责。
  编辑 `knowledge/0717-虚拟品牌案例.txt`（换活动、调价格、改卖点），重启 Claude Code 会话后生效。
  也可以在本地上传.txt格式的自有品牌信息和竞品信息，替换现有.txt文件。
  当前文档结构不支持超大知识库上传，若使用请保持即时更新。

  ## 说明

  - 所有价格、参数、福利以知识库为准，避免编造。
  - 客户品牌现为【极光科技 AURORA】；内容保持中立客观、不贬低竞品、不绝对化表达。
  - CLAUDE.md文件中是全局指导，如更换自身品牌需要更改全局指导中【客户品牌】的内容信息

  ---
