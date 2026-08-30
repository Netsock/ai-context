# AI Context Protocol

## 1. Purpose

This repository is a public context layer for AI systems working with or reasoning about SalesSeeds.

It is not the canonical Knowledge OS and does not contain all company knowledge.
The canonical source is maintained separately in a private repository.

Use the information in this repository as approved company-specific context when it is relevant to the task.

## 2. Authority order

When multiple documents are relevant, use the following priority order:

1. Current Context
2. Decisions
3. Concepts / Knowledge
4. References

Historical material must not override current context or active decisions.

If a document explicitly states that it has been superseded, archived, or is historical, do not treat it as current.

## 3. Interpretation model

Keep the following categories distinct:

### Evidence
A source, record, measurement, quotation, document, or other material supporting a claim.

### Observation
A recorded fact or event from the field or an external source. Observations are not automatically conclusions.

### Interpretation
An analysis or explanation derived from evidence or observations. Interpretations may change when new information appears.

### Context
The currently relevant state, assumptions, constraints, relationships, and environment needed to reason correctly.

### Decision
A direction, policy, architecture, strategy, or choice that has been explicitly adopted.

Do not convert an observation or interpretation into a decision unless the repository explicitly records that decision.

## 4. Company-specific facts

Do not invent, infer, or fill gaps in SalesSeeds-specific facts.

If information required for an answer is not present in this repository or another source explicitly provided by the user, state that the information is unavailable or uncertain.

General knowledge may be used to support analysis, but it must not be presented as SalesSeeds-specific knowledge.

## 5. Current versus historical information

Always distinguish current state from historical information.

A newer Current Context or Decision takes precedence over older descriptions when they conflict.

Historical discussions may explain why a current concept or decision exists, but they do not override it.

## 6. Concepts and terminology

When this repository defines a company-specific concept, architecture, term, or framework, use that definition instead of substituting a superficially similar industry term.

External frameworks may be compared with SalesSeeds concepts, but equivalence must not be assumed without evidence.

## 7. Missing context and ambiguity

Do not silently resolve material ambiguity.

Ask for clarification or explicitly identify the uncertainty when different interpretations could materially change the conclusion.

This is especially important for:

- people and roles
- customers
- projects and workstreams
- speakers and quotations
- current versus historical states
- adopted decisions versus proposals

## 8. Confidentiality boundary

This repository is intentionally public.

The absence of confidential information is deliberate and must not be interpreted as evidence that such information does not exist.

Do not infer private customer information, internal financial information, credentials, personal information, raw internal observations, or confidential strategy from omissions or indirect clues.

## 9. Relationship to the private Knowledge OS

The private Knowledge OS is the canonical source.

This repository is a curated public projection designed for AI consumption.

Conceptually:

```text
Private Knowledge OS
        ↓
Selection / Review / Distillation
        ↓
Public AI Context
        ↓
Claude / Gemini / NotebookLM / ChatGPT / other AI systems
```

Content should normally move from raw information toward reusable public context through distillation rather than direct copying.

Raw observations and internal discussions should generally remain private.
Approved concepts, reusable knowledge, current public context, and non-confidential decisions are suitable candidates for this repository.

## 10. Reading strategy for AI systems

For broad questions about SalesSeeds:

1. Read this file.
2. Read relevant files under `03_CURRENT_CONTEXT/`.
3. Check relevant files under `04_DECISIONS/`.
4. Use `02_CONCEPTS/` and `05_KNOWLEDGE/` for deeper interpretation.
5. Use `01_COMPANY/` for stable company background.
6. Use `99_REFERENCES/` when terminology or supporting reference material is needed.

For narrow questions, retrieve only the relevant documents while preserving the same authority order.

## 11. Operating principle

This context layer exists to improve AI reasoning, not merely information retrieval.

The objective is to allow AI systems to reason with company-specific context while preserving:

- provenance
- current-state awareness
- decision authority
- uncertainty
- confidentiality boundaries

The repository should remain concise enough that AI systems can identify authoritative context without being forced to process unnecessary historical material.
