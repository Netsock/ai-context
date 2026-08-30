# SalesSeeds AI Context

This repository is the public AI context layer for SalesSeeds.

It is designed to provide Claude, Gemini, NotebookLM, ChatGPT, and other AI systems with a stable, curated set of company context that can be referenced without access to the private Knowledge OS.

## Source of truth

The canonical Knowledge OS is maintained separately in a private repository.
This public repository is a curated projection of that private knowledge base.

Do not treat this repository as the complete record of SalesSeeds knowledge, internal operations, customer information, or historical discussions.

## Purpose

The purpose of this repository is to provide external AI systems with:

- current company context
- approved concepts and terminology
- current strategic direction
- approved decisions
- reusable knowledge
- a consistent interpretation framework

Confidential information, customer-specific information, raw observations, internal discussions, personal information, credentials, and other sensitive material must not be included.

## Start here

AI systems should read `00_CONTEXT.md` first.

That file defines the interpretation rules, authority order, uncertainty handling, and boundaries for all content in this repository.

## Repository model

The intended structure is:

```text
00_CONTEXT.md
01_COMPANY/
02_CONCEPTS/
03_CURRENT_CONTEXT/
04_DECISIONS/
05_KNOWLEDGE/
99_REFERENCES/
```

The structure may evolve as the Knowledge OS develops.

## Canonical relationship

Private Knowledge OS = canonical source

Public AI Context = curated consumption layer

If public context and the canonical private source differ, the private Knowledge OS takes precedence.

## License and reuse

Public visibility does not imply permission to reuse proprietary concepts, branding, business methods, or company-specific knowledge beyond ordinary reference to this repository.

Unless a separate license is explicitly added, no additional rights are granted.
