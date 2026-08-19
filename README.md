# System Design Learning Log 🧠📐

A personal, evolving repository where I document my system design learning journey — both **High-Level Design (HLD)** and **Low-Level Design (LLD)** — concepts, trade-offs, real-world case studies, and diagrams (all rendered natively in GitHub via Mermaid).

> **Why this repo exists:** to force myself to explain concepts in my own words, keep a searchable diagram archive, and track progress over time instead of losing notes across scattered docs. Built specifically for an AI Engineer background — classic fundamentals first, then ML/AI-specific patterns where my actual production experience becomes the differentiator.

---

## 📂 Repository Structure

```
root/
├── README.md          ← you are here (overview + top-level tracker)
├── HLD/                ← system design: fundamentals, ML/AI patterns, mock case studies
│   └── README.md       ← full HLD curriculum + tracker
└── LLD/                ← low-level design: OOP, SOLID, patterns, mock problems
    └── README.md       ← full LLD curriculum + tracker
```

Each subdirectory is self-contained: its own README with curriculum, progress tracker, note templates, and diagram conventions. This root README only tracks module-level completion and links out.

---

## 🗂️ Where to go

| Directory | What it covers | Framework used |
|---|---|---|
| [`/HLD`](./HLD/README.md) | Classic system design fundamentals (scaling, caching, CAP, queues, rate limiting) + ML/AI-specific patterns (RAG, model serving, agents, feature stores) + full mock case studies | 5-step: Clarify → Estimate → High-level design → Deep dive → Trade-offs |
| [`/LLD`](./LLD/README.md) | OOP, SOLID, object relationships, design patterns (creational/structural/behavioral), UML, concurrency, persistence + 23 classic LLD problems | 6-step: Clarify scope → Core objects → Relationships → Patterns → Diagrams → Extend & harden |

---

## 📊 Top-Level Module Tracker

| Module | Directory | Status | Target |
|---|---|---|---|
| A — Classic System Design Fundamentals | `HLD/` | ⬜ Not Started | Weeks 1-2 |
| B — Low-Level Design Fundamentals | `LLD/` | ⬜ Not Started | Weeks 2-3 |
| C — ML/AI-Specific System Design Patterns | `HLD/` | ⬜ Not Started | Weeks 4-5 |
| D — Full HLD Mock Sessions (10 prompts) | `HLD/` | ⬜ Not Started | Ongoing |
| E — Full LLD Mock Sessions (23 problems) | `LLD/` | ⬜ Not Started | Ongoing |

**Legend:** ⬜ Not Started · 🟨 In Progress · ✅ Done

Detailed, topic-by-topic trackers live in each subdirectory's own README — this table is just the bird's-eye view.

---

## 🗣️ Frameworks at a Glance

**HLD (system design) — 5 steps, out loud, timed:**
1. Clarify requirements (functional + non-functional)
2. Estimate scale (back-of-envelope)
3. High-level design (components + data flow)
4. Deep dive (1-2 components)
5. Trade-offs & bottlenecks

**LLD (low-level design) — 6 steps, out loud, timed:**
1. Clarify requirements & scope
2. Identify core objects & responsibilities
3. Define relationships (association/aggregation/composition/dependency)
4. Apply relevant design pattern(s) — don't force-fit
5. Sketch class + sequence diagrams
6. Extend & harden (new requirement, concurrency, error handling, persistence)

Full detail, note templates, and diagram conventions for each are in their respective subdirectory READMEs.

---

## 📚 Shared Resources

- *Designing Data-Intensive Applications* — Martin Kleppmann
- *System Design Interview* Vol 1 & 2 — Alex Xu
- *Head First Design Patterns* — Freeman & Robson
- *Design Patterns: Elements of Reusable Object-Oriented Software* — Gang of Four
- [High Scalability blog](http://highscalability.com/)
- [Refactoring.Guru](https://refactoring.guru/design-patterns)
- [ByteByteGo](https://bytebytego.com/)
- Engineering blogs: Uber, Netflix, Airbnb, Discord, Meta

(Topic-specific resources also appear at the bottom of each subdirectory README.)

---

## 🎯 Overall Goals

- [ ] Complete `HLD/` Module A (classic fundamentals) — Weeks 1-2
- [ ] Complete `LLD/` Module B (LLD fundamentals) — Weeks 2-3
- [ ] Complete `HLD/` Module C (ML/AI-specific patterns) — Weeks 4-5
- [ ] Complete all 10 HLD mock sessions, timed and out loud
- [ ] Complete at least 12 of 23 LLD mock problems, timed and out loud
- [ ] Run at least 2-3 mock sessions of each type (HLD + LLD) with a partner playing interviewer
- [ ] Revisit and refine older notes as understanding deepens
- [ ] Use this repo actively during interview prep

---

