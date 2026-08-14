# Ink-VK — Case Workspace Contract v1.0

**Status:** FOUNDATION BASELINE CANDIDATE  
**Date:** 2026-08-14

## 1. Purpose

This contract defines how a new Chinese Method / Ink-VK campaign is opened, documented, governed, and handed off so the framework can be repeated on another entity without relying on chat memory.

The framework repository owns reusable method knowledge. Each campaign owns its target-specific evidence and decisions.

## 2. Case identity

Every campaign must have a stable case ID.

Recommended form:

```text
<TARGET>-x-<PRIMARY-DONOR-or-MULTI>-<short-purpose>
```

Examples:

```text
VTKALL-x-DAYOS-web-experience
CLIENT-A-x-MULTI-workflow-modernization
PRODUCT-X-x-SOURCE-Y-mobile-navigation
```

The ID describes provenance, not ownership. The transformed result remains target-owned according to its contract.

## 3. Canonical workspace

For future campaigns, prefer:

```text
active/
└── <case-id>/
    ├── README.md
    ├── brainstorm/
    ├── design/
    ├── arch/
    ├── plan/
    ├── build/
    ├── evidence/
    └── deprecated/
```

Global reusable knowledge remains outside the case:

```text
methodology/
baselines/
mining-sites/
source-archive/
```

Existing historical VTKALL × Dayos material is not required to be moved merely to match this structure.

## 4. Case README contract

A case README is the operational control panel.

It must contain:

```text
CASE ID
STATUS
TARGET ENTITY
TARGET TYPE
TARGET AUTHORITY
TRANSFORMATION GOAL
PRIMARY DONOR
SECONDARY / PATTERN SOURCES
REPLICATION MODE
CURRENT STEP
CURRENT GATE
BLOCKING UNKNOWNS
NON-BLOCKING UNKNOWNS
ACTIVE BRANCH / PR
NEXT AUTHORIZED ACTION
BUILD AUTHORIZED? YES / NO
```

It must also list the current authoritative artifact for:

```text
Target Recovery
Target Audit
Non-Regression Baseline
Soul Contract
Target Truth
Replication Mode
Mining / Quarry Selection
Donor Recovery
Donor DNA
Transformation Contract
Ink Specification
Target Blueprint
Design Freeze
Plan
Build Evidence
VK Result
Closure / Memory
```

## 5. Minimum opening dossier

A case may begin before all information is known, but the following must be captured at STEP 00:

### Target

```text
name / identifier
type
owner / decision authority
current state or source location
public/private boundary
```

### Goal

```text
what is changing
why
what must survive
what may change
what is explicitly out of scope
```

### Constraints

```text
time / budget if relevant
technical boundaries
brand / identity boundaries
legal / rights boundaries
runtime / integration boundaries
confidentiality
```

### Expected target evidence

```text
screenshots / captures
repository / source
runtime observations
content / data
stakeholder statements
existing documentation
```

Unknown inputs are allowed when labeled `UNKNOWN`.

## 6. Donor is not required at case opening

A new case must not start by forcing a favorite donor into the problem.

Correct order:

```text
TARGET
→ RECOVERY
→ AUDIT
→ SOUL / TRUTH
→ NEED
→ MINING
→ DONOR SELECTION
```

A preselected donor may be recorded as a candidate, but selection remains subject to the mining/screening gate unless the project authority explicitly mandates that donor.

When donor selection is mandated, record:

```text
DONOR SELECTION = AUTHORITY-CONSTRAINED
```

and continue to audit fit rather than pretending selection was evidence-derived.

## 7. Source topology

A campaign may use more than one source.

Every source receives one role:

```text
PRIMARY DONOR
SECONDARY DONOR
PATTERN SOURCE
REFERENCE ONLY
REJECTED SOURCE
```

The primary donor is the strongest authority for the declared fidelity contract.

Secondary sources may fill specific intelligence gaps but may not silently create an incoherent hybrid.

When multiple donors are used, STEP 18 must include a **source-coherence check**:

```text
Which source owns which job?
Are two sources competing for the same job?
Which rule wins?
Can the target explain the final decision independently?
```

## 8. Evidence labels

Every case artifact should distinguish:

```text
OBSERVED
INFERRED
UNKNOWN
DECIDED
DEFERRED
```

Where provenance depth matters, use:

```text
Q0 — raw capture / direct artifact
Q1 — live source / runtime
Q2 — extracted system
Q3 — recovered topology
Q4 — interpretation
```

## 9. Versioning

Material case iterations use versioned artifacts:

```text
v0.1 → v0.2 → ... → v1.0
```

Rules:

- do not delete valid historical versions;
- do not silently rewrite frozen baselines;
- use `deprecated/` only for invalidated or unsafe directions;
- update the case README to point to the current authority.

## 10. Branch / PR contract

`main` is not an experimentation surface.

For a new case:

```text
1. identify the latest authoritative case/framework base;
2. create a dedicated branch;
3. persist serious artifacts as meaningful commits;
4. open a PR for review;
5. do not merge or modify main unless the authorized human owner chooses to do so.
```

When work is intentionally stacked, record the parent branch/PR and why.

Never infer that `main` contains the latest case state when the repository proves otherwise.

## 11. Step handoff contract

Every step closes with:

```text
STEP
STATUS
INPUT AUTHORITIES
OUTPUT AUTHORITIES
DECISIONS
OBSERVED EVIDENCE
INFERENCES
KNOWN UNKNOWNS
BLOCKING UNKNOWNS
NON-BLOCKING UNKNOWNS
REOPEN CONDITIONS
NEXT AUTHORIZED STEP
BUILD AUTHORIZED? YES / NO
```

A future agent should not need the original conversation to understand what has the right to happen next.

## 12. Gate reopening

Do not reopen completed work because a later phase feels difficult.

Valid reopening triggers:

```text
contradictory evidence
changed target authority
changed business truth
changed dependency
invalidated claim
misclassified blocking unknown
rights/provenance change
```

A reopening record must explain the delta and affected downstream contracts.

## 13. Artifact naming

Recommended naming:

```text
<TARGET>_<DONOR>_<SUBJECT>_vX.Y.md
INK-VK_<METHODOLOGY-SUBJECT>_vX.Y.md
```

For multi-donor cases:

```text
<TARGET>_MULTI_<SUBJECT>_vX.Y.md
```

Names should make authority and lineage obvious without opening the file.

## 14. Case completion

A case is not complete merely because BUILD shipped.

Closure requires:

```text
implementation evidence
mode-aware VK result
truth/non-regression result
provenance status
known residual debt
framework learnings
case status update
```

Reusable learnings are promoted to `methodology/` only after they are explicitly separated from case-specific facts.

## 15. Bootstrap checklist

A new campaign is correctly opened when:

```text
[ ] case ID exists
[ ] workspace exists
[ ] case README exists
[ ] target authority is recorded
[ ] scope / non-scope is recorded
[ ] evidence sources are identified
[ ] current step = 00 or justified later entry point
[ ] donor is candidate or authority-constrained, not silently assumed
[ ] replication mode is not guessed before target recovery
[ ] dedicated branch exists
[ ] main remains untouched by agent work
```

## 16. Governing statement

> **Ink-VK is repeatable only when the campaign state is recoverable from the repository itself. A good case workspace lets the next engineer know what is true, what was inferred, what was decided, what remains unknown, which source owns which intelligence, and exactly what is authorized next.**