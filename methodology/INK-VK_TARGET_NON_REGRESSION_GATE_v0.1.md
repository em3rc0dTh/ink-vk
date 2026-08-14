# Ink-VK — Target Non-Regression Gate v0.1

**Status:** PROPOSED / FOUNDATION CANDIDATE  
**Date:** 2026-08-14  
**Origin case:** VTKALL × Dayos — Solutions  
**Framework role:** prevent donor-led redesign from recreating known target defects

---

## 1. Why this gate exists

Target audit is not disposable research.

If a previous target version already exposed concrete failures, a migration is not allowed to recreate them merely because the donor uses a superficially similar composition.

The governing rule is:

> **Donor fidelity may replace the old implementation, but it may not silently reintroduce a known target defect.**

A second rule is equally important:

> **Known positive controls must be preserved as behavioral evidence, even when their visual expression changes.**

This creates a non-regression contract between:

```text
TARGET AUDIT
      ↓
TARGET BLUEPRINT
      ↓
BUILD
      ↓
VALIDATION
```

---

## 2. Two audit outputs must survive migration

A target audit should produce at least two classes of reusable evidence.

### A — KNOWN DEFECT

A directly observed failure or repeated negative pattern.

Examples:

```text
content clipping
overlap
unresolved section leakage
crowded content despite unused space
unjustified whitespace
CTA/footer collapse
interaction state confusion
```

### B — POSITIVE CONTROL

An observed target state that was explicitly acceptable or demonstrably behaved well.

Examples:

```text
content fully visible
balanced composition
whitespace with clear purpose
section self-contained enough to read coherently
no clipping
clear transition
```

Ink-VK must not preserve the pixels of a positive control.

It must preserve the **reason it was positive**.

---

## 3. Non-regression baseline schema

For every meaningful audit finding record:

```text
ID
ROUTE / STATE
SOURCE EVIDENCE
CLASS
    KNOWN DEFECT
    POSITIVE CONTROL
OBSERVED CONDITION
FAILURE / SUCCESS SIGNATURE
DESIGN INVARIANT
DONOR COLLISION RISK
BLUEPRINT OBLIGATION
VALIDATION METHOD
STATUS
```

The baseline should be frozen before blueprint work.

---

## 4. Known-defect rule

A known defect may be considered resolved only when the new design has an explicit invariant that prevents recurrence.

Example:

```text
DEFECT
Hero headline collides with secondary visual/card.

INVALID RESPONSE
"We changed the design."

VALID RESPONSE
The blueprint defines a dominant/secondary field relationship,
content priority, breakpoint behavior, and a no-overlap acceptance rule.
```

The exact implementation may differ.

The failure signature must not return.

---

## 5. Positive-control rule

Positive controls protect learned UX truth from being discarded during redesign.

Example:

```text
POSITIVE CONTROL
A section contained all primary content without clipping,
and the remaining whitespace felt intentional because the composition was balanced.

TRANSFERABLE INVARIANT
Whitespace is valid when it has compositional purpose and does not coexist with avoidable clipping/crowding.
```

The new page does not need to look like the old control.

It must preserve the quality that made it acceptable.

---

## 6. Controlled peeking vs. regression

A frequent donor pattern may intentionally reveal part of the next section.

That does not automatically violate a target audit that previously complained about section mixing.

Use this test:

### CONTROLLED PEEKING

Allowed when:

```text
current narrative unit has resolved
next section enters through an explicit handoff
visual hierarchy makes the state change legible
no primary content is clipped or unfinished
```

### ACCIDENTAL LEAKAGE

Regression when:

```text
current content is still unresolved
next section competes for attention
section boundary is visually ambiguous
content is clipped to make room
CTA/footer/current section collapse together
```

Therefore:

> **The non-regression invariant is not “never show the next section.” It is “never expose unresolved competing section states.”**

---

## 7. Whitespace rule

Target audit evidence may show both excessive whitespace and acceptable whitespace.

Do not translate the audit into:

```text
REDUCE WHITESPACE
```

The stronger invariant is:

```text
EVERY LARGE EMPTY FIELD MUST HAVE A COMPOSITIONAL JOB
```

Examples of valid jobs:

```text
visual anchor
3D/media field
reading focus
transition state
breathing room after resolved content
comparison separation
interaction affordance
```

Regression signal:

```text
large unused area
+
content cramped/clipped elsewhere
```

---

## 8. Density / card-fit rule

A donor may use a dense matrix.

The target must not reproduce density by shrinking cards until content becomes unreadable.

Required invariant:

> **Information count does not determine column count; readable content fit determines the layout mode.**

Valid transformations may include:

```text
fewer columns
wrapping
horizontal browsing
progressive disclosure
different card proportions
multiple rows
```

provided the donor's information job and target fidelity contract are still satisfied.

Do not infer exact donor card dimensions from reduced-zoom evidence.

---

## 9. Hero / secondary-field rule

When the target audit has previously shown headline/visual collision, any future split hero must define:

```text
dominant field
secondary field
minimum separation behavior
content priority
responsive reorder/collapse behavior
```

No blueprint may rely on a single desktop screenshot as proof that overlap cannot occur.

---

## 10. Route-closure rule

If the target audit identified:

```text
previous section tail
+
current CTA
+
footer
```

as one unresolved view, future route closure must explicitly separate:

```text
CONTENT RESOLUTION
↓
CLOSING ACTION
↓
FOOTER / GLOBAL NAVIGATION STATE
```

Controlled overlap/preview is allowed only if each state remains legible and resolved.

---

## 11. Responsive obligation

Non-regression is not desktop-only.

For every defect that could be breakpoint-sensitive, the blueprint must later define validation at the target viewport set or an equivalent agreed matrix.

The framework should record:

```text
WIDE DESKTOP
DESKTOP
TABLET
MOBILE
NARROW MOBILE
```

without hardcoding universal pixel values into Ink-VK methodology.

Project-specific widths belong in the case contract.

---

## 12. Relationship to donor uncertainty

When donor evidence is incomplete, donor uncertainty must not be resolved by copying a risky target behavior.

Example:

```text
DONOR SOLUTION MATRIX
observed only at reduced zoom

UNKNOWN
exact card width / typography / breakpoint behavior

TARGET HISTORY
old five-card layout clipped text

DECISION
preserve donor dense-matrix information job,
but defer exact dimensions and explicitly prohibit the known clipping/crowding failure.
```

This is stronger than guessing the donor implementation.

---

## 13. Blueprint admission test

Before a route blueprint can be approved, answer:

```text
1. Which known target defects apply to this route?
2. Which positive controls apply?
3. What invariant prevents each defect from returning?
4. Does any donor pattern conflict with an invariant?
5. If yes, what conditional rule resolves the conflict?
6. Which unknowns still require responsive/interaction evidence?
```

If a defect has no prevention invariant, the blueprint is incomplete.

---

## 14. Final Target Non-Regression Test

After BUILD, verify against the frozen baseline.

For each known defect:

```text
NOT PRESENT
PRESENT
NOT TESTED
NOT APPLICABLE
```

For each positive control:

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

This is separate from donor parity.

A build may match Dayos closely and still fail because it recreated VTKALL's old clipping or section-boundary problems.

---

## 15. VTKALL Solutions validation example

Recovered negative evidence:

```text
SOLUTIONS-01
headline / secondary card competition
lower content clipped

SOLUTIONS-02
next section enters before current state resolves
large empty central/right field without role

SOLUTIONS-03
five industry cards too narrow
text/card content clipped
cards feel cramped

SOLUTIONS-05
previous section + CTA + footer collapse into one view
```

Recovered positive control:

```text
SOLUTIONS-04
no clipping
balanced composition
whitespace perceived as justified
```

Therefore the VTKALL × Dayos Solutions contract must carry these as hard route-level obligations.

---

# Status

```text
TARGET NON-REGRESSION GATE    ✅ DEFINED v0.1
VALIDATED CASES               ◉ VTKALL SOLUTIONS
CROSS-CASE STATUS             ◉ CANDIDATE
FOUNDATION FREEZE             ⛔ NOT YET
```

**Classification:** `VALIDATED BY THIS CASE ONLY / CROSS-CASE CANDIDATE`.
