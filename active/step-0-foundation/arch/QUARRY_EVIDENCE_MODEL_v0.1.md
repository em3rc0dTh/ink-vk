# Ink-VK — Quarry Evidence Model v0.1

**Step:** 0 — Foundation  
**Lane:** ARCH  
**Status:** PROPOSED  
**Trigger:** Dayos donor study, 2026-08-14

## 1. Decision being proposed

A **quarry is not a file type**.

A quarry is a coherent, provenance-preserving evidence collection about one concrete candidate/source. It may contain multiple instruments — screenshots, URLs, extracted JSON/tokens, CSS references, diagrams, notes, code, videos, or measurements — as long as every instrument declares what it can and cannot prove.

This proposal resolves an important question surfaced by the Dayos pass:

> Can Mermaid, JSON and CSS be part of a quarry?

**Yes.** But they occupy different evidence tiers and must never be flattened into one undifferentiated truth.

## 2. Evidence tiers

### Q0 — RAW CAPTURE

Examples: original screenshot ZIPs, videos, exported frames, untouched source artifacts supplied by the user.

Authority: strongest evidence for **what was actually visible in the captured state**.

Cannot prove automatically: implementation mechanism, responsive behavior outside the capture, animation/motion not visible in evidence, or licensing/reuse rights.

### Q1 — LIVE SOURCE

Examples: donor URL, current route crawl, current navigation/content inspection.

Authority: strongest evidence for **what the donor currently exposes at inspection time**.

Risk: temporal drift. The source may change after capture.

### Q2 — EXTRACTED SYSTEM

Examples: design-token extraction, Refero-style report, JSON, generated CSS variables, inferred typography/spacing palette.

Authority: useful for **system hypotheses and measurement targets**.

Required label: `DERIVED`.

It must not be described as official internal implementation unless first-party provenance proves that claim.

### Q3 — RECOVERED TOPOLOGY

Examples: Mermaid route map, page-flow diagram, section topology, component-family map recovered from evidence.

Authority: useful for **structural understanding and cross-page comparison**.

Required label: `DERIVED / INK-VK RECOVERY`.

A diagram explains evidence; it is not raw evidence.

### Q4 — INTERPRETATION

Examples: Design DNA, transferability audit, candidate extraction, `KEEP / ADAPT / QUESTION / REJECT` classification.

Authority: Ink-VK reasoning.

Rule: `INTERPRETATION MUST ALWAYS POINT BACK TO EVIDENCE.`

## 3. Non-flattening rule

```text
SCREENSHOT
    ≠
LIVE DOM / ROUTE
    ≠
EXTRACTED TOKENS
    ≠
RECOVERED MERMAID
    ≠
DESIGN DNA
```

If layers agree, confidence rises. If they disagree, the disagreement is evidence and must be recorded rather than silently reconciled.

## 4. Reduced-capture rule

Zoom-altered/reduced captures must carry an explicit provenance flag.

They may support:

- macro layout;
- section ordering;
- density mode;
- grid topology;
- broad use of available width.

They should not be used alone to assert:

- exact font sizes;
- exact spacing;
- exact line length;
- card readability;
- accessibility;
- viewport-native density.

## 5. Canonical quarry layout candidate

```text
mining-sites/
└── <problem-space>/
    └── <candidate>/
        ├── README.md
        ├── quarry-00-rendered-captures/
        ├── quarry-01-live-site/
        ├── quarry-02-style-system-extraction/
        ├── quarry-03-recovered-topology/
        └── ...
```

Large/raw bytes remain canonical under `source-archive/`; the mining-site quarry points to them rather than duplicating evidence.

## 6. Promotion rule

A quarry can teach Ink-VK without becoming the donor.

```text
QUARRY
  ↓
TEST / DISSECT
  ↓
CANDIDATE INTELLIGENCE
  ↓
SELECT / REJECT / KEEP CONTEXTUAL
```

Selection remains an explicit later decision.

## 7. Dayos validation

The Dayos study demonstrates why this model is necessary:

- 66 direct rendered captures establish visual reality;
- the live site verifies current route/content families;
- an externally derived token/CSS set proposes a style system;
- a recovered Mermaid topology expresses the relationship between routes and page modes;
- the Design DNA document interprets the combined evidence.

Keeping these layers separate produces a stronger donor analysis than treating all files as equally authoritative.

## 8. Status

This is a **v0.1 framework proposal**, not a frozen Ink-VK baseline.

It should be tested against additional donors before Gate 0 freezes the final quarry contract.
