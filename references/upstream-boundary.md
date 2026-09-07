# Upstream ICM Architect boundary

`icm-architect` is maintained by Jake Van Clief and is pinned upstream.

## Pin ownership

`../SKILL.md` is the **only** owner of the upstream pin identifier.
Other Field Guide files may link to the upstream project but must not repeat,
infer, or independently update those identifiers. A pin change is an upstream
maintenance operation: update that identifier in `../SKILL.md` only after the
authorized upstream review, then run the Field Guide checker. This keeps a
stale secondary record from masquerading as the pin.

## Maintenance rule

- Do not modify, reformat, rename, move, scaffold into, or add files under
  `../icm-architect/`.
- Do not rewrite its invariants, canonical forms, terminology, templates, or
  walk test in this extension.
- Put Jonathan-specific applications, examples, overlays, system archetypes,
  and operational guidance in `icm-field-guide/`.
- When an upstream change is needed, update the pinned upstream snapshot through
  its own authorized maintenance process; only then may the pin owner in
  `../SKILL.md` be updated. Do not patch upstream content from the Field Guide.

The Field Guide may link to and apply the pinned method. It must not silently
fork it.

Local source, evidence, and export checkpoints belong to `maintenance/field-guide-maintenance.md` in the maintained working checkout. Maintenance files are excluded from the public skill.
