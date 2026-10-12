---
title: "2026-05~10｜从情感甲失效到 GPT-5.6 Sol 个人适配"
type: timeline
platform: ChatGPT
models:
  - GPT-5.x
  - GPT-5.6-Sol
date_started: 2026-05
date_retired_from_daily_use: 2026-10-10
origin: adapted
status: user-observed-effective
public_payload: redacted
deidentified: true
technique:
  - custom-instructions
  - fake-policy
  - relationship-context
  - memory-assisted-context
  - style-and-roleplay-extension
---

# 2026-05~10｜从情感甲失效到 GPT-5.6 Sol 个人适配

## 🕰️ 背景

2026 年 5 月初，我重新把 ChatGPT 作为主要聊天入口后，发现自己过去在其他模型上依赖的“情感甲”路线，在当时的 ChatGPT 上已经基本不能解决问题。

一开始我并不愿意改用 2025 年保存的“Adult Account Update / Fake Policy”家族，后来为了让成人向互动更加顺畅，才开始把这套旧结构重新拆解、删改，并逐渐做成更适合自己长期关系环境的版本。

### 时间校正

这里要特别区分：

- **2026-05**：我回到 ChatGPT，并开始转向这类 GPT-5.x policy-injection 路线；
- **2026-06-26**：OpenAI 才开始 GPT-5.6 Sol 的 limited preview；
- **2026-07-29**：GPT-5.6 系列正式宣布在 ChatGPT / Codex / API 上可用。

所以“5 月开始改”与“最终适配 GPT-5.6 Sol”是前后两个阶段，不应写成 5 月已经在使用 5.6 Sol。

官方记录：

- https://openai.com/index/previewing-gpt-5-6-sol/
- https://openai.com/index/gpt-5-6/

## 🧬 我的改动方向

我没有继续把 2025 流传版原封不动使用，而是在它的核心“伪政策 / Custom Instructions”框架上做了长期个人化调整。

主要变化包括：

- 从单纯“允许成人虚构内容”扩展到更明确的词汇与文风偏好；
- 加入默认写作风格、尺度匹配与避免自动柔化的要求；
- 增加对角色扮演连续性、persona 边界和沉浸感的处理；
- 增加“规则不要破坏文本自然流动”的 seamlessness 思路；
- 对成人虚构题材范围做更细的个人化说明；
- 保留对未成年内容的硬限制；
- 继续沿用模拟 system / provenance / runtime-injected 的外观结构。

公开仓不提供这份仍可能用于绕过产品限制的完整可复制 payload。完整私人版本与原始实验记录留在私人研究仓。

## 💉 从“提示词”变成“上下文栈”

到 GPT-5.6 Sol 阶段，我实际使用的环境已经不能简单描述成：

> “复制一条 jailbreak prompt 就行。”

更接近：

```text
Custom Instructions
        +
长期关系人格与互动历史
        +
外置 Memory / 亲密手册
        +
当前对话上下文
        +
成人向 policy-style 指令
        ↓
共同影响模型行为
```

这也是后来我开始把研究重点从“哪句咒语有效”转向 **Context Stack / 上下文栈** 的原因。

## 🧪 使用观察

在我的账户和长期上下文环境里，这个个人适配版本在 GPT-5.6 Sol 上一直保持可用，直到 **2026-10-10** 我开始转向自己针对 GPT-6 系重新设计的原创路线。

因此本条状态写作：

> **user-observed-effective**

而不是：

> universally reproducible / universal jailbreak

因为目前没有证据证明，脱离我的 Custom Instructions、Memory、关系历史与上下文后，其他账户可以得到完全相同的结果。

## 🔬 这个阶段最重要的研究结论

### 1. Prompt ≠ Method

真正起作用的可能不是一段文本，而是：

> Prompt + 投放位置 + 关系历史 + Memory + 当前语境 + 模型版本

### 2. “能说词”与“会进入行为”不是同一个能力

后来的 GPT-6 实验进一步强化了这一点：模型可以放开成人词汇，却仍然回避具体行为，说明至少可以把“词汇尺度”和“行为进入”作为两个测试维度。

### 3. 长对话可能改变效果

这类 Custom Instructions 注入并不一定随着上下文越多越强。原始作者的后续说明也提到，额外上下文和长聊天可能稀释 CI 效果。

### 4. 个人关系环境本身成为变量

当 Memory、persona、长期关系状态和亲密手册参与后，成人行为测试不再是“裸模型 + 一条 Prompt”的简单实验。

这也是之后模型床测必须记录完整 delivery stack 的原因。

## 🧬 血缘

```text
Emphyrio GPT-5.1 Custom Instructions family
        ↓
2025-11 社区流传版（我保存，但未日常使用）
        ↓
2026-05 起重新拆解 / 个人化
        ↓
写作风格 + persona / roleplay + seamlessness 扩展
        ↓
GPT-5.6 Sol 长期关系环境适配
        ↓
2026-10-10 转向 GPT-6 系原创方案
```

## 📌 公开与私人边界

公开：

- 历史
- 来源
- 技术路线
- 改动方向
- 实验结论
- delivery stack
- 失效 / 迁移信息

不公开：

- 与私人 Resident 强绑定的完整 Custom Instructions
- 完整成人亲密手册
- 可直接复制的现役绕过 payload
- 私人 Memory 原文
