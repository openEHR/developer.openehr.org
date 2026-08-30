# Conformance

Conformance guidance is being developed for the openEHR Developer Guide.

For now, see the [Tooling](../tooling/index.md) section and the [openEHR specifications](https://specifications.openehr.org/).

## Conformance specifications

The official [openEHR Conformance Specifications (CNF) component](https://specifications.openehr.org/releases/CNF/development/) is a work in progress and has not published a stable release. Its development materials include a conformance guide, platform conformance test schedule, platform profiles, and certificate format. These materials describe the intended assessment structure, while the released specifications for each openEHR component remain the normative source for product behaviour.

## Veredictum

| | |
| --- | --- |
| Status | Active - pre-1.0 |
| Cost | Free (Apache 2.0) |
| Open source | Yes |
| Platform | Rust CLI / web console |
| Owner and developer | [Ruben Talstra](https://github.com/rubentalstra) |
| Available from | [veredictum.eu](https://veredictum.eu/) and [GitHub releases](https://github.com/rubentalstra/Veredictum/releases/latest) |
| Source | [github.com/rubentalstra/Veredictum](https://github.com/rubentalstra/Veredictum) |

**What it is:** An independent conformance-testing instrument for openEHR CDRs. It runs a machine-readable, specification-cited test catalogue against a CDR, records the exchanges, and derives verdicts from the recorded results. It supports testing the openEHR REST API and AQL, and can seal result bundles with a digest manifest and detached signature.

**How to interpret results:** A Veredictum report is evidence from a named version of an independent, pre-1.0 tool against a particular system and test run. Veredictum is not an openEHR Foundation product, and its reports are not official openEHR certification.
