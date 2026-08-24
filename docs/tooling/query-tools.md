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
| Cost | Free |
| Open source | Yes |
| Owner and developer | [CRS4](https://www.crs4.it/) |
| Available from | [github.com/crs4/openEHRTool-v2](https://github.com/crs4/openEHRTool-v2) |
| Source | [github.com/crs4/openEHRTool-v2](https://github.com/crs4/openEHRTool-v2) |

**What it is:** A web app to interact with an openEHR CDR API, instead of using Postman for instance, currently implemented for EHRBase.


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
