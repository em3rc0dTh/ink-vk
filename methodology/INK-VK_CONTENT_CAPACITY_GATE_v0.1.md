# Ink-VK — Content Capacity Gate v0.1

**Status:** PROPOSED / CROSS-CASE CANDIDATE  
**Date:** 2026-08-14  
**Origin case:** VTKALL Demonstrations × Dayos Use Cases

---

## 1. Why this gate exists

Donors often have more content, more records, more proof, more product depth, or more states than the target.

A common migration failure is:

```text
DONOR HAS DENSE LIBRARY
      ↓
TARGET HAS FEW RECORDS
      ↓
TEAM PRESERVES DONOR DENSITY BY INVENTING PLACEHOLDERS
```

or:

```text
DONOR HAS FILTERS / PAGINATION / TABS
      ↓
TARGET DOES NOT HAVE ENOUGH VARIATION
      ↓
INTERACTIONS EXIST WITHOUT A REAL USER JOB
```

Ink-VK needs a separate concept for this.

The governing rule is:

> **Preserve the donor information job; scale the donor mechanism to the amount and diversity of target evidence actually available.**

This is **cardinality-aware fidelity**.

---

## 2. Capacity is not truth

Target Truth answers:

> Is this content real and supported?

Content Capacity answers:

> Is there enough supported content to justify this donor structure or interaction?

Example:

```text
Turagua Racing / MecánicaPro demonstration = TRUE
```

but:

```text
one demonstration
≠ enough variation to justify a rich filter rail
```

Therefore a target can pass Truth and still fail Capacity for a specific donor mechanism.

---

## 3. Capacity dimensions

For each donor-derived information structure, inspect:

```text
RECORD COUNT
CONTENT DEPTH PER RECORD
VARIABILITY BETWEEN RECORDS
AVAILABLE CLASSIFICATION DIMENSIONS
PROOF DEPTH
STATE DEPTH
INTERACTION NEED
FUTURE EXPANSION EXPECTATION
```

Do not reduce Capacity to record count alone.

Two records can justify comparison if they genuinely differ.

Ten near-identical records may not justify five filters.

---

## 4. Content-capacity states

Use semantic states rather than arbitrary numeric thresholds.

### C0 — NO SUPPORTED CONTENT

```text
No target record exists for the donor slot.
```

Allowed:

```text
OMIT
DEFER
```

Not allowed:

```text
placeholder fake records
```

---

### C1 — SINGLE RECORD / SINGLE STATE

One supported target record exists.

Valid structures may include:

```text
featured record
single evidence surface
single detail experience
```

Usually unjustified:

```text
filters
pagination
carousel solely to show one item
comparison controls
category switching with no alternative
```

---

### C2 — PEER SET

Multiple supported records exist and the user can meaningfully browse or compare them.

Possible structures:

```text
peer cards
grid
carousel
simple category grouping
```

Filters are still not automatic.

---

### C3 — CLASSIFIABLE LIBRARY

The target has enough real diversity for stable classification dimensions.

Possible structures:

```text
filters
facets
search
dense inventory
category navigation
```

The classification must reflect real target attributes.

---

### C4 — DEEP MULTI-STATE SYSTEM

The target has enough records and internal depth to justify advanced donor interactions such as:

```text
multi-axis filters
comparison
saved state
pagination
rich preview/detail transitions
```

This state requires evidence, not ambition.

---

## 5. Mechanism activation rule

Every donor interaction must have a target-side activation condition.

Examples:

```text
FILTER
requires meaningful variation along the filter dimension

CAROUSEL
requires a peer set whose browsing job benefits from sequential exposure

PAGINATION
requires inventory size or performance constraints that make paging useful

TABS
require distinct target states/categories

COMPARISON
requires multiple supported peers and a legitimate comparison job
```

Do not create the interaction first and search for data later.

---

## 6. Future-safe is different from fake-present

Ink-VK may design an architecture that can scale later.

Example:

```text
Demonstrations record schema supports many records
```

while current UI truth is:

```text
one record only
```

Allowed:

```text
component/system designed to expand later
```

Not allowed:

```text
render fake cards to make the future architecture visible today
```

The rule is:

> **Design for future capacity; render current truth.**

---

## 7. Sparse-state equivalence

High-fidelity R2/R3 work may encounter a donor dense mode that the target cannot populate yet.

The target should seek a **sparse-state equivalent**.

A sparse-state equivalent preserves:

```text
information job
visual grammar
surface hierarchy
interaction confidence
entry / closure rhythm
record semantics
```

while reducing mechanisms whose only purpose is handling greater volume.

Example:

```text
DAYOS USE CASES
black library opener
→ rounded handoff
→ filter rail
→ dense two-column inventory
```

with one target record may become:

```text
black evidence-library opener
→ rounded handoff
→ featured demonstration surface
→ structured evidence detail
```

without fake filter controls.

---

## 8. Density fidelity vs. cardinality fidelity

Do not confuse:

```text
DONOR FEELS DENSE
```

with:

```text
TARGET MUST HAVE THE SAME NUMBER OF ITEMS
```

Fidelity may preserve:

```text
compact scanning rhythm
repeatable card grammar
content hierarchy
visual distinction between record and metadata
```

without preserving literal item count.

This is especially important for:

```text
libraries
marketplaces
case-study grids
customer-logo walls
pricing tiers
integration catalogs
teams
portfolios
FAQs
```

---

## 9. Filter validity test

Before adding a filter, record:

```text
FILTER DIMENSION
SUPPORTED VALUES
NUMBER OF ACTUAL DISTINCT VALUES
USER DECISION HELPED
EMPTY / SINGLE-VALUE STATES
```

A filter fails if it merely reproduces donor chrome.

Examples:

```text
Industry filter with only AUTO SERVICES
→ invalid now

Status filter with only DEMONSTRATION
→ invalid now
```

The presence of a field in the record schema does not automatically justify a filter control.

---

## 10. Reusable content-capacity matrix

For each donor structure:

| Field | Meaning |
|---|---|
| Donor mechanism | filter, grid, carousel, tabs, etc. |
| Donor information job | discovery, comparison, orientation, etc. |
| Target records | supported current records |
| Target variability | meaningful differences between records |
| Capacity state | C0–C4 |
| Decision | MATCH / REDUCE / REFRAME / OMIT / DEFER |
| Future-safe requirement | what should scale later |
| Current-render rule | what may appear now |

---

## 11. Relationship to other Ink-VK gates

### Target Truth Gate

Prevents invented facts.

### Target Non-Regression Gate

Prevents old target UX defects from returning.

### Content Capacity Gate

Prevents donor volume/interaction assumptions from being transplanted into a target that cannot support them.

Together:

```text
IS IT TRUE?
↓
IS THERE ENOUGH REAL CONTENT FOR THIS MECHANISM?
↓
WILL THE TRANSFORMATION AVOID KNOWN UX FAILURES?
```

---

## 12. VTKALL × Dayos validation

Dayos Use Cases currently represents a `C3 — CLASSIFIABLE LIBRARY` donor mode:

```text
filter rail
many records
dense two-column inventory
```

Current VertikALL Demonstrations is:

```text
C1 — SINGLE RECORD / SINGLE STATE
```

with:

```text
Turagua Racing / MecánicaPro
```

Therefore the correct transfer is:

```text
LIBRARY IDENTITY / RECORD GRAMMAR     → MATCH / ADAPT
FILTER RAIL                           → OMIT NOW
DENSE TWO-COLUMN MULTI-RECORD GRID    → REDUCE TO SPARSE-STATE EQUIVALENT
REPEATABLE RECORD SCHEMA              → KEEP FUTURE-SAFE
FAKE EXTRA RECORDS                    → FORBIDDEN
```

---

# Status

```text
CONTENT CAPACITY GATE      ✅ DEFINED v0.1
VALIDATED BY               VTKALL × DAYOS DEMONSTRATIONS
CROSS-CASE STATUS          CANDIDATE
FOUNDATION FREEZE          ⛔ NOT YET
```

**Key phrase:** `Design for future capacity; render current truth.`
