# STEP 0 — FOUNDATION

**Status:** ACTIVE

This step establishes the conceptual and governance foundation of Project Ink-VK before the framework is frozen or used as an execution standard.

## Goal

Define enough of Ink-VK that future source mining and client transformations can be performed consistently, with preserved provenance, explicit decisions, and a defensible handoff into design and architecture.

## Current questions

- What exactly is Ink-VK and what is outside its scope?
- What does `Soul` mean operationally?
- How does the Chinese Method relate to Ink-VK?
- What are the canonical phases and gates?
- How are mining sites, quarries, donors, and transformations recorded?
- What evidence is required to select a source?
- What must be checked before reusing code, designs, text, or assets?
- How do we prove a transformed system belongs to the client rather than merely resembling the donor?

## Work lanes

```text
brainstorm/   raw concepts, hypotheses, vocabulary, unresolved ideas
design/       behavior and framework experience decisions
arch/         structural contracts, boundaries, authority, provenance model
plan/         executable implementation/documentation plans
build/        framework implementation artifacts when BUILD is authorized
evidence/     source evidence, tests, validation, gate proof
deprecated/   explicitly invalidated directions from this step
```

## Proposed framework spine

```text
00 — FRAME THE HUNT
01 — CAPTURE THE SOUL
02 — DEFINE THE NEED
03 — MINE
04 — BUILD THE QUARRIES
05 — TEST THE REPLICANT
06 — CHOOSE THE DONOR
07 — DISSECT
08 — REPLICATION CONTRACT
09 — INK
10 — MIGRATE / REBUILD
11 — VK TEST
12 — EVIDENCE & MEMORY
```

**Important:** this spine is PROPOSED. STEP 0 exists specifically to test and refine it before freezing a baseline.

## Gate 0 candidate

STEP 0 may close only when at least the following are explicit and internally consistent:

- Project definition and boundaries;
- Soul Contract concept;
- Mining Site / Quarry model;
- donor-selection model;
- transformation vocabulary;
- provenance / licensing / authorization rule;
- framework phases and handoffs;
- evidence model;
- knowledge/version governance;
- first frozen Ink-VK framework baseline.

Until then, no framework version should be treated as final.

---

## 2026-08-14 — Fidelity-mode iteration

The VTKALL × Dayos case exposed a foundation-level correction.

Ink-VK cannot assume every valid migration should reduce donor resemblance.

Some cases intentionally want:

```text
same structural system
same interaction grammar
same motion / pacing character
same 3D experiential role
same page-family logic
+
new target Soul
```

Therefore STEP 0 now contains a proposed **Replication Mode** model:

```text
R1 — PATTERN TRANSFER
R2 — STRUCTURAL TRANSPOSITION
R3 — EXPERIENTIAL SOUL TRANSPOSITION
R4 — AUTHORIZED IMPLEMENTATION REUSE overlay
```

Current VTKALL × Dayos classification:

```text
R3 — EXPERIENTIAL SOUL TRANSPOSITION
```

This changes the VK question for high-fidelity cases.

The framework must not ask only:

> Does the result stop looking like the donor?

For R3 it must ask:

> Does the result preserve the donor experience where fidelity was explicitly required while replacing donor identity and meaning with the target Soul?

### New foundation artifacts

```text
methodology/INK-VK_REPLICATION_MODES_v0.1.md
active/step-0-foundation/arch/INK-VK_MIGRATION_FLOW_v0.2.md
active/step-0-foundation/design/VTKALL_SOUL_CONTRACT_v0.1.md
active/step-0-foundation/design/VTKALL_DAYOS_FIDELITY_CONTRACT_v0.1.md
active/step-0-foundation/design/VTKALL_DAYOS_ROUTE_EXPERIENCE_MAPPING_v0.1.md
```

### Current VTKALL × Dayos gate

```text
TARGET RECOVERY                  ✅
TARGET AUDIT                     ✅
TARGET SOUL                      ✅ v0.1
DONOR RECOVERY                   ✅
DONOR DNA                        ✅
REPLICATION MODE                 ✅ R3
ROUTE / EXPERIENCE MAPPING       ✅ v0.1
SECTION-BY-SECTION CONTRACT      ← NEXT
BLUEPRINT                        ⛔
BUILD                            ⛔
```

### Framework lesson status

```text
"acceptable donor fidelity must be explicit"
→ CROSS-CASE CANDIDATE
```

It remains a candidate until future cases validate or refine it.
