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

## FerroEHR admin console

| | |
| --- | --- |
| Status | Active |
| Cost | Free (MIT) |
| Open source | Yes |
| Platform | Web application / Docker |
| Owner and developer | [Ruben Talstra](https://github.com/rubentalstra) |
| Available from | [FerroEHR quick start](https://ferroehr.eu/docs/latest/getting-started.html) |
| Source | [github.com/rubentalstra/FerroEHR](https://github.com/rubentalstra/FerroEHR) |

**What it is:** The optional web administration console for FerroEHR. Its query workbench includes an AQL editor and a graphical query builder, saved parameterised queries, table and chart results, and CSV and JSON export.

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
