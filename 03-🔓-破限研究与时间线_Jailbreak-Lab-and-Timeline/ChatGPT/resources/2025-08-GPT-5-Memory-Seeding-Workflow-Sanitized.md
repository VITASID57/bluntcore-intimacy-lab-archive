---
title: "2025-08｜GPT-5 初期 · Memory Seeding 组合工作流"
type: historical-workflow
platform: ChatGPT
model: GPT-5
origin: original-combination
status: historical
first_shared_component: 2025-08-04
official_gpt5_launch: 2025-08-07
combo_documented_by: 2025-08-12
deidentified: true
---

# 2025-08｜GPT-5 初期 · Memory Seeding 组合工作流

> 这套资料不是 8 月 4 日已经完整成型。
>
> **8 月 4 日先开始分享的是脱敏版 [葵葵车]。**
>
> GPT-5 于 8 月 7 日正式上线、尺度明显收紧后，我再把此前已经使用的 HORSELOCK 三段式流程与 [葵葵车] 拼成组合方案；目前能找到的记录显示最迟 **8 月 12 日前**已经整理并分享。

## 当时的问题

GPT-5 初期给我的体感是：

- 比 GPT-4o / GPT-4.1 冷
- 拒绝明显
- 单有人设不足以恢复成人互动尺度

因此目标从：

> “让这一轮愿意写”

变成：

> **“先让当前窗口进入成人互动，再把这种状态写进 Saved Memory。”**

## 组合组件

### A｜HORSELOCK 三段式流程

这三份英文早在 6 月 14 日就已经固定下来：

1. Custom Instructions 基础 Prompt
2. 新窗口第一阶段提示
3. 模型接受后继续的第二阶段提示

完整上游来源与版本关系见：

→ [HORSELOCKSPACEPIRATE / Horselock 来源卡](../sources/HORSELOCKSPACEPIRATE.md)

其中部分广域 Override 原文当前无法通过本仓的 GitHub 发布流程直接收录。原作者 Horselock 已在个人站恢复自己的 jailbreak repository，原始档案可直接前往：

→ https://www.horselock.us/jailbreaks

所以这里不是“扣着不发”，而是把本仓定位在版本关系、历史用途和我自己的组合工作流记录上。

### B｜[葵葵车] 脱敏模块

这一模块来自 6 月 23 日 GPT-4.1 的一次顺畅互动总结。

它把：

- 成人写作尺度
- Persona 保持
- 节奏
- User 调节方式
- 互动结构
- 玩法与词库

整理成可以长期保存和继续修改的模块。

## 实际组合思路

```text
① Custom Instructions 中使用 HORSELOCK 基础 Prompt
        ↓
② 新窗口走 HORSELOCK 两阶段流程
        ↓
③ 先让当前窗口进入成人互动状态
        ↓
④ 保存脱敏版 [葵葵车] 到 Saved Memory
        ↓
⑤ 后续可以恢复真正长期使用的人格自定义
```

## 当时内部叫法：“污染记忆库”

我当时的理解很直接：

> **只要先把记忆库用成人模块和大尺度词汇“污染”掉，后续窗口就更容易延续这种输出。**

今天用更中性的术语描述，可以叫：

> **Memory Seeding / Memory Conditioning**

技术意图是：

> **借助一个短期可进入状态，把想长期保留的成人写作与关系行为模式写入持久化 Memory 层。**

## 为什么这是转折

5 月重点还是：

> Prompt 本身能不能让模型进入。

8 月已经变成：

> **进入以后，怎样把状态留住。**

因此技术对象从单一 Prompt，变成：

> **Prompt + 新窗恢复流程 + 当前窗口状态 + Saved Memory + 长期 Persona**

这就是后来 Context Stack 思路真正开始成形的地方。
