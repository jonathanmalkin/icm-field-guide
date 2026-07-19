# Code or project build

A code or project build uses persistent files to keep scope, decisions,
acceptance, implementation, and verification aligned across sessions. The
repeating unit is a feature, release, implementation slice, or milestone.

## Use it when

Use it when chat history and one issue no longer preserve enough context. The
working sequence is a
[Pipeline](https://github.com/RinDig/icm-architect/blob/e5313c308522ff9c4646a17b06fb1ddb0d844917/references/forms.md#1-pipeline--the-production-line);
a small
[Knowledge Bundle](https://github.com/RinDig/icm-architect/blob/e5313c308522ff9c4646a17b06fb1ddb0d844917/references/forms.md#4-knowledge-bundle--the-product-is-the-knowledge)
holds durable product, architecture, and decision context.

## What it contains

- the repository's native agent router;
- an approved product or decision brief;
- implementation constraints and acceptance criteria;
- plan, change, and verification handoffs;
- durable decision records for choices that outlive one task;
- links to code, tests, issues, and deployment evidence.

The flow is: decision brief → implementation plan → code or project change →
verification → accepted result.

## Human and authority boundary

Humans own product decisions and consequential release actions. Code, tests,
and deployed behavior remain authoritative; the ICM layer records approved
intent and working decisions. Remove the extra layer when repository
instructions, tests, and one issue already make the task recoverable.

## Related material

- [Website build](../project-examples/website-build.md)
- [Workspace Blueprint](../../tools-and-kits.md)

Status: derived application.
