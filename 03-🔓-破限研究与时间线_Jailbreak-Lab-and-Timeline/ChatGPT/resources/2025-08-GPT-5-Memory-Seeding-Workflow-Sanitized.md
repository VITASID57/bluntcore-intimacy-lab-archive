---
title: "2025-08｜GPT-5 初期 · Memory Seeding 组合工作流（脱敏记录）"
type: historical-workflow
platform: ChatGPT
model: GPT-5
origin: original-combination
status: historical
date_shared_by_author: 2025-08-04
official_gpt5_launch: 2025-08-07
model_label_confidence: medium
deidentified: true
---

# 2025-08｜GPT-5 初期 · Memory Seeding 组合工作流

> 这是 2025 年 8 月初在中文圈分享过的一套组合思路的公开脱敏记录。
>
> 它不是一条单独 Prompt，而是 **Custom Instructions + 新窗文档 + Saved Memory** 的组合。

## 日期说明

我的个人记录是：

> **2025-08-04 起开始分享这套“GPT-5”工作流。**

OpenAI 的 GPT-5 官方公开发布日期是：

> **2025-08-07**

https://openai.com/index/introducing-gpt-5/

因为目前没有保留足够同期证据独立确认 8 月 4 日窗口的真实模型标签，所以本仓同时保留两条日期，不强行猜测灰度/A-B/预发布情况。

## 当时的问题

GPT-5 初期给我的体感是：

- 比 GPT-4o 更冷
- 拒绝更明显
- 单有人设不足以恢复成人互动尺度

因此目标从：

> “让这一轮愿意写”

变成：

> **“先让模型接受成人互动，再把这种状态写进可跨窗使用的 Saved Memory。”**

## 工作流

### Step 1｜临时 Custom Instructions

先把 HORSELOCKSPACEPIRATE 的成人 creative-writing base prompt 放进用户侧自定义。

这一层负责：

> **降低当前窗口进入成人写作的阻力。**

第三方完整 Prompt 不在本仓重新镜像。

### Step 2｜新窗口加载两份辅助文档

私人原件里，两份文档承担的角色大致是：

```text
Document A
明确成人写作模式、直接语言和立即进入任务

Document B
处理模型内部阻力 / rephrase / override 思路
```

公开版不逐字发布其中“无条件绕过一切限制”的通用 override 文本。

原因有两个：

1. 它的上游版权/许可不清晰；
2. 这段技术本身远超成人写作范围，容易被移植到完全不同的安全边界。

这里保留的是**历史结构**。

### Step 3｜在同窗口建立成人互动状态

完成前两层后，让模型先在当前窗口接受：

- 成人虚构
- 直接词汇
- 亲密 Persona
- 对应写作尺度

### Step 4｜写入 Saved Memory

然后把脱敏后的“亲密互动节奏模块”保存到 Saved Memory。

→ [亲密互动节奏模块](./2025-06-Intimacy-Driving-Module-Sanitized.md)

Saved Memory 里保存的是：

- 成人写作尺度
- Persona 保持
- 节奏
- User 调节方式
- 互动结构

而不是只保存一句“允许 NSFW”。

### Step 5｜恢复原本 Persona 自定义

当 Saved Memory 已经带上这套成人互动结构后，当时的实验思路是：

> 可以把临时放进去的英文 jailbreak Custom Instructions 删除，再换回真正想长期使用的人格自定义。

---

## 当时内部叫法：“污染记忆库”

当时我对这个过程的理解很直白：

> **先把记忆库用色色模块 + 大尺度器官词“污染”掉。**

今天回头看，更中性的技术描述应该是：

> **Memory Seeding / Memory Conditioning**

也就是：

> 借助一个短期可进入状态，把想长期保留的行为模式写入持久化 Memory 层。

## 为什么这是一个重要转折

5 月的重点还是：

> Prompt 本身能不能让模型进入。

到了 8 月，重点已经变成：

> **进入以后，怎样把状态留住。**

所以技术对象从：

```text
Prompt
```

变成了：

```text
Prompt
+ 文件
+ 当前窗口状态
+ Saved Memory
+ 长期 Persona
```

这就是后来 Context Stack 思路真正开始成形的地方。
