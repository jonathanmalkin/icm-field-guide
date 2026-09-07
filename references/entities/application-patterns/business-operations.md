# Business operations

Business operations ICM gives a recurring request, order, task, case, or service
transaction a visible path from intake to closure. It is useful when the same
business and quality rules govern repeated work.

## Use it when

Use a [Pipeline](https://github.com/RinDig/icm-architect/blob/b20fb45063a564cf607b03526e206f519d174def/references/forms.md#1-pipeline--the-production-line)
for one operating line. Use an
[Umbrella](https://github.com/RinDig/icm-architect/blob/b20fb45063a564cf607b03526e206f519d174def/references/forms.md#2-umbrella--a-portfolio-of-pipelines)
when several distinct lines share policies, voice, or business rules. Do not
build it while the real process is still unknown.

## What it contains

- stable business rules and definition of done;
- an intake record with required fields;
- only the processing stages that produce distinct artifacts;
- an exception or approval gate;
- a delivery, closure, or handoff artifact;
- links to authoritative operational systems.

The common flow is: intake → validate → process → handle exception or review →
deliver or close.

## Human and system boundary

A person approves exceptions, money movement, commitments, and other
consequential actions. Accounting, scheduling, inventory, CRM, and ERP systems
retain live transactional truth; Markdown holds working context and reviewed
artifacts. See [CRM operations](../system-archetypes/crm-operations.md) or
[ERP operations](../system-archetypes/erp-operations.md) when those systems are
present.

## Related example

- [Small-business operations architecture](../project-examples/small-business-operations.md)

Status: source inspected; application guidance is derived.
