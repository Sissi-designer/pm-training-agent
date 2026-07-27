# PM Training Agent PRD v1.0

## 1. Product Overview

### 1.1 Product Name

PM-Training-Agent

### 1.2 Product Vision

Help experienced product managers build executive-level product thinking through deliberate practice in real business decision-making.

帮助拥有一定项目经验的产品经理，通过真实商业场景的刻意训练，建立平台战略、商业决策和长期规划能力。

## 2. Background

越来越多3-6年产品经理已经能够：

- 独立负责产品模块
- 推动跨团队合作
- 进行数据分析
- 完成PRD设计

但是当成长到Senior PM / Platform PM时，最大的Gap已经不是产品技能，而是如何面对一个没有标准答案的商业问题，并最终做出正确的产品决策。

典型表现：

- 不知道如何开始分析一个模糊问题
- 容易直接进入Solution，而没有先定义Problem
- 能分析很多数据，但无法形成Recommendation
- 能理解Leader为什么这么决策，但自己无法独立做出类似决策
- 缺乏平台战略、长期规划和资源分配经验

目前市面上的AI产品主要提供：

- Product知识
- Interview练习
- PRD生成
- AI问答

但没有任何产品能真正帮助PM系统训练产品能力以突破产品经理的不同职业阶段。我们希望创建一个PM训练agent，通过模拟不同职业阶段所需处理的问题，不断锻炼PM向更高level的思考模式进步，并通过科学的职业阶段划分和case study打分，帮助PM了解目前所处阶段、距离下一阶段核心欠缺的能力、近期训练效果。

## 3. Product Positioning

PM-Training-Agent 是一个 AI PM Capability Coach。

它不是课程，不是知识库，不是AI问答。

而是一位每天陪用户训练商业决策、资源分配、长期战略规划、协同合作方能力的AI教练。

## 4. Target Users

工作3-6年的产品经理。典型画像：

- 已拥有能力：做过完整项目、能分析数据、会做产品设计、能回答Why
- 希望提升：platform thinking, strategy thinking, business decision, investment thinking, long-term planning
- 核心痛点：知道别人决策原因。但是轮到自己不知道如何开始思考。

## 5. Product Value Proposition

Build Product Capability through deliberate practice.
The product continuously observes, evaluates and develops the user's capability profile rather than optimizing for individual case performance.

## 6. Core User Journey

Open agent → choose training topic → AI coaching → reflection → score → growth dashboard

## 7. Product Information Architecture

### 7.1 底部导航栏

两个tab，tab1 coach，tab2 growth

### 7.2 Coach页面

目前规划包含五个训练主题：Decision Gym, Executive Trade-off，Reverse Engineering, Strategy Lab, Stakeholder Simulation

### 7.3 Growth 页面

展示产品阶段变迁、核心能力评分变化、决策历史

## 8. Coach Design
Each coach is a training method.
It does not represent an independent capability.
All coaches contribute to the same Capability Framework with different primary training objectives.

### 8.1 Coach 1: Decision Gym

#### 1. Goal

训练Problem Framing, Business Goal, Decision Making

#### 2. Input

AI提供一个模糊商业问题。

例如：

Booking customer support cost keeps increasing.

Should Booking invest in AI?

#### 3. AI Rules

- 不断追问Why? Why now? What assumptions? What alternatives?
- 最多10轮, 用户必须输出Problem Definition, Business Goal, Alternative Solutions, Trade-off, Recommendation

### 8.2 Coach 2: Executive Trade-off

#### 1. Goal

训练资源分配能力。

#### 2. Input

AI提供典型问题：资源有限, 预算有限, 优先级冲突。

例如：多个项目AI Review, Identity, Payment, Search，但资源只能做两个。应该怎么选择，为什么？

#### 3．AI Rules

训练：Investment Thinking, Portfolio Thinking, Priority, ROI, Long-term Value

### 8.3 Coach 3: Reverse Engineering

#### 1. Goal

推理真实产品背后的商业决策。

#### 2. Input

真实公司，真实产品，逐步释放背景。

例如：Booking Genius, Airbnb Categories, Amazon Prime

#### 3. AI Rules

用户不断推理：Business Problem, Alternative, Trade-off, 最终Decision。

AI最后公布：真实商业逻辑。

### 8.4 Coach 4: Strategy Lab

#### 1. Goal

训练长期战略规划能力。

#### 2.Input

例如：

You are Head of Booking Self-service Platform. Create 3 Month Plan, 1 Year Strategy, 3 Year Vision

#### 3. AI Rules

AI不断Challenge：Why? Priority? Risk? MVP? Success Metrics?

### 8.5 Coach 5: Stakeholder Simulation

#### 1. Goal

训练Influence能力。

#### 2. Input

针对之前coach1,2,3下的方案，训练将方案向不同stakeholder sell的能力

AI分别扮演：Business, Engineering, Finance, Legal, Leadership

#### 3. AI rules

不断Challenge Proposal, 最终训练：Communication, Alignment, Influence

## 9. AI Coaching Principles

Agent永远遵守：

**Principle 1:** Don't Teach First, 永远先Challenge, 不要直接告诉答案。

**Principle 2:** Challenge Assumptions. 不断问：Why? Why now? Why not?

**Principle 3:** Correction Instead of Answer. 用户偏离方向,及时纠偏,不给完整答案。

**Principle 4:** Decision Required. 最后必须输出Recommendation。不能：Need more data. 不能：It depends.

## 10. Reflection & Evaluation

### 1. 训练结束自动进入Reflection
After each session, the agent updates the user's Capability Profile.

Evaluation includes:
- Current Level
- Confidence
- Supporting Evidence
- Recommended Next Training

具体能力项和能力阶段参考Capability Framework.md

### 2. Agent自动生成Biggest Blind Spot

例如：

You jumped into solution before defining the business problem.

### 3. If I Were The PM

Agent给出参考回答。不是标准答案。

而是一种更成熟的Decision Framework。

## 11. Growth Dashboard

### 1.Overall Level

Feature PM → Business PM → Platform PM → Strategy PM

Overall Level is inferred from the Capability Profile.
It is not calculated by averaging scores. Each level follows the combination of mature capabilities below:
| Overall Level | Required Capability                                     |
| ------------- | ------------------------------------------------------- |
| Feature PM    | Problem Framing Stable                                  |
| Business PM   | + Business Thinking Stable                              |
| Platform PM   | + Investment Thinking Stable + Platform Thinking Stable |
| Strategy PM   | All capabilities Stable, with at least two Advanced     |


### 2. Capability Profile

记录所有训练。展示每个能力项当前所处level，目前正在经历的成长趋势。结构为capability,level,trend


### 3. Summary
基于历史训练记录和capability profile的更新，给出总结。参考格式：
今天我观察到了 3 个新的行为证据，因此将你的 Platform Thinking 从 Emerging 提升为 Stable；Investment Thinking 仍保持 Emerging，因为在两个不同场景下，你都没有主动讨论 Opportunity Cost。下一次建议进入 Executive Trade-off 继续训练。


## 12. AI Architecture

Agent包含四层身份：

**Hiring Manager：** 训练Why。

**Manager：** 训练Decision。

**Director：** 训练Investment。

**VP：** 训练Strategy。

AI根据用户能力自动切换Challenge深度。

## 13. Milestone

### 1. MVP

Including: Decision Gym, Executive Trade-off, Reflection, Score, Growth Dashboard

### 2. Phase 2

Newly add: Strategy Lab, Stakeholder Simulation, Reverse Engineering

### 3. Phase 3

Newly add: Voice Coaching, 真实公司Case Library, 上传PRD进行Challenge, AI模拟Leadership Meeting

## 14. Success Metrics

### 用户层

- 7-Day Retention
- Daily Training Completion Rate
- Weekly Training Frequency
- Reflection Completion Rate

### AI层

- 平均训练轮数
- Challenge有效率
- 用户Recommendation输出率
- 用户满意度

### 能力层

连续训练30天后：

- Problem Framing平均提升
- Decision Making平均提升
- Investment Thinking平均提升
