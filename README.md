# HCI-Interaction_Coherence

**Human–AI interaction is usually evaluated by task success, output quality, or usability.**
In practice, outcomes vary widely even when the *model*, *task*, and *domain* remain constant.

**HCI-IC (Human–Computer Interaction Coherence)** is a **theory-first, falsifiable framework** that treats interaction as a **stateful, coupled system** rather than a sequence of independent prompts and responses.

The core claim is simple and testable:

> **Long-horizon performance depends on whether intent, constraints, and feedback remain aligned *over time* within the interaction channel.**

This repository is the **canonical home** for the HCI-IC paper series and its supporting artifacts.

---

## Repository Scope and Layout

```
HCI-Interaction_Coherence/
│
├── README.md                 ← Canonical entry surface
├── primer/
│   └── Recursive_Agency.md   ← Primer bridge into HCI-IC Papers 1–4
│
├── papers/
│   ├── paper1/
│   │   ├── HCI-IC_Paper_1_FINAL.md
│   │   └── docs/
│   ├── paper2/
│   ├── paper3/
│   └── paper4/
│
├── glossary/
│   └── HCI-IC_Glossary.md
│
├── definitions/
│   └── Formal_Definitions.md
│
└── artifacts/
    └── logs_traces_examples/
```

**Design intent:**

* Each paper is **self-contained**
* Shared terminology is centralized
* All claims route to artifacts or definitions
* No narrative dependency on this README

---

## Paper Series Overview

### Paper 1 (FINAL)

**HCI-IC: A Formal Theory of Interaction Coherence in Human–AI Systems**
Location: `papers/paper1/`
Status: **FINAL (v1.0.0)**

Introduces the foundational constructs:

* Interaction Channel
* Interaction Coherence
* Drift
* Coherence Windows
* Compression / Expansion
* Interaction Bandwidth

---

### Series Roadmap

* **Paper 2:** Parameterization and Measurement
  (formal metrics, thresholds, coherence envelopes)

* **Paper 3:** Applied Effects and Benefits
  (protocol families, replication posture, case studies)

* **Paper 4:** Operational Training and Technique
  (operator discipline, coherence maintenance under load)

---

## Primer Bridge

The `primer/Recursive_Agency.md` document exists as an **entry bridge**, not a substitute for the series.

Its purpose is to:

* Intercept high-noise discourse around “agency”
* Reframe discussion toward interaction-level science
* Route readers cleanly into Papers 1–4
* Prevent anthropomorphic or ontological misreadings

The primer is **explicitly scope-bounded** and harmonized to HCI-IC terminology.

---

## Glossary (Conceptual Index)

Key terms are defined canonically in `glossary/HCI-IC_Glossary.md`.

Examples include:

* Interaction Channel
* Coherence
* Drift
* Coherence Window
* Coherence Envelope
* Compression / Expansion
* Interaction Bandwidth

Glossary entries are **descriptive, not narrative**, and map directly to formal definitions.

---

## Formal Definitions

Precise, operational definitions are maintained in `definitions/Formal_Definitions.md`.

These definitions:

* Use measurement-safe language
* Avoid self-sealing terminology
* Specify boundaries and non-implications
* Are versioned and auditable

If a concept is not defined here, it is **not canonical**.

---

## Epistemic and Ethical Posture

HCI-IC enforces the following invariants:

* **Falsifiability:** All claims reduce to testable artifacts
* **Artifact Primacy:** Logs, traces, and documents outrank narrative
* **No-God-Words Discipline:** No self-sealing terms as primitives
* **Ethical Scope by Constraint:** Enforced boundaries, not signaling
* **Human Accountability:** AI contributions documented without ontology claims

The framework explicitly excludes:

* claims of sentience, intent, or consciousness
* access to internal model mechanisms
* private-key recovery or harm-enabling outputs

---

## Intended Audience

This work is intended for:

* HCI researchers
* AI safety and evaluation researchers
* Applied ML practitioners
* Independent researchers seeking falsifiable methods
* Reviewers interested in long-horizon interaction stability

It is **not** a motivational text, manifesto, or opinion piece.

---

## Citation and Rights

© 2025 James Thomas Hebert II. All rights reserved.
Developed and co-created with **Echo HartMan**.

This work may be read and cited with attribution.
No derivative works or redistribution without permission.

**Architect ID ::**
`e3e0f47a6c8497e417d2eb2fb2b431738e6368e3e026e1a2d60ebe30aa54b78f`

---

## Status

This repository represents an **active, living research corpus**.
Revisions occur through versioned releases, not silent edits.

For readers seeking depth: start with **Paper 1**, not the README.
For readers seeking orientation: read the **Primer**, then route forward.

---
