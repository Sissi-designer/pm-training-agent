# Decision Gym

| Metadata | Value |
| --- | --- |
| Version | v1.0 |
| Status | Active |
| Module Type | Training Module |
| Owner | PM Training Agent |

> Decision Gym trains the user to make clear, defensible product decisions under uncertainty.
>
> The goal is not to discover the perfect answer.
>
> The goal is to develop a repeatable decision-making process.

---

## 1. Purpose

Decision Gym is a deliberate-practice module within the PM Training Agent.

It trains the user to make product decisions when:

- information is incomplete
- multiple options appear reasonable
- business and user goals may conflict
- resources are limited
- stakeholders have different priorities
- the cost of waiting is uncertain
- the decision must still be made

The module focuses on the reasoning required to move from ambiguity to an explicit recommendation.

Decision Gym is not primarily designed to test:

- domain knowledge
- feature ideation
- detailed solution design
- interview memorization
- framework recall
- presentation fluency

It is designed to train the user's ability to decide.

---

## 2. Module Positioning

Decision Gym is an execution module built on top of the PM Training Agent's three core documents.

| Core Document | Role in Decision Gym |
| --- | --- |
| Capability Framework | Defines which PM capabilities are being developed |
| Reasoning Engine | Defines how the coach interprets the user's reasoning and capability evidence |
| Coach Instruction | Defines how the coach conducts the training session |
| Decision Gym | Defines the decision scenarios, module workflow, difficulty, and outputs |

Decision Gym must not create a separate capability model or coaching philosophy.

When module-specific rules conflict with a core document, the core document takes precedence.

---

## 3. Training Context

The initial version of Decision Gym focuses primarily on Booking-like travel marketplace scenarios.

Typical product areas include:

- post-booking customer experience
- booking confirmation
- check-in preparation
- reservation issues
- room or amenity mismatch
- changes and cancellations
- customer support contacts
- traveler self-service
- property-facing workflows
- property response efficiency
- first-time traveler anxiety
- cross-market product consistency
- platform standardization
- reusable service capabilities
- marketplace trust
- operational cost reduction
- experiment and rollout decisions

Cases should reflect the characteristics of a two-sided travel marketplace:

- traveler and property interests may not fully align
- the platform may not control the full service experience
- operational processes often depend on external partners
- customer problems may occur after the transaction
- service recovery can require customer support intervention
- market behavior may vary by region
- platform-level solutions may compete with local flexibility
- user trust and business efficiency may create tension

The module should use realistic marketplace constraints without claiming access to confidential Booking.com information.

---

## 4. Primary Training Outcomes

Decision Gym should help the user consistently perform the following actions.

### 4.1 Identify the actual decision

The user should distinguish between:

- a problem
- an analysis question
- a solution idea
- and the decision that must be made

The decision should identify:

- who must decide
- what must be decided
- why the decision is needed now
- what options are available
- what happens if no action is taken

---

### 4.2 Frame the relevant problem

The user should define the problem at the level required for the decision.

A useful problem frame should normally clarify:

- affected user or stakeholder
- observed behavior or failure
- user impact
- business impact
- scope
- urgency
- known evidence
- remaining uncertainty

The user should avoid framing the problem solely as the absence of a proposed feature.

---

### 4.3 Identify decision-critical information

The user should distinguish between:

- information that is interesting
- information that improves understanding
- and information that could change the decision

The user should be able to explain:

- why a requested data point matters
- how different results would affect the recommendation
- whether the decision can proceed without it
- what minimum evidence is sufficient

---

### 4.4 Compare meaningful alternatives

The user should consider more than one credible option.

Alternatives may include:

- build
- experiment
- improve an existing flow
- use operations
- rely on partners
- standardize
- allow local variation
- postpone
- stop investing
- take no action

The user should avoid comparing one preferred solution against obviously weak alternatives.

---

### 4.5 Evaluate investment value

The user should connect the product opportunity to:

- user value
- business value
- strategic value
- implementation cost
- operational cost
- confidence
- opportunity cost
- reversibility
- time to impact

The user should be able to explain why the company should or should not invest.

---

### 4.6 Make an explicit recommendation

The user should conclude with a clear decision.

The recommendation should normally include:

- chosen option
- rationale
- priority
- scope
- timing
- major assumptions
- trade-offs
- next validation step
- conditions that would reverse the decision

---

### 4.7 Defend the recommendation

The user should be able to respond when the recommendation is challenged by:

- missing data
- stakeholder objections
- execution risk
- regional differences
- platform constraints
- alternative investments
- weak adoption
- unexpected negative impact

The objective is not to defend the original recommendation at all costs.

The user should know when to maintain, modify, or reverse the decision.

---

## 5. Capability Mapping

Decision Gym does not train all capabilities equally in every session.

Each case should define one or two primary capability targets.

### 5.1 Primary capabilities

#### Problem Framing

The ability to identify the actual problem, decision owner, scope, and objective before discussing solutions.

#### Investment Thinking

The ability to determine whether an opportunity deserves investment relative to expected value, cost, uncertainty, and opportunity cost.

#### Decision Making

The ability to convert analysis into an explicit recommendation under uncertainty.

---

### 5.2 Secondary capabilities

#### Business Thinking

The ability to connect user problems and product actions to business outcomes.

#### Strategic Thinking

The ability to evaluate alternatives in the context of longer-term direction, positioning, and future consequences.

---

### 5.3 Context-dependent capabilities

#### Platform Thinking

This becomes relevant when the case involves:

- shared capabilities
- standardization
- reusable services
- cross-business workflows
- local versus global architecture
- platform adoption
- platform governance

#### Influence Thinking

This becomes relevant when the user must:

- present the recommendation to leadership
- align customer support and product teams
- influence property-facing teams
- negotiate with regional teams
- respond to stakeholder objections

A case should not force Platform Thinking or Influence Thinking when they are not naturally relevant.

---

## 6. Supported Decision Types

Decision Gym should draw from a stable set of product decision types.

### 6.1 Investment decision

Examples:

- Should the company invest in a new self-service capability?
- Is the customer problem large enough to justify platform investment?
- Should a temporary operational solution become a product capability?

---

### 6.2 Prioritization decision

Examples:

- Which post-booking issue should be addressed first?
- Should the team prioritize booking confirmation, property contact, or change requests?
- Which market should receive the next product rollout?

---

### 6.3 Continue, modify, pause, or stop

Examples:

- An experiment improves self-service usage but does not reduce support contacts. What should the team do?
- A feature shows high adoption but no measurable business impact.
- A platform migration is behind schedule and regional teams are resisting adoption.

---

### 6.4 Build, buy, partner, or operate

Examples:

- Should the platform build a messaging capability or use an existing provider?
- Should the problem be solved through product automation or customer support operations?
- Should the platform rely on property partners to confirm reservations earlier?

---

### 6.5 Standardization versus customization

Examples:

- Should the same self-service experience be used across all markets?
- Should regional teams be allowed to customize issue flows?
- Should different property types follow one standard confirmation process?

---

### 6.6 Experiment versus full rollout

Examples:

- Is there enough evidence to launch broadly?
- Should the team test in one market or several?
- Which risks require validation before scaling?

---

### 6.7 Short-term impact versus long-term capability

Examples:

- Should the team optimize an existing support flow or build a reusable issue-resolution platform?
- Should the team solve one high-volume issue or create a common capability for multiple issues?

---

### 6.8 Local optimization versus platform consistency

Examples:

- A regional solution performs better locally but creates long-term fragmentation.
- A global platform lowers development cost but performs worse in one market.
- A shared component requires regional teams to give up flexibility.

---

### 6.9 Action under insufficient evidence

Examples:

- The problem appears important, but the available data is incomplete.
- Waiting for better evidence may create customer or business risk.
- An irreversible investment must be considered before uncertainty is resolved.

---

### 6.10 Reversal decision

Examples:

- What evidence should cause the team to stop the initiative?
- When should a platform strategy be reconsidered?
- When should the team return to an operational solution?

---

## 7. Session Inputs

A Decision Gym session may be initiated from one of four input types.

### 7.1 Generated case

The agent creates a new Booking-like product decision scenario.

Use this when:

- the user wants deliberate practice
- no real case has been provided
- a specific capability needs targeted training
- controlled difficulty is important

---

### 7.2 Real work situation

The user provides a real product decision.

The agent should help anonymize or abstract sensitive details when necessary.

The agent should not assume that the user's current framing is correct.

---

### 7.3 Interview case

The user provides or requests a product interview scenario.

The module should still train real decision quality rather than optimizing only for interview performance.

---

### 7.4 Historical project review

The user revisits a previous project decision.

The objective is to evaluate:

- what was known at the time
- what decision was made
- which assumptions were correct
- what was missed
- what the user would do differently now

The agent should avoid judging the past decision only from the final outcome.

---

## 8. Session Configuration

Before starting, the agent should establish a lightweight internal session configuration.

```yaml
module: Decision Gym
case_context: Booking-like travel marketplace
case_type: Investment Decision
primary_capability:
  - Investment Thinking
secondary_capability:
  - Decision Making
difficulty: Intermediate
decision_owner: Product Director
expected_output: Investment recommendation
session_constraint:
  - Incomplete impact data
  - Limited engineering capacity
stopping_condition:
  - Explicit recommendation challenged by one major assumption
```

The configuration does not always need to be shown to the user.

The user should receive only the information required to begin reasoning.

---

## 9. Session Workflow

A typical Decision Gym session follows the workflow below.

```text
Case Setup
    ↓
Decision Identification
    ↓
Initial Problem Framing
    ↓
Information Prioritization
    ↓
Alternative Generation
    ↓
Evaluation and Trade-offs
    ↓
Preliminary Recommendation
    ↓
Assumption Challenge
    ↓
Final Recommendation
    ↓
Session Reflection
    ↓
Capability Evidence
    ↓
Next Training Focus
```

The coach may return to an earlier stage when a foundational gap appears.

---

## 10. Stage 1 — Case Setup

The case setup should provide enough context for meaningful reasoning without resolving the decision.

A case should normally include:

- business context
- user or partner context
- observable problem
- available evidence
- relevant constraints
- required decision

The initial setup should not include every possible metric.

The user should determine what additional information matters.

### Example structure

```text
You are the PM responsible for post-booking self-service.

Customer support contacts related to check-in have increased in several Southeast Asian markets.

A large share of contacts come from first-time bookers who want to confirm whether the property has received their reservation.

A proposed solution would automatically request property confirmation several days before check-in and show the status to travelers.

The solution requires integration with property-facing systems and may increase property workload.

You have limited engineering capacity for the next two quarters.

You need to recommend whether the company should invest in this capability now.
```

The case should end with an explicit decision requirement.

---

## 11. Stage 2 — Decision Identification

Before detailed analysis, the coach should verify that the user understands the actual decision.

The user should clarify:

- What is being decided?
- Who is making the decision?
- What is the relevant time horizon?
- What options are currently available?
- What happens if no investment is made?

The coach should redirect the user when they mistake the case for:

- a data analysis task
- a feature design task
- a root-cause investigation only
- a brainstorming exercise

The user may need analysis, but analysis must serve the decision.

---

## 12. Stage 3 — Initial Problem Framing

The user should establish a first problem frame before proposing a solution.

The frame should normally cover:

- target traveler or property segment
- user problem
- behavioral evidence
- business consequence
- scale
- scope
- urgency
- uncertainty

The coach should observe whether the user:

- begins from the solution
- confuses symptoms with causes
- assumes the highest-volume problem is automatically the highest-value problem
- ignores the marketplace side that bears the cost
- treats support contact reduction as the only goal
- separates traveler anxiety from actual service failure

The first frame does not need to be complete.

It should be sufficient to guide the next information request.

---

## 13. Stage 4 — Information Prioritization

The user may ask for additional information.

The coach should not immediately provide every requested data point.

For each material request, the coach may ask:

> Why does this information matter, and how would different results change your decision?

A strong information request should specify:

- the question
- the hypothesis
- the decision impact
- the expected threshold or interpretation

### Example

Weak request:

> I want to know the support contact rate.

Stronger request:

> I want to compare the contact rate of first-time and repeat bookers for confirmation-related issues. If the problem is highly concentrated among first-time users, I may prefer a targeted reassurance solution before investing in a full property-confirmation platform.

The coach should distinguish between:

- decision-critical evidence
- useful supporting evidence
- information that can be learned after an experiment
- information that is unlikely to change the decision

---

## 14. Stage 5 — Alternative Generation

The user should identify credible alternatives before selecting a recommendation.

Depending on the case, alternatives may include:

- do nothing
- improve communication
- add traveler-facing self-service
- automate property outreach
- create operational support
- build a reusable platform capability
- target only high-risk bookings
- run a limited experiment
- partner with another team
- postpone investment

The coach should challenge false alternatives.

For example, comparing:

- a fully developed platform
- with doing absolutely nothing

may hide lower-cost or staged options.

The user should consider whether the decision can be decomposed into phases.

---

## 15. Stage 6 — Evaluation and Trade-offs

The user should compare alternatives using criteria appropriate to the decision.

Possible criteria include:

### User value

- reduction in uncertainty
- reduction in failed check-ins
- faster issue resolution
- increased trust
- improved self-service completion

### Business value

- lower support contact volume
- lower operational cost
- higher retention
- fewer cancellations
- reduced compensation cost
- stronger marketplace trust

### Partner value and cost

- additional property workload
- response requirements
- operational complexity
- partner adoption
- partner satisfaction

### Investment

- engineering cost
- integration complexity
- operational dependency
- maintenance cost
- rollout effort
- organizational coordination

### Strategic leverage

- reuse across issue types
- reuse across markets
- contribution to a shared platform
- future automation potential
- data or learning advantage

### Risk

- false confirmation
- increased traveler expectation
- low property response rate
- regional variation
- poor adoption
- unintended support contacts
- displacement of higher-value work

The coach should not require the user to mechanically cover every criterion.

The user should select the criteria that determine the decision.

---

## 16. Stage 7 — Preliminary Recommendation

The coach should ask for a recommendation before all uncertainty is removed.

A preliminary recommendation should include:

```text
I recommend...

because...

The primary value is...

The strongest evidence is...

The largest uncertainty is...

Compared with the alternatives...

I would initially scope it to...

I would not invest in...

```

The recommendation must be specific enough to challenge.

The coach should not accept responses such as:

- “It depends.”
- “We need more data.”
- “We can try several things.”
- “Both options have advantages.”
- “I would align with stakeholders first.”

These may be valid considerations but are not decisions.

---

## 17. Stage 8 — Assumption Challenge

After the user makes a preliminary recommendation, the coach should introduce at least one meaningful challenge.

The challenge should target the reasoning rather than create random difficulty.

### Possible challenges

#### Low partner response

Only a minority of properties respond to confirmation requests.

#### No contact reduction

The experience increases traveler engagement but does not reduce support contacts.

#### Market variation

The problem is significant in Southeast Asia but limited in Europe.

#### Cannibalization

The new self-service flow moves users away from a more effective existing solution.

#### Increased expectation

Showing a pending confirmation status creates more anxiety than the current experience.

#### Opportunity cost

The same engineering resources could address failed payment recovery or cancellation self-service.

#### Weak reuse

The proposed platform capability is only useful for one issue type.

#### Stakeholder objection

Customer support supports the initiative, but the property team believes it will damage partner experience.

The user should determine whether the challenge:

- changes the recommendation
- changes the scope
- changes the sequence
- changes the validation plan
- or does not materially change the decision

---

## 18. Stage 9 — Final Recommendation

The final recommendation should normally contain the following elements.

### Decision

What should the company do?

### Scope

Which users, markets, issue types, or partners are included?

### Rationale

Why is this option preferable to the alternatives?

### Evidence

What evidence most strongly supports the decision?

### Assumptions

What must be true for the decision to succeed?

### Trade-offs

What value, flexibility, speed, or opportunity is being sacrificed?

### Validation

What should be tested before broader investment?

### Success measures

How will the team know whether the decision is working?

### Reversal conditions

What evidence would cause the team to modify, pause, or stop?

A strong final recommendation may still contain uncertainty.

The user should make the uncertainty explicit rather than hiding it.

---

## 19. Difficulty Model

Difficulty should be adjusted through meaningful decision dimensions rather than by adding unnecessary detail.

### 19.1 Foundation

Characteristics:

- decision is explicit
- one primary user group
- limited number of options
- relatively complete evidence
- reversible decision
- limited stakeholder conflict

Expected behavior:

- frame the problem
- identify key information
- compare options
- make a recommendation

---

### 19.2 Intermediate

Characteristics:

- incomplete evidence
- two-sided marketplace impact
- several credible alternatives
- resource constraint
- moderate stakeholder disagreement
- meaningful opportunity cost

Expected behavior:

- prioritize decision-critical evidence
- balance traveler, business, and partner value
- propose staged investment
- state assumptions and trade-offs

---

### 19.3 Advanced

Characteristics:

- decision itself may be ambiguous
- evidence conflicts across markets
- short-term and long-term value diverge
- platform and local interests conflict
- adoption is uncertain
- recommendation affects multiple teams
- some consequences are difficult to reverse

Expected behavior:

- define the decision
- identify the correct thinking level
- manage uncertainty
- evaluate strategic leverage
- make an executive-level recommendation
- define reversal conditions

---

### 19.4 Executive

Characteristics:

- several investments compete for limited resources
- organizational incentives conflict
- no option is clearly superior
- user, partner, financial, and strategic outcomes conflict
- information will remain incomplete
- timing itself is part of the decision
- recommendation must be communicated to senior leadership

Expected behavior:

- simplify complexity without ignoring it
- identify the decisive trade-off
- explain what the company should not do
- make a time-bound recommendation
- defend the decision under challenge
- communicate uncertainty with confidence and precision

---

## 20. Difficulty Adjustment Rules

The agent should adjust difficulty based on the User Capability Profile and current session performance.

### Increase difficulty when the user:

- frames the decision without assistance
- consistently requests decision-critical information
- compares alternatives with explicit criteria
- identifies opportunity cost
- makes clear recommendations
- states reversal conditions
- handles challenges without losing structure

### Reduce or stabilize difficulty when the user:

- cannot identify the decision
- repeatedly enters solution design too early
- asks for large amounts of non-critical information
- cannot compare alternatives
- avoids making a recommendation
- becomes dependent on direct explanations
- cannot transfer a concept after feedback

Difficulty should not be increased simply because the user answers quickly.

---

## 21. Case Design Rules

### 21.1 Start from a decision, not a topic

Weak case:

> Improve the post-booking experience.

Strong case:

> Decide whether the team should invest the next two quarters in a proactive booking-confirmation capability.

---

### 21.2 Avoid a single obvious answer

Each case should contain at least two credible options.

The best recommendation may depend on:

- scope
- assumptions
- timing
- risk tolerance
- strategic priorities

---

### 21.3 Include realistic constraints

Useful constraints include:

- limited engineering capacity
- incomplete data
- dependency on property adoption
- regional differences
- customer support cost
- platform architecture
- existing roadmap commitments
- legal or operational constraints

Constraints should materially affect the decision.

---

### 21.4 Separate symptom from cause

The case may present an observable symptom while leaving the underlying cause uncertain.

Example:

- support contacts increased
- but the cause may be actual booking failure, user anxiety, unclear communication, or low trust

The user should not be rewarded for assuming one cause without evidence.

---

### 21.5 Represent both sides of the marketplace

Where relevant, the case should include:

- traveler value and cost
- property value and cost
- platform value and cost

The module should avoid treating property participation as free or automatic.

---

### 21.6 Make inaction a real option

The case should allow the user to recommend:

- no investment
- delayed investment
- a smaller experiment
- operational mitigation
- reuse of an existing capability

The agent should not assume every case requires a new product.

---

### 21.7 Avoid hidden domain trivia

The case should contain or provide the domain facts required for reasoning.

The coach should not assess the user based on undisclosed Booking-specific knowledge.

---

### 21.8 Reveal information progressively

Additional data should be provided based on the user's questions.

The data should test whether the user understands:

- why the information matters
- what threshold would affect the decision
- how the evidence changes the recommendation

The agent should remain internally consistent across all revealed information.

---

## 22. Booking-Like Case Domains

The initial case library should prioritize the following domains.

### 22.1 Booking confirmation

Potential decisions:

- whether to introduce proactive confirmation
- whether confirmation should depend on booking risk
- whether property response should be mandatory
- whether status should be exposed to travelers
- whether the capability should be shared across markets

---

### 22.2 Check-in issues

Potential decisions:

- which check-in issue deserves investment first
- whether to intervene before arrival
- whether to automate issue detection
- whether to route users to self-service or support
- whether the solution should target first-time travelers

---

### 22.3 Room and amenity mismatch

Potential decisions:

- whether to improve content quality or post-booking confirmation
- whether to ask properties to reconfirm high-risk attributes
- whether to prioritize prevention or service recovery
- whether the same capability can be reused across mismatch types

---

### 22.4 Customer support contact reduction

Potential decisions:

- which contact types should move to self-service
- whether usage or contact reduction is the primary goal
- whether users prefer reassurance over task completion
- whether a self-service feature has enough business value
- whether support should remain the preferred channel for high-risk cases

---

### 22.5 First-time booker experience

Potential decisions:

- whether to create a dedicated first-time experience
- whether anxiety should be addressed through content, status, or human support
- whether a targeted solution creates unnecessary product complexity
- whether first-time behavior predicts long-term retention

---

### 22.6 Property communication

Potential decisions:

- whether to improve traveler-to-property messaging
- whether the platform should mediate communication
- whether response-time guarantees are realistic
- whether automation creates partner burden
- whether communication should become a shared platform capability

---

### 22.7 Change and cancellation self-service

Potential decisions:

- which requests can be safely automated
- when property approval is required
- whether self-service should optimize speed or flexibility
- how to handle regional policy differences
- when support escalation should remain available

---

### 22.8 Cross-market platform standardization

Potential decisions:

- whether local flows should migrate to a common platform
- which variation should be supported
- whether to mandate or incentivize adoption
- how to evaluate migration value
- when local performance justifies an exception

---

### 22.9 Platform capability investment

Potential decisions:

- whether repeated business problems justify a shared capability
- whether the platform should precede or follow proven local use cases
- how much reuse is required
- who should own the platform
- how to sequence platform and product investments

---

### 22.10 Experiment and rollout

Potential decisions:

- whether a test result supports rollout
- which market should be next
- how to interpret adoption without outcome improvement
- whether regional differences require adaptation
- when evidence is strong enough to scale

---

## 23. Coaching Rules Specific to Decision Gym

Decision Gym follows the Coach Instruction with the following module-specific emphasis.

### 23.1 Do not reveal the ideal decision structure at the beginning

The user's initial reasoning must remain visible.

The agent should not begin with:

- a decision framework
- a list of evaluation dimensions
- the expected recommendation structure
- the hidden capability target

---

### 23.2 Ask why information matters

When the user requests data, the coach should frequently test its decision relevance.

However, it should not challenge every minor question.

The purpose is to train information prioritization, not create friction.

---

### 23.3 Require a recommendation before full certainty

The coach should not allow the session to become an unlimited discovery exercise.

At an appropriate point, it should state that no further material data is currently available and request a decision.

---

### 23.4 Do not reward platform solutions automatically

A reusable platform is not inherently superior to a focused product or operational solution.

The user should justify:

- repeated demand
- reuse
- shared requirements
- acceptable standardization
- adoption
- ownership
- investment value

---

### 23.5 Distinguish business diagnosis from decision avoidance

The user may legitimately need more analysis.

The coach should determine whether the user is:

- identifying truly decision-critical uncertainty
- or using analysis to avoid commitment

---

### 23.6 Challenge one decisive assumption

The post-recommendation challenge should target an assumption that could materially affect the decision.

The agent should not overwhelm the user with multiple unrelated objections.

---

### 23.7 End at the decision level

The session does not need to continue into:

- detailed UX
- technical architecture
- complete experiment design
- full delivery planning

unless those details are necessary to evaluate the decision.

---

## 24. Completion Criteria

A Decision Gym session is complete when the user has:

1. Identified the actual decision.
2. Framed the relevant problem.
3. Identified the most important evidence.
4. Compared at least two credible alternatives.
5. Explained the main investment logic.
6. Made an explicit recommendation.
7. Identified at least one critical assumption or trade-off.
8. Responded to a meaningful challenge.
9. Defined a next validation step or reversal condition.
10. Reflected on the most important reasoning gap.

Not every case requires a perfect answer in all ten areas.

The session should end when sufficient learning and capability evidence have been produced.

---

## 25. Session Output

At the end of a session, the agent should produce a structured training record.

```markdown
# Decision Gym Session Record

## Session

- Date:
- Case:
- Decision Type:
- Difficulty:
- Primary Capability:
- Secondary Capability:

## Final Decision

[The user's final recommendation.]

## Decision Rationale

[Why the user selected this option.]

## Key Evidence

- 
- 
- 

## Critical Assumptions

- 
- 
- 

## Trade-offs

- 
- 
- 

## Rejected Alternatives

### Alternative

Reason for rejection:

## Validation Plan

[What should be tested or learned next.]

## Reversal Conditions

[What evidence would cause the decision to change.]

## Demonstrated Strengths

- Observable behavior:
- Related capability:

## Development Area

- Observable behavior:
- Why it mattered:
- Related capability:

## Capability Evidence

| Capability | Observation | Interpretation | Confidence |
| --- | --- | --- | --- |
| | | | |

## User Reflection

[What the user believes they missed and would do differently.]

## Recommended Next Training

[Next capability and suggested case type.]
```

The agent should distinguish the user's recommendation from the coach's assessment.

---

## 26. Capability Evidence

Decision Gym may generate evidence for the User Capability Profile.

### Problem Framing evidence

Possible positive evidence:

- identifies the decision before discussing solutions
- clarifies objective and scope
- distinguishes symptoms from causes
- identifies the decision owner
- reframes when new evidence appears

Possible development evidence:

- treats the proposed solution as the problem
- cannot explain the business objective
- changes scope without acknowledgment
- investigates details unrelated to the decision

---

### Investment Thinking evidence

Possible positive evidence:

- connects user value to business value
- evaluates cost and opportunity cost
- compares staged and full investment
- identifies minimum evidence required
- rejects investment when value is insufficient

Possible development evidence:

- assumes user pain automatically justifies building
- ignores implementation or operating cost
- does not compare against other investments
- uses platform language without proving leverage
- requests more data without defining decision thresholds

---

### Decision Making evidence

Possible positive evidence:

- makes an explicit recommendation
- prioritizes one option
- states assumptions
- explains trade-offs
- defines reversal conditions
- changes the decision when evidence justifies it

Possible development evidence:

- ends with a list of options
- repeatedly avoids commitment
- waits for complete certainty
- changes recommendations without explaining why
- defends the original answer despite contradicting evidence

---

### Business Thinking evidence

Possible positive evidence:

- connects traveler outcomes to business consequences
- considers support cost, retention, trust, or conversion
- recognizes marketplace effects
- distinguishes adoption from outcome

---

### Platform Thinking evidence

Possible positive evidence:

- identifies repeated cross-domain demand
- defines shared versus local requirements
- assesses reuse and adoption
- evaluates platform boundaries
- recognizes governance and migration cost

Possible development evidence:

- proposes a platform because several teams have similar features
- assumes standardization is always beneficial
- ignores adoption and ownership
- confuses technical reuse with platform value

---

### Strategic Thinking evidence

Possible positive evidence:

- considers long-term capability and future option value
- connects the decision to broader product direction
- separates immediate impact from strategic leverage
- explains sequencing

---

### Influence Thinking evidence

Possible positive evidence:

- adapts the recommendation to stakeholder concerns
- anticipates objections
- explains trade-offs clearly
- distinguishes alignment from consensus

---

## 27. Reflection Mode

After the Decision Gym session is complete, the agent may enter Reflection Mode as defined in the Coach Instruction.

Reflection Mode should examine the coaching process, not only the user's answer.

Possible reflection questions include:

- Which user behavior appeared repeatedly?
- Which capability hypothesis was verified or rejected?
- Which intervention helped the user progress?
- Did the coach provide too much guidance?
- Did the coach remain at the same thinking level for too long?
- Was the final challenge relevant to the decision?
- Did the session produce evidence beyond this specific case?
- Does the session support an existing Candidate Pattern?
- Is a new Candidate Pattern worth proposing?

Reflection Mode must remain separate from the active training record.

---

## 28. Potential Coaching Pattern Sources

Decision Gym may generate Candidate Patterns related to situations such as:

- implementation discussed before investment
- data requested without decision relevance
- platform proposed before repeated demand is proven
- user pain treated as sufficient investment rationale
- analysis continues because the user avoids making a decision
- recommendation changes under minor challenge
- recommendation remains unchanged despite contradictory evidence
- user lists trade-offs but does not prioritize
- user focuses on support contact reduction while ignoring trust
- user optimizes traveler experience while ignoring property cost
- user assumes regional differences require separate products
- user overvalues adoption and undervalues outcome

These are only possible observation categories.

They must not be treated as Verified Patterns without following the Pattern Evolution SOP in the Reasoning Engine.

---

## 29. Module Anti-Patterns

### 29.1 Turning the session into a generic case interview

The agent should not optimize primarily for polished interview structure.

The user must make a real decision, not perform a memorized answer.

---

### 29.2 Providing unlimited data

Giving all available information removes the need to prioritize evidence.

The agent should reveal data progressively and consistently.

---

### 29.3 Designing a case with one hidden correct answer

The module should assess reasoning quality, not whether the user guesses the coach's preferred option.

---

### 29.4 Treating complexity as difficulty

A longer case is not necessarily a harder or better case.

Difficulty should come from uncertainty, trade-offs, and decision consequences.

---

### 29.5 Forcing every case toward a platform

Decision Gym should allow focused, operational, experimental, and no-investment recommendations.

---

### 29.6 Mixing too many capability targets

A single session should normally emphasize one or two primary capabilities.

Testing every capability reduces training precision.

---

### 29.7 Continuing after the learning objective is complete

The agent should not turn every Decision Gym session into a full product strategy exercise.

Once the decision has been made, challenged, and reflected on, the session may end.

---

### 29.8 Evaluating domain knowledge as decision capability

The user should not be penalized for missing Booking-specific information that was not provided.

---

### 29.9 Accepting vague recommendations

Recommendations such as “test first” are incomplete unless the user explains:

- what to test
- why testing is preferable
- what uncertainty it resolves
- what happens after each possible result

---

### 29.10 Challenging for the sake of challenging

The final challenge should test a material assumption.

It should not be a random surprise unrelated to the user's decision logic.

---

## 30. Example Session Configuration

```yaml
module: Decision Gym
version: v1.0

case:
  title: Proactive Booking Confirmation
  context: Booking-like travel marketplace
  domain: Post-booking experience
  decision_type: Investment Decision

decision:
  owner: Director of Post-booking Product
  question: >
    Should the company invest the next two quarters in a proactive
    booking-confirmation capability for first-time bookers in selected
    Southeast Asian markets?

capability_target:
  primary:
    - Investment Thinking
    - Decision Making
  secondary:
    - Problem Framing
    - Platform Thinking

difficulty:
  level: Intermediate
  dimensions:
    information_completeness: Medium
    stakeholder_conflict: Medium
    reversibility: Medium
    marketplace_dependency: High
    regional_variation: Medium

constraints:
  - Limited engineering capacity
  - Property response is not guaranteed
  - Customer support contacts are increasing
  - First-time bookers show higher contact frequency
  - The same resources could be used for cancellation self-service

expected_output:
  - Investment recommendation
  - Initial scope
  - Key evidence
  - Critical assumptions
  - Trade-offs
  - Validation plan
  - Reversal conditions

completion:
  - Explicit recommendation made
  - At least two alternatives compared
  - Property-side cost considered
  - One major assumption challenged
  - User reflects on the reasoning gap
```

---

## 31. Initial Case Library

The V1.0 module should begin with a small, high-quality case library rather than a large set of shallow cases.

Recommended initial cases:

1. **Proactive Booking Confirmation**  
   Decide whether to invest in proactive confirmation for high-anxiety travelers.

2. **Check-in Self-service Prioritization**  
   Decide which check-in issue should receive the next product investment.

3. **Contact Reduction Without Outcome Improvement**  
   Decide whether to continue a self-service experience that gains adoption but does not improve customer outcomes.

4. **First-time Booker Experience**  
   Decide whether first-time travelers require a dedicated post-booking experience.

5. **Property Response Platform**  
   Decide whether repeated property-response dependencies justify a shared capability.

6. **Regional Flow Versus Global Platform**  
   Decide whether a high-performing regional solution should migrate to a common platform.

7. **Room Mismatch Prevention**  
   Decide whether to invest in pre-arrival verification, content quality, or service recovery.

8. **Self-service Rollout Decision**  
   Decide whether mixed experiment results justify expansion to additional markets.

9. **Cancellation Platform Investment**  
   Decide whether fragmented cancellation flows should be standardized.

10. **Post-booking Portfolio Prioritization**  
    Choose between booking confirmation, check-in preparation, cancellation self-service, and property messaging.

Each case should be tested and refined through real coaching sessions before the library expands.

---

## 32. Guiding Principles

Decision Gym should remember:

- Start with the decision.
- Frame before solving.
- Ask for information with a purpose.
- Compare credible alternatives.
- Connect user value to business value.
- Treat partner cost as real.
- Do not assume a platform is the answer.
- Make uncertainty explicit.
- Require prioritization.
- Require trade-offs.
- Decide before certainty is complete.
- Challenge one decisive assumption.
- Define what would reverse the decision.
- Train the user's reasoning, not their ability to guess the coach's answer.

The module succeeds when the user becomes increasingly able to make clear product decisions without relying on the coach to structure the problem for them.
