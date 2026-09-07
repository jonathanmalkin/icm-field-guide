# Should this be ICM?

A derived intake aid for choosing the smallest mechanism. It does
not select a canonical ICM form or replace ICM Architect.

## Choose the lowest sufficient rung

| If the work is… | Start with | Do not add yet |
| --- | --- | --- |
| A one-off or simple recurring task with one owner and no durable handoff | Ordinary files or a checklist | A workspace, retrieval, or automation |
| A stable instruction repeated in conversation, without meaningful workflow state | A saved prompt or skill | Pipeline folders or persistent infrastructure |
| A repeated sequence with distinct editable artifacts, human checks, and handoffs | ICM orientation; hand off only if a build, change, or audit is requested | A canonical form chosen before discovery |
| A repeatable system action that needs deterministic validation, integration, or transaction handling | Deterministic software or an automation platform | Markdown as the transaction, permission, or retry system |
| A mix of human-reviewed artifacts and repeatable system actions | A hybrid: ICM may route the human work; software owns the system action | Treating either layer as the other |

## Five intake questions

1. **What repeats?** Name one unit of work, not a wish for better organization.
2. **What must stay editable?** Identify the artifact a person needs to review
   before work continues.
3. **What changes hands?** If artifacts, owners, or decisions repeatedly pass
   between stages, ICM may help make that route visible.
4. **What owns truth or action?** A CRM, repository, database, calendar, or
   service continues to own its live facts and transactions.
5. **What would make folders insufficient?** Concurrent writers, automated
   branching, credentials, sensitive-data egress, or irreversible actions need
   their own controls outside the filesystem.

## Record a reversible verdict

- **Selected mechanism:** ordinary files/checklist, saved prompt/skill, ICM,
  deterministic software, or hybrid.
- **Why this is the smallest sufficient choice:** one observed constraint.
- **Human check:** the person and artifact that must pause progress.
- **What it does not own:** authoritative records, permissions, transactions,
  or another named boundary.
- **Next trigger:** the event that would justify revisiting this choice.

If the verdict is ICM and the user asks to build, change, or audit a real
workspace, use the [Field Guide-to-Architect handoff brief](field-guide-to-architect-handoff.md).
Otherwise, stop after the decision.
