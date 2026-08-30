# Public Context Architecture

Status: Adopted decision
Adopted: 2026-08-30

## Decision

Maintain a public repository, `Netsock/ai-context`, as a curated AI-consumption layer derived from the private canonical Knowledge OS.

## Architecture

```text
Private Knowledge OS
Canonical / Internal
        ↓
Selection, review, distillation
        ↓
Public AI Context
Curated / Public
        ↓
Claude / Gemini / NotebookLM / ChatGPT / other AI systems
```

## Authority

The public repository is not an independent source of truth.

If public context conflicts with the private Knowledge OS, the private canonical source takes precedence.

## Publication rule

Content should normally be distilled rather than copied directly.

Suitable public material includes:

- approved concepts
- reusable non-confidential knowledge
- public current context
- non-confidential decisions
- terminology required for correct AI interpretation

Material that should normally remain private includes:

- customer-specific context
- raw observations
- internal discussions
- personal information
- internal financial information
- credentials and secrets
- unpublished sensitive strategy
- information whose confidentiality status is unclear

## Operating principle

The public layer exists to make company-specific context portable across AI systems without weakening the confidentiality boundary of the canonical Knowledge OS.

The intended long-term direction is to reduce manual duplication and eventually support controlled generation or synchronization from the canonical source, but automated publication must not bypass review of confidentiality and semantic status.
