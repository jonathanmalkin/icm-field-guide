# Cross-client operations

Cross-client operations reuse one sanitized method across separately controlled
client instances. The repeating unit is a client-local run, not a shared pool
of client data.

## Use it when

Use this pattern only when the same delivery method genuinely repeats and real
platform controls isolate clients. Structurally it is an
[Umbrella](https://github.com/RinDig/icm-architect/blob/e5313c308522ff9c4646a17b06fb1ddb0d844917/references/forms.md#2-umbrella--a-portfolio-of-pipelines)
over isolated instances, often following the
[Method factory and instances](../compositions/method-factory-instances.md)
composition.

## What it contains

- one sanitized method with no confidential or nonpublic client facts;
- an explicit active-client declaration;
- separately controlled client inputs, references, credentials, and outputs;
- a local delivery and approval path for each client;
- a separate proposal process for promoting sanitized learning back into the
  method.

The flow is: choose method → declare client boundary → run inside that boundary
→ review → deliver → separately consider a sanitized method improvement.

## Human and platform boundary

A person confirms the active client and authorizes delivery. Folder names,
frontmatter, and instructions are not access controls. Apply the
[authority boundary](../overlays/authority-system-boundary.md),
[deployment lifecycle](../overlays/deployment-lifecycle.md), and
[operational extensions](../../operational-extensions.md#isolation-and-sensitive-data).
Do not use this pattern if isolation cannot be demonstrated.

Remove the shared layer when it saves only minor duplication.

Status: experimental and high-risk.
