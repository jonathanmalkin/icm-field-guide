# ICM Field Guide

An unofficial, read-only community companion to
[Interpretable Context Methodology](https://arxiv.org/abs/2603.16021).

Before building an ICM workspace, use the Field Guide to decide whether ICM is
the smallest sufficient mechanism, which applied pattern fits, what a human
must check, and where ICM should stop. When implementation begins, hand off to
Jake Van Clief's separately distributed
[ICM Architect](https://github.com/RinDig/icm-architect), the canonical build
and restructure skill.

## Distribution status

This repository is prepared for public community distribution under the MIT
license. It contains original application guidance and compact, evidence-labeled
summaries of community examples. It does not reproduce the underlying course
files, transcripts, attachments, or templates.

Release verification completed July 19, 2026:

1. the skill structure, relative links, evidence labels, and named-example
   descriptions passed static validation and independent review;
2. representative advisory behavior was reviewed in Codex; and
3. a clean Claude Code project with the Field Guide and a separately installed
   ICM Architect preserved the read-only boundary and handed implementation off
   by skill name.

No private source paths, source files, transcripts, participant details,
confidential or nonpublic client facts, or authenticated links are included in
this export.

## What is included

```text
icm-field-guide/
├── SKILL.md
├── agents/
├── references/
├── README.md
├── LICENSE
└── NOTICE.md
```

ICM Architect is intentionally not included. The skills are complementary but
independently maintained and distributed. The Field Guide links to the exact
pinned Architect snapshot rather than restating, vendoring, or forking it.

## Install

Clone this repository directly into the skill location for your runtime.

For a project-local Codex installation:

```bash
mkdir -p .agents/skills
git clone https://github.com/jonathanmalkin/icm-field-guide \
  .agents/skills/icm-field-guide
```

For a project-local Claude Code installation:

```bash
mkdir -p .claude/skills
git clone https://github.com/jonathanmalkin/icm-field-guide \
  .claude/skills/icm-field-guide
```

For a user-level installation, use `~/.agents/skills/icm-field-guide` for
Codex or `~/.claude/skills/icm-field-guide` for Claude Code.

For implementation work, install
[RinDig/icm-architect](https://github.com/RinDig/icm-architect) separately.
The Field Guide's canonical references are pinned to upstream commit
[`e5313c3`](https://github.com/RinDig/icm-architect/commit/e5313c308522ff9c4646a17b06fb1ddb0d844917).
This is a stable documentation reference, not an Architect installation
requirement.
Follow Architect's upstream installation instructions for Claude Code. For
Codex, place its separately cloned repository at
`.agents/skills/icm-architect` or `~/.agents/skills/icm-architect`. When both
skills are available to the same runtime, implementation requests hand off by
the `icm-architect` skill name. Field Guide advisory use does not require
Architect to be installed.

Then ask:

- “Which ICM pattern fits this workflow?”
- “Compare a company brain with a research hub.”
- “Does this need ICM, ordinary files, a skill, code, or a hybrid?”

Use ICM Architect when you are ready to build or restructure actual files.

## Design boundary

- Field Guide: explanation, comparison, fit assessment, pattern selection, and
  operational cautions.
- ICM Architect: canonical forms, workspace construction, restructuring,
  migration, contracts, templates, and the walk test.
- External systems: authentication, permissions, transactions, locking,
  authoritative business data, and consequential actions.

See [NOTICE.md](NOTICE.md) for attribution and third-party boundaries. The
Field Guide and repository wrapper use the MIT license in [LICENSE](LICENSE).
ICM Architect is not part of this repository and retains its own upstream
license and maintenance process.
