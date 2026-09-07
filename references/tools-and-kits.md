# Tools and kits

Choose a tool or kit by the user's job, not by a product name. This page names
source material that may help; it is not a platform endorsement or an ICM
implementation guide.

**Evidence:** source inspected means the educational artifact was reviewed but
not independently operated; source-described means it was reported but not
verified; derived means Field Guide guidance. Source IDs are maintenance
provenance markers, not extra reading required for ordinary advice.
Platform behavior, pricing, permissions, and security are not current-product
claims here; re-observe them before a recommendation or deployment.

## Tool roles in one glance

| Tool role | What it does for the user | What it does not own |
|---|---|---|
| Chat or hosted project | keeps instructions and selected references together for repeated conversations | workflow state, permissions, or authoritative records |
| File-oriented agent | reads, drafts, edits, and tests files in an authorized workspace | business approval or external transaction truth |
| Retrieval or memory service | helps find relevant material across a larger corpus | deciding what is correct, current, or safe to retain |
| Automation or orchestrator | schedules steps, connects systems, and manages deterministic branching | expert judgment or permission to take consequential action |
| System of record | owns live customer, financial, operational, or account state | the reusable method or explanatory context around the work |
| Evaluation or security aid | collects evidence, runs checks, or exposes risk for review | a universal trust, quality, or compliance verdict |

ICM can organize the human-readable method and handoffs around these roles. It
does not replace their runtime, authorization, transaction, or security
guarantees.

## Decide the smallest mechanism

| User's job | What helps them do it | Aids and sources |
|---|---|---|
| Decide manual, prompt, ICM, code, or automation | make a reversible operating verdict and retain the necessary human gates | Workflow Audit (`CN-KIT-01`); 60/30/10 (`CN-MOD-01`); Tool Ladder (`CN-MOD-02`); Fragility Spectrum (`CN-MOD-04`) |
| Decide whether to productize expertise | distinguish a repeatable method from software that needs real operations | Effort-to-Output Ladder (`CN-MOD-03`); When to Build Software, Show Your Work, Productionize Your Opinion (`CN-PKG-01`, `CN-PKG-02`) |
| Diagnose expensive or unreliable model work | separate task scope, context, retries, and runtime effects | Context-cost diagnosis (`CN-COST-01`) |

These are decision lenses, not rules. Observed work and actual constraints win.
For human intake, use the one-page [Should this be ICM? mechanism chooser](decision-aids/should-this-be-icm.md).
For compact comparison cases, see [worked decisions](decision-aids/worked-decisions.md).

## Map or improve a human workflow

| User's job | What helps them do it | Kits and sources |
|---|---|---|
| Discover a real workflow before designing it | interview for owners, tools, risks, gates, and outputs | Custom-workflow questionnaire (`CN-KIT-08`) |
| See a compact routing/workspace example | compare a map, local work areas, and context delivery after form selection | Workspace Blueprint (`CN-KIT-03`); Folder Organization Guide (`CN-KIT-12`) |
| Map organization ownership and handoffs | surface teams, systems, sensitivities, and process edges | Team Graph Template (`CN-KIT-04`) |
| Reuse an established job shape | adapt content, client-management, or code-project teaching templates | Vault Toolkit and workflow template set (`CN-KIT-02`, `CN-KIT-05`) |
| Stay with a prompt instead of a workspace | preserve a reusable prompt when no durable workflow is needed | Prompt Library (`CN-KIT-09`) |

Templates are teaching surfaces. Once ICM is selected and an actual workspace
must be built or changed, use ICM Architect rather than copying a template.

## Produce and review a deliverable

| User's job | What helps them do it | References and sources |
|---|---|---|
| Turn creative intent into an approved production brief | make timing, visual constraints, and review points editable before production | Animation spec templates; Remotion; Illustrator and SVG input references (`CN-KIT-06`, `CN-WF-01`) |
| Set role-specific instructions | compare small root-instruction conventions without copying a whole workspace | Production instruction examples (`CN-KIT-07`) |
| Build and verify a site or project | preserve intent and findings while source code and deployed behavior remain authoritative | Astro, GitHub Pages, browser/Chrome workflow references (`CN-WF-02`, `CN-WF-03`, `CN-WF-05`) |
| Turn a session into a usable handoff | produce a decision map, decision record, reusable artifact, and explicit handoff | Session-to-artifact package (`CN-PKG-01`, `CN-PKG-02`) |

## Choose runtime or platform work deliberately

| User's job | What the referenced apps/tools can do | Boundary and sources |
|---|---|---|
| Keep project context in a hosted or file-oriented environment | provide a project surface or an agent runtime for file work | Claude Projects/Cowork/Code, Codex, Cursor are source-described runtime references; [cold-test the target environment](operational-extensions.md#runtime-bridge-and-cold-tests) (`CN-MOD-02`, `CN-MOD-05`, `FG-OPS-01`) |
| Find runtime-specific learning or implementation pointers | route to an existing manual or source-repository index before choosing a runtime | Claude Skills Manual and Claude repository index (`CN-KIT-10`, `CN-KIT-11`) |
| Run a persistent, remote, or multi-agent service | supply gateway, memory, hosting, remote access, or explicit automation components | Hermes, Cognee, DigitalOcean, Cloudflare Tunnel, n8n are source-described examples—not ICM requirements (`CN-STACK-01`, `CN-PKG-02`) |
| Host or evaluate models and prompts | provide serving, structured compliance data, programmatic optimization, or evaluation | Ollama, vLLM, OSCAL, DSPy, Promptfoo are implementation references; validate with current configuration (`CN-PKG-02`) |
| Triage a repository | provide lightweight housekeeping or deeper risk review prompts | repo-scorecard and repo-eval are source-described aids, [not security verdicts](entities/overlays/external-code-dependency-assurance.md) (`CN-SEC-01`) |

For automation, multi-agent coordination, credentials, consequential writes, or
deployment, read [operational overlays](entities/overlays/README.md) before
choosing infrastructure. The inspected material is too thin to expand
Moltbot/OpenClaw, “5 Levels of AI Mastery,” “Worldview Engineering,” or
“Computational Orchestration.”

## Workflow references

### Hermes-Cognee deployment

Source-described example of persistent remote operation: the named components
cover gateway, memory, hosting, and remote access; they do not supply
authentication, security, or an ICM requirement (`CN-STACK-01`).

### Claude Design workflow

Source-inspected course workflow for moving from design intent through an approved
specification to implementation and visual review. Re-observe the current
runtime and design tools (`CN-WF-04`).

### Claude Chrome workflow

Source-inspected browser-assisted project workflow. Browser state is transient, so
preserve findings in files and re-observe before relying on them (`CN-WF-05`).

### Session-to-artifact package

Source-inspected delivery pattern for turning intake and conversation into a decision
map, decision record, reusable artifact, and explicit handoff. It is not proof
that a recommended system was implemented (`CN-PKG-01`, `CN-PKG-02`).
