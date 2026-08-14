# Ink-VK Knowledge Governance

Project Ink-VK is a versioned knowledge environment.

## Precedence

1. Frozen step baselines govern the historical truth and decisions of the step they close.
2. Later approved decisions may refine the framework but do not silently rewrite prior reasoning or evidence.
3. Brainstorms, references, mining results, and source analyses provide input; they do not become adopted framework behavior without an explicit decision.
4. A source candidate is reusable intelligence until Ink-VK explicitly adopts, adapts, or rejects it.
5. New evidence becomes a delta unless it materially invalidates a frozen baseline and reopening is explicitly justified.

## State labels

- DRAFT
- PROPOSED
- ACTIVE
- RECOVERED
- OBSERVED
- CANDIDATE
- SELECTED
- ADOPTED
- ADAPTED
- REJECTED
- KNOWN UNKNOWN
- FROZEN
- FINAL BASELINE
- SUPERSEDED
- DEPRECATED

## Permanent iteration rule

The repository follows an **append-only knowledge principle**.

A meaningful iteration must be persisted in GitHub when it changes project state, reasoning, terminology, architecture, design, plan, implementation contract, source selection, evidence, or a gate decision.

### Normal version evolution

```text
v0.1
  ↓
v0.2
  ↓
v0.3
  ↓
v1.0
```

Rules:

- Published versioned artifacts remain historically available.
- A material iteration creates a new versioned artifact rather than silently rewriting historical meaning.
- A later version may supersede an earlier version without erasing it.
- Frozen baselines are immutable historical records.
- Important knowledge must remain understandable from the repository tree, not only from Git history or chat memory.

## Deprecated material

`deprecated/` is not a trash folder and is not the destination for every old version.

It is reserved for material explicitly determined to be incorrect, invalidated, abandoned, unsafe to continue, or replaced by a decision that makes the prior direction unsuitable for active use.

When deprecating knowledge:

1. Preserve the artifact or an exact historical representation.
2. Move or represent it under the appropriate `deprecated/` scope when practical.
3. Record why it was deprecated.
4. Record what supersedes it, if a replacement exists.
5. Never silently delete the reasoning or evidence that led to it.

A valid older version is **not automatically deprecated**. It may simply be historical or superseded.

## Source provenance rule

Every meaningful external source used by Ink-VK must preserve enough provenance to answer:

```text
Where did it come from?
What was observed?
What rights / license / authorization constraints apply?
What pattern or capability was extracted?
What was selected?
What was rejected?
What was transformed?
What was created new for the target client?
```

Source code, screenshots, copied text, or assets are not assumed reusable merely because they are publicly reachable.

## Transformation rule

Ink-VK distinguishes at minimum:

```text
KEEP
ADAPT
REPLACE
REMOVE
BUILD NEW
```

A successful transformation must not be justified by "the donor did it this way" alone. Client soul, business reality, operational constraints, architecture, user needs, and evidence must justify the target decision.

## Soul rule

`Soul` is not equivalent to branding.

It may influence:

- product behavior;
- terminology;
- information architecture;
- interaction patterns;
- business rules;
- workflows;
- data and ownership boundaries;
- visual identity and motion;
- trust signals;
- architectural choices;
- what must be removed from a donor source.

## Mining rule

External discovery is organized as **mining sites** and **quarries**.

A mining site represents a problem/domain/search space. A quarry represents one concrete source or evidence collection within that site.

Example:

```text
mining-sites/
└── <target-capability>/
    ├── README.md
    ├── quarry-00/
    ├── quarry-01/
    └── quarry-02/
```

Quarries are evidence and candidate intelligence. They do not automatically become donors.

## Safety and legitimacy boundary

Ink-VK supports legitimate reuse, study, adaptation, migration, reimplementation, and client-specific differentiation. It must respect applicable licensing, authorization, privacy, security, intellectual-property, and client-confidentiality constraints.

The project's Blade Runner / Voight-Kampff metaphor may describe replication and transformation, but operational work must not be framed as bypassing anti-bot, anti-abuse, fraud, security, or access-control systems.

## Update rule

Every meaningful update should make it possible to recover:

```text
what changed
why it changed
supporting evidence
source / quarry relationship
client-soul relationship
version relationship
whether anything becomes deprecated
whether a gate must reopen
next handoff
```

## Final test

The repository must let a future engineer or agent answer:

> What were we trying to create, what did we mine, what did each source teach us, what did we select, what did we transform, why does the result belong to the client, what versions existed, what was rejected, what remains unknown, and what has the right to happen next?
