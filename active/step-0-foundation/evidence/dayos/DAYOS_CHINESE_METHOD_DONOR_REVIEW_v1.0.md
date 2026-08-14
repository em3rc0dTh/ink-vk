# Dayos — Chinese Method Donor Review v1.0

**Project:** Ink-VK  
**Target learning case:** `vtkall-website`  
**Donor candidate:** Dayos  
**Source:** https://www.dayos.com/  
**Review date:** 2026-08-14  
**Evidence:** 66 PNG captures / 11 ZIP bundles + live-site verification + derived style extraction  
**Status:** DONOR DISSECTION COMPLETE / TRANSFORMATION NOT STARTED  
**Boundary:** NO VTKALL REDESIGN / NO CODE / NO BUILD

## Executive recovery statement

Dayos does **not** work because it simply uses less content or more whitespace.

Its stronger recurring intelligence is that the site treats layout as a communication system: **the page mode changes with the information job while the visual grammar remains coherent**. Narrative claims, product mechanism, quantitative proof, catalogs, comparisons, sequential processes, company evidence, and conversion actions are not forced into one generic section template.

This pass extracts donor intelligence. It does not prescribe a new VTKALL.

---

# 1. Evidence & provenance

The direct evidence consists of 66 screenshots covering:

```text
HOME
NAVBAR
HERO ANSWERS
HERO ACTIONS
HERO EXPERTS
SOLUTIONS — IT MANAGEMENT
USE CASES
PLANS
PARTNERSHIP
COMPANY
SCHEDULE DEMO
```

The supplied `solutions-itmanagement` and `use-cases` captures were explicitly taken at **reduced zoom** because of content volume. They are used only for macro composition, section order, density mode and broad grid topology. Exact typography, spacing, line length, card readability and native viewport density are not inferred from them.

Canonical raw-source manifest:

`source-archive/dayos/visual-review/DAYOS_VISUAL_SOURCE_MANIFEST_v1.0.md`

The public Dayos site was also inspected on 2026-08-14 to verify the current route/content families. Live-source evidence is time-sensitive and does not replace the screenshot record.

The supplied Refero-style reference, `tokens.json`, `variables.css`, `theme.css` and design reference are classified as **DERIVED / SECONDARY evidence**. They are useful for system hypotheses, not as proof of Dayos's official internal design system.

---

# 2. DONOR VISUAL RECOVERY

## 2.1 Home — 13 captures

### OBSERVED

The home route repeatedly changes visual state instead of stacking one homogeneous stream:

1. warm-gray hero: extreme display headline left + tactile 3D object right;
2. explanatory setup + black `AI / GAP / CLOSED` block;
3. full-black manifesto statement;
4. black product introduction with copy + concrete UI screenshot;
5. platform-family introduction using three 3D objects distributed across the width;
6. `ANSWERS / ACTIONS / EXPERTS` three-column taxonomy;
7. explicit black→white transition through a large rounded top edge;
8. wide split use-case card: copy left / visual right;
9. integration/back-office claim followed immediately by ecosystem proof;
10. highlighted partner/integration state;
11. departmental-solutions introduction;
12. multiple peer solution cards arranged horizontally with previous/next controls;
13. dual closing CTA (`Schedule a Demo` / `About Us`) followed by a clearly separate black footer.

The most important recovered behavior is `HOME-06`: the next white section is already visible, but it does **not** feel like the same failure recovered in VTKALL. The black three-column unit has reached a readable stopping point and the white area enters as an intentional rounded surface.

### INFERRED

The 3D objects are used as category/identity anchors, while actual UI imagery is introduced when the page needs to prove mechanism. The donor appears to vary the visual device according to the communication job.

### UNKNOWN

Animation timing, scroll triggers, responsive transforms, sticky behavior and the exact mechanics of carousel/highlight states are not established by static frames.

## 2.2 Navbar — 4 captures

### OBSERVED

A compact floating navigation pill holds the main route labels while the Dayos mark remains left and the primary demo CTA remains right. Platform, Solutions, Resources and Company reveal compact black dropdowns below their selected label without replacing the page context.

### INFERRED

The same disclosure pattern is likely implemented as a reusable global-nav family.

### UNKNOWN

Keyboard behavior, focus management, hover-vs-click trigger, mobile navigation and accessibility are not proven.

## 2.3 Hero Answers — 7 captures

### OBSERVED

The route uses a reusable platform-detail architecture:

```text
BLACK FAMILY OPENER
Everything that needs doing: Done
+ HERO ANSWERS route identity
        ↓
ROUNDED HANDOFF
        ↓
WHITE DETAIL BODY
local rail + dominant content field
        ↓
TALK TO YOUR ERP
copy + 3D identity object
        ↓
PRODUCT / CHAT UI PROOF
        ↓
METRIC / MOBILE PROOF
        ↓
FAQ
        ↓
DUAL CTA + FOOTER
```

A narrow local rail (`Hero Answers / FAQ`) uses little horizontal area while the main field remains wide enough for copy, 3D identity, product interface and metrics.

### INFERRED

The local rail may be sticky. The route family is likely designed around a shared shell with a capability-specific content payload.

### UNKNOWN

Stickiness, product-demo interactivity, FAQ expanded states, carousel controls and accessibility remain unverified.

## 2.4 Hero Actions — 6 captures

### OBSERVED

Hero Actions repeats the same family architecture rather than inventing a new page grammar. Its specific payload changes to:

- `TRANSFORM YOUR AI FROM ADVISOR TO EXECUTOR`;
- operational/workflow copy + 3D identity object;
- dark conversational/execution UI;
- `70% TIME SAVED` and `50% OF TASKS AUTOMATED` proof composition;
- FAQ.

The route demonstrates consistency without becoming content-identical.

## 2.5 Hero Experts — 4 captures

### OBSERVED

Hero Experts again retains the family shell, but the proof device changes because the proposition changes:

- `AI-FIRST SYSTEM IMPLEMENTATIONS AND MANAGED SERVICES`;
- local rail + wide main field;
- 3D identity object;
- two large operational/UI proof cards;
- FAQ.

This is useful evidence that the shell can stay stable while the proof mechanism changes.

## 2.6 Solutions — IT Management — 6 reduced-zoom captures

### OBSERVED

At macro level the route is structured as:

```text
BLACK SOLUTION OPENER
NOW BUSINESS FUNCTIONS FUNCTION BETTER
        ↓
LIGHT ROUNDED HANDOFF
        ↓
ALL YOUR QUESTIONS ANSWERED IN REAL-TIME
        ↓
DENSE MULTI-COLUMN QUESTION MATRIX
        ↓
SUPPORT-BUDGET / PRODUCT PROOF
        ↓
DARK MECHANISM / DEMO STATE
        ↓
ENTERPRISE-READY DEPLOYMENT PROOF
        ↓
SECURITY / TRUST GRID
        ↓
USE CASES
```

The question matrix is intentionally dense and uses the available width. The donor does not force an inventory of many peer questions into a narrow vertical stack.

Live inspection of sibling solution routes supports the user's observation that solution pages are a family with shared structural grammar; domain content changes while major page roles repeat.

### UNKNOWN / REDUCED-ZOOM BOUNDARY

Exact card size, typography, line length, spacing, native readability and breakpoint behavior are not judged from these captures.

## 2.7 Use Cases — 3 reduced-zoom captures

### OBSERVED

Use Cases deliberately abandons the narrative cadence used on Home:

- black library opener;
- light rounded handoff;
- narrow left filter column;
- dense two-column inventory;
- many repeated result cards with small differentiating visuals.

This is a critical control sample: **Dayos is not dogmatic about one narrative unit per viewport.** When the user's job is discovery/filtering, the page becomes an information-dense library.

### INFERRED

The filter rail may stay visible during scrolling, but the captures do not prove sticky positioning.

### UNKNOWN / REDUCED-ZOOM BOUNDARY

Exact readability, spacing, filter behavior, responsive transformation and accessibility are unknown.

## 2.8 Plans — 5 captures

### OBSERVED

The route shifts into a decision-oriented page mode:

1. black `PROVE IT IN 2 WEEKS` opener with local route choices;
2. three peer pricing/plan columns;
3. middle plan receives strong yellow emphasis;
4. proof/benefit strip;
5. rounded transition into `YEAR ONE. AND EVERY YEAR AFTER`;
6. **four connected horizontal steps:** `DIAGNOSE → SCOPE → BUILD → SHIP`;
7. FAQ;
8. closing CTA state.

`PLANS-04` is especially important for Ink-VK: the process is not rendered as four unrelated cards. A connector line and nodes encode order as geometry.

## 2.9 Partnership — 6 captures

### OBSERVED

The page follows a proof/decision/process narrative:

```text
ENTERPRISE PARTNER PROPOSITION + TRUST LOGOS
        ↓
RESULT METRICS
        ↓
FOUNDING PARTNER COMPARISON
        ↓
HOW IT WORKS
APPLY → LAUNCH PILOT → PROVE VALUE → SCALE
        ↓
FAQ
```

A narrow local rail gives within-page orientation. The comparison table uses an inverted black Dayos column to turn comparison into an argument rather than a neutral matrix.

`PARTNERSHIP-05` independently repeats the connected-sequence pattern found on Plans.

## 2.10 Company — 11 captures

### OBSERVED

Company adopts a long editorial mode:

- black manifesto hero;
- white rounded detail surface;
- narrow local orientation rail (`Mission / First Principles / Partners / The Team`);
- large mission statement;
- numbered First Principles expressed as `number + claim + explanation`;
- long-form thesis copy;
- partner proof;
- compact demographic/location/gender data graphics;
- team/company facts paired with real photography;
- wide recruitment card;
- Latest Updates;
- distinct footer.

The page proves that a coherent donor can use real photography, data graphics, numbered editorial statements and partner cards while still belonging to the same system.

### UNKNOWN

The large open area around Latest Updates cannot be judged as intentional or broken without additional state/content evidence.

## 2.11 Schedule Demo — 1 capture

### OBSERVED

A compact white rounded form is centered over a darkened/blurred page background. It presents one task, one vertical field sequence, one strong submit action and a close control.

### INFERRED

Visually it behaves like a modal/single-task overlay that removes competing page content while retaining page context behind it.

### UNKNOWN

Technical modal implementation, focus trapping, keyboard dismissal, validation and accessibility behavior are not proven.

---

# 3. Cross-page recovery

## Global shell

- stable global nav + primary CTA;
- compact disclosure rather than navigation takeover;
- clear dark footer state;
- repeated route closure grammar.

## Information hierarchy

A frequent narrative stack is:

```text
DOMINANT CLAIM
↓
SHORT EXPLANATION
↓
MECHANISM / EXAMPLE
↓
PROOF
↓
SECONDARY DETAIL / FAQ
↓
ACTION
```

But this is not universal. Library and comparison pages adopt different priorities.

## Viewport composition

Dayos does **not** prove a rule of `one section = 100vh`.

The stronger behavior is:

- protect one dominant narrative state at a time;
- preview the next state only through a deliberate transition;
- use horizontal compositions when peer information must be compared;
- allow multi-viewport sections when the information job is library, FAQ, principles, matrices or long-form proof.

Therefore:

> visual completeness is not the same as forcing every section into one viewport.

## Spatial system

Recurring patterns include:

- wide overall field;
- narrow reading column;
- copy + visual two-column splits;
- three-column peer groups;
- dense multi-column matrices;
- horizontal connected sequences;
- large-radius surface containers.

The secondary style extraction proposes a 1200px max width, 8px spacing base, 80px section gap and large radii. Those values remain **derived hypotheses**, not verified Dayos CSS.

## Typography

Typography acts as geometry: giant condensed uppercase displays create the visual mass of sections, while body text remains much smaller and narrower. The exact Suisse-family typography is Dayos/brand-specific and is not a transfer target.

## Visual devices by job

| Device | Communication job recovered |
|---|---|
| 3D tactile objects | category identity / conceptual anchor |
| Product/UI screenshots | mechanism and concrete proof |
| Metrics | magnitude / outcome |
| Ecosystem/security marks | trust context |
| Comparison table | explicit trade-off |
| Filter + card matrix | inventory discovery |
| Connected step line | temporal/process order |
| Real photography | people/company reality |
| Rounded surface state | narrative handoff |

## Motion / interaction confidence

**OBSERVED:** open dropdown states, prev/next controls, FAQ rows, selected/highlighted states, schedule form overlay state.

**INFERRED:** carousel navigation, hover/selected behavior, sticky local rails, modal mechanics.

**UNKNOWN:** scroll animations, reveal timing, parallax, sticky CSS, keyboard/focus mechanics and responsive transforms.

---

# 4. DONOR DESIGN DNA

## DNA-01 — Surface-state handoffs make section boundaries legible

Dayos repeatedly changes visual state through black/white/warm-gray surfaces and large rounded top edges. The transition itself is part of the narrative.

**Transferability:** `HIGH VALUE FOR VTKALL`

## DNA-02 — Controlled peeking is different from accidental leakage

The next section can be visible without creating confusion when the current narrative unit is already complete and the next state enters through an explicit transition device.

**Transferability:** `HIGH VALUE FOR VTKALL`

This directly refines the current VTKALL issue: the rule should not be `never show the next section`; it should be `never allow several unresolved narrative states to compete`.

## DNA-03 — Density follows purpose

Narrative sections can be spacious and singular; Use Cases and the solution question matrix are intentionally dense.

**Transferability:** `HIGH VALUE FOR VTKALL`

## DNA-04 — Wide visual field + narrow reading column

Readable prose stays narrow while the remaining width receives an actual job: UI, imagery, metrics, comparison, cards or process geometry.

**Transferability:** `HIGH VALUE FOR VTKALL`

## DNA-05 — Family shells create consistency without forcing identical content

Hero Answers / Actions / Experts share one recognizable family architecture. Solution pages share another.

**Transferability:** `HIGH VALUE FOR VTKALL`

## DNA-06 — Local orientation is separated from global navigation

Long detail pages use a small in-page rail without expanding the global nav.

**Transferability:** `CONTEXTUAL`

Useful only where VTKALL genuinely has a long within-page navigation problem.

## DNA-07 — Typography behaves as geometry

Display type creates structural mass and rhythm, not merely textual hierarchy.

**Transferability:** `CONTEXTUAL`

The principle is useful; exact all-caps condensed Dayos voice is not automatically VTKALL.

## DNA-08 — Surface contrast replaces decorative elevation

Hierarchy is created by canvas/card/inverted states and radius rather than heavy shadows/gradients.

**Transferability:** `CONTEXTUAL`

## DNA-09 — Proof sits directly behind the claim

Product UI, metrics, logos, security credentials, comparisons and data are integrated immediately after the proposition they support.

**Transferability:** `HIGH VALUE FOR VTKALL`

## DNA-10 — Visual device follows semantic job

3D identity, UI mechanism, metric magnitude, table comparison, library inventory, photography people, connected timeline sequence.

**Transferability:** `HIGH VALUE FOR VTKALL`

## DNA-11 — Sequential information becomes spatial sequence

Plans and Partnership independently render processes as connected ordered systems.

**Transferability:** `VERY HIGH FOR VTKALL`

This is the strongest external evidence supporting the existing `DEMONSTRATIONS-03` hypothesis.

## DNA-12 — Stable global frame + compact disclosure

The global navigation keeps its footprint while only the disclosed submenu changes.

**Transferability:** `CONTEXTUAL`

## DNA-13 — Page closure is an explicit state

The closing CTA composition and footer are separate, legible states.

**Transferability:** `HIGH VALUE FOR VTKALL`

## DNA-14 — Accent color has a job

Strong chromatic color is sparse and tied to selection/emphasis/action rather than constant decoration.

**Transferability:** `CONTEXTUAL`

The role discipline can survive; Dayos yellow/mint cannot be assumed.

## DNA-15 — Coherence does not require one page template

Home/Company, Hero detail, Solutions, Use Cases, Plans/Partnership and Schedule use different information architectures while sharing the same visual grammar.

**Transferability:** `HIGH VALUE FOR VTKALL`

---

# 5. Transferability audit against recovered VTKALL needs

| VTKALL recovered issue | Donor behavior | Why it works | Transfer |
|---|---|---|---|
| Section boundaries compete | Surface states + rounded handoffs + explicit closure | Transition is designed; current unit reaches a stopping point first | **HIGH** |
| Content clipping | Width is distributed by semantic role instead of one narrow stack | Copy, proof and peer items receive separate fields | **HIGH / CAUTION** |
| Excess vertical whitespace | Spacious narrative + dense library/matrix coexist | Density changes with purpose | **HIGH** |
| Horizontal space unused | UI, imagery, metrics, tables, timelines and card rows use the field | Narrow reading width does not mean unused viewport | **HIGH** |
| Weak process storytelling | Two independent connected four-step processes | Order is encoded spatially | **VERY HIGH** |
| Weak section transitions | Background state, top arcs, bands, closure | User perceives narrative state changes | **HIGH** |
| Content feels stacked | Purpose-specific page modes + claim→proof rhythm | Components serve the story instead of accumulating | **HIGH** |

A high transfer rating means the intelligence deserves to reach the later Replication / Transformation Contract. It does **not** approve copying Dayos.

---

# 6. Donor audit — do not become hypnotized

## KEEP AS INTELLIGENCE

- purpose-driven density;
- explicit state transitions;
- controlled peeking;
- family route contracts;
- claim→mechanism→proof rhythm;
- purpose-matched visual devices;
- connected process representation;
- explicit page closure.

## ADAPT

- local rails on genuinely long pages;
- compact global disclosures;
- horizontal browsing for peer categories;
- sparse semantic accent use;
- wide visual field + narrow reading column.

## QUESTION

- aggressive all-caps condensed typography at exact Dayos scale;
- repeated FAQ patterns;
- probable sticky rails;
- very dense matrices;
- dependence on 3D metaphor;
- dropdown/carousel/modal accessibility.

## REJECT

- exact Dayos palette;
- exact Dayos typography;
- Dayos proprietary 3D assets;
- Dayos UI screenshots;
- Dayos copy;
- partner-logo compositions as a clone;
- pixel-level geometry replication.

## NO EVIDENCE / UNKNOWN

- exact CSS implementation;
- exact motion system;
- responsive breakpoint behavior;
- sticky implementation;
- accessibility compliance;
- internal component architecture.

---

# 7. IP / provenance boundary

Do not reproduce directly without explicit rights:

- Dayos copy/logo/trademarks;
- third-party marks such as Oracle, SAP, Workday and ServiceNow;
- proprietary product screenshots;
- Dayos 3D illustrations/renders;
- company/team photography;
- proprietary font files;
- unique branded compositions as pixel-level clones.

The transferable subject is **structural intelligence**, not copyrighted visual expression.

---

# 8. CHINESE METHOD CANDIDATE EXTRACTION

```text
CANDIDATE-01  Design the section handoff, not only the section.
CANDIDATE-02  Controlled peeking is valid only after the current unit is complete.
CANDIDATE-03  Density follows the user's information job.
CANDIDATE-04  Keep reading columns narrow; give the wider field a real job.
CANDIDATE-05  Use route-family contracts for sibling pages.
CANDIDATE-06  Choose visual devices from semantic purpose.
CANDIDATE-07  Put proof directly behind the claim it supports.
CANDIDATE-08  Represent ordered processes as ordered spatial systems when useful.
CANDIDATE-09  Give route closure its own visual state before the footer.
CANDIDATE-10  Maintain a shared grammar while allowing multiple page modes.
```

## Strongest new external evidence for current VTKALL

`CANDIDATE-08` materially strengthens the earlier VTKALL `DEMONSTRATIONS-03` hypothesis.

Dayos gives two independent examples:

```text
Plans
DIAGNOSE → SCOPE → BUILD → SHIP

Partnership
APPLY → LAUNCH PILOT → PROVE VALUE → SCALE
```

This means the sequence hypothesis deserves to survive into the later transformation contract. It is still **not** approval of any exact VTKALL sequence layout.

---

# 9. Stop condition

```text
NO VTKALL REDESIGN
NO VTKALL COPY CHANGE
NO DAYOS CLONE
NO CSS IMPLEMENTATION
NO MOTION SPEC
NO COMPONENT BUILD
NO MAIN-BRANCH MODIFICATION
```

The next legitimate decision layer is a **Replication / Transformation Contract** deciding what survives, changes, is rejected, remains uniquely VTKALL, or must be created new.

## Review status

```text
66 / 66 captures reviewed
11 / 11 evidence bundles recovered
live route family checked
secondary style extraction classified
Donor Design DNA extracted
VTKALL transferability audited
IP/provenance boundary recorded
transformation NOT STARTED
```

**Dayos Chinese Method Donor Review v1.0: COMPLETE.**
