# PM Training Agent

An AI coaching system for experienced Product Managers to strengthen product thinking through deliberate practice.

## Project Overview

PM Training Agent focuses on five capability areas:

- Decision Making
- Platform Thinking
- Investment Thinking
- Strategy Planning
- Stakeholder Influence

The goal is not to teach product knowledge. It is to help experienced Product Managers improve how they think, reason, and make decisions through deliberate practice.

## Documentation

- [Product Requirements](docs/PRD.md) — Source of truth for product scope and requirements.
- [Coach Instruction](docs/Coach-Instruction.md) — Coaching behavior and interaction guidelines.

## Development Principles

- Documentation before implementation.
- Product thinking over knowledge transfer.
- Deliberate practice over passive learning.
- No functionality outside the approved PRD.
- Clear separation between product requirements and coaching instructions.

## Development Workflow

1. Define and approve requirements in `docs/PRD.md`.
2. Align coaching behavior in `docs/Coach-Instruction.md`.
3. Implement only the approved scope.
4. Validate implementation against the documentation.
5. Update documentation before changing product behavior.

## Repository Structure

```text
pm-training-agent/
├── README.md
└── docs/
    ├── PRD.md
    └── Coach-Instruction.md
```

## Current Status

The project is in its initial documentation phase. Product requirements and coaching instructions are being defined before implementation begins.
