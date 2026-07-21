# Conditional operational extensions

Load only the sections whose triggers are present. These additions do not alter
canonical ICM forms or templates; they address operating boundaries that
folders and Markdown cannot enforce.

## Trigger map

| Trigger | Apply |
| --- | --- |
| External authoritative system | Authority and synchronization |
| Client, tenant, health, identity, or other sensitive data | Isolation and sensitive data |
| Durable or shared memory | Memory promotion |
| Outbound, destructive, financial, account, or irreversible action | Consequential action |
| Concurrent writers or automated branching | Concurrency boundary |
| Persistent automation | Authority, concurrency, and evidence discipline |
| Multiple runtimes | Runtime bridge and cold tests |
| Completion or performance claim | Evidence discipline |
| Moving or renaming anything with outside consumers | Restructure and moves |

If none apply, do not add governance folders, ledgers, roles files, or evidence
machinery merely for completeness.

## Authority and synchronization

- Name the external system that owns each fact or action.
- State what may be mirrored into the ICM workspace, how freshness is checked,
  and where corrections must be made.
- Do not call Markdown the source of truth for data owned by a CRM, drive,
  database, calendar, repository, or service.
- Keep credentials and secret values outside agent-readable context.

## Isolation and sensitive data

- Keep reusable method separate from client-specific facts.
- Use real accounts, stores, permissions, credentials, or processes for
  isolation when risk requires it. A folder boundary or `access_tier` label is
  behavioral guidance, not access control.
- Default to synthetic or rights-cleared examples in reusable materials.
- Require an authorized review before client data can inform shared method.
- For cross-client work, declare the active client before retrieval and stop if
  the boundary cannot be demonstrated.

## Memory promotion

- Default to no automatic promotion from working context into durable or shared
  memory.
- Define allowed content, owner, provenance, approval, retention, correction,
  deletion, and client or role boundary before promotion.
- Do not promote secrets, unsupported inference, private source excerpts,
  another client's facts, or a declined suggestion.
- Give the declared authoritative source precedence over model memory.

## Consequential action

- Put the gate before the action, not after it.
- Name the human or platform authority, the artifact reviewed, and the exact
  approval required.
- Let the model propose language or classification; use deterministic tools for
  required fields, arithmetic, thresholds, and other objective checks.
- Never treat model confidence as authorization.

## Concurrency boundary

ICM's filesystem-as-state-machine model fits sequential, human-reviewed work.
Do not stretch it into high-concurrency or transactional operation.

- Use locks, queues, transactional stores, idempotency, or framework code when
  several writers can modify shared state.
- Use explicit orchestration when automated branching depends on model output.
- If those mechanisms become the real system, let ICM document and route to
  them rather than pretending folders provide their guarantees.

## Runtime bridge and cold tests

- Use the runtime's native root instruction file.
- Follow the target's established instruction chain. When both Codex and
  Claude are supported, choose one canonical router and make the other a
  minimal bridge. Never maintain
  two full copies of the same router.
- Do not assume arbitrary `CONTEXT.md` files auto-load; the root must route to
  them explicitly.
- Cold-test the same representative request on every claimed runtime.

## Evidence discipline

Use the minimum evidence appropriate to the claim:

- **Observed:** directly inspected or executed in the named environment.
- **Inference:** a reasoned conclusion from observed facts.
- **Unverified:** asserted by a source, template, or design but not observed.

A template is not a working system, a generated index is not proof of
freshness, and a file containing `PASS` is not independent evidence. For
important claims, record the action, environment, result, artifact, limitation,
and reviewer without retaining sensitive payloads.

## Restructure and moves

Before moving or renaming a folder or file that has existed for more than a
session, walk both directions:

- **Forward:** from the workspace root, a cold reader reaches the new location
  through files alone.
- **Reverse:** search for who points INTO the old path from outside the moved
  tree: scripts, schedulers, other workspaces, published links. Human readers
  complain; machine consumers break silently.

Record the search command and its scope next to the move, so the all-clear can
be re-run instead of remembered. A version of the reverse walk is proposed
upstream for Architect's walk test; this section is the advisory caution until
it lands there.

## Practical review additions

After applying upstream's walk test, ask only the triggered questions:

1. Is the authoritative source declared?
2. Is any claimed hard boundary only Markdown guidance?
3. Can working or client context enter durable or shared memory?
4. Does an irreversible action pause at a real authority?
5. Does concurrency exceed ICM's filesystem model?
6. Has each claimed runtime actually completed the route?
7. Is the completion claim supported by observed evidence?

Recommend the smallest fix. Do not turn this list into a mandatory governance
subsystem.
