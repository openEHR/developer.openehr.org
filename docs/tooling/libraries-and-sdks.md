# Libraries & SDKs

Libraries and software development kits (SDKs) that developers embed in their own applications to work with openEHR artefacts, data, and APIs.

## oehrpy

| | |
| --- | --- |
| Status | Active (alpha) |
| Cost | Free (Apache 2.0) |
| Open source | Yes |
| Language | Python |
| Owner and developer | [platzhersh](https://github.com/platzhersh) |
| Available from | [PyPI](https://pypi.org/project/oehrpy/) (`pip install oehrpy`) |
| Source | [github.com/platzhersh/oehrpy](https://github.com/platzhersh/oehrpy) |
| Documentation | [oehrpy.dev](https://oehrpy.dev/) |

**What it is:** A Python SDK for openEHR. It provides Pydantic models for the Reference Model 1.1.0, template-specific composition builders, FLAT and canonical JSON serialisation, a fluent AQL builder, an OPT parser and validator, and an async REST client for EHRbase.

**Who should use it:** Python developers building applications, data pipelines, or scripts against an openEHR CDR who want typed RM objects and IDE autocomplete instead of hand-assembling composition JSON. Its REST client and FLAT format support currently target EHRbase 2.26 and later.
