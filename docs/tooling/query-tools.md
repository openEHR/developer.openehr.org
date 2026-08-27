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

## openEHR Explorer

| | |
| --- | --- |
| Status | Active |
| Cost | Free |
| Open source | Yes (Apache 2.0) |
| Platform | Windows, Linux, macOS (Tauri v2) |
| Owner and developer | [platzhersh](https://github.com/platzhersh) |
| Available from | [platzhersh.github.io/openehr-explorer](https://platzhersh.github.io/openehr-explorer/) |
| Source | [github.com/platzhersh/openehr-explorer](https://github.com/platzhersh/openehr-explorer) |

**What it is:** A cross-platform desktop app for browsing and querying openEHR CDR instances - built as "the Postman for openEHR." Server profiles, AQL queries, and environments are stored as files rather than a locked-in database, with secrets kept in the OS keychain. Targets EHRbase, with additional CDR support in progress.

**Who should use it:** Developers who want a dedicated GUI for exploring CDR contents and iterating on AQL queries, as an alternative to raw REST calls via Postman, Insomnia, or curl.
