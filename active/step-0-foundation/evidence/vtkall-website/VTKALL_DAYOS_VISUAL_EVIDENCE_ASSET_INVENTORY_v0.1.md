# VTKALL × Dayos — Visual Evidence Asset Inventory v0.1

**Status:** VERIFIED EXISTENCE / PUBLIC-SAFETY CLASSIFIED  
**Scope:** DF-06  
**Date:** 2026-08-14

---

## 1. Purpose

This inventory answers one narrow question:

> **Which visual assets may the VTKALL × Dayos Design Freeze depend on today without inventing availability, rights, evidence strength or public-safety?**

Existence is not the same as permission to use.

Classification dimensions:

```text
EXISTS
TARGET-OWNED / TARGET-REPO EVIDENCE
ENTITY MATCH
PUBLIC-SAFETY
CLAIM SUPPORT
DESIGN DEPENDENCY STATUS
```

---

# 2. Approved corporate target assets

Source repository:

```text
ronald-zavaleta/vtkall-website
ref: develop
```

## A-01 — VertikALL wordmark

```text
path   public/brand/vertikall-brand-name.png
sha    5c75e9f38925d58dab8940787fb179773922847a
size   5,496,991 bytes
```

**Existence:** VERIFIED  
**Entity:** VertikALL  
**Current public-target use:** YES — referenced by the target SiteHeader  
**Approved role:** brand identity / navigation / closure as appropriate  
**Claim support:** identity only  
**Design dependency:** ALLOWED

---

## A-02 — VertikALL icon

```text
path   public/brand/vertikall-icon.png
sha    0c27537e25ab3165fdc5237643d0e363c148b714
size   262,335 bytes
```

**Existence:** VERIFIED  
**Entity:** VertikALL  
**Current public-target use:** YES — referenced by the target SiteHeader  
**Approved role:** brand mark / identity anchor  
**Claim support:** identity only  
**Design dependency:** ALLOWED

---

# 3. Demonstration-repository candidate assets

Source repository:

```text
ronald-zavaleta/vtkall-demo-pack1-mvvh
ref: main
```

These assets exist in a target-owned technical/demo repository. Their presence does **not** prove they are authorized for the corporate VertikALL website or that they support a public claim.

## C-01 — Gallo Autos logo

```text
path   frontend/public/images/Gallo-Autos-Logo.png
sha    60bf642346c794021a5fb2e52110057e604ec404
size   193,964 bytes
```

**Existence:** VERIFIED  
**Entity:** Gallo Autos / not VertikALL  
**Public-safety for VTKALL corporate site:** UNVERIFIED  
**Relationship/proof meaning:** UNVERIFIED  
**Decision:** CANDIDATE ONLY / DO NOT PLAN AROUND IT

Reason: logo presence could be misread as customer, partner or production proof. Institutional evidence scope must be established separately.

---

## C-02 — `Mecanicos-certificados.png`

```text
path   frontend/public/images/Mecanicos-certificados.png
sha    796d4f42e43867c761cf75f98a601bbc98ced5cb
size   312,692 bytes
```

**Existence:** VERIFIED  
**Entity/content context:** requires inspection/authority confirmation  
**Public-safety:** UNVERIFIED  
**Claim support:** UNVERIFIED  
**Decision:** CANDIDATE ONLY

---

## C-03 — `bateylate.png`

```text
path   frontend/public/images/bateylate.png
sha    d84228509082e1f4d257db9de816738ba2d6d30b
size   97,287 bytes
```

**Existence:** VERIFIED  
**Entity/content context:** requires inspection/authority confirmation  
**Public-safety:** UNVERIFIED  
**Claim support:** UNVERIFIED  
**Decision:** CANDIDATE ONLY

---

## C-04 — Turagua image

```text
path   frontend/public/images/turagua.jpg
sha    9dba43f74dc12b6f058de2650d074130bd9ed23d
size   29,853 bytes
```

**Existence:** VERIFIED  
**Entity:** appears associated with the current Turagua demonstration domain by filename/repository context  
**Public-safety:** UNVERIFIED  
**Production/customer implication:** MUST NOT BE INFERRED  
**Decision:** CANDIDATE ONLY / OPTIONAL EVIDENCE SLOT

The current target claim ceiling remains:

```text
DEMONSTRATION ENVIRONMENT
EXAMPLE INDUSTRY PACK
```

The image cannot elevate that status by itself.

---

## C-05 — Turagua Prado video

```text
path   frontend/public/videos/turagua-prado-1.mp4
sha    a8757889afd456f8ad89ff855f12d80e7258af30
size   12,858,415 bytes
```

**Existence:** VERIFIED  
**Entity/context:** demo-repository context  
**Public-safety:** UNVERIFIED  
**Rights/consent:** UNVERIFIED  
**Freshness/currentness:** UNVERIFIED  
**Design implication:** video/media behavior cannot be required by the current blueprint  
**Decision:** CANDIDATE ONLY

---

# 4. Assets explicitly not transferred from Dayos

The following donor materials are not target evidence and are not authorized by R3 fidelity alone:

```text
Dayos logos
Dayos customer/partner logos
Dayos screenshots
Dayos product UI
Dayos team photography
Dayos source 3D assets
Dayos font files
Dayos metrics / charts
Dayos proprietary media
```

They may be observed as design-role evidence but not used as target visual proof.

---

# 5. Design dependency rule

The frozen VTKALL experience may depend on:

```text
A-01 wordmark
A-02 icon
original target-created conceptual graphics / 3D under the production contract
```

It may **not** depend on C-01 through C-05.

Therefore the Demonstrations route must have a valid zero-optional-media state:

```text
status
context
problem / operating pattern
capability evidence in truthful text/structure
claim boundary
next path
```

If a candidate asset later passes:

```text
entity check
public-safety check
rights/provenance check
freshness check
claim-scope check
```

it may occupy an optional EvidenceVisual slot without changing the route architecture.

---

# 6. Evidence gap intentionally preserved

Current status does **not** prove a public-safe inventory of:

```text
product screenshots
customer screenshots
team/company photography
partner logos
production dashboards
customer metrics
case-study outcome visuals
```

The correct Design Freeze response is not to manufacture replacements that look like proof.

Conceptual 3D may be original target expression, but it remains explicitly conceptual.

---

# 7. Freeze result

```text
CORPORATE BRAND ASSETS         ✅ 2 VERIFIED / ALLOWED
DEMO-REPO MEDIA EXISTENCE      ✅ 5 VERIFIED CANDIDATES
DEMO-REPO PUBLIC APPROVAL      ⛔ NOT ESTABLISHED
DAYOS ASSET TRANSFER           ⛔ FORBIDDEN WITHOUT RIGHTS
ZERO-MEDIA EVIDENCE DESIGN     ✅ REQUIRED / PLAN-SAFE
OPTIONAL FUTURE MEDIA SLOT     ✅ ALLOWED AFTER EVIDENCE GATES
```

**DF-06:** CLOSED FOR PLAN because unapproved media is no longer an architecture dependency.
