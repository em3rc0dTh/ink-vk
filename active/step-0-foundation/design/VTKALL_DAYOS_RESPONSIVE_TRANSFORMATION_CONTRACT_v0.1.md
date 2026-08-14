# VTKALL × Dayos — Responsive Transformation Contract v0.1

**Status:** DESIGN FREEZE  
**Scope:** DF-07 + DF-08 + DF-09 + responsive part of DF-10  
**Build:** NOT AUTHORIZED  
**Date:** 2026-08-14

---

## 1. Governing rule

> **Responsive fidelity preserves the information job and experiential relationship, not the desktop column count.**

No viewport may reintroduce the original target defects:

```text
clipped content
crowded center + idle side space
cramped peer cards
cut lists/processes
meaningless empty fields
unresolved section leakage
CTA + footer collapse
```

---

# 2. Responsive baseline tokens

The current target implementation already contains target-owned responsive anchors at:

```text
920px
760px
620px
```

These values are not treated as proof of an ideal historic layout. They are retained as v0.1 **baseline transformation tokens** so PLAN has concrete architecture anchors without inventing new breakpoints.

Their new semantic ownership is frozen as:

```text
≤ 920px  MAJOR GEOMETRY TRANSFORMATION
≤ 760px  NAVIGATION / LOCAL-ORIENTATION MOBILE MODE
≤ 620px  COMPACT HANDSET DENSITY / SINGLE-SEQUENCE MODE
```

A breakpoint may move during implementation calibration only when rendered evidence proves the frozen transformation occurs too early/late for real content. Such movement may not change which transformation belongs to the layer.

---

# 3. Global transformation invariants

At every width:

```text
brand is recognizable
all admitted routes remain reachable
Start remains distinct as primary action
core content order remains legible
no proof/status label disappears
no information becomes hover-only
no horizontal scrolling is required for prose
no component relies on clipping as composition
surface handoffs remain intentional
closure remains content → valid action → footer
```

---

# 4. Desktop / wide mode — above 920px

Primary composition may use:

```text
wide field + controlled reading column
2-column narrative fields
horizontal process geometry
local Company rail
dense-but-readable pattern matrices
Home 3D as strong counterweight
```

Wide mode is not permission to waste lateral space. Empty field must belong to a semantic device, orientation rail, evidence visual, process geometry or intentional reading rhythm.

---

# 5. Major geometry transformation — ≤ 920px

At this layer:

## Home

- hero copy remains first in reading order;
- 3D moves from peer dominance to supporting dominance;
- two-column narrative fields stack/re-sequence according to semantic order;
- Organize / Follow Up / Control states remain reachable and legible;
- peer patterns avoid narrow multi-column compression.

## Solutions

- pattern matrix reduces columns before cards become cramped;
- item count never dictates column count;
- comparison remains scan-friendly rather than becoming five narrow legacy cards.

## Demonstrations

- featured record becomes a stacked evidence sequence:

```text
status
context
claim / problem
evidence or evidence slot
capabilities
claim boundary
next action
```

Optional media must not be required for the stack to make sense.

## Method

- horizontal connected track transforms to a connected vertical track;
- the five-step order remains explicit;
- no compressed horizontal mini-nodes.

## Company

- editorial reading width remains controlled;
- local rail may remain while there is sufficient width, but it must not squeeze prose.

## Start

- focused surface becomes a bounded single-column sheet/card;
- six labels remain one clear sequence;
- no field labels are placed side-by-side merely to save height.

---

# 6. Navigation / local-orientation mobile mode — ≤ 760px

## 6.1 Global shell

Desktop central navigation is replaced by one explicit **Menu** disclosure.

Persistent visible layer:

```text
[ VertikALL brand ]                  [ Menu ]
```

Disclosure contents:

```text
Solutions
Demonstrations
Method
Company
Start  ← visually distinct primary action
```

### Frozen mechanics

- one level only;
- no fake dropdown children;
- open/close is explicit and deterministic;
- brand remains visible;
- underlying route context may remain visually present but must not compete with open navigation;
- keyboard/focus handling belongs to the implementation acceptance contract;
- all destinations are normal real routes.

The design does not claim this reproduces Dayos mobile mechanics; donor mobile behavior was not recovered.

---

## 6.2 Company local orientation

The wide local rail transforms into a compact in-page orientation control before/near the editorial body.

Required real anchors may include only approved target sections such as:

```text
Mission
Everything is a Network
Principles / editorial statements
Origin / leverage
Harbor / relationship philosophy
What VertikALL is / is not
Current / future honesty
```

Exact final labels follow copy freeze.

### Narrow behavior

The orientation may be:

```text
compact expandable index
or
compact always-visible anchor list
```

PLAN must select one implementation expression; neither may invent missing team/partner/career/update destinations.

Automatic scrollspy is optional and not required for Design Freeze. Anchor navigation itself is the required job.

---

# 7. Compact handset mode — ≤ 620px

At this layer:

```text
single-column sequence is the default
section padding compresses without collapsing hierarchy
large display typography yields before it clips
primary/secondary actions may stack
pattern items become full-width or readable small sets
3D yields further visual dominance
status/meta labels remain visible
footer does not collide with the final CTA state
```

No content is removed merely to make the mobile composition easier.

---

# 8. Start responsive focus contract

`/start` is frozen as a **route-contained overlay-like focused state**.

Across widths:

- route remains directly addressable;
- focused surface owns the user’s attention;
- surrounding context may be dimmed/de-emphasized as a visual technique;
- it is not a true modal dependency;
- no browser-history-only close;
- explicit exit goes to a valid target route;
- D0 remains presentation/schema only;
- no editable fields, validation, submit, scheduling or success state are introduced by responsive transformation.

At compact widths the focused surface may visually fill most/all of the usable width while retaining clear page ownership and exit.

---

# 9. Motion integration

Responsive transformation and motion are separate concerns.

A layout must remain correct before animation is applied.

Required rule:

```text
RESPONSIVE GEOMETRY
must not depend on
ANIMATION COMPLETING SUCCESSFULLY
```

Reduced motion preserves the same transformed layout.

---

# 10. Non-regression acceptance states for later PLAN/BUILD

PLAN must include evidence capture at minimum around:

```text
wide desktop
near 920 transformation
near 760 navigation/local-orientation transformation
near 620 compact transformation
minimum supported width ≥ 320px
```

Acceptance is semantic, not screenshot-count driven:

```text
no clipping
no avoidable crowding
no unjustified idle field beside cramped content
no hidden route
no hidden proof status
correct process order
correct Start dependency ceiling
correct closure
```

Positive controls remain conceptually equivalent to:

```text
SOLUTIONS-04 → complete + balanced whitespace
START-03     → complete/readable intake information
```

---

# 11. Implementation-safe unknowns

Allowed later calibration:

```text
small breakpoint movement driven by real content
exact gaps/padding within frozen hierarchy
exact display-size clamp values
exact open/close animation values
exact local-index compact visual styling
```

Not allowed later without returning to Design:

```text
changing navigation topology
adding nested routes
changing Method order
turning Start into a true submission flow
hiding proof/status on mobile
removing Company orientation
reassigning page-mode ownership
```

---

# 12. Freeze result

```text
RESPONSIVE TRANSFORMATION LAYERS   ✅ FROZEN
920 / 760 / 620 BASELINE TOKENS    ✅ FROZEN AS CALIBRATION BASE
MOBILE NAV TOPOLOGY                ✅ FROZEN
COMPANY LOCAL-ORIENTATION JOB      ✅ FROZEN
START RESPONSIVE PRESENTATION      ✅ FROZEN
ROUTE ORDER / STATUS PRESERVATION  ✅ FROZEN
EXACT OPTICAL VALUES               ◉ IMPLEMENTATION-SAFE UNKNOWN
```

**DF-07:** CLOSED FOR PLAN.  
**DF-08:** CLOSED FOR PLAN.  
**DF-09:** CLOSED FOR PLAN.  
**DF-10 responsive mechanics:** CLOSED FOR PLAN.
