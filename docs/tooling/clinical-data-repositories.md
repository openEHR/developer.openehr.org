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
| Status | Active - source available |
| Cost | Support Fee |
| Open source | Yes - for supporters |
| Platform | Java / ArcadeDB - Apache 2.0 licensed |
| Owner and developer | [ArcEHR project](https://arcehr.com), supported by [Medical](https://medical.si) |
| Available from | [ArcEHR](https://arcehr.com) |
| Source | [github.com/ArcadeEHR](https://github.com/ArcadeEHR) |

**What it is:** A source-available openEHR CDR developed on a Apache 2.0 graph database. It offers querying with AQL, SQL, Cypher, Gremlin, GraphQL.

**What it does:** It provides a standards-compliant openEHR server with REST API 1.1.0 support, an AQL query engine, template management, composition storage, and EHR management.

**Who should use it:** Developers or organisations building openEHR applications that want to have full control of their CDR with access to source code and royalty free license.

**Open source:** As the project matures, the plan is to transition ownership to a community-driven foundation, ensuring that ArcEHR remains open source and vendor-neutral for the long term.
