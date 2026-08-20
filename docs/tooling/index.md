# openEHR Tooling Guide

> Tooling changes frequently
>
> Always cross-check against [openEHR modelling tools](https://openehr.org/modelling-tools/) and the [openEHR Discourse forum](https://discourse.openehr.org/) for the latest status.

## Overview

openEHR has accumulated tools over more than twenty years. Some are still the recommended choice. Some are deprecated but still downloadable and occasionally referenced in older tutorials. Some are commercial products that sit on top of open foundations. This guide tries to be honest about all of them in one place.

Tools are grouped by purpose, because that is how most people approach this: they want to author archetypes, design templates, run a clinical data repository, or query it.

## Key Terms

### Archetypes

Archetypes are reusable clinical content models written in ADL (Archetype Definition Language). They define what clinical concepts mean and what data they hold, for example blood pressure or body weight. Archetypes are shared internationally through the [Clinical Knowledge Manager](https://ckm.openehr.org/ckm/) and are primarily clinically authored with clinician-friendly GUI tools.

### Templates

Templates assemble archetypes for a specific clinical use case, for example an emergency-department discharge summary. A template can be localised or use-case-specific. Templates are also authored using GUI tools and stored in a CKM.

### Operational Templates

Operational templates (OPTs) are the compiled, flattened output of a template. They are exported from a CKM and consumed by clinical data repositories and form renderers.

### Clinical Data Repositories

Clinical data repositories (CDRs) store patient data in openEHR format and expose REST APIs and AQL queries.

### ADL versions

ADL 1.4 is the current workhorse version and is universally supported. ADL 2 is the newer specification that unifies archetypes and templates into a single formalism. Support for ADL 2 is growing, but it is not yet universal.

Continue with [Archetype Authoring](archetype-authoring.md).
