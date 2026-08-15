# Ink-VK — Campaign Operator Manual & Snapshot Protocol v1.0

**Status:** PROPOSED METHODOLOGY TOOLING  
**Derived from:** `INK-VK_FRAMEWORK_BASELINE_v1.0`  
**Suggested repository path:** `methodology/INK-VK_CAMPAIGN_OPERATOR_MANUAL_v1.0.md`

> **Chinese Method finds the DNA.  
> Ink makes it belong.  
> VK proves the transformation.  
> Memory improves the next campaign.**

---

# 0. PURPOSE OF THIS MANUAL

This document is the **human-operable manual** for applying Ink-VK repeatedly to a new entity.

It does not redefine the framework.

It operationalizes the frozen campaign spine:

```text
00 — FRAME
01 — RECOVER TARGET
02 — AUDIT TARGET
03 — FREEZE TARGET NON-REGRESSION
04 — EXTRACT TARGET SOUL
05 — FREEZE TARGET TRUTH
06 — SELECT REPLICATION MODE
07 — DEFINE TRANSFORMATION NEED

08 — MINE
09 — BUILD QUARRIES / SCREEN DONORS
10 — RECOVER DONOR
11 — DISSECT DONOR
12 — EXTRACT DNA + FIDELITY CONTRACT

13 — MAP TARGET × DONOR × SOUL
14 — TARGET-TRUTH / CAPACITY / DEPENDENCY GATE
15 — TARGET NON-REGRESSION GATE
16 — TRANSFORMATION CONTRACT
17 — APPLY INK
18 — DESIGN TARGET BLUEPRINT + COHERENCE / DESIGN FREEZE

19 — PLAN MIGRATION
20 — BUILD / MIGRATE

21 — DONOR PARITY
22 — SOUL INTEGRITY
23 — TARGET TRUTH / CLAIM / DEPENDENCY
24 — TARGET NON-REGRESSION
25 — MODE-AWARE VK

26 — EVIDENCE, MEMORY & FRAMEWORK LEARNING
```

The purpose of this manual is to answer, at every step:

```text
WHAT DO I NEED BEFORE STARTING?

WHAT DO I INSPECT?

WHAT DO I DO?

WHAT DO I RECORD?

WHAT EVIDENCE DO I PRESERVE?

WHAT DECISION AM I ALLOWED TO MAKE?

WHAT ARTIFACT BECOMES AUTHORITATIVE?

WHAT DOES THE GATE REQUIRE?

WHAT DOES THE CAMPAIGN SNAPSHOT LOOK LIKE AFTERWARD?

WHAT IS THE NEXT LEGITIMATE MOVE?
```

A future engineer should be able to apply Ink-VK without needing the conversation in which Ink-VK was invented.

---

# 1. WHAT INK-VK TRANSFORMS

Ink-VK may operate on any sufficiently describable TARGET.

Examples:

```text
website
application
software product
module
repository
architecture
workflow
operational system
service experience
design system
knowledge system
agent system
prompt system
business process
developer experience
content system
```

The evidence and artifacts vary by domain.

The control logic remains the same.

---

# 2. THE CORE MODEL

Every campaign transforms:

```text
TARGET REALITY
+
TARGET SOUL
+
TARGET TRUTH
+
TARGET NEED
+
DONOR INTELLIGENCE
+
EXPLICIT FIDELITY
+
CONTROLLED TRANSFORMATION
+
NON-REGRESSION
+
EVIDENCE
=
TARGET-OWNED RESULT
```

Operationally:

```text
🚁 DRONE
    ↓
🔪 KNIFE
    ↓
🖋 INK
    ↓
🛻 UTV
    ↓
🧪 VK
    ↓
🧠 MEMORY
```

Meaning:

```text
DRONE
understands the terrain.

KNIFE
separates useful anatomy from donor expression.

INK
re-authors intelligence around TARGET.

UTV
executes the frozen transformation in controlled slices.

VK
tests fidelity, Soul, truth, non-regression and provenance.

MEMORY
preserves what the next campaign can reuse.
```

---

# 3. FIRST LAW — TARGET BEFORE DONOR

Never begin an Ink-VK campaign with:

```text
Which site should we copy?
```

Begin with:

```text
What is TARGET?

What exists?

What works?

What hurts?

What must survive?

What is true?

What is missing?

What transformation is needed?
```

Only afterward do we search for external intelligence.

Therefore:

```text
TARGET
   ↓
NEED
   ↓
MINING
   ↓
DONOR
```

Not:

```text
DONOR
   ↓
FORCE TARGET INTO DONOR
```

---

# 4. AUTHORITY ORDER

Before performing any campaign work, recover authority from the repository.

Recommended authority order:

```text
1. FROZEN FRAMEWORK BASELINE

2. CURRENT CASE README / COMMANDER BOARD

3. FROZEN CASE CONTRACTS

4. DIRECT / RAW EVIDENCE

5. LIVE TARGET / LIVE DONOR

6. RECOVERED / EXTRACTED ARTIFACTS

7. INTERPRETATIONS

8. CHAT MEMORY
```

Chat memory may help locate knowledge.

It does not silently outrank repository authority.

---

# 5. EVIDENCE LANGUAGE

Every serious finding should be classified.

Use:

```text
OBSERVED
INFERRED
DECIDED
UNKNOWN
DEFERRED
```

Definitions:

### OBSERVED

Directly supported by evidence.

### INFERRED

Reasonable interpretation derived from observations.

### DECIDED

A conscious campaign decision made under authority.

### UNKNOWN

Insufficient evidence.

### DEFERRED

Known issue intentionally postponed under an explicit boundary.

Never write:

```text
INFERRED
```

as if it were:

```text
OBSERVED
```

---

# 6. EVIDENCE DEPTH

Where useful, use:

```text
Q0 — RAW CAPTURE / DIRECT ARTIFACT
Q1 — LIVE SOURCE / RUNTIME
Q2 — EXTRACTED SYSTEM
Q3 — RECOVERED TOPOLOGY
Q4 — INTERPRETATION
```

Example:

```text
Q0
PNG screenshot

Q1
live website observation

Q2
extracted CSS / route manifest

Q3
reconstructed page-family model

Q4
inference about why that page-family works
```

Higher interpretation does not erase lower evidence.

---

# 7. WHAT A SNAPSHOT MEANS

Every meaningful Ink-VK gate produces a **Campaign Snapshot**.

A snapshot is not merely a screenshot.

Ink-VK distinguishes:

```text
STATE SNAPSHOT
+
EVIDENCE SNAPSHOT
```

## State Snapshot

Records what the campaign currently knows and authorizes.

## Evidence Snapshot

Preserves the direct artifacts that justify that state.

Examples:

```text
screen capture
runtime observation
repository SHA
source file
transcript
diagram
JSON export
test result
video
interaction capture
comparison
raw source archive
```

The combination allows a later engineer to recover:

```text
WHAT WE SAW
+
WHAT WE THOUGHT
+
WHAT WE DECIDED
+
WHY WE WERE ALLOWED TO CONTINUE
```

---

# 8. STANDARD CAMPAIGN SNAPSHOT

Use this after every gate.

```text
INK-VK CAMPAIGN SNAPSHOT

SNAPSHOT ID:
DATE:

CASE ID:
TARGET:
TARGET TYPE:

PRIMARY DONOR:
SECONDARY SOURCES:

REPLICATION MODE:

CURRENT STEP:
STEP STATUS:
    OPEN
    IN PROGRESS
    GATE READY
    CLOSED
    REOPENED

CURRENT GATE:

INPUT AUTHORITIES:

NEW EVIDENCE:

OBSERVED:

INFERRED:

DECIDED:

UNKNOWN:

DEFERRED:

BLOCKING UNKNOWNS:

NON-BLOCKING UNKNOWNS:

OUTPUT AUTHORITY:

REOPEN CONDITIONS:

NEXT AUTHORIZED STEP:

BUILD AUTHORIZED:
    YES / NO

ACTIVE BRANCH:
ACTIVE PR:

EVIDENCE REFERENCES:

NOTES:
```

---

# 9. SNAPSHOT STORAGE

Do not redesign the canonical workspace merely to store snapshots.

Use:

```text
active/<case-id>/
├── README.md
├── brainstorm/
├── design/
├── arch/
├── plan/
├── build/
├── evidence/
│   └── snapshots/
└── deprecated/
```

Recommended snapshot names:

```text
S00_FRAME_v0.1.md
S01_TARGET_RECOVERY_v0.1.md
S02_TARGET_AUDIT_v0.1.md
...
S18_DESIGN_FREEZE_v1.0.md
...
S25_VK_RESULT_v1.0.md
S26_CAMPAIGN_CLOSURE_v1.0.md
```

The latest state should also be summarized in the case `README.md`.

---

# 10. CASE README — COMMANDER BOARD

Every active case should answer immediately:

```text
CASE ID

STATUS

TARGET

TARGET TYPE

TRANSFORMATION GOAL

TARGET AUTHORITY

PRIMARY DONOR

OTHER SOURCES

REPLICATION MODE

CURRENT STEP

CURRENT GATE

CURRENT AUTHORITIES

BLOCKING UNKNOWNS

NON-BLOCKING UNKNOWNS

ACTIVE BRANCH

ACTIVE PR

NEXT AUTHORIZED ACTION

BUILD AUTHORIZED?
```

If this information requires searching old chats:

```text
REPOSITORY CONTROL HAS FAILED.
```

---

# 11. ENTRY ALGORITHM

Do not restart Ink-VK blindly for an existing case.

Use:

```text
FRAME
  ↓
RECOVER REPOSITORY STATE
  ↓
IDENTIFY AUTHORITATIVE BRANCH / SHA
  ↓
READ CASE README
  ↓
RECOVER FROZEN AUTHORITIES
  ↓
VALIDATE FRESHNESS
  ↓
VALIDATE COMPLETENESS
  ↓
FIND FIRST UNRESOLVED GATE
  ↓
CONTINUE THERE
```

Rules:

```text
NO PREVIOUS EVIDENCE
→ start STEP 00.

VALID PREVIOUS EVIDENCE
→ reuse it.

STALE EVIDENCE
→ reopen affected gate.

CONTRADICTORY EVIDENCE
→ version the affected authority.

DIFFICULT NEXT STEP
→ NOT a reason to reopen previous gates.
```

---

# 12. PHASE A — DRONE / TARGET CONTROL

---

# STEP 00 — FRAME

## Mission

Define the campaign.

## Required input

At least:

```text
TARGET
TARGET OWNER / AUTHORITY
GENERAL GOAL
AVAILABLE EVIDENCE
```

Unknowns are acceptable.

Unbounded work is not.

## Operator procedure

Record:

```text
What is being transformed?

Why?

Who owns the decision?

What is inside scope?

What is outside scope?

What surfaces cannot be touched?

What evidence already exists?

What constraints are already known?

What output is expected?
```

Do not solve the target yet.

Do not choose a donor because it looks attractive.

## Evidence to preserve

```text
stakeholder request
original brief
repository location
public URLs
documents
captures
transcripts
known constraints
authority statement
```

## Output

```text
Migration Brief
+
Case README
+
S00_FRAME Snapshot
```

## Gate

You must be able to answer:

```text
WHAT ARE WE TRANSFORMING?

WHY?

WHO HAS AUTHORITY?

WHAT IS IN SCOPE?

WHAT IS CURRENTLY UNKNOWN?
```

## Common failure

```text
starting donor research
before defining the problem.
```

## Suggested repository area

```text
active/<case>/README.md
active/<case>/brainstorm/
active/<case>/evidence/snapshots/
```

## After snapshot

```text
CURRENT STEP        00 CLOSED
NEXT                01 RECOVER TARGET
BUILD               NO
DONOR REQUIRED      NO
```

---

# STEP 01 — RECOVER TARGET

## Mission

Understand what exists without redesigning it.

Question:

> What actually exists today?

## Operator procedure

For a website recover:

```text
routes
navigation
sections
copy
CTAs
forms
components
responsive states
assets
motion
states
information architecture
```

For software recover:

```text
modules
features
entities
data
APIs
roles
integrations
runtime paths
dependencies
repositories
deployment reality
```

For an operational system recover:

```text
actors
inputs
handoffs
records
ownership
authority
exceptions
outputs
current operating reality
```

## Important law

```text
RECOVERY ≠ AUDIT
```

During recovery:

```text
“This section exists.”
```

is valid.

```text
“This section is badly designed.”
```

belongs to STEP 02.

## Evidence to preserve

Whenever possible:

```text
raw screenshots
screen recordings
runtime observations
repository SHA
route manifests
API descriptions
architecture diagrams
data samples
stakeholder evidence
```

## Output

```text
Current Entity Recovery
+
AS-IS Map
+
S01_TARGET_RECOVERY Snapshot
```

## Gate

Important surfaces must be:

```text
RECOVERED
or
explicitly UNKNOWN.
```

Unknown does not automatically block progress.

Hidden unknown does.

## Common failure

Redesigning while discovering.

---

# STEP 02 — AUDIT TARGET

## Mission

Evaluate the recovered TARGET.

Question:

> How well does the current target perform its intended job?

## Classify

```text
STRENGTH
DEFECT
FRICTION
RISK
GAP
POSITIVE CONTROL
UNKNOWN
```

## Operator procedure

Ask:

```text
What already works?

What creates friction?

What contradicts the intended experience?

What is confusing?

What is unnecessarily complex?

What is absent?

What is valuable and must survive?

What appears accidental?

What cannot yet be evaluated?
```

Audit according to the target domain.

Do not replace case evidence with generic best practices.

## Output

```text
Target Audit
+
S02_TARGET_AUDIT Snapshot
```

## Gate

The campaign must know:

```text
WHY TRANSFORMATION IS NEEDED

AND

WHAT CURRENT VALUE ALREADY EXISTS.
```

## Common failure

Treating the target as entirely bad because a donor is more polished.

---

# STEP 03 — FREEZE TARGET NON-REGRESSION

## Mission

Protect existing value.

Question:

> What must the transformation never make worse?

## Convert findings into obligations

```text
MUST PRESERVE

MUST NOT RETURN

MUST VERIFY
```

Examples:

```text
working functionality
critical content
accessible navigation
business truth
known useful workflow
positive visual control
performance baseline
data integrity
SEO
security
trust mechanism
existing customer path
```

## Output

```text
Target Non-Regression Baseline
+
S03_NON_REGRESSION Snapshot
```

## Gate

Every critical known value has a protection rule.

## Common failure

Assuming:

```text
NEW = BETTER
```

or:

```text
DONOR-LIKE = BETTER
```

Neither is true automatically.

---

# STEP 04 — EXTRACT TARGET SOUL

## Mission

Define what makes the transformed entity belong to TARGET.

Soul is not decoration.

## Inspect

```text
mission
worldview
audience
business reality
operational reality
culture
voice
relationship model
trust model
proof discipline
technical character
domain language
symbols
emotional promise
constraints
identity
aspiration
```

Ask:

> If the logo disappeared, what should still make this feel unmistakably like TARGET?

## Separate

```text
SOUL

from

VISUAL EXPRESSION
```

Colors and fonts may express Soul.

They are not the entire Soul.

## Output

```text
Target Soul Contract
+
S04_SOUL Snapshot
```

## Gate

The campaign has target-owned principles strong enough to judge future donor intelligence.

## Common failure

Writing:

```text
Soul = logo + palette + font
```

---

# STEP 05 — FREEZE TARGET TRUTH

## Mission

Determine what TARGET is actually allowed to claim, render, activate or imply.

## Classify

```text
VERIFIED TRUE
SUPPORTED
INFERRED
ASPIRATIONAL
PLANNED
UNKNOWN
UNSUPPORTED
```

Truth dimensions may include:

```text
features
services
products
customers
case studies
metrics
team
integrations
technology
pricing
operations
data
evidence
capabilities
process
availability
institutional relationships
functional dependencies
rights
ownership
```

## Important laws

```text
DONOR CAPABILITY
≠
TARGET CAPABILITY
```

```text
DONOR CONTENT DEPTH
≠
TARGET CONTENT DEPTH
```

```text
DONOR PROOF
≠
TARGET PROOF
```

## Optional truth extensions

When relevant record:

### Content Capacity

```text
C0 — no supported content
C1 — one state / record
C2 — peer set
C3 — classifiable library
C4 — deep multi-state system
```

Law:

```text
DESIGN FOR FUTURE CAPACITY.
RENDER CURRENT TRUTH.
```

### Interaction Dependency

```text
D0 — presentation only
D1 — local state
D2 — validated local state
D3 — submission / transport
D4 — delivery / persistence
D5 — acknowledged downstream outcome
```

## Output

```text
Target Truth Baseline
+
S05_TARGET_TRUTH Snapshot
```

## Gate

The campaign knows the maximum truthful state it may design.

## Common failure

Making TARGET appear more mature merely because DONOR is richer.

---

# STEP 06 — SELECT REPLICATION MODE

## Mission

Declare how close the transformation is intentionally allowed to remain to DONOR intelligence.

## Modes

### R1 — PATTERN TRANSFER

Transfer abstract principles.

Low donor recognizability required.

### R2 — STRUCTURAL TRANSPOSITION

Transfer meaningful structures:

```text
information hierarchy
page families
workflow
component relationships
interaction sequence
navigation logic
```

Expression becomes target-owned.

### R3 — EXPERIENTIAL SOUL TRANSPOSITION

Preserve substantial experiential grammar where explicitly authorized:

```text
composition
rhythm
density
pacing
motion character
spatial behavior
transition logic
page-family grammar
interaction grammar
```

while replacing donor identity and meaning.

### R4 — AUTHORIZED IMPLEMENTATION REUSE

Overlay for direct reuse:

```text
code
assets
components
models
templates
libraries
content
implementation artifacts
```

Requires:

```text
rights
license
provenance
authorization
compatibility
```

## Modes may vary by layer

Example:

```text
STRUCTURE       R3
INTERACTION     R3
MOTION          R2
COPY            TARGET-OWNED
BRAND           TARGET-OWNED
CODE            NO R4
ASSETS          NO R4
```

## Output

```text
Replication Mode Contract
+
S06_REPLICATION_MODE Snapshot
```

## Gate

Fidelity is explicit.

No:

```text
“make it similar”
“copy the vibe”
“make it Dayos-like”
```

without contractual meaning.

---

# STEP 07 — DEFINE TRANSFORMATION NEED

## Mission

Convert target understanding into a mining specification.

We now know:

```text
TARGET REALITY
+
AUDIT
+
NON-REGRESSION
+
SOUL
+
TRUTH
```

Ask:

> What external intelligence do we actually need?

Example:

Not:

```text
Find a cool consultancy site.
```

But:

```text
Find strong examples of:

multi-route coherence
premium technical storytelling
progressive disclosure
high-density service explanation
semantic motion
operational-system visualization
```

## Output

```text
Transformation Need
+
Mining Brief
+
S07_TRANSFORMATION_NEED Snapshot
```

## Gate

The Drone knows what it is hunting for.

---

# MILESTONE SNAPSHOT A — TARGET CONTROL

After STEP 07, capture:

```text
MILESTONE: TARGET CONTROL

TARGET RECOVERED            YES / NO
TARGET AUDITED              YES / NO
NON-REGRESSION FROZEN       YES / NO
SOUL FROZEN                 YES / NO
TRUTH FROZEN                YES / NO
REPLICATION MODE            R1/R2/R3/R4
TRANSFORMATION NEED         FROZEN / OPEN

DONOR SELECTED?             NO / CANDIDATE / MANDATED
BLOCKING UNKNOWN            N

NEXT:
08 MINE
```

This is the point at which external hunting becomes evidence-driven.

---

# 13. PHASE B — DRONE + KNIFE / DONOR INTELLIGENCE

---

# STEP 08 — MINE

## Mission

Search the world for proven intelligence matching the Transformation Need.

Possible mining sites:

```text
websites
applications
GitHub
open source
products
design systems
technical documentation
papers
case studies
Figma
architecture references
workflow models
prompt systems
adjacent industries
competitors
historical systems
experimental work
```

## Operator rule

Do not immediately declare a donor.

Collect candidates.

## Output

```text
Mining Sites
+
source discovery records
+
S08_MINING Snapshot
```

---

# STEP 09 — BUILD QUARRIES / SCREEN DONORS

## Mission

Turn external discovery into organized evidence.

A quarry is:

> A structured body of potentially useful evidence.

It is not automatically a donor.

## For each serious candidate record

```text
SOURCE

SOURCE ROLE

WHY FOUND

TARGET NEED ADDRESSED

QUALITY

STRUCTURAL VALUE

BEHAVIORAL VALUE

EXPERIENTIAL VALUE

CONTENT COMPATIBILITY

TECHNICAL FEASIBILITY

PROVENANCE

RIGHTS BOUNDARY

RISKS

REJECTION REASON
```

## Classify

```text
PRIMARY DONOR
SECONDARY DONOR
PATTERN SOURCE
REFERENCE ONLY
REJECT
```

## Preserve rejected sources

They teach the mining process.

## Output

```text
Quarry Set
+
Donor Shortlist
+
Selection Rationale
+
S09_DONOR_SCREENING Snapshot
```

## Gate

A donor is selected consciously rather than aesthetically.

---

# STEP 10 — RECOVER DONOR

## Mission

Understand what the donor actually contains.

Again:

```text
RECOVERY ≠ DISSECTION
```

Recover as relevant:

```text
routes
screens
modules
components
states
content
information architecture
interaction
motion
responsive transformations
assets
technical implementation
data
dependencies
runtime behavior
business assumptions
```

## Capture raw evidence

Prefer:

```text
route-by-route
screen-by-screen
state-by-state
frame-by-frame
interaction-by-interaction
```

## Output

```text
Donor Recovery Map
+
Raw Donor Evidence
+
S10_DONOR_RECOVERY Snapshot
```

## Gate

Important donor behavior is either:

```text
RECOVERED
or
UNKNOWN.
```

---

# STEP 11 — DISSECT DONOR

## Mission

Use the Knife.

Question:

> What exactly is doing the useful work?

Stop treating a donor page as an indivisible template.

Decompose into jobs.

Examples:

```text
orientation
identity
decision
comparison
proof
process
trust
navigation
disclosure
conversion
status
continuity
exception handling
closure
```

For every major donor unit ask:

```text
What is visible?

What job is being performed?

Why does it work?

Is the effect structural?

Behavioral?

Semantic?

Aesthetic?

What assumptions does it contain?

What target truth would be required?

What breaks if copied literally?
```

## Important distinction

```text
DONOR JOB
≠
DONOR EXPRESSION
```

Example:

```text
EXPRESSION
rotating 3D globe

JOB
communicate interconnected global operations
```

## Output

```text
Donor Dissection
+
Job Ledger
+
S11_DONOR_DISSECTION Snapshot
```

---

# STEP 12 — EXTRACT DNA + FIDELITY CONTRACT

## Mission

Identify reusable intelligence beneath donor expression.

Each DNA record should contain:

```text
DNA ID

PATTERN

OBSERVED EXPRESSION

UNDERLYING JOB

WHY IT WORKS

REUSABLE PRINCIPLE

TRANSFER CONDITIONS

TARGET RELEVANCE

NON-TRANSFERABLE EXPRESSION

RISKS

CONFIDENCE
```

Then define fidelity.

Possible dispositions:

```text
MATCH

MATCH BEHAVIOR / RE-AUTHOR EXPRESSION

TRANSPOSE

REINTERPRET

TARGET-OWNED

OPTIONAL

FORBIDDEN

NOT APPLICABLE

UNKNOWN
```

## Critical test

Ask:

> If we remove DONOR colors, typography, copy, assets and brand, does a reusable principle remain?

If no:

It may be expression, not DNA.

## Output

```text
Donor DNA Catalogue
+
Fidelity Contract
+
Do-Not-Transfer Boundary
+
S12_DNA_FIDELITY Snapshot
```

---

# MILESTONE SNAPSHOT B — DONOR INTELLIGENCE

```text
MILESTONE: DONOR INTELLIGENCE

PRIMARY DONOR               FROZEN
SECONDARY SOURCES           RECORDED

DONOR RECOVERY              COMPLETE / BOUNDED
DONOR JOBS                  MAPPED
DNA                         EXTRACTED
FIDELITY                    FROZEN
DO-NOT-TRANSFER             FROZEN
RIGHTS / PROVENANCE         KNOWN / BOUNDED

BLOCKING UNKNOWN            N

NEXT:
13 TARGET × DONOR × SOUL
```

---

# 14. PHASE C — COLLISION + INK

Three systems now meet:

```text
TARGET
×
DONOR
×
SOUL
```

with:

```text
TRUTH
NON-REGRESSION
FIDELITY
CONSTRAINTS
```

---

# STEP 13 — MAP TARGET × DONOR × SOUL

## Mission

Decide whether each donor DNA actually belongs in this campaign.

For each DNA ask:

```text
What donor job does it perform?

What target problem does it address?

Does TARGET really have that problem?

Does TARGET Soul accept the principle?

Does Target Truth support it?

What target material would inhabit it?

What dependency would it require?

Would we still consider it useful
if DONOR disappeared tomorrow?
```

## Possible dispositions

```text
KEEP TARGET

ADAPT

REPLACE

REMOVE

INTRODUCE

REINTERPRET

MERGE

SPLIT

DEFER

REJECT
```

`INVENT` is not a valid method for filling an unsupported donor slot.

## Output

```text
Target × Donor × Soul Matrix
+
S13_COLLISION_MATRIX Snapshot
```

---

# STEP 14 — TARGET TRUTH / CAPACITY / DEPENDENCY GATE

## Mission

Prevent the proposed transformation from outrunning reality.

For every proposed element test:

### Truth

```text
Is it real?
```

### Capacity

```text
Is there enough real content/data
to justify this mechanism?
```

### Evidence scope

```text
Does this evidence actually belong
to TARGET and to the correct claim?
```

### Freshness

```text
Is the evidence current enough?
```

### Dependency

```text
Does TARGET possess the system required
to make this affordance truthful?
```

## Dispositions

```text
ADMIT
REDUCE
REFRAME
OMIT
DEFER
UNKNOWN
```

## Example

DONOR:

```text
40 case studies
```

TARGET:

```text
1 verified demonstration
```

Correct response:

```text
REDESIGN EXPERIENCE FOR C1 CAPACITY.
```

Incorrect response:

```text
INVENT 39 CASE STUDIES.
```

## Output

```text
Truth / Capacity / Dependency Gate
+
S14_TRUTH_CAPACITY Snapshot
```

---

# STEP 15 — TARGET NON-REGRESSION GATE

## Mission

Test every proposed transformation against STEP 03.

Ask:

```text
What useful capability disappears?

What becomes harder?

What content becomes less accessible?

What workflow weakens?

What known defect returns?

What trust mechanism disappears?

What business reality is oversimplified?
```

Rule:

```text
TARGET NON-REGRESSION
>
DONOR FIDELITY

unless authority explicitly changes
the protected baseline.
```

## Output

```text
Non-Regression Transformation Gate
+
S15_NON_REGRESSION_GATE Snapshot
```

---

# STEP 16 — TRANSFORMATION CONTRACT

## Mission

Freeze what is allowed to happen.

For each major unit record:

```text
TARGET UNIT

DONOR JOB

DONOR DNA

DECISION

TARGET-SIDE INTERPRETATION

TARGET TRUTH AUTHORITY

TARGET SOUL AUTHORITY

FIDELITY LEVEL

WHAT MAY TRANSFER

WHAT MUST NOT TRANSFER

DEPENDENCIES

RISKS

VALIDATION REQUIRED
```

Canonical actions:

```text
KEEP TARGET

PRESERVE DONOR DNA

ADAPT

TRANSPOSE

REINTERPRET

REPLACE

REMOVE

INTRODUCE

MERGE

SPLIT

DEFER

FORBIDDEN TO TRANSFER
```

## Output

```text
Transformation Contract
+
S16_TRANSFORMATION_CONTRACT Snapshot
```

## Gate

Future DESIGN may no longer ask:

```text
Should we copy this donor thing?
```

That decision is already governed.

---

# STEP 17 — APPLY INK

## Mission

Re-author donor intelligence until the meaning belongs to TARGET.

Equation:

```text
DONOR DNA
+
TARGET PROBLEM
+
TARGET SOUL
+
TARGET TRUTH
+
TARGET CONSTRAINTS
+
TARGET CAPACITY
+
NON-REGRESSION
=
TARGET-OWNED EXPRESSION
```

Ask:

> How would this principle behave if TARGET had invented it itself?

Ink may transform:

```text
meaning
terminology
visual semantics
interaction meaning
workflow
states
architecture
content
data ownership
proof
trust
symbols
motion semantics
domain language
```

## Ink pass test

Ask:

> If DONOR disappeared tomorrow, could we still defend this decision using TARGET reality and the Transformation Contract?

If no:

Ink is incomplete.

## Output

```text
Ink Specification
+
S17_INK Snapshot
```

---

# STEP 18 — DESIGN TARGET BLUEPRINT + COHERENCE / DESIGN FREEZE

## Mission

Design the complete TARGET-owned system before PLAN.

Depending on the domain define:

```text
information architecture
routes
screens
modules
flows
global shell
page/module families
states
visual system
interaction grammar
motion grammar
component system
responsive/adaptive rules
data flows
services
permissions
dependencies
fallbacks
error states
terminal states
proof/status grammar
architecture
```

## Coherence check

Ask:

```text
Does the system have one governing logic?

Are repeated patterns intentional?

Do different route/module families
have clear jobs?

Are signature devices semantically owned?

Does Soul survive everywhere?

Is Target Truth consistent everywhere?

Are multiple donors competing?

Did responsive behavior alter meaning?

Did optional future capability become
present-tense functionality?
```

## Concept-frame authority rule

A render or screenshot is evidence.

It is not automatically highest authority.

If conflict exists:

```text
FROZEN SEMANTIC CONTRACT
            >
SCREENSHOT LITERALISM
```

unless explicitly superseded.

## Unknown classification

Every remaining unknown becomes:

```text
FROZEN

BOUNDED / IMPLEMENTATION-SAFE

DEFERRED / OPTIONAL DEPENDENCY

BLOCKING UNKNOWN
```

## PLAN readiness

Requires:

```text
BLOCKING UNKNOWN = 0
```

Not:

```text
UNKNOWN = 0
```

## Output

```text
Consolidated Target Blueprint
+
Coherence Gate
+
Design Freeze
+
S18_DESIGN_FREEZE Snapshot
```

---

# MILESTONE SNAPSHOT C — TRANSFORMATION FREEZE

This is one of the most important snapshots.

```text
MILESTONE: DESIGN FREEZE

TARGET TRUTH                FROZEN
NON-REGRESSION              FROZEN
SOUL                        FROZEN
REPLICATION MODE            FROZEN

DONOR DNA                   FROZEN
FIDELITY                    FROZEN
TRANSFORMATION CONTRACT     FROZEN
INK                         SUFFICIENT
TARGET BLUEPRINT            FROZEN

BLOCKING DESIGN UNKNOWN     0

IMPLEMENTATION-SAFE         LISTED
DEFERRED                    LISTED

PLAN READY                  YES / NO
BUILD READY                 NO

NEXT:
19 PLAN MIGRATION
```

---

# 15. PHASE D — UTV / CONTROLLED MIGRATION

---

# STEP 19 — PLAN MIGRATION

## Mission

Convert the frozen blueprint into controlled executable slices.

The plan is not another design phase.

Each slice should contain:

```text
SLICE ID

MISSION

SCOPE

INPUT AUTHORITY

TARGET STATE

DEPENDENCIES

IMPLEMENTATION BOUNDARY

DO-NOT-CHANGE BOUNDARY

RISKS

ACCEPTANCE CRITERIA

ACCEPTANCE EVIDENCE

FAILURE CONDITION

ROLLBACK / RECOVERY
where applicable
```

Prefer slices that preserve semantic jobs.

Good:

```text
implement global navigation shell

implement Home operational-network hero

implement Method connected sequence

implement Start D0 presentation state
```

Bad:

```text
make site modern

add animations

refactor everything

copy donor header
```

## Output

```text
Controlled Migration Plan
+
S19_PLAN Snapshot
```

## Gate

BUILD should be able to execute without inventing product/design decisions.

---

# STEP 20 — BUILD / MIGRATE

## Mission

Execute exactly what the frozen system authorizes.

BUILD authority:

```text
TARGET TRUTH
+
TRANSFORMATION CONTRACT
+
INK SPECIFICATION
+
FROZEN BLUEPRINT
+
PLAN
```

Not:

```text
DONOR OPEN IN ANOTHER TAB
```

unless R4 explicitly authorizes implementation reuse.

## For every slice

Record:

```text
implementation started

commit / SHA

files touched

tests

visual/runtime evidence

known deviation

acceptance result

regressions

remaining debt
```

## Delta rule

If BUILD discovers a design-shaping contradiction:

```text
STOP SLICE
   ↓
RAISE DELTA
   ↓
IDENTIFY AFFECTED GATE
   ↓
REOPEN WITH JUSTIFICATION
   ↓
VERSION AUTHORITY
   ↓
RESUME
```

Do not improvise silently.

## Output

```text
Build Evidence
+
slice-level evidence
+
S20_BUILD Snapshot
```

---

# BUILD SLICE SNAPSHOT

For each slice use:

```text
INK-VK BUILD SLICE SNAPSHOT

CASE:
SLICE:

MISSION:

INPUT CONTRACTS:

FILES / MODULES TOUCHED:

IMPLEMENTATION:

EVIDENCE:

TESTS:

DONOR FIDELITY REQUIRED:

TRUTH BOUNDARY:

NON-REGRESSION BOUNDARY:

DEVIATIONS:

NEW UNKNOWN:

BLOCKING DELTA:

RESULT:
    PASS
    PARTIAL
    FAIL
    REOPEN REQUIRED

NEXT SLICE:
```

---

# 16. PHASE E — VK / PROVE THE REPLICANT

A successful BUILD is not yet a successful Ink-VK campaign.

Validation occurs in layers.

A pass in one layer cannot excuse failure in another.

---

# STEP 21 — DONOR PARITY

## Mission

Determine whether the implementation preserved the donor intelligence required by the Fidelity Contract.

This test is mode-aware.

### R1

Check abstract pattern transfer.

### R2

Check structural transposition.

### R3

Check contracted experiential grammar.

### R4

Check authorized implementation fidelity plus provenance.

Possible dimensions:

```text
structure
rhythm
density
pacing
interaction
motion
spatial behavior
page-family logic
component relationships
workflow
3D role
```

Only test dimensions the contract actually requires.

## Output

```text
Donor Parity Evidence
+
S21_PARITY Snapshot
```

---

# STEP 22 — SOUL INTEGRITY

## Mission

Determine whether the result still belongs to TARGET.

Check:

```text
identity
language
business meaning
operating reality
domain logic
trust
proof
visual semantics
interaction meaning
emotional character
technical character
relationship model
```

Ask:

> Can we explain the important decisions from TARGET rather than repeatedly saying “because DONOR does it”?

## Output

```text
Soul Integrity Result
+
S22_SOUL_INTEGRITY Snapshot
```

---

# STEP 23 — TARGET TRUTH / CLAIM / DEPENDENCY

## Mission

Search for truth inflation introduced during BUILD.

Audit for:

```text
invented claims
invented metrics
fake customers
unsupported capabilities
fake case studies
fictional integrations
placeholder data presented as real
prototype behavior presented as production
dependency not actually available
unsupported AI claims
incorrect institutional relationships
unauthorized assets
```

## Output

```text
Truth / Claim / Dependency Validation
+
S23_TRUTH_TEST Snapshot
```

---

# STEP 24 — TARGET NON-REGRESSION

## Mission

Compare the final result against STEP 03.

Validate relevant:

```text
functionality
content
navigation
responsive behavior
accessibility
performance
SEO
security
data integrity
workflow
business capability
trust
positive controls
known prior defects
```

## Output

```text
Non-Regression Validation
+
S24_NON_REGRESSION_TEST Snapshot
```

---

# STEP 25 — MODE-AWARE VK

## Mission

Run the final transformation interrogation.

VK combines:

```text
DONOR FIDELITY

SOUL INTEGRITY

TARGET TRUTH

TARGET NON-REGRESSION

PROVENANCE

RIGHTS

SYSTEM COHERENCE

IMPLEMENTATION QUALITY

REPLICATION MODE
```

The final question is not simply:

> Does it resemble DONOR?

For R2/R3, resemblance may be intentional.

The question is:

> Did we preserve exactly the donor intelligence and fidelity explicitly authorized while replacing donor identity, unsupported assumptions and donor-specific meaning with TARGET Soul, TARGET Truth and TARGET-owned expression?

Possible result:

```text
PASS

FAIL — DONOR FIDELITY

FAIL — SOUL

FAIL — TRUTH

FAIL — NON-REGRESSION

FAIL — PROVENANCE

LOCAL PASS / GLOBAL FAIL

NOT TESTED
```

## Output

```text
Mode-Aware VK Result
+
S25_VK_RESULT Snapshot
```

---

# MILESTONE SNAPSHOT D — VK CLOSURE

```text
MILESTONE: VK

DONOR PARITY             PASS / FAIL
SOUL INTEGRITY           PASS / FAIL
TARGET TRUTH             PASS / FAIL
NON-REGRESSION           PASS / FAIL
PROVENANCE               PASS / FAIL
SYSTEM COHERENCE         PASS / FAIL

REPLICATION MODE         R?

GLOBAL VK RESULT         PASS / FAIL

RESIDUAL DEBT:

REOPEN REQUIRED:
    NO
    or STEP XX

NEXT:
26 MEMORY
```

---

# 17. PHASE F — MEMORY

---

# STEP 26 — EVIDENCE, MEMORY & FRAMEWORK LEARNING

## Mission

Make the next campaign stronger.

A finished case must leave behind more than a delivered product.

Capture:

```text
TARGET before state

TARGET after state

target evidence

donor evidence

quarries

rejected sources

selection rationale

DNA extracted

DNA rejected

fidelity decisions

truth decisions

non-regression decisions

Transformation Contract

Ink decisions

blueprints

PLAN

implementation evidence

validation results

VK result

failures

unexpected discoveries

residual debt

future capability

framework weaknesses

framework opportunities
```

## Separate two knowledge classes

```text
CASE-SPECIFIC KNOWLEDGE

FRAMEWORK-GENERIC KNOWLEDGE
```

Do not contaminate Foundation with one-off case decisions.

## Framework learning classification

Use:

```text
CASE-SPECIFIC

VALIDATED BY ONE CASE

CROSS-CASE CANDIDATE

READY FOR FOUNDATION REVIEW

ADOPTED FOUNDATION RULE
```

## Promotion law

Do not change Ink-VK because:

```text
we had an interesting idea.
```

Change it because:

```text
CASE EVIDENCE
revealed
A REUSABLE FRAMEWORK DELTA.
```

Process:

```text
OBSERVE
  ↓
DOCUMENT
  ↓
VALIDATE
  ↓
COMPARE ACROSS CASES
  ↓
GENERALIZE
  ↓
VERSION FRAMEWORK
```

## Output

```text
Campaign Closure Ledger
+
Framework Learning Ledger
+
S26_CAMPAIGN_CLOSURE Snapshot
```

---

# 18. FINAL CAMPAIGN SNAPSHOT

Every completed campaign should be recoverable from this record.

```text
INK-VK FINAL CAMPAIGN SNAPSHOT

CASE ID:

TARGET:

TARGET TYPE:

PRIMARY DONOR:

OTHER SOURCES:

REPLICATION MODE:

ORIGINAL TARGET STATE:

TRANSFORMATION GOAL:

FINAL TARGET STATE:

TARGET SOUL AUTHORITY:

TARGET TRUTH AUTHORITY:

NON-REGRESSION AUTHORITY:

DONOR DNA AUTHORITY:

FIDELITY AUTHORITY:

TRANSFORMATION CONTRACT:

INK AUTHORITY:

BLUEPRINT AUTHORITY:

PLAN AUTHORITY:

BUILD SHAS:

DONOR PARITY:

SOUL INTEGRITY:

TARGET TRUTH TEST:

NON-REGRESSION TEST:

PROVENANCE:

VK RESULT:

RESIDUAL DEBT:

DEFERRED CAPABILITIES:

CASE-SPECIFIC LEARNINGS:

FRAMEWORK CANDIDATES:

ACTIVE / FINAL PR:

CASE STATUS:
    COMPLETE
    COMPLETE WITH DEBT
    REOPEN REQUIRED

BUILD AUTHORIZED:
    N/A — BUILD COMPLETE

NEXT ACTION:
    NONE
    or
    FRAMEWORK REVIEW
```

---

# 19. MAJOR SNAPSHOTS — FAST NAVIGATION

Although every step receives a snapshot, operators should treat these as the major campaign photographs:

```text
M0 — FRAME
STEP 00

M1 — TARGET CONTROL
after STEP 07

M2 — DONOR INTELLIGENCE
after STEP 12

M3 — TRANSFORMATION / DESIGN FREEZE
after STEP 18

M4 — BUILD COMPLETE
after STEP 20

M5 — VK
after STEP 25

M6 — MEMORY / CLOSURE
after STEP 26
```

A future operator should normally be able to reconstruct the campaign primarily from:

```text
CASE README
+
M0
+
M1
+
M2
+
M3
+
M4
+
M5
+
M6
+
their linked authorities
```

---

# 20. GATE REOPENING

A gate is not reopened because:

```text
the next step is difficult

someone has a new aesthetic idea

BUILD would be easier another way

the donor contains an attractive feature
```

Valid reopening triggers include:

```text
new contradictory evidence

target authority changed

business truth changed

dependency changed

claim invalidated

source rights changed

blocking unknown misclassified

BUILD exposed genuine structural contradiction

VK exposed transformation defect
```

Every reopening record must contain:

```text
REOPENED STEP

OLD AUTHORITY

NEW EVIDENCE

WHY OLD AUTHORITY IS INSUFFICIENT

AFFECTED DOWNSTREAM CONTRACTS

NEW DECISION

NEW VERSION

NEW GATE RESULT
```

Never silently overwrite history.

---

# 21. BUILD AUTHORIZATION RULE

At every snapshot include:

```text
BUILD AUTHORIZED?
```

Default:

```text
NO
```

It changes to:

```text
YES
```

only when:

```text
TRANSFORMATION CONTRACT     FROZEN

INK                         SUFFICIENT

TARGET BLUEPRINT            FROZEN

BLOCKING UNKNOWN            0

PLAN                        APPROVED / AUTHORIZED
```

Then BUILD executes.

BUILD does not discover the product.

---

# 22. FAST PATH

Ink-VK permits small campaigns.

It does not permit uncontrolled campaigns.

For small cases multiple STEP outputs may live in one document.

Example:

```text
TARGET_CONTROL_v1.0.md

may contain:

01 Recovery
02 Audit
03 Non-Regression
04 Soul
05 Truth
```

But the document must still make each decision independently recoverable.

Therefore:

```text
FEWER FILES
≠
FEWER GATES
```

Compression is permitted.

Control removal is not.

---

# 23. MULTI-DONOR CAMPAIGNS

If multiple donors are involved, each source gets a role.

```text
PRIMARY DONOR

SECONDARY DONOR

PATTERN SOURCE

REFERENCE ONLY
```

Never create a hybrid without source ownership.

For each important job ask:

```text
WHICH SOURCE OWNS THIS INTELLIGENCE?

ARE TWO SOURCES COMPETING?

WHICH CONTRACT WINS?

CAN TARGET JUSTIFY THE FINAL RESULT
INDEPENDENTLY?
```

STEP 18 must perform a source-coherence audit.

---

# 24. DONOR RIGHTS / PROVENANCE

Public accessibility does not equal reuse authority.

Separate:

```text
STUDY

PATTERN EXTRACTION

REIMPLEMENTATION

DIRECT CODE REUSE

DIRECT ASSET REUSE

DIRECT COPY REUSE
```

Direct reuse requires R4 evidence.

Never infer R4 from:

```text
visual similarity

public URL

browser access

open repository visibility
```

Preserve:

```text
source
license
ownership
authorization
attribution requirement
compatibility
transformation history
```

---

# 25. ANTI-CLONE BOUNDARY

Ink-VK is not governed by:

```text
make it look different enough.
```

The stronger rules are:

```text
DONOR IDENTITY
must not silently become
TARGET IDENTITY.

DONOR CLAIMS
must not become
TARGET CLAIMS.

DONOR PROOF
must not become
TARGET PROOF.

DONOR CONTENT
must not become
TARGET CONTENT
without truth and rights.

DONOR IMPLEMENTATION
must not be reused
without authorization.

DONOR DNA
may be learned and transformed
according to the Fidelity Contract.
```

For R3:

```text
similar experiential grammar
may be intentional.

different target Soul
remains mandatory.
```

---

# 26. THE FINAL VK QUESTION

At the end of every campaign ask:

> If the donor disappeared tomorrow, could we still defend every major decision in the transformed entity using TARGET needs, TARGET Soul, TARGET Truth, protected non-regression obligations, extracted reusable intelligence, and the explicit Transformation Contract?

If:

```text
YES
```

Ink succeeded.

If:

```text
NO — primarily because DONOR did it
```

Ink is incomplete.

---

# 27. REPOSITORY GOVERNANCE

Meaningful Ink-VK knowledge must not remain exclusively in chat.

Rules:

```text
DO NOT DELETE MEANINGFUL HISTORY.

VERSION MATERIAL ITERATIONS.

DO NOT SILENTLY REWRITE FROZEN BASELINES.

KEEP VALID OLDER VERSIONS.

USE deprecated/
ONLY FOR EXPLICITLY INVALIDATED DIRECTIONS.

PRESERVE PROVENANCE.

PRESERVE RAW EVIDENCE.

SEPARATE OBSERVATION FROM INFERENCE.

SEPARATE INFERENCE FROM DECISION.

SEPARATE DONOR FROM TARGET.

SEPARATE CASE KNOWLEDGE
FROM FRAMEWORK KNOWLEDGE.
```

---

# 28. BRANCH / PR PROCEDURE

Before writing:

```text
1. Identify repository.

2. Identify actual authoritative branch / SHA.

3. Do not assume main contains the newest knowledge.

4. Create / continue explicit working branch.

5. Record parent branch if work is stacked.

6. Commit serious artifacts meaningfully.

7. Open / update PR.

8. Leave merge authority to the authorized human owner.
```

`main` is not an experimentation surface.

---

# 29. REPOSITORY UPDATE PROCEDURE FOR THIS MANUAL

This artifact should be added without changing the frozen 00–26 framework.

Suggested file:

```text
methodology/
└── INK-VK_CAMPAIGN_OPERATOR_MANUAL_v1.0.md
```

Then add it to the existing new-campaign authority list alongside:

```text
INK-VK_CASE_WORKSPACE_CONTRACT_v1.0

INK-VK_TACTICAL_PLAYBOOK_v1.0

INK-VK_CAMPAIGN_KICKSTART_TEMPLATE_v1.0
```

Recommended authority stack for a new case:

```text
INK-VK_FRAMEWORK_BASELINE_v1.0
        ↓
INK-VK_MIGRATION_FLOW_v1.0
        ↓
INK-VK_CASE_WORKSPACE_CONTRACT_v1.0
        ↓
INK-VK_CAMPAIGN_OPERATOR_MANUAL_v1.0
        ↓
INK-VK_TACTICAL_PLAYBOOK_v1.0
        ↓
INK-VK_CAMPAIGN_KICKSTART_TEMPLATE_v1.0
        ↓
CASE-SPECIFIC EVIDENCE
```

This manual does **not** supersede any of those artifacts.

Its job is different:

```text
FRAMEWORK BASELINE
defines the law.

MIGRATION FLOW
defines the sequence.

WORKSPACE CONTRACT
defines governance.

OPERATOR MANUAL
defines repeatable execution + snapshots.

TACTICAL PLAYBOOK
defines field behavior.

KICKSTART
bootstraps a conversation/campaign.
```

---

# 30. RECOMMENDED COMMIT

Suggested commit:

```text
docs(methodology): add Ink-VK campaign operator manual and snapshot protocol
```

Recommended PR purpose:

```text
Operationalize Framework Baseline v1.0
without changing the canonical 00–26 campaign spine.

Adds a repeatable human execution manual,
per-step procedure,
state/evidence snapshot protocol,
major campaign checkpoints,
re-entry rules,
gate reopening rules,
and repository handoff discipline.
```

---

# 31. STARTING A NEW ENTITY — MINIMUM PROCEDURE

When a new TARGET arrives:

```text
1. Recover Framework Baseline.

2. Recover actual repository authority.

3. Create case ID.

4. Create case workspace.

5. Create case README.

6. Execute STEP 00.

7. Capture S00.

8. Recover TARGET.

9. Audit TARGET.

10. Protect non-regression.

11. Extract Soul.

12. Freeze Truth.

13. Select fidelity.

14. Define Transformation Need.

15. Capture TARGET CONTROL snapshot.

16. Mine.

17. Build quarries.

18. Select donor.

19. Recover donor.

20. Dissect donor.

21. Extract DNA.

22. Freeze Fidelity.

23. Capture DONOR INTELLIGENCE snapshot.

24. Map Target × Donor × Soul.

25. Run truth/capacity/dependency gate.

26. Run non-regression gate.

27. Freeze Transformation Contract.

28. Apply Ink.

29. Design complete Target Blueprint.

30. Close blocking unknowns.

31. Capture DESIGN FREEZE snapshot.

32. Build migration PLAN.

33. Authorize BUILD.

34. Build in controlled slices.

35. Capture slice evidence.

36. Capture BUILD COMPLETE snapshot.

37. Run Donor Parity.

38. Run Soul Integrity.

39. Run Truth / Claim / Dependency.

40. Run Non-Regression.

41. Run Mode-Aware VK.

42. Capture VK snapshot.

43. Close campaign evidence.

44. Separate case learning from framework learning.

45. Promote only proven reusable deltas.

46. Capture FINAL MEMORY snapshot.

47. Update repository authority pointers.

48. Close or hand off campaign.
```

---

# 32. THE SIMPLE VERSION TO REMEMBER

When the 00–26 numbers become too detailed, remember:

```text
TARGET
  ↓
🚁 KNOW THE TERRAIN
  ↓
PROTECT TRUTH / SOUL / VALUE
  ↓
DEFINE THE NEED
  ↓
🚁 HUNT INTELLIGENCE
  ↓
🔪 DISSECT THE DONOR
  ↓
EXTRACT DNA
  ↓
DECLARE FIDELITY
  ↓
COLLIDE TARGET × DONOR × SOUL
  ↓
FREEZE TRANSFORMATION
  ↓
🖋 MAKE IT BELONG
  ↓
FREEZE BLUEPRINT
  ↓
PLAN
  ↓
🛻 BUILD IN SLICES
  ↓
🧪 INTERROGATE RESULT
  ↓
PROVE TRUTH + SOUL + FIDELITY
  ↓
🧠 RECORD MEMORY
  ↓
BETTER NEXT CAMPAIGN
```

---

# 33. OPERATOR DOCTRINE

We do not hunt appearances.

We hunt intelligence.

We recover before judging.

We judge before mining.

We mine before selecting.

We dissect before transforming.

We declare fidelity instead of speaking vaguely about similarity.

We protect TARGET before introducing DONOR.

We never use donor richness as permission to invent target truth.

We do not let static renders silently outrank frozen semantic contracts.

We do not let BUILD redesign the transformation.

We do not require false precision when an unknown is implementation-safe.

We do require:

```text
BLOCKING UNKNOWN = 0
```

before PLAN becomes BUILD authority.

We test donor fidelity.

We test Soul.

We test Truth.

We test Non-Regression.

We preserve provenance.

We preserve history.

We leave snapshots.

We leave evidence.

We leave the repository capable of continuing without chat memory.

And every completed campaign must make the next Ink-VK campaign stronger.

---

# INK-VK

> **DRONE knows the terrain.  
> KNIFE exposes the anatomy.  
> INK makes the intelligence belong.  
> UTV carries only frozen authority.  
> VK interrogates the result.  
> MEMORY prevents us from relearning the same lesson twice.**

**A campaign is repeatable only when its state, evidence, authority, gates, decisions, and next legitimate move can be recovered from the repository itself.**