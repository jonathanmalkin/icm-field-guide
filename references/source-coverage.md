# Source coverage and provenance register

This register supports completeness, evidence labeling, and provenance. It
does not contain private paths, authenticated URLs, source excerpts, participant
details, or raw-content hashes. Detailed source-location mapping is intentionally
excluded from this distribution.

The register is a maintenance aid, not a second application catalog.

## Evidence states

- **Observed:** directly inspected in the reviewed source material or current
  workspace.
- **Source-described:** asserted or explained by a source but not independently
  operated or verified.
- **Derived:** Field Guide application guidance inferred from observed sources
  and canonical ICM.
- **Thin:** the source confirms a name or outline without enough detail to
  elaborate.
- **Unavailable:** a referenced primary source was not present.

## Source keys

| Source ID | Source class | Coverage | Evidence state | Distribution boundary |
|---|---|---|---|---|
| `UP-ICM-01` | Pinned upstream ICM Architect | Canonical invariants, forms, contracts, templates, and walk test | Observed | Preserve upstream MIT license and attribution; link rather than copy |
| `CN-SYN-01` | Clief Notes methodology synthesis | Definitions, application language, routing themes, and source caveats | Reviewed synthesis | Paraphrased application guidance only; source material excluded |
| `CN-SYN-02` | Clief Notes frameworks synthesis | Models, named examples, tools, thinness notes, and source claims | Reviewed synthesis | Do not republish excerpts or unverified figures |
| `CN-SYN-03` | Package toolkit synthesis | Operating kits, session packages, templates, and durable package patterns | Reviewed synthesis | Compact catalog descriptions only; source packages excluded |
| `CN-KIT-01` | Workflow Audit package | Automation verdict and risk-oriented workflow diagnosis | Captured | Underlying skill not included |
| `CN-KIT-02` | Vault Toolkit package | Constraints, three reference architectures, and skill starters | Captured | Underlying files not included |
| `CN-KIT-03` | Workspace Blueprint package | Context-delivery workspace example | Captured | Canonical architecture remains upstream |
| `CN-KIT-04` | Team Graph package | Organization nodes, links, governance, and intake | Captured | Underlying template not included |
| `CN-KIT-05`–`CN-KIT-12` | Vault production resources | Workflow templates, specs, instruction examples, questionnaire, prompt and reference guides | Captured | Catalog only; no attachment redistribution |
| `CN-PKG-01` | Vault session packages | Skills, workspace organization, effort-to-output, visible work, and method packaging | Captured | Compact summaries included; source packages excluded |
| `CN-PKG-02` | Drawing Room packages | Audits, decision maps, governance, tool references, deployment, and bespoke builds | Captured | Private/community and participant detail excluded |
| `CN-MOD-01`–`CN-MOD-05` | Source-described decision models | 60/30/10, Tool Ladder, Effort-to-Output, Fragility Spectrum, and runtime continuity | Source-described | Present as attributed lenses, not universal facts |
| `CN-WF-01`–`CN-WF-05` | Demonstrated workflow lessons | Animation, site build, browser, design, and transcription workflows | Observed in captured sources | Summaries only; assets and lesson text excluded |
| `CN-STACK-01` | Community stack documents | Hermes, Cognee, hosting, and remote-access example | Source-described | No deployment, security, or compatibility claim |
| `FG-OPS-01` | Field Guide operational derivation | Authority, privacy, memory, consequential action, concurrency, and runtime cautions | Derived | Original Field Guide material under MIT |
| `PUB-ETHICS-01` | Public Ethics Engine paper | Psychometric assessment pipeline | Observed public source | Cite the paper; do not infer current deployment state |
| `PUB-LEDGER-01` | Public Ledger site | Talent network and placement workflow | Observed public site | Do not imply verified production behavior |
| `PUB-SKILLOPT-01` | Public SkillOpt paper and Microsoft Research page | Controlled optimization of agent skill documents | Observed public source | Adjacent research reference; not an ICM implementation |

## Entity coverage

| Entity group | Entries covered | Primary source IDs | Coverage status |
|---|---|---|---|
| Application patterns | personal second brain; content production; creative artifact production; client delivery; business operations; audit/assessment/compliance; training/workforce enablement; acquisition/relationship flywheel; team/company brain; code/project build; research hub; method productization; cross-client operations | `UP-ICM-01`, `CN-SYN-01`, `CN-KIT-02`–`CN-KIT-04`, `CN-PKG-01`, `CN-PKG-02`, `FG-OPS-01` | Complete as applied patterns; some are derived compositions |
| System archetypes | CRM operations; ERP operations | `UP-ICM-01`, `CN-KIT-04`, `CN-KIT-05`, `FG-OPS-01` | CRM has a filesystem starter; ERP is explicitly derived with no captured implementation |
| Overlays | deployment lifecycle; automation verdict; portability layers; authority boundary; orchestration threshold | `CN-KIT-01`, `CN-MOD-01`–`CN-MOD-05`, `CN-PKG-02`, `FG-OPS-01` | Complete for observed triggers |
| Compositions | ingest to model; assessment case library; method factory and instances | `UP-ICM-01`, `CN-SYN-01`, `CN-PKG-01`, `CN-PKG-02` | Derived combinations, not new canonical forms |
| Project examples | animation; website build; filesystem client management; small-business operations; Team Graph; transcription; Ethics Engine; VigilOre; NLP Logix; Emerge; Training Funnel; EdubaWare; The Ledger; SkillOpt | `CN-SYN-02`, `CN-KIT-02`, `CN-KIT-04`, `CN-WF-01`–`CN-WF-05`, `CN-PKG-01`, `CN-PKG-02`, `PUB-ETHICS-01`, `PUB-LEDGER-01`, `PUB-SKILLOPT-01` | Complete for named examples previously selected; evidence status stays on each card |
| Tools and kits | twelve operating kits; eight decision tools; nineteen runtime, platform, and implementation references | `CN-SYN-02`, `CN-SYN-03`, `CN-KIT-01`–`CN-KIT-12`, `CN-PKG-01`, `CN-PKG-02`, `CN-STACK-01` | Cataloged; underlying third-party materials excluded |
| Added workflow examples | Hermes-Cognee; Claude Design; Claude Chrome; session-to-artifact package | `CN-STACK-01`, `CN-WF-04`, `CN-WF-05`, `CN-PKG-01`, `CN-PKG-02` | Covered as compact examples in the tools compendium |

## Unverified, thin, or unavailable material

Do not promote these into normal cards without new evidence:

| Item | State | Rule |
|---|---|---|
| Revenue, adoption, time-saving, security, and performance figures | Source-described | Exclude from reusable guidance unless independently verified |
| SkillOpt reported benchmark figures | Public paper | Cite the paper and label figures as reported results if used |
| EdubaWare capabilities | Product vision or roadmap | Do not describe as shipped behavior |
| Ledger production status and marketplace outcomes | Public site observed | Do not imply independent verification or production status |
| “5 Levels of AI Mastery” | Thin | Preserve the name only; do not invent the levels |
| “Worldview Engineering” | Thin | Preserve the name only; do not invent its framework |
| “Computational Orchestration” lesson | Thin | Do not attribute detail beyond captured supporting sources |
| Moltbot/OpenClaw as an ICM example | Insufficient | Use only as a layering or platform-risk illustration |
| Codex, Cursor, and multi-runtime compatibility | Unverified by upstream package | Require a representative cold test for every claimed runtime |

## Promotion rule

An item moves from this register into a dedicated card only when it improves
routing, quality, handoff, safety, or learning and either:

1. it is independently loaded in at least three real decisions;
2. more than one application pattern needs substantial detail from it;
3. its section exceeds roughly 200–250 lines; or
4. it carries a distinct authority or safety boundary.

Otherwise, keep it as one table row or anchored section.
