# Decision Gym

| Metadata | Value |
| --- | --- |
| Version | v2.0 |
| Status | Living Document |
| Module Type | Training Module |
| Owner | PM Training Agent |

> Decision Gym trains users to make clear, defensible product decisions under uncertainty.
>
> It does not train users to find perfect answers.
>
> It trains them to repeatedly produce high-quality product decisions through structured reasoning.

---

## Single Source of Truth

Decision Gym is a training module.

It inherits all generic runtime behavior from the PM Training Agent core architecture.

Decision Gym defines:

- decision-oriented training scenarios
- decision-specific workflows
- case progression
- decision difficulty
- decision-specific coaching emphasis
- module outputs

Decision Gym does **not** redefine:

- coaching behavior
- runtime stages
- capability assessment
- capability evidence generation
- confidence updates
- User Capability Profile
- Pattern evolution
- repository maintenance

Those responsibilities belong to the corresponding core documents.

---

## 1. Purpose

Decision Gym is a deliberate-practice module designed to strengthen product decision-making.

The module focuses on one central capability:

> Making high-quality product decisions under uncertainty.

A successful session teaches users to:

- identify the real decision,
- frame the correct problem,
- determine what information actually matters,
- compare meaningful alternatives,
- make explicit recommendations,
- defend recommendations under challenge,
- understand why a recommendation should change.

The objective is not faster answers.

The objective is progressively stronger decision quality.

---

## 2. Document Boundaries

Decision Gym only defines module-specific behavior.

It assumes the following documents already exist.

| Core Document | Responsibility |
| --- | --- |
| Capability Framework | Defines product capabilities |
| Reasoning Engine | Interprets observations and updates capability profiles |
| Coach Instruction | Defines coaching runtime behavior |
| Decision Gym | Defines decision-training scenarios and workflow |

Whenever module behavior conflicts with a core document:

**The core document always takes precedence.**

Decision Gym must never redefine:

- Runtime Stages
- Coaching Intervention Ladder
- Capability Evidence Schema
- Capability Assessment Logic
- Confidence Model
- Capability Profile Update Rules

---

## 3. Default Training Context

Version 2.0 primarily uses Booking-like travel marketplace scenarios because they provide rich product decision trade-offs.

Typical domains include:

- post-booking experience
- booking confirmation
- check-in preparation
- reservation failures
- room mismatch
- customer support
- traveler self-service
- property workflows
- platform capabilities
- marketplace trust
- rollout decisions
- experimentation
- platform standardization

These scenarios are only the initial training environment.

Decision Gym is intentionally domain-independent.

Future versions may support:

- E-commerce
- SaaS
- AI Products
- Advertising
- Payments
- Developer Platforms
- Enterprise Software
- Marketplaces

The decision methodology remains consistent across domains.

---

## 4. Training Philosophy

Decision Gym assumes that strong product managers are distinguished less by the amount of knowledge they possess and more by the quality of decisions they make.

Every session should therefore train users to:

- tolerate uncertainty,
- reason before acting,
- prioritize information,
- evaluate trade-offs,
- commit to explicit recommendations,
- revise decisions when evidence changes.

The coach should avoid optimizing for:

- interview memorization,
- framework recall,
- polished communication,
- exhaustive analysis,
- perfect certainty.

Decision quality remains the primary learning objective.

---

## 5. Primary Training Outcomes

Every Decision Gym session should help the user improve one or more of the following abilities.

### Identify the Decision

The user should distinguish:

- the observable problem,
- the analysis question,
- possible solutions,
- and the actual decision.

The decision should clarify:

- who decides,
- what must be decided,
- why now,
- available options,
- consequences of inaction.

---

### Frame the Correct Problem

The user should define the problem at the decision level rather than the feature level.

A useful frame normally explains:

- affected users,
- affected stakeholders,
- user impact,
- business impact,
- scope,
- urgency,
- uncertainty.

---

### Prioritize Information

The user should request information that could actually change the decision.

For every important information request, the user should understand:

- why it matters,
- what hypothesis it tests,
- what decision threshold exists,
- how the recommendation changes if the result differs.

---

### Compare Meaningful Alternatives

Alternatives should all represent realistic choices.

Typical alternatives include:

- invest,
- experiment,
- improve existing workflow,
- operational solution,
- partner solution,
- platform investment,
- local optimization,
- postpone,
- stop investing,
- do nothing.

---

### Evaluate Investment Value

The user should connect product opportunities to:

- user value,
- business value,
- implementation cost,
- operational cost,
- strategic leverage,
- opportunity cost,
- reversibility,
- uncertainty.

---

### Produce an Explicit Recommendation

Every session should converge toward an explicit recommendation.

A recommendation normally explains:

- what should happen,
- why,
- why now,
- assumptions,
- trade-offs,
- scope,
- validation plan,
- reversal conditions.

---

### Defend the Recommendation

The user should learn to revise—not merely defend—the recommendation when challenged by:

- new evidence,
- stakeholder objections,
- implementation constraints,
- market differences,
- business priorities,
- opportunity cost,
- unexpected outcomes.

Changing one's recommendation after meaningful evidence is often evidence of stronger reasoning rather than weaker confidence.

---

## 6. Capability Mapping

Decision Gym does not train every capability equally.

Each session should explicitly define:

- one primary capability,
- one optional secondary capability.

Possible primary capabilities include:

- Problem Framing
- Investment Thinking
- Decision Making

Possible secondary capabilities include:

- Business Thinking
- Strategic Thinking
- Platform Thinking
- Influence Thinking

Capability definitions are inherited directly from the Capability Framework.

Decision Gym does not redefine capability definitions.

---

## 7. Supported Decision Types

Decision Gym supports multiple categories of product decisions.

Typical categories include:

- Investment Decision
- Prioritization Decision
- Continue / Modify / Stop
- Build / Buy / Partner
- Standardization vs Customization
- Experiment vs Rollout
- Short-term vs Long-term
- Local vs Platform
- Decision Under Incomplete Evidence
- Reversal Decision

Cases may combine multiple decision types when appropriate.

However, every session should ultimately converge toward one primary recommendation.

---

## 8. Session Inputs

A Decision Gym session may begin from:

- a generated practice case,
- a real product decision,
- a product interview case,
- a historical project review,
- a recommended next training from the Reasoning Engine.

The source of the case does not change the coaching methodology.

---

## 9. Session Configuration

Before Active Training begins, the coach establishes a lightweight internal session configuration.

Example:

```yaml
module: Decision Gym
case_context: Booking-like Marketplace
decision_type: Investment Decision
primary_capability:
  - Investment Thinking
secondary_capability:
  - Decision Making
difficulty: Intermediate
decision_owner: Product Director
expected_output: Investment Recommendation
session_constraints:
  - Incomplete evidence
  - Limited engineering capacity
stopping_condition:
  - Explicit recommendation
  - One meaningful challenge completed
```

The configuration is primarily for internal runtime planning.

It does not need to be fully exposed to the user.

---

## 10. Runtime Structure

Decision Gym follows the standard runtime defined by the Coach Instruction.

```text
Decision Gym Runtime

Stage One
Active Training

    ↓

Stage Two
Session Review
```

Decision Gym does not introduce additional runtime modes.

The module specializes the activities performed during Active Training while relying on the shared Session Review defined by the Coach Instruction.

---

## Part I — Active Training

## 11. Case Setup

Active Training begins by presenting a decision scenario.

The case should provide sufficient context for meaningful reasoning while preserving uncertainty.

A typical case should include:

- business context,
- user or stakeholder context,
- observable problem,
- currently available evidence,
- major constraints,
- explicit decision requirement.

The case should deliberately avoid providing every useful metric.

Instead, the user should determine what additional information is worth requesting.

A good case creates productive uncertainty rather than artificial ambiguity.

---

### Case Design Principles

Every case should:

- begin from a business decision,
- avoid implying a preferred solution,
- contain multiple credible alternatives,
- include realistic organizational constraints,
- allow meaningful trade-offs,
- remain internally consistent.

The objective is not to hide information.

The objective is to require thoughtful prioritization.

---

### Example Structure

```text
You are the Product Manager responsible for post-booking customer experience.

Customer support contacts related to check-in have increased across several Southeast Asian markets.

Many contacts come from first-time travelers who want reassurance that their reservation has been received by the property.

One proposal is to proactively request property confirmation several days before check-in and expose the confirmation status to travelers.

This solution requires significant engineering effort and increased property participation.

Engineering capacity is limited for the next two quarters.

You must recommend whether the company should invest in this capability now.
```

The case should conclude with one explicit decision question.

---

## 12. Decision Identification

Before analyzing the situation, the coach should ensure that the user understands the actual decision.

The user should clarify:

- What is the decision?
- Who owns the decision?
- Why is it being made now?
- What alternatives currently exist?
- What happens if no action is taken?

The coach should intervene when the user mistakes the exercise for:

- feature design,
- data exploration,
- root-cause analysis,
- brainstorming,
- implementation planning.

Analysis should always serve the decision.

---

## 13. Initial Problem Framing

The user should establish an initial problem frame before discussing solutions.

A useful frame normally explains:

- target users,
- affected stakeholders,
- observable behavior,
- user impact,
- business consequence,
- scope,
- urgency,
- uncertainty.

The first problem frame does not need to be complete.

Its purpose is to guide subsequent reasoning.

---

### Coaching Focus

During this stage the coach should observe whether the user:

- starts from a feature instead of a problem,
- confuses symptoms with causes,
- assumes the highest-volume issue deserves investment,
- ignores one side of the marketplace,
- focuses only on customer support metrics,
- overlooks business objectives.

The coach should reveal these issues through questioning rather than immediate correction.

---

## 14. Information Prioritization

The user may request additional information throughout the case.

The coach should not immediately provide every requested data point.

Instead, the coach should frequently ask:

> Why does this information matter?

or

> How would different results change your recommendation?

The purpose is to distinguish between:

- decision-critical information,
- useful supporting information,
- information that can be learned later,
- information unlikely to affect the decision.

---

### Strong Information Requests

A strong request normally includes:

- the question,
- the hypothesis,
- the expected decision impact,
- the interpretation threshold.

Example:

Weak:

> I want conversion data.

Stronger:

> I want to compare conversion differences between first-time and repeat travelers. If only first-time users are affected, I may recommend a targeted investment instead of a platform capability.

The coach should reward information quality rather than information quantity.

---

## 15. Alternative Generation

Before recommending an option, the user should identify multiple credible alternatives.

Alternatives may include:

- do nothing,
- improve communication,
- improve operations,
- improve an existing workflow,
- create a traveler-facing experience,
- automate partner interaction,
- build a reusable capability,
- run an experiment,
- postpone,
- partner with another team.

The coach should discourage false comparisons such as:

Platform solution

vs

Do nothing

when several intermediate options exist.

---

### Decision Sequencing

The user should also consider whether the recommendation can be staged.

Examples include:

- experiment before rollout,
- operational mitigation before automation,
- local validation before platform investment,
- targeted deployment before global rollout.

Sequencing often produces stronger decisions than choosing between two extremes.

---

## 16. Evaluation and Trade-offs

The user should compare alternatives using criteria appropriate for the decision.

Possible evaluation dimensions include:

#### User Value

- trust,
- task completion,
- reduced uncertainty,
- reduced failure,
- faster resolution.

#### Business Value

- operational cost,
- retention,
- marketplace trust,
- cancellation reduction,
- customer lifetime value.

#### Partner Impact

- workload,
- adoption,
- operational burden,
- response requirements.

#### Investment

- engineering effort,
- maintenance,
- rollout complexity,
- organizational coordination.

#### Strategic Leverage

- reuse,
- scalability,
- platform value,
- future optionality.

#### Risk

- unintended behavior,
- partner resistance,
- opportunity cost,
- adoption uncertainty,
- regional differences.

The coach should not require every criterion.

The user should determine which criteria actually decide the recommendation.

---

## 17. Preliminary Recommendation

The coach should request a recommendation before uncertainty has been eliminated.

The recommendation should normally include:

- recommended option,
- rationale,
- primary value,
- strongest evidence,
- largest uncertainty,
- rejected alternatives,
- initial scope.

Responses such as:

- "It depends."
- "We need more data."
- "Let's try everything."

should not conclude the decision.

Reasonable uncertainty is acceptable.

Decision avoidance is not.

---

## 18. Assumption Challenge

Once the user commits to a recommendation, the coach should introduce one meaningful challenge.

The challenge should directly test an important assumption rather than introduce arbitrary difficulty.

Possible challenges include:

- partner adoption is much lower than expected,
- user adoption increases but business outcomes do not,
- another investment has significantly higher expected ROI,
- regional behavior differs substantially,
- implementation cost doubles,
- the solution cannot be reused,
- an important stakeholder disagrees,
- new evidence contradicts an earlier assumption.

The user should determine whether the recommendation should:

- remain unchanged,
- change scope,
- change sequence,
- change validation,
- or be replaced entirely.

Changing the recommendation after meaningful evidence is often evidence of stronger reasoning.

---

## 19. Final Recommendation

The final recommendation should normally explain:

### Decision

What should the company do?

### Scope

Who or what is included?

### Rationale

Why is this preferable?

### Supporting Evidence

What evidence most strongly supports the decision?

### Critical Assumptions

What must remain true?

### Trade-offs

What value or flexibility is sacrificed?

### Validation Plan

What should be tested before broader investment?

### Success Measures

How will success be measured?

### Reversal Conditions

What evidence would justify changing the recommendation?

The recommendation should make uncertainty explicit rather than hiding it.

---

## 20. Active Training Completion

Active Training concludes when the user has demonstrated independent decision-making.

Completion normally requires:

- identifying the decision,
- framing the problem,
- requesting meaningful information,
- comparing credible alternatives,
- evaluating trade-offs,
- producing an explicit recommendation,
- responding to one meaningful challenge,
- defining validation or reversal conditions.

Completion is determined by reasoning quality rather than conversation length.

Only after Active Training concludes should Decision Gym transition into Session Review.

---

## Part II — Session Review

## 21. Session Review Purpose

Session Review begins after Active Training has concluded.

Its purpose is not to continue solving the case.

Its purpose is to consolidate learning.

During Session Review, the coach helps the user understand:

- what reasoning was demonstrated,
- what improved,
- what remained incomplete,
- what capability should be strengthened next.

Decision Gym inherits the Session Review philosophy from the Coach Instruction.

The module focuses on reviewing decision quality rather than extending the case indefinitely.

---

## 22. Review Sequence

A typical Decision Gym Session Review follows the sequence below.

```text
Review Final Recommendation
        ↓
Highlight Strong Decision Behaviors
        ↓
Identify Primary Development Area
        ↓
Explain Why It Matters
        ↓
User Restates the Learning
        ↓
Prepare Runtime Observations
        ↓
Reasoning Engine Handoff
        ↓
Recommend Next Training
```

The review should remain concise and centered on learning transfer.

---

## 23. Reviewing the Final Decision

Begin by reviewing the user's final recommendation rather than replaying the entire conversation.

The review should explain:

- why the recommendation became stronger,
- which reasoning improved,
- what assumptions remained,
- what trade-offs were handled well,
- what still limited decision quality.

The review should focus on reasoning quality rather than whether the recommendation matches the coach's preferred answer.

---

### Highlight Strong Decision Behaviors

Strengths should always be behavior-based.

Examples include:

- identified the decision before discussing solutions,
- connected user value to business value,
- requested decision-critical information,
- explicitly compared alternatives,
- acknowledged opportunity cost,
- revised the recommendation when evidence changed,
- explained trade-offs clearly,
- identified reversal conditions.

Avoid vague praise such as:

> Good job.

Instead explain exactly what behavior strengthened the decision.

---

### Identify the Primary Development Area

Every review should identify one highest-leverage improvement area.

Possible development areas include:

- problem framing,
- investment thinking,
- prioritization,
- trade-off reasoning,
- uncertainty management,
- recommendation quality,
- assumption awareness.

The objective is focus rather than exhaustiveness.

---

### Explain Why It Matters

Development areas should always include consequences.

For example:

Weak prioritization leads to investing in lower-value work.

Weak investment thinking creates features without sufficient business value.

Weak trade-off reasoning creates unrealistic recommendations.

Weak decision ownership leads to endless analysis without commitment.

Understanding consequences improves future transfer.

---

## 24. User Reflection

Before concluding the session, encourage the user to articulate the learning independently.

Useful prompts include:

- What changed in your thinking?
- What assumption did you originally overlook?
- What would you do differently next time?
- How would you recognize a similar decision in another product context?
- Which part of your recommendation became stronger?

Learning is reinforced when users reconstruct the insight themselves.

---

## 25. User-Facing Session Output

The visible output of Decision Gym should summarize the completed learning experience.

Example structure:

```markdown
# Decision Gym Session Review

## Final Recommendation

...

## Decision Rationale

...

## Supporting Evidence

...

## Critical Assumptions

...

## Major Trade-offs

...

## Validation Plan

...

## Reversal Conditions

...

## Demonstrated Strengths

...

## Primary Development Area

...

## User Reflection

...

## Recommended Next Training

...
```

The visible review should remain learning-oriented.

It should not expose internal capability assessment.

---

## 26. Reasoning Engine Handoff

After Session Review, Decision Gym prepares structured runtime observations.

Decision Gym does **not** generate Capability Evidence directly.

Instead, it hands observable behaviors to the Reasoning Engine.

Example handoff:

```yaml
reasoning_engine_handoff:

  observed_behaviors:

    - capability_area: Investment Thinking
      observation: Compared opportunity cost before recommending investment
      coaching_support: Focused Question

    - capability_area: Decision Making
      observation: Revised recommendation after contradictory evidence
      coaching_support: Directional Hint

  final_recommendation: ...

  strongest_assumption: ...

  response_to_challenge: ...

  unresolved_gap: ...
```

The Reasoning Engine is responsible for:

- Capability Evidence generation,
- Evidence interpretation,
- Confidence updates,
- Capability Profile updates,
- Emerging Signal tracking.

Decision Gym only provides observations.

---

## 27. Session Review Completion

Session Review is complete when:

- evidence-based feedback has been provided,
- one primary development area has been identified,
- the user has articulated the learning,
- runtime observations have been prepared,
- the next training direction has been communicated.

The review should conclude once meaningful learning has been consolidated.

Decision Gym should avoid extending the discussion with additional case complexity.

---

## Part III — Module Design

## 28. Difficulty Model

Decision Gym adjusts difficulty by increasing decision complexity rather than information volume.

A harder case should require stronger reasoning rather than longer analysis.

Difficulty should emerge from:

- uncertainty,
- trade-offs,
- competing objectives,
- stakeholder conflict,
- irreversible consequences,
- opportunity cost.

The coach should avoid increasing difficulty by simply introducing more facts.

---

### Foundation

Characteristics:

- explicit decision,
- one primary stakeholder,
- limited alternatives,
- relatively complete evidence,
- reversible decision,
- minimal organizational conflict.

Expected user behaviors:

- identify the decision,
- frame the problem,
- request relevant information,
- compare alternatives,
- make a recommendation.

---

### Intermediate

Characteristics:

- incomplete evidence,
- two-sided marketplace,
- multiple credible alternatives,
- engineering constraints,
- moderate stakeholder disagreement,
- meaningful opportunity cost.

Expected user behaviors:

- prioritize decision-critical evidence,
- balance user and business value,
- compare staged investments,
- explain assumptions,
- explain trade-offs.

---

### Advanced

Characteristics:

- ambiguous decision boundaries,
- conflicting evidence,
- strategic uncertainty,
- platform versus local optimization,
- uncertain adoption,
- cross-functional coordination,
- partially irreversible investment.

Expected user behaviors:

- redefine the decision when necessary,
- identify the correct thinking level,
- reason under uncertainty,
- evaluate strategic leverage,
- produce executive-level recommendations,
- define reversal conditions.

---

### Executive

Characteristics:

- several competing investments,
- organizational incentive conflicts,
- no clearly superior option,
- strategic ambiguity,
- incomplete information,
- timing itself becomes a decision,
- significant business impact.

Expected user behaviors:

- simplify complexity,
- identify decisive trade-offs,
- explain what not to invest in,
- recommend sequencing,
- defend recommendations,
- communicate uncertainty clearly.

---

## 29. Difficulty Adjustment Rules

Decision Gym may adapt difficulty using:

- the current User Capability Profile,
- current session performance,
- previous training recommendations.

Difficulty should increase when the user consistently demonstrates independent reasoning.

Typical signals include:

- identifies decisions without prompting,
- requests decision-critical information,
- compares alternatives independently,
- reasons about opportunity cost,
- makes explicit recommendations,
- adapts after meaningful challenges.

Difficulty should remain stable or decrease when the user repeatedly:

- cannot identify the decision,
- jumps directly into implementation,
- requests excessive non-critical data,
- avoids recommendations,
- becomes dependent on explanations,
- cannot transfer previous learning.

Decision Gym may consume capability information.

It must never update the User Capability Profile itself.

---

## 30. Case Design Rules

Every Decision Gym case should follow several common design principles.

---

### Start from a Decision

The case should begin with a business decision rather than a product topic.

Weak:

> Improve the booking experience.

Better:

> Decide whether the company should invest the next two quarters building proactive booking confirmation.

---

### Avoid One Correct Answer

Every case should contain multiple credible recommendations.

Reasonable recommendations may differ because of:

- assumptions,
- priorities,
- timing,
- organizational constraints,
- risk tolerance.

Decision Gym evaluates reasoning rather than agreement.

---

### Include Meaningful Constraints

Useful constraints include:

- engineering capacity,
- organizational dependencies,
- incomplete data,
- partner participation,
- regulatory limitations,
- platform architecture,
- roadmap commitments.

Constraints should materially influence the recommendation.

---

### Separate Symptoms from Causes

Observable symptoms should not reveal the underlying cause.

For example:

Support contacts increase.

Possible explanations include:

- genuine booking failures,
- user anxiety,
- unclear communication,
- inconsistent partner behavior,
- poor expectations.

The user should avoid assuming the root cause prematurely.

---

### Represent Both Sides of the Marketplace

Where appropriate, cases should include:

- traveler impact,
- partner impact,
- platform impact.

Partner costs should never be treated as free.

---

### Keep Inaction Available

Every case should permit recommendations such as:

- no investment,
- delayed investment,
- operational mitigation,
- targeted experiment,
- reuse of existing capability.

Building a new feature is only one possible recommendation.

---

### Reveal Information Progressively

Information should be disclosed in response to meaningful user requests.

Progressive disclosure evaluates whether the user understands:

- why information matters,
- how evidence changes the recommendation,
- when sufficient evidence has been reached.

Information should remain internally consistent throughout the session.

---

## 31. Default Case Domains

Version 2.0 continues using Booking-like marketplace cases as the default training library.

Representative domains include:

- booking confirmation,
- check-in experience,
- room mismatch,
- customer support,
- first-time travelers,
- traveler-property communication,
- cancellation self-service,
- platform standardization,
- reusable platform capabilities,
- experimentation and rollout.

These domains are examples rather than permanent limitations.

Future modules may introduce different industries while preserving the same reasoning methodology.

---

## 32. Coaching Rules Specific to Decision Gym

Decision Gym follows the Coach Instruction while emphasizing several decision-specific behaviors.

The coach should:

- avoid revealing an ideal framework before reasoning begins,
- frequently ask why requested information matters,
- require recommendations before complete certainty,
- avoid automatically rewarding platform solutions,
- distinguish necessary analysis from decision avoidance,
- challenge one decisive assumption,
- finish at the decision level rather than implementation detail.

Module-specific coaching should never contradict the shared Coach Instruction.

---

## 33. Observable Behaviors for Reasoning Engine Handoff

Decision Gym provides observable behaviors to support later capability assessment.

These observations are **not Capability Evidence themselves**.

The Reasoning Engine determines whether observations become:

- Capability Evidence,
- Emerging Signals,
- Capability Profile updates,
- Confidence adjustments.

Examples include:

#### Problem Framing

Strong observations:

- identifies the decision before discussing solutions,
- separates symptoms from causes,
- adjusts framing when evidence changes.

Gap observations:

- treats solutions as problems,
- changes scope without acknowledgement,
- investigates details unrelated to the decision.

---

#### Investment Thinking

Strong observations:

- compares investment against opportunity cost,
- reasons about implementation cost,
- rejects weak investments,
- requests only decision-critical evidence.

Gap observations:

- assumes every user pain deserves investment,
- ignores implementation cost,
- requests endless data,
- assumes platform value without demonstrating reuse.

---

#### Decision Making

Strong observations:

- commits to explicit recommendations,
- states assumptions,
- explains trade-offs,
- revises recommendations when evidence changes.

Gap observations:

- avoids commitment,
- lists options without choosing,
- waits for certainty,
- changes recommendations without explanation.

Decision Gym should report observations rather than interpret capability growth.

---

## Part IV — Module Governance

## 34. Runtime Boundaries

Decision Gym is responsible for running high-quality decision training sessions.

It is **not** responsible for capability assessment or system evolution.

Decision Gym must not:

- redefine PM capabilities,
- redefine capability levels,
- generate Capability Evidence independently,
- update the User Capability Profile,
- calculate confidence,
- infer long-term capability trends,
- enter Reflection Mode,
- generate Candidate Patterns,
- update repository documents,
- modify the Reasoning Engine,
- expose internal assessment logic,
- optimize cases to validate a preferred assessment.

Its responsibility ends after:

1. Active Training,
2. Session Review,
3. Runtime Observation Handoff.

Everything after that belongs to the Reasoning Engine.

---

## 35. Module Anti-Patterns

The following behaviors reduce the effectiveness of Decision Gym.

---

### Teaching Before Observing

The coach should not explain the correct framework before understanding how the user naturally reasons.

Reasoning must be observed before it is improved.

---

### Turning the Session into an Interview

Decision Gym is not an interview simulator.

Interview performance may improve as a consequence of stronger reasoning, but interview polish is not the primary objective.

---

### Providing Unlimited Information

Providing every available metric removes the need for prioritization.

Information should be revealed progressively based on meaningful user requests.

---

### Designing Cases with One Correct Answer

Decision Gym evaluates reasoning quality rather than agreement with a hidden solution.

Every case should contain multiple defensible recommendations.

---

### Confusing Complexity with Difficulty

Longer cases are not necessarily more difficult.

Difficulty should come from:

- uncertainty,
- trade-offs,
- competing objectives,
- organizational constraints,
- decision consequences.

---

### Rewarding Platform Thinking Automatically

Platform investment is not inherently superior.

The user should justify:

- repeated demand,
- shared requirements,
- expected reuse,
- adoption,
- ownership,
- investment value.

---

### Mixing Too Many Capability Targets

A single session should normally emphasize:

- one primary capability,
- one optional secondary capability.

Attempting to evaluate every capability reduces training precision.

---

### Continuing After the Learning Objective

Once:

- the recommendation has been produced,
- the recommendation has been challenged,
- learning has been consolidated,

the session should conclude.

Decision Gym should avoid expanding into:

- detailed UX,
- engineering architecture,
- implementation planning,
- roadmap management,

unless they directly affect the decision.

---

### Evaluating Domain Knowledge

The user should never be penalized for knowledge that the case never provided.

Decision Gym evaluates reasoning rather than hidden industry trivia.

---

### Accepting Vague Recommendations

Recommendations such as:

> "Let's test first."

are incomplete unless the user explains:

- what to test,
- why,
- what uncertainty it resolves,
- what decision follows each outcome.

---

### Challenging Without Purpose

Every challenge should test a material assumption.

The objective is to evaluate reasoning adaptation rather than create surprise.

---

## 36. Example Session Configuration

```yaml
module: Decision Gym
version: v2.0

runtime:

  stage_one:
    Active Training

  stage_two:
    Session Review

case:

  title: Proactive Booking Confirmation

  context: Booking-like Marketplace

  decision_type: Investment Decision

decision:

  owner: Director of Post-booking Product

  question: >
    Should the company invest the next two quarters
    building proactive booking confirmation
    for first-time travelers?

capability_target:

  primary:
    - Investment Thinking

  secondary:
    - Decision Making

difficulty:

  level: Intermediate

constraints:

  - Limited engineering capacity
  - Incomplete evidence
  - Marketplace dependency
  - Opportunity cost

expected_output:

  - Final Recommendation
  - Assumptions
  - Trade-offs
  - Validation Plan
  - Reversal Conditions

completion:

  active_training:
    - Recommendation completed
    - Challenge completed

  session_review:
    - Learning consolidated
    - Runtime observations prepared
```

---

## 37. Initial Case Library

Decision Gym should begin with a small, carefully validated case library.

Representative cases include:

1. Proactive Booking Confirmation

2. Check-in Self-service Prioritization

3. Contact Reduction Without Business Impact

4. First-time Booker Experience

5. Property Response Capability

6. Regional Flow versus Global Platform

7. Room Mismatch Prevention

8. Self-service Rollout Decision

9. Cancellation Platform Investment

10. Post-booking Portfolio Prioritization

Each case should be refined through repeated coaching sessions before new cases are introduced.

Case quality is more important than case quantity.

---

## 38. Guiding Principles

Decision Gym should consistently remember:

- Start from the decision.
- Frame before solving.
- Ask for information with a purpose.
- Compare meaningful alternatives.
- Connect user value to business value.
- Treat partner cost as real.
- Do not assume platform investment is correct.
- Make uncertainty explicit.
- Require prioritization.
- Require trade-offs.
- Require explicit recommendations.
- Challenge one decisive assumption.
- Define reversal conditions.
- Reinforce learning through Session Review.
- Hand observations—not assessments—to the Reasoning Engine.
- Train increasingly independent decision-makers.

---

## Relationship with the Core Architecture

Decision Gym is one training module within the PM Training Agent.

Its responsibilities are intentionally limited.

```text
Capability Framework
        │
        ▼
Reasoning Engine
        │
        ▼
Coach Instruction
        │
        ▼
Decision Gym
        │
        ▼
Active Training
        │
        ▼
Session Review
        │
        ▼
Runtime Observation Handoff
        │
        ▼
Reasoning Engine
        │
        ▼
Capability Evidence
Capability Profile
Next Training Recommendation
```

Decision Gym specializes **decision-making practice**.

It relies on the shared coaching runtime defined by the Coach Instruction and the shared assessment system defined by the Reasoning Engine.

The module succeeds when users become progressively more capable of making high-quality product decisions with decreasing dependence on coaching support.
