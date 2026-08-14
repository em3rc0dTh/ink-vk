# VTKALL — Demonstrations Truth Inventory v0.1

**Project:** Ink-VK  
**Target route:** `DEMONSTRATIONS`  
**Status:** EVIDENCE INVENTORY / TARGET TRUTH SUPPORT  
**Date:** 2026-08-14

---

## 1. Purpose

This document freezes what the current VertikALL evidence actually supports for the Demonstrations route before Dayos Use Cases is mapped onto it.

It exists to prevent a rich donor library from manufacturing a richer target catalog than VertikALL currently has.

Governing rule:

> **The donor may donate a library experience. Only target evidence may populate the library.**

---

## 2. Current public route truth

The current VertikALL website already defines one Demonstrations route with one concrete reference:

```text
Turagua Racing / MecánicaPro
```

Current public status language:

```text
DEMONSTRATION ENVIRONMENT
EXAMPLE INDUSTRY PACK
NO PRODUCTION METRICS OR TESTIMONIALS CLAIMED
```

The current route describes the demonstration as a car-workshop / auto-services operating pattern.

Evidence class:

```text
T0 — DIRECT TARGET FACT for the existence of the public demonstration framing
T2 — DEMONSTRATION / POC for capability evidence
```

---

## 3. Current route content supported directly

### Reference pattern

```text
Turagua Racing / MecánicaPro
```

Supported meaning:

```text
car workshop / auto-services demonstration
appointments
customers
services
staff availability
work execution
```

### Problem pattern

Supported workshop-friction language includes:

```text
appointments
quotations
customer messages
service details
work status
visibility loss
manual information chasing
```

### Public-safe capabilities currently represented

```text
appointment booking
automated appointment confirmation and cancellation flow
customer and lead directory
vehicle and customer history
staff availability
service catalog organization
administrative dashboard visibility
work execution tracking
quotation feedback workflow
landing page configuration
```

These are capability/demo facts, not proof of market adoption.

### Guardrail

Current route explicitly states that it is not:

```text
proven case study
production success story
market-validated product
```

and does not claim:

```text
metrics
testimonials
revenue outcomes
traction
```

This guardrail is target truth and must survive the transformation.

---

## 4. Deeper source evidence available from VPack-0

The VPack-0 source contains deeper technical and operational evidence for Turagua Racing / MecánicaPro.

Public-safe capability-level evidence includes:

```text
appointment booking
appointment status management
WhatsApp confirmation / cancellation behavior
customer / lead records
vehicle history
staff / team availability
service catalog management
work-in-progress tracking
quotation / evaluation feedback flow
administrative dashboard visibility
landing-page configuration
```

The source also contains implementation-specific details such as:

```text
Next.js
Node / Express
MongoDB / Mongoose
OpenWA
Gemini
JWT
webhook handling
LID mapping
```

Those technical details are **not automatically public Demonstrations content**.

They may inform internal evidence confidence while the public route remains outcome-oriented.

---

## 5. Current catalog cardinality

Concrete demonstrations with sufficient current evidence:

```text
1
```

Namely:

```text
Turagua Racing / MecánicaPro
```

Other industry categories such as food businesses, clinics, field services, and local services currently exist as:

```text
PATTERNS / EXAMPLES / SOLUTION DIRECTIONS
```

They are **not** currently equivalent demonstration records.

Therefore:

```text
SOLUTION PATTERN
≠
DEMONSTRATION
```

and:

```text
5 SOLUTION PATTERNS
≠
5 DEMONSTRATIONS
```

---

## 6. Unsupported demonstration claims

Current evidence does not support a public Demonstrations inventory containing:

```text
multiple customer case studies
multiple production deployments
verified performance metrics
customer testimonials
ROI data
revenue impact
market traction
partner logos
industry-by-industry live demo portfolio
```

These remain T4 — UNKNOWN / UNSUPPORTED for this route.

---

## 7. Filters / categories truth

Dayos Use Cases contains a filter rail because it has a dense, varied inventory.

VertikALL currently has one concrete demonstration record.

Therefore current target evidence does not justify public filtering by:

```text
industry
capability
company size
workflow
product
result
```

unless those filters operate on real multiple demonstration records.

A category label may describe the single demonstration, but a filter control that produces no meaningful choice is not justified.

---

## 8. Demonstration record schema candidate

The current evidence is sufficient to propose a reusable record schema without fabricating additional records:

```text
DEMONSTRATION NAME
STATUS
INDUSTRY / CONTEXT
PROBLEM PATTERN
CAPABILITIES SHOWN
FLOW / OPERATING AREAS
AVAILABLE EVIDENCE
PUBLIC CLAIM CEILING
NEXT ACTION
```

For Turagua Racing / MecánicaPro:

```text
STATUS                = DEMONSTRATION / EXAMPLE INDUSTRY PACK
INDUSTRY               = AUTO SERVICES / WORKSHOP
CLAIM CEILING          = DEMONSTRATION CAPABILITY
PRODUCTION SUCCESS     = NOT CLAIMED
METRICS                = NOT CLAIMED
TESTIMONIALS           = NOT CLAIMED
```

This schema may scale to later demonstrations when real evidence exists.

---

## 9. Route truth conclusion

Current truth supports:

```text
ONE REAL DEMONSTRATION RECORD
+
RICH DETAIL INSIDE THAT RECORD
```

It does not support:

```text
A RICH MULTI-RECORD LIBRARY
```

Therefore the Dayos Use Cases transformation must preserve the donor's **discovery/evidence-library logic** without forcing false catalog density.

---

# Gate result

```text
CURRENT DEMONSTRATION COUNT       ✅ 1 SUPPORTED
DEMO STATUS                       ✅ FROZEN
PUBLIC CAPABILITY EVIDENCE        ✅ SUFFICIENT
PRODUCTION SUCCESS                ⛔ NOT CLAIMED
METRICS / TESTIMONIALS            ⛔ NOT CLAIMED
MULTI-ITEM FILTER LIBRARY         ⛔ NOT JUSTIFIED YET
REUSABLE RECORD SCHEMA            ✅ CANDIDATE
```

**Next authority:** `VTKALL_DAYOS_DEMONSTRATIONS_SECTION_TRANSFORMATION_CONTRACT_v0.1.md`.
