# Clinical Data Repositories

Clinical data repositories (CDRs) store patient data in openEHR format. They expose REST APIs and support AQL queries.

## EHRbase (vitagroup / Hannover Medical School)

| | |
| --- | --- |
| Status | Current - primary open-source CDR |
| Cost | Free (Apache 2.0) |
| Open source | Yes |
| Platform | Java / PostgreSQL - runs anywhere, Docker image available |
| Owner and steward | [EHRbase project](https://www.ehrbase.org/about-ehrbase/), supported by [vitagroup](https://www.vitagroup.ag/) |
| Available from | [EHRbase download](https://www.ehrbase.org/download/) |
| Source | [github.com/ehrbase/ehrbase](https://github.com/ehrbase/ehrbase) |
| Commercial support | Available through vitagroup (HIP EHRbase, HIP CDR) |
| Sandbox | [sandkiste.ehrbase.org](https://sandkiste.ehrbase.org/) - free public sandbox |

**What it is:** An open-source openEHR clinical data repository developed through the EHRbase project, vitagroup, Hannover Medical School, and HiGHmed.

**What it does:** It provides a standards-compliant openEHR server with REST API support, an AQL query engine, template management, composition storage, and EHR management.

**Who should use it:** Developers or organisations building openEHR applications that need a backend. The sandbox is a useful way to get started without a local installation.

## Better Platform (Better, formerly Marand)

| | |
| --- | --- |
| Status | Active - commercial |
| Cost | Commercial |
| Open source | No |
| Platform | Cloud / on-premise |
| Owner and developer | [Better](https://www.better.care/about-us/) |
| Available from | [Better Platform](https://www.better.care/better-platform/) |

**What it is:** A comprehensive commercial openEHR platform from Better. It includes a CDR, the EHR Studio toolset for AQL querying and composition management, and associated SDK tooling.

**Who should use it:** Enterprises and healthcare providers wanting a full-service openEHR platform with commercial support and enterprise features.

## EHRServer (Cabolabs)

| | |
| --- | --- |
| Status | Active |
| Cost | Free / open source |
| Open source | Yes |
| Platform | Grails / Java - self-hostable |
| Owner and developer | [CaboLabs](https://cabolabs.com/our_software/ehrserver) |
| Available from | [CaboLabs EHRServer](https://cabolabs.com/our_software/ehrserver) |
| Source | [github.com/ppazos/cabolabs-ehrserver](https://github.com/ppazos/cabolabs-ehrserver) |

**What it is:** An open-source, service-oriented openEHR CDR from Cabolabs. It provides a secure REST API supporting JSON and XML, with query capabilities.

**Who should use it:** Smaller projects and teams wanting a lighter-weight alternative to EHRbase, particularly in Latin America where Cabolabs is active.

## ArcEHR (Medical)

| | |
| --- | --- |
| Status | Private beta |
| Cost | Commercial co-development |
| Open source | No - a future Apache-2.0 release is planned |
| Platform | Java / ArcadeDB - self-hosted |
| Owner and developer | [Medical](https://medical.si) |
| Available from | [arcehr.com](https://arcehr.com) |
| Source | Not publicly available; production beta partners receive source access |

**What it is:** A private-beta openEHR CDR built on the ArcadeDB multi-model database. It supports AQL alongside SQL, Cypher, Gremlin, and GraphQL queries.

**What it does:** The project describes an openEHR Reference Model repository with REST API endpoints, template and composition storage, EHR management, and access through ArcadeDB's query languages and PostgreSQL wire protocol.

**Who should use it:** Organisations willing to join the private beta and co-develop a self-hosted CDR. It is not currently a publicly downloadable open-source option.

The project states that it intends to publish ArcEHR under Apache 2.0 and eventually transfer ownership to a community-driven foundation. These are future plans rather than the current licensing and governance model.

## FerroEHR

| | |
| --- | --- |
| Status | Active |
| Cost | Free for non-production use and for non-commercial production use; other production use needs a commercial licence |
| Open source | No - source-available under the Business Source License 1.1; each version becomes Apache-2.0 four years after its release |
| Platform | Rust / PostgreSQL 18 - binaries, containers, and a Helm chart are available |
| Owner and developer | [Cadasto B.V.](https://www.cadasto.com/) (licensor); developed by [Ruben Talstra](https://github.com/rubentalstra) |
| Available from | [ferroehr.eu](https://ferroehr.eu/) and [GitHub releases](https://github.com/FerroHEALTH/FerroEHR/releases/latest) |
| Source | [github.com/FerroHEALTH/FerroEHR](https://github.com/FerroHEALTH/FerroEHR) |
| Commercial support | Commercial licensing through [Cadasto B.V.](https://www.cadasto.com/contact/) |

**What it is:** A source-available openEHR CDR written in Rust and backed by PostgreSQL 18. Its openEHR model types and JSON and XML codecs are generated from the published machine-readable specifications. It is part of the FerroHEALTH family, in which separate servers handle FHIR and OMOP translation, federation, patient identity, and terminology.

**What it does:** It implements the openEHR REST API 1.1.0, AQL 1.1 with stored queries, ADL 1.4 and ADL 2.4 template management with validation on every write, full version history, demographics, and EHR Extract import and export. It offers a choice between the released and the development openEHR specification generations, and a web interface, the FerroEHR Viewer. The repository publishes machine-readable conformance records from runs of the independent Veredictum instrument.

**Who should use it:** Developers evaluating a self-hosted openEHR backend, particularly those who want to inspect the implementation and its published conformance evidence. Its licence terms and its single-maintainer status should be considered when assessing production use and support needs.
