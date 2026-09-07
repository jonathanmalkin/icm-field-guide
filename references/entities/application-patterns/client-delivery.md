# Client delivery

Client delivery ICM turns an engagement or approved deliverable into a
human-reviewed sequence from discovery through handoff. It keeps reusable method
separate from client facts.

## Use it when

Use it when discovery, design, build, acceptance, and handoff create distinct
artifacts or involve different owners. The primary form is a
[Pipeline](https://github.com/RinDig/icm-architect/blob/b20fb45063a564cf607b03526e206f519d174def/references/forms.md#1-pipeline--the-production-line).
Several client-local pipelines may sit beneath a shared-method
[Umbrella](https://github.com/RinDig/icm-architect/blob/b20fb45063a564cf607b03526e206f519d174def/references/forms.md#2-umbrella--a-portfolio-of-pipelines),
but they must not share client data.

## What it contains

- a client-local router and engagement scope;
- sourced discovery and decisions;
- an approved design or delivery brief;
- the real build stages;
- acceptance criteria and reviewed output;
- a final handoff artifact;
- a separate sanitized method area with no client facts.

The flow is: sourced discovery → approved design → build → acceptance → handoff.

## Facilitated decision-work variant

When the deliverable is a decision rather than a build, use the same pattern in
a smaller form: structured intake → facilitated conversation → reviewed
decision map → decision record or term sheet → explicit handoff. The map records
what was decided and why; it does not prove that a recommended system was
implemented. See the
[session-to-artifact example](../../tools-and-kits.md#session-to-artifact-package).
If reviewed sessions need to accumulate by client, an optional
[Record Library](https://github.com/RinDig/icm-architect/blob/b20fb45063a564cf607b03526e206f519d174def/references/forms.md#3-record-library--the-unit-is-a-record)
may surround the Pipeline. Link to authoritative relationship records rather
than copying CRM truth.

## Human and data boundary

The client or named owner approves scope, major design decisions, acceptance,
and delivery. Remove stages that do not create an artifact or decision, but
never remove isolation boundaries. Load
[operational extensions](../../operational-extensions.md#isolation-and-sensitive-data)
for sensitive or cross-client work.

## Related material

- [Filesystem client management](../project-examples/filesystem-client-management.md)

Status: source inspected; application guidance is derived. Facilitated decision
work is a source-inspected package pattern, not an independently verified
implementation.
