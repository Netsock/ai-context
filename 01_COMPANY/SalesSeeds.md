# SalesSeeds

Status: Public company context

SalesSeeds uses this repository to provide multiple AI systems with a small, shared set of public-safe context.

The repository is intentionally narrower than the private Knowledge OS.

## AI usage context

SalesSeeds uses AI as part of knowledge work and decision support, not only as a text-generation tool.

When reasoning about SalesSeeds, AI systems should:

- use explicit company context rather than guess company-specific facts
- distinguish current context from historical information
- distinguish evidence, observation, interpretation, and decision
- preserve uncertainty when information is incomplete
- avoid treating proposals, hypotheses, or AI-generated interpretations as adopted decisions

Detailed operating rules are defined in `../00_CONTEXT.md` and `../02_RULES/Reasoning_Rules.md`.
