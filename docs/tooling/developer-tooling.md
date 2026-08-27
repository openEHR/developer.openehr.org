# Developer Tooling

## VS Code Extension - ADL and AQL Support (Nedap)

| | |
| --- | --- |
| Status | Active |
| Cost | Free |
| Open source | Yes |
| Platform | Windows, Linux, macOS (via VS Code) |
| Owner and developer | [Nedap Healthcare](https://www.nedap.com/) |
| Available from | [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=NedapHealthcare.openehr-adl-lsp) |
| Source | [github.com/nedap/archetype-languageserver](https://github.com/nedap/archetype-languageserver) |

**What it is:** A VS Code extension that adds ADL 1.4 and ADL 2 syntax highlighting, validation, and AQL editing support.

**Who should use it:** Developers who use VS Code and want to edit archetypes or write AQL queries without switching to a browser-based tool.

## openEHR SDK

| | |
| --- | --- |
| Status | Active |
| Cost | Free (Apache 2.0) |
| Open source | Yes |
| Language | Java |
| Owner and steward | [EHRbase project](https://www.ehrbase.org/) |
| Available from | [GitHub releases](https://github.com/ehrbase/openEHR_SDK/releases) |
| Source | [github.com/ehrbase/openEHR_SDK](https://github.com/ehrbase/openEHR_SDK) |

**What it is:** A Java SDK for working with openEHR artefacts: parsing and serialising compositions, working with templates, and building AQL queries. EHRbase uses it internally.

## Archie

| | |
| --- | --- |
| Status | Active |
| Cost | Free (Apache 2.0) |
| Open source | Yes |
| Language | Java |
| Current owner | [openEHR](https://github.com/openEHR) |
| Original author | [Nedap](https://www.nedap.com/) |
| Available from | [github.com/openEHR/archie](https://github.com/openEHR/archie) |
| Source | [github.com/openEHR/archie](https://github.com/openEHR/archie) |

**What it is:** A Java library implementing the openEHR Reference Model and an ADL 2 parser. EHRbase uses it as its RM implementation.

## ADL2 Core Libraries

| | |
| --- | --- |
| Status | Source available; maintenance status unclear |
| Cost | Free |
| Open source | Yes |
| Language | Java |
| Current owner | [openEHR](https://github.com/openEHR) |
| Original author | Marand, now [Better](https://www.better.care/about-us/) |
| Available from | [github.com/openEHR/adl2-core](https://github.com/openEHR/adl2-core) |
| Source | [github.com/openEHR/adl2-core](https://github.com/openEHR/adl2-core) |

**What it is:** A Java-based reference implementation of the ADL 2.0 and AOM specifications, open-sourced by Marand.

## FHIR Bridge

| | |
| --- | --- |
| Status | Source available; release and support status unclear |
| Cost | Free (Apache 2.0) |
| Open source | Yes |
| Current owner | [vitagroup](https://www.vitagroup.ag/) |
| Original author | [EHRbase project](https://www.ehrbase.org/) |
| Available from | [github.com/vitagroupag/fhir-bridge](https://github.com/vitagroupag/fhir-bridge) |
| Source | [github.com/vitagroupag/fhir-bridge](https://github.com/vitagroupag/fhir-bridge) |

**What it is:** A broker between HL7 FHIR clients and an openEHR server, specifically EHRbase. It allows FHIR-speaking applications to read and write data to an openEHR CDR.

## openFHIR

| | |
| --- | --- |
| Status | Active |
| Cost | Free (open-source edition, Apache 2.0); commercial Enterprise edition |
| Open source | Yes (open-source edition) |
| Language | Java |
| Owner and developer | [openFHIR](https://open-fhir.com/) |
| Available from | [open-fhir.com](https://open-fhir.com/) |
| Source | [github.com/openFHIR/openfhir](https://github.com/openFHIR/openfhir) |

**What it is:** An engine that implements the FHIRConnect specification for bidirectional mapping between openEHR and HL7 FHIR. It sits alongside an openEHR repository and a FHIR server, translating data between the two. An open-source edition covers foundational mapping; a commercial Enterprise edition adds features such as multitenancy, terminology integration, and analytics.

**Who should use it:** Teams that need to exchange data between openEHR and FHIR systems using declarative, specification-based mappings rather than hand-coded brokers.
