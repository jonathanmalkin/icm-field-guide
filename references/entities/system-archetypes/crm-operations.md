# CRM operations

- **Status:** source-grounded filesystem starter; derived integration guidance
- **Canonical composition:** Record Library + acquisition Pipeline + optional
  client-delivery Pipelines
- **Repeating units:** contact, company, opportunity, interaction, task, and engagement
- **Clief evidence:** the Client Management workflow starter defines business
  development, lead stages, outreach, proposals, client records,
  communications, deliverables, and case studies. It is CRM-shaped but does not
  define a transactional multi-user CRM.

## Smallest useful ICM

- A router for relationship work.
- Opportunity and deliverable artifacts that need sustained context.
- Reusable proposal, communication, and case-study factories.
- Links or stable identifiers pointing to the authoritative CRM records.
- Human gates for outbound communication, stage changes, commitments, and delivery.

## Authority boundary

When a real CRM exists, it owns identity, relationship facts, opportunity
stage, activities, tasks, consent, and timestamps. ICM owns narrative context,
working briefs, drafts, decision artifacts, and reusable methods. Never maintain
parallel contact or pipeline truth in Markdown.

## Filesystem-only starter

For one operator without a CRM, a Record Library may temporarily hold client
records and a small index. Treat this as a starter, not as authentication,
concurrency control, email logging, or a transactional database.

## Applied cold-routing question

After applying the canonical
[walk test](https://github.com/RinDig/icm-architect/blob/e5313c308522ff9c4646a17b06fb1ddb0d844917/SKILL.md#the-walk-test), ask whether a cold
agent can find the authoritative relationship record, current approved brief,
next human decision, and safe output location without reading another client's
context.
