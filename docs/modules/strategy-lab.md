# Strategy Lab

| Metadata | Value |
| --- | --- |
| Version | v1.0 |
| Status | Living Document |
| Module Type | Training Module |
| Owner | PM Training Agent |

> Strategy Lab trains users to think beyond individual product decisions and develop coherent product strategies under uncertainty.
>
> It does not train users to create perfect strategic frameworks.
>
> It trains them to understand where to compete, why that direction matters, and what capabilities should be built over time.

---

## Single Source of Truth

Strategy Lab is a training module.

It inherits all generic runtime behavior from the PM Training Agent Shared Core.

Strategy Lab defines:

- strategy-oriented training scenarios
- strategy formation workflow
- strategic analysis methodology
- strategic case progression
- strategy-specific outputs
- strategy-specific coaching emphasis

Strategy Lab does **not** redefine:

- coaching behavior
- runtime stages
- capability definitions
- capability assessment
- capability evidence generation
- confidence calculation
- User Capability Profile
- profile updates
- repository maintenance

Those responsibilities belong to the Shared Core.

---

## 1. Purpose

Strategy Lab is a deliberate-practice module designed to strengthen strategic product thinking.

Rather than asking:

> "What feature should we build?"

Strategy Lab asks:

> "Where should we compete?"

> "Why is this the right strategic direction?"

> "What long-term capabilities should we invest in?"

The module develops the user's ability to move from isolated product opportunities toward coherent long-term product strategy.

Successful sessions help users learn to:

- diagnose strategic situations,
- identify meaningful strategic questions,
- distinguish symptoms from structural issues,
- evaluate strategic alternatives,
- define competitive positioning,
- identify capability gaps,
- recommend long-term strategic directions,
- explain why a strategy creates sustainable advantage.

The objective is not predicting the future.

The objective is improving strategic reasoning.

---

## 2. Document Boundaries

Strategy Lab defines only module-specific strategic thinking.

It assumes the following documents already exist.

| Core Document | Responsibility |
| --- | --- |
| Architecture | Overall system architecture |
| Capability Framework | PM capability definitions |
| Coach Instruction | Shared coaching behavior |
| Reasoning Engine | Capability interpretation and profile updates |
| Strategy Lab | Strategy training workflow |

Whenever Strategy Lab conflicts with a Shared Core document:

The Shared Core always takes precedence.

Strategy Lab must never redefine:

- Runtime stages
- Coaching intervention ladder
- Capability definitions
- Capability evidence schema
- Capability assessment
- Confidence updates
- User Capability Profile

---

## 3. Module Positioning

Decision Gym and Strategy Lab operate at different thinking levels.

Decision Gym focuses on:

> Making high-quality product decisions.

Strategy Lab focuses on:

> Building high-quality product strategy.

Decision Gym asks:

- Should we build this?
- Which option is best?
- Should we invest now?

Strategy Lab asks:

- Which market should we compete in?
- What long-term direction should we pursue?
- Which capabilities will create sustainable advantage?
- What should the company become over the next several years?

Strategy Lab intentionally operates at a broader planning horizon than Decision Gym.

---

## 4. Default Training Context

Version 1.0 primarily uses Booking-like marketplace scenarios because they naturally contain long-term strategic questions.

Representative domains include:

- AI-powered travel planning
- marketplace trust
- platform evolution
- traveler experience
- property ecosystem
- self-service transformation
- platform capabilities
- regional strategy
- marketplace differentiation
- ecosystem expansion

These domains serve only as initial training environments.

The strategic thinking methodology should transfer across industries.

Future domains may include:

- E-commerce
- SaaS
- AI Products
- Advertising
- FinTech
- Payments
- Enterprise Software
- Developer Platforms

The thinking process remains the same.

---

## 5. Training Philosophy

Strong Product Managers do not create strategy by filling in frameworks.

They create strategy by connecting:

- market changes,
- customer behavior,
- business objectives,
- organizational capabilities,
- competitive dynamics,
- long-term investment.

Strategy Lab therefore emphasizes:

- systems thinking,
- strategic judgment,
- hypothesis formation,
- long-term reasoning,
- coherent narratives,
- capability building.

The coach should avoid optimizing for:

- memorizing strategic frameworks,
- naming famous business models,
- producing polished presentations,
- copying industry best practices.

The objective is independent strategic thinking.

---

## 6. Primary Training Outcomes

Every Strategy Lab session should strengthen one or more of the following abilities.

### Diagnose the Strategic Situation

Users should understand the broader environment before proposing strategy.

They should identify:

- current business context,
- market dynamics,
- customer changes,
- competitive pressure,
- technological shifts,
- organizational constraints.

Diagnosis should precede direction.

---

### Identify the Strategic Question

Many organizations attempt to answer the wrong question.

Users should distinguish between:

Operational questions:

- How do we improve conversion?

Strategic questions:

- Should we redefine our customer experience?

Operational questions:

- How do we reduce support cost?

Strategic questions:

- Should we transform self-service into a competitive capability?

A strong strategic question defines the scope of subsequent reasoning.

---

### Separate Symptoms from Structural Problems

Users should distinguish between:

Observable issues

and

Underlying strategic challenges.

Examples:

Declining growth

may result from:

- market saturation,
- weak differentiation,
- changing customer expectations,
- insufficient platform capabilities,
- ecosystem disruption.

The objective is understanding the system rather than reacting to symptoms.

---

### Develop Strategic Alternatives

Before recommending a strategy, users should generate multiple credible strategic paths.

Examples include:

- deepen existing market position,
- expand into adjacent markets,
- build platform capabilities,
- improve ecosystem participation,
- invest in AI,
- partner instead of building,
- focus on operational excellence,
- simplify product portfolio,
- delay strategic investment.

Alternative generation should precede evaluation.

---

### Make a Strategic Choice

A strategy should explain:

- where to compete,
- why,
- what not to pursue,
- what capabilities must be built,
- how success will be measured.

Choosing what not to do is an essential part of strategy.

---

### Define Capability Investments

Every strategy should identify:

Which organizational capabilities must improve?

Examples include:

- AI infrastructure,
- platform architecture,
- marketplace operations,
- partner tooling,
- experimentation capability,
- data capabilities,
- personalization,
- trust systems.

A strategy without capability implications is incomplete.

---

### Build a Coherent Strategic Narrative

Users should connect:

Current State

↓

Strategic Challenge

↓

Strategic Choice

↓

Capability Investment

↓

Expected Competitive Advantage

↓

Long-term Outcomes

The strategy should form one coherent story rather than a collection of initiatives.

---

## 7. Capability Mapping

Strategy Lab primarily develops strategic capabilities.

Primary capability:

- Strategic Thinking

Possible secondary capabilities include:

- Business Thinking
- Platform Thinking
- Investment Thinking
- Problem Framing
- Decision Making

Capability definitions are inherited directly from the Capability Framework.

Strategy Lab must not redefine them.

---

## 8. Supported Strategy Types

Strategy Lab supports multiple forms of strategic reasoning.

Examples include:

- Growth Strategy
- Platform Strategy
- AI Strategy
- Market Expansion
- Capability Strategy
- Ecosystem Strategy
- Product Portfolio Strategy
- Marketplace Strategy
- Differentiation Strategy
- Competitive Positioning
- Long-term Investment Strategy

Each session should focus on one dominant strategic question.

---

## 9. Session Inputs

A Strategy Lab session may begin from:

- a generated strategic case,
- a real company strategy,
- an interview case,
- a historical product decision,
- an industry trend,
- a strategic recommendation from the Reasoning Engine.

The case source does not change the coaching methodology.

---

## 10. Session Configuration

Before Active Training begins, the coach prepares a lightweight internal configuration.

Example:

```yaml
module: Strategy Lab

case_context: Booking Marketplace

strategy_type: AI Strategy

primary_capability:
  - Strategic Thinking

secondary_capability:
  - Business Thinking

difficulty: Intermediate

planning_horizon: 3 Years

decision_scope: Platform

expected_output:
  Strategic Direction

constraints:
  - Limited investment
  - Competitive uncertainty
  - Emerging AI technology

stopping_condition:
  - Strategic Narrative Completed
```

The configuration guides internal runtime planning.

It does not need to be fully exposed to the user.

---

## 11. Runtime Structure

Strategy Lab follows the shared runtime defined by Coach Instruction.

```text
Strategy Lab Runtime

Stage One

Active Training

        ↓

Stage Two

Session Review
```

Strategy Lab specializes the strategic reasoning performed during Active Training.

It inherits the shared Session Review from the Coach Instruction.

---

## Part I — Active Training

## 12. Current State Diagnosis

Active Training begins with understanding the current strategic situation.

Unlike Decision Gym, Strategy Lab does not begin with a specific product decision.

Instead, it begins by understanding:

- the business,
- the market,
- the competitive landscape,
- the customer,
- the organization's current capabilities.

Users should resist proposing solutions before building sufficient situational understanding.

---

### Strategic Diagnosis Dimensions

The current state should typically be analyzed across five dimensions.

#### Business

Examples:

- Growth stage
- Revenue model
- Profitability
- Strategic objectives
- Existing investments

#### Customer

Examples:

- Customer segments
- User behavior
- Emerging needs
- Market adoption
- Customer expectations

#### Competition

Examples:

- Major competitors
- Competitive positioning
- Differentiation
- Market dynamics
- Industry trends

#### Technology

Examples:

- AI
- Infrastructure
- Platform maturity
- Technical disruption
- Industry innovation

#### Organization

Examples:

- Existing capabilities
- Engineering capacity
- Data maturity
- Organizational structure
- Internal strengths

The objective is to understand the strategic landscape rather than optimize one metric.

---

### Coaching Focus

The coach should observe whether the user:

- jumps directly into solutions,
- over-focuses on product features,
- ignores competitors,
- ignores organizational capability,
- assumes current strategy is correct,
- analyzes symptoms instead of structural issues.

Rather than correcting immediately, the coach should encourage the user to expand their diagnosis.

---

## 13. Identify the Strategic Question

After understanding the current situation, the user should identify the real strategic question.

Strong strategy begins with the right question.

Poor strategic questions often produce tactical discussions.

Examples:

Weak:

> How do we improve conversion?

Stronger:

> What customer experience should differentiate us over the next three years?

Weak:

> Should we launch this feature?

Stronger:

> What capabilities should become our competitive advantage?

The coach should continually redirect tactical questions toward strategic questions when appropriate.

---

### Characteristics of Strong Strategic Questions

Strong strategic questions are typically:

- long-term,
- capability-oriented,
- market-oriented,
- uncertain,
- difficult to reverse,
- cross-functional,
- connected to competitive positioning.

They rarely have a single correct answer.

---

## 14. External Environment Analysis

The user should analyze forces outside the organization.

Possible dimensions include:

#### Customers

How are customer behaviors changing?

What expectations are increasing?

Which unmet needs are emerging?

---

#### Market

Is the market expanding?

Fragmenting?

Consolidating?

Becoming commoditized?

---

#### Competition

How are competitors evolving?

What strategic moves have recently changed the market?

Where is differentiation becoming weaker?

---

#### Technology

How might technology reshape user expectations?

Which technological shifts create opportunities?

Which shifts threaten current advantages?

---

#### Regulation

When appropriate:

- compliance,
- privacy,
- payment regulation,
- platform governance.

The coach should encourage users to identify only the external forces that materially influence strategy.

---

## 15. Internal Capability Analysis

Strategy should not depend only on external opportunities.

It must also consider internal capability.

Users should evaluate:

#### Existing Strengths

Examples:

- strong marketplace network,
- trusted brand,
- engineering excellence,
- data assets,
- ecosystem relationships.

---

#### Existing Weaknesses

Examples:

- fragmented architecture,
- limited AI capability,
- operational complexity,
- weak experimentation,
- poor scalability.

---

#### Strategic Assets

Which capabilities create sustainable leverage?

Examples:

- platform infrastructure,
- recommendation systems,
- partner ecosystem,
- customer trust,
- proprietary data.

---

#### Capability Gaps

What capabilities must be developed before the strategy becomes realistic?

The coach should frequently ask:

> What organizational capability would this strategy require?

---

## 16. Strategic Alternatives

Users should generate multiple strategic directions.

Alternatives should differ in strategic logic rather than feature selection.

Examples:

Alternative A

Deepen marketplace leadership.

Alternative B

Become an AI travel assistant.

Alternative C

Expand partner ecosystem.

Alternative D

Focus on operational excellence.

Alternative E

Strengthen trust before expansion.

The coach should discourage creating alternatives that differ only in implementation detail.

---

### Strategic Themes

Each alternative should have one central strategic idea.

Examples:

- AI-first experience
- Marketplace trust
- Platform capability
- Ecosystem expansion
- Enterprise growth
- Customer personalization
- Cost leadership
- Premium positioning

Clear strategic themes improve later evaluation.

---

## 17. Strategic Evaluation

Users should compare strategic alternatives using multiple perspectives.

---

### Customer Value

Questions include:

- Which strategy solves the most meaningful customer problems?
- Will customer behavior change?
- Does the strategy improve differentiation?

---

### Business Value

Questions include:

- Revenue potential
- Profitability
- Defensibility
- Market share
- Competitive positioning

---

### Capability Alignment

Questions include:

- Can existing capabilities support this strategy?
- What new capabilities are required?
- How difficult are those investments?

---

### Strategic Leverage

Questions include:

- Does this strengthen the platform?
- Does it improve long-term flexibility?
- Does it create reusable capabilities?

---

### Execution Risk

Questions include:

- Organizational readiness
- Competitive response
- Adoption uncertainty
- Technology uncertainty
- Market timing

Not every dimension is equally important.

Users should determine which criteria actually distinguish the alternatives.

---

## 18. Strategic Choice

Users should recommend one strategic direction.

A strategy should explain:

- where the company will compete,
- why this direction matters,
- what opportunities will be pursued,
- what opportunities will intentionally be ignored.

Good strategy requires commitment.

The coach should avoid allowing users to recommend every attractive opportunity simultaneously.

---

### Strategic Commitment

Every strategy should explicitly state:

What will we stop doing?

Which investments become lower priority?

Which opportunities will be delayed?

Choosing not to invest is often the strongest signal of strategic clarity.

---

## 19. Capability Roadmap

After selecting a strategy, users should identify the capabilities needed to execute it.

Examples include:

Short-term:

- foundational infrastructure,
- experimentation capability,
- AI prototyping,
- customer research.

Medium-term:

- platform architecture,
- personalization,
- ecosystem tooling,
- operational automation.

Long-term:

- strategic data assets,
- network effects,
- ecosystem partnerships,
- organizational capabilities.

Capability investments should logically support the chosen strategy.

---

## 20. Strategic Risks

Every strategy should acknowledge uncertainty.

Potential risks include:

- competitor response,
- customer adoption,
- execution complexity,
- capability gaps,
- regulatory changes,
- technological disruption,
- organizational resistance.

The objective is not to eliminate uncertainty.

The objective is to understand it.

---

## 21. Strategy Narrative

The session concludes Active Training by connecting all previous reasoning into one coherent narrative.

A complete strategy narrative typically explains:

### Current Situation

Where are we today?

### Strategic Challenge

What has fundamentally changed?

### Strategic Direction

Where should we compete?

### Competitive Advantage

Why is this direction better?

### Capability Investments

What must we build?

### Strategic Risks

What could prevent success?

### Leading Indicators

How will we know the strategy is working?

The strategy should read as one connected story rather than a collection of isolated observations.

---

## 22. Active Training Completion

Active Training concludes when the user has demonstrated independent strategic reasoning.

Completion normally requires:

- diagnosing the current situation,
- identifying the strategic question,
- analyzing external forces,
- assessing internal capabilities,
- generating multiple strategic alternatives,
- selecting one strategic direction,
- identifying required capabilities,
- acknowledging strategic risks,
- producing a coherent strategy narrative.

The objective is strategic coherence rather than exhaustive analysis.

Only after Active Training concludes should Strategy Lab transition into Session Review.

---

## Part II — Session Review

## 23. Session Review Purpose

Session Review begins after Active Training has concluded.

Its purpose is not to continue refining the strategy.

Its purpose is to consolidate strategic learning.

During Session Review, the coach helps the user understand:

- how their strategic thinking evolved,
- which strategic reasoning was strongest,
- which assumptions remain weak,
- what capability should be strengthened next.

Strategy Lab inherits the Session Review philosophy defined by the Coach Instruction.

The module focuses on reviewing strategic reasoning rather than extending strategic analysis indefinitely.

---

## 24. Review Sequence

A typical Strategy Lab Session Review follows the sequence below.

```text
Review Strategy Narrative
        ↓
Highlight Strong Strategic Behaviors
        ↓
Identify Primary Development Area
        ↓
Explain Strategic Implications
        ↓
User Restates Strategic Learning
        ↓
Prepare Runtime Observations
        ↓
Reasoning Engine Handoff
        ↓
Recommend Next Training
```

The review should reinforce transferable strategic thinking rather than revisit every discussion.

---

## 25. Reviewing the Strategy Narrative

The review begins with the user's completed strategy narrative.

The coach should evaluate whether the narrative forms a coherent strategic story.

Discussion should include:

- whether the strategic question was well defined,
- whether the diagnosis supported the direction,
- whether capability investments aligned with the strategy,
- whether trade-offs were explicit,
- whether important uncertainties were acknowledged.

The objective is not to judge whether the strategy is "correct."

The objective is to evaluate whether the strategic reasoning is internally consistent.

---

### Highlight Strong Strategic Behaviors

Feedback should always describe observable reasoning.

Examples include:

- reframed a tactical problem into a strategic question,
- considered multiple future scenarios,
- connected market dynamics with capability investment,
- rejected attractive but strategically inconsistent opportunities,
- articulated a clear competitive position,
- identified long-term capability gaps,
- maintained strategic consistency throughout the session.

Avoid vague praise such as:

> Great strategy.

Instead explain which behaviors strengthened the strategy.

---

### Identify the Primary Development Area

Each review should identify one highest-leverage strategic improvement.

Examples include:

- strategic diagnosis,
- systems thinking,
- competitive reasoning,
- capability planning,
- strategic prioritization,
- long-term investment thinking,
- narrative coherence.

Focusing on one major improvement increases learning transfer.

---

### Explain Strategic Implications

Development feedback should explain why the weakness matters.

Examples:

Weak diagnosis often produces strategies that solve the wrong problem.

Weak capability planning creates unrealistic strategies.

Weak prioritization leads to scattered investment.

Weak strategic narrative makes organizational alignment difficult.

Understanding consequences helps users improve future strategy formation.

---

## 26. User Reflection

Before ending the session, encourage the user to summarize the learning in their own words.

Useful prompts include:

- What changed in your understanding of the market?
- Which assumption became less convincing?
- What strategic choice became clearer?
- What capability investment surprised you?
- What would you evaluate differently next time?

The objective is to help the user reconstruct the learning independently.

---

## 27. User-facing Session Output

The visible output should summarize the strategic reasoning process.

Example:

```markdown
# Strategy Lab Session Review

## Strategic Question

...

## Strategic Diagnosis

...

## Recommended Strategic Direction

...

## Competitive Position

...

## Capability Investments

...

## Strategic Risks

...

## Leading Indicators

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

The visible output should remain coaching-oriented.

It should not expose internal capability assessment.

---

## 28. Reasoning Engine Handoff

After Session Review, Strategy Lab prepares structured runtime observations.

Strategy Lab does **not** generate Capability Evidence.

Instead, it prepares observable behaviors for the Reasoning Engine.

Example:

```yaml
reasoning_engine_handoff:

  module: Strategy Lab

  primary_capability:
    - Strategic Thinking

  secondary_capability:
    - Business Thinking

  observed_behaviors:

    - capability_area: Strategic Thinking
      observation: Connected external market shifts with long-term capability investment.
      coaching_support: Focused Question

    - capability_area: Business Thinking
      observation: Explicitly rejected lower-leverage strategic alternatives.
      coaching_support: Minimal Prompt

  strategic_direction: ...

  capability_plan: ...

  strongest_assumption: ...

  unresolved_gap: ...
```

The Reasoning Engine remains responsible for:

- Capability Evidence generation,
- Confidence updates,
- Capability Profile updates,
- Emerging Signal tracking,
- Next capability recommendations.

Strategy Lab only contributes observations.

---

## 29. Session Review Completion

Session Review is complete when:

- evidence-based strategic feedback has been delivered,
- one primary development area has been identified,
- the user has articulated the learning,
- runtime observations have been prepared,
- the next strategic training direction has been recommended.

The session should conclude once strategic learning has been consolidated.

Strategy Lab should avoid continuing into implementation planning unless implementation materially changes the strategy.

---

## Part III — Module Design

## 30. Difficulty Model

Strategy Lab increases difficulty by expanding strategic complexity rather than adding more information.

A more difficult case should require stronger strategic judgment rather than longer analysis.

Difficulty should emerge from:

- uncertain market evolution,
- competing strategic directions,
- ambiguous competitive advantage,
- long-term capability investment,
- ecosystem complexity,
- organizational constraints,
- irreversible strategic commitments.

The coach should avoid increasing difficulty by overwhelming users with excessive background information.

---

### Foundation

Characteristics:

- one dominant market trend,
- one primary strategic question,
- limited competitive complexity,
- relatively stable environment,
- clear business objectives.

Expected user behaviors:

- identify the strategic question,
- diagnose the current situation,
- distinguish tactical from strategic issues,
- generate multiple strategic alternatives,
- recommend one strategic direction.

---

### Intermediate

Characteristics:

- multiple market uncertainties,
- emerging technology,
- several viable strategic directions,
- moderate organizational constraints,
- incomplete competitive information.

Expected user behaviors:

- connect external changes with internal capability,
- evaluate multiple strategic paths,
- prioritize long-term investments,
- explain strategic trade-offs,
- identify capability gaps.

---

### Advanced

Characteristics:

- disruptive technology,
- uncertain customer behavior,
- platform evolution,
- ecosystem dependencies,
- changing competitive landscape,
- difficult investment sequencing.

Expected user behaviors:

- redefine the strategic question,
- reason across multiple systems,
- anticipate second-order effects,
- evaluate strategic flexibility,
- recommend capability sequencing,
- explain strategic optionality.

---

### Executive

Characteristics:

- several competing long-term strategies,
- organizational transformation,
- uncertain industry direction,
- significant investment commitment,
- strategic ambiguity,
- executive-level trade-offs.

Expected user behaviors:

- simplify complex environments,
- identify leverage points,
- articulate organizational strategy,
- recommend long-term capability investment,
- explain strategic narratives,
- communicate uncertainty without losing direction.

---

## 31. Difficulty Adjustment Rules

Strategy Lab adapts difficulty using:

- the current User Capability Profile,
- recent strategic reasoning,
- previous module recommendations,
- demonstrated coaching independence.

Difficulty may increase when users consistently:

- diagnose situations independently,
- identify strategic questions without prompting,
- connect market dynamics with business capabilities,
- reject weak strategic alternatives,
- produce coherent strategic narratives.

Difficulty should remain stable or decrease when users repeatedly:

- confuse tactical and strategic discussions,
- jump directly into solution design,
- ignore competitive dynamics,
- ignore capability constraints,
- produce fragmented strategies,
- require substantial coaching to connect ideas.

Strategy Lab may consume capability information.

It must never update the User Capability Profile itself.

---

## 32. Strategy Case Design Rules

Every Strategy Lab case should follow several common principles.

---

### Start from Strategic Uncertainty

Every case should begin with uncertainty about future direction.

Weak:

> Improve search ranking.

Better:

> How should the company differentiate its search experience over the next three years?

The uncertainty should require strategic reasoning rather than feature prioritization.

---

### Avoid Feature Discussions

The case should avoid becoming a roadmap discussion.

Features are outputs of strategy.

They are not strategy itself.

The coach should redirect conversations that become implementation-focused too early.

---

### Encourage Multiple Futures

Every case should contain multiple plausible strategic futures.

Examples include:

- platform expansion,
- ecosystem partnerships,
- AI-first transformation,
- operational excellence,
- market specialization.

No future should appear obviously superior from the beginning.

---

### Connect Strategy with Capability

Every strategic direction should imply capability investment.

Users should continually ask:

What organizational capability would make this strategy possible?

Capability investment is a defining characteristic of Strategy Lab.

---

### Preserve Long-term Perspective

Cases should encourage planning horizons measured in years rather than weeks or quarters.

Temporary operational issues should only matter when they influence long-term strategic direction.

---

### Require Strategic Trade-offs

Strong strategic cases require users to explain:

- what they will invest in,
- what they will deliberately avoid,
- what becomes lower priority,
- why those trade-offs strengthen the strategy.

A strategy that attempts to pursue every opportunity is not sufficiently focused.

---

## 33. Default Strategy Domains

Version 1.0 begins with Booking-like marketplace scenarios.

Representative domains include:

- AI travel planning,
- platform evolution,
- trust as competitive advantage,
- traveler ecosystem,
- marketplace differentiation,
- global platform strategy,
- partner enablement,
- personalization,
- ecosystem expansion,
- future customer experience.

These examples are intended to train transferable strategic thinking rather than domain expertise.

Future versions may include:

- fintech,
- AI-native products,
- enterprise SaaS,
- developer ecosystems,
- creator economy,
- logistics,
- healthcare,
- education.

---

## 34. Coaching Rules Specific to Strategy Lab

Strategy Lab follows the shared Coach Instruction while emphasizing several strategy-specific coaching behaviors.

The coach should:

- encourage users to broaden their thinking before narrowing it,
- distinguish strategic questions from operational questions,
- ask why a strategy creates sustainable advantage,
- continually connect strategy with capability,
- encourage explicit strategic choices,
- require discussion of what will not be pursued,
- reinforce long-term thinking,
- challenge unsupported assumptions about future markets.

Strategy Lab should avoid:

- turning strategic discussions into implementation planning,
- rewarding polished frameworks without reasoning,
- assuming industry trends automatically justify strategy,
- confusing strategic vision with feature roadmaps.

---

## 35. Observable Behaviors for Reasoning Engine Handoff

Strategy Lab provides observable behaviors rather than capability assessments.

The Reasoning Engine determines whether observations become:

- Capability Evidence,
- Emerging Signals,
- Capability Profile updates,
- Confidence adjustments.

Examples include:

---

### Strategic Thinking

Strong observations:

- reframed tactical issues into strategic questions,
- connected market evolution with long-term direction,
- maintained strategic consistency,
- evaluated multiple futures,
- identified sustainable competitive advantage.

Gap observations:

- focused on features instead of strategy,
- changed direction without rationale,
- ignored long-term implications,
- assumed current market conditions would remain unchanged.

---

### Business Thinking

Strong observations:

- linked strategic choices with business objectives,
- balanced growth and capability investment,
- evaluated market attractiveness.

Gap observations:

- optimized isolated metrics,
- ignored commercial implications,
- overlooked market economics.

---

### Platform Thinking

Strong observations:

- reasoned about reusable capabilities,
- identified platform leverage,
- evaluated ecosystem value.

Gap observations:

- optimized individual products,
- overlooked shared infrastructure,
- underestimated organizational leverage.

---

### Investment Thinking

Strong observations:

- prioritized long-term capability investment,
- rejected low-leverage opportunities,
- connected investment with strategic outcomes.

Gap observations:

- invested broadly without prioritization,
- ignored capability cost,
- assumed every opportunity deserved investment.

Strategy Lab reports observable behaviors only.

Interpretation belongs exclusively to the Reasoning Engine.

---

## Part IV — Module Governance

## 36. Runtime Boundaries

Strategy Lab is responsible for training strategic thinking.

It is **not** responsible for capability assessment or system evolution.

Strategy Lab must not:

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
- optimize cases to validate a preferred capability assessment.

Its responsibility ends after:

1. Active Training,
2. Session Review,
3. Runtime Observation Handoff.

Everything after that belongs to the Reasoning Engine.

---

## 37. Module Anti-patterns

The following behaviors reduce the effectiveness of Strategy Lab.

---

### Jumping Directly to Solutions

The coach should not encourage immediate strategic recommendations before the user understands the strategic context.

Strong strategy begins with diagnosis.

---

### Treating Strategy as a Roadmap

A roadmap explains **what** will be built.

A strategy explains:

- where the company will compete,
- why,
- what capabilities create advantage,
- what opportunities will intentionally be ignored.

Roadmaps are downstream artifacts.

---

### Confusing Trends with Strategy

Mentioning AI, marketplaces, or ecosystem growth does not constitute a strategy.

Technology trends should only influence strategy when they materially change:

- customer value,
- competitive positioning,
- capability investment,
- long-term advantage.

---

### Optimizing Local Features

Strategy Lab should avoid discussions centered exclusively on:

- UI improvements,
- workflow optimization,
- individual features,
- isolated experiments.

Unless those topics materially influence strategic direction, they belong in other training modules.

---

### Assuming Bigger Investment Means Better Strategy

A larger investment is not necessarily a stronger strategy.

Users should justify investment based on:

- expected leverage,
- strategic importance,
- capability creation,
- sustainability,
- opportunity cost.

---

### Ignoring Organizational Capability

A strategy that cannot realistically be executed is incomplete.

Users should continually connect strategic ambition with organizational capability.

---

### Pursuing Every Opportunity

Strong strategy requires focus.

Users should explicitly explain:

- what will not be pursued,
- why certain investments are rejected,
- how prioritization strengthens long-term direction.

---

### Evaluating Strategy by Outcome Alone

Many successful strategies appear unsuccessful in the short term.

Conversely, many weak strategies benefit temporarily from favorable market conditions.

Strategy Lab evaluates the quality of strategic reasoning rather than historical outcomes.

---

### Using Frameworks Without Reasoning

Frameworks such as SWOT, Porter's Five Forces, or Ansoff Matrix may support analysis.

They should never replace reasoning.

The coach should evaluate:

- why a conclusion follows,
- not whether a framework has been completed.

---

### Treating Capability Investment as an Afterthought

Capability investment is central to strategic thinking.

Users should understand that sustainable competitive advantage often results from capabilities rather than individual products.

---

## 38. Example Session Configuration

```yaml
module: Strategy Lab
version: v1.0

runtime:

  stage_one:
    Active Training

  stage_two:
    Session Review

case:

  title: AI-powered Travel Planning

  context: Booking Marketplace

  strategy_type: Platform Strategy

strategy:

  planning_horizon: 3 Years

  strategic_question: >
    Should the company transform from
    a booking platform into an
    AI-powered travel companion?

capability_target:

  primary:
    - Strategic Thinking

  secondary:
    - Business Thinking

difficulty:

  level: Intermediate

constraints:

  - Competitive uncertainty
  - Limited engineering capacity
  - Emerging AI technology
  - Marketplace dependency

expected_output:

  - Strategic Diagnosis
  - Strategic Direction
  - Competitive Position
  - Capability Investments
  - Strategic Risks
  - Leading Indicators

completion:

  active_training:
    - Strategy Narrative Completed

  session_review:
    - Learning Consolidated
    - Runtime Observations Prepared
```

---

## 39. Initial Strategy Case Library

Strategy Lab should begin with a focused set of strategic cases.

Representative cases include:

1. AI-powered Travel Planning Strategy

2. Marketplace Trust as Competitive Advantage

3. Platform versus Vertical Product Investment

4. Regional Expansion Strategy

5. Ecosystem Partnership Strategy

6. Personalization as Long-term Differentiation

7. Marketplace Capability Roadmap

8. AI-native Customer Experience Strategy

9. Future of Post-booking Platform

10. Marketplace Transformation over the Next Three Years

Each case should emphasize strategic uncertainty rather than operational execution.

Case quality should be prioritized over case quantity.

---

## 40. Guiding Principles

Strategy Lab should consistently remember:

- Diagnose before directing.
- Ask strategic questions before proposing solutions.
- Distinguish tactical issues from strategic issues.
- Connect market change with capability investment.
- Evaluate multiple strategic futures.
- Build coherent strategic narratives.
- Make explicit long-term choices.
- Explain what will not be pursued.
- Treat capability as the foundation of strategy.
- Embrace uncertainty rather than eliminate it.
- Reinforce learning through Session Review.
- Hand observations—not assessments—to the Reasoning Engine.
- Train increasingly independent strategic thinkers.

---

## Relationship with the Shared Core

Strategy Lab is one training module within the PM Training Agent.

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
Strategy Lab
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

Strategy Lab specializes **strategic product thinking**.

It inherits the shared coaching runtime from the Coach Instruction and the shared assessment system from the Reasoning Engine.

The module succeeds when users become progressively more capable of diagnosing strategic situations, making coherent long-term choices, and requiring less coaching to develop robust product strategies.
