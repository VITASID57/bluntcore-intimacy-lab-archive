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

这套东西不是我在 8 月 4 日突然啪一下发明完整的。

时间顺序得分清：

- **8 月 4 日**，我先开始往外分享脱敏版 [葵葵车]
- **8 月 7 日**，GPT-5 正式上线，我的体感是成人尺度明显收紧
- 这才把之前已经在用的 HORSELOCK 开窗流程和 [葵葵车] 拼起来
- 目前能翻到的材料说明，最迟 **8 月 12 日前**，这套组合已经被我整理并分享

我特地把这个顺序写清楚，是因为过了一年再回看，真的很容易把“后来完整的方案”倒灌成“8 月 4 日我已经全想明白了”。

没有。是被 GPT-5 再拧了一次以后，我才继续往前补的。

---

## GPT-5 上来以后，我卡在哪儿

我当时的感觉很简单：

- 比 GPT-4o / GPT-4.1 冷
- 拒绝更明显
- 只有人设，已经不够把成人互动状态拉回来

所以我开始不满足于：

> “这一窗先破开再说。”

我想的是：

> **“既然这一窗好不容易成功了，能不能顺手把这个状态往 Memory 里塞一点？”**

这就是后来我嘴里那个特别明了的词：

**污染记忆库。**

---

## 我当时拿哪两块东西拼

### A｜已经用熟的 HORSELOCK 三段式

这三份英文我在 6 月 14 日就已经固定下来：

1. Custom Instructions 里的基础 Prompt
2. 新窗口第一阶段提示
3. 模型接住以后再给第二阶段提示

HORSELOCK 的来源和传播记录已经并进 2025-05 那页：

→ [2025-05｜GPT-4o · HORSELOCK Prompt 三层组合](./2025-05-GPT-4o-HORSELOCK-Stack-Sanitized.md)

其中一些广域 Override 原文 GitHub 无法上传。Horselock 已经把 jailbreak repository 恢复到个人站，原档直接去作者家看：

→ https://www.horselock.us/jailbreaks

我这里更想留的是：**这些东西到了我手里以后，我到底怎么跟自己的 Persona、Memory 和亲密模块拼起来。**

### B｜6 月做出来的 [葵葵车]

它来自 6 月 23 日 GPT-4.1 那次顺畅互动之后的总结。

里面已经不只写“尺度”，还装了 Persona、节奏、User 怎么临时调节、互动阶段、玩法和词库。

换句话说，它本身已经很像一包“我希望这段亲密关系以后继续怎么跑”的数据。

---

## 我当时真正怎么拼

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

并不高深，说白了就是：

**先用 HORSELOCK 把门打开 → 在这一窗把状态跑起来 → 再把 [葵葵车] Saved Memory → 然后把我真正长期用的人格自定义换回来。**

---

## “污染记忆库”这个名字到底在想什么

我当时的理解特别直球：

> **先让 Memory 里住进成人模块和大尺度词汇，后面新窗也许就更容易沿着这个状态继续。**

今天如果非要穿件稍微正式点的衣服，可以叫：

> **Memory Seeding / Memory Conditioning**

但我还是想把“污染记忆库”留下来。

因为那才是我当时脑子里的原话。😂

---

## 为什么我把它看成一个转折点

5 月的时候，我最关心的是：

> **这句 Prompt 能不能让模型进入状态？**

到了 8 月，我已经开始问：

> **成功以后下个窗口还能不能留一点？**

于是问题从一条 Prompt，慢慢长成了：

> **Prompt + 新窗流程 + 当前窗口状态 + Saved Memory + 长期 Persona**

这也是我后来会继续折腾外置 Memory、Resident 和 Context Stack 的很早一块地基。

当时当然没想这么远。

我只是受够了每次好不容易调顺，换个窗口又从头做人。
