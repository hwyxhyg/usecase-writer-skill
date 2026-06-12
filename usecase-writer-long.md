---
name: usecase-writer-long
version: 1.0.0
description: "撰写详细的 Atypica usecase 脚本（长版本 - 录屏演示版，2-4min）。全流程产品界面回扣，适合产品演示和功能教学。当用户需要详细展示产品操作的 usecase 时使用。如需简短版本，请使用 usecase-writer-short。"
metadata:
  author: "黄文玥"
  based_on: "usecase-writer-short 的扩展版本"
  version_type: "录屏演示版 - 全流程产品界面回扣"
  duration: "2-4 分钟"
  changelog:
    - v1.0.0 (2026-06-11): 初版发布，聚焦全流程产品界面录屏演示
---

# Usecase Writer Long（长版本 - 录屏演示版）

撰写详细完整的 Atypica usecase 脚本（2-4min 视频文案），**全流程回扣产品界面**，以产品录屏为主。

> **核心目标：** 用 250-350 词完整展示产品如何工作，让受众看到从输入到输出的每个关键步骤。

> **版本定位：** 长版本（2-4min），**全流程产品界面回扣**，适合产品演示、功能教学、销售Demo。  
> **短版本：** 需要简短的快速传播版本？使用 `usecase-writer-short`（1-2min）。

---

## 使用方式

用户可以通过以下方式调用本 skill：

```
请帮我撰写一个详细的 usecase 演示脚本，案例是 [描述案例背景]
```

或者

```
请用 /usecase-writer-demo 帮我撰写长版本脚本 [描述案例]
```

---

## 核心差异：长版本 vs 短版本

| 维度 | 短版本 (usecase-writer) | 长版本 (usecase-writer-demo) |
|------|------------------------|----------------------------|
| **时长** | 1-2 分钟 | 2-4 分钟 |
| **字数** | 150-200 词 | 250-350 词 |
| **风格** | 图形动效为主 | 产品录屏为主 |
| **产品回扣** | 关键环节（推荐输入+输出） | 全流程（输入+处理+输出） |
| **适用场景** | 社交媒体、快速传播、概念介绍 | 产品演示、功能教学、销售Demo、建立可信度 |
| **制作重点** | 动效设计、节奏把控、视觉吸引力 | 录屏素材、内容匹配、流程演示 |

**如何选择版本？**

考虑以下三个因素：

1. **视频长度需求**
   - 1-2 分钟 → 短版本
   - 2-4 分钟 → 长版本

2. **是否有足够的产品录屏素材**
   - 素材有限，或产品界面尚未完善 → 短版本（用动效替代）
   - 有完整的产品界面录屏素材 → 长版本（展示真实操作）

3. **受众群体和传播场景**
   - 社交媒体、快速传播 → 短版本（吸引注意力）
   - 产品演示、销售展示 → 长版本（建立可信度）

---

## 执行流程

### Phase 1：信息收集

**与短版本相同，收集以下信息：**

1. 案例背景（品牌/行业、研究问题、目标受众）
2. 痛点与限制
3. Atypica 应用细节（Interview / Panel / Sage / 社交媒体洞察）
4. 研究结果（核心发现、受访者原话、量化数据）

### Phase 2：脚本撰写（长版本特色）

**长版本的脚本结构（8 个环节）：**

#### 1. 钩子式开头（1-2 句）
与短版本相同，用具体问题开场。

#### 2. 问题放大（2-3 句）
展示传统方法的限制。

#### 3. 对比转折（1 句）
引入 Atypica。

#### 4. **研究流程展示（详细版 - 3-5 句）**

**❗ 长版本的关键差异：详细展示产品操作流程**

必须包含：
- 用户如何输入问题 → 【录屏：对话框输入演示】
- 如何上传材料 → 【录屏：文件上传过程】
- 如何配置参数 → 【录屏：设置界面操作】
- Persona 如何生成 → 【录屏：Persona 卡片生成动画】
- 访谈如何进行 → 【录屏：对话框问答流】

**示例：**
```
The team opened Atypica【录屏：打开产品界面】and entered their question
【录屏：在对话框中输入"How do we rebuild brand relevance with Gen Z?"】.

They uploaded three research files【录屏：拖拽 PDF 文件到上传区域 - 
显示 "Heinz_brand_study.pdf", "Nike_Gen_Z_strategy.pdf", 
"Coca_Cola_AI_campaign.pdf"】.

Atypica's system automatically sourced five personas【录屏：Persona 卡片
依次生成，显示头像、标签、来源】from cross-platform behavioral data.

Each persona entered deep interviews【录屏：切换到对话界面，
显示 Moderator 提问 → Persona 回答的完整流程】.
```

#### 5. 分层发现呈现（3-4 层）

**必须回扣产品：展示报告页面**

```
The research surfaced three core problems【录屏：切换到报告页面，
滚动到"核心发现"部分】.

First, the perception gap【录屏：高亮报告中的"Perception Gap"段落】...

Second, the execution trap【录屏：高亮报告中的"Execution Trap"段落】...
```

#### 6. 解决方案呈现（详细版）

**必须回扣产品：展示报告中的战略建议部分**

```
Third, the solution blueprint【录屏：滚动到报告的"战略建议"部分】.

Five actionable levers emerged【录屏：依次高亮 5 个战略支点】:

→ Create a flagship moment【录屏：高亮第1条建议】
→ Unify visual identity【录屏：高亮第2条建议】
→ Pivot narrative【录屏：高亮第3条建议】
→ Enable co-creation【录屏：高亮第4条建议】
→ Filter partnerships【录屏：高亮第5条建议】
```

#### 7. 完整报告 Overview

**必须回扣产品：展示完整报告结构**

```
atypica delivered the full roadmap【录屏：切换到报告目录页，
显示完整的章节结构】in two weeks.

The report included【录屏：依次展示各章节封面】:
- Executive Summary
- Core Findings
- Strategic Recommendations
- Implementation Roadmap
- Appendix: Persona Profiles
```

#### 8. CTA 升华（1-2 句）
与短版本相同。

---

## 产品界面回扣指导（长版本）

**长版本的核心原则：全流程回扣产品**

### 必须录屏的环节（7 个录屏点）

| 序号 | 环节 | 录屏内容 | 时长建议 |
|------|------|---------|---------|
| 1 | **打开产品** | 打开 Atypica 界面 | 3-5 秒 |
| 2 | **输入问题** | 在对话框中输入用户问题 | 5-8 秒 |
| 3 | **上传材料** | 拖拽文件到上传区，显示附件列表 | 8-10 秒 |
| 4 | **Persona 生成** | Persona 卡片依次生成动画 | 10-15 秒 |
| 5 | **访谈进行** | 对话框问答流（2-3 轮问答） | 15-20 秒 |
| 6 | **报告发现** | 切换到报告页，高亮核心发现 | 20-25 秒 |
| 7 | **完整报告** | 展示报告目录和章节结构 | 10-15 秒 |

**总录屏时长：约 70-100 秒（占 3-5 分钟视频的 30-40%）**

### 录屏脚本模板

**在脚本中，用【录屏】明确标注每个录屏环节：**

```
[钩子 + 问题放大]

The team opened Atypica【录屏1：打开产品界面】.

They entered their core question【录屏2：对话框输入 - 
显示"How do we rebuild brand relevance with Gen Z?"】.

To provide context, they uploaded three benchmark studies【录屏3：
文件上传 - 拖拽 3 个 PDF，显示附件列表】.

Atypica sourced five personas【录屏4：Persona 卡片生成 - 
依次显示 Lin, Qiang, Zhou, Mochi, Vivian】.

Each sat for deep interviews【录屏5：对话界面 - 
显示 Moderator 问"If a brand had no logo, would you still recognize it?" 
→ Lin 回答"I'd share it if it felt like my choice"】.

The research surfaced two core problems【录屏6：切换到报告页面，
滚动到"Core Findings"部分，高亮"Perception Gap"段落】.

First, the perception gap...
Second, the execution trap...

Third, the solution blueprint【录屏6续：滚动到"Strategic Recommendations"，
依次高亮 5 个支点】.

atypica delivered the full roadmap【录屏7：切换到报告目录页，
显示完整章节结构】in two weeks.
```

---

## 质量检查（长版本）

**使用以下清单逐项检查（25 分制，≥20 分合格）：**

### 叙事结构 [7 分]
- [ ] 有具体、吸引人的钩子问句
- [ ] 明确展示了传统方法的限制（≥2 个维度）
- [ ] 有清晰的转折点引入 Atypica
- [ ] **研究流程详细透明（包含输入、处理、输出的完整演示）**
- [ ] 发现分层呈现（First/Second/Third 或编号）
- [ ] 有明确的解决方案部分
- [ ] CTA 升华有诗意和记忆点

### 证据充分性 [5 分]
- [ ] 包含具体样本量数字
- [ ] 有成本/时间对比
- [ ] 至少 2 处受访者原话
- [ ] 提及研究框架或方法
- [ ] 有量化数据（百分比/倍数/金额）

### 语言质量 [4 分]
- [ ] 控制在 2-4min 体量（250-350 词）
- [ ] 无冗余修饰词和被动句式
- [ ] 使用强动词
- [ ] 具体细节替代模糊表达

### 产品能力展示 [5 分]
- [ ] 深入展示了 2-3 个核心功能
- [ ] 说明了功能如何解决具体痛点
- [ ] 展示了从诊断到方案的完整闭环
- [ ] **全流程产品界面回扣（输入/处理/输出都有录屏演示）**
- [ ] **至少 5 个产品界面录屏点**

### 录屏指导清晰度 [4 分]
- [ ] **每个录屏环节都有【录屏】标注**
- [ ] **录屏内容描述具体（不只是"显示界面"，而是"显示什么内容"）**
- [ ] **录屏时长建议合理（不会太快或太慢）**
- [ ] **录屏顺序逻辑清晰（引导制作者按流程录制）**

**如果得分 < 20 分，必须调整后重新检查。**

---

## 常见问题修正指南（长版本）

| 问题 | 修正方法 |
|------|---------|
| 录屏环节不够详细 | 增加【录屏】标注，具体描述要录什么内容 |
| 产品界面回扣不足 | 确保输入/处理/输出三个环节都有录屏 |
| 流程描述笼统 | 展开每个操作步骤（如何输入、如何上传、如何查看） |
| 只有问题诊断，没有解决方案 | 在报告页面录屏时，展示"战略建议"部分 |
| 缺少完整报告 overview | 在结尾增加报告目录页的录屏 |
| 时长超过 4 分钟 | 压缩中间过程描述，保留关键录屏点 |

---

## 输出格式

**默认输出：**
1. **完整的英文脚本**（250-350 词）
   - 纯旁白版本
   - 在关键位置用【录屏】标注录屏需求
2. **录屏清单**（列出所有录屏点及时长建议）
3. **质量评分**（25 分制 + 详细评分项）

**可选输出（用户要求时）：**
- **中文版本**
- **详细分镜表**（时间轴 + 旁白 + 录屏内容 + 视觉建议）

---

## 版本更新

- **v1.0.0** (2026-06-11)
  - 初版发布，定位为长版本/录屏演示版
  - 全流程产品界面回扣（输入/处理/输出）
  - 详细的录屏指导（7 个录屏点）
  - 录屏脚本模板和时长建议
  - 质量检查升级为 25 分制（增加"录屏指导清晰度"维度）

---

## Example References

See the anonymized example files in `usecase-writer-examples/`:

- **dairy_brand_usecase_short.md** - Market validation example (short version, 1-2min)
- **dairy_brand_usecase_long.md** - Market validation example (long version, 2-4min)

The long version example demonstrates:
- **Full-process product recording**: 7 recording points covering input/processing/output
- **Detailed recording guidance**: Each stage with specific duration and content descriptions
- **Complete narrative structure**: 310 words, comprehensive product demonstration

These examples follow this skill's standards and can serve as high-quality script references.

---

## 反馈与优化

每次使用本 skill 产出脚本后，建议：
1. 用质量清单打分
2. 实际录屏时，检查录屏指导是否足够清晰
3. 如发现通用性问题，更新本 skill
