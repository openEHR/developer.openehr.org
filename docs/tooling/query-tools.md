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

## FerroEHR admin console

| | |
| --- | --- |
| Status | Active |
| Cost | Free (MIT) |
| Open source | Yes |
| Owner and developer | [Ruben Talstra](https://github.com/rubentalstra) |
| Available from | [ghcr.io/rubentalstra/ferroehr-admin-ui](https://github.com/rubentalstra/FerroEHR/pkgs/container/ferroehr-admin-ui) - ships with the [FerroEHR quickstart](https://ferroehr.eu/docs/latest/getting-started.html) |
| Source | [github.com/rubentalstra/FerroEHR](https://github.com/rubentalstra/FerroEHR) |

**What it is:** The web console that ships with the FerroEHR CDR. Its query workbench has a raw AQL editor and a point-and-click query builder that generates the AQL for you: pick a template, add criteria (coded criteria can pick codes from a connected terminology server), choose columns and ordering, and run. Queries can be saved as stored parameterised queries, results render as a table or a chart, and result sets export to CSV and JSON.

**Who should use it:** Anyone running FerroEHR who wants to write or prototype AQL against their own data without leaving the browser. It talks to the server over the standard openEHR REST API, so the AQL it generates works against the same endpoints your application would call.
