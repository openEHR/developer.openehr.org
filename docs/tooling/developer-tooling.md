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
| Cost | Free (Apache 2.0) open-source edition; commercial Enterprise edition |
| Open source | Yes |
| Platform | Java / Docker |
| Owner and developer | [openFHIR](https://open-fhir.com/) |
| Available from | [GitHub releases](https://github.com/openFHIR/openFHIR/releases/latest) and [openFHIR sandbox](https://sandbox.open-fhir.com/) |
| Source | [github.com/openFHIR/openfhir](https://github.com/openFHIR/openfhir) |

**What it is:** An engine that implements the FHIR Connect specification for bidirectional mapping between openEHR compositions and HL7 FHIR resources. It translates data without storing the clinical data itself. The commercial Enterprise edition adds production capabilities including authentication, terminology integration, multitenancy, operational-template synchronization, and performance optimizations.

**Who should use it:** Teams evaluating declarative, specification-based mappings between openEHR and FHIR systems. The project explicitly states that its open-source edition is not intended for production use because it lacks authentication, role-based access control, terminology integration, and other production capabilities; production users should assess the Enterprise edition or provide equivalent controls themselves.
