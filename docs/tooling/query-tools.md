# Query Tools

AQL (Archetype Query Language) is the SQL equivalent for openEHR. Tooling for writing and testing AQL is thinner than for archetype authoring.

## EHRbase REST API

The most common way to run AQL queries against EHRbase is directly through the REST API, using tools such as Postman, Insomnia, or curl. The [EHRbase sandbox](https://sandkiste.ehrbase.org/) includes an API explorer.

## EHR Studio (Better)

| | |
| --- | --- |
| Status | Active - commercial |
| Cost | Commercial (part of Better Platform) |

**What it is:** Better's integrated development environment for its openEHR platform, including an AQL Builder with a graphical query-construction interface. It is not available as a standalone free tool.

## AQL Builder for EHRbase (CRS4)

| | |
| --- | --- |
| Status | Active |
| Cost | Free |
| Open source | Yes |
| Source | Available through CRS4 GitHub, derived from Better's open-source UI components |

**What it is:** An adaptation of Better's open-source AQL Builder UI components, modified to work with EHRbase rather than Better Platform.
