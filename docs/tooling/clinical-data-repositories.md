# Clinical Data Repositories

Clinical data repositories (CDRs) store patient data in openEHR format. They expose REST APIs and support AQL queries.

## FerroEHR

| | |
| --- | --- |
| Status | Active |
| Cost | Free (MIT) |
| Open source | Yes |
| Platform | Rust / PostgreSQL 18 - single static binary, Docker images and a Helm chart |
| Owner and developer | [Ruben Talstra](https://github.com/rubentalstra) |
| Available from | [ferroehr.eu](https://ferroehr.eu/) and [GitHub releases](https://github.com/rubentalstra/FerroEHR/releases) |
| Source | [github.com/rubentalstra/FerroEHR](https://github.com/rubentalstra/FerroEHR) |
| Commercial support | None |

**What it is:** An MIT-licensed openEHR CDR written in Rust. The RM, BASE and AM types and the canonical JSON/XML codecs are generated from the published machine-readable specifications, and the server ships as one static binary on PostgreSQL 18.

**What it does:** It provides the openEHR REST API (ITS-REST 1.1.0) with canonical JSON and XML, an AQL 1.1 engine, template management in both ADL 1.4 and ADL 2, the simplified formats (WebTemplate, FLAT, STRUCTURED), EHR Extract, demographics, and a web admin console. The repository includes a conformance runner that executes a machine-readable test catalogue against the server; the run records are committed, so the published conformance and performance numbers can be checked against the artifacts that produced them.

**Who should use it:** Developers who want a small self-contained openEHR backend, and evaluators who want to check a CDR's conformance claims against committed test runs. It is a young project with a single maintainer, and its documentation states that support position plainly.

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
