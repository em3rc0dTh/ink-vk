# VTKALL Start — Truth & Dependency Inventory v0.1

**Project:** Ink-VK  
**Target:** VertikALL website  
**Route:** `/start`  
**Status:** RECOVERED / TARGET TRUTH + FUNCTIONAL DEPENDENCY BASELINE  
**Date:** 2026-08-14  
**Boundary:** NO BUILD / NO NEW BACKEND ASSUMPTIONS

---

## 1. Purpose

This document freezes the target-side truth for the VertikALL `Start` route before mapping it against Dayos `Schedule Demo`.

The route is special because its public meaning is not only content-bearing. It also contains **interaction implications**.

A form-like interface can imply:

```text
I can enter information
I can submit information
someone will receive it
something will happen next
I may receive confirmation
```

Those are functional claims.

The current target evidence does **not** support all of them.

Therefore this inventory separates:

```text
CONTENT TRUTH
INTERACTION TRUTH
DEPENDENCY TRUTH
VISUAL RECOVERY
UNKNOWN / FUTURE STATE
```

---

# 2. Authoritative source basis

Primary target sources:

```text
ronald-zavaleta/vtkall-website@develop
├── data/site-content.ts
└── components/start-page.tsx
```

Visual non-regression source:

```text
ink-vk/
active/step-0-foundation/evidence/vtkall-website/
VTKALL_WEBSITE_VISUAL_RECOVERY_v1.0.md
```

Route/Soul context:

```text
VTKALL_SOUL_CONTRACT_v0.1.md
VTKALL_DAYOS_ROUTE_EXPERIENCE_MAPPING_v0.3.md
```

---

# 3. Supported Start information job

The current target source explicitly supports this job:

> A visitor can understand what information would be useful to begin a practical VertikALL conversation about an operating flow.

Current route language establishes:

```text
Start with your business flow.
```

and frames the conversation around:

```text
appointments
customer follow-up
service requests
staff coordination
daily visibility
another daily process
```

Evidence class:

```text
T0 — DIRECT TARGET FACT
```

This is sufficient to justify a Start route independently of Dayos.

---

# 4. Supported target fields

Current source defines these labels:

```text
Name
Business name
Business type
WhatsApp / phone
Email
What do you want to organize?
```

The last field has explicit helper context:

```text
Appointments, follow-up, service flow, staff coordination,
visibility, or another daily process.
```

Evidence class:

```text
T0 — DIRECT TARGET FACT
```

Important distinction:

```text
FIELD LABEL EXISTS
≠
EDITABLE FORM EXISTS
```

The labels currently define the **intake information schema**, not an operational submission system.

---

# 5. Current functional state from implementation evidence

`components/start-page.tsx` does not render native form inputs.

It renders:

```text
DiagnosticPreview
FieldGrid
StatusPanel
CTA links
```

The preview explicitly declares:

```text
Static shell
No information is sent from this page yet.
```

The field grid renders each future intake item as an informational card and describes it as:

```text
Static label for future diagnostic intake.
```

No evidence was recovered in this component for:

```text
<form>
<input>
<textarea>
submit handler
server action
API call
persistence
CRM handoff
email delivery
webhook
success state
failure state
validation state
```

Therefore the current proven functional ceiling is:

```text
PRESENTATION / PREPARATION STATE ONLY
```

---

# 6. Explicit target boundary

Current target copy says:

```text
Contact destination pending configuration.
No information is sent from this page yet.
```

and:

```text
No silent submission.
```

This is not merely placeholder copy.

It is an explicit public truth boundary.

Current allowed claim:

> These are the kinds of details that would help start the conversation once a contact destination exists.

Current forbidden claim:

> Submit this form and VertikALL will receive your request.

---

# 7. Functional dependency inventory

## D0 — Presentation / intake schema

**Status:** `PROVEN`

Evidence:

```text
field labels exist
static preview exists
preparation language exists
```

Allowed public UI:

```text
field labels
explanatory preview
preparation checklist
static form-like composition with explicit status
```

---

## D1 — Editable local input

**Status:** `NOT CURRENTLY PROVEN`

No current source evidence proves that Start accepts typed user state.

Could be introduced later, but would require an explicit product/design decision.

Allowed now:

```text
DEFER
```

Do not infer D1 merely because Dayos shows form controls.

---

## D2 — Client-side validation

**Status:** `NOT PROVEN`

No recovered validation contract exists for:

```text
required fields
email format
phone format
business-type values
message length
error copy
```

Therefore:

```text
VALIDATION UI → DEFER
```

---

## D3 — Submission transport

**Status:** `NOT PROVEN / EXPLICITLY ABSENT`

No target evidence establishes:

```text
server action
API endpoint
webhook
email transport
CRM endpoint
form provider
```

Current copy explicitly states that information is not sent.

Therefore:

```text
ENABLED SUBMIT ACTION → FORBIDDEN NOW
```

---

## D4 — Delivery destination / persistence

**Status:** `UNRESOLVED`

Current target source explicitly says:

```text
Contact destination pending configuration.
```

No approved destination is established here.

Unknown candidates must remain unknown.

Do not invent:

```text
email inbox
CRM
WhatsApp automation
calendar system
lead database
```

---

## D5 — Acknowledged outcome

**Status:** `NOT PROVEN`

No evidence establishes:

```text
request received
lead created
meeting scheduled
email sent
notification delivered
record persisted
```

Therefore no public success state may claim an outcome.

---

# 8. Current interaction ceiling

The current route may truthfully support:

```text
READ
UNDERSTAND
PREPARE
NAVIGATE
```

The current route does not yet prove:

```text
ENTER
VALIDATE
SUBMIT
DELIVER
CONFIRM
SCHEDULE
```

This is the baseline that donor interaction must respect.

---

# 9. Start Soul alignment

The route strongly fits VertikALL Soul because it supports the Harbor sequence:

```text
ARRIVE
OBSERVE
UNDERSTAND
DECIDE
```

The route also supports the relationship model:

```text
low pressure
practical conversation
no technical brief required
```

Current source explicitly says:

```text
No long technical brief required.
```

Therefore the Start experience should feel:

```text
focused
calm
clear
low-pressure
practical
honest about its current capability
```

It should not become a high-pressure enterprise lead-capture experience merely because the donor is conversion-oriented.

---

# 10. Current visual non-regression evidence

The original Start route has five annotated captures.

## START-01

Recovered issues:

```text
too cramped
large unjustified white space
section clipped
```

Observed condition:

```text
large headline + static-shell card compete in narrow center
upper/right area remains unused
bottom content clips
```

### Prevention invariant

Use available width deliberately or reduce competing elements.

Do not combine:

```text
cramped core
+
meaningless empty field
```

---

## START-02

Recovered issues:

```text
sections combine
meaningless empty space
```

Observed condition:

```text
next Diagnostic section enters before current state resolves
large right-side field has no clear job
```

### Prevention invariant

The Start task state must reach a readable stopping point before secondary context enters.

---

## START-03 — partial positive control

Recovered note:

```text
No se corta, aceptable.
```

Observed condition:

```text
diagnostic card grid fully visible
no clipping
```

A question mark still flags unused upper-right space.

### Preservation invariant

Keep:

```text
complete readable diagnostic content
```

Do not automatically preserve:

```text
unused upper-right field
```

This is a partial positive control, not a full visual approval.

---

## START-04

Recovered issue:

```text
sections combine
```

Observed condition:

```text
dark boundary state + following CTA share one unresolved frame
```

### Prevention invariant

Boundary/reassurance and next action must not compete as unresolved states.

---

## START-05

Recovered issue:

```text
sections combine
```

Observed condition:

```text
previous dark state tail
+
current CTA
+
footer
```

### Prevention invariant

Route closure must resolve in order:

```text
TASK / BOUNDARY
↓
ACTION / EXIT
↓
FOOTER
```

---

# 11. Target truth vs desired future capability

The current source clearly anticipates a future real contact path.

That future intent is legitimate.

However:

```text
FUTURE INTENT
≠
CURRENT CAPABILITY
```

The route may be architected so that future operational intake can be activated later.

Current UI must still represent current state honestly.

---

# 12. Approved target-side semantic roles for donor mapping

The following target jobs are real:

```text
single-task focus
explain what information matters
show the intake schema
reduce technical burden
prepare a future contact request
provide a safe exit / alternate route
state the current submission boundary
```

These can receive Dayos structural/interaction grammar.

---

# 13. Unsupported target-side jobs

No current evidence establishes:

```text
book a demo
choose appointment time
select salesperson
select calendar slot
submit lead
create CRM record
send email
send WhatsApp
receive confirmation
receive SLA/response-time promise
```

Those must not be introduced because the donor uses the phrase `Schedule Demo`.

---

# 14. Claim ceiling

## Allowed

```text
Start with your business flow.
Prepare the details that will help frame the conversation.
Contact destination is not yet configured.
No information is currently sent.
```

## Not allowed yet

```text
Send your request.
We'll contact you.
Book a demo.
Schedule your call.
Your request was received.
We'll reply within X time.
```

unless new evidence explicitly raises the functional ceiling.

---

# 15. Unknowns that must remain open

```text
future contact destination
future backend mechanism
whether future intake persists data
whether future Start remains a route or becomes an overlay
whether local input is allowed before submission exists
validation rules
privacy notice / data handling contract
success/error states
spam protection
accessibility interaction details
mobile input behavior
```

No donor fidelity decision may silently resolve these.

---

# 16. Gate result

```text
START INFORMATION JOB                  ✅ PROVEN
START ROUTE                            ✅ JUSTIFIED
TARGET INTAKE FIELD SCHEMA             ✅ PROVEN
CURRENT EDITABLE INPUT                 ⛔ NOT PROVEN
CURRENT VALIDATION                     ⛔ NOT PROVEN
CURRENT SUBMISSION                     ⛔ EXPLICITLY ABSENT
CONTACT DESTINATION                    ⛔ PENDING / UNKNOWN
DELIVERY / PERSISTENCE                 ⛔ NOT PROVEN
SUCCESS / FAILURE STATES               ⛔ NOT PROVEN
VISUAL NON-REGRESSION BASELINE         ✅ RECOVERED
DAYOS SINGLE-TASK MAPPING              ← NEXT
BUILD                                  ⛔ NOT AUTHORIZED
```

---

# 17. Governing statement

> **The Start route has real intent and real intake semantics, but only a preparation-state implementation is currently proven. A donor may improve the experience without pretending the downstream system already exists.**
