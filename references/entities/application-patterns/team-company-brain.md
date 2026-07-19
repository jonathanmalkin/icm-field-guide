# Team or company brain

A team or company brain is a navigable map of who owns work, how processes move,
where authoritative data lives, and how teams hand work to one another. It
helps a person or agent answer questions such as “Who owns this?”, “What does
this process consume and produce?”, and “Where is the best pilot for
improvement?”

## Use it when

Use it when ownership, inputs, outputs, source systems, or cross-team
dependencies are difficult to trace. Its primary canonical form is a
[Context Map](https://github.com/RinDig/icm-architect/blob/e5313c308522ff9c4646a17b06fb1ddb0d844917/references/forms.md#5-context-map--the-organization-as-a-graph).
A team or domain may link to a
[Knowledge Bundle](https://github.com/RinDig/icm-architect/blob/e5313c308522ff9c4646a17b06fb1ddb0d844917/references/forms.md#4-knowledge-bundle--the-product-is-the-knowledge)
when it has deeper policies, concepts, or evidence, but that is optional.

## What it contains

Illustrative applied shape, not a canonical ICM template:

```text
company-brain/
├── AGENTS.md or CLAUDE.md    # small entry and task routing
├── _meta/                    # node schema and shared rules
├── teams/
│   └── marketing/
│       ├── team.md           # owner, purpose, inputs, outputs, edges
│       ├── processes/        # how work moves
│       ├── data/             # links to authoritative data assets
│       └── governance.md     # limits and human authority
├── patterns/                 # only repeated cross-team findings
└── dashboards/               # generated views over node metadata
```

The repeating unit is a team, process, data asset, governance rule, or
organizational handoff. Build it by observing or interviewing owners, creating
small typed nodes, connecting inputs and outputs, validating the map, and then
selecting one real pilot.

## Human and system boundary

Owners validate their nodes, shared governance, and proposed pilots. The brain
points to CRM, ERP, accounting, trackers, drives, and databases; it does not
copy or replace their live truth. Remove node types nobody queries and graph
layers that do not improve a decision.

## Examples and deeper reading

- [Team Graph summary](../project-examples/team-graph.md)
- [Tools and kits compendium](../../tools-and-kits.md)

Status: source-grounded starter.
