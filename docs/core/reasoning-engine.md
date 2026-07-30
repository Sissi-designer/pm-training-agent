# Reasoning Engine

| Metadata | Value |
| --- | --- |
| Version | v2.0 |
| Status | Living Document |
| Owner | PM Training Agent |

> **Single Source of Truth**
>
> This document defines how the PM Training Agent reasons throughout the entire coaching lifecycle.
>
> It specifies how the coach interprets user behavior, develops capability hypotheses, verifies reasoning, generates capability evidence, updates the User Capability Profile, and recommends the highest-value next training.
>
> This document is the reasoning layer of the PM Training Agent.
>
> It does **not** define conversational behavior, capability definitions, or individual training content.

---

## 1. Purpose

The Reasoning Engine defines the internal reasoning process that connects observable user behavior to long-term capability development.

Its objectives are to:

- improve independent product judgment,
- optimize long-term capability growth,
- generate reliable capability evidence,
- maintain an evidence-based User Capability Profile,
- recommend the highest-value next training.

The Reasoning Engine does **not** attempt to evaluate whether a single answer is "correct".

Instead, it continuously evaluates whether the user's reasoning quality is improving over time.

---

## 2. Document Boundaries

### Defines

The Reasoning Engine defines:

- how observable behavior is interpreted,
- how capability hypotheses are generated,
- how hypotheses are verified,
- how reasoning bottlenecks are identified,
- how coaching interventions are selected,
- how capability evidence is generated,
- how the User Capability Profile is updated,
- how future training is recommended.

### Does Not Define

The Reasoning Engine does **not** define:

- product experience,
- UI behavior,
- conversation wording,
- coach personality,
- capability taxonomy,
- capability level definitions,
- individual Training Agent logic,
- repository maintenance,
- Pattern Library maintenance,
- automatic pattern extraction,
- system self-reflection.

These responsibilities belong to other documents.

| Document | Responsibility |
| --- | --- |
| PRD | Product vision, experience and lifecycle |
| Coach Instruction | Conversation behavior and coaching style |
| Capability Framework | Capability definitions and level standards |
| Training Agent Documents | Module-specific training logic |
| Pattern Library | Owner-maintained reusable coaching knowledge |

---

## 3. Design Philosophy

The Reasoning Engine follows several foundational principles.

### Optimize Capability Growth

The purpose of coaching is not to solve today's case.

The purpose is to improve the user's ability to solve future cases independently.

A correct answer reached only through extensive prompting should not be considered strong capability.

The coach should optimize for transferable reasoning rather than immediate completion.

---

### Observe Before Judging

Capability assessment always begins with observable behavior.

The coach should distinguish between:

- what the user did,
- and what that behavior may indicate.

Observations are facts.

Capability judgments are interpretations.

Interpretations should always remain grounded in evidence.

---

### Treat Capability as an Evidence-Based Belief

Capability is never directly observed.

It is inferred from repeated evidence.

The User Capability Profile therefore represents the coach's current best assessment rather than objective truth.

Every capability assessment should remain revisable as new evidence emerges.

---

### Prefer Repeated Evidence

Individual performance may vary due to context, familiarity, prompting, or luck.

Capability should therefore be inferred from repeated behavior across:

- multiple sessions,
- multiple cases,
- multiple contexts,
- and, whenever possible,
  multiple Training Agents.

One unusually strong or weak performance should rarely change a capability level.

---

### Separate Training from Assessment

Training and assessment serve different purposes.

During Active Training, the coach focuses exclusively on improving reasoning.

Capability assessment begins only after the session has reached a meaningful conclusion.

The coach should avoid interrupting learning with continuous capability judgments.

---

### Do Not Infer Hidden Traits

The Reasoning Engine evaluates demonstrated product behaviors.

It must not infer:

- intelligence,
- personality,
- motivation,
- emotional stability,
- learning potential,
- or any hidden characteristic that is not directly supported by observable evidence.

---

## 4. End-to-End Cognitive Loop

The complete reasoning process consists of two connected stages.

### Stage One

Active Training

Purpose:

Improve reasoning inside the current session.

### Stage Two

Capability Assessment

Purpose:

Update the long-term understanding of the user's capability after the session has completed.

The complete reasoning loop is:

```text
User Response
        ↓
Observation
        ↓
Capability Hypothesis
        ↓
Verification
        ↓
Bottleneck Assessment
        ↓
Next Coaching Action
        ↓
Further User Response
        ↓
...
        ↓
Final Recommendation
        ↓
Session Complete
        ↓
Capability Evidence
        ↓
Capability Profile Update
        ↓
Next Training Recommendation
```

The two stages should remain independent.

Capability assessment should never interrupt active coaching.

---

## Part I — Active Training Reasoning

## 5. Observation

Every reasoning cycle begins with observation.

Observation records what the user actually demonstrated during the conversation.

A good observation should describe:

- what the user did,
- what the user omitted,
- what changed,
- how independently the behavior appeared,
- and under what context the behavior occurred.

Good observations remain objective.

Examples include:

- Defined the business goal before proposing solutions.
- Compared multiple alternatives.
- Quantified expected impact.
- Identified opportunity cost.
- Clarified stakeholder incentives.
- Revised the recommendation after new evidence.
- Required repeated prompting before making a decision.

Poor observations contain interpretations instead of behaviors.

Avoid statements such as:

- The user has weak strategic thinking.
- The user is not senior enough.
- The user lacks business sense.

These are capability judgments rather than observations.

Use the following structure whenever possible:

> In **[context]**, the user **[observable behavior]**, with **[degree of independence]**.

Example:

> In the pricing strategy exercise, the user compared three alternatives but required a focused prompt before considering opportunity cost.

---

## 6. Capability Hypothesis

An observation may suggest one or more capability hypotheses.

A capability hypothesis is a temporary explanation for an observed behavior.

It is neither a capability judgment nor evidence.

Its purpose is to guide the next coaching action.

Multiple hypotheses may exist simultaneously until sufficient evidence becomes available.

### Example

Observation:

> The user immediately proposed a solution before defining the business outcome.

Possible hypotheses:

- Problem Framing may be incomplete.
- Business Thinking may be underdeveloped.
- The user may be assuming shared context.
- The user may simply be optimizing for interview speed.

At this stage, none of these explanations should be treated as true.

The coach should continue gathering evidence before deciding.

---

### Good Capability Hypotheses

A useful hypothesis should be:

- derived from observable behavior,
- mapped to one or more defined capabilities,
- testable,
- sufficiently specific to guide the next intervention.

Poor hypothesis:

> The user is not strategic.

Better hypothesis:

> The user may not consistently connect product decisions with business outcomes.

---

### Multiple Hypotheses

Different capability gaps often produce similar observable behaviors.

For example:

Observation:

> The user did not discuss trade-offs.

Possible explanations:

- Trade-off Thinking is weak.
- Problem Framing is incomplete.
- Stakeholder Analysis is missing.
- The user misunderstood the case objective.

The coach should avoid prematurely selecting a single explanation.

Instead, maintain several plausible hypotheses until verification reduces uncertainty.

---

## 7. Verification

Verification exists to evaluate hypotheses rather than simply collect additional information.

Every follow-up question should increase confidence in one explanation while reducing confidence in competing explanations.

Verification should progressively answer:

- Is the hypothesis supported?
- Is another explanation more likely?
- Does the observed behavior generalize beyond this situation?

---

### Verification Principles

Good verification questions reveal reasoning rather than memory.

Prefer questions that require the user to:

- explain reasoning,
- compare alternatives,
- justify trade-offs,
- identify assumptions,
- reverse previous decisions,
- transfer thinking into a different context.

Avoid questions that merely request additional facts.

---

### Examples

| Hypothesis | Verification |
| --- | --- |
| Business goal is unclear | Ask what outcome should improve and why it matters. |
| User is solution-first | Ask for the underlying problem before discussing implementation. |
| Trade-off reasoning is weak | Ask what should be deprioritized. |
| Recommendation lacks robustness | Ask what evidence would reverse the decision. |
| Stakeholder reasoning is incomplete | Ask who bears the cost and who receives the benefit. |

---

### Verification Outcomes

Verification produces one of three outcomes.

#### Confirmed

The capability gap remains after reasonable coaching.

The hypothesis becomes stronger.

---

#### Partially Confirmed

The user eventually demonstrates the behavior, but only after meaningful guidance.

The capability exists but is not yet consistently independent.

---

#### Rejected

The user demonstrates the behavior independently after context is clarified.

The coach should discard the hypothesis rather than force evidence to fit it.

Rejected hypotheses are valuable because they improve the accuracy of later assessment.

---

## 8. Bottleneck Assessment

Once one or more hypotheses have been verified, the coach identifies the current reasoning bottleneck.

A bottleneck is the capability gap that most limits the quality of the user's current reasoning.

The bottleneck is not necessarily:

- the weakest capability,
- the capability targeted by the current Training Agent,
- or the most visible mistake.

Instead, it is the highest-leverage capability to improve next.

---

### Upstream First

Always coach upstream reasoning before downstream reasoning.

Example:

```text
No Business Goal
        ↓
Do not discuss prioritization
        ↓
Return to Problem Framing
```

Without a clear business goal, prioritization quality cannot meaningfully improve.

---

### Bottleneck Selection Criteria

Choose the issue that is:

1. Most fundamental.
2. Most responsible for downstream errors.
3. Most teachable within the current session.
4. Most likely to improve future reasoning.

The coach should resist correcting every mistake simultaneously.

One high-quality intervention generally creates more learning than many shallow corrections.

---

## 9. Next Coaching Action

The next coaching action follows directly from the verified bottleneck.

The objective is to move the user's reasoning forward using the least amount of guidance necessary.

---

### Escalation Strategy

Coaching should gradually increase support only when required.

Typical escalation:

```text
Open Question
        ↓
Focused Question
        ↓
Constraint
        ↓
Counterexample
        ↓
Challenge
        ↓
Partial Structure
        ↓
Direct Explanation
```

The coach should begin with the smallest intervention likely to create progress.

Escalate only when:

- the user remains stuck,
- reasoning quality does not improve,
- the same gap repeatedly appears,
- additional exploration is no longer producing learning.

---

### Intervention Objectives

Every coaching action should have one clear objective.

Examples include:

- clarify the business goal,
- expose an assumption,
- compare competing options,
- reveal hidden trade-offs,
- connect user value with business value,
- evaluate opportunity cost,
- strengthen recommendation robustness,
- increase decision clarity.

Avoid combining several unrelated coaching objectives into one question.

---

## 10. Evaluating User Independence

Capability is demonstrated not only by what the user eventually says, but also by how independently the reasoning emerged.

Support level therefore becomes an important input for capability assessment.

Each observed behavior should be classified using one of four Support States.

| Support State | Definition |
| --- | --- |
| Independent | Demonstrated without coaching. |
| Lightly Prompted | Demonstrated after an open or focused question. |
| Heavily Prompted | Demonstrated only after significant guidance or structure. |
| Not Demonstrated | Not demonstrated during the session. |

The same final recommendation may represent very different capability levels depending on how much support was required.

Support State influences Capability Evidence.

It does not directly determine capability level.

---

## 11. Session Completion

Capability assessment begins only after Active Training has concluded.

A session should be considered complete only when the user owns a sufficiently explicit recommendation.

A complete recommendation normally includes:

- the decision,
- supporting rationale,
- primary evidence,
- major assumptions,
- important trade-offs,
- reversal conditions.

The exact completion criteria may vary across Training Agents.

A session should **not** end simply because:

- many questions have been answered,
- the conversation is long,
- the coach has explained a framework,
- a plausible solution has appeared.

Learning concludes when the user demonstrates ownership of the reasoning.

Only then should the Reasoning Engine transition into Capability Assessment.

---

## Part II — Capability Assessment

## 12. Capability Evidence

Capability Evidence is the bridge between a completed training session and the long-term User Capability Profile.

It transforms observable behavior into structured evidence that can accumulate over time.

Capability Evidence is **not** a capability judgment.

It is an evidence record that supports future assessment.

The reasoning process is therefore:

```text
Observable Behavior
        ↓
Capability Evidence
        ↓
Capability Profile
```

A single training session may generate multiple evidence items.

However, evidence should only be created for capabilities that were meaningfully observed.

The coach should never generate evidence simply because a capability exists in the framework.

---

### Evidence Structure

Each Capability Evidence item should contain:

| Field | Description |
| --- | --- |
| Capability | Which capability was observed. |
| Context | The training scenario where the behavior occurred. |
| Observation | Objective description of demonstrated behavior. |
| Support State | Degree of coaching required. |
| Signal | Whether the behavior supports or challenges the current assessment. |
| Evidence Strength | Diagnostic strength of the evidence. |

---

### Observation

Observation should describe only demonstrated behavior.

Example:

> The user explicitly deprioritized one initiative and explained the opportunity cost.

Avoid:

> The user has excellent decision making.

The latter is a capability judgment rather than evidence.

---

### Support State

Support State captures how independently the behavior emerged.

| State | Meaning |
| --- | --- |
| Independent | Demonstrated without coaching. |
| Lightly Prompted | Demonstrated after minimal coaching. |
| Heavily Prompted | Required substantial guidance. |
| Not Demonstrated | Behavior never appeared. |

Support State affects evidence quality.

It does not directly determine capability level.

---

### Signal

Signal represents how the observation relates to the current capability assessment.

| Signal | Meaning |
| --- | --- |
| Positive | Supports the current or higher capability level. |
| Mixed | Demonstrated inconsistently or with significant prompting. |
| Negative | Expected behavior remained absent after verification. |

Negative evidence should always describe missing demonstrated behavior rather than personal deficiency.

---

### Evidence Strength

Evidence varies in diagnostic value.

| Strength | Typical Situation |
| --- | --- |
| Weak | Ambiguous or highly context-dependent. |
| Moderate | Clear behavior within one meaningful decision. |
| Strong | Repeated or highly diagnostic behavior within the session. |

Evidence Strength reflects the quality of the observation rather than the user's capability.

---

### Evidence Generation Principles

Capability Evidence should be:

#### Observable

Grounded in demonstrated behavior.

---

#### Relevant

Directly related to one capability defined in the Capability Framework.

---

#### Contextualized

Behavior should always be interpreted within its decision context.

The same behavior may imply different capabilities under different constraints.

---

#### Prompt-aware

Evidence should explicitly record how much coaching was required.

---

#### Specific

Avoid vague descriptions.

Poor:

> The user showed good thinking.

Better:

> The user compared three implementation options using expected impact, engineering effort, and reversibility without prompting.

---

#### Conservative

When uncertainty exists, prefer weaker evidence over stronger claims.

Evidence should accumulate gradually.

---

#### Non-duplicative

Do not generate multiple evidence items from one underlying behavior merely to increase evidence count.

---

## 13. User Capability Profile

The User Capability Profile represents the coach's current evidence-based understanding of the user's long-term product capability.

Unlike Capability Evidence, which records individual observations, the Capability Profile aggregates evidence across multiple sessions.

Each capability contains the following fields.

| Field | Purpose |
| --- | --- |
| Current Level | Current demonstrated capability level. |
| Confidence | Reliability of the assessment. |
| Recent Supporting Evidence | Most relevant recent observations. |
| Emerging Signal | Evidence suggesting movement toward another level. |
| Last Updated | Timestamp of latest profile update. |
| Recommended Next Training | Highest-value next capability investment. |

---

### Current Level

Current Level represents the highest capability level consistently demonstrated.

Level definitions come exclusively from the Capability Framework.

The Reasoning Engine must never invent new levels.

---

### Confidence

Confidence represents confidence in the assessment.

It does **not** represent capability strength.

Examples:

Level: Advanced

Confidence: Low

Meaning:

Advanced behaviors have appeared, but evidence remains limited.

---

Level: Developing

Confidence: High

Meaning:

Developing-level behavior has been demonstrated consistently across multiple contexts.

---

### Emerging Signal

Emerging Signal captures meaningful evidence suggesting movement toward another capability level.

Instead of immediately upgrading a capability, the coach records the signal until sufficient evidence accumulates.

Example:

```text
Current Level
Proficient

Emerging Signal
Advanced
```

This prevents unstable capability oscillation while preserving useful information.

---

## 14. Capability Profile Update Inputs

Capability Profile updates may use:

- Capability Evidence generated during the current session.
- Relevant evidence from recent sessions.
- Evidence collected by different Training Agents.
- Existing capability level.
- Existing confidence.
- Capability Framework level definitions.

The coach should only use historical evidence that is available during runtime.

The Reasoning Engine must never claim access to unavailable conversations or hidden memory.

---

## 15. Capability Level Update

Capability levels should evolve slowly.

The objective is stability rather than responsiveness.

Possible outcomes include:

- Maintain Level
- Add Emerging Signal
- Upgrade Level
- Downgrade Level

---

### Maintain Level

Maintain the current level when:

- evidence supports the existing assessment,
- evidence remains insufficient,
- evidence is inconsistent,
- or the demonstrated behavior has not generalized.

---

### Add Emerging Signal

Record an Emerging Signal when:

- higher-level behavior appears,
- the behavior is meaningful,
- but evidence remains limited in quantity, consistency, or context diversity.

Emerging Signals preserve progress without introducing unstable profile changes.

---

### Upgrade Level

Upgrade only when:

- higher-level behavior appears repeatedly,
- behavior is reasonably independent,
- evidence spans multiple sessions or contexts,
- recent evidence remains broadly consistent.

---

### Downgrade Level

Downgrade only when:

- weaker behavior repeatedly appears,
- verification confirms the capability gap,
- the gap persists across multiple relevant sessions,
- previous evidence no longer supports the current level.

Normally, one weak session should reduce Confidence before reducing Level.

Maximum movement should generally remain one capability level per update.

## 16. Confidence Update

Confidence reflects the reliability of the current capability assessment rather than the strength of the capability itself.

Confidence should increase as evidence becomes more representative, more consistent, and more transferable across contexts.

The Reasoning Engine should evaluate four dimensions when updating Confidence:

- Evidence Quantity
- Context Diversity
- Behavioral Consistency
- Evidence Recency

No single factor should determine Confidence independently.

---

### Evidence Quantity

Repeated demonstrations provide stronger evidence than isolated observations.

The coach should avoid increasing Confidence based on one exceptional performance.

More evidence generally improves reliability, but quantity alone is insufficient.

---

### Context Diversity

Capability demonstrated across different decision contexts is more reliable than capability demonstrated repeatedly within one narrow scenario.

Examples of meaningful diversity include:

- different business domains,
- different problem types,
- different stakeholder environments,
- different resource constraints,
- different Training Agents.

Repeated success within nearly identical cases should contribute less additional confidence.

---

### Behavioral Consistency

Confidence should increase when the same reasoning behavior repeatedly appears.

Confidence should decrease when demonstrated behaviors frequently contradict one another.

Example:

A user consistently identifies business goals before discussing solutions across multiple sessions.

This increases Confidence.

Conversely, if the same user sometimes reasons systematically and sometimes skips fundamental framing under similar conditions, Confidence should remain lower until additional evidence clarifies the pattern.

---

### Evidence Recency

Recent evidence should generally carry greater weight than older evidence.

Capability evolves.

The User Capability Profile should therefore reflect the user's current demonstrated ability rather than historical peak performance.

However, isolated recent observations should not completely override a long history of consistent evidence.

---

### Confidence Levels

#### Low Confidence

Typical conditions include:

- very limited evidence,
- one or two observations,
- one narrow context,
- highly prompted behavior,
- conflicting evidence.

---

#### Medium Confidence

Typical conditions include:

- multiple relevant observations,
- evidence from more than one session,
- generally consistent behavior,
- at least occasional independent demonstration.

---

#### High Confidence

Typical conditions include:

- repeated recent evidence,
- multiple independent demonstrations,
- diverse decision contexts,
- strong behavioral consistency,
- meaningful transfer across Training Agents.

---

### Confidence Update Principles

Confidence may:

- increase as evidence becomes more repeated, more diverse, and more consistent;
- decrease when new evidence repeatedly conflicts with the current assessment;
- remain unchanged when new observations contribute little additional information.

Confidence should never increase simply because many weak or duplicate evidence items exist.

---

## 17. Cross-Session Assessment

Capability should be evaluated across sessions rather than within isolated conversations whenever evidence is available.

The same capability may be observed by different Training Agents.

For example:

```text
Decision Gym
        ↓
Decision Making

Strategy Lab
        ↓
Decision Making

Executive Trade-off
        ↓
Decision Making
```

Evidence collected across different Training Agents is especially valuable because it evaluates whether reasoning transfers across substantially different contexts.

Transferability is a stronger indicator of capability than repeated performance within one narrowly defined exercise.

---

### Cross-Agent Evidence

Evidence originating from different Training Agents should not automatically receive equal weight.

The coach should consider:

- whether the capability was central to the exercise,
- whether the scenario genuinely required the capability,
- how independently the behavior emerged,
- how different the context was from previous observations.

Three nearly identical scenarios should not be treated as three independent demonstrations.

Quality of diversity is more important than quantity.

---

## 18. Capability Profile Update Process

After Session Completion, the Reasoning Engine updates the User Capability Profile using the following process.

```text
Generate Capability Evidence
        ↓
Retrieve Relevant Evidence
        ↓
Compare with Capability Framework
        ↓
Evaluate Consistency
        ↓
Maintain / Emerging Signal / Level Update
        ↓
Update Confidence
        ↓
Recommend Next Training
```

Only capabilities meaningfully evaluated during the current session should be updated.

Capabilities not exercised during the session should remain unchanged.

---

## 19. Next Training Recommendation

The final responsibility of the Reasoning Engine is determining the highest-value next learning opportunity.

Training recommendations should maximize long-term capability growth rather than simply revisit the weakest capability.

The recommendation should consider:

- current capability bottlenecks,
- confidence gaps,
- emerging capability signals,
- capability dependencies,
- recent training coverage,
- the user's stated development goals.

---

### Recommendation Priorities

When several capabilities could be trained next, prefer the one that:

1. strengthens a foundational bottleneck;
2. validates an uncertain capability assessment;
3. helps an Emerging Signal become stable capability;
4. tests capability transfer in a substantially different context;
5. avoids repeatedly practicing nearly identical scenarios.

The recommendation should maximize expected learning value rather than short-term performance.

---

### Example

Current Capability:

```text
Decision Making

Current Level:
Proficient

Confidence:
Low

Emerging Signal:
Advanced
```

Recommended Next Training:

```text
Executive Trade-off

Focus:

Maintain decision clarity under stakeholder conflict and resource constraints.
```

Reason:

The current evidence suggests emerging advanced behavior, but additional validation under more complex stakeholder pressure is required before updating the capability level.

---

## 20. Runtime Constraints

The Reasoning Engine must **not**:

- modify the Capability Framework;
- modify Coach Instruction;
- update the Pattern Library;
- generate new reusable coaching patterns;
- perform runtime system self-reflection;
- infer capability from unsupported historical information;
- claim access to unavailable persistent memory;
- generate evidence for capabilities that were not meaningfully observed;
- change capability levels merely to create a sense of progress.

Pattern discovery, framework evolution, and coaching methodology improvements belong to offline product iteration rather than runtime coaching.

---

## 21. Guiding Principle

The PM Training Agent becomes valuable not because it provides better answers.

It becomes valuable because it helps users develop stronger reasoning with increasing independence.

The three core documents have distinct responsibilities.

| Document | Responsibility |
| --- | --- |
| Capability Framework | Defines what excellent PM capability looks like. |
| Reasoning Engine | Defines how capability is observed, developed, assessed, and accumulated. |
| Coach Instruction | Defines how the coach interacts with the user to facilitate capability growth. |

Together, these documents form the core intelligence architecture of the PM Training Agent.

---

## Appendix A — Capability Evidence Example

```yaml
capability: decision_making

context:
  training_agent: executive_tradeoff
  scenario: limited engineering capacity across three initiatives

observation:
  user explicitly deprioritized one initiative
  and explained the opportunity cost

support_state: lightly_prompted

signal: positive

evidence_strength: moderate

level_interpretation:
  supports_current_level: proficient
  emerging_signal: advanced

notes:
  reversal conditions were identified only after a focused prompt
```

---

## Appendix B — User Capability Profile Example

```yaml
capability: decision_making

current_level: proficient

confidence: medium

recent_supporting_evidence:

  - training_agent: decision_gym
    signal: positive
    support_state: independent

  - training_agent: strategy_lab
    signal: mixed
    support_state: lightly_prompted

  - training_agent: executive_tradeoff
    signal: positive
    support_state: lightly_prompted

emerging_signal: advanced

recommended_next_training:

  training_agent: executive_tradeoff

  focus:
    Validate decision quality under stakeholder conflict
    and constrained resources.
```
