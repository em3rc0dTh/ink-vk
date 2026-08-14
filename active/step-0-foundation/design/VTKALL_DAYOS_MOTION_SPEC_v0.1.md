# VTKALL × Dayos — Motion Specification v0.1

**Status:** DESIGN FREEZE  
**Scope:** semantic motion behavior before PLAN  
**Build:** NOT AUTHORIZED  
**Date:** 2026-08-14

---

## 1. Evidence boundary

The Dayos capture set proves visible states and recurring motion opportunities, but static screenshots do not prove exact:

```text
duration
easing
spring physics
scroll thresholds
hover/click trigger choice
sticky behavior
3D response curve
slider drag/swipe mechanics
focus management
```

Therefore this specification freezes target motion **semantics and state relationships**, not invented donor measurements.

---

## 2. Motion principles

VTKALL motion must express:

```text
CALM CONTROL
VISIBLE RELATIONSHIPS
PURPOSEFUL STATE CHANGE
LOW-PRESSURE EXPLORATION
```

Motion may clarify:

```text
entry
orientation
state handoff
relationship
sequence
focus
selection
continuity
```

Motion must never imply unsupported system behavior:

```text
fake loading
fake processing
fake submission
fake success
fake synchronization
fake live status
fake AI activity
```

---

# 3. Frozen motion classes

## M1 — Global navigation disclosure

**Job**  
Reveal or dismiss the compact mobile/global disclosure without losing page context.

**Trigger**  
Explicit user activation.

**Frozen behavior**

```text
closed → open
open → closed
```

- the disclosure remains visually subordinate to the brand and route context;
- Start remains identifiable as primary action;
- no nested child animation exists without real child routes;
- dismissal is deterministic;
- keyboard/focus behavior must be accessible in implementation.

**Implementation-safe unknowns**  
Duration/easing and exact opacity/translation amount.

---

## M2 — Surface handoff

**Job**  
Make a narrative-state transition legible.

**Observed donor precedent**  
Repeated dark/light rounded surface transitions and controlled peeking.

**Frozen behavior**

A handoff may reveal the next semantic surface only when:

```text
current state is resolved
next state is subordinate during transition
primary content is not clipped
surface identity remains legible
```

Motion is optional if static composition alone communicates the handoff.

**Forbidden**  
Using animated peeking to recreate the original VTKALL defect where unresolved sections collide.

---

## M3 — Content / typography reveal

**Job**  
Support reading order, not theatricalize every text block.

**Frozen behavior**

- reveal may follow the visual hierarchy already present;
- a dominant statement resolves before secondary explanatory material becomes visually competitive;
- long-form Company prose remains restrained;
- Demonstrations prioritizes proof readability over reveal spectacle.

**Implementation-safe unknowns**  
Exact stagger interval, offset and easing.

---

## M4 — 3D ambient / response

**Owner**  
Primarily Home.

**Job**  
Make the Operational Network / Flow Graph feel alive enough to communicate relationship and change.

**Frozen states**

```text
BASE NETWORK
→ ORGANIZE
→ FOLLOW UP
→ CONTROL
```

The transition must remain interpretable as a change in operational relationships, not random object motion.

**Allowed response**

- subtle ambient movement;
- viewport/scroll-linked state transition when the corresponding narrative job changes;
- restrained pointer response if it does not interfere with reading or imply direct manipulation.

**Forbidden**

```text
constant distracting spin
physics spectacle without semantic meaning
fake product interaction
motion that obscures text
motion required to understand core information
```

**Reduced motion**  
Show the same semantic states as stable compositions/crossfades with no information loss.

---

## M5 — Peer browsing

**Job**  
Move through a real peer set without forcing unreadable compression.

**Eligible current target context**  
Home/Solutions pattern peers where real items exist.

**Not eligible**  
Demonstrations at C1, where there is only one approved record.

**Frozen behavior**

- browsing changes which real peer receives emphasis;
- controls cannot imply more records than exist;
- text remains readable without drag-only interaction;
- sequence is not falsely converted into process progression.

**Implementation-safe unknowns**  
Whether the final implementation uses snap, button-led shift or another accessible peer-browse mechanic consistent with the same visible state contract.

---

## M6 — Process progression

**Owner**  
Method.

**Job**  
Clarify the real five-step order.

**Frozen order**

```text
1 Understand the business flow
2 Map recurring friction
3 Configure the operating flow
4 Activate follow-up and control
5 Improve with real usage
```

Wide mode may progressively reveal connected horizontal geometry. Narrow mode uses connected vertical geometry.

No completion/check state is required. The website explains a method; it does not claim the visitor is executing it in real time.

---

## M7 — Focused task entry / exit

**Owner**  
Start.

**Job**  
Visually isolate the D0 preparation surface from surrounding context.

**Frozen behavior**

- `/start` remains a route-contained focused state;
- surrounding context may be visually de-emphasized;
- entry/exit motion may reinforce focus;
- the surface remains direct-address safe;
- exit goes to an explicit valid destination;
- no submit/success/progress animation exists at D0.

**Not a true modal**  
No design dependency on modal focus trapping or browser-back-only close behavior.

---

# 4. Route allocation

| Route | Primary classes | Motion intensity |
|---|---|---|
| Home | M2, M3, M4, contextual M5 | highest, still calm |
| Solutions | M2, M3, contextual M5 | medium |
| Demonstrations | M2, M3 | restrained / evidence-first |
| Method | M2, M3, M6 | ordered |
| Company | M2, restrained M3 | low / editorial |
| Start | M7 | focused / minimal |

Motion intensity is part of page-mode differentiation. Coherence does not mean identical animation density.

---

# 5. Reduced-motion contract

Every motion class must have an information-equivalent reduced-motion state.

Minimum acceptance:

```text
navigation remains usable
surfaces remain distinguishable
3D semantic state remains visible
peer items remain reachable
process order remains explicit
Start remains focused and safely exit-able
```

No target meaning may exist only inside an animation.

---

# 6. Acceptance evidence for later BUILD

PLAN must require later evidence at representative viewports for:

```text
normal motion
reduced motion
keyboard/focus navigation
interruption / repeated activation
surface handoff without clipping
3D state readability
process order readability
```

Exact milliseconds/easing are accepted by comparative playback and non-regression evidence, not by pretending they were recovered from static Dayos captures.

---

# 7. Freeze result

```text
MOTION CLASS OWNERSHIP          ✅ FROZEN
SEMANTIC JOBS                   ✅ FROZEN
TRIGGERS / STATE RELATIONSHIPS  ✅ FROZEN
ROUTE INTENSITY                 ✅ FROZEN
REDUCED-MOTION REQUIREMENT      ✅ FROZEN
NO-FAKE-STATE RULE              ✅ FROZEN
EXACT DURATION / EASING         ◉ IMPLEMENTATION-SAFE UNKNOWN
DONOR MOTION PHYSICS            ? UNKNOWN / NOT INVENTED
```

**DF-03:** CLOSED FOR PLAN.
