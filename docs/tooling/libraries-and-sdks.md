# Libraries & SDKs

Libraries and software development kits (SDKs) that developers embed in their own applications to work with openEHR artefacts, data, and APIs.

## oehrpy

| | |
| --- | --- |
| Status | Active - pre-1.0 |
| Cost | Free (Apache 2.0) |
| Open source | Yes |
| Language | Python |
| Owner and developer | [platzhersh](https://github.com/platzhersh) |
| Available from | [PyPI](https://pypi.org/project/oehrpy/) (`pip install oehrpy`) |
| Source | [github.com/platzhersh/oehrpy](https://github.com/platzhersh/oehrpy) |
| Documentation | [oehrpy.dev](https://oehrpy.dev/) |

**What it is:** A Python SDK for openEHR. It provides Pydantic models for Reference Model 1.1.0, template-specific composition builders, FLAT and canonical JSON serialisation, a fluent AQL builder, OPT parsing and validation, and asynchronous REST clients with EHRbase and FerroEHR adapters.

**Who should use it:** Python developers building applications, data pipelines, or scripts against an openEHR CDR who want typed RM objects and IDE autocomplete instead of hand-assembling composition JSON. Its documented adapters currently support EHRbase 2.26 and later and FerroEHR 4.3 and later, with a generic client for other ITS-REST 1.1.0 servers.

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
