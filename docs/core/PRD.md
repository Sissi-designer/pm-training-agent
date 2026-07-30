# PM Training Agent PRD v2.0

---

# 1. Product Overview

## 1.1 Product Name

PM Training Agent

## 1.2 Product Vision

Help experienced product managers build senior- and executive-level product thinking through deliberate practice in realistic business situations.

帮助拥有一定项目经验的产品经理，通过真实商业场景下的持续训练，建立更加成熟的问题分析、商业判断、资源分配、平台战略和影响力能力。

PM Training Agent 的目标不是帮助用户完成某一道题，而是帮助用户长期提升产品能力。

---

# 2. Background

拥有 3–8 年经验的产品经理通常已经能够：

- 独立负责产品模块
- 推动跨团队合作
- 完成产品设计与交付
- 使用数据分析问题

但随着成长到 Senior PM、Platform PM、Lead PM，真正的挑战逐渐发生变化。

他们需要面对的是：

- 没有标准答案的问题
- 信息不完整的商业决策
- 多个合理方案之间的取舍
- 长短期利益平衡
- 资源有限下的优先级判断
- 与不同 Stakeholder 建立共识

这些能力很难通过课程或阅读获得，更需要长期、高质量的刻意训练。

当前大多数 AI 产品主要提供：

- AI 问答
- 产品知识
- 面试练习
- PRD 生成

但缺少一个真正帮助 PM 持续训练产品思维能力的产品。

PM Training Agent 希望成为这样的长期成长伙伴。

---

# 3. Product Positioning

PM Training Agent 是一个 AI Product Capability Coach。

它不是：

- 产品课程
- AI 搜索
- PRD 写作工具
- 面试模拟器

而是一套持续训练产品思维的 AI 教练系统。

系统通过不同训练 Agent，引导用户不断思考、挑战、修正，并持续记录能力成长。

---

# 4. Target Users

## Primary Users

拥有约 3–8 年经验，希望进一步成长的产品经理。

典型用户已经：

- 完整负责过产品项目
- 具备基础商业分析能力
- 能推动跨团队合作
- 希望成长为 Senior PM、Platform PM 或更高阶段

## Core Needs

用户希望提升：

- Problem Framing
- Business Thinking
- Decision Making
- Investment Thinking
- Platform Thinking
- Strategic Thinking
- Influence Thinking

---

# 5. Product Value

PM Training Agent 提供长期、持续的产品能力训练，而不是一次性的答案。

产品价值包括：

- Structured Practice
- Adaptive Coaching
- Capability Evaluation
- Long-term Growth

每一次训练都会帮助用户积累新的能力证据，并持续更新 Capability Profile。

---

# 6. Product Experience

产品包含两个核心体验：

## Training

用户进入训练，与 AI Coach 完成一个完整 Session。

## Review

训练结束后，帮助用户总结本次学习内容，更新 Capability Profile，并推荐下一步训练。

---

# 7. Training

用户首先选择一个 Training Agent。

每个 Agent 是一种不同的训练方式，而不是一种能力。

所有 Agent 最终都会更新同一份 Capability Profile。

## MVP

- Decision Gym
- Strategy Lab
- Executive Trade-off

## V2

- Reverse Engineering
- Stakeholder Simulation

---

# 8. Training Agents

## Decision Gym

### Purpose

Train product decision making under ambiguity.

### Primary Capabilities

- Problem Framing
- Decision Making
- Investment Thinking

### Input

A realistic business decision with incomplete information.

### Output

- Final Recommendation
- Decision Rationale
- Capability Evidence
- Recommended Next Training

---

## Strategy Lab

### Purpose

Train long-term strategic thinking.

### Primary Capabilities

- Strategic Thinking
- Platform Thinking
- Business Thinking

### Input

A strategic product challenge.

### Output

- Strategy
- Roadmap
- Key Assumptions
- Capability Evidence
- Recommended Next Training

---

## Executive Trade-off

### Purpose

Train resource allocation and prioritization.

### Primary Capabilities

- Investment Thinking
- Decision Making
- Strategic Thinking

### Input

Multiple competing investment opportunities under limited resources.

### Output

- Investment Decision
- Trade-offs
- Opportunity Cost
- Capability Evidence
- Recommended Next Training

---

## Reverse Engineering (V2)

### Purpose

Infer the business reasoning behind real product decisions.

---

## Stakeholder Simulation (V2)

### Purpose

Train communication, alignment and influence across stakeholders.

---

# 9. Training Session

All Training Agents follow the same high-level session flow.

```text
Start Session

↓

Coach Conversation

↓

Final Recommendation

↓

Session Complete

↓

Reflection

↓

Capability Profile Update

↓

Choose Next Action
```

Session 结束时，系统会明确告知用户：

```
✓ Session Complete

Decision Gym

Capability Updated
```

然后进入 Review。

---

# 10. Review

Review 是训练结束后的学习阶段。

包括三个部分。

## 10.1 Reflection

Coach 提出一个 Closing Question，引导用户总结本次训练。

例如：

- What changed most during today's discussion?
- Which assumption proved to be incorrect?
- What would you do differently next time?

Reflection 直接在聊天中完成，不需要单独页面。

---

## 10.2 Capability Profile

Reflection 完成后，系统更新 Capability Profile。

用户可以查看：

- Current Capability Levels
- Recent Progress
- Coach Observations
- Recommended Next Training

系统内部使用的推理过程、置信度和中间判断不会展示给用户。

---

## 10.3 Coach Reference

用户可以主动查看 Coach 的参考思路。

Reference Response 不是标准答案，而是一种更成熟的产品思考方式。

该内容按需查看，不作为训练流程的必经步骤。

---

# 11. Capability Profile

Capability Profile 是用户长期成长记录。

每次 Session 都会更新相关能力。

每项能力包括：

- Current Level
- Supporting Evidence
- Recent Trend
- Coach Observations
- Recommended Next Training

能力不会因为一次训练立即发生变化。

系统更关注长期行为模式，而不是单次表现。

---

# 12. Reflection Mode

Reflection Mode 是系统内部能力。

它不会直接面向用户。

每次训练结束后，Reflection Mode 会：

- Review Coaching Quality
- Identify User Thinking Patterns
- Accumulate Candidate Patterns
- Improve Future Coaching

Reflection Mode 不会自动修改 Capability Framework。

---

# 13. Roadmap

## MVP

验证核心训练闭环。

包含：

- Decision Gym
- Strategy Lab
- Executive Trade-off
- Capability Profile
- Reflection
- Coach Reference

重点验证：

- 用户是否愿意持续训练
- Agent 是否真正起到 Coaching 作用
- Capability Profile 是否能够正确记录成长

---

## V2

扩展训练场景。

新增：

- Reverse Engineering
- Stakeholder Simulation
- Cross-agent Learning
- Richer Case Library

---

## V3

打造长期成长平台。

新增：

- Growth Workspace
- Capability Timeline
- Personalized Learning Path
- Long-term Coaching Agent
- Voice Coaching

---

# 14. Success Metrics

## User

- Session Completion Rate
- Weekly Training Frequency
- Retention
- Cross-agent Usage

## Coaching

- Recommendation Completion Rate
- Reflection Completion Rate
- User Satisfaction
- Coaching Effectiveness

## Capability

- Capability Evidence Coverage
- Capability Growth
- Repeated Blind Spot Reduction

---

# 15. Product Principles

PM Training Agent exists to help users become better product managers without depending on AI.

The product should train better thinking, not generate better answers.

Every training session should strengthen the user's ability to frame problems, make decisions and lead products independently.
