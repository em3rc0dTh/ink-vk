# Ink-VK — Implementation-Safe Unknown Gate v0.1

**Status:** CROSS-CASE CANDIDATE / VALIDATED BY VTKALL × DAYOS  
**Date:** 2026-08-14

---

## 1. Problem

A design process can fail in two opposite ways:

```text
FALSE FREEZE
→ invent exact values merely to remove unknowns

FALSE DEFER
→ leave architecture-shaping decisions for engineers to improvise during BUILD
```

Ink-VK needs a third state.

> **An unknown may survive Design Freeze only when it is implementation-safe.**

---

## 2. Definition

An **implementation-safe unknown** is a value or detail that may still be calibrated during implementation without changing:

```text
target truth
target Soul
information architecture
page-mode ownership
interaction dependency ceiling
semantic behavior
responsive content order
proof / status meaning
asset rights boundary
R3 fidelity obligation
non-regression obligation
```

If changing the unknown could change any item above, it is not implementation-safe and must be resolved before PLAN is considered ready.

---

## 3. Required closure

An unknown may be marked `BOUNDED / IMPLEMENTATION-SAFE` only when all five fields are frozen:

```text
1. SEMANTIC ROLE
   What job does it perform?

2. TRIGGER / CONTEXT
   When does it apply?

3. INVARIANTS
   What must remain true while tuning it?

4. ACCEPTANCE BOUNDARY
   How do we know calibration still satisfies the design?

5. FORBIDDEN MUTATION
   What may implementation never redefine?
```

---

## 4. Examples

### Safe: animation duration

Exact milliseconds may remain open when already frozen:

```text
motion class
trigger
state relationship
sequence
interruptibility
reduced-motion equivalent
no-fake-state rule
visual acceptance method
```

Changing 420 ms to 520 ms does not create a new information architecture.

### Unsafe: Start as route vs true modal

This changes:

```text
direct-address behavior
focus mechanics
exit behavior
navigation architecture
browser-history assumptions
```

It must be decided before PLAN.

### Safe: optical breakpoint movement

A baseline breakpoint may move slightly if:

```text
transformation ownership is already frozen
content order remains fixed
mobile navigation mode remains fixed
change exists only to prevent clipping/crowding
```

### Unsafe: whether mobile navigation contains nested children

That changes route/disclosure architecture and cannot be delegated to BUILD.

### Safe: 3D material roughness / camera tuning

Only when the semantic object, states, rights boundary and composition role are already frozen.

### Unsafe: what the 3D object means

Meaning controls narrative and asset production. It is a Design decision.

---

## 5. Classification

Use:

```text
FROZEN
BOUNDED / IMPLEMENTATION-SAFE
DEFERRED / OPTIONAL DEPENDENCY
BLOCKING UNKNOWN
```

Definitions:

### FROZEN
Changing it requires a new design decision or explicit contract revision.

### BOUNDED / IMPLEMENTATION-SAFE
A narrow calibration range or implementation expression remains open, but the design job cannot change.

### DEFERRED / OPTIONAL DEPENDENCY
The current truthful experience does not depend on it. If added later, it re-enters the relevant gates.

### BLOCKING UNKNOWN
PLAN would force engineers to invent architecture, truth, interaction promises, rights assumptions or semantic design.

---

## 6. PLAN gate

PLAN readiness requires:

```text
BLOCKING UNKNOWN = 0
```

It does **not** require:

```text
UNKNOWN = 0
```

A mature freeze makes uncertainty explicit and constrained rather than cosmetically eliminating it.

---

## 7. BUILD boundary

During BUILD, an implementation-safe unknown may be calibrated only with evidence.

Examples:

```text
rendered viewport comparison
motion playback comparison
clipping/readability test
reduced-motion validation
asset-performance evidence
interaction accessibility test
```

Calibration that crosses the frozen semantic boundary is not a BUILD tweak. It is a design-contract change and must return to the appropriate gate.

---

## 8. Governing statement

> **Design Freeze is not the moment when every number is known. It is the moment when no remaining unknown can silently redesign the product.**
