# Ink-VK — Interaction Dependency Truth Gate v0.1

**Status:** PROPOSED / FOUNDATION ITERATION  
**Date:** 2026-08-14  
**Learning source:** VTKALL Start × Dayos Schedule Demo  
**Applies to:** interactive donor jobs and target states  
**Boundary:** contextual gate inside Target Truth; no new macro phase

---

# 1. Why this gate exists

Target Truth originally focused primarily on content and claims.

Interactive surfaces expose another kind of truth:

```text
A CONTROL IS A CLAIM ABOUT CAPABILITY.
```

Examples:

```text
editable input
→ claims user state can be entered

validation error
→ claims a validation contract exists

submit button
→ claims a transport action exists

success message
→ claims an outcome occurred

calendar picker
→ may claim real availability exists

login form
→ claims an authentication path exists

upload control
→ claims file intake exists
```

A donor may contain convincing interaction chrome even when the target has none of the dependencies required to make that interaction real.

Therefore Ink-VK needs a reusable dependency-aware truth test.

---

# 2. Governing rules

> **Visible controls do not prove operational capability.**

> **Transfer interaction choreography only up to the highest target dependency state that is actually supported.**

> **Functional parity requires dependency closure, not merely visual parity.**

And:

> **A success state is a claim about a real effect, not decorative reassurance.**

---

# 3. Relationship to existing Ink-VK gates

This is not a new universal authority.

It refines:

```text
TARGET TRUTH
+
UNKNOWN BOUNDARY
```

Existing authorities remain:

```text
Donor Fidelity
Donor Job Decomposition
Target Soul
Target Truth
Target Capacity
Target Non-Regression
Unknown Boundary
```

Interaction Dependency Truth answers:

> What functional state does this affordance imply, and are the dependencies required for that state actually proven?

---

# 4. Interaction dependency ladder

The ladder describes the deepest functional state that is currently supported.

It is not a product maturity score.

## D0 — Presentation / schema only

The target can truthfully show:

```text
labels
structure
example states
preparation guidance
read-only preview
```

but does not accept or act on user data.

Examples:

```text
future intake schema
read-only checkout preview
sample booking fields
```

---

## D1 — Local interactive state

The target can accept/change state locally.

Examples:

```text
typing into an input
opening a local disclosure
selecting an option
client-only configuration
```

This does not imply persistence or submission.

---

## D2 — Validated local state

The target has a real validation contract.

Examples:

```text
required fields
format validation
business-rule validation
local error state
```

The rules must be target-supported.

Donor error copy cannot invent target policy.

---

## D3 — Submission / transport

A real action can leave the local UI boundary.

Examples:

```text
server action
API request
webhook
email transport
form-provider submission
```

A visible enabled submit action normally implies at least D3.

---

## D4 — Delivery / persistence / integration

The target has evidence that submitted information reaches an approved destination or durable state.

Examples:

```text
CRM lead created
email delivered to approved inbox
record persisted
workflow queued
calendar reservation created
```

Transport alone does not prove D4.

---

## D5 — Acknowledged downstream outcome

The target can verify the result it communicates to the user.

Examples:

```text
request received
booking confirmed
payment accepted
file stored
lead created
message delivered
```

A D5 success message must correspond to a proven effect.

---

# 5. The ladder is a ceiling, not a forced sequence

Some interactions do not need every state.

Example:

```text
accordion
```

may stop at D1.

A static configurator preview may stop at D0.

A local calculator may reach D2 without any D3 transport.

The rule is:

```text
RENDER ONLY THE STATES
THE TARGET ACTUALLY SUPPORTS
```

---

# 6. Affordance Claim Ledger

For each meaningful interactive donor element, record:

```text
AFFORDANCE ID
DONOR ELEMENT
DONOR OBSERVED STATE
DONOR FUNCTION CONFIDENCE
TARGET USER JOB
IMPLIED USER PROMISE
REQUIRED DEPENDENCY LEVEL
TARGET CURRENT LEVEL
DEPENDENCIES
TRUTH EVIDENCE
ALLOWED RENDERING
FORBIDDEN RENDERING
PROMOTION TRIGGER
UNKNOWN
```

This is the primary reusable artifact for interactive mappings.

---

# 7. Donor observed state vs donor actual function

Ink-VK must not overclaim donor behavior either.

Example:

```text
OBSERVED
form + submit button

UNKNOWN
whether backend succeeds
whether validation exists
whether keyboard/focus behavior is correct
```

Therefore record separately:

```text
DONOR VISUAL STATE
DONOR VERIFIED BEHAVIOR
DONOR INFERRED BEHAVIOR
DONOR UNKNOWN
```

A screenshot of a submit button proves only that the donor presents a submit affordance.

It does not prove transport or delivery.

---

# 8. Functional anti-smuggling invariant

A visual donor match cannot authorize missing dependencies.

```text
FORM VISUAL MATCH
≠ SUBMISSION AUTHORIZATION

CALENDAR VISUAL MATCH
≠ AVAILABILITY AUTHORIZATION

LOGIN FORM MATCH
≠ AUTHENTICATION AUTHORIZATION

UPLOAD CONTROL MATCH
≠ STORAGE AUTHORIZATION

CHECKOUT MATCH
≠ PAYMENT AUTHORIZATION

SUCCESS SCREEN MATCH
≠ OUTCOME AUTHORIZATION
```

This extends the existing Ink-VK anti-smuggling rules.

---

# 9. Dependency closure

For an affordance to be activated, all dependencies required by its implied promise must be closed.

Example:

```text
SUBMIT REQUEST
```

may require:

```text
editable inputs
validation contract
transport endpoint
destination
privacy/data handling decision
failure behavior
success criterion
```

If the system has only:

```text
visual fields
```

then:

```text
SUBMIT → DEFER / OMIT
```

---

# 10. Enabled vs disabled controls

A disabled control is still communication.

It may be valid if:

```text
its unavailable state has a real target job
+
reason is understandable
+
future capability is not misrepresented as imminent/guaranteed
```

Do not use disabled controls merely to preserve donor geometry.

A dead button that looks enabled is always invalid.

---

# 11. Local-only interaction

Ink-VK may sometimes preserve interaction feel without external side effects.

Examples:

```text
editable preparation worksheet
local calculator
client-side preview
configuration sandbox
```

But the target must clearly establish the local-only nature when users could reasonably infer persistence/submission.

Rule:

> **Local interactivity may be rich; external effect claims must remain explicit.**

---

# 12. Success-state integrity

Never render a success state because the donor has one.

Required fields:

```text
SUCCESS CLAIM
TRIGGER
VERIFIABLE EFFECT
SOURCE OF CONFIRMATION
FAILURE ALTERNATIVE
```

If these are unknown:

```text
SUCCESS STATE → DEFER
```

Examples of invalid states:

```text
"Request received"
without receipt evidence

"Booking confirmed"
without reservation creation

"Message sent"
without delivery/queue evidence
```

---

# 13. Validation-state integrity

A donor may display errors, required markers, warnings, or helper text.

Transfer only when the target has real rules.

For each validation:

```text
FIELD
RULE
WHY RULE EXISTS
SOURCE
ERROR STATE
RECOVERY PATH
```

No guessed policy.

---

# 14. Scheduling / availability special case

Scheduling UI creates particularly strong expectations.

A date/time selector may imply:

```text
availability source
resource/calendar binding
time zone handling
reservation semantics
conflict handling
confirmation state
```

If those do not exist:

```text
SCHEDULE / BOOK UI → OMIT / REFRAME
```

A donor called `Schedule Demo` does not force the target to support scheduling.

---

# 15. Forms special case

For forms, distinguish:

```text
FIELD SCHEMA
EDITABLE INPUT
VALIDATION
SUBMISSION
DELIVERY
ACKNOWLEDGEMENT
```

These are separate evidence states.

A target may possess only the first.

That still justifies a preparation/intake-information experience.

---

# 16. Authentication special case

A login/signup donor state requires proof of:

```text
identity system
credential/session mechanism
authorization boundary
failure/recovery behavior
```

Do not create a login shell that implies an account system unless the target actually has one, except when clearly labeled as non-operational prototype evidence.

---

# 17. Search special case

A search box implies:

```text
searchable corpus
query execution
result contract
empty/error states
```

A search field with no target corpus is decorative state complexity.

Content Capacity applies together with Interaction Dependency Truth.

---

# 18. Relationship with Content Capacity

Capacity asks:

```text
IS THERE ENOUGH REAL CONTENT/STATE
TO JUSTIFY THE MECHANISM?
```

Dependency Truth asks:

```text
DOES THE SYSTEM ACTUALLY SUPPORT
THE FUNCTION IMPLIED BY THE MECHANISM?
```

Example:

```text
100 real case records
→ capacity supports search

but no search index / query mechanism
→ dependency truth does not support active search
```

Both gates must pass.

---

# 19. Relationship with Donor Job Decomposition

Donor job decomposition identifies interactive jobs such as:

```text
conversion
navigation
disclosure
search
submission
scheduling
selection
configuration
```

Interaction Dependency Truth determines how deeply each can transfer.

---

# 20. Relationship with Non-Regression

Even a truthful interaction may reintroduce known UX defects.

Example:

```text
true intake fields
+
cramped clipped form
=
truth pass / non-regression fail
```

Therefore both remain independent.

---

# 21. R3 functional fidelity rule

For R3:

```text
MATCH VERIFIED DONOR INTERACTION EXPERIENCE
WHERE TARGET DEPENDENCIES SUPPORT IT
```

When target capability is shallower:

```text
PRESERVE
focus
surface grammar
field rhythm
hierarchy
entry / exit choreography

REDUCE / OMIT
unsupported functional states
```

This is not a fidelity failure.

It is truth-preserving transposition.

---

# 22. Current-state mode patterns

Useful transformations include:

## Operational equivalent

```text
donor D3–D5
+
target D3–D5
→ high functional parity possible
```

## Preparation equivalent

```text
donor operational form
+
target D0
→ single-task preparation surface
```

## Local-only equivalent

```text
donor submission workflow
+
target D1/D2 only
→ local worksheet/configurator with explicit no-submit boundary
```

---

# 23. Promotion rule

A deferred interaction may be promoted only when the missing dependency state becomes evidenced.

Example:

```text
D0 Start shell
+
approved editable input design
→ D1

D1
+
approved validation contract
→ D2

D2
+
real endpoint
→ D3

D3
+
approved destination / durable receipt
→ D4

D4
+
verified acknowledgement semantics
→ D5
```

No promotion by visual redesign alone.

---

# 24. Blueprint requirements

For interactive routes, the blueprint must include:

```text
INTERACTION STATE DIAGRAM
AFFORDANCE CLAIM LEDGER
DEPENDENCY CEILING
ENABLED / DISABLED / OMITTED CONTROLS
ERROR / EMPTY / SUCCESS BOUNDARIES
ACCESSIBILITY REQUIREMENTS
MOBILE / RESPONSIVE INTERACTION NOTES
UNRESOLVED DEPENDENCIES
```

Do not plan implementation from screenshots alone.

---

# 25. Build requirements

BUILD may implement only the admitted state.

If the target is D0:

```text
no hidden submission
no fake success
no silent persistence
```

If later promoted:

```text
change the truth inventory
change the contract
then activate the new state
```

---

# 26. Validation requirements

Post-build Target Truth validation asks:

```text
Does every visible affordance have a real job?
Does it imply more capability than exists?
Can every enabled action complete its promised state?
Are success/error states evidence-backed?
Are hidden side effects documented?
Are unresolved dependencies still represented honestly?
```

Possible result:

```text
TRUTHFUL
OVERCLAIMS CAPABILITY
UNDER-SPECIFIED
NOT TESTED
```

---

# 27. VTKALL Start case

Current target state:

```text
D0 — PRESENTATION / INTAKE SCHEMA
```

Supported:

```text
Start route
intake field labels
single-task preparation job
no-technical-brief positioning
explicit no-submission status
navigation back to Method
```

Not supported:

```text
editable input
validation
submit
contact delivery
scheduling
success confirmation
```

Therefore Dayos Schedule Demo may donate:

```text
single-task focus
compact rounded surface
vertical field rhythm
strong hierarchy
close/exit role
background de-emphasis
```

but not currently:

```text
enabled submit action
booking promise
success state
```

---

# 28. Framework status

```text
CROSS-CASE CANDIDATE                  ✅
VALIDATED IN SECOND INTERACTIVE CASE  ⛔ NOT YET
FOUNDATION CANON                      ◉ PROPOSED
```

The rule should be re-tested in a future migration involving another interaction type such as authentication, search, booking, checkout, or file submission.

---

# 29. Governing statement

> **An interface is truthful only when the capability implied by its affordances is supported by the target system or clearly bounded as non-operational/local-only.**
