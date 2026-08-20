# Template Authoring Tools

Templates assemble archetypes for specific clinical use cases. In ADL 2 the distinction blurs because a template is a specialised archetype, but in ADL 1.4 templates are separate artefacts with their own tooling.

## Archetype Designer (Better/Marand) - template mode

Archetype Designer handles both archetype and template authoring in a single tool. It is the recommended path for template work today.

## Template Designer (Ocean Informatics / Ocean Health Systems)

| | |
| --- | --- |
| Status | Legacy - use only for .oet format templates if required |
| Cost | Free |
| Open source | No |
| Platform | Windows only |
| ADL support | .oet templates only |
| Access | [Ocean Template Designer](http://downloads.oceaninformatics.com/downloads/TemplateDesigner/) |

**What it is:** The original template authoring tool from Ocean Informatics, now Ocean Health Systems, used alongside the Archetype Editor. It produces `.oet` files, the pre-ADL 2 template format, which are then compiled to OPTs.

**Why it is legacy:** It is Windows-only, produces the older `.oet` format, and has been superseded by Archetype Designer for new work. Many existing templates in CKM and UK national programmes were built with this tool.

**Who might still use it:** Anyone maintaining older `.oet` templates. Avoid it for new projects.

## Medical Flows Template Designer

| | |
| --- | --- |
| Status | Active - commercial |
| Cost | Commercial (pricing not publicly listed) |
| Open source | No |
| Platform | Web-based |
| Access | [medicalflows.com](https://medicalflows.com/) |

**What it is:** A commercial modelling tool for creating executable medical workflows with openEHR CDR support. It is not a replacement for Archetype Designer: it targets clinical pathways, guidelines, protocols, and task-planning workflows.

**Who should use it:** Organisations modelling and executing care processes and clinical decision logic, not only data structures.
