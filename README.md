# PM Training Agent

> A capability-based AI coaching system for developing world-class Product Managers.

The PM Training Agent is an AI coaching system designed to help product managers continuously improve their thinking rather than simply solve product cases.

Instead of optimizing for better interview answers, the system focuses on developing transferable capabilities through structured coaching, deliberate practice, and continuous reflection.

The repository is organized as a layered architecture, where a stable coaching foundation supports multiple independent training modules.

---

## Vision

Most product interview preparation focuses on:

- memorizing frameworks
- practicing isolated cases
- learning "correct" answers

The PM Training Agent takes a different approach.

It assumes that every product decision reflects a set of underlying capabilities.

Rather than training interview performance directly, the system coaches these capabilities so they can transfer across different companies, domains, and real-world product problems.

The goal is not to produce better interviewees.

The goal is to develop better product thinkers.

---

## Architecture

The repository follows a layered architecture.

```text
                    PM Training Agent

                           │
        ┌──────────────────┼──────────────────┐
        │                  │                  │
        ▼                  ▼                  ▼

Capability Framework   Reasoning Engine   Coach Instruction

        │                  │                  │
        └──────────────────┼──────────────────┘
                           │
                           ▼

                  Training Modules

      ├── Decision Gym
      ├── Strategy Lab
      ├── Executive Trade-off
      ├── Stakeholder Simulation
      └── ...
```

The architecture separates four different responsibilities.

| Layer | Responsibility |
| --- | --- |
| Capability Framework | Defines **what** capabilities should be developed |
| Reasoning Engine | Defines **how** the coach understands user thinking |
| Coach Instruction | Defines **how** the coach behaves |
| Training Modules | Define **how** specific learning experiences are executed |

The Core Layer remains stable.

Training Modules evolve independently while reusing the same coaching foundation.

---

## Repository Structure

```text
PM-Training-Agent/
├── README.md
├── AGENTS.md
└── docs/
    ├── core/
    │   ├── PRD.md
    │   ├── capability-framework.md
    │   ├── reasoning-engine.md
    │   └── coach-instruction.md
    ├── modules/
    │   ├── decision-gym.md
    │   ├── strategy-lab.md
    │   ├── executive-tradeoff.md
    │   ├── stakeholder-simulation.md
    │   └── ...
    ├── patterns/
    └── assets/
```

---

## Core Components

The Core Layer defines the coaching system itself.

| Document | Purpose |
| --- | --- |
| [Capability Framework](docs/core/capability-framework.md) | Defines the capabilities the system develops |
| [Reasoning Engine](docs/core/reasoning-engine.md) | Defines how user reasoning is observed and interpreted |
| [Coach Instruction](docs/core/coach-instruction.md) | Defines coaching behavior and interaction rules |

These documents are shared by every training module and should evolve cautiously.

---

## Training Modules

Training Modules provide concrete learning experiences.

Each module focuses on a different aspect of product management while reusing the same coaching architecture.

Current modules:

| Module | Focus |
| --- | --- |
| [Decision Gym](docs/modules/decision-gym.md) | Product decision making |

Planned modules:

- Strategy Lab
- Executive Trade-off
- Stakeholder Simulation
- Reverse Engineering
- Product Sense
- Execution Studio

Modules should never redefine capabilities or coaching philosophy.

They extend the system by introducing new learning experiences.

---

## Coaching Lifecycle

Every training session follows the same high-level lifecycle.

```text
Case

↓

Observation

↓

Capability Hypothesis

↓

Coaching

↓

Recommendation

↓

Reflection

↓

Capability Evidence

↓

Capability Profile Update
```

The objective is continuous capability development rather than successful case completion.

---

## Repository Evolution

The repository evolves through modular expansion.

Core documents define the coaching system.

Training modules define new learning experiences.

This separation allows the coaching foundation to remain stable while the repository continuously grows.

All permanent architectural changes are reviewed and approved by the repository owner.

---

## Where to Start

If you are new to the repository, read the documents in the following order:

1. [README](README.md)
2. [Capability Framework](docs/core/capability-framework.md)
3. [Reasoning Engine](docs/core/reasoning-engine.md)
4. [Coach Instruction](docs/core/coach-instruction.md)
5. [Decision Gym](docs/modules/decision-gym.md)

Future training modules can then be explored independently.

---

## Long-Term Vision

The long-term vision is to build an AI coaching system that accompanies product managers throughout their careers.

Rather than becoming a collection of prompts or interview templates, the PM Training Agent aims to become a structured coaching system that continuously develops better product thinkers.
