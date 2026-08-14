# Ink-VK — Donor Job Decomposition Gate v0.1

**Status:** PROPOSED / CROSS-CASE CANDIDATE  
**Date:** 2026-08-14  
**Origin case:** VTKALL Method × Dayos Plans

---

## 1. Why this gate exists

A donor page is often not one information job.

It may combine:

```text
commercial decision
comparison
proof
process
FAQ
conversion
trust
navigation
```

A dangerous migration treats the donor page as an indivisible template:

```text
DONOR PAGE MATCHES TARGET GENERALLY
        ↓
COPY THE WHOLE PAGE MODE
        ↓
UNSUPPORTED TARGET JOBS ENTER SILENTLY
```

The correct Ink-VK behavior is:

> **Decompose the donor page into independent information/interaction jobs before deciding what transfers.**

---

## 2. Governing rule

Never approve a whole donor page because one part maps well.

Use:

```text
DONOR PAGE
↓
JOB DECOMPOSITION
↓
TARGET JOB MATCH PER UNIT
↓
TRUTH CHECK
↓
CAPACITY CHECK
↓
NON-REGRESSION CHECK
↓
TRANSFER / REFRAME / OMIT / DEFER
```

This is especially important for R2/R3, where structural resemblance can otherwise hide semantic overreach.

---

## 3. Job types

Useful working classes:

```text
J1 — ORIENTATION
hero / route identity / local route choices

J2 — DECISION
choose between plans, options, paths, states

J3 — COMPARISON
peer columns, matrices, highlighted winner

J4 — PROOF
metrics, benefits, evidence, logos, outcomes

J5 — PROCESS
ordered sequence / temporal progression

J6 — TRUST / RISK
security, guarantees, policies, limitations

J7 — EDUCATION / FAQ
questions, objections, explanations

J8 — CONVERSION
CTA / form / next action

J9 — NAVIGATION / DISCLOSURE
rail, tabs, filters, dropdowns, pagination
```

These are job labels, not mandatory page sections.

---

## 4. Donor job record

For each recovered donor job record:

```text
JOB ID
DONOR SECTION / STATE
JOB TYPE
USER DECISION OR NEED SERVED
DONOR CONTENT DEPENDENCY
DONOR INTERACTION DEPENDENCY
TARGET EQUIVALENT JOB
TARGET EVIDENCE CLASS
TARGET CAPACITY
CLAIM CEILING
NON-REGRESSION OBLIGATION
DISPOSITION
CONFIDENCE
UNKNOWN
```

---

## 5. Job disposition

Each donor job resolves independently to:

```text
TRANSFER
REFRAME
OMIT
DEFER
```

### TRANSFER

Target has the same real job and enough truth/capacity to support it.

### REFRAME

The donor job is useful, but target meaning differs.

### OMIT

No target-side job/evidence currently exists.

### DEFER

A target job is plausible but current evidence is insufficient.

---

## 6. Partial page transposition

A donor page may legitimately produce:

```text
TRANSFER 30%
REFRAME 20%
OMIT 40%
DEFER 10%
```

and still be the correct donor.

High R3 fidelity does not require semantic completeness against every donor block.

The parity target becomes:

> **High fidelity for admitted jobs, zero fabrication for rejected jobs.**

---

## 7. Case example — Dayos Plans

Recovered donor jobs:

```text
A. BLACK COMMERCIAL OPENER
B. LOCAL ROUTE CHOICES
C. THREE PRICING / PLAN COLUMNS
D. HIGHLIGHTED MIDDLE PLAN
E. BENEFIT / PROOF STRIP
F. ROUNDED TRANSITION
G. CONNECTED PROCESS
   DIAGNOSE → SCOPE → BUILD → SHIP
H. FAQ
I. CLOSING CTA
```

VertikALL Method truth currently supports:

```text
route identity
five-step process
process order
start-flow CTA
solution-pattern CTA
```

It does not support:

```text
pricing
plan tiers
recommended plan
fixed proof metrics
formal FAQ
fixed delivery promise
```

Therefore job-level disposition can be:

```text
A → REFRAME
B → OMIT / DEFER
C → OMIT
D → OMIT
E → REFRAME only if supported target principles are used; otherwise OMIT
F → TRANSFER
G → TRANSFER HIGH FIDELITY
H → DEFER
I → TRANSFER / REFRAME
```

The entire Dayos Plans page is not copied as a commercial page.

Its strongest transferable job is the process system.

---

## 8. Composite-page anti-smuggling rule

A strong donor match in one dimension must not smuggle adjacent unsupported jobs.

Examples:

```text
PROCESS MATCH
≠ PRICING AUTHORIZATION

LIBRARY MATCH
≠ FILTER AUTHORIZATION

COMPANY STORY MATCH
≠ PARTNER LOGO AUTHORIZATION

FORM MATCH
≠ BACKEND SUBMISSION AUTHORIZATION
```

This rule complements:

```text
Target Truth Gate
Content Capacity Gate
Target Non-Regression Gate
```

---

## 9. Geometry can transfer when content cannot

A donor section may contain reusable visual/interaction geometry even when its semantic content is rejected.

Example:

```text
THREE PRICING COLUMNS
```

If VertikALL has no three comparable options, the three-column decision geometry must not be retained merely as decorative shells.

But the donor's broader spatial lessons may still inform other valid sections:

```text
peer alignment
strong selected-state contrast
wide-field usage
clear separation
```

Only the generic principle transfers, not the unsupported component instance.

---

## 10. Process-specific rule

A connected process device requires:

```text
ORDERED TARGET STATES
+
ORDER EVIDENCE
```

If both exist:

```text
CONNECTED SEQUENCE → ELIGIBLE
```

If order is inferred only because the donor has arrows:

```text
CONNECTED SEQUENCE → NOT ELIGIBLE
```

This distinguishes the Method case from the earlier Demonstrations case.

### Method

Target explicitly defines Step 1 → Step 5.

Connected process geometry is justified.

### Demonstrations

Several capabilities exist, but one canonical end-to-end order was not frozen.

Connected sequence remained deferred.

---

## 11. Proof-strip rule

A donor benefit/proof strip must be decomposed into:

```text
VISUAL EMPHASIS JOB
+
ACTUAL CLAIM CONTENT
```

The visual emphasis can transfer only if there is truthful target content worth emphasizing.

Allowed target substitutions may include:

```text
approved principle
verified status
verified capability
verified metric
```

Do not replace a donor metric with an invented target percentage to preserve visual density.

---

## 12. FAQ rule

FAQ is not neutral filler.

A FAQ implies:

```text
known recurring questions
+
approved answers
```

If neither is evidenced:

```text
FAQ → DEFER / OMIT
```

Do not generate speculative objections and policy answers simply because the donor has an FAQ.

---

## 13. Local navigation rule

Local route choices, tabs, rails, or anchors require real destinations/states.

```text
DONOR LOCAL ROUTE CHOICES
+
TARGET HAS ONE LINEAR METHOD
→ OMIT / REDUCE
```

Interaction parity remains conditional on state existence.

---

## 14. Blueprint implication

Before a blueprint adopts a donor page family, include a `DONOR JOB LEDGER`:

| Donor job | Target job | Truth | Capacity | Non-regression | Disposition |
|---|---|---|---|---|---|
| ... | ... | ... | ... | ... | ... |

The blueprint may only render jobs marked `TRANSFER` or `REFRAME`.

`DEFER` may remain in future-safe architecture but not as fake-present UI.

---

## 15. Framework status

```text
DONOR JOB DECOMPOSITION GATE   ✅ v0.1
CASE VALIDATION                ✅ VTKALL Method × Dayos Plans
CROSS-CASE VALIDATION          ◉ CANDIDATE
FOUNDATION FREEZE              ⛔ NOT YET
```

**Canonical shorthand:**

> **Match donor jobs, not donor pages as indivisible blocks.**
