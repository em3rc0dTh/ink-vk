# Ink-VK — Migration Flow v0.4

**Status:** PROPOSED / FOUNDATION ITERATION  
**Date:** 2026-08-14  
**Supersedes conceptually:** `INK-VK_MIGRATION_FLOW_v0.3.md`; previous versions remain preserved.  
**New learning source:** VTKALL Solutions × Dayos

---

# 1. Why v0.4 exists

v0.3 added the Target Truth Baseline and stopped donor slots from manufacturing target facts.

The Solutions pass exposed a second independent risk:

```text
TARGET AUDIT FINDS A DEFECT
      ↓
DONOR-LED REDESIGN BEGINS
      ↓
OLD IMPLEMENTATION IS REPLACED
      ↓
DEFECT KNOWLEDGE IS FORGOTTEN
      ↓
NEW BUILD RECREATES THE SAME FAILURE
```

Examples from VTKALL Solutions include:

```text
headline / visual collision
content clipping
unresolved next-section leakage
unjustified empty fields
five cards compressed into unreadable widths
CTA + footer + previous section collapse
```

The target audit also contained a positive control where composition and whitespace were acceptable.

Therefore v0.4 promotes audit findings into a formal **Target Non-Regression Baseline**.

Governing rule:

> **Donor fidelity may replace the target expression, but it may not silently reintroduce a known target defect.**

---

# 2. Canonical working flow v0.4

```text
00 — FRAME THE MIGRATION
      ↓
01 — RECOVER TARGET
      ↓
02 — AUDIT TARGET
      ↓
03 — FREEZE TARGET NON-REGRESSION BASELINE
      ↓
04 — EXTRACT TARGET SOUL
      ↓
05 — FREEZE TARGET TRUTH BASELINE
      ↓
06 — SELECT REPLICATION MODE
      ↓
07 — DEFINE TRANSFORMATION NEED
      ↓
08 — MINE
      ↓
09 — BUILD QUARRIES / SCREEN DONORS
      ↓
10 — RECOVER SELECTED DONOR
      ↓
11 — DISSECT DONOR SYSTEM
      ↓
12 — EXTRACT DNA + FIDELITY DIMENSIONS
      ↓
13 — MAP TARGET × DONOR × SOUL
      ↓
14 — RUN ROUTE / SLOT TARGET-TRUTH GATE
      ↓
15 — APPLY TARGET NON-REGRESSION OBLIGATIONS
      ↓
16 — FREEZE FIDELITY / TRANSFORMATION CONTRACT
      ↓
17 — APPLY INK
      ↓
18 — DESIGN TARGET BLUEPRINT
      ↓
19 — PLAN MIGRATION
      ↓
20 — BUILD / MIGRATE
      ↓
21 — DONOR PARITY TEST
      ↓
22 — SOUL INTEGRITY TEST
      ↓
23 — TARGET TRUTH / CLAIM TEST
      ↓
24 — TARGET NON-REGRESSION TEST
      ↓
25 — MODE-AWARE VK TEST
      ↓
26 — EVIDENCE & MEMORY
```

---

# 3. STEP 03 — Freeze Target Non-Regression Baseline

The target audit must produce more than a list of observations.

Extract:

```text
KNOWN DEFECTS
+
POSITIVE CONTROLS
```

For each record:

```text
ID
ROUTE / STATE
SOURCE EVIDENCE
CLASS
OBSERVED CONDITION
FAILURE / SUCCESS SIGNATURE
DESIGN INVARIANT
DONOR COLLISION RISK
VALIDATION NEED
```

Output:

```text
TARGET NON-REGRESSION BASELINE
```

This baseline is separate from Soul and Truth.

---

# 4. Why Soul, Truth, and Non-Regression are different

### Soul

Answers:

> What must still belong to the target?

Example:

```text
VertikALL = practical leverage without enterprise burden
```

### Truth

Answers:

> What is the target currently allowed to assert or present as real?

Example:

```text
Turagua/MecánicaPro = demonstration, not production success proof
```

### Non-Regression

Answers:

> Which already-observed UX failures must not return, and which successful qualities must survive?

Example:

```text
five industry cards must not be compressed until text clips
```

A page can pass two of these and fail the third.

---

# 5. STEP 13 — Target × Donor × Soul mapping v0.4

In addition to v0.3 fields, every route/section mapping now references relevant audit obligations:

```text
TARGET JOB
DONOR JOB
SOUL FIT
TARGET EVIDENCE CLASS
CLAIM CEILING
FIDELITY LEVEL
KNOWN TARGET DEFECTS
POSITIVE CONTROLS
DONOR COLLISION RISK
CONFIDENCE
```

This makes previous target UX evidence active during transformation.

---

# 6. STEP 15 — Apply Target Non-Regression Obligations

After truth-gating donor slots, apply the route's defect baseline.

For each relevant defect:

```text
DEFECT
↓
WHY THE DONOR MAPPING COULD RECREATE IT
↓
PREVENTION INVARIANT
↓
BLUEPRINT REQUIREMENT
↓
TEST REQUIREMENT
```

For each positive control:

```text
SUCCESS QUALITY
↓
WHAT MADE IT ACCEPTABLE
↓
QUALITY TO PRESERVE
```

Output:

```text
TARGET NON-REGRESSION CONTRACT
```

This may be embedded in a route contract when small enough.

---

# 7. Conditional donor fidelity

High fidelity does not mean copying uncertain donor geometry.

Example learned from Dayos Solutions:

```text
OBSERVED
Dense multi-column matrix uses width effectively.

UNKNOWN
Exact native card width, typography, spacing, breakpoint behavior
because evidence is reduced zoom.

TARGET KNOWN DEFECT
Five equal narrow cards previously clipped copy.
```

Correct decision:

```text
MATCH
information-density role
broad-field usage
peer scanability

DO NOT FREEZE YET
exact column count
exact card width
exact responsive behavior
```

Therefore:

> **Preserve verified donor behavior; do not use uncertainty as permission to recreate target defects.**

---

# 8. Controlled peeking rule v0.4

A prior target audit may mark next-section visibility as a failure while the donor intentionally exposes the next state.

Resolve with a conditional rule.

### Allowed

```text
current narrative resolved
+
explicit surface handoff
+
no clipped primary content
+
next state visually subordinate until entry
```

### Regression

```text
current state unresolved
+
next state competes
+
content clips
or
CTA/footer/current state collapse together
```

Thus Ink-VK protects the target insight without forbidding valid donor behavior.

---

# 9. Density rule v0.4

For card/matrix/library sections:

```text
ITEM COUNT
≠
COLUMN COUNT
```

The blueprint must choose a layout that satisfies:

```text
readability
content fit
peer comparison/discovery job
donor fidelity
responsive behavior
```

Allowed structural forms may include:

```text
multiple rows
fewer columns
horizontal browsing
progressive disclosure
responsive collapse
```

No universal card width belongs in framework methodology.

---

# 10. Whitespace rule v0.4

A target audit should not convert whitespace complaints into a simplistic `reduce spacing` command.

The rule is:

> **Large empty fields need a compositional job.**

Positive target controls are especially important here.

If a previous target state was accepted because whitespace felt balanced and content remained complete, that quality becomes an invariant even if the donor uses a different visual composition.

---

# 11. Route-closure rule v0.4

If an audit detected unresolved:

```text
previous content
+
closing CTA
+
footer
```

future blueprint must establish:

```text
CONTENT RESOLUTION
↓
ACTION STATE
↓
GLOBAL FOOTER STATE
```

The exact amount of visual overlap may vary, but semantic/visual resolution may not disappear.

---

# 12. STEP 18 — Blueprint admission v0.4

A route blueprint cannot enter migration planning until it can answer all five authorities:

```text
1. DONOR FIDELITY
What donor jobs/states are being matched?

2. TARGET SOUL
Why does this belong to the target?

3. TARGET TRUTH
What evidence supports every content-bearing slot?

4. TARGET NON-REGRESSION
What known defects are prevented and what positive controls survive?

5. UNKNOWN BOUNDARY
What donor/target behavior still cannot be safely specified?
```

If one authority is missing, blueprint is incomplete.

---

# 13. STEP 24 — Target Non-Regression Test

After BUILD, validate every baseline item.

Known defects:

```text
NOT PRESENT
PRESENT
NOT TESTED
NOT APPLICABLE
```

Positive controls:

```text
QUALITY PRESERVED
QUALITY LOST
NOT TESTED
NOT APPLICABLE
```

Output:

```text
TARGET NON-REGRESSION EVIDENCE
```

A donor-parity success does not override a regression failure.

---

# 14. Updated R3 validation stack

```text
DONOR PARITY TEST
      ↓
SOUL INTEGRITY TEST
      ↓
TARGET TRUTH / CLAIM TEST
      ↓
TARGET NON-REGRESSION TEST
      ↓
MODE-AWARE VK TEST
```

These answer different questions:

```text
PARITY
Did we reproduce the donor where promised?

SOUL
Does the result belong to the target?

TRUTH
Is every public claim within evidence?

NON-REGRESSION
Did we avoid recreating known target UX failures?

VK
Did the whole transformation satisfy the selected mode?
```

---

# 15. VTKALL Solutions case application

Baseline:

```text
DEFECT S01
hero component competition + clipping

DEFECT S02
unresolved next-section leakage + meaningless empty field

DEFECT S03
five cramped cards + clipped text

POSITIVE S04
no clipping + balanced justified whitespace

DEFECT S05
previous section + CTA + footer collapse
```

Donor evidence:

```text
black solution opener
rounded light handoff
dense matrix
proof state
dark mechanism/demo state
trust/deployment states
use-case path
```

v0.4 result:

```text
MATCH DONOR INFORMATION JOBS
+
TRUTH-GATE TARGET CONTENT
+
NON-REGRESSION-GATE COMPOSITION
```

not:

```text
COPY DONOR DENSITY
+
RECREATE OLD TARGET CROWDING
```

---

# 16. Current framework state

```text
REPLICATION MODE             ✅ CANDIDATE
TARGET TRUTH GATE            ✅ CANDIDATE
TARGET NON-REGRESSION GATE   ✅ NEW CANDIDATE
ROUTE ADMISSION              ✅ CANDIDATE
SECTION CONTRACT SCHEMA      ✅ CANDIDATE
MODE-AWARE VK                ✅ CANDIDATE
```

These remain pre-v1.0 until tested across additional migrations.

---

# 17. Canonical shorthand v0.4

```text
RECOVER WHAT EXISTS
AUDIT WHAT FAILS AND WHAT WORKS
FREEZE THE LESSONS
EXTRACT WHAT MUST SURVIVE
FREEZE WHAT IS TRUE
DECLARE DESIRED DONOR FIDELITY
RECOVER DONOR DEEPLY ENOUGH
MAP DONOR JOBS TO TARGET JOBS
REJECT SLOTS WITHOUT TARGET TRUTH
BLOCK KNOWN TARGET REGRESSIONS
INK THE SURVIVING SYSTEM
BLUEPRINT
PLAN
BUILD
TEST DONOR PARITY
TEST SOUL
TEST TRUTH
TEST NON-REGRESSION
VK
REMEMBER
```

That is the current strongest Ink-VK migration hypothesis after the VTKALL Solutions pass.
