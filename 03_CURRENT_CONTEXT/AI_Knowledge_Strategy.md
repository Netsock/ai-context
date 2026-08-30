# Current AI Knowledge Strategy

Status: Current public context
Last reviewed: 2026-08-30

SalesSeeds is currently developing an operating model in which AI works from company-specific context rather than relying only on general model knowledge.

## Current direction

The current direction is to separate:

```text
Canonical private Knowledge OS
        ↓
Selection / Review / Distillation
        ↓
Public AI Context
        ↓
Multiple AI systems
```

The private Knowledge OS remains the canonical source.

This public repository exists because some AI systems cannot directly access the private repository. It provides a common, curated context layer that can be used across Claude, Gemini, NotebookLM, ChatGPT, and other systems where appropriate.

## Strategic assumptions currently in use

- Frontier model capability is broadly available and should not be treated as the only source of durable organizational advantage.
- Company-specific context, accumulated decision history, tacit knowledge, and ontology may create more differentiated AI behavior than model access alone.
- AI should support reasoning with organizational context, not merely retrieve documents or draft text.
- Human judgment remains necessary for meaning, values, important ambiguity, and adoption of decisions.
- Knowledge should be treated as something that can be developed through repeated observation, discussion, action, and revision.

## Current implementation principle

The public context layer should be concise, curated, and safe for public exposure.

It should prioritize current context and approved reusable knowledge while excluding raw internal observations, confidential discussions, customer-specific information, personal information, credentials, internal financial information, and unpublished sensitive strategy.

## Current development status

Knowledge OS is an established internal operating concept.

KAMOSU AI / Knowledge Nurturing OS is under active concept development and validation. Its current definitions are useful for reasoning but should not be presented as a fully validated product or final category definition.
