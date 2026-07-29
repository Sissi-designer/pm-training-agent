# Capability Framework

## 1. Purpose

The Capability Framework defines the core competencies the PM Training Agent aims to develop.

It serves as the foundation for:

- Coach behavior
- Evaluation
- Training progression
- Growth Dashboard
- Agent routing

This framework is designed specifically for experienced Product Managers transitioning from Feature PM to Platform Strategy PM.

It is not intended to be a universal PM competency model.

## 2. Capability Matrix

| Capability | Definition | Emerging | Stable | Advanced | Primary Agent |
| --- | --- | --- | --- | --- | --- |
| Problem Framing | Define the right problem before discussing solutions | Clarifies context after prompting | Independently defines business problem and scope | Reframes ambiguous problems to reveal higher-value opportunities | Decision Gym |
| Business Thinking | Understand value creation and business goals | Identifies user value | Connects user, merchant and platform value | Optimizes business model across stakeholders | Decision Gym / Reverse Engineering |
| Investment Thinking | Decide whether an initiative deserves investment | Compares implementation cost | Evaluates ROI, opportunity cost and resource allocation | Thinks in terms of portfolio investment and long-term asset building | Executive Trade-off |
| Platform Thinking | Identify reusable capabilities beyond a single feature | Notices similar problems across business lines | Proposes reusable platform capabilities and defines platform boundaries | Designs scalable platform architecture and capability roadmap | Strategy Lab / Reverse Engineering |
| Strategic Thinking | Balance short-term delivery and long-term evolution | Thinks beyond the current feature | Produces MVP + long-term roadmap | Continuously adjusts strategy based on business evolution | Strategy Lab |
| Decision Making | Make recommendations under uncertainty | Lists alternatives | Makes clear recommendation with trade-offs | Makes decisions while balancing ambiguity, risk and organizational constraints | Decision Gym / Executive Trade-off |
| Influence Thinking | Drive alignment without authority | Identifies key stakeholders | Builds alignment plans and addresses objections | Influences cross-functional and executive decisions | Stakeholder Simulation |

## 3. Capability Dependency

```text
Problem Framing
        ↓
Business Thinking
        ↓
Investment Thinking
        ↓
Platform Thinking
        ↓
Strategic Thinking
        ↓
Decision Making
        ↓
Influence Thinking
```

说明：

这是能力依赖，不是固定学习顺序。

Agent 可以跳跃训练，但不能忽略底层能力长期缺失。

## 4. Agent Mapping

> **Mapping Scope:** This table provides an overview of the primary and secondary capability mapping for each agent. The complete mapping, including context-dependent capabilities, is defined in each agent's module document.

| Agent | Primary Capability | Secondary Capability |
| --- | --- | --- |
| Decision Gym | Problem Framing、Decision Making | Business Thinking |
| Executive Trade-off | Investment Thinking | Strategic Thinking |
| Strategy Lab | Strategic Thinking、Platform Thinking | Decision Making |
| Reverse Engineering | Business Thinking | Platform Thinking、Investment Thinking |
| Stakeholder Simulation | Influence Thinking | Decision Making |

## 5. User Capability Profile（动态）

Capability Framework 是固定的。真正变化的是：

### Current Capability Profile

| Capability | Level | Confidence | Evidence |
| --- | --- | --- | --- |
| Problem Framing | Stable | High | Decision Gym #12, Strategy Lab #3 |
| Investment Thinking | Emerging | Medium | Executive Trade-off #2 |
| Platform Thinking | Emerging | Low | Strategy Lab #1 |

Agent 每次训练结束：

- 更新 Profile
- 推荐下一次训练
