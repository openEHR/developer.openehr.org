# Template Authoring Tools

Templates assemble archetypes for specific clinical use cases. In ADL 2 the distinction blurs because a template is a specialised archetype, but in ADL 1.4 templates are separate artefacts with their own tooling.

## Archetype Designer - template mode

| | |
| --- | --- |
| Owner and developer | [Better](https://www.better.care/about-us/) |
| Available from | [tools.openehr.org/designer](https://tools.openehr.org/designer/) |

Archetype Designer handles both archetype and template authoring in a single tool. It is the recommended path for template work today.

## Template Designer (Ocean Informatics / Ocean Health Systems)

| | |
| --- | --- |
| Status | Legacy - use only for .oet format templates if required |
| Cost | Free |
| Open source | No |
| Platform | Windows only |
| ADL support | .oet templates only |
| Owner and developer | [Ocean Health Systems](https://oceanhealthsystems.com/about/) |
| Available from | [Ocean Template Designer](https://oceanhealthsystems.com/software/template-designer/) |

**What it is:** The original template authoring tool from Ocean Informatics, now Ocean Health Systems, used alongside the Archetype Editor. It produces `.oet` files, the pre-ADL 2 template format, which are then compiled to OPTs.

**Why it is legacy:** It is Windows-only, produces the older `.oet` format, and has been superseded by Archetype Designer for new work. Many existing templates in CKM and UK national programmes were built with this tool.

**Who might still use it:** Anyone maintaining older `.oet` templates. Avoid it for new projects.

## Archetype Inclusion Patterns

| | |
| --- | --- |
| Status | Active |
| Cost | Free (Apache 2.0) |
| Open source | Yes |
| Platform | Browser-based |
| Owner and developer | [Martin A. Koch, PhD](https://github.com/martinkochdesign/) (CatSalut) |
| Available from | [hosted visualization](https://martinkochdesign.github.io/openEHR_archetype_inclusion_patterns/) |
| Source | [github.com/martinkochdesign/openEHR_archetype_inclusion_patterns](https://github.com/martinkochdesign/openEHR_archetype_inclusion_patterns/) |

**What it is:** An interactive network visualization of archetype containment relationships extracted from operational templates in several international, national, and regional CKM mirrors. Relationships are aggregated across the sampled templates and classified by frequency.

**Who should use it:** Template modellers studying common archetype reuse and nesting patterns. It is an analysis and reference tool rather than a template editor, and its results reflect the source mirrors and generation date used for the published dataset.

## Medical Flows Template Designer

| | |
| --- | --- |
| Status | Web-based |
| Cost | Contact supplier |
| Open source | No |
| Platform | Web-based |
| Owner | [Medical Flows](https://medicalflows.com/) |
| Available from | [Medical Flows](https://medicalflows.com/) |

**What it is:** A modelling tool for creating executable medical workflows with openEHR CDR support. It is not a replacement for Archetype Designer: it targets clinical pathways, guidelines, protocols, and task-planning workflows.

**Who should use it:** Organisations modelling and executing care processes and clinical decision logic, not only data structures.
