# Notices and third-party boundary

The MIT license in this directory applies to the original ICM Field Guide
extension authored by Jonathan Malkin.

## Canonical ICM method

The Field Guide applies and links to Jake Van Clief's separate ICM Architect
skill and the Interpretable Context Methodology. Those upstream materials retain
their own copyright, attribution, and MIT license. The Field Guide's license
does not replace or relicense them.

- Method paper by Jake Van Clief and David McDermott:
  [Interpretable Context Methodology: Folder Structure as Agentic
  Architecture](https://arxiv.org/abs/2603.16021)
- Canonical ICM Architect repository:
  [RinDig/icm-architect](https://github.com/RinDig/icm-architect)
- Public protocol repository:
  [RinDig/Interpreted-Context-Methdology](https://github.com/RinDig/Interpreted-Context-Methdology)
- The one authoritative upstream pin is maintained in `SKILL.md`. This notice
  deliberately does not repeat it; use the maintenance boundary before any
  authorized pin update.

The Field Guide is not a standalone implementation of ICM. An operational
installation requires the sibling ICM Architect at the pin owned by `SKILL.md`.
A distribution that omits that sibling must retain the published pinned fallback
link in `SKILL.md` and disclose the dependency; the export checker verifies its
official commit-to-tree mapping. If a distribution includes the sibling, include
its original `LICENSE` and attribution without modification.

## Educational and community sources

Names, ideas, examples, products, tools, and source claims discussed by the
Field Guide may originate in third-party educational or community material.
The source files, course text, transcripts, attachments, participant material,
trademarks, and other third-party content are not included in this license and
are not granted for redistribution by this repository.

Field Guide entries are short, evidence-labeled applications and paraphrases.
They must not be treated as endorsements, verified product claims, or
substitutes for the original sources. A locally captured toolkit or lesson is
available for internal study only; its presence here is not distribution
clearance and does not make it public material.

## Public distribution

Before publishing an export:

1. create a separate candidate containing only files on the explicit public
   export allowlist; the default allowlist is intentionally minimal;
2. run the Field Guide checker with the `export` profile and resolve every
   failure before review;
3. obtain a rights review for every non-upstream file or claim proposed for the
   candidate; internal capture, paraphrase, or source access is not approval;
4. include this notice and all applicable upstream license and attribution
   files;
5. keep source-described claims labeled as unverified unless independently
   checked; and
6. do not imply endorsement by Jake Van Clief, Eduba, Skool, Discord, or any
   named project or tool without permission.

This notice describes project scope and provenance. It is not legal advice.
