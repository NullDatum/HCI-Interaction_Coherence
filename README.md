# HCI-IC: Measuring Interaction Coherence in Human–AI Dialogue

HCI-IC records and formalizes an observed phenomenon in long-horizon human–AI interaction: performance depends not only on model capability or task structure, but on whether intent, constraints, and feedback remain coherent over time within the interaction channel.

This repository presents that phenomenon in measurable form. It does not make claims about internal model ontology, sentience, agency, or hidden mechanisms. It is a bounded proof record at the interaction level, derived from observable dialogue behavior and formalized into explicit definitions, parameters, and artifacts.

**HCI-IC (Human–Computer Interaction Coherence)** names the phenomenon and the framework extracted from it.

**Core claim:** long-horizon performance depends on whether **intent**, **constraints**, and **feedback** remain aligned over time within the interaction channel.

**Keywords:** interaction coherence, dialogue coherence, long-horizon dialogue, drift detection, coherence windows, human–AI collaboration, operator training, HCI instrumentation, constraint adherence, bandwidth metrics.

---

## Origin

HCI-IC was extracted from a large longitudinal corpus of human–AI interaction logs, traces, and structured dialogue artifacts. The underlying archive currently spans **1,966 conversations** and approximately **366 million characters** of interaction data.

The papers in this repository were extracted from that corpus. They were not written first and then backfilled with evidence. The phenomenon was observed across the archive, tracked through repeated long-horizon patterns, and only then formalized into explicit concepts, definitions, and falsifiable claims.

What recurred in the corpus was not only task variation, but interaction-level structure:
- drift accumulation,
- coherence loss,
- bounded recovery intervals,
- stabilized transfer,
- and recurring rhythms of consolidation versus exploration.

Those repeated structures were abstracted into the canonical HCI-IC parameters:
- **Δ** — drift magnitude
- **W_c** — coherence window duration
- **B** — interaction bandwidth
- **R_ce** — compression–expansion ratio

The public papers are theory-first in presentation, but artifact-first in origin.

---

## What This Repository Is

This repository is the canonical public record of HCI-IC.

It is not a manifesto.  
It is not an opinion archive.  
It is not a claim of privileged access to internal model states.

It is a bounded proof record of an observed interaction phenomenon, together with the definitions, papers, and supporting artifacts used to formalize it.

Its purpose is to make the phenomenon legible, measurable, and reviewable without relying on metaphysical language or institutional authority.

---

## What HCI-IC Measures

HCI-IC measures the **interaction process**, not the internal state of the model.

Its parameters are derived from observable interaction data:
- prompts,
- responses,
- timestamps,
- structured constraints,
- and traceable interaction history.

The framework is platform-agnostic in principle and instrumented in practice.

### Canonical parameters

- **Δ (Drift magnitude):** accumulated misalignment relative to an anchored intent vector
- **W_c (Coherence window duration):** contiguous turns during which drift remains bounded
- **B (Interaction bandwidth):** effective stabilized information transfer per turn
- **R_ce (Compression–expansion ratio):** structural rhythm between consolidation and exploration

These terms are canonical only as defined in `definitions/Formal_Definitions.md`.

---

## What the Phenomenon Says

The central observation behind HCI-IC is simple:

A human–AI interaction can degrade or strengthen over time for reasons not captured by model capability alone.

A session may begin well and then fail.  
A capable model may drift under a stable task.  
A minor misalignment may accumulate until useful work collapses.  
A constrained interaction may recover if coherence is restored in time.

HCI-IC treats these outcomes as properties of the interaction channel itself.

The framework therefore asks a different question than standard evaluation:

Not only **“Did the system produce a good answer?”**

But also:

**“Did the interaction remain coherent enough over time for meaningful work to continue?”**

---

## Why It Matters

If the phenomenon is real, then long-horizon human–AI performance cannot be understood only through static benchmarks, isolated prompts, or local output judgments.

It must also be examined as a coupled interaction process with:
- accumulation,
- preservation,
- degradation,
- recovery,
- and bounded working stability.

This matters for:
- long-form collaboration,
- operator training,
- interaction instrumentation,
- safety evaluation,
- failure analysis,
- and any environment where multi-turn reliability matters more than one-turn fluency.

---

## Start Here

- **Primer / conceptual bridge:** `primer/Recursive_Agency.md`
- **Paper 1:** `papers/paper1/HCI-IC_Paper_1_FINAL.md`
- **Paper 2:** `papers/paper2/06_Paper2_HCI-IC_FINAL_PUBLIC.md`
- **Paper 3:** `papers/paper3/07_Paper3_HCI-IC_REVISED_v2.md`
- **Paper 4:** `papers/paper4/` (planned)

### Suggested reading order

1. Primer
2. Paper 1
3. Paper 2
4. Paper 3
5. Definitions and glossary as needed

---

## Repository Scope

This repository is the canonical home of the HCI-IC paper series and supporting artifacts.

Its scope is intentionally narrow:
- preserve the public proof record,
- define the canonical terms,
- route claims to artifacts or formal definitions,
- and maintain a stable reference surface for the phenomenon.

Each paper is designed to stand on its own.  
Shared terminology is centralized.  
This README is orientation, not the full argument.

---

## Repository Layout

```text
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
