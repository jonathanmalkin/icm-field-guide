# Authority and system-of-record boundary

- **Trigger:** a workflow touches CRM, ERP, accounting, calendar, email, HRIS,
  ticketing, publishing, payment, inventory, identity, or another external system.
- **Declare:** which system owns each fact, identifier, status, and action.
- **ICM may hold:** routing, working context, drafts, analyses, evidence snapshots,
  and proposed changes.
- **ICM must not impersonate:** permissions, authentication, locks, balances,
  transactional state, consent, or delivery confirmation.
- **Readiness is not completion:** a file can show a draft or request is ready;
  only the external system's receipt, operation ID, or read-back confirms its
  authoritative completion.
- **Human check:** approve consequential actions at the boundary.
- **Removal test:** do not add external-state protocols when a workflow only
  creates local, reversible artifacts.
- **Operational detail:** [authority and synchronization](../../operational-extensions.md#authority-and-synchronization).
