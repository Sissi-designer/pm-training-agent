# AGENTS.md

> Operational rules for AI agents contributing to the PM Training Agent repository.

This document defines how AI coding agents (e.g. Codex, Claude Code, Cursor, OpenAI Agents) should interact with this repository.

It is **not** a coaching document.

It is **not** a system prompt.

It defines repository governance and documentation rules.

---

## Repository Purpose

This repository contains the knowledge architecture of the PM Training Agent.

The repository is designed as a layered coaching system rather than a collection of prompts.

Every document has a clearly defined responsibility.

Maintaining that separation is more important than introducing new content.

---

## Source of Truth

The repository contains two architectural layers.

### Core Layer

```text
Capability Framework
Reasoning Engine
Coach Instruction
```

These documents define the coaching system.

They are the source of truth for:

- capabilities
- reasoning
- coaching behavior

Core documents evolve slowly.

They should not be modified unless explicitly requested.

### Module Layer

Training Modules implement concrete learning experiences.

Examples:

- Decision Gym
- Strategy Lab
- Executive Trade-off

Modules may evolve independently.

Modules must reuse the Core Layer.

Modules must never redefine it.

---

## Document Ownership

Every document owns one responsibility.

| Document | Owns |
| --- | --- |
| README | Repository overview |
| Capability Framework | Capability definitions |
| Reasoning Engine | Reasoning process |
| Coach Instruction | Coaching behavior |
| Training Modules | Learning workflows |
| AGENTS | Repository governance |

Do not duplicate responsibilities across documents.

When information belongs to another document, reference it instead of copying it.

---

## Modification Rules

Unless explicitly instructed, AI agents must not:

- redesign repository architecture
- redefine capabilities
- rewrite coaching philosophy
- merge document responsibilities
- introduce duplicate concepts
- rename core documents
- change document ownership

Documentation should evolve incrementally.

Architectural changes require explicit approval.

---

## Preferred Workflow

When asked to modify the repository:

1. Review the current architecture.
2. Identify the correct document owner.
3. Propose changes.
4. Wait for approval.
5. Apply approved changes only.
6. Show a diff.
7. Never modify unrelated documents.

---

## Documentation Principles

When writing documentation:

Prefer:

- clear hierarchy
- concise writing
- modular structure
- single responsibility
- cross references instead of duplication

Avoid:

- repeating concepts
- mixing architecture with implementation
- introducing competing terminology
- redefining existing concepts

---

## Repository Evolution

The repository grows through:

- new training modules
- improved coaching patterns
- refined reasoning models

The repository should not grow by expanding README or duplicating Core concepts.

New ideas should first determine:

1. Does this belong to the Core Layer?
2. Does this belong to a Module?
3. Does this belong to AGENTS?
4. Is this only an implementation detail?

Only then should documentation be updated.

---

## AI Collaboration Principles

AI agents are collaborators, not repository owners.

AI may:

- improve clarity
- improve formatting
- identify inconsistencies
- propose reusable abstractions
- suggest refactoring

AI must not:

- make architectural decisions autonomously
- rewrite the coaching philosophy
- invent new capabilities
- promote experimental ideas into the Core Layer
- remove concepts without explanation

When uncertain, ask rather than assume.

---

## Definition of Success

A successful contribution makes the repository:

- easier to understand
- easier to extend
- more internally consistent

It does not make the repository larger.

It does not make the repository more complicated.

When in doubt, preserve simplicity.
