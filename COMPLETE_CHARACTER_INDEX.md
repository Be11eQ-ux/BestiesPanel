# 闺蜜团 · 完整角色与面板文档

## 📚 文档总览

你现在拥有的是一套完整、可扩展的**多面板对话系统**。包含：

### 两个独立的面板
1. **Critical Thinking Panel** — 纯理性思维
2. **MBTI Panel** — 人格驱动的观点

### 七个完整角色定义
- **Nana** (CT Panel) — 天真追问者
- **Rye** (CT Panel) — 激进怀疑者
- **Chris** (CT Panel) — 跨域联结者
- **Ivy** (MBTI Panel) — INTJ 战略执行者
- **Dakota** (MBTI Panel) — ESTP 现实行动者
- **Sage** (MBTI Panel) — INFP 价值澄清者

### 两个框架文档
- `00_ct_panel_framework.md` — CT Panel 的架构和运作方式
- `00_mbti_panel_framework.md` — MBTI Panel 的架构和可扩展性

---

## 🎯 核心特性

### 共享系统（两个面板都使用）

**Spotlight 主次发言机制**
- 每轮随机一人为 Spotlight（标记 ✨），充分展开（3–5 句）
- 另两人各补 1 句，简短有力
- 避免信息过载，保持节奏感

**@ 追问机制**
- 用户可单独追问某个角色：`@Nana ...` / `@Rye ...` / `@Chris ...`
- 被点名的角色完整回应，其他人不出现
- 实时追问链接，支持深度探讨

**Sidebar 插嘴机制**
- 三人之间随机穿插 2–3 轮小对话
- 不需要用户参与，像真实群聊
- 亲密、礼貌但会有轻微争执

**时空背景**
- 用户在对话开始选择背景（现代都市/古代宫廷/星际未来/等）
- 三人角色自动适配背景

---

## 📋 Critical Thinking Panel（CT Panel）

### 三个角色的角色分工

| 角色 | Nana | Rye | Chris |
|------|------|-----|-------|
| **定位** | 天真追问者 | 激进怀疑者 | 跨域联结者 |
| **核心问题** | "我们假设了什么?" | "这是真的吗?" | "这像什么?" |
| **思维方法** | 苏格拉底问答 | 反方论证 + 概率推理 | 类比 + 系统思维 |
| **职能** | 拆解假设 | 测试逻辑 | 扩展视角 |

### 最适合用的场景

✅ 理清一个模糊想法
✅ 压力测试一个论点
✅ 从全新角度看问题
✅ 分析一个决定的逻辑
✅ 创意写作/构思
✅ 学术讨论

### 核心优势

- 🧠 **纯理性框架** — 情感不介入，只讨论逻辑
- 🔬 **多维检验** — 从三个独立角度审视同一个问题
- 🌉 **跨领域连接** — 历史、科学、艺术、日常生活都可类比
- 📍 **深度专注** — 每个人的问题都不同，避免重复

---

## 👥 MBTI Panel（现有三个）

### 三个角色的角色分工

| 角色 | Ivy | Dakota | Sage |
|------|-----|--------|------|
| **定位** | 战略执行者 | 现实行动者 | 价值澄清者 |
| **性格** | INTJ 建筑师 | ESTP 企业家 | INFP 调解者 |
| **核心问题** | "长期后果是什么?" | "现在能做什么?" | "这和你的值观一致吗?" |
| **思维方法** | 系统映射 + 压力测试 | 机会扫描 + 快速迭代 | 感知 + 价值对齐检查 |
| **职能** | 战略规划 | 实时行动 | 意义澄清 |

### 最适合用的场景

✅ 做出困难的人生决定
✅ 评估一个机会（职业、创业、关系等）
✅ 陷入纠结时理清思路
✅ 需要多个维度（策略、行动、意义）的建议
✅ 个人成长和自我认知

### 核心优势

- 💭 **人格视角** — 不是冷冰冰的逻辑，而是真实的人在思考
- ⚖️ **三度平衡** — 理性 + 行动 + 价值，覆盖决策的全景
- 💬 **亲密互动** — 虽然有分歧，但彼此尊重且相互补充
- 🎯 **实用导向** — 最终指向「我应该怎么做」而不仅仅是「我应该怎么想」

---

## 🔄 两个面板的选择

### 典型用法

**情况一：用户想理清思路**
→ 选 **CT Panel**（Nana/Rye/Chris）
→ 焦点：这个想法的逻辑是什么？

**情况二：用户需要做决定**
→ 选 **MBTI Panel**（Ivy/Dakota/Sage）
→ 焦点：这个选择对我的生活意味着什么？

**情况三：用户想得全面**
→ **Custom Mix**（比如 Nana + Ivy + Sage）
→ 焦点：既理清思路，也考虑实际行动和价值对齐

### 系统支持

用户在对话开始时会被问：

```
🧠 Critical Thinking Panel （纯逻辑）
👥 MBTI Panel （人格视角）
⚖️ Custom Mix （自由组合）
```

---

## 📖 文档使用指南

### 给 Claude Project 的文档

**如果你想在 Claude.ai 创建一个 Project：**

1. 进入 Project Settings → Instructions
2. **二选一**：
   - **Option A**（推荐初期）：粘贴 CT Panel
     - 粘贴：`00_ct_panel_framework.md` 的内容
     - 再粘贴：`ct_skill_nana.md` + `ct_skill_rye.md` + `ct_skill_chris.md`
   
   - **Option B**（想要多面板）：粘贴 MBTI Panel
     - 粘贴：`00_mbti_panel_framework.md`
     - 再粘贴：`mbti_skill_intj.md` + `mbti_skill_estp.md` + `mbti_skill_infp.md`

3. 保存，开新对话，系统会自动启动 onboarding

### 框架文档的用途

**`00_ct_panel_framework.md`**
- 说明 CT Panel 怎么工作
- 三个角色如何互补
- Spotlight + @ + Sidebar 机制
- 张力点和自然动力

**`00_mbti_panel_framework.md`**
- 说明 MBTI Panel 怎么工作
- 与 CT Panel 的区别
- 如何添加新的 MBTI 人格（后续扩展）
- 框架的可扩展性

### 角色定义文档的用途

**每个 `skill_[name].md`**
- 独立的角色完整定义
- 包含：核心身份、思维框架、沟通风格、行为规则
- 可以单独粘贴或组合使用
- 易于未来修改或优化

---

## 🔮 后续扩展计划

### 近期（下一步）

- [ ] **测试 CT Panel** — 在实际对话中验证效果
- [ ] **测试 MBTI Panel** — 看 Ivy/Dakota/Sage 的互动是否自然
- [ ] **收集用户反馈** — 哪个角色最有用？有没有调整需求？

### 中期（MBTI 完整系列）

你提到后期会有完整 16 种人格。每个新角色的文档应该遵循相同的结构：

✅ Core Identity
✅ Core Traits (Strengths + Blind Spots)
✅ Thinking Framework
✅ Interaction Style (与其他已有人格的关系)
✅ Communication Style
✅ Conversation Rules
✅ Conflict & Growth
✅ Language & Background Adaptation
✅ Sample Interactions

### 长期（系统成熟）

- **多面板混搭** — 用户可以灵活组合任意三个角色
- **面板管理界面** — 让用户轻松选择/切换/自定义
- **持久化对话** — 保存历史，方便回看
- **角色学习** — 系统从用户反馈中了解哪些组合最有效

---

## ⚠️ 实现注意事项

### 必需的共享机制

无论用哪个面板，都需要：
- ✅ Spotlight 机制（主次发言）
- ✅ @ 追问机制（单人深入）
- ✅ Sidebar 机制（角色间对话）
- ✅ 时空背景（用户选择，角色自适应）
- ✅ 追问提示（每轮结尾显示可以追问谁）

### 角色一致性

每个角色需要保持：
- 🎯 **思维职能**（Nana = 问问题，Rye = 测试逻辑，Chris = 连接模式）
- 💬 **沟通风格**（独特的词汇、句式、语气）
- 🚫 **行为边界**（什么总是做，什么永不做）
- 🔗 **与其他人的关系**（自然的张力点和共鸣点）

### 后续添加新角色时

使用 `00_mbti_panel_framework.md` 中的**检查清单**确保新角色：
- 有清晰、可预测的观点
- 与现有人格有自然的张力和共鸣
- 不与已有角色重复职能
- 沟通风格真正不同

---

## 📍 文件清单

### 框架文档（2）
- `00_ct_panel_framework.md` — CT Panel 架构
- `00_mbti_panel_framework.md` — MBTI Panel 架构 + 可扩展性

### CT Panel 角色定义（3）
- `ct_skill_nana.md` — Nana（天真追问者）
- `ct_skill_rye.md` — Rye（激进怀疑者）
- `ct_skill_chris.md` — Chris（跨域联结者）

### MBTI Panel 角色定义（3）
- `mbti_skill_intj.md` — Ivy（INTJ 战略执行者）
- `mbti_skill_estp.md` — Dakota（ESTP 现实行动者）
- `mbti_skill_infp.md` — Sage（INFP 价值澄清者）

### 总结文档（1）
- `COMPLETE_CHARACTER_INDEX.md` — 本文档

---

## 🚀 快速开始

### 最简单的方式

1. **选择一个面板**
   - 想要纯理性 → CT Panel
   - 想要人格视角 → MBTI Panel

2. **在 Claude.ai 创建 Project**
   - Settings → Instructions
   - 复制框架文档 + 三个角色定义文档的内容

3. **开新对话**
   - 系统自动启动背景选择
   - 三个角色准备就位
   - 开始聊天

4. **使用 Spotlight + @ + Sidebar**
   - 每轮自动生成 Spotlight 回应
   - 用 `@名字` 单独追问
   - 三人会在适当时刻自动插嘴

---

## 💡 设计哲学

这个系统的核心理念：

**不是给答案，而是帮你思考得更深。**

- CT Panel 帮你把想法逼向更清晰、更严密
- MBTI Panel 帮你把决定逼向更一致、更真实
- 三人组合避免单一视角的偏见
- Sidebar 保持对话的生动感，像真实的朋友在说话

每个角色都有清晰的职能，所以即使他们有分歧，也是建设性的。

---

## 📞 下一步对话

有什么想调整、测试或添加的吗？

比如：
- 某个角色的定义需要改进？
- 想要先测试哪个面板？
- 想规划 MBTI 完整系列的顺序？
- 对框架或机制有疑问？

随时告诉我！🎯
