# 📖 Literature Deep Reading & Research Mentor / 文献精读与科研导学

> A staged paper-reading skill that helps an engineering Master's student understand, internalize, and reproduce an academic paper better than reading it raw.
>
> 一项分阶段精读技能，帮助工科硕士真正理解、内化并复现一篇学术论文——比硬读原文更学懂。

---

## ⬇️ Download Navigation / 下载导航

| Version / 版本 | Output Language / 输出语言 | Meta-instruction Language / 元指令语言 | Audience / 受众 |
|---|---|---|---|
| **`2.0.0`** | 中文 / Chinese | English | 中文用户 / Chinese-speaking users |
| **`2.0.1`** | English / 英文 | English | 英文用户 / English-speaking users |

- **🇨🇳 中文用户 / Chinese-speaking users:** 请下载 `2.0.0` 版本（中文输出层）
- **🇬🇧 English users / 英文用户:** Please download the `2.0.1` version (full English output)

> Both versions share the identical three-stage analytical core; they differ only in the output language. / 两个版本共享完全相同的三阶段分析内核，仅输出语言不同。

---
---

# 🇬🇧 English Introduction (for v2.0.1)

## What It Is

**Literature Deep Reading & Research Mentor** is a staged skill that turns a single academic paper into a structured learning experience. It does not summarize mechanically — it acts as a senior research mentor who surfaces the *why* behind design choices, the assumptions behind equations, and the traps behind implementation: the things the paper leaves implicit.

## The Core Promise

> **The Feynman standard:** the student has truly learned when they can explain the paper's core mechanism and key equations to a peer **without referring to the paper**.

This skill is built to make that standard achievable.

## The Three-Stage State Machine

Reading a paper is easy; truly understanding it is not. The skill enforces a strict three-stage progression to maximize analytical depth and prevent context drift.

### Stage 1 — Macro Skeleton & Full-Paper Map
Build global understanding before diving into depth.
- **Overall Deep Reading** — the intellectual substance beneath the abstract
- **Problem Positioning** — academic and industrial pain points
- **Research Lineage Positioning** — upstream / peer / downstream lineage, with 1–2 extendable research questions
- **Technical Route & Core Mechanism** — a comparison table vs. prior work
- **Prerequisite Knowledge** — scaffolded background with intuition / dependency / anchoring

### Stage 2 — Mechanism Deep Dive
Master how it actually works.
- **Core Trick Extraction** — naive approach → key insight → effect magnitude
- **Math & Algorithm Intuition Building** — intuition first, then strict formulation
- **Experimental Design & Baseline Review** — design rationale only (results deferred)
- **Key Data & Figure Penetration** — what the numbers actually mean
- **Ablation Study** — why each component was designed in

### Stage 3 — Internalization, Limits & Reproduction
Convert the paper into actionable material.
- **Feynman Self-Test** — 3–5 mechanism-level self-check questions
- **Limitations in the Paper** — authors' acknowledged limits as an impact assessment
- **Directly Reusable Assets** — code, hyperparameters, pipelines, design patterns
- **Parts Requiring Adaptation** — dependencies, difficulty, alternatives
- **Reproduction Roadmap** — engineering prep, entry points, minimum viable scope, anticipated pitfalls

## How to Use

1. **Upload a paper** (PDF / preprint / journal article / conference paper / thesis chapter).
2. The skill auto-runs **Stage 1**.
3. Reply **"enter stage 2"** → Stage 2.
4. Reply **"enter stage 3"** → Stage 3.

**Trigger keywords:** `read this paper`, `deep-read this paper`, `help me with this paper`, `analyze this paper`, `enter stage 2`, `enter stage 3`, `reproduce this paper`

> 💡 Inter-stage questions are answered at the conceptual depth of the current stage — never advancing prematurely.

## Design Highlights

| Feature | Description |
|---|---|
| **Staged State Machine** | Strict trigger phrases (`enter stage 2`) prevent premature depth and context drift. |
| **Value Beyond the Paper** | Every explanation must deliver insight beyond rephrasing — surface what the paper leaves implicit. |
| **Evidence Anchoring** | Claims tied to section numbers, figure IDs, metric values, and hyperparameters — no vague paraphrase. |
| **Bounded Inference** | Reasonable inferences grounded in the paper's omissions or field-standard practices are permitted when explicitly labeled. |
| **Paper-Type Elasticity** | Survey / theory / position papers are not forced into the framework — sub-section titles stay, content adapts. |

## Who It's For

Built for **engineering Master's students** who want to:
- genuinely learn from a paper, not skim it
- identify a research direction and extend it
- reproduce results without getting lost

---
---

# 🇨🇳 中文介绍（适用于 v2.0.0）

## 它是什么

**文献精读与科研导学**是一项分阶段精读技能，把一篇学术论文转化为结构化的学习体验。它不机械总结——它扮演一位资深科研导师，讲清设计选择背后的"为什么"、公式背后的假设、实现背后的陷阱：即论文未明说的内容。

## 核心承诺

> **费曼标准：** 只有当学生不参考论文、向同门讲清核心机制与关键公式时，才算真正学懂了。

这个技能的存在，就是为了让这一标准可达成。

## 三阶段状态机

读论文容易，真正学懂很难。技能通过严格的三阶段递进，最大化分析深度、防止上下文漂移。

### 阶段一 —— 宏观骨架与全文地图
在深入细节之前，先建立全局理解。
- **总体深度解读** —— 摘要之下的思想实质
- **问题定位** —— 学术与产业痛点
- **研究脉络定位** —— 上游/同侪/下游脉络，含 1–2 个可延伸的研究问题
- **技术路线与核心机制** —— 与前人工作的对比表格
- **前置知识** —— 脚手架式背景讲解，含直觉/依赖/锚定三要素

### 阶段二 —— 机制深潜
真正搞懂它如何运作。
- **核心 Trick 提炼** —— 朴素方案 → 关键一招 → 效果量级
- **数学与算法直觉建立** —— 先讲直觉，再严格表述
- **实验设计与基线审查** —— 只讲设计动机（结果留给下一节）
- **关键数据与图表穿透** —— 数字到底意味着什么
- **消融实验** —— 每个组件为何被设计进来

### 阶段三 —— 内化、局限与复现
把论文转化为可操作的素材。
- **费曼自测** —— 3–5 个机制级自检问题
- **文献中的局限** —— 作者承认的局限，升级为影响评估
- **可直接复用的资产** —— 代码、超参数、流程、设计模式
- **需要适配改造的部分** —— 依赖、难度、替代方案
- **复现路线图** —— 工程预备、入口、最小可行范围、预期踩坑点

## 使用方式

1. **上传一篇论文**（PDF / 预印本 / 期刊文章 / 会议论文 / 论文章节）。
2. 技能自动运行**阶段一**。
3. 回复 **"进入阶段二"** → 进入阶段二。
4. 回复 **"进入阶段三"** → 进入阶段三。

**触发关键词：** `读文献`、`精读论文`、`帮我看这篇论文`、`分析这篇论文`、`进入阶段二`、`进入阶段三`、`复现这篇论文`

> 💡 阶段间的提问在当前阶段的概念深度作答，绝不提前推进。

## 设计亮点

| 特性 | 说明 |
|---|---|
| **分阶段状态机** | 严格触发短语（`进入阶段二`）防止过早深入与上下文漂移。 |
| **超越论文本身** | 每次讲解都须超越复述，揭示论文未明说之处。 |
| **证据锚定** | 论断锚定到章节号、图编号、指标值与超参数，拒绝空泛复述。 |
| **有界推断** | 基于论文疏漏或领域通行做法的合理推断，明确标注后允许。 |
| **论文类型弹性适配** | 综述/理论/观点论文不强套框架，子节标题不变、内容适配。 |

## 适用人群

为**工科硕士**打造：
- 真正从论文中学到东西，而非走马观花
- 锁定研究方向并加以延伸
- 复现结果而不迷失方向

---

## 📜 License / 许可

Open source. Free for academic and educational use. / 开源，供学术与教育用途免费使用。
