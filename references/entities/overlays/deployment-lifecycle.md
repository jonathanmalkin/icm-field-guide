# Deployment lifecycle

- **Trigger:** a personal workflow will be shared, operated by a team, or run by a buyer.
- **Life 1 — personal:** local files, one operator, recoverable version history.
- **Life 2 — shared:** stable contracts, ownership, conflict handling, real
  permissions, synchronized sources, and change review.
- **Life 3 — deployable:** configured instances, defined interfaces, isolation,
  observability, support, upgrade policy, and hidden/private factory material.
- **Human check:** explicitly approve every lifecycle transition.
- **Removal test:** do not add deployment machinery to a workflow that is still
  being discovered by one person.
- **Role model:** Productionizing ICM at Scale.

## Persistent and remote operation

Apply this lifecycle when an agent workspace must survive sessions, operate
across devices, or be reached remotely. Files may carry durable working context,
but hosting, authentication, authorization, encrypted transport, service
availability, backups, and memory controls must come from the operating
platform. Treat a remote stack as infrastructure around ICM, not a new
canonical form. See the
[Hermes-Cognee example](../../tools-and-kits.md#hermes-cognee-deployment).
