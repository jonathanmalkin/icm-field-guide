# ICM Field Guide

Decide whether a workflow needs ICM before building a workspace around it.

This is Jonathan Malkin’s unofficial community companion to Jake Van Clief and David McDermott’s [Interpretable Context Methodology](https://arxiv.org/abs/2603.16021). It helps you compare ordinary files, a checklist, a saved prompt or skill, ICM, deterministic software, and combinations of those approaches.

The Field Guide gives advice and records the next decision. When you ask to build, change, or audit a workspace, it hands off to Jake’s separately installed [ICM Architect](https://github.com/RinDig/icm-architect). Architect owns the method, forms, contracts, templates, and walk test.

## Start with a real job

Try one of these prompts:

- “Client intake, research, delivery, and follow-up span several tools. Does this need ICM?”
- “Help me choose between a saved skill and a workspace for workshop preparation.”
- “I have a repository that agents struggle to navigate. What is the smallest useful next step?”

The guide asks what repeats, which artifacts need review, who takes over at each step, and which systems already own the records. A checklist or an existing router may be enough.

## What changed in September 2026

The public package now includes the current decision-focused entrypoint, a repository change-impact pattern, four decision and verification aids, and guidance for untrusted content, external systems, concurrent work, and software dependencies.

Start with [Should this be ICM?](references/decision-aids/should-this-be-icm.md), compare the [worked decisions](references/decision-aids/worked-decisions.md), or inspect the [handoff brief](references/decision-aids/field-guide-to-architect-handoff.md). The [runtime check card](references/decision-aids/current-runtime-cold-test-card.md) records what was actually tested in a particular environment.

## Install

Place this repository in the skill directory your agent uses. For the project layouts used here:

```bash
# Codex
git clone https://github.com/jonathanmalkin/icm-field-guide .agents/skills/icm-field-guide

# Claude Code
git clone https://github.com/jonathanmalkin/icm-field-guide .claude/skills/icm-field-guide
```

Use the command for your runtime. For an existing installation, update that checkout through your usual Git workflow while preserving local changes.

Install [ICM Architect](https://github.com/RinDig/icm-architect) separately when you want implementation. The Field Guide’s reference snapshot lives in [SKILL.md](SKILL.md); links in this public package point to that published snapshot. Advisory use can consult those links without a sibling Architect installation. Test the routes you need in your actual runtime before relying on them.

## Scope and attribution

The package contains original application guidance, generic decision aids, and brief evidence-labeled descriptions of community examples. Example descriptions distinguish source inspection from observed operation. They are not product endorsements or verified performance claims.

Private study maps, source registers, course files, transcripts, client information, and local maintenance records are excluded. The Field Guide does not bundle Architect or reproduce its templates. Existing business systems retain their records, permissions, and transactions.

The September refresh passed structural, local-link, export-integrity, and pinned-upstream checks. Those checks do not establish compatibility with every runtime or verify the named community projects.

See [NOTICE.md](NOTICE.md) for attribution and distribution boundaries and [LICENSE](LICENSE) for the MIT license covering Jonathan’s original contribution.
