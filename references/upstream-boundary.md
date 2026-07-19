# Upstream ICM Architect boundary

`icm-architect` is a separately distributed skill maintained by Jake Van Clief
and pinned upstream.

## Maintenance rule

- Do not vendor, copy, submodule, modify, reformat, rename, move, scaffold into,
  or add ICM Architect files to this repository.
- Do not rewrite its invariants, canonical forms, terminology, templates, or
  walk test in this extension.
- Put Jonathan-specific applications, examples, overlays, system archetypes,
  and operational guidance in `icm-field-guide/`.
- When an upstream change is needed, update the pinned upstream snapshot through
  its own authorized maintenance process rather than patching it from the Field
  Guide.

The Field Guide may link to and apply the pinned method. It must not silently
fork it or imply joint maintenance.
