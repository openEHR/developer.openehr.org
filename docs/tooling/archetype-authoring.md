# Archetype Authoring Tools

These tools create and edit archetypes from scratch or modify existing ones.

## Archetype Designer

| | |
| --- | --- |
| Status | Current - actively recommended |
| Cost | Free to use as a hosted service |
| Owner and developer | [Better](https://www.better.care/about-us/) (formerly Marand) |
| Platform | Web-based (any browser) |
| ADL support | ADL 1.4 and ADL 2 (internal representation is ADL 2) |
| Available from | [tools.openehr.org/designer](https://tools.openehr.org/designer/) |

**What it is:** Better's browser-based archetype and template authoring tool, hosted by openEHR. It runs without local installation.

**What it does:** It creates and edits ADL 1.4 archetypes and templates with a graphical interface. It can generate operational templates and JSON web templates used by EHRbase and other platforms. It supports connections to GitHub repositories and the CKM, so you can work against real archetype libraries.

**Who should use it:** Anyone starting out with openEHR modelling today, including clinicians, informaticians, and developers.

**Naming note:** The web-based Archetype Designer should not be confused with the legacy Windows Archetype Editor below, which is sometimes loosely called "the archetype designer" in older documentation.

## ADL Workbench (AWB)

| | |
| --- | --- |
| Status | Specialist technical tooling |
| Cost | Free |
| Open source | Yes (Apache 2.0) |
| Owner | [openEHR](https://github.com/openEHR) |
| ADL support | ADL 1.4, ADL 2, BMMs |
| Available from | [GitHub releases](https://github.com/openEHR/adl-tools/releases) |
| Source | [github.com/openEHR/adl-tools](https://github.com/openEHR/adl-tools) |

**What it is:** A technical reference implementation and IDE for parsing, compiling, analysing, converting, and editing archetypes. It is built directly on the reference ADL parser, which makes it authoritative for validation.

**What it does:** It provides an IDE-style interface for technical archetype work, including syntax-level editing, validation against the reference model, ADL 1.4 to ADL 2 conversion, and BMM inspection.

**Who should use it:** Developers building openEHR tools, people working on the ADL specification, or those needing strict ADL 2 validation. It is not required for day-to-day clinical modelling.

## Archetype Editor (Ocean Informatics / Ocean Health Systems)

| | |
| --- | --- |
| Status | Legacy - still functional but no longer recommended for new work |
| Cost | Free |
| Open source | Yes (source on GitHub, archived) |
| Platform | Windows only |
| ADL support | ADL 1.4 only |
| Owner and developer | [Ocean Health Systems](https://oceanhealthsystems.com/about/) |
| Available from | [Ocean Archetype Editor](https://oceanhealthsystems.com/software/archetype-editor/) |
| Source | [github.com/openEHR/arch_ed-dotnet](https://github.com/openEHR/arch_ed-dotnet) |

**What it is:** Ocean Health Systems' Windows desktop tool for authoring ADL 1.4 archetypes.

**Why it is legacy:** It is Windows-only, supports ADL 1.4 only, and has been superseded by Archetype Designer for new work. Older training material may still reference it.

**Who might still use it:** Someone working through older training material or maintaining a Windows-only environment. Avoid it for new projects.

## Archetype Companion

| | |
| --- | --- |
| Status | Web-based companion tool |
| Cost | Free |
| Open source | Yes |
| Platform | Web-based |
| Author | [martinkochdesign](https://github.com/martinkochdesign) |
| Available from | [hosted application](https://martinkochdesign.github.io/archetype_companion/) |
| Source | [martinkochdesign/archetype_companion](https://github.com/martinkochdesign/archetype_companion) |

**What it is:** A lightweight companion tool for openEHR modellers. It is intended as a sidekick, not a replacement for Archetype Designer.

**What it does:** It focuses on mapping clinical data elements to archetypes. It helps modellers search and explore the archetype ecosystem before opening a full editor.

**Who should use it:** Anyone at the "what archetypes do I need?" stage of a project.

## LinkEHR Editor / LinkEHR Studio (Veratech)

| | |
| --- | --- |
| Status | Active |
| Cost | The editor in LinkEHR Studio is free; other platform modules are commercially licensed |
| Open source | No |
| Platform | Windows (desktop) |
| ADL support | ADL 1.4 archetypes, .oet templates, ADL 1.4 OPTs |
| Owner and developer | [VeraTech for Health](https://linkehr.veratech.es/about.html) |
| Available from | [LinkEHR Studio download](https://linkehr.veratech.es/getlinkehr.html) |

**What it is:** A multi-model archetype editor from the Valencian research group at Universitat Politecnica de Valencia, now commercialised through Veratech. It supports reference models including openEHR, ISO 13606, HL7 CDA, HL7 FHIR, and CDISC ODM.

**What LinkEHR Studio adds:** Data normalisation and mapping workflows, plus the LinkEHR Model Manager for publication and governance of clinical models.

**Who should use it:** Organisations needing to work across multiple standards or perform data transformation.
