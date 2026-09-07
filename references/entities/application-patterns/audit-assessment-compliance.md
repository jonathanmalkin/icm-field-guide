# Audit, assessment, and compliance

This pattern turns a stable framework and case-specific evidence into reviewed
findings, scores, exceptions, or remediation. The repeating unit is an assessed
site, workflow, organization, system, or case.

## Use it when

Use it when each case follows the same evidence and judgment sequence and must
retain a reviewable trail. A likely composition is a
[Pipeline](https://github.com/RinDig/icm-architect/blob/b20fb45063a564cf607b03526e206f519d174def/references/forms.md#1-pipeline--the-production-line)
that publishes approved results into a
[Record Library](https://github.com/RinDig/icm-architect/blob/b20fb45063a564cf607b03526e206f519d174def/references/forms.md#3-record-library--the-unit-is-a-record).
See the [Assessment case library](../compositions/assessment-case-library.md)
composition.

## What it contains

- versioned framework, scoring rules, and evidence schema;
- an isolated case record;
- sourced evidence intake;
- deterministic validation or scoring where possible;
- a separate judgment stage;
- reviewed findings, exceptions, and remediation;
- an approval record before consequential use.

The flow is: scope → collect evidence → run objective checks → apply judgment →
draft findings → approve → remediate.

## Human and authority boundary

A qualified owner approves consequential findings and status changes. Legal,
regulatory, and policy sources remain external and versioned. The workspace
stores what was applied to this case and the resulting evidence trail; it does
not become the source of legal truth.

## Related examples

- [Ethics Engine](../project-examples/ethics-engine.md)
- [VigilOre](../project-examples/vigilore.md)
- [Workflow decision aids](../../tools-and-kits.md#decide-the-smallest-mechanism)

Status: source inspected; application guidance is derived.
