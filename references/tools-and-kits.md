# Tools and kits compendium

Use this compendium when a decision benefits from a concrete kit, decision aid,
workflow example, or implementation reference. It is an application catalog,
not a replacement for canonical ICM Architect instructions and not a bundle of
the underlying third-party materials.

Load only the closest section. Evidence labels mean:

- **captured:** an artifact is present in the reviewed community source set;
- **source-described:** a source explains or claims the item, but this review
  did not independently operate it;
- **derived:** the Field Guide translates observed material into application
  guidance; and
- **thin:** the name or outline is present without enough evidence to elaborate.

Source IDs route to [source coverage](source-coverage.md). They deliberately
avoid private paths, authenticated URLs, and source excerpts.

## Contents

- [Operating kits and templates](#operating-kits-and-templates)
- [Decision tools](#decision-tools)
- [Implementation and platform references](#implementation-and-platform-references)
- [Applied workflow examples](#applied-workflow-examples)
- [Deliberately thin entries](#deliberately-thin-entries)

## Operating kits and templates

| Item | Job | Use it when | Evidence | Source |
|---|---|---|---|---|
| Workflow Audit | Decide manual, hybrid, deterministic, or agent-assisted operation before building | A proposed automation has unclear repetition, judgment, variability, or failure cost | Captured skill | `CN-KIT-01` |
| Vault Toolkit | Supply constraints, reference architectures, and diagnostic skill starters | A user needs examples for content, operations, or client delivery after fit is established | Captured toolkit | `CN-KIT-02` |
| Workspace Blueprint | Demonstrate context delivery through a small map, routing layer, and local work areas | A user needs a concrete workspace reference after choosing canonical form | Captured template | `CN-KIT-03` |
| Team Graph Template | Map teams, processes, owners, systems, sensitivity, and handoffs | Organizational relationships are harder to navigate than a linear pipeline | Captured template | `CN-KIT-04` |
| Workflow template set | Provide content, client-management, and code-project starting points | A matching recurring job has already been observed | Captured templates | `CN-KIT-05` |
| Animation spec templates | Turn creative intent, timing, visual constraints, and review points into an approved brief | Creative implementation needs a human-approved spec before production | Captured templates | `CN-KIT-06` |
| Production instruction examples | Show role-specific root-instruction conventions | Comparing instruction surfaces without copying a full workspace | Captured examples | `CN-KIT-07` |
| Custom-workflow questionnaire | Elicit the real work, owners, tools, constraints, risks, and desired outputs | A bespoke workspace needs structured discovery | Captured questionnaire | `CN-KIT-08` |
| Prompt Library | Preserve session-built strategy prompts as reusable aids | A prompt is sufficient and a workspace would be excessive | Captured collection | `CN-KIT-09` |
| Claude Skills Manual | Explain skill packaging and use on a specific runtime | Runtime-specific skill guidance is required | Captured reference | `CN-KIT-10` |
| Claude repository index | Route to source repositories and implementation references | A user needs a tool reference rather than an ICM pattern | Captured index | `CN-KIT-11` |
| Folder Organization Guide | Compare practical folder setups and common organization failures | A user needs examples after the repeating unit is known | Captured guide | `CN-KIT-12` |

Templates are teaching and adaptation surfaces. Do not copy one before the
repeating unit, human pauses, authoritative systems, and real deliverable are
known. Use ICM Architect for any actual build or restructure.

## Decision tools

| Decision aid | Question it answers | Output | Evidence | Source |
|---|---|---|---|---|
| Workflow Audit | Should this work remain manual, become hybrid, or be automated? | An operating verdict and required gates | Captured | `CN-KIT-01` |
| 60/30/10 | Is too much responsibility being placed on the model instead of deterministic infrastructure and routing? | A layer allocation hypothesis, not a required ratio | Source-described | `CN-MOD-01` |
| Tool Ladder | What is the lowest-complexity interface that can carry the work? | A choice among hosted chat/project, agent workspace, or custom interface | Source-described | `CN-MOD-02` |
| Effort-to-Output Ladder | Which work creates leverage beyond one-off effort? | A packaging or reuse decision | Source-described | `CN-MOD-03` |
| When to Build Software | Does the service need a product, software inside delivery, or no software yet? | Build, embed, or defer decision | Source-described | `CN-PKG-02` |
| Fragility Spectrum | Would the system survive a model or prompt replacement? | Thin wrapper, hybrid, or architected-system assessment | Source-described | `CN-MOD-04` |
| Show Your Work | Which reasoning and artifacts should become visible proof? | A selected proof artifact and publication gate | Source-described | `CN-PKG-01` |
| Productionize Your Opinion | Which expert decisions can be made explicit and repeatedly applied? | Candidate method rules and examples | Source-described | `CN-PKG-01` |

Treat these as lenses, not laws. When a decision aid conflicts with observed
work, the observed workflow wins.

## Implementation and platform references

These tools were mentioned or supplied as implementation references. Their
presence does not make them part of ICM and does not constitute a Field Guide
endorsement.

| Tool or surface | Source-described role | Field Guide boundary | Source |
|---|---|---|---|
| Claude Projects | Hosted project instructions and knowledge | Use when a saved prompt or hosted project is sufficient | `CN-MOD-02` |
| Claude Cowork | Hosted collaborative work surface | Verify current product behavior before recommending it | `CN-MOD-02` |
| Claude Code | File-oriented agent runtime | Runtime behavior and permissions remain platform concerns | `CN-MOD-02` |
| Codex | File-oriented agent runtime | Compatibility must be cold-tested rather than inferred | `FG-OPS-01` |
| Cursor | File-oriented development runtime | Compatibility is source-described, not verified here | `CN-MOD-05` |
| Hermes | Agent gateway in a persistent-stack example | Hosting, credentials, and access controls are outside ICM | `CN-STACK-01` |
| Cognee | Knowledge and memory service in a persistent-stack example | It is optional infrastructure, not an ICM requirement | `CN-STACK-01` |
| DigitalOcean | Hosting surface in the persistent-stack example | Deployment claims require current provider verification | `CN-STACK-01` |
| Cloudflare Tunnel | Remote-access layer in the persistent-stack example | Network security cannot be guaranteed by folders | `CN-STACK-01` |
| Remotion | Code-driven video and animation tool | The approved creative spec remains the ICM edit surface | `CN-WF-01` |
| Illustrator and SVG | Design-to-web animation inputs | Treat design files as source artifacts, not routing authority | `CN-WF-01` |
| Astro | Static-site implementation framework | Repository and deployed behavior remain authoritative | `CN-WF-02` |
| GitHub Pages | Static-site deployment target | Publication remains a consequential action | `CN-WF-02` |
| Browser and Chrome tooling | Interactive research, design, and testing surfaces | Browser state is external context and must be re-observed | `CN-WF-03` |
| Ollama and vLLM | Local or self-hosted model serving references | Model hosting is infrastructure outside ICM | `CN-PKG-02` |
| OSCAL | Compliance-data reference | Schemas and regulatory authority remain external | `CN-PKG-02` |
| DSPy | Programmatic model-optimization reference | Evaluation code, not folders, must establish performance | `CN-PKG-02` |
| Promptfoo | Prompt and model evaluation reference | Test results need observed evidence and current configuration | `CN-PKG-02` |
| n8n | Workflow-automation reference | Use explicit orchestration when automation owns branching | `CN-PKG-02` |

## Applied workflow examples

### Hermes-Cognee deployment

- **Pattern:** persistent and remote operation over a deployment Pipeline
- **Application:** provision infrastructure, deploy services, configure remote
  access, and pass reviewed outputs between stages.
- **Boundary:** the source describes the stack; this Field Guide did not deploy
  or security-test it. Hosting, authentication, memory, and networking are not
  supplied by ICM.
- **Evidence:** source-described community stack, `CN-STACK-01`.

### Claude Design workflow

- **Pattern:** creative artifact production
- **Application:** move from design intent and source material through an
  approved specification, implementation, and visual review.
- **Boundary:** runtime and design-tool behavior must be observed for the
  current environment.
- **Evidence:** demonstrated course workflow, `CN-WF-04`.

### Claude Chrome workflow

- **Pattern:** code or project build with browser-assisted observation
- **Application:** preserve task intent and findings in files while using the
  browser for current page state, interaction, and verification.
- **Boundary:** browser state is transient; files must not claim that a page or
  session remains unchanged.
- **Evidence:** demonstrated course workflow, `CN-WF-05`.

### Session-to-artifact package

- **Pattern:** facilitated client delivery
- **Application:** intake and conversation produce a decision map, decision
  record or term sheet, reusable artifact, and explicit handoff.
- **Boundary:** a decision map records the session; it is not proof that a
  recommended system was implemented. A source-described term sheet in this
  pattern is a vocabulary and decision artifact, not a legal contract.
- **Evidence:** captured Vault and Drawing Room packages, `CN-PKG-01` and
  `CN-PKG-02`.

## Deliberately thin entries

Moltbot/OpenClaw is retained only as a source-described illustration for
layering and platform-risk discussions. The captured material does not establish
it as an ICM implementation. The named “5 Levels of AI Mastery,” “Worldview
Engineering,” and “Computational Orchestration” sources are too thin to expand
without inventing missing detail. See [source coverage](source-coverage.md).
