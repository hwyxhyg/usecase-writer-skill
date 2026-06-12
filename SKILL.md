---
name: usecase-writer
version: 1.1.0
description: "撰写高质量的 Atypica usecase 脚本（1min 视频文案）。基于宠物润唇膏、沃尔沃、丁克家庭等优秀案例总结的写作标准。当用户需要撰写或优化 usecase 脚本时使用。"
metadata:
  author: "Wenyue Huang"
  based_on: "逐字稿案例分析（宠物润唇膏、沃尔沃、丁克家庭）"
  changelog:
    - v1.1.0 (2026-06-10): 去除硬性证据要求，强化功能确认环节，增加视觉呈现建议
    - v1.0.0 (2026-06-10): 初版发布
---

# Usecase Writer

撰写成熟可靠的 Atypica usecase 脚本（1min 视频文案），覆盖产品痛点、解决方案、产品优势及适度 CTA。

> **核心目标：** 用 150-180 词讲好一个故事，用数据和原话说话，展示 Atypica 的独特价值。

---

## 使用方式

用户可以通过以下方式调用本 skill：

```
请帮我撰写一个 usecase，案例是 [描述案例背景]
```

或者

```
请用 /usecase-writer 帮我优化这个脚本 [粘贴现有脚本]
```

---

## 执行流程

### Phase 1：信息收集

**必须向用户收集以下信息（如果用户未提供）：**

1. **案例背景**
   - 品牌/行业类型（需模糊化处理避免侵权）
   - 核心研究问题
   - 目标受众画像

2. **痛点与限制**
   - 传统方法遇到的具体限制（成本？时间？伦理？招募难度？）
   - 为什么这个研究难做

3. **Atypica 应用细节（必须详细确认）**
   
   根据用户提到的功能，**逐项确认细节**：
   
   **如果使用 AI Interview：**
   - ❓ Persona 是如何创建的？（从人设库选择？基于社交媒体构建？）
   - ❓ 有几位 Persona？他们的背景是什么？
   - ❓ Moderator 问了什么类型的问题？
   - ❓ 生成了什么形式的输出？
   
   **如果使用 Reusable Panel：**
   - ❓ Panel 是基于什么材料构建的？（上传的访谈？用户数据？）
   - ❓ Panel 有多少人？什么画像？
   - ❓ 如何被反复使用的？（测试概念？验证策略？）
   - ❓ 相比一次性调研节省了什么？
   
   **如果使用 Sage 模拟：**
   - ❓ 模拟了什么类型的角色？（专家？消费者？两者都有？）
   - ❓ 上传了什么材料？（专家著作？行业报告？社交数据？）
   - ❓ 这些角色如何互动？（专家提方案，消费者反馈？独立输出？）
   - ❓ 输出了什么形式的内容？
   - ❓ 为什么可以反复利用？
   
   **如果使用社交媒体洞察：**
   - ❓ 使用了哪些平台？（X, TikTok, 小红书, Instagram？）
   - ❓ 搜索了什么关键词？
   - ❓ 发现了什么模式或讨论？
   
   **❗ 重要：** 在开始写脚本前，必须把上述问题逐一确认清楚。不要假设或模糊带过。

4. **研究结果**
   - 核心发现（2-3 层）
   - 受访者原话（如果有）
   - 量化数据（如果有）

### Phase 2：脚本撰写

**严格按照以下结构撰写：**

#### 1. 钩子式开头（1-2 句）
用一个具体、高风险的问题开场。

✅ 好的示例：
- "do American pet owners actually want a pet-friendly lip balm?"
- "Why are more young couples choosing to remain childfree?"

❌ 避免：
- "很多品牌都面临市场验证的问题"（太泛泛）

#### 2. 问题放大（2-3 句）
展示传统方法的限制，**至少包含 2 个维度**：
- 成本维度（如 "$14,000 TMIC test"）
- 时间维度（如 "recruiting could take years"）
- 伦理维度（如 "ethical review is complex"）
- 可行性维度（如 "bringing them together wasn't feasible"）

#### 3. 对比转折（1 句）
用强有力的过渡句引入 Atypica：
- "This is why we need atypica.AI"
- "atypica solved this through..."
- "Then they ran atypica. The conclusion was identical. But the cost wasn't."

#### 4. 研究流程展示（2-3 句）
**必须包含：**
- 研究框架名称（JTBD / Kano / Fishbowl）
- 样本设计（具体数字："9 personas", "14 interviews"）
- Persona 构建来源或讨论形式

示例：
- "The brand built a question list across six dimensions... Atypica sourced matched personas automatically — a pet-owning professional, a pet store owner, a multi-cat household."

**视觉呈现建议：**
在脚本关键位置用【】标注视觉需求：
- 痛点部分 → 标注需要的屏显文字（精炼到 10-15 字）
- 流程部分 → 标注录屏演示的环节
- 原话部分 → 标注引用卡片或字幕样式

示例：
```
A leading dairy group faced a brutal truth【屏显："信任 ≠ 心动"】...

By feeding Heinz archives into Sage【录屏：上传界面】, 
they constructed a council【视觉：角色卡片依次出现】...

As one persona put it【引用卡片】: "We buy narratives about ourselves."
```

#### 5. 分层发现呈现（主体部分）
用 **First, Second, Third** 或 **Finding 1, 2, 3** 结构化呈现。

每层必须包含：
- 维度名称
- 具体发现
- 证据支撑（受访者原话或数据）

✅ 好的示例：
```
First, starting from the scene: the safety anxiety beneath intimate interaction is real. 
Almost every respondent described the same moment — applying lip balm, 
then feeling a pet's tongue graze their lips.

Second, digging deeper into the need: how users understand risk...
Most respondents were willing to pay a 20–30% premium — but only if trust was established.

Third, from need to purchase action...
```

#### 6. 核心洞察（1-2 句）
提炼更深层的 **why**（不只是 what）：
- 意外发现或反直觉结论
- 对品牌/产品的实际指导意义

示例：
- "The product has a clear use case, safety anxiety is a genuine pain point, and pet-friendliness functions as an emotional necessity — all three supporting willingness to pay a premium."

#### 7. CTA 升华（1 句）
诗意化的价值主张：
- "Real simulation. No expensive guesswork"
- "One round of interviews. Multiple rounds of insight"
- "design silence"（概念性升华）

### Phase 3：质量检查

**使用以下清单逐项检查（20 分制，≥16 分合格）：**

#### 叙事结构 [7 分]
- [ ] 有具体、吸引人的钩子问句
- [ ] 明确展示了传统方法的限制（≥2 个维度）
- [ ] 有清晰的转折点引入 Atypica
- [ ] 研究流程透明（框架/方法/阶段）
- [ ] 发现分层呈现（First/Second/Third 或编号）
- [ ] 有更深层的洞察（why, not just what）
- [ ] CTA 升华有诗意和记忆点

#### 证据充分性 [5 分]
- [ ] 包含具体样本量数字
- [ ] 有成本/时间对比（或详细的流程描述 + 视觉演示）
- [ ] 至少 1 处受访者原话（或清晰的角色互动说明）
- [ ] 提及研究框架名称（或清晰的研究设计描述）
- [ ] 有量化数据（百分比/倍数/金额，或具体的流程步骤）

**说明：** 不强制要求所有证据。如果流程描述清晰 + 视觉配合到位，可以补足证据的缺失。

#### 语言质量 [4 分]
- [ ] 控制在 1min 体量（150-180 词）
- [ ] 无冗余修饰词和被动句式
- [ ] 使用强动词（replaced, shifted, surfaced, delivered）
- [ ] 具体细节替代模糊表达

#### 产品能力展示 [4 分]
- [ ] 深入展示了 1-2 个核心功能
- [ ] 说明了功能如何解决具体痛点
- [ ] 避免功能罗列，聚焦案例相关性
- [ ] 体现了 Atypica 的独特价值

**如果得分 < 16 分，必须按修正指南调整后重新检查。**

---

## 常见问题修正指南

| 问题 | 修正方法 |
|------|---------|
| 开头平淡，缺少吸引力 | 改为具体的问句或冲突场景 |
| 传统方法限制不明确 | 具体说明成本/时间/伦理/招募难度 |
| 流程描述笼统 | 补充研究框架名称和具体阶段 |
| 发现平铺直叙 | 用 First/Second/Third 分层 + 添加原话 |
| 缺少量化数据 | 补充样本量/百分比/成本对比 |
| 结尾无升华 | 提炼诗意化的价值主张 |
| 超过 1min 体量 | 删除冗余修饰，每句话推进叙事 |

---

## 参考模板

根据案例类型选择对应模板：

### 模板 A：市场验证类

适用场景：品牌想验证一个新产品概念是否有市场需求

```
[钩子问句：具体的市场验证问题]

[品牌尝试 + 限制（成本/数据/招募）]

Atypica solved this through [核心功能]. 

[研究设计：维度/框架/样本]

After [N] in-depth conversations, Atypica produced a full report.

The report delivered multi-layered insights:

First, [维度1 + 发现 + 原话]
Second, [维度2 + 发现 + 原话]
Third, [维度3 + 发现 + 原话]

[核心洞察和价值评估]

[CTA 升华]
```

**参考案例：** 跨境出海（小猫润唇膏）

### 模板 B：Panel 重激活类

适用场景：已有访谈数据，需要重新召集受访者深度讨论

```
[背景：某个常被忽视的用户群体]

[已有研究 + 限制：无法重聚]

So Atypica built AI personas [来源] and brought all [N] 
into the same [研究形式].

[研究框架 + 方法论]

The findings reframed [议题] around [N] paradigm shifts:

First, from [旧范式] to [新范式]. [具体描述]
Second, from [旧范式] to [新范式]. [具体描述]
Third, from [旧范式] to [新范式]. [具体描述]

[根本差异分析]
[分歧点说明（诚实呈现）]
[共识与方向]
[Panel 可复用性的价值]
```

**参考案例：** 沃尔沃（女性车主 MPV 需求）

### 模板 C：对比验证类

适用场景：品牌已做过传统调研，用 Atypica 验证或深化

```
[品牌决策场景]

They ran [传统方法] — [$成本], [样本量]. [结果]

However, [疑虑]

Then they ran atypica.

The conclusion was identical. But [对比维度] wasn't.

[Atypica 如何分解问题：维度列举]
[Persona 招募和讨论过程]

The research produced [N] core findings:

Finding 1: [发现 + 证据]
Finding 2: [发现 + 证据]
Finding 3: [发现 + 证据]

The results were identical [to 传统方法].
atypica confirmed [结论], and went further: [增量价值]

[可信度 + 深度 + 成本优势]

[CTA]
```

**参考案例：** 美妆图片测试

---

## 语言风格要求

### ✅ 必须做到：

1. **简洁有力**
   - 删除所有可有可无的修饰词
   - 一句话推进一个点，不绕圈子

2. **主动语态 + 强动词**
   - ✅ "atypica solved this"
   - ❌ "this was solved by atypica"
   - 强动词：replaced, shifted, surfaced, delivered
   - 弱动词：did, made, got

3. **具体细节**
   - ✅ "9 personas", "$14,000", "20-30% premium"
   - ❌ "很多受访者", "成本较高", "大部分人"

4. **对比与转折**
   - 用 But, Yet, However 制造张力
   - 示例："The conclusion was identical. But the cost wasn't."

5. **诗意升华**（仅在 CTA 部分）
   - "Real simulation. No expensive guesswork"
   - "design silence"

### ❌ 必须避免：

1. **技术黑话**
   - ❌ "leveraging AI-powered personas"
   - ✅ "matching personas from its library"

2. **空洞形容词**
   - ❌ "强大的""先进的""创新的"
   - ✅ 用具体功能和数据说话

3. **不确定表达**
   - ❌ "我们认为""可能""也许""比较"
   - ✅ 用数据和原话

4. **功能堆砌**
   - 不要试图在一个 usecase 中展示所有功能
   - 深入讲 1-2 个最相关的能力

---

## 证据标准（建议）

以下证据能增强脚本可信度，**建议包含但不强制**：

1. ✅ **具体样本量**：9 personas / 14 interviews / 58 personas
2. ✅ **成本或时间对比**（可选）：$14,000 TMIC test vs Atypica / 3x faster
3. ✅ **百分比/倍数**：20-30% premium / 3x faster
4. ✅ **受访者原话**："Maybe your life is the purpose I was looking for."
5. ✅ **对比参照点**：与传统方法的明确对比
6. ✅ **研究框架**：JTBD / Kano / Fishbowl

**重要说明：**
- **可信度来源多样化**：如果流程描述足够详细（上传什么材料 → 构建什么角色 → 如何互动），配合清晰的视觉呈现（录屏演示、角色卡片、对话界面），即使没有上述证据，脚本同样可以是高质量的。
- **不捏造数据**：没有的数据不要编造。用清晰的流程叙述替代。
- **视觉补充**：屏显文字、录屏演示、引用卡片等视觉元素可以有效补充证据的缺失。

---

## 边界

### ❌ 不做：

1. 在一个 usecase 中展示所有功能
2. 使用技术术语让脚本像产品说明书
3. 夸大效果或保证特定结果
4. 直接使用真实品牌名（需模糊化）
5. 平铺直叙，流水账式描述
6. 只有观点没有数据支撑

### ✅ 坚持：

1. 每个 usecase 讲好一个故事
2. 用具体细节替代抽象概念
3. 展示研究的专业性和严谨性
4. 让数据和原话说话
5. 升华但不夸大
6. 诚实呈现研究的局限性（如果有分歧也要说明）

---

## 输出格式

**默认输出：**
1. **完整的英文脚本**（150-180 词）
   - 纯旁白版本
   - 在关键位置用【】标注视觉需求
2. **质量评分**（20 分制 + 详细评分项）
3. 如果得分 < 16 分，附带修改建议

**可选输出（用户要求时）：**
- **中文版本**
- **屏显文字建议**：提供 3-5 条精炼的屏显文字（痛点、关键数据、引语、CTA）
  - 中文：10-15 字以内
  - 英文：5-8 词以内
  - 示例：`"信任 ≠ 心动"` / `"One build. Infinite sessions"`
  
- **分镜建议（简要版）**：标注关键场景的视觉呈现方式
  
  | 场景 | 旁白概要 | 视觉建议 |
  |------|----------|----------|
  | 痛点 | "trusted but not desired" | 屏显对比文字 + 产品/社交界面对比 |
  | 流程 | "feeding archives into Sage" | 录屏：上传界面 → 角色卡片生成 |
  | 发现 | "three patterns emerged" | 引用卡片逐一显示 |
  | CTA | "one build, infinite sessions" | 产品界面演示 |

---

## 优秀案例参考

用户可以查看以下飞书文档中的逐字稿案例作为参考：

- **跨境出海（小猫润唇膏）** - 市场验证类典范
- **沃尔沃** - Panel 重激活类典范  
- **丁克家庭** - 社会实验类典范

这些案例都严格遵循了本 skill 的标准，可以作为高质量脚本的参照。

---

## 版本更新

- **v1.1.0** (2026-06-10)
  - ✅ 去除硬性证据要求，改为建议性标准
  - ✅ 强化功能确认环节（Interview / Panel / Sage / 社交媒体）
  - ✅ 增加视觉呈现建议（屏显文字、录屏演示、分镜标注）
  - ✅ 明确"流程描述 + 视觉配合"可以替代部分数据证据

- **v1.0.0** (2026-06-10)
  - 基于宠物润唇膏、沃尔沃、丁克家庭等案例分析
  - 确立叙事黄金公式（7 环节）
  - 建立 20 分质量评分体系
  - 提供 3 套参考模板

---

## 反馈与优化

每次使用本 skill 产出脚本后，建议：
1. 用质量清单打分
2. 记录不足之处
3. 如发现通用性问题，更新本 skill
