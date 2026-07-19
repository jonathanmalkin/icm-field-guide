# ERP operations

- **Status:** derived system archetype
- **Evidence note:** no ERP or enterprise-resource-planning implementation was
  found in Clief Notes. The Team Graph examples mention accounting systems,
  ledgers, campaign trackers, finance, and cross-team data flows.
- **Canonical composition:** Context Map + process Pipelines; optional Record
  Libraries for non-transactional cases or evidence
- **Repeating units:** order, invoice, purchase, inventory movement, work order,
  close, forecast, or fulfillment exception

## Smallest useful ICM

- Context-map nodes for functions, processes, data assets, owners, and handoffs.
- A Pipeline only for a real human-reviewed process such as month-end close,
  purchase approval, or exception resolution.
- Stable references to ERP objects, reports, policies, and schemas.
- Plain-file workpapers, explanations, reconciliations, and approval artifacts.

## Authority boundary

The ERP owns vendors, customers, chart of accounts, inventory, orders,
invoices, payments, journal entries, permissions, and transaction history. ICM
must not simulate balances, locks, approvals, or posting state in Markdown.
Writes to the ERP are consequential actions and require explicit authorization,
validation, idempotency, and audit logging outside the folder architecture.

## Applied cold-routing question

After applying the canonical
[walk test](https://github.com/RinDig/icm-architect/blob/e5313c308522ff9c4646a17b06fb1ddb0d844917/SKILL.md#the-walk-test), ask whether a cold
agent can identify the authoritative module and record, the process owner, the
exact source inputs, the proposed action, and the human approval needed before
any transaction changes.
