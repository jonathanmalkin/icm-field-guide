# Authority and system-of-record boundary

- **Trigger:** a workflow touches CRM, ERP, accounting, calendar, email, HRIS,
  ticketing, publishing, payment, inventory, identity, or another external system.
- **Declare:** which system owns each fact, identifier, status, and action.
- **ICM may hold:** routing, working context, drafts, analyses, evidence snapshots,
  and proposed changes.
- **ICM must not impersonate:** permissions, authentication, locks, balances,
  transactional state, consent, or delivery confirmation.
- **Writes:** validate current state, use explicit authorization and stable IDs,
  preserve audit evidence, and handle retries outside Markdown.
- **Human check:** approve consequential actions at the boundary.
