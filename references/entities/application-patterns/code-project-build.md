# Code or project build

A code or project build uses persistent files to keep scope, decisions,
acceptance, implementation, and verification aligned across sessions. The
repeating unit is a feature, release, implementation slice, or milestone.

## Use it when

Use it when chat history and one issue no longer preserve enough context. The
working sequence is a
[Pipeline](https://github.com/RinDig/icm-architect/blob/b20fb45063a564cf607b03526e206f519d174def/references/forms.md#1-pipeline--the-production-line);
a small
[Knowledge Bundle](https://github.com/RinDig/icm-architect/blob/b20fb45063a564cf607b03526e206f519d174def/references/forms.md#4-knowledge-bundle--the-product-is-the-knowledge)
holds durable product, architecture, and decision context.

If the job is instead to map an existing repository or mixed workspace so a
later agent can answer “what is this?” and “what else moves if I change it?”,
use the [repository or workspace change-impact map](repository-workspace-change-impact.md)
and upstream's System Map form. Do not force that audit into a feature-delivery
Pipeline.

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
When external repositories or dependencies enter the build, apply
[external code and dependency assurance](../../operational-extensions.md#external-code-and-dependency-assurance).

## Related material

- [Website build](../project-examples/website-build.md)
- [Repository or workspace change-impact map](repository-workspace-change-impact.md)
- [Workspace and workflow kits](../../tools-and-kits.md#map-or-improve-a-human-workflow)

Status: derived application.
