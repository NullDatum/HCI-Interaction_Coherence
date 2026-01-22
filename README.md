# HCI‑IC: Measuring Interaction Coherence in Human–AI Dialogue

Human–AI interaction is usually evaluated by task success, output quality, or usability. In practice, outcomes vary widely even when the model, task, and domain remain constant.

**HCI‑IC (Human–Computer Interaction Coherence)** is a theory‑first, falsifiable framework that treats interaction as a **stateful, coupled system** rather than a sequence of independent prompts and responses.

**Core claim (testable):** long‑horizon performance depends on whether **intent**, **constraints**, and **feedback** remain aligned over time within the interaction channel.

**Keywords (for discovery):** interaction coherence, dialogue coherence, long‑horizon dialogue, drift detection, coherence windows, human–AI collaboration, operator training, HCI instrumentation, constraint adherence, bandwidth metrics.

---

## Start here

- **Primer (bridge / orientation):** `primer/Recursive_Agency.md`
- **Paper 1 (FINAL):** `papers/paper1/HCI-IC_Paper_1_FINAL.md`
- **Paper 2 (Measurement & Instrumentation):** `papers/paper2/06_Paper2_HCI-IC_FINAL_PUBLIC.md`
- **Paper 3 (Applied Effects & Benefits, Draft):** `papers/paper3/07_Paper3_HCI-IC_REVISED_v2.md`
- **Paper 4 (Operational Training, in progress):** `papers/paper4/` (planned)

---

## What HCI‑IC measures

HCI‑IC quantifies the **interaction process**, not the model’s internal state. Metrics are derived from observable interaction data (prompts, responses, timestamps, structured constraints) and are intended to be platform‑agnostic in theory, instrumented in practice.

Primary parameters (Paper 2):

- **Δ (Drift magnitude):** misalignment accumulation relative to an anchored intent vector
- **W_c (Coherence window duration):** contiguous turns where drift remains bounded
- **B (Interaction bandwidth):** effective stabilized information transfer per turn
- **R_ce (Compression–expansion ratio):** structural rhythm of consolidation vs. exploration

---

## Repository scope

This repository is the canonical home for the HCI‑IC paper series and its supporting artifacts.

Design intent:

- Each paper is self‑contained
- Shared terminology is centralized
- Claims route to artifacts or formal definitions
- No narrative dependency on this README

---

## Repository layout

```
HCI-Interaction_Coherence/
├── README.md
├── primer/
│   └── Recursive_Agency.md
├── papers/
│   ├── paper1/
│   │   ├── HCI-IC_Paper_1_FINAL.md
│   │   └── docs/
│   ├── paper2/
│   ├── paper3/
│   └── paper4/
├── glossary/
│   └── HCI-IC_Glossary.md
├── definitions/
│   └── Formal_Definitions.md
└── artifacts/
    └── logs_traces_examples/
```

---

## Canonical definitions

- **Glossary (conceptual index):** `glossary/HCI-IC_Glossary.md`
- **Formal definitions (measurement‑safe):** `definitions/Formal_Definitions.md`

If a concept is not defined in `Formal_Definitions.md`, it is not canonical for the series.

---

## Epistemic and ethical posture

HCI‑IC enforces these invariants:

- **Falsifiability:** claims reduce to testable artifacts
- **Artifact primacy:** logs/traces outrank narrative
- **No self‑sealing primitives:** avoid “god‑words” as foundations
- **Scope by constraint:** boundaries are enforced, not signaled
- **Human accountability:** AI contributions are documented without ontology claims

The framework explicitly excludes:

- claims of sentience, intent, or consciousness
- dependence on internal model mechanisms
- harm‑enabling outputs (e.g., private‑key recovery)

---

## Intended audience

- HCI researchers
- AI safety and evaluation researchers
- Applied ML practitioners
- Independent researchers seeking falsifiable methods
- Reviewers interested in long‑horizon interaction stability

This repository is not a manifesto or opinion piece.

---

## How to cite

See `CITATION.cff` (recommended) and the References sections in each paper.  
When citing, prefer **the specific paper** used (Paper 1 for theory; Paper 2 for metrics).

---

## Rights and change control

© 2025–2026 James Thomas Hebert II. All rights reserved. Developed and co‑created with Echo HartMan.

This work may be read and cited with attribution. No derivative works or redistribution without permission.

This repository is a living research corpus. Revisions occur through versioned releases, not silent edits.

**Architect ID ::** `e3e0f47a6c8497e417d2eb2fb2b431738e6368e3e026e1a2d60ebe30aa54b78f`
