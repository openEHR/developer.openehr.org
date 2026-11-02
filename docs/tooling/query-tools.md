# Query Tools

AQL (Archetype Query Language) is the SQL equivalent for openEHR. Tooling for writing and testing AQL is thinner than for archetype authoring.

## EHRbase REST API

| | |
| --- | --- |
| Owner and developers | [EHRbase project](https://www.ehrbase.org/), [Vitasystems](https://www.vitagroup.ag/de_DE/Ueber-uns/vitasystems), and Peter L. Reichertz Institute |
| Available from | [EHRbase sandbox](https://sandkiste.ehrbase.org/) |

The most common way to run AQL queries against EHRbase is directly through the REST API, using tools such as Postman, Insomnia, or curl. The sandbox includes an API explorer.

## EHR Studio (Better)

| | |
| --- | --- |
| Status | Active - commercial |
| Cost | Commercial (part of Better Platform) |
| Owner and developer | [Better](https://www.better.care/about-us/) |
| Available from | [Better Studio registration](https://studio.better.care/registration) |

**What it is:** Better's integrated development environment for its openEHR platform, including an AQL Builder with a graphical query-construction interface. It is not available as a standalone free tool.

## openEHRTool (CRS4)

| | |
| --- | --- |
| Status | Active |
| Cost | Free (GPL-3.0) |
| Open source | Yes |
| Platform | Web application / Docker |
| Owner and developer | [CRS4](https://www.crs4.it/) |
| Available from | [github.com/crs4/openEHRTool-v2](https://github.com/crs4/openEHRTool-v2) |
| Source | [github.com/crs4/openEHRTool-v2](https://github.com/crs4/openEHRTool-v2) |

**What it is:** A web application for interacting with an EHRbase server. It provides interfaces for EHR, template, composition, query, and other openEHR REST API operations as a purpose-built alternative to a general API client.

## AQL Builder for EHRbase (CRS4)

| | |
| --- | --- |
| Status | Active |
| Cost | Free |
| Open source | Yes |
| Owner and developer | [CRS4](https://www.crs4.it/) |
| Available from | [github.com/crs4/aqlbetter](https://github.com/crs4/aqlbetter) |
| Source | [github.com/crs4/aqlbetter](https://github.com/crs4/aqlbetter) |

**What it is:** An adaptation of Better's open-source AQL Builder UI components, modified to work with EHRbase rather than Better Platform.

## AQL Manager

| | |
| --- | --- |
| Status | Active |
| Cost | Free (Apache 2.0) |
| Open source | Yes |
| Platform | Browser-based / offline-capable |
| Owner and developer | [Martin A. Koch, PhD](https://github.com/martinkochdesign/) (CatSalut) |
| Available from | [hosted application](https://martinkochdesign.github.io/openEHR_AQL_manager/) |
| Source | [github.com/martinkochdesign/openEHR_AQL_manager](https://github.com/martinkochdesign/openEHR_AQL_manager/) |

**What it is:** A client-side web application for organizing, editing, formatting, and searching collections of AQL queries. It stores working data in browser storage, imports and exports collections as JSON files, and can generate an EHRbase-compatible request payload.

**Who should use it:** Developers and analysts maintaining reusable AQL collections who want formatting and organization without connecting the tool to a CDR. It does not execute queries or validate them against a server.

## FerroEHR Viewer

| | |
| --- | --- |
| Status | Active |
| Cost | Free for non-production use and for non-commercial production use; other production use needs a commercial licence |
| Open source | No - source-available under the Business Source License 1.1 |
| Platform | Web application / Docker |
| Owner and developer | [Cadasto B.V.](https://www.cadasto.com/) (licensor); developed by [Ruben Talstra](https://github.com/rubentalstra) |
| Available from | [FerroEHR Viewer documentation](https://ferroehr.eu/docs/latest/viewer/index.html) |
| Source | [github.com/FerroHEALTH/FerroEHR](https://github.com/FerroHEALTH/FerroEHR) |

**What it is:** The web interface for FerroEHR, working over the same public REST API. Its query pages include an AQL editor and a query builder driven by a template, table and chart results, export, and stored queries saved to the CDR as versioned stored queries.

**Who should use it:** Developers running FerroEHR who want to write and test AQL against their own data in a browser.

## openEHR Explorer

| | |
| --- | --- |
| Status | Active |
| Cost | Free (Apache 2.0) |
| Open source | Yes |
| Platform | Desktop application for Windows, Linux, and macOS |
| Owner and developer | [platzhersh](https://github.com/platzhersh) |
| Available from | [GitHub releases](https://github.com/platzhersh/openehr-explorer/releases/latest) |
| Source | [github.com/platzhersh/openehr-explorer](https://github.com/platzhersh/openehr-explorer) |

**What it is:** A cross-platform desktop application for browsing openEHR EHRs, compositions, and templates. It includes an AQL editor with autocomplete, saved queries, tabular results, and CSV export, along with an inspector for the underlying REST requests.

**Who should use it:** Developers who want a dedicated graphical client for exploring CDR contents and iterating on AQL queries instead of using a general REST client.

## ehr-ctrl

| | |
| --- | --- |
| Status | Active |
| Cost | Free |
| Open source | No |
| Platform | Desktop application for Windows, Linux, and macOS |
| Owner and developer | [Richard Kavanagh](https://www.linkedin.com/in/richardkavanagh/) |
| Available from | [ehr-ctrl downloads](https://www.ehr-ctrl.info/downloads) |

**What it is:** A cross-platform desktop client for querying, inspecting, and administering openEHR CDRs through the REST API. Its documentation focuses on EHRbase and describes support for EHRs, compositions, templates, contributions, directories, and stored queries, with request and response diagnostics.

**What it does:** It includes an AQL editor with autocomplete, saved queries, CSV export, template management, and CRUD interfaces for supported CDR resources.

**Who should use it:** Developers and clinical IT teams that want a desktop interface for exploring or administering an EHRbase deployment or testing compatibility with another openEHR CDR.
