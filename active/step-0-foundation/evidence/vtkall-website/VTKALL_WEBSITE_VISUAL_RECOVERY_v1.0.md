# VTKALL Website — Visual Recovery v1.0

**Project:** Ink-VK  
**Case:** `vtkall-website`  
**Evidence type:** annotated rendered-view recovery  
**Date:** 2026-08-14  
**Status:** RECOVERED / NOT YET REDESIGNED  

## 1. Purpose

This document recovers the user's handwritten visual observations from the first rendered-view evidence set for `vtkall-website`.

The goal of this pass is deliberately narrow:

1. read every supplied image individually;
2. preserve the observation attached to that image;
3. distinguish direct observation from interpretation;
4. identify repeated visual symptoms without yet prescribing implementation changes.

This is the visual counterpart to code recovery. Reading source code establishes structure and intent; these captures establish how that structure actually appeared when rendered at the captured viewport.

**Route order supplied by the user:**

```text
home → solutions → demonstrations → method → start
```

**Evidence set:** 29 PNG captures.

Source provenance and hashes are preserved in:

`source-archive/vtkall-website/visual-review/VTKALL_VISUAL_SOURCE_MANIFEST_v1.0.md`

---

# 2. Image-by-image recovery

## 2.1 Home — 7 captures

### HOME-01 — `vtkall-home-view (1).png`

**Recovered annotations**

- The information is cut within the same visible view.
- Handwritten note reads approximately: **“Se traspone la data”**; the marked area shows the large hero text and the right-side business-flow card occupying/conflicting with the same visual region.

**Observed visual condition**

- Hero content is not comfortably contained in the viewport.
- The lower copy/CTA area is visibly clipped.
- The two-column hero composition feels spatially conflicted rather than clearly separated.

### HOME-02 — `vtkall-home-view (2).png`

**Recovered annotations**

- **“¿? Demasiado espacio en blanco.”**
- **“Se mezclan secciones CTA + footer.”**

**Observed visual condition**

- The CTA occupies a large amount of empty vertical space.
- CTA and footer are simultaneously visible, weakening the sense of a clean section boundary.

### HOME-03 — `vtkall-home-view (3).png`

**Recovered annotations**

- Left note is partially ambiguous; it indicates that the large content should be seen complete rather than cut across the viewport.
- **“¿? Demasiado espacio en blanco.”**

**Observed visual condition**

- The oversized heading consumes most of the left column and reads as visually cut/awkwardly segmented.
- A large empty region remains beneath/right of the method list.

### HOME-04 — `vtkall-home-view (4).png`

**Recovered annotation**

- **“Se combinan secciones.”**

**Observed visual condition**

- The dark demonstration block and the following method block are both present in one viewport.
- The screenshot does not read as one self-contained visual section.

### HOME-05 — `vtkall-home-view (5).png`

**Recovered annotations**

- Left note again indicates that the primary section should appear complete instead of being cut.
- **“¿? Demasiado espacio vacío.”**
- **“Se ve parte de la siguiente sección.”**

**Observed visual condition**

- Main content is concentrated on the left while a large right-side area remains unused.
- The next section becomes visible at the bottom before the current composition feels visually complete.

### HOME-06 — `vtkall-home-view (6).png`

**Recovered annotations**

- Left note again indicates a preference for the current section to appear complete rather than cut.
- **“¿? Espacio en blanco.”**

**Observed visual condition**

- The content hierarchy is heavily left-weighted.
- The upper-right region is almost entirely empty despite the section being visually dense elsewhere.

### HOME-07 — `vtkall-home-view (7).png`

**Recovered annotations**

- **“Se ve data de la sección siguiente.”**
- **“Demasiado espacio en blanco.”**

**Observed visual condition**

- The next section label (`ORGANIZE`) is already visible at the bottom.
- The right side of the current section contains a very large unused region.

### Home recovery signal

The repeated symptoms are:

- incomplete/cut section presentation;
- next-section leakage into the same viewport;
- large unjustified empty regions;
- hero/content columns that compete for space instead of forming a stable composition.

---

## 2.2 Solutions — 5 captures

### SOLUTIONS-01 — `vtkall-solutions-view (1).png`

**Recovered annotations**

- **“Se sobreponen los componentes.”**
- **“Se corta la información.”**

**Observed visual condition**

- The large headline and right-side card visually collide/compete.
- Lower copy and controls are cut by the viewport.

### SOLUTIONS-02 — `vtkall-solutions-view (2).png`

**Recovered annotations**

- Left note indicates that the following section is again entering the current view.
- **“¿? Espacio vacío injustificado.”**

**Observed visual condition**

- `EXAMPLES AND PATTERNS / Industry pack` appears at the bottom while the current section remains on screen.
- A large central/right empty area has no visible compositional role.

### SOLUTIONS-03 — `vtkall-solutions-view (3).png`

**Recovered annotations**

- **“Se corta el cuadro de texto.”**
- **“Cada cuadro se ve apretado.”**

**Observed visual condition**

- The five industry cards are narrow relative to their copy.
- Text extends toward/beyond the visible lower boundary.
- The card content lacks breathing room.

### SOLUTIONS-04 — `vtkall-solutions-view (4).png`

**Recovered annotation**

- **“Aceptable, no se corta y se justifica el espacio.”**

**Observed visual condition**

- This is an explicit positive reference inside the evidence set.
- The section is self-contained in the viewport.
- Empty space is perceived as intentional because the layout remains balanced.
- No card or primary content is visibly clipped.

### SOLUTIONS-05 — `vtkall-solutions-view (5).png`

**Recovered annotation**

- **“Se combinan 3 secciones.”**

**Observed visual condition**

Three distinct visual layers appear together:

1. tail of the preceding green section;
2. current CTA (`Move from pattern to demonstration.`);
3. footer.

### Solutions recovery signal

The route demonstrates both failure and a useful internal control sample:

- overlap/crowding and clipping occur in the hero/cards;
- section boundaries repeatedly leak;
- unjustified whitespace appears;
- **SOLUTIONS-04 establishes that whitespace itself is not the problem** — it becomes acceptable when the section is balanced, complete, and visually intentional.

---

## 2.3 Demonstrations — 6 captures

### DEMONSTRATIONS-01 — `vtkall-demonstration-view (1).png`

**Recovered annotations**

- **“No se sobrepone, sin embargo se ve apretado. Tenemos mucho espacio lateral.”**
- **“Se corta la data.”**

**Observed visual condition**

- The hero columns do not directly overlap, but the center composition feels compressed.
- Significant unused lateral space coexists with tight central content.
- Lower status/content is clipped.

### DEMONSTRATIONS-02 — `vtkall-demonstration-view (2).png`

**Recovered annotation**

- **“Se combinan secciones.”**

**Observed visual condition**

- Reference-pattern content and the beginning of the following problem-pattern section are visible together.

### DEMONSTRATIONS-03 — `vtkall-demonstration-view (3).png`

**Recovered annotations**

- Green handwritten **“Sugerencia”** with a drawn horizontal sequence of boxes connected by arrows.
- Red note: **“Se ve cortado.”**

**Observed visual condition**

- Current numbered list is vertically stacked and reaches the lower viewport boundary.
- The user's sketch proposes representing the process as an actual **sequence/flow** rather than only a stacked list.
- This is the only explicit alternative-composition suggestion in the supplied evidence set and should be preserved as such, not treated as an already-approved redesign.

### DEMONSTRATIONS-04 — `vtkall-demonstration-view (4).png`

**Recovered annotations**

- **“¿? Espacio en blanco injustificado.”**
- **“Se cortan las tarjetas.”**

**Observed visual condition**

- A large unused area occupies the upper-right portion of the section.
- The second row of capability cards is cut by the bottom of the viewport.

### DEMONSTRATIONS-05 — `vtkall-demonstration-view (5).png`

**Recovered annotation**

- **“Se combinan secciones.”**

**Observed visual condition**

- The dark guardrail section and the following white CTA section share the same visible frame.

### DEMONSTRATIONS-06 — `vtkall-demonstration-view (6).png`

**Recovered annotation**

- **“Se combinan secciones.”**

**Observed visual condition**

The screenshot exposes three layers at once:

1. tail of the previous dark guardrail section;
2. current CTA (`Move from example to method.`);
3. footer.

### Demonstrations recovery signal

Repeated symptoms:

- central compression despite available lateral space;
- clipped lower content/cards;
- repeated section-boundary leakage;
- unused whitespace with no obvious visual function.

The route also contains one explicit design idea worth carrying forward as evidence: **represent a sequential operating flow as a visual sequence**.

---

## 2.4 Method — 6 captures

> **Source naming note:** the files inside `vtkall-method-view.zip` are named `vtkall-start-view (...)`. Route attribution follows the supplied ZIP and the visible `METHOD` content.

### METHOD-01 — supplied as `vtkall-start-view (1).png`

**Recovered annotations**

- **“¿? Espacio en blanco injustificado.”**
- Lower annotation indicates that a substantial amount of information is being cut.

**Observed visual condition**

- The left headline and right diagram are concentrated in the lower/central area while the upper-right remains largely empty.
- Supporting copy is visibly cut at the bottom.

### METHOD-02 — supplied as `vtkall-start-view (2).png`

**Recovered annotations**

- **“No se justifica el espacio en blanco.”**
- Left note indicates that the section below can already be seen.

**Observed visual condition**

- Large empty right-side region.
- The `FIVE STEPS` label from the following section is visible at the bottom.

### METHOD-03 — supplied as `vtkall-start-view (3).png`

**Recovered annotation**

- **“Se corta la lista.”**

**Observed visual condition**

- The numbered five-step list extends beyond the viewport; step 03 begins but is visibly cut.

### METHOD-04 — supplied as `vtkall-start-view (4).png`

**Recovered annotation**

- Handwritten note identifies this capture as **the following part/continuation of the previous section**.

**Observed visual condition**

- The viewport contains the continuation of steps 02–05 rather than a new independent section.
- This capture is evidence that the five-step component requires more than one viewport at the captured dimensions.

### METHOD-05 — supplied as `vtkall-start-view (5).png`

**Recovered annotation**

- **“Se combinan secciones.”**

**Observed visual condition**

- Dark `NO TECHNICAL BURDEN` content and the following white CTA are visible together.
- The next headline is itself cut at the bottom.

### METHOD-06 — supplied as `vtkall-start-view (6).png`

**Recovered annotation**

- **“Se combinan secciones.”**

**Observed visual condition**

Three visual layers are present together:

1. previous dark section tail;
2. CTA (`Start with one flow worth organizing.`);
3. footer.

### Method recovery signal

The route repeats the same evidence already present elsewhere:

- whitespace imbalance;
- current/next section mixing;
- list/content clipping;
- multi-section visibility at CTA/footer transitions.

---

## 2.5 Start — 5 captures

### START-01 — `vtkall-start-view (1).png`

**Recovered annotations**

- **“Se ve demasiado apretado.”**
- **“¿? Demasiado espacio blanco injustificado.”**
- **“Se corta la sección.”**

**Observed visual condition**

- Large headline and static-shell card compete within a narrow central composition.
- Right/upper whitespace is large despite the center feeling crowded.
- Bottom content is clipped.

### START-02 — `vtkall-start-view (2).png`

**Recovered annotations**

- **“Se combinan secciones.”**
- **“¿? Espacio en blanco sin sentido.”**

**Observed visual condition**

- The next `DIAGNOSTIC` section appears at the bottom.
- A very large empty right-side region has no visible content function.

### START-03 — `vtkall-start-view (3).png`

**Recovered annotations**

- Black note: **“No se corta, aceptable.”**
- A red **“¿?”** marks the large empty upper-right region without a more specific written conclusion.

**Observed visual condition**

- The diagnostic card grid is fully visible and not clipped.
- This is a second explicit positive control sample, although the marked question indicates unresolved concern about the unused upper-right space.

### START-04 — `vtkall-start-view (4).png`

**Recovered annotation**

- **“Se combinan secciones.”**

**Observed visual condition**

- Dark boundary section and the following white preparation CTA share the viewport.

### START-05 — `vtkall-start-view (5).png`

**Recovered annotation**

- **“Se combinan secciones.”**

**Observed visual condition**

Three layers are simultaneously visible:

1. tail of the previous dark boundary section;
2. current preparation CTA;
3. footer.

### Start recovery signal

Repeated symptoms:

- crowding in the hero despite large unused space elsewhere;
- section mixing;
- clipped content in the first view;
- questionable/unjustified whitespace.

`START-03` is a useful partial positive reference because the card grid is complete and readable even though the upper-right whitespace remains questioned.

---

# 3. Cross-route recovered patterns

This section does **not** prescribe a redesign. It only consolidates what the image-level evidence repeatedly shows.

## Pattern A — Section boundary leakage

The strongest repeated observation is some form of:

> **“Se combinan secciones.”**

or

> **“Se ve parte/data de la siguiente sección.”**

It appears across every supplied route.

The recurring forms are:

- current section + beginning of next section;
- previous section tail + current CTA;
- previous section tail + current CTA + footer.

This establishes **viewport section containment / transition framing** as a real visual-review concern, not an isolated screenshot anomaly.

## Pattern B — Content clipping

Multiple captures explicitly mark:

- information cut;
- cards cut;
- list cut;
- section cut;
- lower copy cut.

The issue occurs in hero compositions, card grids, long lists, and lower supporting content.

## Pattern C — Unjustified whitespace

The user repeatedly distinguishes between:

- **empty space that feels arbitrary**, and
- **space that is acceptable because the composition is balanced**.

This distinction is important.

`SOLUTIONS-04` is explicitly approved as:

> **“Aceptable, no se corta y se justifica el espacio.”**

Therefore Ink-VK should not encode a naive rule such as “reduce whitespace.” The recovered requirement is closer to:

> **Whitespace must have compositional purpose and must not coexist with avoidable crowding, clipping, or broken section framing.**

That final sentence is a normalization of the evidence, not a verbatim user annotation.

## Pattern D — Crowded center / unused sides

Several hero or two-column sections feel compressed even when significant lateral or right-side space exists.

The clearest explicit statement is in `DEMONSTRATIONS-01`:

> **“No se sobrepone, sin embargo se ve apretado. Tenemos mucho espacio lateral.”**

This is a stronger signal than simple overlap: a layout may technically avoid collision and still fail visually because its available space is distributed poorly.

## Pattern E — Completeness is a visual quality criterion

The user repeatedly reacts negatively when a component/section is only partially visible and positively when a section is complete.

Two internal positive controls exist:

- `SOLUTIONS-04`: complete, balanced, space justified;
- `START-03`: content not cut and therefore acceptable, while whitespace remains questioned.

This suggests that **visual completeness/readability within the intended section frame** is an important quality criterion for the later Ink-VK visual gate.

## Pattern F — Sequential information may need sequential representation

`DEMONSTRATIONS-03` contains a green user suggestion showing connected boxes with arrows.

This evidence should be preserved as:

> When the information itself describes a sequence, test whether the visual representation should express that sequence explicitly rather than presenting it as a generic stacked list.

This is a recovered hypothesis for later DESIGN; it is **not yet an approved rule**.

---

# 4. What this evidence changes for Ink-VK

Before these screenshots, the `vtkall-website` review could only reason from implementation structure and code intent.

This evidence demonstrates why Ink-VK needs a distinct **rendered-result recovery layer** before donor extraction, redesign, or VK validation.

A codebase can be structurally understandable while the rendered result still exhibits:

- section-boundary problems;
- clipping;
- poor spatial distribution;
- crowded components;
- whitespace without compositional justification.

Therefore the framework must preserve at least three distinct truths when studying a real implementation:

```text
CODE INTENT
    ≠
RENDERED RESULT
    ≠
USER-PERCEIVED QUALITY
```

The captures in this recovery are evidence for that separation.

This is a framework-learning conclusion derived from the supplied visual evidence; it does not yet freeze the final Ink-VK phase model.

---

# 5. Current boundary

This recovery intentionally stops before redesign.

No decision has yet been frozen about:

- exact section heights;
- viewport strategy;
- CSS/layout changes;
- typography sizing;
- replacement component designs;
- animation/motion;
- responsive breakpoints;
- whether all sections should occupy a full viewport;
- whether the user's sequence sketch becomes the final interaction pattern.

Those require correlation with the earlier code review and a subsequent DESIGN decision.

## Recovery status

```text
29 / 29 annotated captures reviewed
5 / 5 routes recovered
source provenance preserved
cross-route symptoms extracted
positive control samples identified
redesign NOT STARTED
```

**Visual Recovery v1.0: COMPLETE.**
